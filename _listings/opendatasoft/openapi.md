---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 1
info:
  title: OpenDataSoft
  description: opendatasoft-is-a-cloudbased-turnkey-platform-for-data-publishing-and-api-management--its-interface-is-intuitively-designed-to-empower-anyone-regardless-of-technical-skills-to-upload-easytounderstand-open-data-or-to-even-share-data-within-an-admi---
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
  /{source}/metadata_templates:
    get:
      summary: Get Source Metadata Templates
      description: List of available metadata templates types, each with their endpoints.
      operationId: getMetadataTemplatesTypes
      x-api-path-slug: sourcemetadata-templates-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Metadata
      - Templates
  /{source}/metadata_templates/{metadata_template_type}:
    get:
      summary: Get Source Metadata Templates Metadata Template Type
      description: List of metadata templates available for this type.
      operationId: getMetadataTemplatesType
      x-api-path-slug: sourcemetadata-templatesmetadata-template-type-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Metadata
      - Templates
      - Metadata
      - Template
      - Type
  /{source}/metadata_templates/{metadata_template_type}/{metadata_template_name}:
    get:
      summary: Get Source Metadata Templates Metadata Template Type Metadata Template
        Name
      description: A single metadata_template
      operationId: getMetadataTemplate
      x-api-path-slug: sourcemetadata-templatesmetadata-template-typemetadata-template-name-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Metadata
      - Templates
      - Metadata
      - Template
      - Type
      - Metadata
      - Template
      - Name
---