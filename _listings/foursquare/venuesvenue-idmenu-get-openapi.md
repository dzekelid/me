---
swagger: "2.0"
x-collection-name: Foursquare
x-complete: 0
info:
  title: Foursquare Get Venues Menu
  description: /venues/{VENUE_ID}/listed
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /campaigns/{CAMPAIGN_ID}/timeseries:
    get:
      summary: Get Campaigns Timeseries
      description: /campaigns/list
      operationId: campaignslist
      x-api-path-slug: campaignscampaign-idtimeseries-get
      parameters:
      - in: query
        name: CAMPAIGN_ID
        description: The campaign id to retrieve stats for
      - in: path
        name: CAMPAIGN_ID
      - in: query
        name: endAt
        description: The end of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: startAt
        description: The start of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Campaigns
      - Timeseries
  /checkins/{CHECKIN_ID}/addcomment:
    post:
      summary: Post Checkins Checkin Addcomment
      description: /checkins/recent
      operationId: checkinsrecent
      x-api-path-slug: checkinscheckin-idaddcomment-post
      parameters:
      - in: query
        name: CHECKIN_ID
        description: The ID of the checkin to add a comment to
      - in: path
        name: CHECKIN_ID
      - in: query
        name: text
        description: The text of the comment, up to 200 characters
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Checkins
      - Checkin
      - Comment
  /checkins/{CHECKIN_ID}/deletecomment:
    post:
      summary: Post Checkins Checkin Deletecomment
      description: /checkins/{CHECKIN_ID}/addcomment
      operationId: checkinscheckin-idaddcomment
      x-api-path-slug: checkinscheckin-iddeletecomment-post
      parameters:
      - in: query
        name: CHECKIN_ID
        description: The ID of the checkin to remove a comment from
      - in: path
        name: CHECKIN_ID
      - in: query
        name: commentId
        description: The id of the comment to remove
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Checkins
      - Checkin
      - Comment
  /venues/timeseries:
    get:
      summary: Get Venues Timeseries
      description: /venues/suggestcompletion
      operationId: venuessuggestcompletion
      x-api-path-slug: venuestimeseries-get
      parameters:
      - in: query
        name: endAt
        description: The end of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: startAt
        description: The start of the time range to retrieve stats for (seconds since
          epoch)
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: venueId
        description: A comma-separated list of venue ids to retrieve series data for
      responses:
        200:
          description: OK
      tags:
      - Venues
      - Timeseries
  /venues/{VENUE_ID}/menu:
    get:
      summary: Get Venues Menu
      description: /venues/{VENUE_ID}/listed
      operationId: venuesvenue-idlisted
      x-api-path-slug: venuesvenue-idmenu-get
      parameters:
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      - in: query
        name: VENUE_ID
        description: The venue id for which menu is being requested
      - in: path
        name: VENUE_ID
      responses:
        200:
          description: OK
      tags:
      - Venues
      - Menu
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