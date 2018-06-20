---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Get users by usernames
  x-api-slug: mattermost-api
  description: |-
    Get a list of users based on a provided list of usernames.
    ##### Permissions
    Requires an active session but no other permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/usernames
  tags: Users,By,Usernames
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersusernames-post-openapi.md
- name: Mattermost API Get a user by username
  x-api-slug: mattermost-api
  description: |-
    Get a user object by providing a username. Sensitive information will be sanitized out.
    ##### Permissions
    Requires an active session but no other permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/username/{username}
  tags: User,By,Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersusernameusername-get-openapi.md
- name: Mattermost API Switch login method
  x-api-slug: mattermost-api
  description: |-
    Switch a user's login method from using email to OAuth2/SAML/LDAP or back to email. When switching to OAuth2/SAML, account switching is not complete until the user follows the returned link and completes any steps on the OAuth2/SAML service provider.

    To switch from email to OAuth2/SAML, specify `current_service`, `new_service`, `email` and `password`.

    To switch from OAuth2/SAML to email, specify `current_service`, `new_service`, `email` and `new_password`.

    To switch from email to LDAP/AD, specify `current_service`, `new_service`, `email`, `password`, `ldap_ip` and `new_password` (this is the user's LDAP password).

    To switch from LDAP/AD to email, specify `current_service`, `new_service`, `ldap_ip`, `password` (this is the user's LDAP password), `email`  and `new_password`.

    Additionally, specify `mfa_code` when trying to switch an account on LDAP/AD or email that has MFA activated.

    ##### Permissions
    No current authentication required except when switching from OAuth2/SAML to email.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/login/switch
  tags: Switch,Login,Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersloginswitch-post-openapi.md
- name: Mattermost API Update a users authentication method
  x-api-slug: mattermost-api
  description: |-
    Updates a user's authentication method. This can be used to change them to/from LDAP authentication for example.

    __Minimum server version__: 4.6
    ##### Permissions
    Must have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/auth
  tags: Users,Authentication,Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersuser-idauth-put-openapi.md
- name: Mattermost API Get a team by name
  x-api-slug: mattermost-api
  description: |-
    Get a team based on provided name string
    ##### Permissions
    Must be authenticated, team type is open and have the `view_team` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/name/{name}
  tags: Team,By,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsnamename-get-openapi.md
- name: Mattermost API Get team members
  x-api-slug: mattermost-api
  description: |-
    Get a page team members list based on query string parameters - team id, page and per page.
    ##### Permissions
    Must be authenticated and have the `view_team` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/{team_id}/members
  tags: Team,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsteam-idmembers-get-openapi.md
- name: Mattermost API Get team members for a user
  x-api-slug: mattermost-api
  description: |-
    Get a list of team members for a user. Useful for getting the ids of teams the user is on and the roles they have in those teams.
    ##### Permissions
    Must be logged in as the user or have the `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/teams/members
  tags: Team,Membersa,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersuser-idteamsmembers-get-openapi.md
- name: Mattermost API Get a team member
  x-api-slug: mattermost-api
  description: |-
    Get a team member on the system.
    ##### Permissions
    Must be authenticated and have the `view_team` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/{team_id}/members/{user_id}
  tags: Team,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsteam-idmembersuser-id-get-openapi.md
- name: Mattermost API Get team members by ids
  x-api-slug: mattermost-api
  description: |-
    Get a list of team members based on a provided array of user ids.
    ##### Permissions
    Must have `view_team` permission for the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/{team_id}/members/ids
  tags: Team,Members,By,Ids
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsteam-idmembersids-post-openapi.md
- name: Mattermost API Update a team member roles
  x-api-slug: mattermost-api
  description: |-
    Update a team member roles. Valid team roles are "team_user", "team_admin" or both of them. Overwrites any previously assigned team roles.
    ##### Permissions
    Must be authenticated and have the `manage_team_roles` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/{team_id}/members/{user_id}/roles
  tags: Team,Member,Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsteam-idmembersuser-idroles-put-openapi.md
- name: Mattermost API Create a direct message channel
  x-api-slug: mattermost-api
  description: |-
    Create a new direct message channel between two users.
    ##### Permissions
    Must be one of the two users and have `create_direct_channel` permission. Having the `manage_system` permission voids the previous requirements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//channels/direct
  tags: Direct,Message,Channel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/channelsdirect-post-openapi.md
- name: Mattermost API Create a group message channel
  x-api-slug: mattermost-api
  description: |-
    Create a new group message channel to group of users. If the logged in user's id is not included in the list, it will be appended to the end.
    ##### Permissions
    Must have `create_group_channel` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//channels/group
  tags: Group,Message,Channel
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/channelsgroup-post-openapi.md
- name: Mattermost API Get a channel by name
  x-api-slug: mattermost-api
  description: |-
    Gets channel from the provided team id and channel name strings.
    ##### Permissions
    `read_channel` permission for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/{team_id}/channels/name/{channel_name}
  tags: Channel,By,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsteam-idchannelsnamechannel-name-get-openapi.md
- name: Mattermost API Get a channel by name and team name
  x-api-slug: mattermost-api
  description: |-
    Gets a channel from the provided team name and channel name strings.
    ##### Permissions
    `read_channel` permission for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//teams/name/{team_name}/channels/name/{channel_name}
  tags: Channel,By,Name,Team,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/teamsnameteam-namechannelsnamechannel-name-get-openapi.md
- name: Mattermost API Get channel members
  x-api-slug: mattermost-api
  description: |-
    Get a page of members for a channel.
    ##### Permissions
    `read_channel` permission for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//channels/{channel_id}/members
  tags: Channel,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/channelschannel-idmembers-get-openapi.md
- name: Mattermost API Get channel members by ids
  x-api-slug: mattermost-api
  description: |-
    Get a list of channel members based on the provided user ids.
    ##### Permissions
    Must have the `read_channel` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//channels/{channel_id}/members/ids
  tags: Channel,Members,By,Ids
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/channelschannel-idmembersids-post-openapi.md
- name: Mattermost API Get channel member
  x-api-slug: mattermost-api
  description: |-
    Get a channel member.
    ##### Permissions
    `read_channel` permission for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//channels/{channel_id}/members/{user_id}
  tags: Channel,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/channelschannel-idmembersuser-id-get-openapi.md
- name: Mattermost API Get channel members for user
  x-api-slug: mattermost-api
  description: |-
    Get all channel members on a team for a user.
    ##### Permissions
    Logged in as the user and `view_team` permission for the team. Having `manage_system` permission voids the previous requirements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/teams/{team_id}/channels/members
  tags: Channel,Membersuser
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersuser-idteamsteam-idchannelsmembers-get-openapi.md
- name: Mattermost API Get unread messages
  x-api-slug: mattermost-api
  description: |-
    Get the total unread messages and mentions for a channel for a user.
    ##### Permissions
    Must be logged in as user and have the `read_channel` permission, or have `edit_other_usrs` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/channels/{channel_id}/unread
  tags: Unread,Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/usersuser-idchannelschannel-idunread-get-openapi.md
- name: Mattermost API Create a ephemeral post
  x-api-slug: mattermost-api
  description: |-
    Create a new ephemeral post in a channel.
    ##### Permissions
    Must have `create_post_ephemeral` permission (currently only given to system admin)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//posts/ephemeral
  tags: Ephemeral,Post
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/postsephemeral-post-openapi.md
- name: Mattermost API Get metadata for a file
  x-api-slug: mattermost-api
  description: |-
    Gets a file's info.
    ##### Permissions
    Must have `read_channel` permission or be uploader of the file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//files/{file_id}/info
  tags: Metadataa,File
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/filesfile-idinfo-get-openapi.md
- name: Mattermost API Get configuration made through environment variables
  x-api-slug: mattermost-api
  description: |-
    Retrieve a json object mirroring the server configuration where fields are set to true
    if the corresponding config setting is set through an environment variable. Settings
    that haven't been set through environment variables will be missing from the object.

    __Minimum server version__: 4.10

    ##### Permissions
    Must have `manage_system` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//config/environment
  tags: Configuration,Made,Through,Environment,Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/configenvironment-get-openapi.md
- name: Mattermost API Add log message
  x-api-slug: mattermost-api
  description: |-
    Add log messages to the server logs.
    ##### Permissions
    Users with `manage_system` permission can log ERROR or DEBUG messages.
    Logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` or just DEBUG messages when `false`.
    Non-logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` and cannot log when `false`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//logs
  tags: Log,Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/logs-post-openapi.md
- name: Mattermost API Get a custom emoji by name
  x-api-slug: mattermost-api
  description: |-
    Get some metadata for a custom emoji using its name.
    ##### Permissions
    Must be authenticated.

    __Minimum server version__: 4.7
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//emoji/name/{emoji_name}
  tags: Custom,Emoji,By,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/emojinameemoji-name-get-openapi.md
- name: Mattermost API Get metadata
  x-api-slug: mattermost-api
  description: |-
    Get SAML metadata from the server. SAML must be configured properly.
    ##### Permissions
    No permission required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//saml/metadata
  tags: Metadata
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/samlmetadata-get-openapi.md
- name: Mattermost API Get a list of roles by name
  x-api-slug: mattermost-api
  description: |-
    Get a list of roles from their names.

    ##### Permissions
    Requires an active session but no other permissions.

    __Minimum server version__: 4.9
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//roles/names
  tags: List,Of,Roles,By,Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/rolesnames-post-openapi.md
- name: Mattermost API
  x-api-slug: mattermost-api
  description: Open source, private cloud Slack-alternative, Workplace messaging for
    web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
    configurable, and scalable from teams to the enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mattermost/openapi.md
x-common:
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---