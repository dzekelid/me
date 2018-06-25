---
name: Google Plus
x-slug: google-plus
description: Create a more engaging experience and connect with more users by integrating
  social into your web site. Show profile information, and relevant content and connections
  from circles. Let visitors recommend and share your content, and prompt friends
  to take specific actions on your site.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/apis.md
specificationVersion: "0.14"
apis:
- name: Google Plus Get Activity Comments
  x-api-slug: google-plus
  description: List all of the comments for an activity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
  humanURL: https://plus.google.com/
  baseURL: https://///activities/{activityId}/comments
  tags: Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/activitiesactivityidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/activitiesactivityidcomments-get-openapi.md
- name: Google Plus Get Comments
  x-api-slug: google-plus
  description: Get a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
  humanURL: https://plus.google.com/
  baseURL: https://///comments/{commentId}
  tags: Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/commentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/commentscommentid-get-openapi.md
- name: Google Plus Get Comment
  x-api-slug: google-plus
  description: Get a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
  humanURL: https://plus.google.com/
  baseURL: https://///comments/{commentId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/commentscommentid-get-openapi.md
- name: Google Plus Add Media To Collection
  x-api-slug: google-plus
  description: Add a new media item to an album. The current upload size limitations
    are 36MB for a photo and 1GB for a video. Uploads do not count against quota if
    photos are less than 2048 pixels on their longest side or videos are less than
    15 minutes in length.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
  humanURL: https://plus.google.com/
  baseURL: https://///people/{userId}/media/{collection}
  tags: Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/peopleuseridmediacollection-post-openapi.md
- name: Google Plus
  x-api-slug: google-plus
  description: Create a more engaging experience and connect with more users by integrating
    social into your web site. Show profile information, and relevant content and
    connections from circles. Let visitors recommend and share your content, and prompt
    friends to take specific actions on your site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-plus.png
  humanURL: https://plus.google.com/
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-plus/openapi.md
x-common:
- type: x-badges
  url: https://developers.google.com/+/web/badge/
- type: x-buttons
  url: https://developers.google.com/+/web/+1button/
- type: x-change-log
  url: https://developers.google.com/+/web/release-notes
- type: x-code
  url: https://developers.google.com/+/web/samples/javascript
- type: x-developer
  url: https://developers.google.com/+/web/api/rest/
- type: x-documentation
  url: https://developers.google.com/+/web/api/rest/latest/
- type: x-issues
  url: https://code.google.com/p/google-plus-platform/
- type: x-support
  url: https://developers.google.com/+/web/support
- type: x-terms-of-service
  url: https://developers.google.com/+/web/terms
- type: x-website
  url: https://plus.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---