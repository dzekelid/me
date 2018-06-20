---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get team members for a user
  description: |-
    Get a list of team members for a user. Useful for getting the ids of teams the user is on and the roles they have in those teams.
    ##### Permissions
    Must be logged in as the user or have the `edit_other_users` permission.
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