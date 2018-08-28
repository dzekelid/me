---
swagger: "2.0"
x-collection-name: LoginRadius
x-complete: 1
info:
  title: Login Operations
  version: 1.0.0
host: /login
basePath: http://localhost:8008/_matrix/client/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /login:
    get:
      summary: Get the login mechanism to use when logging in.
      description: All login stages MUST be mentioned if there is >1 login type.
      operationId: get_login_info
      x-api-path-slug: login-get
      responses:
        200:
          description: OK
      tags:
      - Login
      - Mechanism
      - To
      - Use
      - When
      - Logging
      - In
---