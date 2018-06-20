---
swagger: "2.0"
x-collection-name: Google Cloud Pub Sub
x-complete: 0
info:
  title: Google Cloud Pub/Sub API Pull Message
  description: |-
    Pulls messages from the server. Returns an empty list if there are no
    messages available in the backlog. The server may return `UNAVAILABLE` if
    there are too many concurrent pull requests pending for the given
    subscription.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: pubsub.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{subscription}:pull:
    post:
      summary: Pull Message
      description: |-
        Pulls messages from the server. Returns an empty list if there are no
        messages available in the backlog. The server may return `UNAVAILABLE` if
        there are too many concurrent pull requests pending for the given
        subscription.
      operationId: pubsub.projects.subscriptions.pull
      x-api-path-slug: v1subscriptionpull-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: subscription
        description: The subscription from which messages should be pulled
      responses:
        200:
          description: OK
      tags:
      - Message
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