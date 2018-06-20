---
swagger: "2.0"
x-collection-name: Spreaker
x-complete: 0
info:
  title: Spreaker API Create Media
  version: v1
  description: Upload a new Media in the specified user library
host: api.spreaker.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /episode/{episode_id}/media:
    get:
      summary: Get Episode Media List
      description: Get Episode Media List
      operationId: getEpisodeEpisodeMedia
      x-api-path-slug: episodeepisode-idmedia-get
      parameters:
      - in: path
        name: episode_id
        description: Unique id of episode
      responses:
        200:
          description: OK
      tags:
      - Episode
      - Media
      - List
  /library/{user_id}:
    post:
      summary: Create Media
      description: Upload a new Media in the specified user library
      operationId: postLibraryUser
      x-api-path-slug: libraryuser-id-post
      parameters:
      - in: path
        name: Filedata
        description: The file to upload, encoded multipart/form-data
      - in: query
        name: length
        description: The media length in milliseconds
      - in: query
        name: style_id
        description: The music style associated to this media
      - in: query
        name: type
        description: 'The media type: can be one of SONG, JINGLE, LOOP, UNKNOWN, EFFECT,
          EPISODE'
      - in: path
        name: user_id
        description: The unique user id
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