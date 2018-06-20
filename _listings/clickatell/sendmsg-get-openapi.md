---
swagger: "2.0"
x-collection-name: Clickatell
x-complete: 0
info:
  title: Clickatell SMS Send Message
  description: The Clickatell HTTP/S API provides just about the simplest way of programming
    your connection to Clickatell, and if you need to overcome a firewall problem
    HTTP/S is almost certainly your best solution.
  termsOfService: https://www.clickatell.com/about-us/terms-and-conditions/?_ga=1.209522258.1120142809.1413957851
  version: v1
host: api.clickatell.com
basePath: http/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  sendmsg/:
    get:
      summary: Send Message
      description: The Clickatell HTTP/S API provides just about the simplest way
        of programming your connection to Clickatell, and if you need to overcome
        a firewall problem HTTP/S is almost certainly your best solution.
      operationId: getSendmsg
      x-api-path-slug: sendmsg-get
      parameters:
      - in: query
        name: api_id
      - in: query
        name: password
      - in: query
        name: text
      - in: query
        name: to
      - in: query
        name: user
        description: The user id sending message
      responses:
        200:
          description: OK
      tags:
      - Messaging
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