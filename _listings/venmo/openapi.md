swagger: "2.0"
x-collection-name: Venmo
x-complete: 1
info:
  title: Venmo API
  description: the-venmo-api-provides-developers-a-straightforward-way-to-integrate-venmo-into-their-applications--
  version: 1.0.0
host: api.venmo.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Get Me
      description: Get me.
      operationId: getMe
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me