---
swagger: "2.0"
x-collection-name: IEX
x-complete: 1
info:
  title: IEX
  description: the-iex-api-is-a-set-of-services-designed-for-developers-and-engineers--it-can-be-used-to-build-highquality-apps-and-services--were-always-working-to-improve-the-iex-api--please-check-back-for-enhancements-and-improvements-
  termsOfService: https://iextrading.com/api-terms/
  version: 1.0.0
host: api.iextrading.com
basePath: /1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stock/{symbol}/previous:
    get:
      summary: Previous
      description: This returns previous day adjusted price data for a single stock,
        or an object keyed by symbol of price data for the whole market.
      operationId: previous
      x-api-path-slug: stocksymbolprevious-get
      parameters:
      - in: path
        name: symbol
        description: Stock ticker symbol
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Quotes
      - Adjustments
---