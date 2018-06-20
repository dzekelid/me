---
name: Google Glass
x-slug: google-glass
description: Glass is fundamentally different than existing mobile platforms in both
  design and use. Follow these principles when building Glassware to give users the
  best experience.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2017-03-16 at 11.10.43 PM.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/apis.md
specificationVersion: "0.14"
apis:
- name: Google Glass APIs Get Timelines
  x-api-slug: google-glass-apis
  description: Retrieves a list of timeline items for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline
  tags: Timeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timeline-get-openapi.md
- name: Google Glass APIs Update Timeline
  x-api-slug: google-glass-apis
  description: Inserts a new item into the timeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline
  tags: Timeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timeline-post-openapi.md
- name: Google Glass APIs Delete Timeline
  x-api-slug: google-glass-apis
  description: Deletes a timeline item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{id}
  tags: Timeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineid-delete-openapi.md
- name: Google Glass APIs Get Timeline
  x-api-slug: google-glass-apis
  description: Gets a single timeline item by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{id}
  tags: Timeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineid-get-openapi.md
- name: Google Glass APIs Update Timeline
  x-api-slug: google-glass-apis
  description: Updates a timeline item in place. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{id}
  tags: Timeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineid-patch-openapi.md
- name: Google Glass APIs Update Timeline
  x-api-slug: google-glass-apis
  description: Updates a timeline item in place.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{id}
  tags: Timeline Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineid-put-openapi.md
- name: Google Glass APIs Get Timeline Attachments
  x-api-slug: google-glass-apis
  description: Returns a list of attachments for a timeline item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{itemId}/attachments
  tags: Timeline Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineitemidattachments-get-openapi.md
- name: Google Glass APIs Add Timeline Attachment
  x-api-slug: google-glass-apis
  description: Adds a new attachment to a timeline item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{itemId}/attachments
  tags: Timeline Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineitemidattachments-post-openapi.md
- name: Google Glass APIs Delete Timeline Attachment
  x-api-slug: google-glass-apis
  description: Deletes an attachment from a timeline item.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{itemId}/attachments/{attachmentId}
  tags: Timeline Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineitemidattachmentsattachmentid-delete-openapi.md
- name: Google Glass APIs Get Timeline Attachment
  x-api-slug: google-glass-apis
  description: Retrieves an attachment on a timeline item by item ID and attachment
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1//timeline/{itemId}/attachments/{attachmentId}
  tags: Timeline Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/timelineitemidattachmentsattachmentid-get-openapi.md
- name: Google Glass APIs
  x-api-slug: google-glass-apis
  description: Glass is fundamentally different than existing mobile platforms in
    both design and use. Follow these principles when building Glassware to give users
    the best experience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 11.10.43 PM.png
  humanURL: https://developers.google.com/glass/
  baseURL: ://www.googleapis.com//mirror/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-glass/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/glass/develop/gdk/authentication
- type: x-best-practices
  url: https://developers.google.com/glass/distribute/best-practices
- type: x-getting-started
  url: https://developers.google.com/glass/develop/gdk/quick-start
- type: x-website
  url: https://developers.google.com/glass/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---