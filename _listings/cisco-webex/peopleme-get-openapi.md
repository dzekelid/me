---
swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 0
info:
  title: WebEx Teams API Get person details (me)
  description: |-
    Show the profile for the authenticated user.

    https://developer.webex.com/endpoint-people-me-get.html
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /people/me:
    get:
      summary: Get person details (me)
      description: |-
        Show the profile for the authenticated user.

        https://developer.webex.com/endpoint-people-me-get.html
      operationId: PeopleMeGet
      x-api-path-slug: peopleme-get
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Person
      - Details
      - (me)
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