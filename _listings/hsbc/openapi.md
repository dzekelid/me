---
swagger: "2.0"
x-collection-name: HSBC
x-complete: 1
info:
  title: HSBC
  description: this-is-an-openapi-definition-for-the-standard-set-of-open-banking-httpopenbankingapis-io-apis-for-hsbc-
  termsOfService: https://www.openbanking.org.uk/open-licence/
  contact:
    name: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
  version: 1.0.0
host: api.hsbc.com
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
      summary: Get Unsecured SME Loans
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
---