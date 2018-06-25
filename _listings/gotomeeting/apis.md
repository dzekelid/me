---
name: GoToMeeting
x-slug: gotomeeting
description: Citrix enables business mobility through the secure delivery of apps
  and data to any device on any network.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
x-kinRank: "7"
x-alexaRank: "7422"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/apis.md
specificationVersion: "0.14"
apis:
- name: Go To Meeting Get historical meetings by group
  x-api-slug: go-to-meeting
  description: 'Get historical meetings for the specified group that started within
    the specified date/time range. This API call is only available to users with the
    admin role. This API call is restricted to groups with a maximum of 50 organizers.
    Remark: Meetings which are still ongoing at the time of the request are NOT contained
    in the result array.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//groups/{groupKey}/historicalMeetings
  tags: Groups,GroupKey,HistoricalMeetings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/groupsgroupkeyhistoricalmeetings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/groupsgroupkeyhistoricalmeetings-get-openapi.md
- name: 'Go To Meeting DEPRECATED: Get historical meetings by group'
  x-api-slug: go-to-meeting
  description: 'DEPRECATED: Please use the new API calls ''Get historical meetings
    by group'' and ''Get upcoming meetings by group''. Get meetings for a specified
    group. Additional filters can be used to view only meetings within a specified
    date range. This API call is only available to users with the admin role.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//groups/{groupKey}/meetings
  tags: Groups,GroupKey,Meetings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/groupsgroupkeymeetings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/groupsgroupkeymeetings-get-openapi.md
- name: Go To Meeting Get upcoming meetings by group
  x-api-slug: go-to-meeting
  description: Get upcoming meetings for a specified group. This API call is only
    available to users with the admin role. This API call can be used only for groups
    with maximum 50 organizers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//groups/{groupKey}/upcomingMeetings
  tags: Groups,GroupKey,UpcomingMeetings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/groupsgroupkeyupcomingmeetings-get-openapi.md
- name: Go To Meeting Get historical meetings
  x-api-slug: go-to-meeting
  description: 'Get historical meetings for the currently authenticated organizer
    that started within the specified date/time range. Remark: Meetings which are
    still ongoing at the time of the request are NOT contained in the result array.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//historicalMeetings
  tags: HistoricalMeetings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/historicalmeetings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/historicalmeetings-get-openapi.md
- name: 'Go To Meeting DEPRECATED: Get historical meetings'
  x-api-slug: go-to-meeting
  description: 'DEPRECATED: Please use the new API calls ''Get historical meetings''
    and ''Get upcoming meetings''.  Gets historical meetings for the current authenticated
    organizer. Requires date range for filtering results to only meetings within specified
    dates. History searches will contain the parameter ''meetingInstanceKey'' which
    is used in conjunction with the call ''Get Attendees by Meeting'' to get attendee
    information for a past meeting.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings
  tags: Meetings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetings-get-openapi.md
- name: Go To Meeting Create meeting
  x-api-slug: go-to-meeting
  description: Create a new meeting based on the parameters specified.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings
  tags: Meetings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetings-post-openapi.md
- name: Go To Meeting Delete meeting
  x-api-slug: go-to-meeting
  description: Deletes the meeting identified by the meetingId.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings/{meetingId}
  tags: Meetings,MeetingId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetingsmeetingid-delete-openapi.md
- name: Go To Meeting Get meeting
  x-api-slug: go-to-meeting
  description: Returns the meeting details for the specified meeting.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings/{meetingId}
  tags: Meetings,MeetingId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetingsmeetingid-get-openapi.md
- name: Go To Meeting Update meeting
  x-api-slug: go-to-meeting
  description: Updates an existing meeting specified by meetingId.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings/{meetingId}
  tags: Meetings,MeetingId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetingsmeetingid-put-openapi.md
- name: Go To Meeting Get attendees by meeting
  x-api-slug: go-to-meeting
  description: List all attendees for specified meetingId of historical meeting. The
    historical meetings can be fetched using 'Get historical meetings', 'Get historical
    meetings by organizer', and 'Get historical meetings by group'. For users with
    the admin role this call returns attendees for any meeting. For any other user
    the call will return attendees for meetings on which the user is a valid organizer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings/{meetingId}/attendees
  tags: Meetings,MeetingId,Attendees
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetingsmeetingidattendees-get-openapi.md
- name: Go To Meeting Start meeting
  x-api-slug: go-to-meeting
  description: Returns a host URL that can be used to start a meeting. When this URL
    is opened in a web browser, the GoToMeeting client will be downloaded and launched
    and the meeting will start. The end user is not required to login to a client.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//meetings/{meetingId}/start
  tags: Meetings,MeetingId,Start
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/meetingsmeetingidstart-get-openapi.md
- name: Go To Meeting Get historical meetings by organizer
  x-api-slug: go-to-meeting
  description: 'Get historical meetings for the specified organizer that started within
    the specified date/time range. Remark: Meetings which are still ongoing at the
    time of the request are NOT contained in the result array.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//organizers/{organizerKey}/historicalMeetings
  tags: Organizers,OrganizerKey,HistoricalMeetings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeyhistoricalmeetings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeyhistoricalmeetings-get-openapi.md
