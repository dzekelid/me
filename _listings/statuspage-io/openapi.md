---
swagger: "2.0"
x-collection-name: StatusPage.io
x-complete: 1
info:
  title: StatusPage.io
  version: 1.0.0
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
    post:
      summary: Create a custom metric
      description: Create a custom metric
      operationId: create-a-custom-metric
      x-api-path-slug: pagespage-idmetrics-providersmetrics-provider-idmetrics-json-post
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
  /pages/[page_id]/metrics/[metric_id]/data.json:
    post:
      summary: Submit data for a custom metric
      description: Submit data for a custom metric
      operationId: submit-data-for-a-custom-metric
      x-api-path-slug: pagespage-idmetricsmetric-iddata-json-post
      responses:
        200:
          description: OK
      tags:
      - Metrics
    delete:
      summary: Delete all data for a custom metric
      description: Delete all data for a custom metric
      operationId: delete-all-data-for-a-custom-metric
      x-api-path-slug: pagespage-idmetricsmetric-iddata-json-delete
      responses:
        200:
          description: OK
      tags:
      - Metrics
---