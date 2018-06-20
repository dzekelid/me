---
name: SoundCloud
x-slug: soundcloud
description: SoundCloud is a music and podcast streaming platform that lets you listen
  to millions of songs from around the world, or upload your own. Start listening
  now!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
x-kinRank: "9"
x-alexaRank: "114"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/apis.md
specificationVersion: "0.14"
apis:
- name: Sound Cloud Get Tracks Track Comments
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-json-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.json
  tags: Tracks,Track,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-json-post-openapi.md
- name: Sound Cloud Get Users Comments
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/comments.json
  tags: Users,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/usersuser-idcomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/usersuser-idcomments-json-get-openapi.md
- name: Sound Cloud Get Me
  x-api-slug: sound-cloud
  description: Returns the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-json-get-openapi.md
- name: Sound Cloud Put Me
  x-api-slug: sound-cloud
  description: Updates the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.json
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-json-put-openapi.md
- name: Sound Cloud Get Me Tracks
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.json
  tags: Me,Tracks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/metracks-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/metracks-json-get-openapi.md
- name: Sound Cloud Get Me Comments
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/comments.json
  tags: Me,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mecomments-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mecomments-json-get-openapi.md
- name: Sound Cloud Get Me Followings
  x-api-slug: sound-cloud
  description: Returns a collection of users the logged-in user is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings.json
  tags: Me,Followings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowings-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowings-json-get-openapi.md
- name: Sound Cloud Get Me Followings Contact
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-get-openapi.md
- name: Sound Cloud Put Me Followings Contact
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the logged-in user's list of
    contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-put-openapi.md
- name: Sound Cloud Delete Me Followings Contact
  x-api-slug: sound-cloud
  description: Deletes the user with the id contact_id from the logged-in user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.json
  tags: Me,Followings,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-json-delete-openapi.md
- name: Sound Cloud Get Me Followers
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers.json
  tags: Me,Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowers-json-get-openapi.md
- name: Sound Cloud Get Me Followers Contact
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is a follower of the logged-in
    user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers/{contact_id}.json
  tags: Me,Followers,Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowerscontact-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowerscontact-id-json-get-openapi.md
- name: Sound Cloud Get Me Favorites
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.json
  tags: Me,Favorites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavorites-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavorites-json-get-openapi.md
- name: Sound Cloud Put Me Favorites Track
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-json-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-json-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.json
  tags: Me,Favorites,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-json-delete-openapi.md
- name: Sound Cloud Get Me Groups
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/groups.json
  tags: Me,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/megroups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/megroups-json-get-openapi.md
- name: Sound Cloud Get Me Playlists
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/playlists.json
  tags: Me,Playlists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/meplaylists-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/meplaylists-json-get-openapi.md
- name: Sound Cloud Get Groups Members
  x-api-slug: sound-cloud
  description: Returns a collection of members of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/members.json
  tags: Groups,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/groupsgroup-idmembers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/groupsgroup-idmembers-json-get-openapi.md
- name: Sound Cloud Get Comments
  x-api-slug: sound-cloud
  description: Returns a comment by comment id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////comments/{comment_id}.json
  tags: Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/commentscomment-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/commentscomment-id-json-get-openapi.md
- name: Sound Cloud Get Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Returns comments of a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-format-get-openapi.md
- name: Sound Cloud Post Tracks Track Comments. Format
  x-api-slug: sound-cloud
  description: Posts a comments to a track by track id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////tracks/{track_id}/comments.{format}
  tags: Tracks,Track,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/trackstrack-idcomments-format-post-openapi.md
- name: Sound Cloud Get Users Comments. Format
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by user id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////users/{user_id}/comments.{format}
  tags: Users,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/usersuser-idcomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/usersuser-idcomments-format-get-openapi.md
- name: Sound Cloud Get Me. Format
  x-api-slug: sound-cloud
  description: Returns the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.{format}
  tags: Me,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-format-get-openapi.md
- name: Sound Cloud Put Me. Format
  x-api-slug: sound-cloud
  description: Updates the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me.{format}
  tags: Me,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/me-format-put-openapi.md
- name: Sound Cloud Get Me Tracks. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks uploaded by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/tracks.{format}
  tags: Me,Tracks,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/metracks-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/metracks-format-get-openapi.md
