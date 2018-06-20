---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 0
info:
  title: Google Play Update Entitlement
  version: 1.0.0
  description: Adds or updates an entitlement to an app for a user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{packageName}/entitlements:
    get:
      summary: Get Entitlements
      description: Lists the user's current inapp item or subscription entitlements
      operationId: androidpublisher.entitlements.list
      x-api-path-slug: packagenameentitlements-get
      parameters:
      - in: query
        name: maxResults
      - in: path
        name: packageName
        description: The package name of the application the inapp product was sold
          in (for example, com
      - in: query
        name: productId
        description: The product id of the inapp product (for example, sku1)
      - in: query
        name: startIndex
      - in: query
        name: token
      responses:
        200:
          description: OK
      tags:
      - Entitlement
  /enterprises/{enterpriseId}/users/{userId}/entitlements:
    get:
      summary: Get Entitlements
      description: Lists all entitlements for the specified user. Only the ID is set.
      operationId: androidenterprise.entitlements.list
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlements-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
  /enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}:
    delete:
      summary: Remove Entitlement
      description: Removes an entitlement to an app for a user.
      operationId: androidenterprise.entitlements.delete
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-delete
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    get:
      summary: Get Entitlement
      description: Retrieves details of an entitlement.
      operationId: androidenterprise.entitlements.get
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    patch:
      summary: Update Entitlement
      description: Adds or updates an entitlement to an app for a user. This method
        supports patch semantics.
      operationId: androidenterprise.entitlements.patch
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: query
        name: install
        description: Set to true to also install the product on all the users devices
          where possible
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    put:
      summary: Update Entitlement
      description: Adds or updates an entitlement to an app for a user.
      operationId: androidenterprise.entitlements.update
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: query
        name: install
        description: Set to true to also install the product on all the users devices
          where possible
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
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