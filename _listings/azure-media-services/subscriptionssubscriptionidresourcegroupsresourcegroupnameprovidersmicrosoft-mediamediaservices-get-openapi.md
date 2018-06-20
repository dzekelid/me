---
swagger: "2.0"
x-collection-name: Azure Media Services
x-complete: 0
info:
  title: Azure Media Services API Media Service List By Resource Group
  description: Lists all of the Media Services in a resource group.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.Media/CheckNameAvailability:
    post:
      summary: Media Service Check Name Availability
      description: Checks whether the Media Service resource name is available. The
        name must be globally unique.
      operationId: MediaService_CheckNameAvailability
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-mediachecknameavailability-post
      parameters:
      - in: body
        name: CheckNameAvailabilityInput
        description: Properties needed to check the availability of a name
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Media Service Name Availability
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Media/mediaservices:
    get:
      summary: Media Service List By Resource Group
      description: Lists all of the Media Services in a resource group.
      operationId: MediaService_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-mediamediaservices-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Media Service Resource Group
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