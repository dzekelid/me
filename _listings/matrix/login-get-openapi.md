---
swagger: "2.0"
x-collection-name: Matrix
x-complete: 0
info:
  title: Matrix Login Operations API Get the login mechanism to use when logging in.
  version: 1.0.0
  description: All login stages MUST be mentioned if there is >1 login type.
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