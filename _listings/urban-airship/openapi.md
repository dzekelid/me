---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
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
  /user/{user_id}/messages/message/{message_id}/read:
    post:
      summary: Post User User Messages Message Message Read
      description: Marks a message as read.
      operationId: user.user_id.messages.message.message_id.read.post
      x-api-path-slug: useruser-idmessagesmessagemessage-idread-post
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
      - Read
  /user/{user_id}/messages/delete:
    post:
      summary: Post User User Messages Delete
      description: Deletes multiple messages at once. If a message has already been
        deleted, it will be silently skipped.
      operationId: user.user_id.messages.delete.post
      x-api-path-slug: useruser-idmessagesdelete-post
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
      - Delete
---