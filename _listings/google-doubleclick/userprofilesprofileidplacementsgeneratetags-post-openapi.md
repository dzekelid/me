---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Generate Placement Tag
  version: 1.0.0
  description: Generates tags for a placement.
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
    post:
      summary: Insert Placement Group
      description: Inserts a new placement group.
      operationId: dfareporting.placementGroups.insert
      x-api-path-slug: userprofilesprofileidplacementgroups-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Group
    put:
      summary: Update Placement Group
      description: Updates an existing placement group.
      operationId: dfareporting.placementGroups.update
      x-api-path-slug: userprofilesprofileidplacementgroups-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Group
  /userprofiles/{profileId}/placementGroups/{id}:
    get:
      summary: Get Placement Group
      description: Gets one placement group by ID.
      operationId: dfareporting.placementGroups.get
      x-api-path-slug: userprofilesprofileidplacementgroupsid-get
      parameters:
      - in: path
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
  /userprofiles/{profileId}/placementStrategies:
    get:
      summary: Get Placement Strategies
      description: Retrieves a list of placement strategies, possibly filtered. This
        method supports paging.
      operationId: dfareporting.placementStrategies.list
      x-api-path-slug: userprofilesprofileidplacementstrategies-get
      parameters:
      - in: query
        name: ids
        description: Select only placement strategies with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
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
      - Placement Strategy
    patch:
      summary: Update Placement Strategy
      description: Updates an existing placement strategy. This method supports patch
        semantics.
      operationId: dfareporting.placementStrategies.patch
      x-api-path-slug: userprofilesprofileidplacementstrategies-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Placement strategy ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Strategy
    post:
      summary: Insert Placement Strategy
      description: Inserts a new placement strategy.
      operationId: dfareporting.placementStrategies.insert
      x-api-path-slug: userprofilesprofileidplacementstrategies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Strategy
    put:
      summary: Update Placement Strategy
      description: Updates an existing placement strategy.
      operationId: dfareporting.placementStrategies.update
      x-api-path-slug: userprofilesprofileidplacementstrategies-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Strategy
  /userprofiles/{profileId}/placementStrategies/{id}:
    delete:
      summary: Delete Placement Strategy
      description: Deletes an existing placement strategy.
      operationId: dfareporting.placementStrategies.delete
      x-api-path-slug: userprofilesprofileidplacementstrategiesid-delete
      parameters:
      - in: path
        name: id
        description: Placement strategy ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Strategy
    get:
      summary: Get Placement Strategy
      description: Gets one placement strategy by ID.
      operationId: dfareporting.placementStrategies.get
      x-api-path-slug: userprofilesprofileidplacementstrategiesid-get
      parameters:
      - in: path
        name: id
        description: Placement strategy ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement Strategy
  /userprofiles/{profileId}/placements:
    get:
      summary: Get Placements
      description: Retrieves a list of placements, possibly filtered. This method
        supports paging.
      operationId: dfareporting.placements.list
      x-api-path-slug: userprofilesprofileidplacements-get
      parameters:
      - in: query
        name: advertiserIds
        description: Select only placements that belong to these advertisers
      - in: query
        name: archived
        description: Select only archived placements
      - in: query
        name: campaignIds
        description: Select only placements that belong to these campaigns
      - in: query
        name: compatibilities
        description: Select only placements that are associated with these compatibilities
      - in: query
        name: contentCategoryIds
        description: Select only placements that are associated with these content
          categories
      - in: query
        name: directorySiteIds
        description: Select only placements that are associated with these directory
          sites
      - in: query
        name: groupIds
        description: Select only placements that belong to these placement groups
      - in: query
        name: ids
        description: Select only placements with these IDs
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
        name: paymentSource
        description: Select only placements with this payment source
      - in: query
        name: placementStrategyIds
        description: Select only placements that are associated with these placement
          strategies
      - in: query
        name: pricingTypes
        description: Select only placements with these pricing types
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for placements by name or ID
      - in: query
        name: siteIds
        description: Select only placements that are associated with these sites
      - in: query
        name: sizeIds
        description: Select only placements that are associated with these sizes
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
      - Placement
    patch:
      summary: Update Placement
      description: Updates an existing placement. This method supports patch semantics.
      operationId: dfareporting.placements.patch
      x-api-path-slug: userprofilesprofileidplacements-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Placement ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement
    post:
      summary: Insert Placement
      description: Inserts a new placement.
      operationId: dfareporting.placements.insert
      x-api-path-slug: userprofilesprofileidplacements-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement
    put:
      summary: Update Placement
      description: Updates an existing placement.
      operationId: dfareporting.placements.update
      x-api-path-slug: userprofilesprofileidplacements-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement
  /userprofiles/{profileId}/placements/generatetags:
    post:
      summary: Generate Placement Tag
      description: Generates tags for a placement.
      operationId: dfareporting.placements.generatetags
      x-api-path-slug: userprofilesprofileidplacementsgeneratetags-post
      parameters:
      - in: query
        name: campaignId
        description: Generate placements belonging to this campaign
      - in: query
        name: placementIds
        description: Generate tags for these placements
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: tagFormats
        description: Tag formats to generate for these placements
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Placement
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