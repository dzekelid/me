---
swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Messages API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buckets/{bucketKey}/messages:
    delete:
      summary: Clear a bucket (remove all messages).
      description: Clear a bucket (remove all messages)..
      operationId: deleteBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-delete
      parameters:
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
    get:
      summary: Retrieve a list of messages in a bucket
      description: Retrieve a list of messages in a bucket.
      operationId: getBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-get
      parameters:
      - in: query
        name: before
        description: Only return messages before the given Unix timestamp
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      - in: query
        name: count
        description: Maxiumum number of messages to return
      - in: query
        name: since
        description: Only return messages after the given Unix timestamp
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
    post:
      summary: Create a message
      description: Create a message.
      operationId: postBucketsBucketkeyMessages
      x-api-path-slug: bucketsbucketkeymessages-post
      parameters:
      - in: body
        name: NewMessage
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
  /buckets/{bucketKey}/messages/{messageId}:
    get:
      summary: Retrieve the details for a single message.
      description: Retrieve the details for a single message..
      operationId: getBucketsBucketkeyMessagesMessage
      x-api-path-slug: bucketsbucketkeymessagesmessageid-get
      parameters:
      - in: path
        name: bucketKey
        description: Unique identifier for a bucket
      - in: query
        name: messageId
        description: The unique identifier for this message
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - BucketKey
      - Messages
      - MessageId
  '/messages?active={active}&amp;customerId={customerId} ':
    ' get ':
      summary: Messages?active={active}&amp;customerId={customerId}
      description: Gets a list of UI messages. UI messages are used for user notifications
        on announcements/information/warnings.
      operationId: getMessagesActiveActive&amp;customerCustomer
      x-api-path-slug: messagesactiveactiveampcustomeridcustomerid-get
      responses:
        200:
          description: OK
      tags:
      - Messages?active=active&amp;customerId=customerId
  '/messages ':
    ' post ':
      summary: Messages
      description: Creates an UI message.
      operationId: postMessages
      x-api-path-slug: messages-post
      responses:
        200:
          description: OK
      tags:
      - Messages
  '/messages/{id} ':
    ' get ':
      summary: Messages {id}
      description: Gets an existing UI message by Id.
      operationId: getMessages
      x-api-path-slug: messagesid-get
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Id
    ' put ':
      summary: Messages {id}
      description: Updates an existing UI message.
      operationId: putMessages
      x-api-path-slug: messagesid-put
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Id
    ' delete ':
      summary: Messages {id}
      description: Deletes an existing UI message.
      operationId: deleteMessages
      x-api-path-slug: messagesid-delete
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Id
---