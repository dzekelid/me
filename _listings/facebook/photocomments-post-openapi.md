---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Post Photo Comments
  description: Posts a comment to this photo.
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
    post:
      summary: Post Comment Likes
      description: Likes the comment
      operationId: postCommentLikes
      x-api-path-slug: commentlikes-post
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
    delete:
      summary: Delete Comment Likes
      description: Unlikes the comment
      operationId: deleteCommentLikes
      x-api-path-slug: commentlikes-delete
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
  /{friendlist}/members:
    get:
      summary: Get Friendlist Members
      description: All of the users who are members of this list.
      operationId: getFriendlistMembers
      x-api-path-slug: friendlistmembers-get
      parameters:
      - in: path
        name: friendlist
        description: Represents the ID of the FriendList object
      responses:
        200:
          description: OK
      tags:
      - Friendlist
      - Members
  /{friendlist}/members/{user}:
    post:
      summary: Post Friendlist Members User
      description: Adds a user to the friend list
      operationId: postFriendlistMembersUser
      x-api-path-slug: friendlistmembersuser-post
      parameters:
      - in: path
        name: friendlist
        description: Represents the ID of the FriendList object
      - in: path
        name: user
        description: Represents the ID of the User to add to or remove from the friend
          list
      responses:
        200:
          description: OK
      tags:
      - Friendlist
      - Members
      - User
    delete:
      summary: Delete Friendlist Members User
      description: Removes a user from the friend list
      operationId: deleteFriendlistMembersUser
      x-api-path-slug: friendlistmembersuser-delete
      parameters:
      - in: path
        name: friendlist
        description: Represents the ID of the FriendList object
      - in: path
        name: user
        description: Represents the ID of the User to add to or remove from the friend
          list
      responses:
        200:
          description: OK
      tags:
      - Friendlist
      - Members
      - User
  /{group}/members:
    get:
      summary: Get Group Members
      description: All of the users who are members of this group
      operationId: getGroupMembers
      x-api-path-slug: groupmembers-get
      parameters:
      - in: path
        name: group
        description: Represents the ID of the group object
      responses:
        200:
          description: OK
      tags:
      - Group
      - Members
  /{link}/comments:
    get:
      summary: Get Link Comments
      description: All of the comments on this link.
      operationId: getLinkComments
      x-api-path-slug: linkcomments-get
      parameters:
      - in: path
        name: link
        description: Represents the ID of the link object
      responses:
        200:
          description: OK
      tags:
      - Link
      - Comments
    post:
      summary: Post Link Comments
      description: Posts a comment to this link.
      operationId: postLinkComments
      x-api-path-slug: linkcomments-post
      parameters:
      - in: path
        name: link
        description: Represents the ID of the link object
      - in: query
        name: message
        description: Comment text
      responses:
        200:
          description: OK
      tags:
      - Link
      - Comments
  /{note}/comments:
    get:
      summary: Get Note Comments
      description: All of the comments on this note.
      operationId: getNoteComments
      x-api-path-slug: notecomments-get
      parameters:
      - in: path
        name: note
        description: Represents the ID of the note object
      responses:
        200:
          description: OK
      tags:
      - Note
      - Comments
    post:
      summary: Post Note Comments
      description: Posts a comment to this note.
      operationId: postNoteComments
      x-api-path-slug: notecomments-post
      parameters:
      - in: query
        name: message
        description: Comment text
      - in: path
        name: note
        description: Represents the ID of the note object
      responses:
        200:
          description: OK
      tags:
      - Note
      - Comments
  /{photo}/comments:
    get:
      summary: Get Photo Comments
      description: All of the comments on this photo.
      operationId: getPhotoComments
      x-api-path-slug: photocomments-get
      parameters:
      - in: path
        name: photo
        description: Represents the ID of the photo object
      responses:
        200:
          description: OK
      tags:
      - Photo
      - Comments
    post:
      summary: Post Photo Comments
      description: Posts a comment to this photo.
      operationId: postPhotoComments
      x-api-path-slug: photocomments-post
      parameters:
      - in: query
        name: message
        description: Comment text
      - in: path
        name: photo
        description: Represents the ID of the photo object
      responses:
        200:
          description: OK
      tags:
      - Photo
      - Comments
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