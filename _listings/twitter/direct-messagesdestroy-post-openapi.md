---
swagger: "2.0"
x-collection-name: Twitter
x-complete: 0
info:
  title: Twitter Remove Direct Message
  description: destroys direct messages specified in required ID
  version: "1.1"
host: api.twitter.com
basePath: /1.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /direct_messages/sent:
    get:
      summary: Get Sent Direct Messages
      description: return 20 most recent direct messages sent
      operationId: return-20-most-recent-direct-messages-sent
      x-api-path-slug: direct-messagessent-get
      parameters:
      - in: query
        name: count
      - in: query
        name: include_entities
      - in: query
        name: max_id
      - in: query
        name: page
      - in: query
        name: since_id
      responses:
        200:
          description: OK
      tags:
      - Social
      - Messages
  /direct_messages/show:
    get:
      summary: Show Direct Message
      description: returns a single direct message specified by an id
      operationId: returns-a-single-direct-message-specified-by-an-id
      x-api-path-slug: direct-messagesshow-get
      parameters:
      - in: query
        name: id
        description: ID of direct message
      responses:
        200:
          description: OK
      tags:
      - Social
      - Messages
  /direct_messages:
    get:
      summary: Get Direct Messages
      description: return 20 most recent direct messages sent to user
      operationId: return-20-most-recent-direct-messages-sent-to-user
      x-api-path-slug: direct-messages-get
      parameters:
      - in: query
        name: include_entities
        description: whether or not to include entities
      - in: query
        name: max_id
        description: returns results with an ID less than/equal to specified ID
      - in: query
        name: since_id
        description: return results with ID greater than specified
      - in: query
        name: skip_status
        description: whether or not to include status
      responses:
        200:
          description: OK
      tags:
      - Social
      - Messages
  /direct_messages/destroy:
    post:
      summary: Remove Direct Message
      description: destroys direct messages specified in required ID
      operationId: destroys-direct-messages-specified-in-required-id
      x-api-path-slug: direct-messagesdestroy-post
      parameters:
      - in: query
        name: id
        description: ID of direct message to delete
      - in: query
        name: include_entities
        description: whether or not to include entities
      responses:
        200:
          description: OK
      tags:
      - Social
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