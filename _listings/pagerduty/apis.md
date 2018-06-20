---
name: PagerDuty
x-slug: pagerduty
description: See how PagerDuty Digital Operations Management Platform integrates machine
  data & human intelligence to improve visibility & agility across organizations.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
x-kinRank: "8"
x-alexaRank: "19574"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/apis.md
specificationVersion: "0.14"
apis:
- name: PagerDuty List a user's contact methods
  x-api-slug: pagerduty
  description: List contact methods of your PagerDuty user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/usersidcontact-methods-get-openapi.md
- name: PagerDuty Create a user contact method
  x-api-slug: pagerduty
  description: Create a new contact method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/usersidcontact-methods-post-openapi.md
- name: PagerDuty Get a user's contact method
  x-api-slug: pagerduty
  description: Get details about a user's contact method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-get-openapi.md
- name: PagerDuty Delete a user's contact method
  x-api-slug: pagerduty
  description: Delete users  contact methods contact method
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-delete-openapi.md
- name: PagerDuty Update a user's contact method
  x-api-slug: pagerduty
  description: Put users  contact methods contact method
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/contact_methods/{contact_method_id}
  tags: User Contact Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/usersidcontact-methodscontact-method-id-put-openapi.md
- name: PagerDuty Creating a recipient
  x-api-slug: pagerduty
  description: Create recipients for your alert notifications
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///notifications/recipients
  tags: Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/notificationsrecipients-get-openapi.md
- name: PagerDuty
  x-api-slug: pagerduty
  description: See how PagerDuty Digital Operations Management Platform integrates
    machine data & human intelligence to improve visibility & agility across organizations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/pagerduty/openapi.md
x-common:
- type: x-base
  url: https://acme.pagerduty.com/api/
- type: x-blog
  url: http://blog.pagerduty.com/
- type: x-blog-rss
  url: http://blog.pagerduty.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pagerduty
- type: x-crunchbase
  url: https://crunchbase.com/organization/pagerduty
- type: x-developer
  url: http://developer.pagerduty.com/
- type: x-email
  url: info@pagerduty.com
- type: x-email
  url: sales@pagerduty.com
- type: x-email
  url: support@pagerduty.com
- type: x-email
  url: legal@pagerduty.com
- type: x-github
  url: https://github.com/PagerDuty
- type: x-openapi-spec--authoritative
  url: https://api-reference.pagerduty.com/output.json
- type: x-pricing
  url: https://www.pagerduty.com/pricing/
- type: x-twitter
  url: https://twitter.com/pagerduty
- type: x-website
  url: http://www.pagerduty.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---