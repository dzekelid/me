---
name: OpenRouteService
x-slug: openrouteservice
description: OpenStreetMap is the free wiki world map.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
x-kinRank: "7"
x-alexaRank: "6266"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/apis.md
specificationVersion: "0.14"
apis:
- name: AP Content API Get Item Mediatype Rendition
  x-api-slug: ap-content-api
  description: Pulls item media
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2//item/{mediaType}/{id}/{rendition}
  tags: Item,Mediatype,Rendition
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/itemmediatypeidrendition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/itemmediatypeidrendition-get-openapi.md
- name: AP Content API Get Search Mediatype
  x-api-slug: ap-content-api
  description: Search news
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2//search/{mediaType}
  tags: Search,Mediatype
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/searchmediatype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/searchmediatype-get-openapi.md
- name: AP Content API
  x-api-slug: ap-content-api
  description: OpenStreetMap is the free wiki world map.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/882-openrouteservice.jpg
  humanURL: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
  baseURL: https://api.ap.org/v2/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/openrouteservice/openapi.md
x-common:
- type: x-website
  url: http://wiki.openstreetmap.org/wiki/OpenRouteService#ORS_.22API.22
- type: x-crunchbase
  url: https://crunchbase.com/organization/openstreetmap-3
- type: x-developer
  url: https://developer.ap.org/
- type: x-website
  url: http://ap.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---