---
swagger: "2.0"
x-collection-name: API Science
x-complete: 0
info:
  title: API Science Uptime Report
  version: 1.0.0
  description: Uptime Report
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /monitors/{id}/uptime.json:
    get:
      summary: Uptime Report
      description: Uptime Report
      operationId: uptimeReport
      x-api-path-slug: monitorsiduptime-json-get
      parameters:
      - in: query
        name: end
        description: The end point you want to build a performance report from
      - in: path
        name: id
        description: Id for the monitor
      - in: query
        name: preset
        description: Present for commonly requested reports
      - in: query
        name: resolution
        description: The resolution is the time unit for aggregating data, with allowable
          values of hourly, daily, and weekly
      - in: query
        name: start
        description: The start point you want to build a performance report from
      responses:
        200:
          description: OK
      tags:
      - Uptime
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