---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Sync Volume Licenses
  description: Request downloaded content access for specified volumes on the My eBooks
    shelf.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /myconfig/syncVolumeLicenses:
    post:
      summary: Sync Volume Licenses
      description: Request downloaded content access for specified volumes on the
        My eBooks shelf.
      operationId: books.myconfig.syncVolumeLicenses
      x-api-path-slug: myconfigsyncvolumelicenses-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to release the restriction
      - in: query
        name: features
        description: List of features supported by the client, i
      - in: query
        name: includeNonComicsSeries
        description: Set to true to include non-comics series
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: nonce
        description: The client nonce value
      - in: query
        name: showPreorders
        description: Set to true to show pre-ordered books
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeIds
        description: The volume(s) to request download restrictions for
      responses:
        200:
          description: OK
      tags:
      - Volume License
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