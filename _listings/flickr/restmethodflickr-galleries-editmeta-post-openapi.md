---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Galleries Edit Meta
  description: Modify the metadata for a gallery.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.activity.userComments:
    get:
      summary: Activity User Comments
      description: Returns a list of recent activity on photos commented on by the
        calling user. Do not poll this method more than once an hour.
      operationId: getRestMethodFlickr.activity.usercomments
      x-api-path-slug: restmethodflickr-activity-usercomments-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of items to return per page
      responses:
        200:
          description: OK
      tags:
      - Activity
      - UserComments
  /rest/?method=flickr.galleries.editMeta:
    post:
      summary: Galleries Edit Meta
      description: Modify the metadata for a gallery.
      operationId: postRestMethodFlickr.galleries.editmeta
      x-api-path-slug: restmethodflickr-galleries-editmeta-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: description
        description: The new description for the gallery
      - in: query
        name: gallery_id
        description: The gallery ID to update
      - in: query
        name: title
        description: The new title for the gallery
      responses:
        200:
          description: OK
      tags:
      - Galleries
      - EditMeta
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