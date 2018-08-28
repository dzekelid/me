---
swagger: "2.0"
x-collection-name: VictorOps
x-complete: 0
info:
  title: Victor Ops Get the available timeout values
  description: |-
    Get the available timeout values

    description: "If still unacked after 1 minute", type: 1
    description: "If still unacked after 5 minutes", type: 5
    description: "If still unacked after 10 minutes", type: 10
    description: "If still unacked after 15 minutes", type: 15
    description: "If still unacked after 20 minutes", type: 20
    description: "If still unacked after 25 minutes", type: 25
    description: "If still unacked after 30 minutes", type: 30
    description: "If still unacked after 45 minutes", type: 45
    description: "If still unacked after 60 minutes", type: 60

    This API may be called a maximum of 15 times per minute.
  version: 0.0.2
host: api.victorops.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api-public/v1/policies/types/timeouts:
    get:
      summary: Get the available timeout values
      description: |-
        Get the available timeout values

        description: "If still unacked after 1 minute", type: 1
        description: "If still unacked after 5 minutes", type: 5
        description: "If still unacked after 10 minutes", type: 10
        description: "If still unacked after 15 minutes", type: 15
        description: "If still unacked after 20 minutes", type: 20
        description: "If still unacked after 25 minutes", type: 25
        description: "If still unacked after 30 minutes", type: 30
        description: "If still unacked after 45 minutes", type: 45
        description: "If still unacked after 60 minutes", type: 60

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.policies.types.timeouts.get
      x-api-path-slug: apipublicv1policiestypestimeouts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Policies
      - Types
      - Timeouts
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