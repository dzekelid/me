---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 0
info:
  title: Data.gov API Add Organizations Org Member User
  description: Add a member into a given organization
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/:
    get:
      summary: Get Me
      description: Fetch the current user (me) identity
      operationId: getMe
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Me
    put:
      summary: Put Me
      description: Update my profile
      operationId: putMe
      x-api-path-slug: me-put
      responses:
        200:
          description: OK
      tags:
      - Me
  /me/apikey:
    delete:
      summary: Delete Me Apikey
      description: Clear/destroy an apikey
      operationId: deleteMeApikey
      x-api-path-slug: meapikey-delete
      responses:
        200:
          description: OK
      tags:
      - Me
      - Apikey
    post:
      summary: Add Me Apikey
      description: (Re)Generate my API Key
      operationId: postMeApikey
      x-api-path-slug: meapikey-post
      responses:
        200:
          description: OK
      tags:
      - Me
      - Apikey
  /me/avatar:
    post:
      summary: Add Me Avatar
      description: Upload a new avatar
      operationId: postMeAvatar
      x-api-path-slug: meavatar-post
      parameters:
      - in: formData
        name: bbox
      - in: formData
        name: file
      responses:
        200:
          description: OK
      tags:
      - Me
      - Avatar
  /me/datasets/:
    get:
      summary: Get Me Datasets
      description: List all my datasets (including private ones)
      operationId: getMeDatasets
      x-api-path-slug: medatasets-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Datasets
  /me/metrics/:
    get:
      summary: Get Me Metrics
      description: Fetch the current user (me) metrics
      operationId: getMeMetrics
      x-api-path-slug: memetrics-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Metrics
  /me/org_community_resources/:
    get:
      summary: Get Me Org Community Resources
      description: List all community resources related to me and my organizations
      operationId: getMeOrgCommunityResources
      x-api-path-slug: meorg-community-resources-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Community
      - Resources
  /me/org_datasets/:
    get:
      summary: Get Me Org Datasets
      description: List all datasets related to me and my organizations
      operationId: getMeOrgDatasets
      x-api-path-slug: meorg-datasets-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Datasets
  /me/org_discussions/:
    get:
      summary: Get Me Org Discussions
      description: List all discussions related to my organizations
      operationId: getMeOrgDiscussions
      x-api-path-slug: meorg-discussions-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Discussions
  /me/org_issues/:
    get:
      summary: Get Me Org Issues
      description: List all issues related to my organizations
      operationId: getMeOrgIssues
      x-api-path-slug: meorg-issues-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Issues
  /me/org_reuses/:
    get:
      summary: Get Me Org Reuses
      description: List all reuses related to me and my organizations
      operationId: getMeOrgReuses
      x-api-path-slug: meorg-reuses-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Reuses
  /me/reuses/:
    get:
      summary: Get Me Reuses
      description: List all my reuses (including private ones)
      operationId: getMeReuses
      x-api-path-slug: mereuses-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Reuses
  /metrics/{id}:
    get:
      summary: Get Metrics
      description: Fetch metrics for an object given its ID
      operationId: getMetrics
      x-api-path-slug: metricsid-get
      parameters:
      - in: query
        name: cumulative
        description: Either cumulative metrics or not
      - in: query
        name: day
        description: Specific day date to fetch
      - in: query
        name: end
        description: End of the period to fetch
      - in: path
        name: id
        description: The object ID to fetch metric for
      - in: query
        name: start
        description: Start of the period to fetch
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /organizations/{org}/member/{user}:
    delete:
      summary: Delete Organizations Org Member User
      description: Delete member from an organization
      operationId: deleteOrganizationsOrgMemberUser
      x-api-path-slug: organizationsorgmemberuser-delete
      parameters:
      - in: path
        name: org
        description: The organization ID or slug
      - in: path
        name: user
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Member
      - User
    post:
      summary: Add Organizations Org Member User
      description: Add a member into a given organization
      operationId: postOrganizationsOrgMemberUser
      x-api-path-slug: organizationsorgmemberuser-post
      parameters:
      - in: path
        name: org
        description: The organization ID or slug
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Member
      - User
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