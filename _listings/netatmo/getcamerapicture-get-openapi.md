---
swagger: "2.0"
x-collection-name: Netatmo
x-complete: 0
info:
  title: Netatmo Get Getcamerapicture
  description: Returns the snapshot associated to an event.
  termsOfService: https://dev.netatmo.com/dev/resources/legal/introduction
  contact:
    name: Netatmo
    email: contact-api@netatmo.com
  version: 1.1.1
host: api.netatmo.net
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /getcamerapicture:
    get:
      summary: Get Getcamerapicture
      description: Returns the snapshot associated to an event.
      operationId: getcamerapicture
      x-api-path-slug: getcamerapicture-get
      parameters:
      - in: query
        name: image_id
        description: id of the image (can be retrieved as id in face in Gethomedata,
          or as id in snapshot in Getnextevents, Getlasteventof and Geteventsuntil)
      - in: query
        name: key
        description: Security key to access snapshots
      responses:
        200:
          description: OK
      tags:
      - Cameras
      - ictures
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