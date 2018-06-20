---
name: Google Doubleclick
x-slug: google-doubleclick
description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
  to access and update account information and to submit creatives. The API also allows
  an application (whether it does static bidding or real-time bidding) to discover
  direct deals that sellers make available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/apis.md
specificationVersion: "0.14"
apis:
- name: Google Doubleclick API Get Dimensions
  x-api-slug: google-doubleclick-api
  description: List the metadata for the dimensions available to this AdExchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{accountId}/metadata/dimensions
  tags: Advertising,Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/accountsaccountidmetadatadimensions-get-openapi.md
- name: Google Doubleclick API Get Metrics
  x-api-slug: google-doubleclick-api
  description: List the metadata for the metrics available to this AdExchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{accountId}/metadata/metrics
  tags: Advertising,Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/accountsaccountidmetadatametrics-get-openapi.md
- name: Google Doubleclick API Get Metros
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of metros.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/metros
  tags: Advertising,Metro
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidmetros-get-openapi.md
- name: Google Doubleclick API Get Placement Groups
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of placement groups, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementGroups
  tags: Advertising,Placement Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-get-openapi.md
- name: Google Doubleclick API Update Placement Group
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement group. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementGroups
  tags: Advertising,Placement Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-patch-openapi.md
- name: Google Doubleclick API Insert Placement Group
  x-api-slug: google-doubleclick-api
  description: Inserts a new placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementGroups
  tags: Advertising,Placement Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-post-openapi.md
- name: Google Doubleclick API Update Placement Group
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementGroups
  tags: Advertising,Placement Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementgroups-put-openapi.md
- name: Google Doubleclick API Get Placement Group
  x-api-slug: google-doubleclick-api
  description: Gets one placement group by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementGroups/{id}
  tags: Advertising,Placement Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementgroupsid-get-openapi.md
- name: Google Doubleclick API Get Placement Strategies
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of placement strategies, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-get-openapi.md
- name: Google Doubleclick API Update Placement Strategy
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement strategy. This method supports patch
    semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-patch-openapi.md
- name: Google Doubleclick API Insert Placement Strategy
  x-api-slug: google-doubleclick-api
  description: Inserts a new placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-post-openapi.md
- name: Google Doubleclick API Update Placement Strategy
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategies-put-openapi.md
- name: Google Doubleclick API Delete Placement Strategy
  x-api-slug: google-doubleclick-api
  description: Deletes an existing placement strategy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies/{id}
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategiesid-delete-openapi.md
- name: Google Doubleclick API Get Placement Strategy
  x-api-slug: google-doubleclick-api
  description: Gets one placement strategy by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placementStrategies/{id}
  tags: Advertising,Placement Strategy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementstrategiesid-get-openapi.md
- name: Google Doubleclick API Get Placements
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of placements, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacements-get-openapi.md
- name: Google Doubleclick API Update Placement
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacements-patch-openapi.md
- name: Google Doubleclick API Insert Placement
  x-api-slug: google-doubleclick-api
  description: Inserts a new placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacements-post-openapi.md
- name: Google Doubleclick API Update Placement
  x-api-slug: google-doubleclick-api
  description: Updates an existing placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacements-put-openapi.md
- name: Google Doubleclick API Generate Placement Tag
  x-api-slug: google-doubleclick-api
  description: Generates tags for a placement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements/generatetags
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementsgeneratetags-post-openapi.md
- name: Google Doubleclick API Get Placement
  x-api-slug: google-doubleclick-api
  description: Gets one placement by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/placements/{id}
  tags: Advertising,Placement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplacementsid-get-openapi.md
- name: Google Doubleclick API Get Platform Types
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of platform types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/platformTypes
  tags: Advertising,Placement Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplatformtypes-get-openapi.md
- name: Google Doubleclick API Get Platform Type
  x-api-slug: google-doubleclick-api
  description: Gets one platform type by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/platformTypes/{id}
  tags: Advertising,Placement Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidplatformtypesid-get-openapi.md
- name: Google Doubleclick API Get Order Documents
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of order documents, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/projects/{projectId}/orderDocuments
  tags: Advertising,Order Document
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidorderdocuments-get-openapi.md
- name: Google Doubleclick API Get Order Document
  x-api-slug: google-doubleclick-api
  description: Gets one order document by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/projects/{projectId}/orderDocuments/{id}
  tags: Advertising,Order Document
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/userprofilesprofileidprojectsprojectidorderdocumentsid-get-openapi.md
- name: Google Doubleclick API
  x-api-slug: google-doubleclick-api
  description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
    to access and update account information and to submit creatives. The API also
    allows an application (whether it does static bidding or real-time bidding) to
    discover direct deals that sellers make available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-doubleclick/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/ad-exchange/buyer-rest/auth-guide
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/ad_exchange
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/ad-exchange/buyer-rest/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-doubleclick-ad-exchange-buyer-api
- type: x-getting-started
  url: https://developers.google.com/ad-exchange/buyer-rest/start
- type: x-support
  url: https://developers.google.com/ad-exchange/buyer-rest/community/
- type: x-website
  url: https://www.doubleclickbygoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---