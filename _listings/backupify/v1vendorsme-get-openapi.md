---
swagger: "2.0"
x-collection-name: Backupify
x-complete: 0
info:
  title: Backupify Provides information about the currently authenticated vendor user
  description: Provides information about the currently authenticated vendor user.
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/vendors/me:
    get:
      summary: Provides information about the currently authenticated vendor user
      description: Provides information about the currently authenticated vendor user.
      operationId: getV1VendorsMe
      x-api-path-slug: v1vendorsme-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      responses:
        200:
          description: OK
      tags:
      - V1
      - Vendors
      - Me
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