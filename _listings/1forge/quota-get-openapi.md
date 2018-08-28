---
swagger: "2.0"
x-collection-name: 1Forge
x-complete: 0
info:
  title: 1Forge API Usage Quota API
  description: Returns the current quota for the API consumer.
  version: 1.0.0
host: forex.1forge.com
basePath: 1.0.3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /quota:
    get:
      summary: API Usage Quota API
      description: Returns the current quota for the API consumer.
      operationId: getQuota
      x-api-path-slug: quota-get
      parameters:
      - in: query
        name: api_key
        description: The api key
        type: string
        format: string
      - in: query
        name: format
        description: The format to return
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Management
      - Quota
      - Usage
x-streamrank:
  polling_total_time_average: "0.59"
  polling_size_download_average: "81.06"
  streaming_total_time_average: "0.4"
  streaming_size_download_average: "40.75"
  change_yes: "2"
  change_no: "187"
  time_percentage: "32"
  size_percentage: "50"
  change_percentage: "1"
  last_run: "2018-02-19"
  days_run: "0"
  minute_run: "0"
---