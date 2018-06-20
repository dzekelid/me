---
swagger: "2.0"
x-collection-name: AWS WorkDocs
x-complete: 0
info:
  title: AWS WorkDocs API Initiate Document Version Upload
  version: 1.0.0
  description: Creates a new document object and version object.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AbortDocumentVersionUpload:
    get:
      summary: Abort Document Version Upload
      description: Aborts the upload of the specified document version that was previously
        initiated by.
      operationId: abortDocumentVersionUpload
      x-api-path-slug: actionabortdocumentversionupload-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: VersionId
        description: The ID of the version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=DeleteDocument:
    get:
      summary: Delete Document
      description: Permanently deletes the specified document and its associated metadata.
      operationId: deleteDocument
      x-api-path-slug: actiondeletedocument-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=DescribeDocumentVersions:
    get:
      summary: Describe Document Versions
      description: Retrieves the document versions for the specified document.
      operationId: describeDocumentVersions
      x-api-path-slug: actiondescribedocumentversions-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: Fields
        description: Specify SOURCE to include initialized versions and a URL for
          the source document
        type: string
      - in: query
        name: Include
        description: A comma-separated list of values
        type: string
      - in: query
        name: Limit
        description: The maximum number of versions to return with this call
        type: string
      - in: query
        name: Marker
        description: The marker for the next set of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=GetDocument:
    get:
      summary: Get Document
      description: Retrieves the specified document object.
      operationId: getDocument
      x-api-path-slug: actiongetdocument-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document object
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=GetDocumentPath:
    get:
      summary: Get Document Path
      description: Retrieves the path information (the hierarchy from the root folder)
        for the requested document.
      operationId: getDocumentPath
      x-api-path-slug: actiongetdocumentpath-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: Fields
        description: A comma-separated list of values
        type: string
      - in: query
        name: Limit
        description: The maximum number of levels in the hierarchy to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=GetDocumentVersion:
    get:
      summary: Get Document Version
      description: Retrieves version metadata for the specified document.
      operationId: getDocumentVersion
      x-api-path-slug: actiongetdocumentversion-get
      parameters:
      - in: query
        name: DocumentId
        description: The ID of the document
        type: string
      - in: query
        name: Fields
        description: A comma-separated list of values
        type: string
      - in: query
        name: VersionId
        description: The version ID of the document
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
  /?Action=InitiateDocumentVersionUpload:
    get:
      summary: Initiate Document Version Upload
      description: Creates a new document object and version object.
      operationId: initiateDocumentVersionUpload
      x-api-path-slug: actioninitiatedocumentversionupload-get
      parameters:
      - in: query
        name: ContentType
        description: The content type of the document
        type: string
      - in: query
        name: DocumentSizeInBytes
        description: The size of the document, in bytes
        type: string
      - in: query
        name: Id
        description: The ID of the document
        type: string
      - in: query
        name: Name
        description: The name of the document
        type: string
      - in: query
        name: ParentFolderId
        description: The ID of the parent folder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Documents
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