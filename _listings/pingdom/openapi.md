---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 1
info:
  title: Servertime API
  description: the-servertime-api-
  version: 1.0.0
host: api.pingdom.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? |2-

        /api/{version}/servertime
  : ? |2-

          get
    : summary: Get Current Server Time
      description: Get the current time of the API server.
      operationId: get-current-server-time
      x-api-path-slug: apiversionservertime-get
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
      tags:
      - Servertime
---