---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  description: the-meetup-api-provides-simple-restful-http-and-streaming-interfaces-for-exploring-and-interacting-meetup-platform-from-your-own-apps--the-api-is-a-set-of-core-methods-and-a-common-request-format--these-are-combined-to-form-a-url-that-returns-the-information-you-want--
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /members:
    get:
      summary: Members
      description: API method for accessing members of Meetup Groups
      operationId: deprecated
      x-api-path-slug: members-get
      parameters:
      - in: query
        name: fields
        description: Request that additional fields (separated by commas) be included
          in the output
        type: string
      - in: query
        name: group_id
        description: Return members in groups with these ID numbers, separated by
          commas
        type: string
      - in: query
        name: group_urlname
        description: Return members for the group with the given custom URL path
        type: string
      - in: query
        name: member_id
        description: Return the member with this ID
        type: string
      - in: query
        name: relation
        description: Supply the string self as the value for this parameter to get
          the information of the member linked to the API key making the request
        type: string
      - in: query
        name: service
        description: Match users by the external services theyve linked to their member
          account, specified as servicename:identifier
        type: string
      - in: query
        name: topic,groupnum
        description: Return members for the group with given topic and number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
      - Members
  /2/members:
    get:
      summary: Members
      description: API method for accessing members of Meetup Groups
      operationId: members
      x-api-path-slug: 2members-get
      parameters:
      - in: query
        name: fields
        description: Request that additional fields (separated by commas) be included
          in the output
        type: string
      - in: query
        name: group_id
        description: Return members in groups with these ID numbers, separated by
          commas
        type: string
      - in: query
        name: group_urlname
        description: Return members for the group with the given custom URL path
        type: string
      - in: query
        name: member_id
        description: Return the member with this ID
        type: string
      - in: query
        name: service
        description: Match users by the external services theyve linked to their member
          account, specified as servicename:identifier
        type: string
      - in: query
        name: topic,groupnum
        description: Return members for the group with given topic and number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
      - Member
  /2/member/:id:
    get:
      summary: Member Get
      description: Retrieve a single member
      operationId: members
      x-api-path-slug: 2memberid-get
      parameters:
      - in: query
        name: fields
        description: comma-separate list of optional fields
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
      - Member
    post:
      summary: Member Edit
      description: Edit the authorized member's attributes
      operationId: members
      x-api-path-slug: 2memberid-post
      parameters:
      - in: query
        name: add_topics
        description: Comma-delimited list of topics ids to add to your alert list
        type: string
      - in: query
        name: bio
        description: Free form text passage about you
        type: string
      - in: query
        name: bio_privacy
        description: Controls the visibility of the members bio
        type: string
      - in: query
        name: birthday
        description: Day you were born
        type: string
      - in: query
        name: city
        description: City name for your location
        type: string
      - in: query
        name: city_id
        description: Valid city id from /2/cities method
        type: string
      - in: query
        name: country
        description: Valid country code for your location
        type: string
      - in: query
        name: facebook_privacy
        description: Controls the visibility of the members facebook connection
        type: string
      - in: query
        name: gender
        description: Your gender (used for better recommendations)
        type: string
      - in: query
        name: groups_privacy
        description: Controls the visibility of the members groups
        type: string
      - in: query
        name: hometown
        description: Hometown of member
        type: string
      - in: query
        name: lang
        description: Language preference used on the site
        type: string
      - in: query
        name: lat
        description: latitude of city
        type: string
      - in: query
        name: lon
        description: longitude of city
        type: string
      - in: query
        name: messaging_pref
        description: This specifies the members preference for being contacted from
          members on the site
        type: string
      - in: query
        name: name
        description: The name of the current member
        type: string
      - in: query
        name: photos_privacy
        description: Controls the visibility of the members photos
        type: string
      - in: query
        name: photo_id
        description: A valid photo_id from the members photos to set as the main profile
          photo
        type: string
      - in: query
        name: radius
        description: radius, in miles to search for city given a lat and lon
        type: string
      - in: query
        name: remove_topics
        description: Comma-delimited list of topic ids to remove from your alert list
        type: string
      - in: query
        name: sync_photo
        description: When set to true, this parameter will sync all of the group profile
          photos for the member with the provided photo_id
        type: string
      - in: query
        name: topics_privacy
        description: Controls the visibility of the members topics
        type: string
      - in: query
        name: zip
        description: Valid zip code for city
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
      - Member
  /comments:
    get:
      summary: Comments
      description: API method for accessing meetup group comments
      operationId: groups
      x-api-path-slug: comments-get
      parameters:
      - in: query
        name: group_id
        description: Return comments in groups with these ID numbers [separated by
          commas]
        type: string
      - in: query
        name: group_urlname
        description: Return comments for the group with this custom URL path
        type: string
      - in: query
        name: topic, groupnum
        description: Return comments for the group with given topic and number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comments:
    get:
      summary: Comments v2
      description: This method returns messages that appear under Talk about this
        Meetup. To post messages, see the corresponding write method.
      operationId: events
      x-api-path-slug: 2event-comments-get
      parameters:
      - in: query
        name: api_version
        description: "2"
        type: string
      - in: query
        name: callback
        description: Name of a function to be called with an array of Event Comment
          notification objects
        type: string
      - in: query
        name: comment_id
        description: Return comments for a given set of comment IDs, separated by
          commas
        type: string
      - in: query
        name: event_id
        description: Limit notifications to a specific event id
        type: string
      - in: query
        name: event_id
        description: Return comments on these events, separated by commas
        type: string
      - in: query
        name: fields
        description: Optionally accepts the value member_photo or notifications
        type: string
      - in: query
        name: group_id
        description: Return comments in groups with these ID numbers, separated by
          commas
        type: string
      - in: query
        name: member_id
        description: Return comments for the given member_ids, separated by commas
        type: string
      - in: query
        name: since_count
        description: Request that some number of recent messages be sent immediately,
          if available
        type: string
      - in: query
        name: since_mtime
        description: Should be supplied for all but the first polling request, so
          that any missed notifications are can be sent in an immediate response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
    ws:
      summary: WebSockets Event Comments Stream
      description: |-
        For browsers that support it, [WebSockets](http://dev.w3.org/html5/websockets/) is a more
        efficient alternative to the long-polling stream. This is a **push only** endpoint and will discard
        any messages received from the client after the socket is open.

        Because browser support for WebSockets is limited, we recommend that you consume this stream
        through the [must.js](https://github.com/meetup/must.js#readme) client, which can fallback to long-polling.
      operationId: streams
      x-api-path-slug: 2event-comments-ws
      parameters:
      - in: query
        name: api_version
        description: "2"
        type: string
      - in: query
        name: event_id
        description: Limit notifications to a specific event id
        type: string
      - in: query
        name: since_count
        description: Request that some number of recent messages be sent immediately,
          if available
        type: string
      - in: query
        name: since_mtime
        description: Return recent Event Comments with an mtime greater than the supplied
          time, in milliseconds since the epoch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment:
    post:
      summary: Event Comment v2
      description: This method posts messages that appear under Talk about this Meetup.
      operationId: events
      x-api-path-slug: 2event-comment-post
      parameters:
      - in: query
        name: comment
        description: The comment text
        type: string
      - in: query
        name: event_id
        description: The event related to this comment
        type: string
      - in: query
        name: in_reply_to
        description: If this comment is a reply, the ID of the comment being replied
          to
        type: string
      - in: query
        name: notifications
        description: Notification control for authorized member on this comment thread
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment/:id:
    get:
      summary: Event Comment Get
      description: Retrieve a single event comment or reply
      operationId: events
      x-api-path-slug: 2event-commentid-get
      parameters:
      - in: query
        name: fields
        description: comma-separate list of optional fields
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
    delete:
      summary: Event Comment Delete
      description: Delete a single event comment or reply
      operationId: events
      x-api-path-slug: 2event-commentid-delete
      parameters:
      - in: query
        name: fields
        description: comma-separate list of optional fields
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment_flag:
    post:
      summary: Event Comment Flag
      description: This method creates a spam report for comment content
      operationId: events
      x-api-path-slug: 2event-comment-flag-post
      parameters:
      - in: query
        name: comment_id
        description: The id of the comment
        type: string
      - in: query
        name: reason
        description: Reason for flagging the comment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment_subscribe/:id:
    delete:
      summary: Event Comment Unsubscribe
      description: Unsubscribe to notifications for updates to a given comment thread
      operationId: events
      x-api-path-slug: 2event-comment-subscribeid-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment_like/:id:
    post:
      summary: Event Comment Like
      description: Like a given Event comment
      operationId: events
      x-api-path-slug: 2event-comment-likeid-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
    delete:
      summary: Event Comment Unlike
      description: Unlike a given Event comment
      operationId: events
      x-api-path-slug: 2event-comment-likeid-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/event_comment_likes:
    get:
      summary: Comment Likes
      description: Api for listing likes of a given event comment
      operationId: events
      x-api-path-slug: 2event-comment-likes-get
      parameters:
      - in: query
        name: comment_id
        description: Return likes for a given comment_id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /2/photo_comment:
    post:
      summary: Photo Comment v2
      description: This method posts comments that appear below photos
      operationId: photos
      x-api-path-slug: 2photo-comment-post
      parameters:
      - in: query
        name: comment
        description: The comment text
        type: string
      - in: query
        name: photo_id
        description: The photo related to this comment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
      - Comments
  /2/photo_albums:
    get:
      summary: Photo Albums
      description: This method returns photo albums associated with Meetup groups.
        To create albums, see the corresponding write method.
      operationId: photos
      x-api-path-slug: 2photo-albums-get
      parameters:
      - in: query
        name: event_id
        description: Return photo albums for these event ids, separated by commas
        type: string
      - in: query
        name: group_id
        description: Return albums in groups with these ID, separated by commas
        type: string
      - in: query
        name: photo_album_id
        description: Return albums with these IDs, separated by commas
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
      - Comments
  /2/member_photo:
    post:
      summary: Member Photo Upload
      description: Uploads a photo to be associated with a Member
      operationId: members
      x-api-path-slug: 2member-photo-post
      parameters:
      - in: query
        name: await
        description: If true, this ensures a response will not be returned until the
          upload is accessible
        type: string
      - in: query
        name: main
        description: Set to true to have this photo become the members main profile
          photo
        type: string
      - in: query
        name: photo
        description: The photo, encoded as multipart/form-data
        type: string
      - in: query
        name: sync_matching_photo
        description: When set to true and main is set to true, this will replace all
          group profile photos matching the current photo with the provided replacement
        type: string
      - in: query
        name: sync_photo
        description: When set to true, this parameter will sync all of the group profile
          photos for the member with the provided photo_id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Groups
      - Member
  /oembed:
    get:
      summary: oEmbed
      description: oEmbed implementation
      operationId: oembed
      x-api-path-slug: oembed-get
      parameters:
      - in: query
        name: maxwidth
        description: maximum width to display
        type: string
      - in: query
        name: url
        description: url of resource to be embedded
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - oEmbed
      - Media
  /self/blocks/:member_id:
    post:
      summary: Block member
      description: Blocks a target member from various interactions with the authenticated
        member on the platform
      operationId: abuse
      x-api-path-slug: selfblocksmember-id-post
      parameters:
      - in: query
        name: comments
        description: An optional string of text describing why you have chosen to
          block this member
        type: string
      - in: query
        name: report
        description: An optional value that represents a type of abuse the target
          member is being blocked for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Abuse
      - Members
    delete:
      summary: Unblock member
      description: Unblocks a previously blocked member from various interactions
        with the authenticated member on the platform
      operationId: abuse
      x-api-path-slug: selfblocksmember-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Abuse
      - Members
  /:urlname/member/approvals:
    post:
      summary: Membership Approval
      description: Approves one or more requests for group membership
      operationId: profiles
      x-api-path-slug: urlnamememberapprovals-post
      parameters:
      - in: query
        name: member
        description: Comma-delimited numeric pending member IDs
        type: string
      - in: query
        name: send_copy
        description: Optional boolean value indicating whether or not the org should
          receive a copy of the message sent to the approved members
        type: string
      - in: query
        name: welcome_message
        description: Optional message to send to the members being approved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members
    delete:
      summary: Membership Decline
      description: Declines one or more requests for group membership
      operationId: profiles
      x-api-path-slug: urlnamememberapprovals-delete
      parameters:
      - in: query
        name: anon
        description: Optional Boolean value indicating whether the declining members
          email address should be hidden in the resulting response
        type: string
      - in: query
        name: ban
        description: Optional Boolean value indicating whether or not to ban the member
          in the future
        type: string
      - in: query
        name: explanation
        description: Optional explanation to send to the members being declined
        type: string
      - in: query
        name: member
        description: Comma-delimited numeric pending member IDs
        type: string
      - in: query
        name: send_copy
        description: Optional Boolean value indicating whether or not to send a copy
          to the member issuing the decline
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members
  /self/events:
    get:
      summary: Member Events
      description: |-
        Gets a listing of all scheduled Meetup Events the authenticated member has RSVP'd to
        that have been announced to the group.
        This listing is ordered from oldest to most recent by default
      operationId: events
      x-api-path-slug: selfevents-get
      parameters:
      - in: query
        name: desc
        description: When true, sorts results in descending order
        type: string
      - in: query
        name: fields
        description: A comma-delimited list of optional fields names which may be
          appended to the response
        type: string
      - in: query
        name: page
        description: Number of results to return
        type: string
      - in: query
        name: rsvp
        description: Comma-delimited list of RSVP responses
        type: string
      - in: query
        name: scroll
        description: A string representing an alias for a point on a timeline
        type: string
      - in: query
        name: status
        description: Comma-delimited list of event statuses
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members
  /:urlname/events/:event_id/comments:
    get:
      summary: Event Comments List
      description: |-
        Lists the comments and replies posted in a given Meetup Event.

        To view the list of likes for a comment or reply
        see the [likes](/meetup_api/docs/:urlname/events/:event_id/comments/:comment_id/likes/)
        endpoint
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcomments-get
      parameters:
      - in: query
        name: fields
        description: A comma-delimited list of optional fields to append to the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
    post:
      summary: Event comment and reply
      description: Creates new comments and replies to existing comments within an
        Meetup event
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcomments-post
      parameters:
      - in: query
        name: comment
        description: The text of the comment in at most 1024 characters
        type: string
      - in: query
        name: in_reply_to
        description: If posting a reply, set this to the numeric identifier of the
          associated top level comment
        type: string
      - in: query
        name: notifications
        description: A boolean value indicating whether or not you wish to recieve
          future notifications about updates to this comment thread
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /:urlname/events/:event_id/comments/:comment_id:
    delete:
      summary: Event comment delete
      description: Deletes comments posted in events
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcommentscomment-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /:urlname/events/:id/payments:
    post:
      summary: Event Payments
      description: Allows organizers of a group to note payments made by members for
        an event. This is the 'Mark Paid' feature seen in the RSVP listings on event
        details pages and affects the 'pay_status' response fields in [2/rsvps](/meetup_api/docs/2/rsvps/#response)
        for paid events
      operationId: events
      x-api-path-slug: urlnameeventsidpayments-post
      parameters:
      - in: query
        name: amount
        description: The monetary amount of money the member submitted
        type: string
      - in: query
        name: member
        description: Member Id of member who made a payment
        type: string
      - in: query
        name: paid_on
        description: The time the payment was made in milliseconds from the epoc
        type: string
      - in: query
        name: quantity
        description: The number of payments made
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Payments
  /self/calendar:
    get:
      summary: Member Calendar
      description: Get a listing of all upcoming Meetup events for the authenticated
        member
      operationId: events
      x-api-path-slug: selfcalendar-get
      parameters:
      - in: query
        name: fields
        description: A comma-delimited list of optional fields names which may be
          appended to the response
        type: string
      - in: query
        name: page
        description: Number of results to return in a page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members
      - Calendardars
  /self/groups:
    get:
      summary: Member groups
      description: |-
        Lists the authenticated member's groups in the order of leadership,
        next upcoming event, then alphabetical order by name
      operationId: groups
      x-api-path-slug: selfgroups-get
      parameters:
      - in: query
        name: fields
        description: A comma-delimited list of optional fields to append to the response
        type: string
      - in: query
        name: page
        description: Number of groups to return in a single page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members
      - Groups
  /:urlname/events/:event_id/comments/:comment_id/likes:
    get:
      summary: Event Comment and Reply Likes
      description: Returns lists of likes for an event comment or reply
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcommentscomment-idlikes-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
    delete:
      summary: Event Comment Unlike
      description: Unlike a given event comment
      operationId: comments
      x-api-path-slug: urlnameeventsevent-idcommentscomment-idlikes-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Comments
  /:urlname/events/:event_id/photos/:photo_id/comments:
    post:
      summary: Photo Comment
      description: Creates a new photo comment
      operationId: photos
      x-api-path-slug: urlnameeventsevent-idphotosphoto-idcomments-post
      parameters:
      - in: query
        name: comment
        description: The text of the comment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
      - Comments
    get:
      summary: Photo Comments
      description: Lists photo comments associated with a photo
      operationId: photos
      x-api-path-slug: urlnameeventsevent-idphotosphoto-idcomments-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
      - Comments
  /:urlname/events/:event_id/photos/:photo_id/comments/:comment_id:
    delete:
      summary: Photo Comment Delete
      description: Deletes photo comments
      operationId: photos
      x-api-path-slug: urlnameeventsevent-idphotosphoto-idcommentscomment-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
      - Comments
  /recommended/events:
    get:
      summary: Recommended Events
      description: Returns a list of upcoming recommended events
      operationId: deprecated
      x-api-path-slug: recommendedevents-get
      parameters:
      - in: query
        name: fields
        description: A comma-delimited list of optional fields to populate in the
          response
        type: string
      - in: query
        name: lat
        description: Approximate target latitude
        type: string
      - in: query
        name: lon
        description: Approximate target longitude
        type: string
      - in: query
        name: page
        description: A target minimum number of events to return in a single page
          of results
        type: string
      - in: query
        name: self_groups
        description: Boolean indicator of whether or not to include events within
          your existing Meetup network
        type: string
      - in: query
        name: topic_category
        description: Numeric topic category identifier for filtering recommendations
          by a topic category
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Recomendations
  /recommended/group_topics:
    get:
      summary: Recommend Group Topics
      description: Recommends suggestions for group topics based on a text search
        or other topics
      operationId: topics
      x-api-path-slug: recommendedgroup-topics-get
      parameters:
      - in: query
        name: exclude_topics
        description: A comma-delimited list of topic ids to exclude from the recommendations
        type: string
      - in: query
        name: lang
        description: Defines a language preference for ordering results
        type: string
      - in: query
        name: other_topics
        description: A comma-delimited list of topic ids to inform recommendations
        type: string
      - in: query
        name: page
        description: Target number of recommendations to return
        type: string
      - in: query
        name: text
        description: Free form text search
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Recomendations
      - Groups
      - Topics
  /recommended/groups:
    get:
      summary: Recommended Groups
      description: Returns groups Meetup finds relevant to you
      operationId: groups
      x-api-path-slug: recommendedgroups-get
      parameters:
      - in: query
        name: category
        description: A valid category id which limits recommended groups to a particular
          category
        type: string
      - in: query
        name: country
        description: A valid two character country code, defaults to US
        type: string
      - in: query
        name: fields
        description: Request that additional fields (separated by commas) be included
          in the output
        type: string
      - in: query
        name: instant_join_only
        description: Recommend only groups without join requirements and that can
          be joined instantly
        type: string
      - in: query
        name: lat
        description: Approximate latitude
        type: string
      - in: query
        name: location
        description: Raw text location query
        type: string
      - in: query
        name: lon
        description: Approximate longitude
        type: string
      - in: query
        name: radius
        description: Radius in miles
        type: string
      - in: query
        name: sort
        description: How to order the results
        type: string
      - in: query
        name: topic_id
        description: Comma delimited list of up to 100 topic ids to help inform recommendations
        type: string
      - in: query
        name: zip
        description: Zip code you are searching for recommendations in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Recomendations
      - Groups
  /recommended/groups/ignores/:urlname:
    post:
      summary: Recommended Groups Ignore
      description: Provides a form of feedback by requesting to remove a group from
        future recommendations
      operationId: groups
      x-api-path-slug: recommendedgroupsignoresurlname-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Recomendations
      - Groups
  /recommended/venues:
    get:
      summary: Recommended Venues
      description: Returns venues Meetup finds relevant to you based on location and
        category. This method does not yet support sorting or pagination.
      operationId: venues
      x-api-path-slug: recommendedvenues-get
      parameters:
      - in: query
        name: category
        description: Comma-delimited list of up to 200 category ids to help inform
          recommendations
        type: string
      - in: query
        name: country
        description: A valid two character country code, defaults to US
        type: string
      - in: query
        name: group_id
        description: Comma-delimited list of up to 200 group ids to help inform recommendations
        type: string
      - in: query
        name: group_urlname
        description: Comma-delimited list of up to 200 group urlnames to help inform
          recommendations
        type: string
      - in: query
        name: lat
        description: Approximate latitude
        type: string
      - in: query
        name: location
        description: Raw text location query
        type: string
      - in: query
        name: lon
        description: Approximate longitude
        type: string
      - in: query
        name: min_groups
        description: The minimum number of groups that have hosted events at this
          venue
        type: string
      - in: query
        name: radius
        description: Radius in miles
        type: string
      - in: query
        name: used_between
        description: Return venues that have been used within the given time range,
          defined by two times separated with a single comma
        type: string
      - in: query
        name: zip
        description: Zip code you are searching for recommendations in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Recomendations
      - Venues
---