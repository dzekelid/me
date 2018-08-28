---
name: Spreaker
x-slug: spreaker
description: Discover and listen to your favorite podcasts for free or sign up to
  create your own!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
x-kinRank: "8"
x-alexaRank: "12286"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/apis.md
specificationVersion: "0.14"
apis:
- name: Spreaker API Get Episode Media List
  x-api-slug: spreaker-api
  description: Get Episode Media List
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////episode/{episode_id}/media
  tags: Episode,Media,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/episodeepisode-idmedia-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/episodeepisode-idmedia-get-openapi.md
- name: Spreaker API Create Media
  x-api-slug: spreaker-api
  description: Upload a new Media in the specified user library
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}
  tags: Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-id-post-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/effects/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-ideffectsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-ideffectsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/jingles/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idjinglesowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idjinglesowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/loops/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idloopsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idloopsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/songs/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idsongsowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idsongsowned-get-openapi.md
- name: Spreaker API Get Owned Media
  x-api-slug: spreaker-api
  description: Get a paginated list of media owned by <user_id> filtered by type:.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////library/{user_id}/soundtracks/owned
  tags: Owned,Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idsoundtracksowned-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/libraryuser-idsoundtracksowned-get-openapi.md
- name: Spreaker API Get Media
  x-api-slug: spreaker-api
  description: Retrieves a Media by unique identifier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com////media/{media_id}
  tags: Media
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/mediamedia-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/mediamedia-id-get-openapi.md
- name: Spreaker API
  x-api-slug: spreaker-api
  description: Spreaker platform enables you to host and listen thousands of radio
    shows. Spreaker provides a REST web service that enables developers to read and
    write data to Spreaker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/657-spreaker.jpg
  humanURL: http://spreaker.com
  baseURL: http://api.spreaker.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spreaker/openapi.md
x-common:
- type: x-base
  url: http://api.spreaker.com/
- type: x-blog
  url: http://blog.spreaker.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/spreaker
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spreaker
- type: x-developer
  url: http://developers.spreaker.com
- type: x-email
  url: info@spreaker.com
- type: x-email
  url: support@spreaker.com
- type: x-email
  url: advertise@spreaker.com
- type: x-email
  url: tonia.maffeo@spreaker.com
- type: x-email
  url: press@spreaker.com
- type: x-email
  url: legal@Spreaker.com
- type: x-github
  url: https://github.com/spreaker
- type: x-linkedin
  url: https://www.linkedin.com/company/spreaker/
- type: x-pricing
  url: http://www.spreaker.com/plans
- type: x-twitter
  url: https://twitter.com/spreaker
- type: x-website
  url: http://spreaker.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---