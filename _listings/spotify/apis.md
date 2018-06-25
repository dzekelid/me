---
name: Spotify
x-slug: spotify
description: Spotify is a digital music service that gives you access to millions
  of songs.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
x-kinRank: "8"
x-alexaRank: "132"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/apis.md
specificationVersion: "0.14"
apis:
- name: Spotify Get Me
  x-api-slug: spotify
  description: '[Get Current User''s Profile](https://developer.spotify.com/web-api/get-current-users-profile/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me
  tags: Music,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/me-get-openapi.md
- name: Spotify Delete Following
  x-api-slug: spotify
  description: '[Unfollow Artists or Users](https://developer.spotify.com/web-api/unfollow-artists-users/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-delete-openapi.md
- name: Spotify Get Following
  x-api-slug: spotify
  description: '[Get User''s Followed Artists](https://developer.spotify.com/web-api/get-followed-artists/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-get-openapi.md
- name: Spotify Update Following
  x-api-slug: spotify
  description: '[Follow Artists or Users](https://developer.spotify.com/web-api/follow-artists-users/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowing-put-openapi.md
- name: Spotify Get Following contains
  x-api-slug: spotify
  description: '[Check if Current User Follows Artists or Users](https://developer.spotify.com/web-api/check-current-user-follows/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/following/contains
  tags: Music,Me,Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowingcontains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/mefollowingcontains-get-openapi.md
- name: Spotify Delete My Tracks
  x-api-slug: spotify
  description: '[Remove Tracks for Current User](https://developer.spotify.com/web-api/remove-tracks-user/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-delete-openapi.md
- name: Spotify Get My Tracks
  x-api-slug: spotify
  description: '[Get Current User''s Saved Tracks](https://developer.spotify.com/web-api/get-users-saved-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-get-openapi.md
- name: Spotify Update My Tracks
  x-api-slug: spotify
  description: '[Save Tracks for Current User](https://developer.spotify.com/web-api/save-tracks-user/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metracks-put-openapi.md
- name: Spotify Get My Track Contains
  x-api-slug: spotify
  description: '[Check Current User''s Saved Tracks](https://developer.spotify.com/web-api/check-users-saved-tracks/)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1//me/tracks/contains
  tags: Music,Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metrackscontains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/metrackscontains-get-openapi.md
- name: Spotify
  x-api-slug: spotify
  description: Spotify is a digital music service that gives you access to millions
    of songs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1165-spotify.jpg
  humanURL: http://www.spotify.com
  baseURL: https://api.spotify.com//v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/spotify/openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://developer.spotify.com/wp-content/uploads/apis.json
- type: x-android-sdk
  url: https://developer.spotify.com/technologies/spotify-android-sdk/
- type: x-application-gallery
  url: https://developer.spotify.com/my-applications/
- type: x-application-gallery
  url: https://developer.spotify.com/showcase/
- type: x-base-url
  url: https://api.spotify.com
- type: x-blog
  url: http://www.spotify.com/blog/
- type: x-blog-rss
  url: http://www.spotify.com/blog/feed
- type: x-change-log
  url: https://developer.spotify.com/web-api/change-log/
- type: x-console
  url: https://developer.spotify.com/web-api/console/
- type: x-crunchbase
  url: https://crunchbase.com/organization/spotify
- type: x-crunchbase
  url: http://www.crunchbase.com/company/spotify
- type: x-developer
  url: https://developer.spotify.com/
- type: x-email
  url: office@spotify.com
- type: x-ios-sdk
  url: https://developer.spotify.com/technologies/spotify-ios-sdk/
- type: x-issues
  url: https://github.com/spotify/web-api/issues
- type: x-linkedin
  url: https://www.linkedin.com/company/spotify/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/spotify
- type: x-terms-of-service
  url: https://developer.spotify.com/developer-terms-of-use/
- type: x-twitter
  url: https://twitter.com/SpotifyPlatform
- type: x-twitter
  url: https://twitter.com/spotify
- type: x-github
  url: https://github.com/spotify
- type: x-website
  url: http://www.spotify.com
- type: x-website
  url: http://spotify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---