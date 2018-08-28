---
swagger: "2.0"
x-collection-name: Instagram
x-complete: 0
info:
  title: Instagram Instagram Media
  version: 1.0.0
  description: Instagram Media
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;instagram-media-id&#125;/comments:
    get:
      summary: Instagram Media Comments
      description: Instagram Media Comments
      operationId: getInstagramMediaComments
      x-api-path-slug: 123instagrammediaid125comments-get
      parameters:
      - in: query
        name: "100"
        description: Invalid parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instagram
      - Media
      - Comments
  /&#123;instagram-media-id&#125;:
    get:
      summary: Instagram Media
      description: Instagram Media
      operationId: getInstagramMedia
      x-api-path-slug: 123instagrammediaid125-get
      parameters:
      - in: query
        name: caption_textstring
        description: Caption text
        type: string
      - in: query
        name: comment_countint32
        description: Number of comments
        type: string
      - in: query
        name: content_typeint32
        description: 0 for photo, 1 for video
        type: string
      - in: query
        name: display_urlstring
        description: URL of the photo or cover frame
        type: string
      - in: query
        name: filter_namestring
        description: Name of filter
        type: string
      - in: query
        name: idnumeric string
        description: ID of the Instagram media
        type: string
      - in: query
        name: latitudefloat
        description: Latitude of the location
        type: string
      - in: query
        name: like_countint32
        description: Number of likes
        type: string
      - in: query
        name: locationLocation
        description: Location data
        type: string
      - in: query
        name: location_namestring
        description: Name of location for location tag
        type: string
      - in: query
        name: longitudefloat
        description: Longitude of the location
        type: string
      - in: query
        name: owner_instagram_userInstagramUser
        description: The Instagram user that owns this media
        type: string
      - in: query
        name: permalinkstring
        description: Link to the media page on Instagram
        type: string
      - in: query
        name: taken_atdatetime
        description: When the media was created
        type: string
      - in: query
        name: video_urlstring
        description: URL of the video
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instagram
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