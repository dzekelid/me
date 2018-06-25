---
name: Meetup
x-slug: meetup
description: Find Meetups so you can do more of what matters to you. Or create your
  own group and meet people near you who share your interests.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
x-kinRank: "9"
x-alexaRank: "917"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/apis.md
specificationVersion: "0.14"
apis:
- name: Meetup Members
  x-api-slug: meetup
  description: API method for accessing members of Meetup Groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////members
  tags: Events,Groups,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/members-get-openapi.md
- name: Meetup Members
  x-api-slug: meetup
  description: API method for accessing members of Meetup Groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/members
  tags: Events,Groups,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2members-get-openapi.md
- name: Meetup Member Get
  x-api-slug: meetup
  description: Retrieve a single member
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/member/:id
  tags: Events,Groups,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2memberid-get-openapi.md
- name: Meetup Member Edit
  x-api-slug: meetup
  description: Edit the authorized member's attributes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/member/:id
  tags: Events,Groups,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2memberid-post-openapi.md
- name: Meetup Comments
  x-api-slug: meetup
  description: API method for accessing meetup group comments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////comments
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/comments-get-openapi.md
- name: Meetup Comments v2
  x-api-slug: meetup
  description: This method returns messages that appear under Talk about this Meetup.
    To post messages, see the corresponding write method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comments
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comments-get-openapi.md
- name: Meetup Event Comment v2
  x-api-slug: meetup
  description: This method posts messages that appear under Talk about this Meetup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-post-openapi.md
- name: Meetup Event Comment Get
  x-api-slug: meetup
  description: Retrieve a single event comment or reply
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment/:id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-commentid-get-openapi.md
- name: Meetup Event Comment Delete
  x-api-slug: meetup
  description: Delete a single event comment or reply
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment/:id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-commentid-delete-openapi.md
- name: Meetup Event Comment Flag
  x-api-slug: meetup
  description: This method creates a spam report for comment content
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment_flag
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-flag-post-openapi.md
- name: Meetup Event Comment Unsubscribe
  x-api-slug: meetup
  description: Unsubscribe to notifications for updates to a given comment thread
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment_subscribe/:id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-subscribeid-delete-openapi.md
- name: Meetup Event Comment Like
  x-api-slug: meetup
  description: Like a given Event comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment_like/:id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-likeid-post-openapi.md
- name: Meetup Event Comment Unlike
  x-api-slug: meetup
  description: Unlike a given Event comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment_like/:id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-likeid-delete-openapi.md
- name: Meetup Comment Likes
  x-api-slug: meetup
  description: Api for listing likes of a given event comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comment_likes
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comment-likes-get-openapi.md
- name: Meetup Photo Comment v2
  x-api-slug: meetup
  description: This method posts comments that appear below photos
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/photo_comment
  tags: Events,Photos,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2photo-comment-post-openapi.md
- name: Meetup Photo Albums
  x-api-slug: meetup
  description: This method returns photo albums associated with Meetup groups. To
    create albums, see the corresponding write method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/photo_albums
  tags: Events,Photos,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2photo-albums-get-openapi.md
- name: Meetup Member Photo Upload
  x-api-slug: meetup
  description: Uploads a photo to be associated with a Member
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/member_photo
  tags: Events,Groups,Member
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2member-photo-post-openapi.md
- name: Meetup oEmbed
  x-api-slug: meetup
  description: oEmbed implementation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////oembed
  tags: Events,oEmbed,Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/oembed-get-openapi.md
