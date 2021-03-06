---
swagger: "2.0"
x-collection-name: U.S. Digital Registry
x-complete: 1
info:
  title: U.S. Digital Registry Social Media API
  description: provides-access-to-the-social-media-accounts-for-top-federal-agencies-
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
  /social_media.json:
    get:
      summary: Social Media
      description: This lists all active accounts. It accepts parameters to perform
        basic search as well as search by service, agency, or tags.
      operationId: Api::V1::SocialMedia#index
      x-api-path-slug: social-media-json-get
      parameters:
      - in: query
        name: agencies
        description: Comma separated list of agency ids
      - in: query
        name: language
        description: Language of the social media accounts to return
      - in: query
        name: page
        description: Page number
      - in: query
        name: page_size
        description: Number of results per page, defaults to 25
      - in: query
        name: q
        description: String to compare to the name of accounts
      - in: query
        name: services
        description: Comma separated list of service keys (available via services
          call)
      - in: query
        name: tags
        description: Comma separated list of tag ids
      responses:
        200:
          description: OK
      tags:
      - Social Media
  /social_media/{id}.json:
    get:
      summary: Social Media
      description: This returns an agency based on an ID.
      operationId: Api::V1::SocialMedia#show
      x-api-path-slug: social-mediaid-json-get
      parameters:
      - in: path
        name: id
        description: ID of the account
      responses:
        200:
          description: OK
      tags:
      - Social Media
---