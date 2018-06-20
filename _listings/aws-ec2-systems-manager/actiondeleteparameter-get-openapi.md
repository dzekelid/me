---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Delete Parameter
  version: 1.0.0
  description: Delete a parameter from the system.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateDocument:
    get:
      summary: Create Document
      description: Creates an SSM document.
      operationId: createDocument
      x-api-path-slug: actioncreatedocument-get
      parameters:
      - in: query
        name: Content
        description: A valid JSON string
        type: string
      - in: query
        name: DocumentType
        description: The type of document to create
        type: string
      - in: query
        name: Name
        description: A name for the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DeleteDocument:
    get:
      summary: Delete Document
      description: Deletes the SSM document and all instance associations to the document.
      operationId: deleteDocument
      x-api-path-slug: actiondeletedocument-get
      parameters:
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DeleteParameter:
    get:
      summary: Delete Parameter
      description: Delete a parameter from the system.
      operationId: deleteParameter
      x-api-path-slug: actiondeleteparameter-get
      parameters:
      - in: query
        name: Name
        description: The name of the parameter to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter
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