- name: Meetup WebSockets Event Comments Stream
  x-api-slug: meetup
  description: |-
    For browsers that support it, [WebSockets](http://dev.w3.org/html5/websockets/) is a more
    efficient alternative to the long-polling stream. This is a **push only** endpoint and will discard
    any messages received from the client after the socket is open.

    Because browser support for WebSockets is limited, we recommend that you consume this stream
    through the [must.js](https://github.com/meetup/must.js#readme) client, which can fallback to long-polling.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////2/event_comments
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/2event-comments-ws-openapi.md
- name: Meetup Block member
  x-api-slug: meetup
  description: Blocks a target member from various interactions with the authenticated
    member on the platform
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////self/blocks/:member_id
  tags: Events,Abuse,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/selfblocksmember-id-post-openapi.md
- name: Meetup Unblock member
  x-api-slug: meetup
  description: Unblocks a previously blocked member from various interactions with
    the authenticated member on the platform
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////self/blocks/:member_id
  tags: Events,Abuse,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/selfblocksmember-id-delete-openapi.md
- name: Meetup Membership Approval
  x-api-slug: meetup
  description: Approves one or more requests for group membership
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/member/approvals
  tags: Events,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnamememberapprovals-post-openapi.md
- name: Meetup Membership Decline
  x-api-slug: meetup
  description: Declines one or more requests for group membership
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/member/approvals
  tags: Events,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnamememberapprovals-delete-openapi.md
- name: Meetup Member Events
  x-api-slug: meetup
  description: |-
    Gets a listing of all scheduled Meetup Events the authenticated member has RSVP'd to
    that have been announced to the group.
    This listing is ordered from oldest to most recent by default
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////self/events
  tags: Events,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/selfevents-get-openapi.md
- name: Meetup Event Comments List
  x-api-slug: meetup
  description: |-
    Lists the comments and replies posted in a given Meetup Event.

    To view the list of likes for a comment or reply
    see the [likes](/meetup_api/docs/:urlname/events/:event_id/comments/:comment_id/likes/)
    endpoint
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/comments
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idcomments-get-openapi.md
- name: Meetup Event comment and reply
  x-api-slug: meetup
  description: Creates new comments and replies to existing comments within an Meetup
    event
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/comments
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idcomments-post-openapi.md
- name: Meetup Event comment delete
  x-api-slug: meetup
  description: Deletes comments posted in events
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/comments/:comment_id
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idcommentscomment-id-delete-openapi.md
- name: Meetup Event Payments
  x-api-slug: meetup
  description: Allows organizers of a group to note payments made by members for an
    event. This is the 'Mark Paid' feature seen in the RSVP listings on event details
    pages and affects the 'pay_status' response fields in [2/rsvps](/meetup_api/docs/2/rsvps/#response)
    for paid events
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:id/payments
  tags: Events,Payments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsidpayments-post-openapi.md
- name: Meetup Member Calendar
  x-api-slug: meetup
  description: Get a listing of all upcoming Meetup events for the authenticated member
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////self/calendar
  tags: Events,Members,Calendardars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/selfcalendar-get-openapi.md
- name: Meetup Member groups
  x-api-slug: meetup
  description: |-
    Lists the authenticated member's groups in the order of leadership,
    next upcoming event, then alphabetical order by name
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////self/groups
  tags: Events,Members,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/selfgroups-get-openapi.md
- name: Meetup Event Comment and Reply Likes
  x-api-slug: meetup
  description: Returns lists of likes for an event comment or reply
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/comments/:comment_id/likes
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idcommentscomment-idlikes-get-openapi.md
- name: Meetup Event Comment Unlike
  x-api-slug: meetup
  description: Unlike a given event comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/comments/:comment_id/likes
  tags: Events,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idcommentscomment-idlikes-delete-openapi.md
- name: Meetup Photo Comment
  x-api-slug: meetup
  description: Creates a new photo comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/photos/:photo_id/comments
  tags: Events,Photos,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idphotosphoto-idcomments-post-openapi.md
- name: Meetup Photo Comment Delete
  x-api-slug: meetup
  description: Deletes photo comments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/photos/:photo_id/comments/:comment_id
  tags: Events,Photos,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idphotosphoto-idcommentscomment-id-delete-openapi.md
- name: Meetup Photo Comments
  x-api-slug: meetup
  description: Lists photo comments associated with a photo
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////:urlname/events/:event_id/photos/:photo_id/comments
  tags: Events,Photos,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/urlnameeventsevent-idphotosphoto-idcomments-get-openapi.md
- name: Meetup Recommended Events
  x-api-slug: meetup
  description: Returns a list of upcoming recommended events
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////recommended/events
  tags: Events,Recomendations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/recommendedevents-get-openapi.md
- name: Meetup Recommend Group Topics
  x-api-slug: meetup
  description: Recommends suggestions for group topics based on a text search or other
    topics
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////recommended/group_topics
  tags: Events,Recomendations,Groups,Topics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/recommendedgroup-topics-get-openapi.md
- name: Meetup Recommended Groups
  x-api-slug: meetup
  description: Returns groups Meetup finds relevant to you
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////recommended/groups
  tags: Events,Recomendations,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/recommendedgroups-get-openapi.md
- name: Meetup Recommended Groups Ignore
  x-api-slug: meetup
  description: Provides a form of feedback by requesting to remove a group from future
    recommendations
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////recommended/groups/ignores/:urlname
  tags: Events,Recomendations,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/recommendedgroupsignoresurlname-post-openapi.md
- name: Meetup Recommended Venues
  x-api-slug: meetup
  description: Returns venues Meetup finds relevant to you based on location and category.
    This method does not yet support sorting or pagination.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com////recommended/venues
  tags: Events,Recomendations,Venues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/recommendedvenues-get-openapi.md
- name: Meetup
  x-api-slug: meetup
  description: Find Meetups so you can do more of what matters to you. Or create your
    own group and meet people near you who share your interests.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/6564-meetup.jpg
  humanURL: http://meetup.com
  baseURL: https://api.meetup.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/meetup/openapi.md
x-common:
- type: x-base
  url: http://api.meetup.com
- type: x-crunchbase
  url: https://crunchbase.com/organization/meetup
- type: x-developer
  url: http://www.meetup.com/meetup_api/
- type: x-email
  url: privacy@meetup.com
- type: x-email
  url: abuse@meetup.com
- type: x-email
  url: api_license@meetup.com
- type: x-email
  url: arbitration-opt-out@meetup.com
- type: x-email
  url: legal@meetup.com
- type: x-github
  url: https://github.com/meetup
- type: x-pricing
  url: http://www.meetup.com/pricing/
- type: x-privacy
  url: http://www.meetup.com/privacy/
- type: x-support
  url: http://www.meetup.com/help/
- type: x-terms-of-service
  url: http://www.meetup.com/terms/
- type: x-twitter
  url: https://twitter.com/MeetupAPI
- type: x-twitter
  url: https://twitter.com/Meetup
- type: x-website
  url: http://meetup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---