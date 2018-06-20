---
swagger: "2.0"
x-collection-name: Google Partners
x-complete: 0
info:
  title: Google Partners API Get Generic Message Log
  description: |-
    Logs a generic message from the client, such as
    `Failed to render component`, `Profile page is running slow`,
    `More than 500 users have accessed this result.`, etc.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: partners.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/clientMessages:log:
    post:
      summary: Get Generic Message Log
      description: |-
        Logs a generic message from the client, such as
        `Failed to render component`, `Profile page is running slow`,
        `More than 500 users have accessed this result.`, etc.
      operationId: partners.clientMessages.log
      x-api-path-slug: v2clientmessageslog-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
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