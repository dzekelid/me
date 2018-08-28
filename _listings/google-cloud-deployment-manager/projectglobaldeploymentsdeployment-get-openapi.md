---
swagger: "2.0"
x-collection-name: Google Cloud Deployment Manager
x-complete: 0
info:
  title: Google Cloud Deployment Manager Get Deployment
  version: 1.0.0
  description: Gets information about a specific deployment.
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
  /{project}/global/deployments/{deployment}:
    delete:
      summary: Delete Deployment
      description: Deletes a deployment and all of the resources in the deployment.
      operationId: deploymentmanager.deployments.delete
      x-api-path-slug: projectglobaldeploymentsdeployment-delete
      parameters:
      - in: query
        name: deletePolicy
        description: Sets the policy to use for deleting resources
      - in: path
        name: deployment
        description: The name of the deployment for this request
      - in: path
        name: project
        description: The project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Deployment
    get:
      summary: Get Deployment
      description: Gets information about a specific deployment.
      operationId: deploymentmanager.deployments.get
      x-api-path-slug: projectglobaldeploymentsdeployment-get
      parameters:
      - in: path
        name: deployment
        description: The name of the deployment for this request
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