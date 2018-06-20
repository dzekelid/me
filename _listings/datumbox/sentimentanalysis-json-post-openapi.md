---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Identifies the Sentiment of the Document
  description: The Sentiment Analysis function classifies documents as positive, negative
    or neutral (lack of sentiment) depending on whether they express a positive, negative
    or neutral opinion.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /CommercialDetection.json:
    post:
      summary: Classifies the Document as commercial or nocommercial
      description: The Commercial Detection function labels the documents as commercial
        or non-commercial based on their keywords and expressions. It can be used
        to detect whether a website is commercial or not.
      operationId: CommercialDetection
      x-api-path-slug: commercialdetection-json-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Commercial
      - Detection
  /DocumentSimilarity.json:
    post:
      summary: Estimates the similarity between 2 Documents
      description: The Document Similarity function estimates the degree of similarity
        between two documents. It can be used to detect duplicate webpages or detect
        plagiarism.
      operationId: DocumentSimilarity
      x-api-path-slug: documentsimilarity-json-post
      parameters:
      - in: formData
        name: copy
        description: The second text
      - in: formData
        name: original
        description: The first text
      responses:
        200:
          description: OK
      tags:
      - DocumentsSimilarity
  /ReadabilityAssessment.json:
    post:
      summary: Evaluates the Readability of the Document
      description: The Readability Assessment function determines the degree of readability
        of a document based on its terms and idioms. The texts are classified as basic,
        intermediate and advanced depending their difficulty.
      operationId: ReadabilityAssessment
      x-api-path-slug: readabilityassessment-json-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Readability
      - Assessment
  /SentimentAnalysis.json:
    post:
      summary: Identifies the Sentiment of the Document
      description: The Sentiment Analysis function classifies documents as positive,
        negative or neutral (lack of sentiment) depending on whether they express
        a positive, negative or neutral opinion.
      operationId: SentimentAnalysis
      x-api-path-slug: sentimentanalysis-json-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Sentiment
      - Analysis
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