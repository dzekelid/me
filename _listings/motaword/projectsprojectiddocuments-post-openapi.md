---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Upload a new document
  description: Upload a new document.
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Get your account information and summary.
      description: Get your account information and summary..
      operationId: getAccount
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me
  /projects/{projectId}/activities/{activityId}/comments:
    get:
      summary: Get a list of comments belonging to this activity.
      description: Get a list of comments belonging to this activity..
      operationId: getActivityComments
      x-api-path-slug: projectsprojectidactivitiesactivityidcomments-get
      parameters:
      - in: path
        name: activityId
        description: Activity ID
      - in: path
        name: projectId
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - ProjectId
      - Activities
      - ActivityId
      - Comments
  /projects/{projectId}/comments:
    get:
      summary: Get a list of activity comments throughout the whole project.
      description: Get a list of activity comments throughout the whole project..
      operationId: getComments
      x-api-path-slug: projectsprojectidcomments-get
      parameters:
      - in: query
        name: page
      - in: query
        name: per_page
      - in: path
        name: projectId
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - ProjectId
      - Comments
  /projects/{projectId}/documents:
    get:
      summary: Get a list of documents
      description: Get a list of documents.
      operationId: getDocuments
      x-api-path-slug: projectsprojectiddocuments-get
      parameters:
      - in: path
        name: projectId
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - ProjectId
      - Documents
    post:
      summary: Upload a new document
      description: Upload a new document.
      operationId: createDocument
      x-api-path-slug: projectsprojectiddocuments-post
      parameters:
      - in: formData
        name: documents[]
        description: You can add as many files as you want in documents[] parameter
      - in: path
        name: projectId
        description: Project ID
      - in: formData
        name: schemes[]
        description: JSON string
      responses:
        200:
          description: OK
      tags:
      - Projects
      - ProjectId
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