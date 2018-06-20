---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Groups API Redirect to the assignment override for a group
  description: Redirect to the assignment override for a group.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /groups/{group_id}/assignments/assignment_id/override:
    get:
      summary: Redirect to the assignment override for a group
      description: Redirect to the assignment override for a group.
      operationId: redirect-to-the-assignment-override-for-a-group
      x-api-path-slug: groupsgroup-idassignmentsassignment-idoverride-get
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Assignments
      - Assignment
      - Id
      - Override
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