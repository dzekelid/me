---
swagger: "2.0"
x-collection-name: Spotify
x-complete: 0
info:
  title: Spotify Delete Following
  description: '[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)'
  version: v1
host: api.spotify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me:
    get:
      summary: Get Me
      description: '[Get Current User''s Profile](https://developer.spotify.com/web-api/get-current-users-profile/)'
      operationId: get-current-users-profilehttpsdeveloperspotifycomwebapigetcurrentusersprofile
      x-api-path-slug: me-get
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
  /me/following:
    delete:
      summary: Delete Following
      description: '[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)'
      operationId: unfollow-artists-or-usershttpsdeveloperspotifycomwebapiunfollowartistsusers
      x-api-path-slug: mefollowing-delete
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of the artists or users ids
      - in: query
        name: type
        description: The type to unfollow
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---