---
swagger: "2.0"
x-collection-name: U.S. Digital Registry
x-complete: 0
info:
  title: U.S. Digital Registry Social Media API Social Media Token
  description: This returns tokens representing services, agencies, tags, and a basic
    text search token for the purpose of building search dialogs
  version: 1.0.0
host: usdigitalregistry.digitalgov.gov
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /social_media/verify.json:
    get:
      summary: Social Media Verify
      description: This returns an agency based on an URL. If not found, it will return
        a 404
      operationId: Api::V1::SocialMedia#verify
      x-api-path-slug: social-mediaverify-json-get
      parameters:
      - in: query
        name: url
        description: URL of social media account
      responses:
        200:
          description: OK
      tags:
      - Social Media
  /social_media/services.json:
    get:
      summary: Social Media Services
      description: This returns a list of services along with the number of accounts
        registered with them
      operationId: Api::V1::SocialMedia#services
      x-api-path-slug: social-mediaservices-json-get
      responses:
        200:
          description: OK
      tags:
      - Social Media
  /social_media/tokeninput.json:
    get:
      summary: Social Media Token
      description: This returns tokens representing services, agencies, tags, and
        a basic text search token for the purpose of building search dialogs
      operationId: Api::V1::SocialMedia#tokeninput
      x-api-path-slug: social-mediatokeninput-json-get
      parameters:
      - in: query
        name: q
        description: String to compare to the various values
      responses:
        200:
          description: OK
      tags:
      - Social Media
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