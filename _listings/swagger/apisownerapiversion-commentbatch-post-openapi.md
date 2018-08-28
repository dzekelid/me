---
swagger: "2.0"
x-collection-name: Swagger
x-complete: 0
info:
  title: Swagger Hub Registry Updates passed batch of comments
  description: Updates passed batch of comments.
  contact:
    name: SwaggerHub
    url: http://swaggerhub.com
    email: info@swaggerhub.com
  version: 1.0.45
host: api.swaggerhub.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apis/{owner}/{api}/.newname:
    post:
      summary: Renames API
      description: Renames api.
      operationId: renameApi
      x-api-path-slug: apisownerapi-newname-post
      parameters:
      - in: path
        name: api
        description: API identifier
      - in: query
        name: newName
        description: New name
      - in: path
        name: owner
        description: API owner identifier
      responses:
        200:
          description: OK
      tags:
      - APIs
      - Owner
      - ""
      - Newname
  /apis/{owner}/{api}/{version}/.comment:
    get:
      summary: Returns the list of comments for the specified API
      description: Returns the list of comments for the specified api.
      operationId: getApiComments
      x-api-path-slug: apisownerapiversion-comment-get
      parameters:
      - in: path
        name: api
        description: API identifier
      - in: path
        name: owner
        description: API owner identifier
      - in: path
        name: version
        description: version identifier
      responses:
        200:
          description: OK
      tags:
      - APIs
      - Owner
      - Version
      - ""
      - Comment
    post:
      summary: Adds a new comment to the specified API
      description: Adds a new comment to the specified api.
      operationId: addApiComment
      x-api-path-slug: apisownerapiversion-comment-post
      parameters:
      - in: path
        name: api
        description: API identifier
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: API owner identifier
      - in: path
        name: version
        description: version identifier
      responses:
        200:
          description: OK
      tags:
      - APIs
      - Owner
      - Version
      - ""
      - Comment
  /apis/{owner}/{api}/{version}/.comment/batch:
    post:
      summary: Updates passed batch of comments
      description: Updates passed batch of comments.
      operationId: updateApiComments
      x-api-path-slug: apisownerapiversion-commentbatch-post
      parameters:
      - in: path
        name: api
        description: API identifier
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: API owner identifier
      - in: path
        name: version
        description: version identifier
      responses:
        200:
          description: OK
      tags:
      - APIs
      - Owner
      - Version
      - ""
      - Comment
      - Batch
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