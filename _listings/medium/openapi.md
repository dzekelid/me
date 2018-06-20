---
swagger: "2.0"
x-collection-name: Medium
x-complete: 1
info:
  title: Medium.com
  description: mediums-unofficial-api-documentation-using-openapi-specification--official-apiofficial-api-document-can-also-be-viewed-for-most-up-to-date-api-spec-at-httpsgithub-commediummediumapidocshttpsgithub-commediummediumapidocs-developer-blog--welcome-to-the-medium-apihttpsmedium-comblogwelcometothemediumapi3418f956552
  termsOfService: https://medium.com/@feerst/2b405a832a2f
  contact:
    name: Hossain Khan
    url: https://github.com/amardeshbd/medium-api-specification
  version: 1.0.0
host: api.medium.com
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
      summary: User details
      description: Returns details of the user who has granted permission to the application.
      operationId: me.get
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me
---