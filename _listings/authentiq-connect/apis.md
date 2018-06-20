---
name: Authentiq Connect
x-slug: authentiq-connect
description: Authentiq offers the convenience of passwordless authentication with
  the safety of two step verification. Sign up for Authentiq today, and never think
  about authentication again.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/authentiq-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/authentiq-connect/apis.md
specificationVersion: "0.14"
apis:
- name: Authentiq Connect Include a session iframe
  x-api-slug: authentiq-connect
  description: |-
    An OpenID Connect Session Management iframe to facilitate e.g. single sign-on or remote logouts.

    The iframe implements the OIDC postMessage-based [change notification protocol](http://openid.net/specs/openid-connect-session-1_0.html#ChangeNotification) via which a client can receive notifications about session state changes.

    See also:
    - [OIDC OP iframe](http://openid.net/specs/openid-connect-session-1_0.html#OPiframe)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/authentiq-logo.png
  humanURL: http://authentiq.com
  baseURL: https://connect.authentiq.io////{client_id}/iframe
  tags: Client,Id,Iframe
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/authentiq-connect/client-idiframe-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/authentiq-connect/client-idiframe-get-openapi.md
- name: Authentiq Connect
  x-api-slug: authentiq-connect
  description: Authentiq offers the convenience of passwordless authentication with
    the safety of two step verification. Sign up for Authentiq today, and never think
    about authentication again.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/authentiq-logo.png
  humanURL: http://authentiq.com
  baseURL: https://connect.authentiq.io//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/authentiq-connect/openapi.md
x-common:
- type: x-website
  url: http://authentiq.com
- type: x-blog
  url: https://www.authentiq.com/blog/
- type: x-developer
  url: https://www.authentiq.com/developers/
- type: x-github
  url: https://github.com/AuthentiqID
- type: x-pricing
  url: https://www.authentiq.com/pricing/
- type: x-twitter
  url: AuthentiqID
- type: x-website
  url: http://authentiq.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---