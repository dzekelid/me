---
swagger: "2.0"
x-collection-name: Google Dataflow
x-complete: 1
info:
  title: Google Dataflow
  description: manages-google-cloud-dataflow-projects-on-google-cloud-platform-
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
---