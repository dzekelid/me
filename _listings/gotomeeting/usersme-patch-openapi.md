---
swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 0
info:
  title: SCIM Update Current User
  description: Changes a limited set (or all if you choose) of the current authenticated
    user's data. The updated user email domain must be an existing organization email
    domain.
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: N/A
host: api.citrixonline.com
basePath: /identity/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Users/me:
    get:
      summary: Get Current User
      description: Queries the identity of the current authenticated user.
      operationId: getMe
      x-api-path-slug: usersme-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Me
    patch:
      summary: Update Current User
      description: Changes a limited set (or all if you choose) of the current authenticated
        user's data. The updated user email domain must be an existing organization
        email domain.
      operationId: updateMe
      x-api-path-slug: usersme-patch
      parameters:
      - in: body
        name: body
        description: The new user data
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Me
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