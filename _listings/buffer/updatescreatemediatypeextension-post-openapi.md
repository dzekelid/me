---
swagger: "2.0"
x-collection-name: Buffer
x-complete: 0
info:
  title: Buffer Post Updates Create Mediatypeextension
  description: Create one or more new status updates.
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
  /profiles/{id}/updates/pending{mediaTypeExtension}:
    get:
      summary: Get Profiles Updates Pending Mediatypeextension
      description: Get Profiles Updates Pending Mediatypeextension
      operationId: returns-an-array-of-updates-that-are-currently-in-the-buffer-for-an-individual-social-media-profile-
      x-api-path-slug: profilesidupdatespendingmediatypeextension-get
      parameters:
      - in: query
        name: count
        description: Specifies the number of status updates to receive
      - in: path
        name: id
      - in: path
        name: mediaTypeExtension
      - in: query
        name: page
        description: Specifies the page of status updates to receive
      - in: query
        name: since
        description: Specifies a unix timestamp which only status updates created
          after this time will be retrieved
      - in: query
        name: utc
        description: If utc is set times will be returned relative to UTC rather than
          the users associated timezone
      responses:
        200:
          description: OK
      tags:
      - Profiles
      - Id
      - Updates
      - PendingmediaTypeExtension
  /profiles/{id}/updates/reorder{mediaTypeExtension}:
    post:
      summary: Post Profiles Updates Reorder Mediatypeextension
      description: Edit the order at which statuses for the specified social media
        profile will be sent out of the buffer.
      operationId: edit-the-order-at-which-statuses-for-the-specified-social-media-profile-will-be-sent-out-of-the-buff
      x-api-path-slug: profilesidupdatesreordermediatypeextension-post
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
      - Updates
      - ReordermediaTypeExtension
  /profiles/{id}/updates/sent{mediaTypeExtension}:
    get:
      summary: Get Profiles Updates Sent Mediatypeextension
      description: Returns an array of updates that have been sent from the buffer
        for an individual social media profile.
      operationId: returns-an-array-of-updates-that-have-been-sent-from-the-buffer-for-an-individual-social-media-profi
      x-api-path-slug: profilesidupdatessentmediatypeextension-get
      parameters:
      - in: query
        name: count
        description: Specifies the number of status updates to receive
      - in: path
        name: id
      - in: path
        name: mediaTypeExtension
      - in: query
        name: page
        description: Specifies the page of status updates to receive
      - in: query
        name: since
        description: Specifies a unix timestamp which only status updates created
          after this time will be retrieved
      - in: query
        name: utc
        description: If utc is set times will be returned relative to UTC rather than
          the users associated timezone
      responses:
        200:
          description: OK
      tags:
      - Profiles
      - Id
      - Updates
      - SentmediaTypeExtension
  /profiles/{id}/updates/shuffle{mediaTypeExtension}:
    post:
      summary: Post Profiles Updates Shuffle Mediatypeextension
      description: Randomize the order at which statuses for the specified social
        media profile will be sent out of the buffer.
      operationId: randomize-the-order-at-which-statuses-for-the-specified-social-media-profile-will-be-sent-out-of-the
      x-api-path-slug: profilesidupdatesshufflemediatypeextension-post
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
      - Updates
      - ShufflemediaTypeExtension
  /profiles/{id}{mediaTypeExtension}:
    get:
      summary: Get Profiles Mediatypeextension
      description: Returns details of the single specified social media profile.
      operationId: returns-details-of-the-single-specified-social-media-profile-
      x-api-path-slug: profilesidmediatypeextension-get
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
      - IdmediaTypeExtension
  /profiles{mediaTypeExtension}:
    get:
      summary: Get Profiles Mediatypeextension
      description: Returns an array of social media profiles connected to a users
        account.
      operationId: returns-an-array-of-social-media-profiles-connected-to-a-users-account-
      x-api-path-slug: profilesmediatypeextension-get
      parameters:
      - in: path
        name: mediaTypeExtension
      responses:
        200:
          description: OK
      tags:
      - ProfilesmediaTypeExtension
  /updates/create{mediaTypeExtension}:
    post:
      summary: Post Updates Create Mediatypeextension
      description: Create one or more new status updates.
      operationId: create-one-or-more-new-status-updates-
      x-api-path-slug: updatescreatemediatypeextension-post
      parameters:
      - in: path
        name: mediaTypeExtension
      responses:
        200:
          description: OK
      tags:
      - Updates
      - CreatemediaTypeExtension
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