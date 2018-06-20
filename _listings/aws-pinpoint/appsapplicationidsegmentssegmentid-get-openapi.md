---
swagger: "2.0"
x-collection-name: AWS Pinpoint
x-complete: 0
info:
  title: AWS Pinpoint API Segment Instance
  version: 1.0.0
  description: Use the GET method to request information about a segment.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/application-id/segments:
    get:
      summary: Segments List
      description: Use the GET method to request information about your segments.
      operationId: segmentsList
      x-api-path-slug: appsapplicationidsegments-get
      responses:
        200:
          description: OK
      tags:
      - Segments
    post:
      summary: Segments List
      description: Use the POST method to create or update a segment.
      operationId: addSegmentsList
      x-api-path-slug: appsapplicationidsegments-post
      responses:
        200:
          description: OK
      tags:
      - Segments
  /apps/application-id/segments/segment-id:
    get:
      summary: Segment Instance
      description: Use the GET method to request information about a segment.
      operationId: getSegmentInstance
      x-api-path-slug: appsapplicationidsegmentssegmentid-get
      responses:
        200:
          description: OK
      tags:
      - Segments
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