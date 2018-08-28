swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/me:
    get:
      summary: Get Me
      description: Get my details
      operationId: userMe
      x-api-path-slug: userme-get
      responses:
        200:
          description: OK
      tags:
      - Me