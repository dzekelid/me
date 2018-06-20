---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Update Placement Group
  version: 1.0.0
  description: Updates an existing placement group. This method supports patch semantics.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/metadata/dimensions:
    get:
      summary: Get Dimensions
      description: List the metadata for the dimensions available to this AdExchange
        account.
      operationId: adexchangeseller.accounts.metadata.dimensions.list
      x-api-path-slug: accountsaccountidmetadatadimensions-get
      parameters:
      - in: path
        name: accountId
        description: Account with visibility to the dimensions
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Dimension
  /accounts/{accountId}/metadata/metrics:
    get:
      summary: Get Metrics
      description: List the metadata for the metrics available to this AdExchange
        account.
      operationId: adexchangeseller.accounts.metadata.metrics.list
      x-api-path-slug: accountsaccountidmetadatametrics-get
      parameters:
      - in: path
        name: accountId
        description: Account with visibility to the metrics
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Metric
  /userprofiles/{profileId}/metros:
    get:
      summary: Get Metros
      description: Retrieves a list of metros.
      operationId: dfareporting.metros.list
      x-api-path-slug: userprofilesprofileidmetros-get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Metro
  /userprofiles/{profileId}/placementGroups:
    get:
      summary: Get Placement Groups
      description: Retrieves a list of placement groups, possibly filtered. This method
        supports paging.
      operationId: dfareporting.placementGroups.list
      x-api-path-slug: userprofilesprofileidplacementgroups-get
      parameters:
      - in: query
        name: advertiserIds
        description: Select only placement groups that belong to these advertisers
      - in: query
        name: archived
        description: Select only archived placements
      - in: query
        name: campaignIds
        description: Select only placement groups that belong to these campaigns
      - in: query
        name: contentCategoryIds
        description: Select only placement groups that are associated with these content
          categories
      - in: query
        name: directorySiteIds
        description: Select only placement groups that are associated with these directory
          sites
      - in: query
        name: ids
        description: Select only placement groups with these IDs
      - in: query
        name: maxEndDate
        description: Select only placements or placement groups whose end date is
          on or before the specified maxEndDate
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: maxStartDate
        description: Select only placements or placement groups whose start date is
          on or before the specified maxStartDate
      - in: query
        name: minEndDate
        description: Select only placements or placement groups whose end date is
          on or after the specified minEndDate
      - in: query
        name: minStartDate
        description: Select only placements or placement groups whose start date is
          on or after the specified minStartDate
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: query
        name: placementGroupType
        description: Select only placement groups belonging with this group type
      - in: query
        name: placementStrategyIds
        description: Select only placement groups that are associated with these placement
          strategies
      - in: query
        name: pricingTypes
        description: Select only placement groups with these pricing types
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for placement groups by name or ID
      - in: query
        name: siteIds
        description: Select only placement groups that are associated with these sites
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Group
    patch:
      summary: Update Placement Group
      description: Updates an existing placement group. This method supports patch
        semantics.
      operationId: dfareporting.placementGroups.patch
      x-api-path-slug: userprofilesprofileidplacementgroups-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Placement group ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Group
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