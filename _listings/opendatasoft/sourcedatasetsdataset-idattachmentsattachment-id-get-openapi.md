---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 0
info:
  title: OpenDataSoft Get Source Datasets Dataset Attachments Attachment
  description: Download attachment
  version: 2.1.0
host: public.opendatasoft.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{source}/datasets/{dataset_id}/attachments:
    get:
      summary: Get Source Datasets Dataset Attachments
      description: Get list of all available attachments
      operationId: getDatasetAttachements
      x-api-path-slug: sourcedatasetsdataset-idattachments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Attachments
  /{source}/datasets/{dataset_id}/attachments/{attachment_id}:
    get:
      summary: Get Source Datasets Dataset Attachments Attachment
      description: Download attachment
      operationId: downloadDatasetAttachement
      x-api-path-slug: sourcedatasetsdataset-idattachmentsattachment-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
      - Id
      - Attachments
      - Attachment
      - Id
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