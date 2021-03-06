---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 0
info:
  title: Context.IO Get Accounts Messages
  description: 'Lists email messages for an account. List filters: each of the email,
    to, from, cc and bcc parameters can be set to a comma-separated list of email
    addresses. These multiple addresses are treated as an OR combination. You can
    set more than one parameter when doing this call. Multiple parameters are treated
    as an AND combination.'
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/contacts/{email}/messages:
    get:
      summary: Get Accounts Contacts Email Messages
      description: Lists messages where a contact is present. Returns the latest email
        messages exchanged with one or more email addresses. By "exchanged with Mr.
        X" we mean any email received from Mr. X, sent to Mr. X or sent by anyone
        to both Mr. X and the mailbox owner.
      operationId: listAccountContactMessages_
      x-api-path-slug: accountsidcontactsemailmessages-get
      parameters:
      - in: path
        name: email
        description: Email address of a contact
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: query
        name: limit
        description: The maximum number of results to return
      - in: query
        name: offset
        description: Start the list at this offset (zero-based)
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Contacts
      - Email
      - Messages
  /accounts/{id}/messages:
    get:
      summary: Get Accounts Messages
      description: 'Lists email messages for an account. List filters: each of the
        email, to, from, cc and bcc parameters can be set to a comma-separated list
        of email addresses. These multiple addresses are treated as an OR combination.
        You can set more than one parameter when doing this call. Multiple parameters
        are treated as an AND combination.'
      operationId: listAccountMessages_
      x-api-path-slug: accountsidmessages-get
      parameters:
      - in: query
        name: bcc
        description: Email address of a contact BCCed on the messages
      - in: query
        name: body_type
        description: Used when include_body is set to get only body parts of a given
          MIME-type (i
      - in: query
        name: cc
        description: Email address of a contact CCed on the messages
      - in: query
        name: date_after
        description: Only include messages after a given timestamp
      - in: query
        name: date_before
        description: Only include messages before a given timestamp
      - in: query
        name: email
        description: Email address of the contact for whom you want the latest messages
          exchanged with
      - in: query
        name: folder
        description: Filter messages by the folder (or Gmail label)
      - in: query
        name: from
        description: Email address of a contact messages have been received from
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: query
        name: include_body
        description: Set to 1 to include message bodies in the result
      - in: query
        name: include_flags
        description: Set to 1 to include IMAP flags for this message in the result
      - in: query
        name: include_headers
        description: Can be set to 0 (default), 1 or raw
      - in: query
        name: indexed_after
        description: Only include messages indexed after a given timestamp
      - in: query
        name: indexed_before
        description: Only include messages indexed before a given timestamp
      - in: query
        name: limit
        description: The maximum number of results to return
      - in: query
        name: offset
        description: Start the list at this offset (zero-based)
      - in: query
        name: subject
        description: Get messages whose subject matches this search string
      - in: query
        name: to
        description: Email address of a contact messages have been sent to
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Messages
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