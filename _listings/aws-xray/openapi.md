---
swagger: "2.0"
x-collection-name: AWS X-Ray
x-complete: 1
info:
  title: AWS X-Ray API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PutTelemetryRecords:
    get:
      summary: Put Telemetry Records
      description: Used by the AWS X-Ray daemon to upload telemetry.
      operationId: putTelemetryRecords
      x-api-path-slug: actionputtelemetryrecords-get
      parameters:
      - in: query
        name: EC2InstanceId
        type: string
      - in: query
        name: Hostname
        type: string
      - in: query
        name: ResourceARN
        type: string
      - in: query
        name: TelemetryRecords
        type: string
      responses:
        200:
          description: OK
      tags:
      - Telemetry Records
  /?Action=PutTraceSegments:
    get:
      summary: Put Trace Segments
      description: Uploads segment documents to AWS X-Ray.
      operationId: putTraceSegments
      x-api-path-slug: actionputtracesegments-get
      parameters:
      - in: query
        name: TraceSegmentDocuments
        description: A JSON document defining one or more segments or subsegments
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trace Segments
---