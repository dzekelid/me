swagger: "2.0"
x-collection-name: Box
x-complete: 1
info:
  title: Box
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/me:
    get:
      summary: Get Current User
      description: Retrieves information about the user who is currently logged in
        i.e. the user for whom this auth token was generated.
      operationId: getCurrentUser
      x-api-path-slug: usersme-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Users
      - Me