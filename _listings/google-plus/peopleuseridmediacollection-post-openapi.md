---
swagger: "2.0"
x-collection-name: Google Plus
x-complete: 0
info:
  title: Google Plus Add Media To Collection
  version: 1.0.0
  description: Add a new media item to an album. The current upload size limitations
    are 36MB for a photo and 1GB for a video. Uploads do not count against quota if
    photos are less than 2048 pixels on their longest side or videos are less than
    15 minutes in length.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activities/{activityId}/comments:
    get:
      summary: Get Activity Comments
      description: List all of the comments for an activity.
      operationId: plus.comments.list
      x-api-path-slug: activitiesactivityidcomments-get
      parameters:
      - in: path
        name: activityId
        description: The ID of the activity to get comments for
      - in: query
        name: maxResults
        description: The maximum number of comments to include in the response, which
          is used for paging
      - in: query
        name: pageToken
        description: The continuation token, which is used to page through large result
          sets
      - in: query
        name: sortOrder
        description: The order in which to sort the list of comments
      responses:
        200:
          description: OK
      tags:
      - Comment
  /comments/{commentId}:
    get:
      summary: Get Comment
      description: Get a comment.
      operationId: plusDomains.comments.get
      x-api-path-slug: commentscommentid-get
      parameters:
      - in: path
        name: commentId
        description: The ID of the comment to get
      responses:
        200:
          description: OK
      tags:
      - Comment
  /people/{userId}/media/{collection}:
    post:
      summary: Add Media To Collection
      description: Add a new media item to an album. The current upload size limitations
        are 36MB for a photo and 1GB for a video. Uploads do not count against quota
        if photos are less than 2048 pixels on their longest side or videos are less
        than 15 minutes in length.
      operationId: plusDomains.media.insert
      x-api-path-slug: peopleuseridmediacollection-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: collection
      - in: path
        name: userId
        description: The ID of the user to create the activity on behalf of
      responses:
        200:
          description: OK
      tags:
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