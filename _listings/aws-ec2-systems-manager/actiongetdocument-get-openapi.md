---
swagger: "2.0"
x-collection-name: AWS EC2 Systems Manager
x-complete: 0
info:
  title: Amazon EC2 Systems Manager API Get Document
  version: 1.0.0
  description: Gets the contents of the specified SSM document.
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
  /?Action=DescribeDocument:
    get:
      summary: Describe Document
      description: Describes the specified SSM document.
      operationId: describeDocument
      x-api-path-slug: actiondescribedocument-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version for which you want information
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
  /?Action=DescribeDocumentPermission:
    get:
      summary: Describe Document Permission
      description: Describes the permissions for an SSM document.
      operationId: describeDocumentPermission
      x-api-path-slug: actiondescribedocumentpermission-get
      parameters:
      - in: query
        name: Name
        description: The name of the document for which you are the owner
        type: string
      - in: query
        name: PermissionType
        description: The permission type for the document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
      - Permission
  /?Action=DescribeParameters:
    get:
      summary: Describe Parameters
      description: Get information about a parameter.
      operationId: describeParameters
      x-api-path-slug: actiondescribeparameters-get
      parameters:
      - in: query
        name: Filters
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameters
  /?Action=GetDocument:
    get:
      summary: Get Document
      description: Gets the contents of the specified SSM document.
      operationId: getDocument
      x-api-path-slug: actiongetdocument-get
      parameters:
      - in: query
        name: DocumentVersion
        description: The document version for which you want information
        type: string
      - in: query
        name: Name
        description: The name of the SSM document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Document
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