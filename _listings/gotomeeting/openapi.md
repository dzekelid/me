---
swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 1
info:
  title: SCIM
  description: the-scim-api-lets-you-manage-users-in-your-organization--you-can-then-automate-the-provisioning-of-product-licenses-for-these-users-and-they-can-use-your-companys-single-signon-solution-through-an-identity-provider-
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
    put:
      summary: Replace Current User
      description: Changes the current authenticated user's displayName, locale, timezone,
        username and password. The request must include the full user definition (to
        modify one or more values without sending the full definition, see Update
        User). The replaced user email domain must be an existing organization email
        domain.
      operationId: replaceMe
      x-api-path-slug: usersme-put
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
---