---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Get User User Messages Message Message Body
  description: Gets a message's body.
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
  /user/{user_id}/messages/unread:
    get:
      summary: Get User User Messages Unread
      description: Returns a list of unread message IDs and their URLs.
      operationId: user.user_id.messages.unread.get
      x-api-path-slug: useruser-idmessagesunread-get
      parameters:
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
      - Unread
    post:
      summary: Post User User Messages Unread
      description: Marks multiple messages as read at once. If a message has already
        been marked as read, it will be silently skipped.
      operationId: user.user_id.messages.unread.post
      x-api-path-slug: useruser-idmessagesunread-post
      parameters:
      - in: header
        name: Content-Type
        description: Content type
      - in: query
        name: Content-Type
        description: Content type
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
      - Unread
  /user/{user_id}/messages/message/{message_id}:
    get:
      summary: Get User User Messages Message Message
      description: Gets a message.
      operationId: user.user_id.messages.message.message_id.get
      x-api-path-slug: useruser-idmessagesmessagemessage-id-get
      parameters:
      - in: query
        name: message_id
        description: The message ID
      - in: path
        name: message_id
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
      - Message
      - Message
      - Id
    delete:
      summary: Delete User User Messages Message Message
      description: Deletes a message.
      operationId: user.user_id.messages.message.message_id.delete
      x-api-path-slug: useruser-idmessagesmessagemessage-id-delete
      parameters:
      - in: query
        name: message_id
        description: The message ID
      - in: path
        name: message_id
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
      - Message
      - Message
      - Id
  /user/{user_id}/messages/message/{message_id}/body:
    get:
      summary: Get User User Messages Message Message Body
      description: Gets a message's body.
      operationId: user.user_id.messages.message.message_id.body.get
      x-api-path-slug: useruser-idmessagesmessagemessage-idbody-get
      parameters:
      - in: query
        name: message_id
        description: The message ID
      - in: path
        name: message_id
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
      - Message
      - Message
      - Id
      - Body
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