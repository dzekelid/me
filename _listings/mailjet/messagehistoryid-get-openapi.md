---
swagger: "2.0"
x-collection-name: Mailjet
x-complete: 0
info:
  title: Mailjet Messages API Message History
  description: Get the history of a message.
  version: v3
host: api.mailjet.com
basePath: v3/REST/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  message/:
    get:
      summary: Message List
      description: Allows you to list messages.
      operationId: getMessage
      x-api-path-slug: message-get
      parameters:
      - in: query
        name: Campaign
        description: Only retrieve message resources for which Campaign ID equals
          the specified value
      - in: query
        name: Contact
        description: Only retrieve message resources for which Contact ID equals the
          specified value
      - in: query
        name: MessageState
        description: Only show messages with this state
      - in: query
        name: PlanSubscription
        description: Only retrieve message resources for which PlanSubscription ID
          equals the specified value
      - in: query
        name: Sender
        description: Only show messages from this sender
      responses:
        200:
          description: OK
      tags:
      - Message
      - List
  messagehistory/:
    get:
      summary: Message History
      description: List message history resources
      operationId: getMessagehistory
      x-api-path-slug: messagehistory-get
      parameters:
      - in: path
        name: Message
        description: ID of message for which to show the history
      responses:
        200:
          description: OK
      tags:
      - Message
      - History
  messagehistory/{id}:
    get:
      summary: Message History
      description: Get the history of a message.
      operationId: getMessagehistory
      x-api-path-slug: messagehistoryid-get
      parameters:
      - in: path
        name: id
        description: ID of the message history
      responses:
        200:
          description: OK
      tags:
      - Message
      - History
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