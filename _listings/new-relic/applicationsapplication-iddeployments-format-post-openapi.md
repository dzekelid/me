---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Add Applications Application  Deployments. Format
  version: 1.0.0
  description: "This API endpoint creates a deployment record for a given application.\nDeployment
    records are created with the following attributes:\n\nRequired:\n\_\_- Application
    ID\n\_\_- Revision, such as a git SHA\n\nOptional:\n\_\_- Changelog \n\_\_- Description
    \n\_\_- User posting the deployment\n\nNote that the time of your deployment will
    be recorded as the current time in UTC."
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /applications/{application_id}/deployments.{format}:
    get:
      summary: Get Applications Application  Deployments. Format
      description: |-
        This API endpoint returns a paginated list of the deployments associated with a given application.

        See our documentation for a discussion on output pagination.
      operationId: getApplicationsApplicationDeployments.Format
      x-api-path-slug: applicationsapplication-iddeployments-format-get
      parameters:
      - in: path
        name: application_id
        description: Application ID
        type: integer
      - in: query
        name: page
        description: Pagination index
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Application
      - ""
      - Deployments.
      - Format
    post:
      summary: Add Applications Application  Deployments. Format
      description: "This API endpoint creates a deployment record for a given application.\nDeployment
        records are created with the following attributes:\n\nRequired:\n\_\_- Application
        ID\n\_\_- Revision, such as a git SHA\n\nOptional:\n\_\_- Changelog \n\_\_-
        Description \n\_\_- User posting the deployment\n\nNote that the time of your
        deployment will be recorded as the current time in UTC."
      operationId: postApplicationsApplicationDeployments.Format
      x-api-path-slug: applicationsapplication-iddeployments-format-post
      parameters:
      - in: path
        name: application_id
        description: Application ID
        type: integer
      - in: body
        name: deployment
        description: Deployment schema
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Application
      - ""
      - Deployments.
      - Format
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