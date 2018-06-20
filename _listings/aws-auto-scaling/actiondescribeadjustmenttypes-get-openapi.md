---
swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 0
info:
  title: AWS Auto Scaling API Describe Adjustment Types
  version: 1.0.0
  description: Describes the policy adjustment types for use with.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAdjustmentTypes:
    get:
      summary: Describe Adjustment Types
      description: Describes the policy adjustment types for use with.
      operationId: describeAdjustmentTypes
      x-api-path-slug: actiondescribeadjustmenttypes-get
      parameters:
      - in: query
        name: AdjustmentTypes.member.N
        description: The policy adjustment types
        type: string
      responses:
        200:
          description: OK
      tags:
      - Adjustment Types
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