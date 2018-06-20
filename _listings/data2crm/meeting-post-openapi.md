---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM POST for Meeting
  description: Add meeting into the system
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /attachment:
    get:
      summary: GET for Attachment
      description: Returns all attachments from the system
      operationId: getAttachmentCollection
      x-api-path-slug: attachment-get
      parameters:
      - in: query
        name: filter
        description: Filter
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: query
        name: parent_id
        description: Parent Identifier
      - in: query
        name: parent_type
        description: Parent Type
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
    post:
      summary: POST for Attachment
      description: Add attachment into the system
      operationId: createAttachmentEntity
      x-api-path-slug: attachment-post
      parameters:
      - in: body
        name: body
        description: Add attachment into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
  /attachment/count:
    get:
      summary: COUNT for Attachment
      description: Count all attachments from the system
      operationId: getAttachmentCountCollection
      x-api-path-slug: attachmentcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
      - Count
  /attachment/describe:
    get:
      summary: DESCRIBE for Attachment
      description: Returns describe for attachments
      operationId: getAttachmentDescribe
      x-api-path-slug: attachmentdescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
      - Describe
  /attachment/{attachment_id}:
    delete:
      summary: DELETE for Attachment
      description: Delete attachment information
      operationId: deleteAttachmentEntity
      x-api-path-slug: attachmentattachment-id-delete
      parameters:
      - in: path
        name: attachment_id
        description: Attachment Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
    get:
      summary: GET for Attachment
      description: Return attachment information
      operationId: getAttachmentEntity
      x-api-path-slug: attachmentattachment-id-get
      parameters:
      - in: path
        name: attachment_id
        description: Attachment Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
    put:
      summary: PUT for Attachment
      description: Update attachment information
      operationId: updateAttachmentEntity
      x-api-path-slug: attachmentattachment-id-put
      parameters:
      - in: path
        name: attachment_id
        description: Attachment Identifier
      - in: body
        name: body
        description: Update attachment information
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
  /meeting:
    get:
      summary: GET for Meeting
      description: Returns all meetings from the system
      operationId: getMeetingCollection
      x-api-path-slug: meeting-get
      parameters:
      - in: query
        name: filter
        description: Filter
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: query
        name: parent_id
        description: Parent Identifier
      - in: query
        name: parent_type
        description: Parent Type
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Meeting
    post:
      summary: POST for Meeting
      description: Add meeting into the system
      operationId: createMeetingEntity
      x-api-path-slug: meeting-post
      parameters:
      - in: body
        name: body
        description: Add meeting into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Meeting
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