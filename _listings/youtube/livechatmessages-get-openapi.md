---
swagger: "2.0"
x-collection-name: YouTube
x-complete: 0
info:
  title: Youtube Get Live Chat Messages
  description: Lists live chat messages for a specific chat.
  termsOfService: https://developers.google.com/terms/
  contact:
    name: Google
    url: https://google.com
  version: 1.0.0
host: www.googleapis.com
basePath: /youtube/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/media/{resourceName}:
    get:
      summary: Get Media Resource Name
      description: |-
        Method for media download. Download is supported
        on the URI `/v1/media/{+name}?alt=media`.
      operationId: getV1MediaResourcename
      x-api-path-slug: v1mediaresourcename-get
      parameters:
      - in: path
        name: resourceName
        description: Name of the media that is being downloaded
      responses:
        200:
          description: OK
      tags:
      - V1
      - Media
      - Resourcename
  /commentThreads:
    get:
      summary: Get Comment Threads
      description: Returns a list of comment threads that match the API request parameters.
      operationId: getCommentthreads
      x-api-path-slug: commentthreads-get
      parameters:
      - in: query
        name: allThreadsRelatedToChannelId
        description: The allThreadsRelatedToChannelId parameter instructs the API
          to return all comment threads associated with the specified channel
      - in: query
        name: channelId
        description: The channelId parameter instructs the API to return comment threads
          containing comments about the specified channel
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of comment
          thread IDs for the resources that should be retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: moderationStatus
        description: Set this parameter to limit the returned comment threads to a
          particular moderation state
      - in: query
        name: order
        description: The order parameter specifies the order in which the API response
          should list comment threads
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more commentThread resource properties that the API response will include
      - in: query
        name: searchTerms
        description: The searchTerms parameter instructs the API to limit the API
          response to only contain comments that contain the specified search terms
      - in: query
        name: textFormat
        description: Set this parameters value to html or plainText to instruct the
          API to return the comments left by users in html formatted or in plain text
      - in: query
        name: videoId
        description: The videoId parameter instructs the API to return comment threads
          associated with the specified video ID
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
    post:
      summary: Add Comment Threads
      description: Creates a new top-level comment. To add a reply to an existing
        comment, use the comments.insert method instead.
      operationId: postCommentthreads
      x-api-path-slug: commentthreads-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
    put:
      summary: Put Comment Threads
      description: Modifies the top-level comment in a comment thread.
      operationId: putCommentthreads
      x-api-path-slug: commentthreads-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of commentThread
          resource properties that the API response will include
      responses:
        200:
          description: OK
      tags:
      - Commentthreads
  /comments:
    delete:
      summary: Delete Comments
      description: Deletes a comment.
      operationId: deleteComments
      x-api-path-slug: comments-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the comment ID for the resource that
          is being deleted
      responses:
        200:
          description: OK
      tags:
      - Comments
    get:
      summary: Get Comments
      description: Returns a list of comments that match the API request parameters.
      operationId: getComments
      x-api-path-slug: comments-get
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of comment
          IDs for the resources that are being retrieved
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of items
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: parentId
        description: The parentId parameter specifies the ID of the comment for which
          replies should be retrieved
      - in: query
        name: part
        description: The part parameter specifies a comma-separated list of one or
          more comment resource properties that the API response will include
      - in: query
        name: textFormat
        description: This parameter indicates whether the API should return comments
          formatted as HTML or as plain text
      responses:
        200:
          description: OK
      tags:
      - Comments
    post:
      summary: Add Comments
      description: 'Creates a reply to an existing comment. Note: To create a top-level
        comment, use the commentThreads.insert method.'
      operationId: postComments
      x-api-path-slug: comments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Comments
    put:
      summary: Put Comments
      description: Modifies a comment.
      operationId: putComments
      x-api-path-slug: comments-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: part
        description: The part parameter identifies the properties that the API response
          will include
      responses:
        200:
          description: OK
      tags:
      - Comments
  /comments/markAsSpam:
    post:
      summary: Add Comments Mark as SPAM
      description: Expresses the caller's opinion that one or more comments should
        be flagged as spam.
      operationId: postCommentsMarkasspam
      x-api-path-slug: commentsmarkasspam-post
      parameters:
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs of comments
          that the caller believes should be classified as spam
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Markasspam
  /comments/setModerationStatus:
    post:
      summary: Add Comments Set Moderation Status
      description: Sets the moderation status of one or more comments. The API request
        must be authorized by the owner of the channel or video associated with the
        comments.
      operationId: postCommentsSetmoderationstatus
      x-api-path-slug: commentssetmoderationstatus-post
      parameters:
      - in: query
        name: banAuthor
        description: The banAuthor parameter lets you indicate that you want to automatically
          reject any additional comments written by the comments author
      - in: query
        name: id
        description: The id parameter specifies a comma-separated list of IDs that
          identify the comments for which you are updating the moderation status
      - in: query
        name: moderationStatus
        description: Identifies the new moderation status of the specified comments
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Setmoderationstatus
  /liveChat/messages:
    delete:
      summary: Delete Live Chat Messages
      description: Delete livechat messages
      operationId: deleteLivechatMessages
      x-api-path-slug: livechatmessages-delete
      parameters:
      - in: query
        name: id
        description: The id parameter specifies the YouTube chat message ID of the
          resource that is being deleted
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
    get:
      summary: Get Live Chat Messages
      description: Lists live chat messages for a specific chat.
      operationId: getLivechatMessages
      x-api-path-slug: livechatmessages-get
      parameters:
      - in: query
        name: hl
        description: The hl parameter instructs the API to retrieve localized resource
          metadata for a specific application language that the YouTube website supports
      - in: query
        name: liveChatId
        description: The liveChatId parameter specifies the ID of the chat whose messages
          will be returned
      - in: query
        name: maxResults
        description: The maxResults parameter specifies the maximum number of messages
          that should be returned in the result set
      - in: query
        name: pageToken
        description: The pageToken parameter identifies a specific page in the result
          set that should be returned
      - in: query
        name: part
        description: The part parameter specifies the liveChatComment resource parts
          that the API response will include
      - in: query
        name: profileImageSize
        description: The profileImageSize parameter specifies the size of the user
          profile pictures that should be returned in the result set
      responses:
        200:
          description: OK
      tags:
      - Chat
      - Messages
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---