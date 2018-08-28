swagger: "2.0"
x-collection-name: MotaWord
x-complete: 1
info:
  title: Mota Word
  description: use-motaword-api-to-post-and-track-your-translation-projects-
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Get your account information and summary.
      description: Get your account information and summary..
      operationId: getAccount
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me