---
name: Urban Airship
x-slug: urban-airship
description: A market-leading mobile app engagement, mobile analytics, mobile data
  integration and mobile wallet marketing solution.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
x-kinRank: "8"
x-alexaRank: "79571"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/apis.md
specificationVersion: "0.14"
apis:
- name: Urban Airship Get User User Messages
  x-api-slug: urban-airship
  description: Returns a list of messages and some metadata about them. It will also
    include some metadata about the user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages
  tags: User,User,Id,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessages-get-openapi.md
- name: Urban Airship Get User User Messages Unread
  x-api-slug: urban-airship
  description: Returns a list of unread message IDs and their URLs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/unread
  tags: User,User,Id,Messages,Unread
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesunread-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesunread-get-openapi.md
- name: Urban Airship Post User User Messages Unread
  x-api-slug: urban-airship
  description: Marks multiple messages as read at once. If a message has already been
    marked as read, it will be silently skipped.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/unread
  tags: User,User,Id,Messages,Unread
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesunread-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesunread-post-openapi.md
- name: Urban Airship Get User User Messages Message Message
  x-api-slug: urban-airship
  description: Gets a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/message/{message_id}
  tags: User,User,Id,Messages,Message,Message,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-id-get-openapi.md
- name: Urban Airship Delete User User Messages Message Message
  x-api-slug: urban-airship
  description: Deletes a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/message/{message_id}
  tags: User,User,Id,Messages,Message,Message,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-id-delete-openapi.md
- name: Urban Airship Get User User Messages Message Message Body
  x-api-slug: urban-airship
  description: Gets a message's body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/message/{message_id}/body
  tags: User,User,Id,Messages,Message,Message,Id,Body
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-idbody-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-idbody-get-openapi.md
- name: Urban Airship Post User User Messages Message Message Read
  x-api-slug: urban-airship
  description: Marks a message as read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/message/{message_id}/read
  tags: User,User,Id,Messages,Message,Message,Id,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-idread-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesmessagemessage-idread-post-openapi.md
- name: Urban Airship Post User User Messages Delete
  x-api-slug: urban-airship
  description: Deletes multiple messages at once. If a message has already been deleted,
    it will be silently skipped.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api///user/{user_id}/messages/delete
  tags: User,User,Id,Messages,Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/useruser-idmessagesdelete-post-openapi.md
- name: Urban Airship
  x-api-slug: urban-airship
  description: The Urban Airship Push API is a major update which unifies several
    legacy endpoints into two&mdash; one for sending messages and one for scheduling.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/75-urban-airship.jpg
  humanURL: http://urbanairship.com/
  baseURL: https://go.urbanairship.com//api/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/urban-airship/openapi.md
x-common:
- type: x-website
  url: http://urbanairship.com/
- type: x-android-sdk
  url: http://docs.urbanairship.com/platform/android.html
- type: x-blackberry-sdk
  url: http://docs.urbanairship.com/platform/blackberry.html
- type: x-blog
  url: http://urbanairship.com/blog
- type: x-blog-rss
  url: http://urbanairship.com/blog/rss
- type: x-case-studies
  url: http://urbanairship.com/resources/case-studies
- type: x-crunchbase
  url: http://www.crunchbase.com/company/urban-airship
- type: x-crunchbase
  url: https://crunchbase.com/organization/urban-airship
- type: x-developer
  url: http://docs.urbanairship.com/
- type: x-email
  url: legal@urbanairship.com
- type: x-email
  url: privacy@urbanairship.com
- type: x-email
  url: support@urbanairship.com
- type: x-github
  url: https://github.com/urbanairship
- type: x-glossary
  url: http://docs.urbanairship.com/reference/glossary.html
- type: x-ios-sdk
  url: http://docs.urbanairship.com/platform/ios.html
- type: x-linkedin
  url: https://www.linkedin.com/company/urban-airship/
- type: x-phonegap-sdk
  url: http://docs.urbanairship.com/platform/phonegap.html
- type: x-pricing
  url: https://www.urbanairship.com/products/engage/pricing
- type: x-privacy
  url: http://urbanairship.com/legal/privacy-policy
- type: x-security
  url: http://docs.urbanairship.com/reference/app_keys_secrets.html
- type: x-twitter
  url: https://twitter.com/urbanairship
- type: x-website
  url: http://urbanairship.com
- type: x-white-papers
  url: http://urbanairship.com/resources/whitepapers
- type: x-windows-sdk
  url: http://docs.urbanairship.com/platform/windows.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---