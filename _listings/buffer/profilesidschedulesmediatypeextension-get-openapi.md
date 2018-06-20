---
swagger: "2.0"
x-collection-name: Buffer
x-complete: 0
info:
  title: Buffer Get Profiles Schedules Mediatypeextension
  description: Returns details of the posting schedules associated with a social media
    profile.
  version: "1"
host: api.bufferapp.com
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /info/configuration{mediaTypeExtension}:
    get:
      summary: Get Info Configuration Mediatypeextension
      description: Returns an object with the current configuration that Buffer is
        using, including supported services, their icons and the varying limits of
        character and schedules.
      operationId: returns-an-object-with-the-current-configuration-that-buffer-is-using-including-supported-services-t
      x-api-path-slug: infoconfigurationmediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
      responses:
        200:
          description: OK
      tags:
      - Info
      - ConfigurationmediaTypeExtension
  /links/shares{mediaTypeExtension}:
    get:
      summary: Get Links Shares Mediatypeextension
      description: Returns an object with a the numbers of shares a link has had using
        Buffer.
      operationId: returns-an-object-with-a-the-numbers-of-shares-a-link-has-had-using-buffer-
      x-api-path-slug: linkssharesmediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
      - in: query
        name: url
        description: URL-encoded URL of the page for which the number of shares is
          requested
      responses:
        200:
          description: OK
      tags:
      - Links
      - SharesmediaTypeExtension
  /profiles/{id}/schedules/update{mediaTypeExtension}:
    post:
      summary: Post Profiles Schedules Update Mediatypeextension
      description: Post Profiles Schedules Update Mediatypeextension
      operationId: set-the-posting-schedules-for-the-specified-social-media-profile-
      x-api-path-slug: profilesidschedulesupdatemediatypeextension-post
      parameters:
      - in: path
        name: id
      - in: path
        name: mediaTypeExtension
      responses:
        200:
          description: OK
      tags:
      - Profiles
      - Id
      - Schedules
      - UpdatemediaTypeExtension
  /profiles/{id}/schedules{mediaTypeExtension}:
    get:
      summary: Get Profiles Schedules Mediatypeextension
      description: Returns details of the posting schedules associated with a social
        media profile.
      operationId: returns-details-of-the-posting-schedules-associated-with-a-social-media-profile-
      x-api-path-slug: profilesidschedulesmediatypeextension-get
      parameters:
      - in: path
        name: id
      - in: path
        name: mediaTypeExtension
      responses:
        200:
          description: OK
      tags:
      - Profiles
      - Id
      - SchedulesmediaTypeExtension
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