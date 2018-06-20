---
swagger: "2.0"
x-collection-name: Authentiq Connect
x-complete: 1
info:
  title: Authentiq Connect
  description: authentiq-connect-oauth-2-0-and-openid-connect-api-reference-learn-about-authentiq-idhttpswww-authentiq-com-or-check-out-the-authentiq-connecthttpsdevelopers-authentiq-com-developer-documentation-
  termsOfService: https://www.authentiq.com/tos/
  contact:
    name: Team Authentiq
    url: https://www.authentiq.com/
    email: hello@authentiq.com
  version: "1.0"
host: connect.authentiq.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{client_id}/iframe:
    get:
      summary: Include a session iframe
      description: |-
        An OpenID Connect Session Management iframe to facilitate e.g. single sign-on or remote logouts.

        The iframe implements the OIDC postMessage-based [change notification protocol](http://openid.net/specs/openid-connect-session-1_0.html#ChangeNotification) via which a client can receive notifications about session state changes.

        See also:
        - [OIDC OP iframe](http://openid.net/specs/openid-connect-session-1_0.html#OPiframe)
      operationId: authorizeIframe
      x-api-path-slug: client-idiframe-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Client
      - Id
      - Iframe
---