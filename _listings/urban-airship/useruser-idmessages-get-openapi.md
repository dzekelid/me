---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Get User User Messages
  description: Returns a list of messages and some metadata about them. It will also
    include some metadata about the user.
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/messages:
    get:
      summary: Get User User Messages
      description: Returns a list of messages and some metadata about them. It will
        also include some metadata about the user.
      operationId: user.user_id.messages.get
      x-api-path-slug: useruser-idmessages-get
      parameters:
      - in: query
        name: full_list
        description: Get the full message included in this list (which might take
          a while to download)
      - in: query
        name: since
        description: Return only new items
      - in: query
        name: user_id
        description: The user ID
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - User
      - User
      - Id
      - Messages
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---