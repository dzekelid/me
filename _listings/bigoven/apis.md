---
name: BigOven
x-slug: bigoven
description: Free recipe app for home cooks. Create a meal plan, grocery list and
  more from your favorite recipes. Organize your recipe collection and take it anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
x-kinRank: "8"
x-alexaRank: "117577"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/bigoven/apis.md
specificationVersion: "0.14"
apis:
- name: Big Oven Gets a recipe collection metadata. A recipe collection is a curated
    set of recipes.
  x-api-slug: big-oven
  description: Gets a recipe collection metadata. a recipe collection is a curated
    set of recipes..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////collection/{id}/meta
  tags: Recipes,Collection,Meta
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/bigoven/collectionidmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/bigoven/collectionidmeta-get-openapi.md
- name: Big Oven Departmentalize a list of strings -- used for ad-hoc grocery list
    item addition
  x-api-slug: big-oven
  description: Departmentalize a list of strings -- used for ad-hoc grocery list item
    addition.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com////grocerylist/department
  tags: Recipes,Grocerylist,Department
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/bigoven/grocerylistdepartment-post-openapi.md
- name: Big Oven
  x-api-slug: big-oven
  description: Free recipe app for home cooks. Create a meal plan, grocery list and
    more from your favorite recipes. Organize your recipe collection and take it anywhere.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/bigoven/openapi.md
x-common:
- type: x-website
  url: http://www.bigoven.com
- type: x-base
  url: http://api.bigoven.com/
- type: x-blog
  url: http://blog.bigoven.com/
- type: x-blog-rss
  url: http://blog.bigoven.com/index.php/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/bigoven
- type: x-crunchbase
  url: http://www.crunchbase.com/company/bigoven
- type: x-developer
  url: http://api.bigoven.com
- type: x-documentation
  url: http://api2.bigoven.com/
- type: x-email
  url: support@bigoven.com
- type: x-twitter
  url: https://twitter.com/bigoven
- type: x-website
  url: http://bigoven.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---