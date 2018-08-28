---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 0
info:
  title: hetras Hotel API Version 0 Get the setup of the daily rates for a specific
    rateplan and a defined timeperiod.
  version: v0
  description: "With this call you can read the daily rates setup including the cancellation
    policy and minimum guarantee per day for the\r\n            specified rateplan.
    You can specify a timeperiod to read the daily rates for. The rateplan needs to
    be active for at least\r\n            one business day in the defined time period
    and have rates loaded."
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates:
    get:
      summary: Get the setup of the daily rates for a specific rateplan and a defined
        timeperiod.
      description: "With this call you can read the daily rates setup including the
        cancellation policy and minimum guarantee per day for the\r\n            specified
        rateplan. You can specify a timeperiod to read the daily rates for. The rateplan
        needs to be active for at least\r\n            one business day in the defined
        time period and have rates loaded."
      operationId: RatePlans_GetRates
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderates-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: expand
        description: You can expand the supplements per room type on demand
      - in: query
        name: from
        description: Defines the last business day you would like to get rates for
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: query
        name: inlinecount
        description: Return total number of items for a given filter criteria
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to see details for
      - in: query
        name: skip
        description: Amount of items to skip
      - in: query
        name: to
        description: Defines the first business day you would like to get rates for
      - in: query
        name: top
        description: Amount of items to select
      responses:
        200:
          description: OK
      tags:
      - Setup
      - Of
      - Daily
      - Ratesa
      - Specific
      - Rateplan
      - Defined
      - Timeperiod
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