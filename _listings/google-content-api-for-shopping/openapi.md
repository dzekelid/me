---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 1
info:
  title: Content API for Shopping
  description: manages-product-items-inventory-and-merchant-center-accounts-for-google-shopping-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{merchantId}/orders/{orderId}/updateMerchantOrderId:
    post:
      summary: Update Merchant Order ID
      description: Updates the merchant order ID for a given order. This method can
        only be called for non-multi-client accounts.
      operationId: content.orders.updatemerchantorderid
      x-api-path-slug: merchantidordersorderidupdatemerchantorderid-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: orderId
        description: The ID of the order
      responses:
        200:
          description: OK
      tags:
      - Merchant
      - Order
      - ID
  /{merchantId}/orders/{orderId}/updateShipment:
    post:
      summary: Update order Shippment
      description: Updates a shipment's status, carrier, and/or tracking ID. This
        method can only be called for non-multi-client accounts.
      operationId: content.orders.updateshipment
      x-api-path-slug: merchantidordersorderidupdateshipment-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: orderId
        description: The ID of the order
      responses:
        200:
          description: OK
      tags:
      - order
      - Shippment
---