---
swagger: "2.0"
x-collection-name: Spotify
x-complete: 0
info:
  title: Spotify Get Following contains
  description: '[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)'
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
    get:
      summary: Get Following
      description: '[Get User''s Followed Artists](https://developer.spotify.com/web-api/get-followed-artists/)'
      operationId: get-users-followed-artistshttpsdeveloperspotifycomwebapigetfollowedartists
      x-api-path-slug: mefollowing-get
      parameters:
      - in: query
        name: after
        description: The last artist ID retrieved from the previous request
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: type
        description: The ID type, currently only artist is supported
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
    put:
      summary: Update Following
      description: '[Follow Artists or Users](https://developer.spotify.com/web-api/follow-artists-users/)'
      operationId: follow-artists-or-usershttpsdeveloperspotifycomwebapifollowartistsusers
      x-api-path-slug: mefollowing-put
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of the artists or users ids
      - in: query
        name: type
        description: The type to follow
      responses:
        200:
          description: OK
      tags:
      - Music
      - Me
      - Following
  /me/following/contains:
    get:
      summary: Get Following contains
      description: '[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)'
      operationId: check-if-current-user-follows-artists-or-usershttpsdeveloperspotifycomwebapicheckcurrentuserfollows
      x-api-path-slug: mefollowingcontains-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated string of the artists or users ids
      - in: query
        name: type
        description: The type to follow
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