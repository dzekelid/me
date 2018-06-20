---
name: Google Classroom
x-slug: google-classroom
description: Google Classroom is mission control for your classes. As a free service
  for teachers and students, you can create classes, distribute assignments, send
  feedback, and see everything in one place. Instant. Paperless. Easy.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-classroom.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-classroom/apis.md
specificationVersion: "0.14"
apis:
- name: Google Classroom API Modify Attachments
  x-api-slug: google-classroom-api
  description: |-
    Modifies attachments of student submission.

    Attachments may only be added to student submissions belonging to course
    work objects with a `workType` of `ASSIGNMENT`.

    This request must be made by the Developer Console project of the
    [OAuth client ID](https://support.google.com/cloud/answer/6158849) used to
    create the corresponding course work item.

    This method returns the following error codes:

    * `PERMISSION_DENIED` if the requesting user is not permitted to access the
    requested course or course work, if the user is not permitted to modify
    attachments on the requested student submission, or for
    access errors.
    * `INVALID_ARGUMENT` if the request is malformed.
    * `NOT_FOUND` if the requested course, course work, or student submission
    does not exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-classroom.png
  humanURL: https://classroom.google.com/
  baseURL: ://classroom.googleapis.com////v1/courses/{courseId}/courseWork/{courseWorkId}/studentSubmissions/{id}:modifyAttachments
  tags: Attachment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-classroom/v1coursescourseidcourseworkcourseworkidstudentsubmissionsidmodifyattachments-post-openapi.md
- name: Google Classroom API
  x-api-slug: google-classroom-api
  description: Google Classroom is mission control for your classes. As a free service
    for teachers and students, you can create classes, distribute assignments, send
    feedback, and see everything in one place. Instant. Paperless. Easy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-classroom.png
  humanURL: https://classroom.google.com/
  baseURL: ://classroom.googleapis.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-classroom/openapi.md
x-common:
- type: x-button
  url: https://developers.google.com/classroom/guides/sharebutton
- type: x-developer
  url: https://developers.google.com/classroom/
- type: x-getting-started
  url: ""
- type: x-issues
  url: https://code.google.com/a/google.com/p/apps-api-issues/issues/list?can=2&q=label%3AAPI-Classroom
- type: x-website
  url: https://classroom.google.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---