---
name: Postmark
x-slug: postmark
description: Trusted by thousands of developers, Postmark is a fast and reliable transactional
  email service. Send with Postmark to ensure your transactional emails get to the
  inbox on time, every time.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
x-kinRank: "8"
x-alexaRank: "92150"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/apis.md
specificationVersion: "0.14"
apis:
- name: Postmark Get Messages Inbound
  x-api-slug: postmark
  description: Get messages inbound.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/inbound
  tags: Messages,Inbound
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesinbound-get-openapi.md
- name: Postmark Put Messages Inbound Message Bypass
  x-api-slug: postmark
  description: Put messages inbound message bypass.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/inbound/{messageid}/bypass
  tags: Messages,Inbound,Messageid,Bypass
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesinboundmessageidbypass-put-openapi.md
- name: Postmark Get Messages Inbound Message Details
  x-api-slug: postmark
  description: Get messages inbound message details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/inbound/{messageid}/details
  tags: Messages,Inbound,Messageid,Details
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesinboundmessageiddetails-get-openapi.md
- name: Postmark Put Messages Inbound Message Retry
  x-api-slug: postmark
  description: Put messages inbound message retry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/inbound/{messageid}/retry
  tags: Messages,Inbound,Messageid,Retry
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesinboundmessageidretry-put-openapi.md
- name: Postmark Get Messages Outbound
  x-api-slug: postmark
  description: Get messages outbound.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound
  tags: Messages,Outbound
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutbound-get-openapi.md
- name: Postmark Get Messages Outbound Clicks
  x-api-slug: postmark
  description: Get messages outbound clicks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/clicks
  tags: Messages,Outbound,Clicks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundclicks-get-openapi.md
- name: Postmark Get Messages Outbound Clicks Message
  x-api-slug: postmark
  description: Get messages outbound clicks message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/clicks/{messageid}
  tags: Messages,Outbound,Clicks,Messageid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundclicksmessageid-get-openapi.md
- name: Postmark Get Messages Outbound Opens
  x-api-slug: postmark
  description: Get messages outbound opens.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/opens
  tags: Messages,Outbound,Opens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundopens-get-openapi.md
- name: Postmark Get Messages Outbound Opens Message
  x-api-slug: postmark
  description: Get messages outbound opens message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/opens/{messageid}
  tags: Messages,Outbound,Opens,Messageid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundopensmessageid-get-openapi.md
- name: Postmark Get Messages Outbound Message Details
  x-api-slug: postmark
  description: Get messages outbound message details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/{messageid}/details
  tags: Messages,Outbound,Messageid,Details
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundmessageiddetails-get-openapi.md
- name: Postmark Get Messages Outbound Message Dump
  x-api-slug: postmark
  description: Get messages outbound message dump.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/{messageid}/dump
  tags: Messages,Outbound,Messageid,Dump
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/messagesoutboundmessageiddump-get-openapi.md
- name: Postmark Get Stats Outbound Opens Readtimes
  x-api-slug: postmark
  description: Get stats outbound opens readtimes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////stats/outbound/opens/readtimes
  tags: Stats,Outbound,Opens,Readtimes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/statsoutboundopensreadtimes-get-openapi.md
- name: Postmark
  x-api-slug: postmark
  description: Postmark helps deliver and track transactional emails for web applications.
    In a nutshell, the service replaces SMTP (or Sendmail) with a far more reliable,
    scalable and care-free environment. In addition, you can track statistics for
    number of emails sent, bounces and spam complaints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/postmark/openapi.md
x-common:
- type: x--net-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#dot-net
- type: x-base
  url: https://api.postmarkapp.com
- type: x-blog
  url: http://blog.postmarkapp.com/
- type: x-blog-rss
  url: http://blog.postmarkapp.com/rss
- type: x-contact-form
  url: http://support.postmarkapp.com/customer/portal/emails/new
- type: x-crunchbase
  url: https://crunchbase.com/organization/postmark
- type: x-crunchbase
  url: http://www.crunchbase.com/company/postmark
- type: x-developer
  url: http://developer.postmarkapp.com/
- type: x-email
  url: support@postmarkapp.com
- type: x-email
  url: 451d9b70cf9364d23ff6f9d51d870251569e+ahoy@inbound.postmarkapp.com
- type: x-faq
  url: http://support.postmarkapp.com/
- type: x-pricing
  url: http://developer.postmarkapp.com/developer-api-messages.html
- type: x-privacy
  url: https://postmarkapp.com/privacy-policy
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#rails
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#ruby
- type: x-selfservice-registration
  url: https://postmarkapp.com/sign_up
- type: x-status
  url: http://status.postmarkapp.com/
- type: x-terms-of-service
  url: https://postmarkapp.com/terms-of-service
- type: x-twitter
  url: https://twitter.com/postmarkapp
- type: x-website
  url: http://postmarkapp.com
- type: x-website
  url: http://postmarkapp.com/
- type: x-wordpress-pdk
  url: http://developer.postmarkapp.com/developer-official-libs.html#wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---