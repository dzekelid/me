---
swagger: "2.0"
x-collection-name: Google Cloud Pub Sub
x-complete: 1
info:
  title: Google Cloud Pub/Sub
  description: provides-reliable-manytomany-asynchronous-messaging-between-applications-
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
---