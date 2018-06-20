---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 1
info:
  title: Data.gov API
  description: the-data-gov-catalog-is-powered-by-ckan-a-powerful-open-source-data-platform-that-includes-a-robust-api--please-be-aware-that-data-gov-and-the-data-gov-ckan-api-only-contain-metadata-about-datasets--this-metadata-includes-urls-and-descriptions-of-datasets-but-it-does-not-include-the-actual-data-within-each-dataset-
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
    put:
      summary: Put Organizations Org Member User
      description: Update member status into a given organization
      operationId: putOrganizationsOrgMemberUser
      x-api-path-slug: organizationsorgmemberuser-put
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
  /organizations/{org}/membership/:
    get:
      summary: Get Organizations Org Membership
      description: List membership requests for a given organization
      operationId: getOrganizationsOrgMembership
      x-api-path-slug: organizationsorgmembership-get
      parameters:
      - in: path
        name: org
        description: The organization ID or slug
      - in: query
        name: status
        description: If provided, only return requests ith a given status
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Membership
    post:
      summary: Add Organizations Org Membership
      description: Apply for membership to a given organization
      operationId: postOrganizationsOrgMembership
      x-api-path-slug: organizationsorgmembership-post
      parameters:
      - in: path
        name: org
        description: The organization ID or slug
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Membership
  /organizations/{org}/membership/{id}/accept/:
    post:
      summary: Add Organizations Org Membership  Accept
      description: Accept user membership to a given organization
      operationId: postOrganizationsOrgMembershipAccept
      x-api-path-slug: organizationsorgmembershipidaccept-post
      parameters:
      - in: path
        name: id
      - in: path
        name: org
        description: The organization ID or slug
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Membership
      - ""
      - Accept
  /organizations/{org}/membership/{id}/refuse/:
    post:
      summary: Add Organizations Org Membership  Refuse
      description: Refuse user membership to a given organization
      operationId: postOrganizationsOrgMembershipRefuse
      x-api-path-slug: organizationsorgmembershipidrefuse-post
      parameters:
      - in: body
        name: comment
        description: The refusal reason
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: path
        name: org
        description: The organization ID or slug
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Membership
      - ""
      - Refuse
  /site/home/datasets/:
    get:
      summary: Get Site Home Datasets
      description: List homepage datasets
      operationId: getSiteHomeDatasets
      x-api-path-slug: sitehomedatasets-get
      responses:
        200:
          description: OK
      tags:
      - Site
      - Home
      - Datasets
    put:
      summary: Put Site Home Datasets
      description: Set the homepage datasets editorial selection
      operationId: putSiteHomeDatasets
      x-api-path-slug: sitehomedatasets-put
      parameters:
      - in: body
        name: payload
        description: Dataset IDs to put in homepage
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Site
      - Home
      - Datasets
  /site/home/reuses/:
    get:
      summary: Get Site Home Reuses
      description: List homepage featured reuses
      operationId: getSiteHomeReuses
      x-api-path-slug: sitehomereuses-get
      responses:
        200:
          description: OK
      tags:
      - Site
      - Home
      - Reuses
    put:
      summary: Put Site Home Reuses
      description: Set the homepage reuses editorial selection
      operationId: putSiteHomeReuses
      x-api-path-slug: sitehomereuses-put
      parameters:
      - in: body
        name: payload
        description: Reuse IDs to put in homepage
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Site
      - Home
      - Reuses
---