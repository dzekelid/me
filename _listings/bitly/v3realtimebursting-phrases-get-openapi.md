---
swagger: "2.0"
x-collection-name: Bitly
x-complete: 0
info:
  title: Bitly Domains API Get Realtime Bursting Phrases
  description: Returns phrases that are receiving an uncharacteristically high volume
    of click traffic, and the individual links (hashes) driving traffic to pages containing
    these phrases.
  version: 1.0.0
host: api-ssl.bitly.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/realtime/bursting_phrases:
    get:
      summary: Get Realtime Bursting Phrases
      description: Returns phrases that are receiving an uncharacteristically high
        volume of click traffic, and the individual links (hashes) driving traffic
        to pages containing these phrases.
      operationId: Get_realtime_bursting_phrases_
      x-api-path-slug: v3realtimebursting-phrases-get
      parameters:
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Realtime
      - Bursting
      - Phrases
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