---
swagger: "2.0"
x-collection-name: Bank of Ireland
x-complete: 0
info:
  title: Bank of Ireland Get Commercial Credit Cards
  description: This endpoint can contain multiple brands owned by a particular banking
    group. Each brand can own multiple SME Commercial Credit Card products.
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: openapi.bankofireland.com
basePath: open-banking/v2.1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  unsecured-sme-loans/:
    get:
      summary: Get Unsecured Sme Loans
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple SME Unsecured Loan products.
      operationId: pathOperation
      x-api-path-slug: unsecuredsmeloans-get
      responses:
        200:
          description: OK
      tags:
      - Unsecured
      - Sme
      - Loans
  commercial-credit-cards/:
    get:
      summary: Get Commercial Credit Cards
      description: This endpoint can contain multiple brands owned by a particular
        banking group. Each brand can own multiple SME Commercial Credit Card products.
      operationId: getCommercialCreditCards
      x-api-path-slug: commercialcreditcards-get
      responses:
        200:
          description: OK
      tags:
      - Commercial
      - Credit
      - Cards
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