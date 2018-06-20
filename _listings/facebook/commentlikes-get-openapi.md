---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get Comment Likes
  description: All the likes on this comment
  version: 1.0.0
host: graph.facebook.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{album}/comments:
    get:
      summary: Get Album Comments
      description: The comments made on this album
      operationId: getAlbumComments
      x-api-path-slug: albumcomments-get
      parameters:
      - in: path
        name: album
        description: Represents the ID of the album object
      responses:
        200:
          description: OK
      tags:
      - Album
      - Comments
    post:
      summary: Post Album Comments
      description: Posts a comment on the album
      operationId: postAlbumComments
      x-api-path-slug: albumcomments-post
      parameters:
      - in: path
        name: album
        description: Represents the ID of the album object
      - in: query
        name: message
        description: Comment text
      responses:
        200:
          description: OK
      tags:
      - Album
      - Comments
  /{application}/achievements:
    post:
      summary: Post Application Achievements
      description: Registers an achievement for the application
      operationId: postApplicationAchievements
      x-api-path-slug: applicationachievements-post
      parameters:
      - in: query
        name: achievement
        description: Unique URL to the achievement
      - in: path
        name: application
        description: Represents the ID of the application object
      - in: query
        name: display_order
        description: Order of this achievement as it shows up in the achievement stories
          UI (low to high)
      responses:
        200:
          description: OK
      tags:
      - Application
      - Achievements
    delete:
      summary: Delete Application Achievements
      description: Unregisters an achievement for the application
      operationId: deleteApplicationAchievements
      x-api-path-slug: applicationachievements-delete
      parameters:
      - in: query
        name: achievement
        description: Unique URL to the achievement
      - in: path
        name: application
        description: Represents the ID of the application object
      responses:
        200:
          description: OK
      tags:
      - Application
      - Achievements
  /{checkin}/comments:
    get:
      summary: Get Checkin Comments
      description: All of the comments on this checkin.
      operationId: getCheckinComments
      x-api-path-slug: checkincomments-get
      parameters:
      - in: path
        name: checkin
        description: Represents the ID of the checkin object
      responses:
        200:
          description: OK
      tags:
      - Checkin
      - Comments
    post:
      summary: Post Checkin Comments
      description: Posts a comment to this checkin.
      operationId: postCheckinComments
      x-api-path-slug: checkincomments-post
      parameters:
      - in: path
        name: checkin
        description: Represents the ID of the checkin object
      - in: query
        name: message
        description: Comment text
      responses:
        200:
          description: OK
      tags:
      - Checkin
      - Comments
  /{comment}:
    get:
      summary: Get Comment
      description: Returns a comment
      operationId: getComment
      x-api-path-slug: comment-get
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
    delete:
      summary: Delete Comment
      description: Deletes a comment
      operationId: deleteComment
      x-api-path-slug: comment-delete
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
  /{comment}/likes:
    get:
      summary: Get Comment Likes
      description: All the likes on this comment
      operationId: getCommentLikes
      x-api-path-slug: commentlikes-get
      parameters:
      - in: path
        name: comment
        description: Represents the ID of the comment object
      responses:
        200:
          description: OK
      tags:
      - Comment
      - Likes
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