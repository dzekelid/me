---
swagger: "2.0"
x-collection-name: Mailgun
x-complete: 0
info:
  title: Mailgun API Posts Mime Message
  description: 'Posts a message in MIME format. Note: you will need to build a MIME
    string yourself. Use a MIME library for your programming language to do this.
    Pass the resulting MIME string as message parameter.'
  version: v2
host: api.mailgun.net
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  lists/{address}/members/:
    get:
      summary: List Members
      description: Fetches the list of mailing list members.
      operationId: getListsAddressMembers
      x-api-path-slug: listsaddressmembers-get
      parameters:
      - in: query
        name: limit
        description: Maximum number of records to return (100 by default)
      - in: query
        name: skip
        description: Records to skip (0 by default)
      - in: query
        name: subscribed
        description: yes to list subscribed, no for unsubscribed, list all if not
          set
      responses:
        200:
          description: OK
      tags:
      - List
      - Members
  lists/{address}/members/{member_address}:
    get:
      summary: List Member
      description: Retrieves a mailing list member.
      operationId: getListsAddressMembersMemberAddress
      x-api-path-slug: listsaddressmembersmember-address-get
      parameters:
      - in: query
        name: address
        description: Email address of commenter
      - in: query
        name: member_address
        description: Email address on the list
      responses:
        200:
          description: OK
      tags:
      - List
      - Member
  messages.mime:
    post:
      summary: Posts Mime Message
      description: 'Posts a message in MIME format. Note: you will need to build a
        MIME string yourself. Use a MIME library for your programming language to
        do this. Pass the resulting MIME string as message parameter.'
      operationId: postMessages.mime
      x-api-path-slug: messages-mime-post
      parameters:
      - in: query
        name: h:X-My-Header
        description: 'h: prefix followed by an arbitrary value allows to appendna
          custom MIME header to the message (X-My-Headernin this case)'
      - in: query
        name: message
        description: MIME string of the message
      - in: query
        name: o:campaign
        description: Id of the campaign the message belongs to
      - in: query
        name: o:deliverytime
        description: Desired time of delivery
      - in: query
        name: o:dkim
        description: Enables/disabled DKIM signatures on per-message basis
      - in: query
        name: o:tag
        description: Tag string
      - in: query
        name: o:testmode
        description: Enables sending in test mode
      - in: query
        name: o:tracking
        description: Toggles tracking on a per-message basis, seenTracking Messages
          for details
      - in: query
        name: o:tracking-clicks
        description: Toggles clicks tracking on a per-message basis
      - in: query
        name: o:tracking-opens
        description: Toggles opens tracking on a per-message basis
      - in: query
        name: to
        description: Email address of the recipient(s)
      - in: query
        name: v:my-var
        description: 'v: prefix followed by an arbitrary name allows tonattach a custom
          JSON data to the message'
      responses:
        200:
          description: OK
      tags:
      - S
      - Mime
      - Message
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