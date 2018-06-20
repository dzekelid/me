---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Merchandised Product
  description: This call returns an array of products based on the category and metric
    specified. This includes details of the product, such as the eBay product Id (EPID),
    title, and user reviews and ratings for the product. You can use the epid returned
    by this call in the Browse API search call to retrieve items for this product.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /merchandised_product:
    get:
      summary: Get Merchandised Product
      description: This call returns an array of products based on the category and
        metric specified. This includes details of the product, such as the eBay product
        Id (EPID), title, and user reviews and ratings for the product. You can use
        the epid returned by this call in the Browse API search call to retrieve items
        for this product. Restrictions For a list of supported sites and other restrictions,
        see API Restrictions.
      operationId: getMerchandisedProducts
      x-api-path-slug: merchandised-product-get
      parameters:
      - in: query
        name: aspect_filter
        description: The aspect name/value pairs used to further refine product results
      - in: query
        name: category_id
        description: This query parameter limits the products returned to a specific
          eBay category
      - in: query
        name: limit
        description: This value specifies the maximum number of products to return
          in a result set
      - in: query
        name: metric_name
        description: This value filters the result set by the specified metric
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product
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