---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Post Shoppers Me
  description: Post shoppers me.
  version: v1
host: store.digitalriver.com
basePath: /store/{mysite}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/shoppers/me:
    get:
      summary: Get Shoppers Me
      description: Get shoppers me.
      operationId: getV1ShoppersMe
      x-api-path-slug: v1shoppersme-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
    post:
      summary: Post Shoppers Me
      description: Post shoppers me.
      operationId: postV1ShoppersMe
      x-api-path-slug: v1shoppersme-post
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
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