---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Groups Group Members
  description: "### Create a Group Member\n\nAdds a member to a group with a ```group_id```.
    \u200BMake sure you provide an accurate email address and/or phone number or alerts
    will not be received by the member."
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /realtime:
    post:
      summary: Post Realtime
      description: |-
        ## Current Weather Data
        The ```realtime``` API call provides weather information at the present time, down to the minute, for a specific location. The location can be specified as a geocode, or one of your own defined locations (see ```locations``` API calls). The weather parameters returned are detailed in the __Weather Data__ section.
      operationId: -current-weather-datathe-realtime-api-call-provides-weather-information-at-the-present-time-down-to-
      x-api-path-slug: realtime-post
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Realtime
  /groups/{group_id}/members:
    get:
      summary: Get Groups Group Members
      description: |-
        ### List all Group Members
        Page through a list of all members of a group with a ```group_id```. You can specify the maximum number of results to be retuned, and from which result to start.
      operationId: -list-all-group-memberspage-through-a-list-of-all-members-of-a-group-with-a-group-id-you-can-specify
      x-api-path-slug: groupsgroup-idmembers-get
      parameters:
      - in: path
        name: group_id
        description: UUID of the Group
      - in: query
        name: limit
        description: The maximum number of records to load
      - in: query
        name: offset
        description: The number of records to skip
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
      - Group
      - Members
    post:
      summary: Post Groups Group Members
      description: "### Create a Group Member\n\nAdds a member to a group with a ```group_id```.
        \u200BMake sure you provide an accurate email address and/or phone number
        or alerts will not be received by the member."
      operationId: -create-a-group-memberadds-a-member-to-a-group-with-a-group-id-make-sure-you-provide-an-accurate-ema
      x-api-path-slug: groupsgroup-idmembers-post
      parameters:
      - in: body
        name: group
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: group_id
        description: UUID of the Group
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Groups
      - Group
      - Members
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