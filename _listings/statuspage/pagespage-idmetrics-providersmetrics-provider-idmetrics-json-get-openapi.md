---
swagger: "2.0"
x-collection-name: StatusPage
x-complete: 0
info:
  title: StatusPage.io Get a list of metrics created for a linked metrics provider
  version: 1.0.0
  description: Get a list of metrics created for a linked metrics provider
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metrics_providers.json:
    get:
      summary: Get a list of available public metric providers
      description: Get a list of available public metric providers
      operationId: get-a-list-of-available-public-metric-providers
      x-api-path-slug: metrics-providers-json-get
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /pages/[page_id]/metrics_providers.json:
    get:
      summary: Get a list of metric providers linked to your page
      description: Get a list of metric providers linked to your page
      operationId: get-a-list-of-metric-providers-linked-to-your-page
      x-api-path-slug: pagespage-idmetrics-providers-json-get
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
  /pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json:
    get:
      summary: Get a list of metrics created for a linked metrics provider
      description: Get a list of metrics created for a linked metrics provider
      operationId: get-a-list-of-metrics-created-for-a-linked-metrics-provider
      x-api-path-slug: pagespage-idmetrics-providersmetrics-provider-idmetrics-json-get
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
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