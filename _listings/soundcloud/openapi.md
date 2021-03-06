swagger: "2.0"
x-collection-name: SoundCloud
x-complete: 1
info:
  title: Sound Cloud
  description: access-host-upload-and-comment-on-audio-
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
  /me/playlists.{format}:
    get:
      summary: Get Me Playlists. Format
      description: Returns a collection of playlists created by the logged-in user
      operationId: getMePlaylists.Format
      x-api-path-slug: meplaylists-format-get
      responses:
        200:
          description: OK
      tags:
      - Me
      - Playlists
      - ""
      - Format