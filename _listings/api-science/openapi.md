---
swagger: "2.0"
x-collection-name: API Science
x-complete: 1
info:
  title: API Science
  version: 1.0.0
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
---