---
swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 0
info:
  title: Sound Cloud Get Me Groups. Format
  description: Returns a collection of groups joined by logged-in user
  version: 1.0.0
host: api.soundcloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracks/{track_id}/comments.json:
    get:
      summary: Get Tracks Track Comments
      description: Returns comments of a track by track id
      operationId: getTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
    post:
      summary: Post Tracks Track Comments
      description: Posts a comments to a track by track id
      operationId: postTracksTrackComments.json
      x-api-path-slug: trackstrack-idcomments-json-post
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
  /users/{user_id}/comments.json:
    get:
      summary: Get Users Comments
      description: Returns a collection of comments made by user id
      operationId: getUsersUserComments.json
      x-api-path-slug: usersuser-idcomments-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Users
      - Comments
  /me.json:
    get:
      summary: Get Me
      description: Returns the logged-in user
      operationId: getMe.json
      x-api-path-slug: me-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
    put:
      summary: Put Me
      description: Updates the logged-in user
      operationId: putMe.json
      x-api-path-slug: me-json-put
      responses:
        200:
          description: OK
      tags:
      - Me
  /me/tracks.json:
    get:
      summary: Get Me Tracks
      description: Returns a collection of tracks uploaded by logged-in user
      operationId: getMeTracks.json
      x-api-path-slug: metracks-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Tracks
  /me/comments.json:
    get:
      summary: Get Me Comments
      description: Returns a collection of comments made by logged-in user
      operationId: getMeComments.json
      x-api-path-slug: mecomments-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Comments
  /me/followings.json:
    get:
      summary: Get Me Followings
      description: Returns a collection of users the logged-in user is following
      operationId: getMeFollowings.json
      x-api-path-slug: mefollowings-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
  /me/followings/{contact_id}.json:
    get:
      summary: Get Me Followings Contact
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts.
      operationId: getMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
    put:
      summary: Put Me Followings Contact
      description: Adds the user with the id contact_id to the logged-in user's list
        of contacts.
      operationId: putMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
    delete:
      summary: Delete Me Followings Contact
      description: Deletes the user with the id contact_id from the logged-in user's
        list of contacts.
      operationId: deleteMeFollowingsContact.json
      x-api-path-slug: mefollowingscontact-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
  /me/followers.json:
    get:
      summary: Get Me Followers
      description: Returns a collection of users who follow the logged-in user
      operationId: getMeFollowers.json
      x-api-path-slug: mefollowers-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
  /me/followers/{contact_id}.json:
    get:
      summary: Get Me Followers Contact
      description: Checks if the user with the id contact_id is a follower of the
        logged-in user
      operationId: getMeFollowersContact.json
      x-api-path-slug: mefollowerscontact-id-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
      - Contact
  /me/favorites.json:
    get:
      summary: Get Me Favorites
      description: Returns a collection of tracks favorited by the logged-in user
      operationId: getMeFavorites.json
      x-api-path-slug: mefavorites-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
  /me/favorites/{track_id}.json:
    put:
      summary: Put Me Favorites Track
      description: Adds the given track to the logged-in user's list of favorites.
      operationId: putMeFavoritesTrack.json
      x-api-path-slug: mefavoritestrack-id-json-put
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
    delete:
      summary: Delete Me Favorites Track
      description: Deletes the given track from the logged-in user's list of favorites.
      operationId: deleteMeFavoritesTrack.json
      x-api-path-slug: mefavoritestrack-id-json-delete
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
  /me/groups.json:
    get:
      summary: Get Me Groups
      description: Returns a collection of groups joined by logged-in user
      operationId: getMeGroups.json
      x-api-path-slug: megroups-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Groups
  /me/playlists.json:
    get:
      summary: Get Me Playlists
      description: Returns a collection of playlists created by the logged-in user
      operationId: getMePlaylists.json
      x-api-path-slug: meplaylists-json-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Playlists
  /groups/{group_id}/members.json:
    get:
      summary: Get Groups Members
      description: Returns a collection of members of the group with group id
      operationId: getGroupsGroupMembers.json
      x-api-path-slug: groupsgroup-idmembers-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Members
  /comments/{comment_id}.json:
    get:
      summary: Get Comments
      description: Returns a comment by comment id
      operationId: getCommentsComment.json
      x-api-path-slug: commentscomment-id-json-get
      parameters:
      - in: query
        name: consumer_key
      responses:
        200:
          description: OK
      tags:
      - Comments
  /tracks/{track_id}/comments.{format}:
    get:
      summary: Get Tracks Track Comments. Format
      description: Returns comments of a track by track id
      operationId: getTracksTrackComments.Format
      x-api-path-slug: trackstrack-idcomments-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
      - ""
      - Format
    post:
      summary: Post Tracks Track Comments. Format
      description: Posts a comments to a track by track id
      operationId: postTracksTrackComments.Format
      x-api-path-slug: trackstrack-idcomments-format-post
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Tracks
      - Track
      - Comments
      - ""
      - Format
  /users/{user_id}/comments.{format}:
    get:
      summary: Get Users Comments. Format
      description: Returns a collection of comments made by user id
      operationId: getUsersUserComments.Format
      x-api-path-slug: usersuser-idcomments-format-get
      parameters:
      - in: query
        name: consumer_key
        description: Access, host, upload, and comment on audio
      - in: path
        name: user_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Users
      - Comments
      - ""
      - Format
  /me.{format}:
    get:
      summary: Get Me. Format
      description: Returns the logged-in user
      operationId: getMe.Format
      x-api-path-slug: me-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - ""
      - Format
    put:
      summary: Put Me. Format
      description: Updates the logged-in user
      operationId: putMe.Format
      x-api-path-slug: me-format-put
      responses:
        200:
          description: OK
      tags:
      - Me
      - ""
      - Format
  /me/tracks.{format}:
    get:
      summary: Get Me Tracks. Format
      description: Returns a collection of tracks uploaded by logged-in user
      operationId: getMeTracks.Format
      x-api-path-slug: metracks-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Tracks
      - ""
      - Format
  /me/comments.{format}:
    get:
      summary: Get Me Comments. Format
      description: Returns a collection of comments made by logged-in user
      operationId: getMeComments.Format
      x-api-path-slug: mecomments-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Comments
      - ""
      - Format
  /me/followings.{format}:
    get:
      summary: Get Me Followings. Format
      description: Returns a collection of users the logged-in user is following
      operationId: getMeFollowings.Format
      x-api-path-slug: mefollowings-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - ""
      - Format
  /me/followings/{contact_id}.{format}:
    get:
      summary: Get Me Followings Contact . Format
      description: Checks if the user with the id contact_id is in the logged-in user's
        list of contacts.
      operationId: getMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-get
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
    put:
      summary: Put Me Followings Contact . Format
      description: Adds the user with the id contact_id to the logged-in user's list
        of contacts.
      operationId: putMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-put
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
    delete:
      summary: Delete Me Followings Contact . Format
      description: Deletes the user with the id contact_id from the logged-in user's
        list of contacts.
      operationId: deleteMeFollowingsContact.Format
      x-api-path-slug: mefollowingscontact-id-format-delete
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followings
      - Contact
      - ""
      - ""
      - Format
  /me/followers.{format}:
    get:
      summary: Get Me Followers. Format
      description: Returns a collection of users who follow the logged-in user
      operationId: getMeFollowers.Format
      x-api-path-slug: mefollowers-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
      - ""
      - Format
  /me/followers/{contact_id}.{format}:
    get:
      summary: Get Me Followers Contact . Format
      description: Checks if the user with the id contact_id is a follower of the
        logged-in user
      operationId: getMeFollowersContact.Format
      x-api-path-slug: mefollowerscontact-id-format-get
      parameters:
      - in: path
        name: contact_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Followers
      - Contact
      - ""
      - ""
      - Format
  /me/favorites.{format}:
    get:
      summary: Get Me Favorites. Format
      description: Returns a collection of tracks favorited by the logged-in user
      operationId: getMeFavorites.Format
      x-api-path-slug: mefavorites-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - ""
      - Format
  /me/favorites/{track_id}.{format}:
    put:
      summary: Put Me Favorites Track . Format
      description: Adds the given track to the logged-in user's list of favorites.
      operationId: putMeFavoritesTrack.Format
      x-api-path-slug: mefavoritestrack-id-format-put
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
      - ""
      - ""
      - Format
    delete:
      summary: Delete Me Favorites Track . Format
      description: Deletes the given track from the logged-in user's list of favorites.
      operationId: deleteMeFavoritesTrack.Format
      x-api-path-slug: mefavoritestrack-id-format-delete
      parameters:
      - in: path
        name: track_id
        description: Access, host, upload, and comment on audio
      responses:
        200:
          description: OK
      tags:
      - Me
      - Favorites
      - Track
      - ""
      - ""
      - Format
  /me/groups.{format}:
    get:
      summary: Get Me Groups. Format
      description: Returns a collection of groups joined by logged-in user
      operationId: getMeGroups.Format
      x-api-path-slug: megroups-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Groups
      - ""
      - Format
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