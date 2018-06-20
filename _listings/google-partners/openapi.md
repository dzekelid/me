---
swagger: "2.0"
x-collection-name: Google Partners
x-complete: 1
info:
  title: Google Partners
  description: searches-certified-companies-and-creates-contact-leads-with-them-and-also-audits-the-usage-of-clients-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: partners.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/clientMessages:log:
    post:
      summary: Get Generic Message Log
      description: |-
        Logs a generic message from the client, such as
        `Failed to render component`, `Profile page is running slow`,
        `More than 500 users have accessed this result.`, etc.
      operationId: partners.clientMessages.log
      x-api-path-slug: v2clientmessageslog-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Message
---