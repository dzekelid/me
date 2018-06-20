---
swagger: "2.0"
x-collection-name: Google Cloud Deployment Manager
x-complete: 0
info:
  title: Google Cloud Deployment Manager Create Deployment
  version: 1.0.0
  description: Creates a deployment and all of the resources described by the deployment
    manifest.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/global/deployments:
    get:
      summary: Get Deployments
      description: Lists all deployments for a given project.
      operationId: deploymentmanager.deployments.list
      x-api-path-slug: projectglobaldeployments-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: The project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Deployment
    post:
      summary: Create Deployment
      description: Creates a deployment and all of the resources described by the
        deployment manifest.
      operationId: deploymentmanager.deployments.insert
      x-api-path-slug: projectglobaldeployments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: preview
        description: If set to true, creates a deployment and creates shell resources
          but does not actually instantiate these resources
      - in: path
        name: project
        description: The project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Deployment
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