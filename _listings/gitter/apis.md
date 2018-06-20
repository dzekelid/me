---
name: Gitter
x-slug: gitter
description: Gitter is a chat and networking platform that helps to manage, grow and
  connect communities through messaging, content and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
x-kinRank: "8"
x-alexaRank: "18282"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/apis.md
specificationVersion: "0.14"
apis:
- name: Gitter API List Room Messages
  x-api-slug: gitter-api
  description: List of messages in a room.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///rooms/:roomId/chatMessages
  tags: Rooms, Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessages-get-openapi.md
- name: Gitter API Get Room Message
  x-api-slug: gitter-api
  description: There is also a way to retrieve a single message using its id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///rooms/:roomId/chatMessages/:messageId
  tags: Rooms,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessagesmessageid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessagesmessageid-get-openapi.md
- name: Gitter API Send Message
  x-api-slug: gitter-api
  description: Send a message to a room.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///rooms/:roomId/chatMessages
  tags: Rooms,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessages-post-openapi.md
- name: Gitter API Update Message
  x-api-slug: gitter-api
  description: Update a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///rooms/:roomId/chatMessages/:chatMessageId
  tags: Rooms,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessageschatmessageid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/roomsroomidchatmessageschatmessageid-put-openapi.md
- name: Gitter API Get User Unread Items
  x-api-slug: gitter-api
  description: You can retrieve unread items and mentions using the following endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///user/:userId/rooms/:roomId/unreadItems
  tags: Users,Messages,Unread
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/useruseridroomsroomidunreaditems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/useruseridroomsroomidunreaditems-get-openapi.md
- name: Gitter API Mark Unread Items as Read
  x-api-slug: gitter-api
  description: There is an additional endpoint nested under rooms that you can use
    to mark chat messages as read.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https://///user/:userId/rooms/:roomId/unreadItems
  tags: Messages,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/useruseridroomsroomidunreaditems-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/useruseridroomsroomidunreaditems-post-openapi.md
- name: Gitter API
  x-api-slug: gitter-api
  description: Gitter is a chat and networking platform that helps to manage, grow
    and connect communities through messaging, content and discovery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gitter-logo.png
  humanURL: http://gitter.im
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gitter/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/gitter
- type: x-developer
  url: https://developer.gitter.im/docs/streaming-api
- type: x-github
  url: https://github.com/gitterHQ
- type: x-curated-source
  url: https://gitter.im/apiaryio/api-blueprint
- type: x-website
  url: http://gitter.im
- type: x-twitter
  url: https://twitter.com/gitchat
- type: x-website
  url: https://gitter.im
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---