---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Order Order Shipping Fulfillment
  description: Use this call to retrieve the contents of all fulfillments currently
    defined for a specified order based on the order's unique identifier, orderId.
    This value is returned in the getOrders call's members.orderId field when you
    search for orders by creation date or shipment status.
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
  /merchandised_product/get_also_bought_products:
    get:
      summary: Get Merchandised Product Get Also Bought Products
      description: 'This call returns products that were also bought when shoppers
        bought the product specified in the request. Showing ''also bought'' products
        inspires up-selling and cross-selling. You specify the product by one of the
        following. epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand
        name such as Nike) plus mpn (Manufacturer''s Part Number) Restrictions For
        a list of supported sites and other restrictions, see API Restrictions. Maximum:
        A maximum of 12 products are returned. The call will return up to 12 products,
        but it can be less than 12. If the number of products found is less than 12,
        the call will return all of the products matching the criteria.'
      operationId: getAlsoBoughtByProduct
      x-api-path-slug: merchandised-productget-also-bought-products-get
      parameters:
      - in: query
        name: brand
        description: The brand of the product
      - in: query
        name: epid
        description: The eBay product identifier of a product
      - in: query
        name: gtin
        description: The unique Global Trade Item Number of the item as defined by
          http://www
      - in: query
        name: mpn
        description: The manufacturer part number of the product
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product
      - ""
      - Also
      - Bought
      - Products
  /merchandised_product/get_also_viewed_products:
    get:
      summary: Get Merchandised Product Get Also Viewed Products
      description: 'This call returns products that were also viewed when shoppers
        viewed the product specified in the request. Showing ''also viewed'' products
        encourages up-selling and cross-selling. You specify the product by one of
        the following. epid (eBay Product Id) gtin (Global Trade Item Number) brand
        (brand name such as Nike) plus mpn (Manufacturer''s Part Number) Restrictions
        For a list of supported sites and other restrictions, see API Restrictions.
        Maximum: A maximum of 12 products are returned. The call will return up to
        12 products, but it can be less than 12. If the number of products found is
        less than 12, the call will return all of the products matching the criteria.'
      operationId: getAlsoViewedByProduct
      x-api-path-slug: merchandised-productget-also-viewed-products-get
      parameters:
      - in: query
        name: brand
        description: The brand of the product
      - in: query
        name: epid
        description: The eBay product identifier of a product
      - in: query
        name: gtin
        description: The unique Global Trade Item Number of the item as defined by
          http://www
      - in: query
        name: mpn
        description: The manufacturer part number of the product
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product
      - ""
      - Also
      - Viewed
      - Products
  /order/{orderId}/shipping_fulfillment:
    get:
      summary: Get Order Order Shipping Fulfillment
      description: Use this call to retrieve the contents of all fulfillments currently
        defined for a specified order based on the order's unique identifier, orderId.
        This value is returned in the getOrders call's members.orderId field when
        you search for orders by creation date or shipment status.
      operationId: getShippingFulfillments
      x-api-path-slug: orderorderidshipping-fulfillment-get
      parameters:
      - in: path
        name: orderId
        description: The unique identifier of the order
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Order
      - Order
      - Shipping
      - Fulfillment
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