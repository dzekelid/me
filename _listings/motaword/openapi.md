---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 1
info:
  title: Mota Word
  description: use-motaword-api-to-post-and-track-your-translation-projects-
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
  /projects/{projectId}/documents/{documentId}:
    delete:
      summary: Delete the document
      description: Delete the document.
      operationId: deleteDocument
      x-api-path-slug: projectsprojectiddocumentsdocumentid-delete
      parameters:
      - in: path
        name: documentId
        description: Document ID
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
      - DocumentId
    get:
      summary: Get single document
      description: Get single document.
      operationId: getDocument
      x-api-path-slug: projectsprojectiddocumentsdocumentid-get
      parameters:
      - in: path
        name: documentId
        description: Document ID
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
      - DocumentId
    put:
      summary: Update the document.
      description: Update the document. File name and contents will replaced with
        the new one.
      operationId: updateDocument
      x-api-path-slug: projectsprojectiddocumentsdocumentid-put
      parameters:
      - in: path
        name: documentId
        description: Document ID
      - in: formData
        name: documents
        description: Single file data
      - in: path
        name: projectId
        description: Project ID
      - in: formData
        name: schemes
        description: JSON string
      responses:
        200:
          description: OK
      tags:
      - Projects
      - ProjectId
      - Documents
      - DocumentId
  /projects/{projectId}/documents/{documentId}/download:
    get:
      summary: Download a document
      description: Download a document.
      operationId: downloadDocument
      x-api-path-slug: projectsprojectiddocumentsdocumentiddownload-get
      parameters:
      - in: path
        name: documentId
        description: Document ID
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
      - DocumentId
      - Download
---