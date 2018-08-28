---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Media
  description: Return an image for a given id.
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /checkout_settings/methods/:
    get:
      summary: Get Checkout Settings Methods
      description: Get the available checkout methods to do payments given a country
        and a currency.
      operationId: getCheckoutSettingsMethods
      x-api-path-slug: checkout-settingsmethods-get
      parameters:
      - in: query
        name: country
        description: Expected methods for Country
        type: query
      - in: query
        name: currency
        description: Expected methods for Currency
        type: query
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Settings
      - Methods
  /media/{id}/:
    get:
      summary: Get Media
      description: Return an image for a given id.
      operationId: getMedia
      x-api-path-slug: mediaid-get
      parameters:
      - in: query
        name: height
        description: Optional thumbnail height (you can specify only this value or
          also width)
        type: query
      - in: query
        name: width
        description: Optional thumbnail width (you can specify only this value or
          also height)
        type: query
      responses:
        200:
          description: OK
      tags:
      - Media
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