---
swagger: "2.0"
x-collection-name: Google Drive
x-complete: 0
info:
  title: Google Drive Delete File Comment
  description: Deletes a comment.
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /drive/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /files/{fileId}/comments:
    get:
      summary: Get File Comments
      description: Lists a file's comments.
      operationId: drive.comments.list
      x-api-path-slug: filesfileidcomments-get
      parameters:
      - in: path
        name: fileId
        description: The ID of the file
      - in: query
        name: includeDeleted
        description: Whether to include deleted comments
      - in: query
        name: pageSize
        description: The maximum number of comments to return per page
      - in: query
        name: pageToken
        description: The token for continuing a previous list request on the next
          page
      - in: query
        name: startModifiedTime
        description: The minimum value of modifiedTime for the result comments (RFC
          3339 date-time)
      responses:
        200:
          description: OK
      tags:
      - Comment
    post:
      summary: Create File Comment
      description: Creates a new comment on a file.
      operationId: drive.comments.create
      x-api-path-slug: filesfileidcomments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: fileId
        description: The ID of the file
      responses:
        200:
          description: OK
      tags:
      - Comment
  /files/{fileId}/comments/{commentId}:
    delete:
      summary: Delete File Comment
      description: Deletes a comment.
      operationId: drive.comments.delete
      x-api-path-slug: filesfileidcommentscommentid-delete
      parameters:
      - in: path
        name: commentId
        description: The ID of the comment
      - in: path
        name: fileId
        description: The ID of the file
      responses:
        200:
          description: OK
      tags:
      - Comment
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