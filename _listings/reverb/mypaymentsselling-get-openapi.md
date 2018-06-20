---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: reverb Get My Payments Selling
  description: Get my payments selling.
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/conversations/{conversation_id}/messages:
    post:
      summary: Post My Conversations Conversation Messages
      description: Post my conversations conversation messages.
      operationId: postMyConversationsConversationMessages
      x-api-path-slug: myconversationsconversation-idmessages-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: conversation_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Conversations
      - Conversation
      - Id
      - Messages
  /my/orders/selling/awaiting_shipment:
    get:
      summary: Get My Orders Selling Awaiting Shipment
      description: Get seller orders awaiting shipment, newest first.
      operationId: getMyOrdersSellingAwaitingShipment
      x-api-path-slug: myorderssellingawaiting-shipment-get
      parameters:
      - in: query
        name: created_end_date
        description: Filter by date created in ISO8601 format - e
      - in: query
        name: created_start_date
        description: Filter by date created in ISO8601 format - e
      - in: query
        name: offset
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: updated_end_date
        description: Filter by date modified in ISO8601 format - e
      - in: query
        name: updated_start_date
        description: Filter by date modified in ISO8601 format - e
      responses:
        200:
          description: OK
      tags:
      - My
      - Orders
      - Selling
      - Awaiting
      - Shipment
  /my/payments/selling:
    get:
      summary: Get My Payments Selling
      description: Get my payments selling.
      operationId: getMyPaymentsSelling
      x-api-path-slug: mypaymentsselling-get
      parameters:
      - in: query
        name: created_end_date
        description: Filter by date created in ISO8601 format - e
      - in: query
        name: created_start_date
        description: Filter by date created in ISO8601 format - e
      - in: query
        name: offset
      - in: query
        name: order_id
        description: Look up payments by order id
      - in: query
        name: page
      - in: query
        name: per_page
      - in: query
        name: updated_end_date
        description: Filter by date modified in ISO8601 format - e
      - in: query
        name: updated_start_date
        description: Filter by date modified in ISO8601 format - e
      responses:
        200:
          description: OK
      tags:
      - My
      - Payments
      - Selling
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