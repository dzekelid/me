---
swagger: "2.0"
x-collection-name: Runscope
x-complete: 0
info:
  title: Runscope Add Buckets Tests Environments
  description: Create new test environment.
  version: 1.0.0
host: api.runscope.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buckets/{bucketKey}/environments:
    get:
      summary: Get Buckets Environments
      description: Returns list of shared environments for a specified bucket.
      operationId: buckets.bucketKey.environments.get
      x-api-path-slug: bucketsbucketkeyenvironments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Environments
    post:
      summary: Add Buckets Environments
      description: Create new shared environment.
      operationId: buckets.bucketKey.environments.post
      x-api-path-slug: bucketsbucketkeyenvironments-post
      parameters:
      - in: body
        name: NewEnvironment
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Environments
  /buckets/{bucketKey}/environments/{environmentId}:
    put:
      summary: Put Buckets Environments
      description: Update the details of a shared environment.
      operationId: buckets.bucketKey.environments.environmentId.put
      x-api-path-slug: bucketsbucketkeyenvironmentsenvironmentid-put
      parameters:
      - in: body
        name: ModifiedEnvironment
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Environments
  /buckets/{bucketKey}/messages:
    delete:
      summary: Delete Buckets Messages
      description: Clear a bucket (remove all messages).
      operationId: buckets.bucketKey.messages.delete
      x-api-path-slug: bucketsbucketkeymessages-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
    get:
      summary: Get Buckets Messages
      description: Retrieve a list of messages in a bucket
      operationId: buckets.bucketKey.messages.get
      x-api-path-slug: bucketsbucketkeymessages-get
      parameters:
      - in: query
        name: before
        description: Only return messages before the given Unix timestamp
      - in: query
        name: count
        description: Maxiumum number of messages to return
      - in: query
        name: No Name
      - in: query
        name: since
        description: Only return messages after the given Unix timestamp
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
    post:
      summary: Add Buckets Messages
      description: Create a message
      operationId: buckets.bucketKey.messages.post
      x-api-path-slug: bucketsbucketkeymessages-post
      parameters:
      - in: body
        name: NewMessage
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
  /buckets/{bucketKey}/messages/{messageId}:
    get:
      summary: Get Buckets Messages Message
      description: Retrieve the details for a single message.
      operationId: buckets.bucketKey.messages.messageId.get
      x-api-path-slug: bucketsbucketkeymessagesmessageid-get
      parameters:
      - in: path
        name: messageId
        description: The unique identifier for this message
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Messages
      - Message
  /buckets/{bucketKey}/tests/{testId}/environments:
    get:
      summary: Get Buckets Tests Environments
      description: Return details of the test's environments (only those that belong
        to the specified test)
      operationId: buckets.bucketKey.tests.testId.environments.get
      x-api-path-slug: bucketsbucketkeyteststestidenvironments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Environments
    post:
      summary: Add Buckets Tests Environments
      description: Create new test environment.
      operationId: buckets.bucketKey.tests.testId.environments.post
      x-api-path-slug: bucketsbucketkeyteststestidenvironments-post
      parameters:
      - in: body
        name: NewEnvironment
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Buckets
      - Tests
      - Environments
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