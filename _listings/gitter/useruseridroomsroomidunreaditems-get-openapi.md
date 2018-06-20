---
swagger: "2.0"
x-collection-name: Gitter
x-complete: 0
info:
  title: Gitter API Get User Unread Items
  version: 1.0.0
  description: You can retrieve unread items and mentions using the following endpoint.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rooms/:roomId/chatMessages:
    get:
      summary: List Room Messages
      description: List of messages in a room.
      operationId: listRoomMessages
      x-api-path-slug: roomsroomidchatmessages-get
      parameters:
      - in: query
        name: afterId
        description: Get messages after afterId
        type: string
        format: string
      - in: query
        name: aroundId
        description: Get messages around aroundId including this message
        type: string
        format: string
      - in: query
        name: beforeId
        description: Get messages before beforeId
        type: string
        format: string
      - in: query
        name: limit
        description: Maximum number of messages to return (constrained to 100 or less)
        type: string
        format: string
      - in: query
        name: q
        description: Search query
        type: string
        format: string
      - in: query
        name: skip
        description: Skip n messages (constrained to 5000 or less)
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Rooms
      - Messages
    post:
      summary: Send Message
      description: Send a message to a room.
      operationId: sendMessage
      x-api-path-slug: roomsroomidchatmessages-post
      parameters:
      - in: query
        name: text
        description: Required Body of the message
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Rooms
      - Messages
  /rooms/:roomId/chatMessages/:messageId:
    get:
      summary: Get Room Message
      description: There is also a way to retrieve a single message using its id.
      operationId: getRoomMessage
      x-api-path-slug: roomsroomidchatmessagesmessageid-get
      responses:
        200:
          description: OK
      tags:
      - Rooms
      - Message
  /rooms/:roomId/chatMessages/:chatMessageId:
    put:
      summary: Update Message
      description: Update a message.
      operationId: updateMessage
      x-api-path-slug: roomsroomidchatmessageschatmessageid-put
      parameters:
      - in: query
        name: text
        description: Required Body of the message
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Rooms
      - Messages
  /user/:userId/rooms/:roomId/unreadItems:
    get:
      summary: Get User Unread Items
      description: You can retrieve unread items and mentions using the following
        endpoint.
      operationId: getUserUnreadItems
      x-api-path-slug: useruseridroomsroomidunreaditems-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Messages
      - Unread
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