---
swagger: "2.0"
x-collection-name: Datadog
x-complete: 1
info:
  title: DataDog Merged API
  version: 1.0.0
basePath: api/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metrics:
    get:
      summary: Get Metrics
      description: Get the list of actively reporting metrics from a given time until
        now. This endpoint is not available in the Python and Ruby libraries.
      operationId: getMetrics
      x-api-path-slug: metrics-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Metrics
  /downtime:
    post:
      summary: Add Downtime
      description: Schedule monitor downtime
      operationId: postDowntime
      x-api-path-slug: downtime-post
      parameters:
      - in: query
        name: period
        description: how often to repeat as an integer
        type: string
      - in: query
        name: type
        description: the type of recurrence
        type: string
      - in: query
        name: until_date
        description: (optional) the date at which the recurrence should end as a POSIX
          timestmap
        type: string
      - in: query
        name: until_occurrences
        description: (optional) how many times the downtime will be rescheduled
        type: string
      - in: query
        name: week_days
        description: (optional) a list of week days to repeat on
        type: string
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
    get:
      summary: Get Downtime
      description: Get all monitor downtimes
      operationId: getDowntime
      x-api-path-slug: downtime-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
  /downtime/:downtime_id:
    put:
      summary: Put Downtime Downtime
      description: Update monitor downtime
      operationId: putDowntimeDowntime
      x-api-path-slug: downtimedowntime-id-put
      parameters:
      - in: query
        name: period
        description: how often to repeat as an integer
        type: string
      - in: query
        name: type
        description: the type of recurrence
        type: string
      - in: query
        name: until_date
        description: (optional) the date at which the recurrence should end as a POSIX
          timestmap
        type: string
      - in: query
        name: until_occurrences
        description: (optional) how many times the downtime will be rescheduled
        type: string
      - in: query
        name: week_days
        description: (optional) a list of week days to repeat on
        type: string
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
      - Downtime
    delete:
      summary: Delete Downtime Downtime
      description: DELETE downtime downtime
      operationId: deleteDowntimeDowntime
      x-api-path-slug: downtimedowntime-id-delete
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
      - Downtime
    get:
      summary: Get Downtime Downtime
      description: Get a monitor downtime
      operationId: getDowntimeDowntime
      x-api-path-slug: downtimedowntime-id-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Downtime
      - Downtime
  /tags/hosts/:host_name:
    get:
      summary: Get Tags Hosts Host Name
      description: Return the list of tags that apply to a given host.
      operationId: getTagsHostsHostName
      x-api-path-slug: tagshostshost-name-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Tags
      - Hosts
      - Host
      - Name
    post:
      summary: Add Tags Hosts Host Name
      description: This end point allows you to add tags to a host.
      operationId: postTagsHostsHostName
      x-api-path-slug: tagshostshost-name-post
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Tags
      - Hosts
      - Host
      - Name
    put:
      summary: Put Tags Hosts Host Name
      description: This end point allows you to update all tags for a given host.
      operationId: putTagsHostsHostName
      x-api-path-slug: tagshostshost-name-put
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Tags
      - Hosts
      - Host
      - Name
    delete:
      summary: Delete Tags Hosts Host Name
      description: This end point allows you to remove all tags for a given host.
      operationId: deleteTagsHostsHostName
      x-api-path-slug: tagshostshost-name-delete
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Tags
      - Hosts
      - Host
      - Name
  comments:
    post:
      summary: Add Comments
      description: |-
        Comments are essentially special forms of events that
                  appear in the stream. They can start a new discussion thread or
                  optionally, reply in another thread.
      operationId: postComments
      x-api-path-slug: comments-post
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Comments
  comments/:comment_id:
    put:
      summary: Put Comments Comment
      description: PUT comments comment
      operationId: putCommentsComment
      x-api-path-slug: commentscomment-id-put
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Comments
      - Comment
    delete:
      summary: Delete Comments Comment
      description: DELETE comments comment
      operationId: deleteCommentsComment
      x-api-path-slug: commentscomment-id-delete
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - Comments
      - Comment
---