---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetRealTimeVWAP:
    get:
      summary: Get Real Time VWAP
      description: Returns a real-time VWAP for a security based on all INET trades.
      operationId: GetRealTimeVWAP
      x-api-path-slug: getrealtimevwap-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Real
      - Time
      - VWAP
---