---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 0
info:
  title: LH Public Shipment Tracking
  version: "1.0"
  description: With this tracking service you can easily retrieve your shipment or
    flight status information.
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cargo/shipmentTracking/{aWBPrefix}-{aWBNumber}:
    get:
      summary: Shipment Tracking
      description: With this tracking service you can easily retrieve your shipment
        or flight status information.
      operationId: CargoShipmentTrackingByAWBPrefixAndAWBNumberGet
      x-api-path-slug: cargoshipmenttrackingawbprefixawbnumber-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: aWBNumber
        description: 'aWBNumber : The Air Waybill Number , format : [0-9]{8} e'
      - in: path
        name: aWBPrefix
        description: 'aWBPrefix : Represents the airline that is the owner of this
          AWB, i'
      responses:
        200:
          description: OK
      tags:
      - Cargo
      - ShipmentTracking
      - AWBPrefix
      - AWBNumber
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