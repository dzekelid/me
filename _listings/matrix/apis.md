---
name: Matrix
x-slug: matrix
description: An open standard for decentralised secure communication. Please support
  at https://t.co/oZd61hbMx3! | bridged to https://t.co/ujgzEXDSa4
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11769-matrix.jpg
x-kinRank: "8"
x-alexaRank: "156652"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/matrix/apis.md
specificationVersion: "0.14"
apis:
- name: Matrix Login Operations API Get the login mechanism to use when logging in.
  x-api-slug: matrix-login-operations-api
  description: All login stages MUST be mentioned if there is >1 login type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11769-matrix.jpg
  humanURL: http://matrix.org/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1//login
  tags: Login,Mechanism,To,Use,When,Logging,In
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/matrix/login-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/matrix/login-get-openapi.md
- name: Matrix Login Operations API
  x-api-slug: matrix-login-operations-api
  description: Matrix is an open standard for decentralised communication, providing
    simple HTTP APIs and open source reference implementations for securely distributing
    and persisting JSON over an open federation of servers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11769-matrix.jpg
  humanURL: http://matrix.org/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/matrix/openapi.md
x-common:
- type: x-blog
  url: http://matrix.org/blog/posts/
- type: x-blog-rss
  url: http://matrix.org/blog/comments/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/matrix-org
- type: x-github
  url: https://github.com/matrix-org
- type: x-twitter
  url: https://twitter.com/matrixdotorg
- type: x-website
  url: http://matrix.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---