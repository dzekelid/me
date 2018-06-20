---
swagger: "2.0"
x-collection-name: Open FinTech
x-complete: 0
info:
  title: Open FinTech Merchant industry by ID
  description: Returns merchant industry with specific ID.
  version: "2017-08-24"
host: api.openfintech.io
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /merchant-industries:
    get:
      summary: List of merchant industries
      description: Returns all available merchant fields of activity.
      operationId: merchant_industries.get
      x-api-path-slug: merchantindustries-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Merchant-industries
  /merchant-industries/{id}:
    get:
      summary: Merchant industry by ID
      description: Returns merchant industry with specific ID.
      operationId: merchant_industries.id.get
      x-api-path-slug: merchantindustriesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Merchant-industries
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