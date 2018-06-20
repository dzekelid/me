---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Add log message
  description: |-
    Add log messages to the server logs.
    ##### Permissions
    Users with `manage_system` permission can log ERROR or DEBUG messages.
    Logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` or just DEBUG messages when `false`.
    Non-logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` and cannot log when `false`.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/usernames:
    post:
      summary: Get users by usernames
      description: |-
        Get a list of users based on a provided list of usernames.
        ##### Permissions
        Requires an active session but no other permissions.
      operationId: get-a-list-of-users-based-on-a-provided-list-of-usernames-permissionsrequires-an-active-session-but-
      x-api-path-slug: usersusernames-post
      parameters:
      - in: body
        name: body
        description: List of usernames
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
      - By
      - Usernames
  /users/username/{username}:
    get:
      summary: Get a user by username
      description: |-
        Get a user object by providing a username. Sensitive information will be sanitized out.
        ##### Permissions
        Requires an active session but no other permissions.
      operationId: get-a-user-object-by-providing-a-username-sensitive-information-will-be-sanitized-out-permissionsreq
      x-api-path-slug: usersusernameusername-get
      parameters:
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - User
      - By
      - Username
  /users/login/switch:
    post:
      summary: Switch login method
      description: |-
        Switch a user's login method from using email to OAuth2/SAML/LDAP or back to email. When switching to OAuth2/SAML, account switching is not complete until the user follows the returned link and completes any steps on the OAuth2/SAML service provider.

        To switch from email to OAuth2/SAML, specify `current_service`, `new_service`, `email` and `password`.

        To switch from OAuth2/SAML to email, specify `current_service`, `new_service`, `email` and `new_password`.

        To switch from email to LDAP/AD, specify `current_service`, `new_service`, `email`, `password`, `ldap_ip` and `new_password` (this is the user's LDAP password).

        To switch from LDAP/AD to email, specify `current_service`, `new_service`, `ldap_ip`, `password` (this is the user's LDAP password), `email`  and `new_password`.

        Additionally, specify `mfa_code` when trying to switch an account on LDAP/AD or email that has MFA activated.

        ##### Permissions
        No current authentication required except when switching from OAuth2/SAML to email.
      operationId: switch-a-users-login-method-from-using-email-to-oauth2samlldap-or-back-to-email-when-switching-to-oa
      x-api-path-slug: usersloginswitch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Switch
      - Login
      - Method
  /users/{user_id}/auth:
    put:
      summary: Update a users authentication method
      description: |-
        Updates a user's authentication method. This can be used to change them to/from LDAP authentication for example.

        __Minimum server version__: 4.6
        ##### Permissions
        Must have the `edit_other_users` permission.
      operationId: updates-a-users-authentication-method-this-can-be-used-to-change-them-tofrom-ldap-authentication-for
      x-api-path-slug: usersuser-idauth-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Users
      - Authentication
      - Method
  /teams/name/{name}:
    get:
      summary: Get a team by name
      description: |-
        Get a team based on provided name string
        ##### Permissions
        Must be authenticated, team type is open and have the `view_team` permission.
      operationId: get-a-team-based-on-provided-name-string-permissionsmust-be-authenticated-team-type-is-open-and-have
      x-api-path-slug: teamsnamename-get
      parameters:
      - in: path
        name: name
        description: Team Name
      responses:
        200:
          description: OK
      tags:
      - Team
      - By
      - Name
  /teams/{team_id}/members:
    get:
      summary: Get team members
      description: |-
        Get a page team members list based on query string parameters - team id, page and per page.
        ##### Permissions
        Must be authenticated and have the `view_team` permission.
      operationId: get-a-page-team-members-list-based-on-query-string-parameters--team-id-page-and-per-page-permissions
      x-api-path-slug: teamsteam-idmembers-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of users per page
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Members
  /users/{user_id}/teams/members:
    get:
      summary: Get team members for a user
      description: |-
        Get a list of team members for a user. Useful for getting the ids of teams the user is on and the roles they have in those teams.
        ##### Permissions
        Must be logged in as the user or have the `edit_other_users` permission.
      operationId: get-a-list-of-team-members-for-a-user-useful-for-getting-the-ids-of-teams-the-user-is-on-and-the-rol
      x-api-path-slug: usersuser-idteamsmembers-get
      parameters:
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Membersa
      - User
  /teams/{team_id}/members/{user_id}:
    get:
      summary: Get a team member
      description: |-
        Get a team member on the system.
        ##### Permissions
        Must be authenticated and have the `view_team` permission.
      operationId: get-a-team-member-on-the-system-permissionsmust-be-authenticated-and-have-the-view-team-permission
      x-api-path-slug: teamsteam-idmembersuser-id-get
      parameters:
      - in: path
        name: team_id
        description: Team GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Member
  /teams/{team_id}/members/ids:
    post:
      summary: Get team members by ids
      description: |-
        Get a list of team members based on a provided array of user ids.
        ##### Permissions
        Must have `view_team` permission for the team.
      operationId: get-a-list-of-team-members-based-on-a-provided-array-of-user-ids-permissionsmust-have-view-team-perm
      x-api-path-slug: teamsteam-idmembersids-post
      parameters:
      - in: body
        name: body
        description: List of user ids
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Members
      - By
      - Ids
  /teams/{team_id}/members/{user_id}/roles:
    put:
      summary: Update a team member roles
      description: |-
        Update a team member roles. Valid team roles are "team_user", "team_admin" or both of them. Overwrites any previously assigned team roles.
        ##### Permissions
        Must be authenticated and have the `manage_team_roles` permission.
      operationId: update-a-team-member-roles-valid-team-roles-are-team-user-team-admin-or-both-of-them-overwrites-any-
      x-api-path-slug: teamsteam-idmembersuser-idroles-put
      parameters:
      - in: body
        name: body
        description: Space-delimited team roles to assign to the user
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: team_id
        description: Team GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Member
      - Roles
  /channels/direct:
    post:
      summary: Create a direct message channel
      description: |-
        Create a new direct message channel between two users.
        ##### Permissions
        Must be one of the two users and have `create_direct_channel` permission. Having the `manage_system` permission voids the previous requirements.
      operationId: create-a-new-direct-message-channel-between-two-users-permissionsmust-be-one-of-the-two-users-and-ha
      x-api-path-slug: channelsdirect-post
      parameters:
      - in: body
        name: body
        description: The two user ids to be in the direct message
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Direct
      - Message
      - Channel
  /channels/group:
    post:
      summary: Create a group message channel
      description: |-
        Create a new group message channel to group of users. If the logged in user's id is not included in the list, it will be appended to the end.
        ##### Permissions
        Must have `create_group_channel` permission.
      operationId: create-a-new-group-message-channel-to-group-of-users-if-the-logged-in-users-id-is-not-included-in-th
      x-api-path-slug: channelsgroup-post
      parameters:
      - in: body
        name: body
        description: User ids to be in the group message channel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Group
      - Message
      - Channel
  /teams/{team_id}/channels/name/{channel_name}:
    get:
      summary: Get a channel by name
      description: |-
        Gets channel from the provided team id and channel name strings.
        ##### Permissions
        `read_channel` permission for the channel.
      operationId: gets-channel-from-the-provided-team-id-and-channel-name-strings-permissionsread-channel-permission-f
      x-api-path-slug: teamsteam-idchannelsnamechannel-name-get
      parameters:
      - in: path
        name: channel_name
        description: Channel Name
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Channel
      - By
      - Name
  /teams/name/{team_name}/channels/name/{channel_name}:
    get:
      summary: Get a channel by name and team name
      description: |-
        Gets a channel from the provided team name and channel name strings.
        ##### Permissions
        `read_channel` permission for the channel.
      operationId: gets-a-channel-from-the-provided-team-name-and-channel-name-strings-permissionsread-channel-permissi
      x-api-path-slug: teamsnameteam-namechannelsnamechannel-name-get
      parameters:
      - in: path
        name: channel_name
        description: Channel Name
      - in: path
        name: team_name
        description: Team Name
      responses:
        200:
          description: OK
      tags:
      - Channel
      - By
      - Name
      - Team
      - Name
  /channels/{channel_id}/members:
    get:
      summary: Get channel members
      description: |-
        Get a page of members for a channel.
        ##### Permissions
        `read_channel` permission for the channel.
      operationId: get-a-page-of-members-for-a-channel-permissionsread-channel-permission-for-the-channel
      x-api-path-slug: channelschannel-idmembers-get
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of members per page
      responses:
        200:
          description: OK
      tags:
      - Channel
      - Members
  /channels/{channel_id}/members/ids:
    post:
      summary: Get channel members by ids
      description: |-
        Get a list of channel members based on the provided user ids.
        ##### Permissions
        Must have the `read_channel` permission.
      operationId: get-a-list-of-channel-members-based-on-the-provided-user-ids-permissionsmust-have-the-read-channel-p
      x-api-path-slug: channelschannel-idmembersids-post
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: body
        name: user_ids
        description: List of user ids
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Channel
      - Members
      - By
      - Ids
  /channels/{channel_id}/members/{user_id}:
    get:
      summary: Get channel member
      description: |-
        Get a channel member.
        ##### Permissions
        `read_channel` permission for the channel.
      operationId: get-a-channel-member-permissionsread-channel-permission-for-the-channel
      x-api-path-slug: channelschannel-idmembersuser-id-get
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Channel
      - Member
  /users/{user_id}/teams/{team_id}/channels/members:
    get:
      summary: Get channel members for user
      description: |-
        Get all channel members on a team for a user.
        ##### Permissions
        Logged in as the user and `view_team` permission for the team. Having `manage_system` permission voids the previous requirements.
      operationId: get-all-channel-members-on-a-team-for-a-user-permissionslogged-in-as-the-user-and-view-team-permissi
      x-api-path-slug: usersuser-idteamsteam-idchannelsmembers-get
      parameters:
      - in: path
        name: team_id
        description: Team GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Channel
      - Membersuser
  /users/{user_id}/channels/{channel_id}/unread:
    get:
      summary: Get unread messages
      description: |-
        Get the total unread messages and mentions for a channel for a user.
        ##### Permissions
        Must be logged in as user and have the `read_channel` permission, or have `edit_other_usrs` permission.
      operationId: get-the-total-unread-messages-and-mentions-for-a-channel-for-a-user-permissionsmust-be-logged-in-as-
      x-api-path-slug: usersuser-idchannelschannel-idunread-get
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Unread
      - Messages
  /posts/ephemeral:
    post:
      summary: Create a ephemeral post
      description: |-
        Create a new ephemeral post in a channel.
        ##### Permissions
        Must have `create_post_ephemeral` permission (currently only given to system admin)
      operationId: create-a-new-ephemeral-post-in-a-channel-permissionsmust-have-create-post-ephemeral-permission-curre
      x-api-path-slug: postsephemeral-post
      parameters:
      - in: body
        name: ephemeral_post
        description: Ephemeral Post object to send
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Ephemeral
      - Post
  /files/{file_id}/info:
    get:
      summary: Get metadata for a file
      description: |-
        Gets a file's info.
        ##### Permissions
        Must have `read_channel` permission or be uploader of the file.
      operationId: gets-a-files-info-permissionsmust-have-read-channel-permission-or-be-uploader-of-the-file
      x-api-path-slug: filesfile-idinfo-get
      parameters:
      - in: path
        name: file_id
        description: The ID of the file info to get
      responses:
        200:
          description: OK
      tags:
      - Metadataa
      - File
  /config/environment:
    get:
      summary: Get configuration made through environment variables
      description: |-
        Retrieve a json object mirroring the server configuration where fields are set to true
        if the corresponding config setting is set through an environment variable. Settings
        that haven't been set through environment variables will be missing from the object.

        __Minimum server version__: 4.10

        ##### Permissions
        Must have `manage_system` permission.
      operationId: retrieve-a-json-object-mirroring-the-server-configuration-where-fields-are-set-to-trueif-the-corresp
      x-api-path-slug: configenvironment-get
      responses:
        200:
          description: OK
      tags:
      - Configuration
      - Made
      - Through
      - Environment
      - Variables
  /logs:
    post:
      summary: Add log message
      description: |-
        Add log messages to the server logs.
        ##### Permissions
        Users with `manage_system` permission can log ERROR or DEBUG messages.
        Logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` or just DEBUG messages when `false`.
        Non-logged in users can log ERROR or DEBUG messages when `ServiceSettings.EnableDeveloper` is `true` and cannot log when `false`.
      operationId: add-log-messages-to-the-server-logs-permissionsusers-with-manage-system-permission-can-log-error-or-
      x-api-path-slug: logs-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Log
      - Message
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---