- name: 'Go To Meeting DEPRECATED: Get meetings by organizer'
  x-api-slug: go-to-meeting
  description: 'DEPRECATED: Please use the new API calls ''Get historical meetings
    by organizer'' and ''Get upcoming meetings by organizer''. Gets future (scheduled)
    or past (history) meetings for a specified organizer. Include ''history=true''
    and the past start and end dates in the URL to retrieve past meetings. Enter ''scheduled=true''
    (without dates) to get scheduled meetings.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//organizers/{organizerKey}/meetings
  tags: Organizers,OrganizerKey,Meetings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeymeetings-get-openapi.md
- name: Go To Meeting Get upcoming meetings by organizer
  x-api-slug: go-to-meeting
  description: Get upcoming meetings for a specified organizer. This API call is only
    available to users with the admin role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//organizers/{organizerKey}/upcomingMeetings
  tags: Organizers,OrganizerKey,UpcomingMeetings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeyupcomingmeetings-get-openapi.md
- name: Go To Meeting Get upcoming meetings
  x-api-slug: go-to-meeting
  description: Gets upcoming meetings for the current authenticated organizer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest//upcomingMeetings
  tags: UpcomingMeetings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/upcomingmeetings-get-openapi.md
- name: Go To Meeting
  x-api-slug: go-to-meeting
  description: Citrix enables business mobility through the secure delivery of apps
    and data to any device on any network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2M/rest
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/openapi.md
- name: Go To Training Update Training Name and Description
  x-api-slug: go-to-training
  description: Request to update a scheduled training name and description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2T/rest//organizers/{organizerKey}/trainings/{trainingKey}/nameDescription
  tags: Organizers,OrganizerKey,Trainings,TrainingKey,NameDescription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeytrainingstrainingkeynamedescription-put-openapi.md
- name: Go To Training Update Training Times
  x-api-slug: go-to-training
  description: A request to update a scheduled training's start and end times. If
    the request contains 'notifyTrainers = true' and 'notifyRegistrants = true', both
    organizers and registrants are notified. The response provides the number of notified
    trainers and registrants.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2T/rest//organizers/{organizerKey}/trainings/{trainingKey}/times
  tags: Organizers,OrganizerKey,Trainings,TrainingKey,Times
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeytrainingstrainingkeytimes-put-openapi.md
- name: Go To Training
  x-api-slug: go-to-training
  description: Citrix enables business mobility through the secure delivery of apps
    and data to any device on any network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2T/rest
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/openapi.md
- name: Go To Webinar Get webinar meeting times
  x-api-slug: go-to-webinar
  description: Retrieves the meeting times for a webinar.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2W/rest//organizers/{organizerKey}/webinars/{webinarKey}/meetingtimes
  tags: Organizers,OrganizerKey,Webinars,WebinarKey,Meetingtimes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeywebinarswebinarkeymeetingtimes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/organizersorganizerkeywebinarswebinarkeymeetingtimes-get-openapi.md
- name: Go To Webinar
  x-api-slug: go-to-webinar
  description: Citrix enables business mobility through the secure delivery of apps
    and data to any device on any network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//G2W/rest
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/openapi.md
- name: SCIM Get Current User
  x-api-slug: scim
  description: Queries the identity of the current authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//identity/v1//Users/me
  tags: Users,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/usersme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/usersme-get-openapi.md
- name: SCIM Update Current User
  x-api-slug: scim
  description: Changes a limited set (or all if you choose) of the current authenticated
    user's data. The updated user email domain must be an existing organization email
    domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//identity/v1//Users/me
  tags: Users,Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/usersme-patch-openapi.md
- name: SCIM Replace Current User
  x-api-slug: scim
  description: Changes the current authenticated user's displayName, locale, timezone,
    username and password. The request must include the full user definition (to modify
    one or more values without sending the full definition, see Update User). The
    replaced user email domain must be an existing organization email domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//identity/v1//Users/me
  tags: Users,Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/usersme-put-openapi.md
- name: SCIM
  x-api-slug: scim
  description: Citrix enables business mobility through the secure delivery of apps
    and data to any device on any network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/731-gotomeeting.jpg
  humanURL: https://citrixonline.com
  baseURL: https://api.citrixonline.com//identity/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gotomeeting/openapi.md
x-common:
- type: x-base
  url: https://api.citrixonline.com
- type: x-blog
  url: http://blogs.citrix.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/citrix-systems
- type: x-crunchbase
  url: http://www.crunchbase.com/company/citrix-systems
- type: x-developer
  url: https://developer.citrixonline.com/
- type: x-email
  url: secure@citrix.com
- type: x-email
  url: americasconsulting@citrix.com
- type: x-email
  url: poland@citrix.com
- type: x-email
  url: citrix_ru@citrix.com
- type: x-email
  url: Licensing-emea@eu.citrix.com
- type: x-email
  url: eduardo.fleites@citrix.com
- type: x-email
  url: CitrixReady@citrix.com
- type: x-email
  url: CSP@citrix.com
- type: x-email
  url: partneroperationsEMEA@eu.citrix.com
- type: x-github
  url: https://github.com/citrix
- type: x-twitter
  url: https://twitter.com/gotomeeting
- type: x-twitter
  url: https://twitter.com/citrix
- type: x-website
  url: https://citrixonline.com
- type: x-website
  url: http://citrixonline.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---