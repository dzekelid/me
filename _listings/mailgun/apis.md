---
name: Mailgun
x-slug: mailgun
description: Mailgun provides a web service for integrating email inboxes into apps.
  Providing APIs for sending, receiving, and storing APis, including tools for managing
  delivery, real-time integration, organizing, routing, and tracking on emails. Malign
  provides a free trial to learn about services, and pay as you go, unit based pricing
  to continue from there, including volume pricing for increased usage.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
x-kinRank: "8"
x-alexaRank: "24750"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/apis.md
specificationVersion: "0.14"
apis:
- name: Mailgun API List Members
  x-api-slug: mailgun-api
  description: Fetches the list of mailing list members.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2//lists/{address}/members/
  tags: List,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/listsaddressmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/listsaddressmembers-get-openapi.md
- name: Mailgun API List Member
  x-api-slug: mailgun-api
  description: Retrieves a mailing list member.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2//lists/{address}/members/{member_address}
  tags: List,Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/listsaddressmembersmember-address-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/listsaddressmembersmember-address-get-openapi.md
- name: Mailgun API Posts Mime Message
  x-api-slug: mailgun-api
  description: 'Posts a message in MIME format. Note: you will need to build a MIME
    string yourself. Use a MIME library for your programming language to do this.
    Pass the resulting MIME string as message parameter.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2//messages.mime
  tags: S,Mime,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messages-mime-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messages-mime-post-openapi.md
- name: Mailgun API Send Message
  x-api-slug: mailgun-api
  description: Sends a message by assembling it from the components. Note that you
    can specify most parameters multiple times, HTTP supports this out of the box.
    This makes sense for parameters like cc, to or attachment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2//messages/
  tags: Send,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messages-post-openapi.md
- name: Mailgun API Message
  x-api-slug: mailgun-api
  description: Gets a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2//messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/messagesid-get-openapi.md
- name: Mailgun API
  x-api-slug: mailgun-api
  description: Mailgun is a set of powerful APIs that allow you to send, receive,
    track and store email effortlessly.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/612-mail_gun.jpg
  humanURL: http://mailgun.net
  baseURL: https://api.mailgun.net/v2/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/mailgun/openapi.md
x-common:
- type: x--net-library
  url: http://documentation.mailgun.com/libraries.html#c
- type: x-base
  url: https://api.mailgun.net
- type: x-blog
  url: http://blog.mailgun.net
- type: x-blog-rss
  url: https://twitter.com/unbounce
- type: x-crunchbase
  url: http://www.crunchbase.com/company/mailgun
- type: x-crunchbase
  url: https://crunchbase.com/organization/mailgun
- type: x-developer
  url: http://documentation.mailgun.com/
- type: x-email
  url: privacy@mailgun.com
- type: x-faq
  url: http://documentation.mailgun.com/faqs.html
- type: x-github
  url: https://github.com/mailgun
- type: x-heroku-addon
  url: https://addons.heroku.com/mailgun
- type: x-java-library
  url: http://documentation.mailgun.com/libraries.html#java
- type: x-node-js-library
  url: http://documentation.mailgun.com/libraries.html#node-js
- type: x-php-library
  url: http://documentation.mailgun.com/libraries.html#php
- type: x-pricing
  url: http://www.mailgun.com/pricing
- type: x-privacy
  url: http://www.mailgun.com/privacy
- type: x-python-library
  url: http://documentation.mailgun.com/libraries.html#python
- type: x-ruby-library
  url: http://documentation.mailgun.com/libraries.html#ruby
- type: x-selfservice-registration
  url: https://www.mailgun.com/signup
- type: x-stack-overflow
  url: https://stackoverflow.com/questions/tagged/mailgun
- type: x-terms-of-service
  url: http://www.mailgun.com/terms
- type: x-twitter
  url: https://twitter.com/#!/mail_gun
- type: x-website
  url: http://mailgun.net
- type: x-wordpress-plugin
  url: https://wordpress.org/plugins/mailgun/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---