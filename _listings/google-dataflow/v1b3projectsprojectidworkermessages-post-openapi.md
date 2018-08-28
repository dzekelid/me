---
swagger: "2.0"
x-collection-name: Google Dataflow
x-complete: 0
info:
  title: Google Cloud Dataflow API Send Worker Message
  description: Send a worker_message to the service.
  contact:
    name: Google
    url: https://google.com
  version: v1b3
host: dataflow.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1b3/projects/{projectId}/WorkerMessages:
    post:
      summary: Send Worker Message
      description: Send a worker_message to the service.
      operationId: dataflow.projects.workerMessages
      x-api-path-slug: v1b3projectsprojectidworkermessages-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: projectId
        description: The project to send the WorkerMessages to
      responses:
        200:
          description: OK
      tags:
      - Worker Message
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