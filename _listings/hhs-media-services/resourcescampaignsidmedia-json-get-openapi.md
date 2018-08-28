---
swagger: "2.0"
x-collection-name: HHS Media Services
x-complete: 0
info:
  title: HHS Media Services Get MediaItems by Campaign ID
  description: Returns the list of MediaItems for the Campaign identified by the 'id'.
  termsOfService: http://www.hhs.gov/web/socialmedia/policies/tos.html#ready
  version: "2"
host: api.digitalmedia.hhs.gov
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /resources/campaigns/{id}/media.json:
    get:
      summary: Get MediaItems by Campaign ID
      description: Returns the list of MediaItems for the Campaign identified by the
        'id'.
      operationId: getMediaByCampaignId
      x-api-path-slug: resourcescampaignsidmedia-json-get
      parameters:
      - in: path
        name: id
        description: The id of the campaign to find media items for
      - in: query
        name: max
        description: The maximum number of records to return
      - in: query
        name: offset
        description: The offset of the records set to return for pagination
      - in: query
        name: sort
        description: The name of the property to which sorting will be applied
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Campaigns
      - Id
      - Media
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