---
name: Swagger
x-slug: swagger
description: Swagger aides in development across the entire API lifecycle, from design
  and documentation, to test and deployment. Try it today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
x-kinRank: "8"
x-alexaRank: "23531"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swagger/apis.md
specificationVersion: "0.14"
apis:
- name: Swagger Generator Returns options for a server framework
  x-api-slug: swagger-generator
  description: Returns options for a server framework.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api//gen/servers/{framework}
  tags: Generate,Servers,Framework
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swagger/genserversframework-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swagger/genserversframework-get-openapi.md
- name: Swagger Generator Generates a server library
  x-api-slug: swagger-generator
  description: Accepts a `GeneratorInput` options map for spec location and generation
    options.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api//gen/servers/{framework}
  tags: Generate,Servers,Framework
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swagger/genserversframework-post-openapi.md
- name: Swagger Generator
  x-api-slug: swagger-generator
  description: Swagger aides in development across the entire API lifecycle, from
    design and documentation, to test and deployment. Try it today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swagger/openapi.md
x-common:
- type: x-blog
  url: http://swagger.io/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/swagger
- type: x-github
  url: https://github.com/swagger-api
- type: x-twitter
  url: https://twitter.com/SwaggerApi
- type: x-website
  url: http://swagger.io/
- type: x-website
  url: http://swagger.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---