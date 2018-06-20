---
swagger: "2.0"
x-collection-name: AWS Simple Queue Service
x-complete: 0
info:
  title: AWS Simple Queue Service API Delete Message
  version: 1.0.0
  description: Deletes the specified message from the specified queue.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ChangeMessageVisibility:
    get:
      summary: Change Message Visibility
      description: Changes the visibility timeout of a specified message in a queue
        to a new value.
      operationId: changeMessageVisibility
      x-api-path-slug: actionchangemessagevisibility-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose messages visibility is
          changed
        type: string
      - in: query
        name: ReceiptHandle
        description: The receipt handle associated with the message whose visibility
          timeout is changed
        type: string
      - in: query
        name: VisibilityTimeout
        description: The new value for the messages visibility timeout (in seconds)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message Visibility
  /?Action=ChangeMessageVisibilityBatch:
    get:
      summary: Change Message Visibility Batch
      description: Changes the visibility timeout of multiple messages.
      operationId: changeMessageVisibilityBatch
      x-api-path-slug: actionchangemessagevisibilitybatch-get
      parameters:
      - in: query
        name: ChangeMessageVisibilityBatchRequestEntry.N
        description: A list of receipt handles of the messages for which the visibility
          timeout must be changed
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose messages visibility is
          changed
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message Visibility
  /?Action=DeleteMessage:
    get:
      summary: Delete Message
      description: Deletes the specified message from the specified queue.
      operationId: deleteMessage
      x-api-path-slug: actiondeletemessage-get
      parameters:
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue from which messages are deleted
        type: string
      - in: query
        name: ReceiptHandle
        description: The receipt handle associated with the message to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Messages
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