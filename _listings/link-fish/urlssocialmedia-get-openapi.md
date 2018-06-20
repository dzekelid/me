---
swagger: "2.0"
x-collection-name: link.fish
x-complete: 0
info:
  title: link.fish Get social media accounts
  description: |-
    Visits the URL and checks if there are any social media accounts and returns the found ones.

    Will by default return the account identifiers and not the full URL to the profiles. To return URLs instead set the parameter "return_urls" to true.

    The URLs can also be created manually like this:

    | Property        | URL                                    |
    | --------------- | -------------------------------------- |
    | facebookPage    | https://facebook.com/{ID}              |
    | githubUser      | https://github.com/{ID}                |
    | googlePlus      | https://plus.google.com/+{ID}          |
    | instagram       | https://instagram.com/{ID}             |
    | linkedInCompany | https://linkedin.com/company/{ID}      |
    | pinterest       | https://pinterest.com/{ID}             |
    | twitter         | https://twitter.com/{ID}               |
    | youTubeUser     | https://youtube.com/user/{ID}          |

    Properties only get set when a value for it has been found. That means that if no social media account has been found only the property "url" will be set.
  termsOfService: https://link.fish/terms-of-service/
  contact:
    name: link.fish
    url: https://link.fish/api
    email: api@link.fish
  version: "2017-12-01"
host: api.link.fish
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Urls/social-media:
    get:
      summary: Get social media accounts
      description: |-
        Visits the URL and checks if there are any social media accounts and returns the found ones.

        Will by default return the account identifiers and not the full URL to the profiles. To return URLs instead set the parameter "return_urls" to true.

        The URLs can also be created manually like this:

        | Property        | URL                                    |
        | --------------- | -------------------------------------- |
        | facebookPage    | https://facebook.com/{ID}              |
        | githubUser      | https://github.com/{ID}                |
        | googlePlus      | https://plus.google.com/+{ID}          |
        | instagram       | https://instagram.com/{ID}             |
        | linkedInCompany | https://linkedin.com/company/{ID}      |
        | pinterest       | https://pinterest.com/{ID}             |
        | twitter         | https://twitter.com/{ID}               |
        | youTubeUser     | https://youtube.com/user/{ID}          |

        Properties only get set when a value for it has been found. That means that if no social media account has been found only the property "url" will be set.
      operationId: Urls.social_media.get
      x-api-path-slug: urlssocialmedia-get
      parameters:
      - in: query
        name: browser_render
        description: If the page should be fully rendered with a browser to extract
          data
      - in: query
        name: return_urls
        description: Returns profile URLs instead of the profile names/ids
      - in: query
        name: url
        description: The URL of the website to query
      responses:
        200:
          description: OK
      tags:
      - Urls
      - Social
      - Media
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