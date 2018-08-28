---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Currencies Get Real Time Forward Rate
  description: Returns a set of real-time currency forward rates.
  version: 1.0.0
host: www.xignite.com/xCurrencies.json
basePath: /XigniteCurrencies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ConvertRealTimeValue:
    get:
      summary: Convert Real Time Value
      description: Convert value from one currency to another in real-time.
      operationId: postConvertrealtimevalue
      x-api-path-slug: convertrealtimevalue-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Convert
      - Real
      - Time
      - Value
  /GetRealTimeForwardRate:
    get:
      summary: Get Real Time Forward Rate
      description: Returns a set of real-time currency forward rates.
      operationId: postGetrealtimeforwardrate
      x-api-path-slug: getrealtimeforwardrate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Real
      - Time
      - Forward
      - Rate
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