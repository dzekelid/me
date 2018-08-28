---
swagger: "2.0"
x-collection-name: Datadog
x-complete: 0
info:
  title: DataDog API Put Downtime Downtime
  version: 1.0.0
  description: Update monitor downtime
basePath: api/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metrics:
    get:
      summary: Get Metrics
      description: Get the list of actively reporting metrics from a given time until
        now. This endpoint is not available in the Python and Ruby libraries.
      operationId: getMetrics
      x-api-path-slug: metrics-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Metrics
  /downtime:
    post:
      summary: Add Downtime
      description: Schedule monitor downtime
      operationId: postDowntime
      x-api-path-slug: downtime-post
      parameters:
      - in: query
        name: period
        description: how often to repeat as an integer
        type: string
      - in: query
        name: type
        description: the type of recurrence
        type: string
      - in: query
        name: until_date
        description: (optional) the date at which the recurrence should end as a POSIX
          timestmap
        type: string
      - in: query
        name: until_occurrences
        description: (optional) how many times the downtime will be rescheduled
        type: string
      - in: query
        name: week_days
        description: (optional) a list of week days to repeat on
        type: string
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
  /downtime/:downtime_id:
    put:
      summary: Put Downtime Downtime
      description: Update monitor downtime
      operationId: putDowntimeDowntime
      x-api-path-slug: downtimedowntime-id-put
      parameters:
      - in: query
        name: period
        description: how often to repeat as an integer
        type: string
      - in: query
        name: type
        description: the type of recurrence
        type: string
      - in: query
        name: until_date
        description: (optional) the date at which the recurrence should end as a POSIX
          timestmap
        type: string
      - in: query
        name: until_occurrences
        description: (optional) how many times the downtime will be rescheduled
        type: string
      - in: query
        name: week_days
        description: (optional) a list of week days to repeat on
        type: string
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
      - Downtime
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