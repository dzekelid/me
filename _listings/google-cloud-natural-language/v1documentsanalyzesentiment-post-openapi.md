---
swagger: "2.0"
x-collection-name: Google Cloud Natural Language
x-complete: 0
info:
  title: Google Cloud Natural Language API Analyze SEntiment
  description: Analyzes the sentiment of the provided text.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: language.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/documents:analyzeSentiment:
    post:
      summary: Analyze SEntiment
      description: Analyzes the sentiment of the provided text.
      operationId: language.documents.analyzeSentiment
      x-api-path-slug: v1documentsanalyzesentiment-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Sentiment
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