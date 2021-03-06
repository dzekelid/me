---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 0
info:
  title: BMC Software API Available metrics
  version: 1.0.0
  description: Determine which metrics are available to return historical data for,
    for a specific subject (device or service) over a specific time range.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/mobile-devices/:userDeviceId:
    delete:
      summary: Delete Mobile Device
      description: Deletes a device from a user
      operationId: delete-mobile-device
      x-api-path-slug: v1mobiledevicesuserdeviceid-delete
      parameters:
      - in: query
        name: |-
          userDeviceId
          The user device ID to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /v1/meter/:meterName/registration:
    post:
      summary: Registration
      description: Register a Meter with TrueSight Pulse
      operationId: registration
      x-api-path-slug: v1metermeternameregistration-post
      parameters:
      - in: formData
        name: meterVersion
        description: What version of the Meter is running, ex
        type: string
      responses:
        200:
          description: OK
      tags:
      - Meters
  /v1/measurements:
    post:
      summary: Add measures
      description: Adds measurement readings to the data store.
      operationId: add-measures
      x-api-path-slug: v1measurements-post
      parameters:
      - in: formData
        name: source
        description: The source of the metric
        type: string
      responses:
        200:
          description: OK
      tags:
      - Measurements
  /v1/metrics:
    post:
      summary: Create metric
      description: Creates a new metric
      operationId: create-metric
      x-api-path-slug: v1metrics-post
      parameters:
      - in: formData
        name: |-
          name
          Name of the metric, must be globally unique, recommended that you add your own namespace
        description: typeType of metric, could be a device metric, a plugin metric
          or any arbitrary type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Metrics
    get:
      summary: Get Metrics
      description: Retrieves the list of metrics in a project.
      operationId: get-metrics
      x-api-path-slug: v1metrics-get
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /v1/measurements/:metric:
    get:
      summary: Get measures
      description: Retrieves measurement readings.
      operationId: get-measures
      x-api-path-slug: v1measurementsmetric-get
      responses:
        200:
          description: OK
      tags:
      - Measurements
  /v1/measurementsBatch:
    post:
      summary: Get measures batch
      description: Same as /v1/measurements/:metric except that an array of query
        objects are passed in the body.
      operationId: get-measures-batch
      x-api-path-slug: v1measurementsbatch-post
      responses:
        200:
          description: OK
      tags:
      - Measurements
  /v1/metrics/:metric:
    delete:
      summary: Remove metric
      description: |-
        Removes a metric from the account.
         Note that a metric will not deleted if it has been alarmed unless that <em>removeAlarms</em>
         flag is added.
      operationId: remove-metric
      x-api-path-slug: v1metricsmetric-delete
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /v1/metrics/dashactions/:dashboardSetId:
    get:
      summary: Get actions for a dashboard
      description: |-
        Retrieves the needed configuration changes for a dashboard
         Returns an an array of objects, each has the following properties:
      operationId: get-actions-for-a-dashboard
      x-api-path-slug: v1metricsdashactionsdashboardsetid-get
      responses:
        200:
          description: OK
      tags:
      - Metrics
    post:
      summary: Perform dashboard actions
      description: |-
        Performs necessary actions for a dashboard.
         Only enables or adds metrics at this time.
      operationId: perform-dashboard-actions
      x-api-path-slug: v1metricsdashactionsdashboardsetid-post
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /v1/metrics/:metricName:
    put:
      summary: Update metric
      description: Updates a metric
      operationId: update-metric
      x-api-path-slug: v1metricsmetricname-put
      parameters:
      - in: formData
        name: |-
          type
          Type of metric, could be a device metric, a plugin metric or any arbitrary type
        description: descriptionDescription of the metric
        type: string
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /metrics/definitions:
    "":
      summary: Available metrics
      description: Determine which metrics are available to return historical data
        for, for a specific subject (device or service) over a specific time range.
      operationId: available-metrics
      x-api-path-slug: metricsdefinitions-
      parameters:
      - in: query
        name: end
        description: The UTC date string for the end time range in format YYYY-MM-DDTHH:mm:SSZ
          e
        type: string
      - in: query
        name: start
        description: The UTC date string for the start time range in format YYYY-MM-DDTHH:mm:SSZ
          e
        type: string
      - in: query
        name: subjectId
        description: The ID of the subject to get the definitions for, e
        type: string
      - in: query
        name: token
        description: Your API token
        type: string
      responses:
        200:
          description: OK
      tags:
      - Metrics
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