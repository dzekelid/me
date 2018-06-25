---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 0
info:
  title: Taxamo List Payments
  description: List payments.
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/reports/domestic/summary:
    get:
      summary: Calculate Domestic Summary
      description: Calculate domestic summary.
      operationId: getDomesticSummaryReport
      x-api-path-slug: apiv1reportsdomesticsummary-get
      parameters:
      - in: query
        name: country_code
        description: ISO 2-letter country code which will be used for determining
          which country is domestic
      - in: query
        name: currency_code
        description: ISO 3-letter currency code, e
      - in: query
        name: end_month
        description: Period end month in yyyy-MM format
      - in: query
        name: format
        description: Output format
      - in: query
        name: fx_date_type
        description: Which date should be used for FX
      - in: query
        name: start_month
        description: Period start month in yyyy-MM format
      responses:
        200:
          description: OK
      tags:
      - Calculate
      - Domestic
      - Summary
  /api/v1/settlement/{quarter}:
    get:
      summary: Fetch Settlement
      description: Fetch settlement.
      operationId: getSettlement
      x-api-path-slug: apiv1settlementquarter-get
      parameters:
      - in: query
        name: currency_code
        description: ISO 3-letter currency code, e
      - in: query
        name: end_month
        description: Period end month in yyyy-MM format
      - in: query
        name: format
        description: Output format
      - in: query
        name: moss_country_code
        description: MOSS country code, used to determine currency/region
      - in: query
        name: moss_tax_id
        description: MOSS-assigned tax ID - if not provided, merchants national tax
          number will be used
      - in: path
        name: quarter
        description: Quarter in yyyy-MM format
      - in: query
        name: refund_date_kind_override
        description: Set to order_date to show only refunds for the transactions in
          the selected reporting period
      - in: query
        name: start_month
        description: Period start month in yyyy-MM format
      - in: query
        name: tax_country_code
        description: Tax entity country code, used to determine currency/region
      - in: query
        name: tax_id
        description: MOSS-assigned tax ID - if not provided, merchants national tax
          number will be used
      responses:
        200:
          description: OK
      tags:
      - Fetch
      - Settlement
  /api/v1/stats/settlement/by_country:
    get:
      summary: Settlement By Country
      description: Settlement by country.
      operationId: getSettlementStatsByCountry
      x-api-path-slug: apiv1statssettlementby-country-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Country
  /api/v1/stats/settlement/by_taxation_type:
    get:
      summary: Settlement By Tax Type
      description: Settlement by tax type.
      operationId: getSettlementStatsByTaxationType
      x-api-path-slug: apiv1statssettlementby-taxation-type-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Tax
      - Type
  /api/v1/stats/settlement/daily:
    get:
      summary: Settlement Stats Over Time
      description: Settlement stats over time.
      operationId: getDailySettlementStats
      x-api-path-slug: apiv1statssettlementdaily-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      - in: query
        name: interval
        description: Interval type - day, week, month
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Stats
      - Over
      - Time
  /api/v1/stats/transactions/by_country:
    get:
      summary: Settlement By Country
      description: Settlement by country.
      operationId: getTransactionsStatsByCountry
      x-api-path-slug: apiv1statstransactionsby-country-get
      parameters:
      - in: query
        name: date_from
        description: Date from in yyyy-MM format
      - in: query
        name: date_to
        description: Date to in yyyy-MM format
      - in: query
        name: global_currency_code
        description: Global currency code to use for conversion - in addition to countrys
          currency if rate is available
      responses:
        200:
          description: OK
      tags:
      - Settlement
      - Country
  /api/v1/transactions/{key}/payments:
    get:
      summary: List Payments
      description: List payments.
      operationId: listPayments
      x-api-path-slug: apiv1transactionskeypayments-get
      parameters:
      - in: path
        name: key
        description: Transaction key
      - in: query
        name: limit
        description: Max record count (no more than 100, defaults to 10)
      - in: query
        name: offset
        description: How many records need to be skipped, defaults to 0
      responses:
        200:
          description: OK
      tags:
      - List
      - Payments
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