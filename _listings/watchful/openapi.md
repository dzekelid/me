---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 1
info:
  title: Watchful
  description: watchful-resulted-from-the-need-for-a-single-unified-dashboard-to-easily-monitor-all-of-the-web-sites-in-our-portfolios--after-years-of-evolution-our-solution-has-matured-into-a-simple-complete-and-professional-service--
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /audits/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsAudits
      x-api-path-slug: auditsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Metadata
  /extensions/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsExtensions
      x-api-path-slug: extensionsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Extensions
      - Metadata
  /feedbacks/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsFeedbacks
      x-api-path-slug: feedbacksmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Feedbacks
      - Metadata
  /logs/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsLogs
      x-api-path-slug: logsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Logs
      - Metadata
  /sites/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: sites.metadata.get
      x-api-path-slug: sitesmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Metadata
  /sites/{id}/uptime:
    get:
      summary: Return Uptime Data
      description: Return uptime data
      operationId: getUptime
      x-api-path-slug: sitesiduptime-get
      parameters:
      - in: path
        name: id
        description: ID of the website
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Uptime
  /tags/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: tags.metadata.get
      x-api-path-slug: tagsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Tags
      - Metadata
---