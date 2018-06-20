---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 0
info:
  title: BMC Software API Create metric
  version: 1.0.0
  description: Creates a new metric
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