- name: Sound Cloud Get Me Comments. Format
  x-api-slug: sound-cloud
  description: Returns a collection of comments made by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/comments.{format}
  tags: Me,Comments,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mecomments-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mecomments-format-get-openapi.md
- name: Sound Cloud Get Me Followings. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users the logged-in user is following
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings.{format}
  tags: Me,Followings,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowings-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowings-format-get-openapi.md
- name: Sound Cloud Get Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is in the logged-in user's
    list of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-get-openapi.md
- name: Sound Cloud Put Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Adds the user with the id contact_id to the logged-in user's list of
    contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-put-openapi.md
- name: Sound Cloud Delete Me Followings Contact . Format
  x-api-slug: sound-cloud
  description: Deletes the user with the id contact_id from the logged-in user's list
    of contacts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followings/{contact_id}.{format}
  tags: Me,Followings,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowingscontact-id-format-delete-openapi.md
- name: Sound Cloud Get Me Followers. Format
  x-api-slug: sound-cloud
  description: Returns a collection of users who follow the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers.{format}
  tags: Me,Followers,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowers-format-get-openapi.md
- name: Sound Cloud Get Me Followers Contact . Format
  x-api-slug: sound-cloud
  description: Checks if the user with the id contact_id is a follower of the logged-in
    user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/followers/{contact_id}.{format}
  tags: Me,Followers,Contact,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowerscontact-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefollowerscontact-id-format-get-openapi.md
- name: Sound Cloud Get Me Favorites. Format
  x-api-slug: sound-cloud
  description: Returns a collection of tracks favorited by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites.{format}
  tags: Me,Favorites,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavorites-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavorites-format-get-openapi.md
- name: Sound Cloud Put Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Adds the given track to the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-format-put-openapi.md
- name: Sound Cloud Delete Me Favorites Track . Format
  x-api-slug: sound-cloud
  description: Deletes the given track from the logged-in user's list of favorites.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/favorites/{track_id}.{format}
  tags: Me,Favorites,Track,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/mefavoritestrack-id-format-delete-openapi.md
- name: Sound Cloud Get Me Groups. Format
  x-api-slug: sound-cloud
  description: Returns a collection of groups joined by logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/groups.{format}
  tags: Me,Groups,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/megroups-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/megroups-format-get-openapi.md
- name: Sound Cloud Get Me Playlists. Format
  x-api-slug: sound-cloud
  description: Returns a collection of playlists created by the logged-in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////me/playlists.{format}
  tags: Me,Playlists,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/meplaylists-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/meplaylists-format-get-openapi.md
- name: Sound Cloud Get Groups Members. Format
  x-api-slug: sound-cloud
  description: Returns a collection of members of the group with group id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////groups/{group_id}/members.{format}
  tags: Groups,Members,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/groupsgroup-idmembers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/groupsgroup-idmembers-format-get-openapi.md
- name: Sound Cloud Get Comments . Format
  x-api-slug: sound-cloud
  description: Returns a comment by comment id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com////comments/{comment_id}.{format}
  tags: Comments,,,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/commentscomment-id-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/commentscomment-id-format-get-openapi.md
- name: Sound Cloud
  x-api-slug: sound-cloud
  description: SoundCloud is a music and podcast streaming platform that lets you
    listen to millions of songs from around the world, or upload your own. Start listening
    now!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/252-soundcloud.jpg
  humanURL: http://soundcloud.com
  baseURL: https://api.soundcloud.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/soundcloud/openapi.md
x-common:
- type: x-base
  url: https://api.soundcloud.com
- type: x-blog
  url: http://blog.soundcloud.com
- type: x-blog-rss
  url: http://blog.soundcloud.com/feed/
- type: x-console
  url: https://developers.soundcloud.com/console
- type: x-crunchbase
  url: https://crunchbase.com/organization/soundcloud
- type: x-crunchbase
  url: http://www.crunchbase.com/company/soundcloud
- type: x-developer
  url: http://developers.soundcloud.com
- type: x-github
  url: https://github.com/soundcloud
- type: x-pricing
  url: https://on.soundcloud.com/
- type: x-privacy
  url: https://soundcloud.com/pages/privacy
- type: x-support
  url: https://soundcloud.com/imprint
- type: x-terms-of-service
  url: https://soundcloud.com/terms-of-use
- type: x-twitter
  url: https://twitter.com/soundcloudapi
- type: x-twitter
  url: https://twitter.com/SoundCloud
- type: x-website
  url: http://soundcloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---