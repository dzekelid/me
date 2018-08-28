---
name: Plivo
x-slug: plivo
description: 'Voice & SMS API Platform: Plivo enables businesses and developers to
  tap into powerful Voice and SMS capabilities without carrier lock-in.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
x-kinRank: "8"
x-alexaRank: "130970"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/apis.md
specificationVersion: "0.14"
apis:
- name: Codenvy Account API Get Account Memberships
  x-api-slug: codenvy-account-api
  description: ID of a user should be specified as a query parameter. JSON with membership
    details is returned. For this API call system/admin or system/manager role is
    required
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/memberships
  tags: Account,Memberships
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/accountmemberships-get-openapi.md
- name: Codenvy Account API Get Account Members
  x-api-slug: codenvy-account-api
  description: Get all members for a specific account. This API call requires account/owner,
    system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members
  tags: Account,Id,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/accountidmembers-get-openapi.md
- name: Codenvy Account API Post Account Members
  x-api-slug: codenvy-account-api
  description: Add a new user to an account. This user will have account/member role.
    This API call requires account/owner, system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members
  tags: Account,Id,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/accountidmembers-post-openapi.md
- name: Codenvy Account API Delete Account Members User
  x-api-slug: codenvy-account-api
  description: Remove user from a specific account. This API call requires account/owner,
    system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members/{userid}
  tags: Account,Id,Members,Userid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/accountidmembersuserid-delete-openapi.md
- name: Codenvy Account API Post Blogs Comments
  x-api-slug: codenvy-account-api
  description: Creates a comment for the Story.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//blogs/:id/comments
  tags: Blogs,:id,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/blogsidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/blogsidcomments-post-openapi.md
- name: Codenvy Account API Post Comments Comments
  x-api-slug: codenvy-account-api
  description: Creates a reply to an existing comment. Comments can only be nested
    one level deep, you cannot reply to a reply of a comment. If a comment has a non-null
    parent_id value then it cannot be replied to.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//comments/:id/comments
  tags: Comments,:id,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/commentsidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/commentsidcomments-post-openapi.md
- name: Codenvy Account API Post Photos Comments
  x-api-slug: codenvy-account-api
  description: Creates a new comment for the photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//photos/:id/comments
  tags: Photos,:id,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/photosidcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/photosidcomments-post-openapi.md
- name: Codenvy Account API
  x-api-slug: codenvy-account-api
  description: 'Voice & SMS API Platform: Plivo enables businesses and developers
    to tap into powerful Voice and SMS capabilities without carrier lock-in.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/openapi.md
- name: Plivo SMS Message
  x-api-slug: plivo-sms
  description: Get details of a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: https://api.plivo.com/v1//{auth_id}/Message/
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessage-get-openapi.md
- name: Plivo SMS Send Message
  x-api-slug: plivo-sms
  description: This API enables you to send messages via Plivou2019s SMS service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: https://api.plivo.com/v1//{auth_id}/Message/
  tags: Send,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessage-post-openapi.md
- name: Plivo SMS Message
  x-api-slug: plivo-sms
  description: Get details of a single message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: https://api.plivo.com/v1//{auth_id}/Message/{message_uuid}/
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessagemessage-uuid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/auth-idmessagemessage-uuid-get-openapi.md
- name: Plivo SMS
  x-api-slug: plivo-sms
  description: Plivo provides web developers with basic building blocks in the form
    of Plivo XML and HTTP API, to create telephony apps, so developers can completely
    do away with learning the nitty-gritty of the telephony plumbing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: https://api.plivo.com/v1/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/plivo/openapi.md
x-common:
- type: x--net-library
  url: https://www.plivo.com/docs/helpers/dotnet/
- type: x-android-sdk
  url: https://www.plivo.com/docs/sdk/android/
- type: x-base
  url: https://api.plivo.com
- type: x-blog
  url: http://blog.plivo.com
- type: x-blog-rss
  url: http://blog.plivo.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/plivo
- type: x-crunchbase
  url: http://www.crunchbase.com/company/plivo
- type: x-documentation
  url: https://plivo.com/docs/
- type: x-email
  url: marketing@plivo.com
- type: x-email
  url: legalrequests@plivo.com
- type: x-email
  url: privacy@plivo.com
- type: x-faq
  url: https://plivo.com/faq/
- type: x-github
  url: https://github.com/plivo
- type: x-ios-sdk
  url: https://www.plivo.com/docs/sdk/ios/
- type: x-java-sdk
  url: https://www.plivo.com/docs/helpers/java/
- type: x-linkedin
  url: https://www.linkedin.com/company/plivo-inc/
- type: x-node-js-library
  url: https://www.plivo.com/docs/helpers/node/
- type: x-php-sdk
  url: https://www.plivo.com/docs/helpers/php/
- type: x-pricing
  url: https://plivo.com/pricing/
- type: x-privacy
  url: https://plivo.com/privacy/
- type: x-ruby-library
  url: https://www.plivo.com/docs/helpers/python
- type: x-selfservice-registration
  url: https://manage.plivo.com/accounts/register/
- type: x-status
  url: https://status.plivo.com/
- type: x-terms-of-service
  url: https://plivo.com/terms/
- type: x-twitter
  url: https://twitter.com/plivo
- type: x-website
  url: http:///account
- type: x-website
  url: http://plivo.com
- type: x-website
  url: https://www.plivo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---