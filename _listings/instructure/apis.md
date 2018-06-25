---
name: Instructure
x-slug: instructure
description: Instructure makes software that makes smarter people. Products include
  Canvas LMS, Bridge and Canvas Network.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
x-kinRank: "8"
x-alexaRank: "367"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/apis.md
specificationVersion: "0.14"
apis:
- name: Instructure Canvas Appointment Groups API List appointment groups
  x-api-slug: instructure-canvas-appointment-groups-api
  description: List appointment groups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups
  tags: Appointment,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groups-get-openapi.md
- name: Instructure Canvas Appointment Groups API Create an appointment group
  x-api-slug: instructure-canvas-appointment-groups-api
  description: Create an appointment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups
  tags: Appointment,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groups-post-openapi.md
- name: Instructure Canvas Appointment Groups API Delete an appointment group
  x-api-slug: instructure-canvas-appointment-groups-api
  description: Delete an appointment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups/{id}
  tags: Appointment,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-delete-openapi.md
- name: Instructure Canvas Appointment Groups API Get a single appointment group
  x-api-slug: instructure-canvas-appointment-groups-api
  description: Get a single appointment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups/{id}
  tags: Appointment,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-get-openapi.md
- name: Instructure Canvas Appointment Groups API Update an appointment group
  x-api-slug: instructure-canvas-appointment-groups-api
  description: Update an appointment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups/{id}
  tags: Appointment,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsid-put-openapi.md
- name: Instructure Canvas Appointment Groups API List student group participants
  x-api-slug: instructure-canvas-appointment-groups-api
  description: List student group participants.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups/{id}/groups
  tags: Appointment,Groups,Id,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsidgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsidgroups-get-openapi.md
- name: Instructure Canvas Appointment Groups API List user participants
  x-api-slug: instructure-canvas-appointment-groups-api
  description: List user participants.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//appointment_groups/{id}/users
  tags: Appointment,Groups,Id,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsidusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/appointment-groupsidusers-get-openapi.md
- name: Instructure Canvas Appointment Groups API
  x-api-slug: instructure-canvas-appointment-groups-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Audit API Query by assignment.
  x-api-slug: instructure-canvas-audit-api
  description: Query by assignment..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//audit/grade_change/assignments/{assignment_id}
  tags: Audit,Grade,Change,Assignments,Assignment,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/auditgrade-changeassignmentsassignment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/auditgrade-changeassignmentsassignment-id-get-openapi.md
- name: Instructure Canvas Audit API
  x-api-slug: instructure-canvas-audit-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Conversations API Add a message
  x-api-slug: instructure-canvas-conversations-api
  description: Add a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//conversations/{id}/add_message
  tags: Conversations,Id,Add,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/conversationsidadd-message-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/conversationsidadd-message-post-openapi.md
- name: Instructure Canvas Conversations API Delete a message
  x-api-slug: instructure-canvas-conversations-api
  description: Delete a message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//conversations/{id}/remove_messages
  tags: Conversations,Id,Remove,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/conversationsidremove-messages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/conversationsidremove-messages-post-openapi.md
- name: Instructure Canvas Conversations API
  x-api-slug: instructure-canvas-conversations-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Courses API Get course-level assignment data
  x-api-slug: instructure-canvas-courses-api
  description: Get course-level assignment data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/analytics/assignments
  tags: Courses,Course,Id,Analytics,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idanalyticsassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idanalyticsassignments-get-openapi.md
- name: Instructure Canvas Courses API Get user-in-a-course-level assignment data
  x-api-slug: instructure-canvas-courses-api
  description: Get user-in-a-course-level assignment data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/analytics/users/student_id/assignments
  tags: Courses,Course,Id,Analytics,Users,Student,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idanalyticsusersstudent-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idanalyticsusersstudent-idassignments-get-openapi.md
- name: Instructure Canvas Courses API List assignments
  x-api-slug: instructure-canvas-courses-api
  description: List assignments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments
  tags: Courses,Course,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignments-get-openapi.md
- name: Instructure Canvas Courses API Create an assignment
  x-api-slug: instructure-canvas-courses-api
  description: Create an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments
  tags: Courses,Course,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignments-post-openapi.md
- name: Instructure Canvas Courses API List gradeable students
  x-api-slug: instructure-canvas-courses-api
  description: List gradeable students.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/gradeable_students
  tags: Courses,Course,Id,Assignments,Assignment,Id,Gradeable,Students
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idgradeable-students-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idgradeable-students-get-openapi.md
- name: Instructure Canvas Courses API List students selected for moderation
  x-api-slug: instructure-canvas-courses-api
  description: List students selected for moderation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/moderated_students
  tags: Courses,Course,Id,Assignments,Assignment,Id,Moderated,Students
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idmoderated-students-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idmoderated-students-get-openapi.md
- name: Instructure Canvas Courses API Select students for moderation
  x-api-slug: instructure-canvas-courses-api
  description: Select students for moderation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/moderated_students
  tags: Courses,Course,Id,Assignments,Assignment,Id,Moderated,Students
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idmoderated-students-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idmoderated-students-post-openapi.md
- name: Instructure Canvas Courses API List assignment overrides
  x-api-slug: instructure-canvas-courses-api
  description: List assignment overrides.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/overrides
  tags: Courses,Course,Id,Assignments,Assignment,Id,Overrides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverrides-get-openapi.md
- name: Instructure Canvas Courses API Create an assignment override
  x-api-slug: instructure-canvas-courses-api
  description: Create an assignment override.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/overrides
  tags: Courses,Course,Id,Assignments,Assignment,Id,Overrides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverrides-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverrides-post-openapi.md
- name: Instructure Canvas Courses API Delete an assignment override
  x-api-slug: instructure-canvas-courses-api
  description: Delete an assignment override.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/overrides/{id}
  tags: Courses,Course,Id,Assignments,Assignment,Id,Overrides,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-delete-openapi.md
- name: Instructure Canvas Courses API Get a single assignment override
  x-api-slug: instructure-canvas-courses-api
  description: Get a single assignment override.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/overrides/{id}
  tags: Courses,Course,Id,Assignments,Assignment,Id,Overrides,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-get-openapi.md
- name: Instructure Canvas Courses API Update an assignment override
  x-api-slug: instructure-canvas-courses-api
  description: Update an assignment override.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/overrides/{id}
  tags: Courses,Course,Id,Assignments,Assignment,Id,Overrides,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idoverridesid-put-openapi.md
- name: Instructure Canvas Courses API Get all Peer Reviews
  x-api-slug: instructure-canvas-courses-api
  description: Get all peer reviews.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/peer_reviews
  tags: Courses,Course,Id,Assignments,Assignment,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idpeer-reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idpeer-reviews-get-openapi.md
- name: Instructure Canvas Courses API Publish provisional grades for an assignment
  x-api-slug: instructure-canvas-courses-api
  description: Publish provisional grades for an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/provisional_grades/publish
  tags: Courses,Course,Id,Assignments,Assignment,Id,Provisional,Grades,Publish
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradespublish-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradespublish-post-openapi.md
- name: Instructure Canvas Courses API Show provisional grade status for a student
  x-api-slug: instructure-canvas-courses-api
  description: Show provisional grade status for a student.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/provisional_grades/status
  tags: Courses,Course,Id,Assignments,Assignment,Id,Provisional,Grades,Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesstatus-get-openapi.md
- name: Instructure Canvas Courses API Copy provisional grade
  x-api-slug: instructure-canvas-courses-api
  description: Copy provisional grade.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/provisional_grades/{provisional_grade_id}/copy_to_final_mark
  tags: Courses,Course,Id,Assignments,Assignment,Id,Provisional,Grades,Provisional,Grade,Id,Copy,To,Final,Mark
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesprovisional-grade-idcopy-to-final-mark-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesprovisional-grade-idcopy-to-final-mark-post-openapi.md
- name: Instructure Canvas Courses API Select provisional grade
  x-api-slug: instructure-canvas-courses-api
  description: Select provisional grade.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/provisional_grades/{provisional_grade_id}/select
  tags: Courses,Course,Id,Assignments,Assignment,Id,Provisional,Grades,Provisional,Grade,Id,Select
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesprovisional-grade-idselect-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idprovisional-gradesprovisional-grade-idselect-put-openapi.md
- name: Instructure Canvas Courses API List assignment submissions
  x-api-slug: instructure-canvas-courses-api
  description: List assignment submissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissions-get-openapi.md
- name: Instructure Canvas Courses API Submit an assignment
  x-api-slug: instructure-canvas-courses-api
  description: Submit an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissions-post-openapi.md
- name: Instructure Canvas Courses API Grade or comment on multiple submissions
  x-api-slug: instructure-canvas-courses-api
  description: Grade or comment on multiple submissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/update_grades
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,Update,Grades
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsupdate-grades-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsupdate-grades-post-openapi.md
- name: Instructure Canvas Courses API Create Peer Review
  x-api-slug: instructure-canvas-courses-api
  description: Create peer review.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-delete-openapi.md
- name: Instructure Canvas Courses API Get all Peer Reviews
  x-api-slug: instructure-canvas-courses-api
  description: Get all peer reviews.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-get-openapi.md
- name: Instructure Canvas Courses API Create Peer Review
  x-api-slug: instructure-canvas-courses-api
  description: Create peer review.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-post-openapi.md
- name: Instructure Canvas Courses API Get a single submission
  x-api-slug: instructure-canvas-courses-api
  description: Get a single submission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-id-get-openapi.md
- name: Instructure Canvas Courses API Grade or comment on a submission
  x-api-slug: instructure-canvas-courses-api
  description: Grade or comment on a submission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-id-put-openapi.md
- name: Instructure Canvas Courses API Upload a file
  x-api-slug: instructure-canvas-courses-api
  description: Upload a file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}/comments/files
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id,Comments,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idcommentsfiles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idcommentsfiles-post-openapi.md
- name: Instructure Canvas Courses API Upload a file
  x-api-slug: instructure-canvas-courses-api
  description: Upload a file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}/files
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idfiles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idfiles-post-openapi.md
- name: Instructure Canvas Courses API Mark submission as unread
  x-api-slug: instructure-canvas-courses-api
  description: Mark submission as unread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}/read
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idread-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idread-delete-openapi.md
- name: Instructure Canvas Courses API Mark submission as read
  x-api-slug: instructure-canvas-courses-api
  description: Mark submission as read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/assignment_id/submissions/{user_id}/read
  tags: Courses,Course,Id,Assignments,Assignment,Id,Submissions,User,Id,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idread-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsassignment-idsubmissionsuser-idread-put-openapi.md
- name: Instructure Canvas Courses API Delete an assignment
  x-api-slug: instructure-canvas-courses-api
  description: Delete an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/id
  tags: Courses,Course,Id,Assignments,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-delete-openapi.md
- name: Instructure Canvas Courses API Get a single assignment
  x-api-slug: instructure-canvas-courses-api
  description: Get a single assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/id
  tags: Courses,Course,Id,Assignments,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-get-openapi.md
- name: Instructure Canvas Courses API Edit an assignment
  x-api-slug: instructure-canvas-courses-api
  description: Edit an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignments/id
  tags: Courses,Course,Id,Assignments,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignmentsid-put-openapi.md
- name: Instructure Canvas Courses API List assignment groups
  x-api-slug: instructure-canvas-courses-api
  description: List assignment groups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignment_groups
  tags: Courses,Course,Id,Assignment,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groups-get-openapi.md
- name: Instructure Canvas Courses API Create an Assignment Group
  x-api-slug: instructure-canvas-courses-api
  description: Create an assignment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignment_groups
  tags: Courses,Course,Id,Assignment,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groups-post-openapi.md
- name: Instructure Canvas Courses API Destroy an Assignment Group
  x-api-slug: instructure-canvas-courses-api
  description: Destroy an assignment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignment_groups/assignment_group_id
  tags: Courses,Course,Id,Assignment,Groups,Assignment,Group,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-delete-openapi.md
- name: Instructure Canvas Courses API Get an Assignment Group
  x-api-slug: instructure-canvas-courses-api
  description: Get an assignment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignment_groups/assignment_group_id
  tags: Courses,Course,Id,Assignment,Groups,Assignment,Group,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-get-openapi.md
- name: Instructure Canvas Courses API Edit an Assignment Group
  x-api-slug: instructure-canvas-courses-api
  description: Edit an assignment group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/assignment_groups/assignment_group_id
  tags: Courses,Course,Id,Assignment,Groups,Assignment,Group,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idassignment-groupsassignment-group-id-put-openapi.md
- name: Instructure Canvas Courses API List enrollments
  x-api-slug: instructure-canvas-courses-api
  description: List enrollments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/enrollments
  tags: Courses,Course,Id,Enrollments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollments-get-openapi.md
- name: Instructure Canvas Courses API Enroll a user
  x-api-slug: instructure-canvas-courses-api
  description: Enroll a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/enrollments
  tags: Courses,Course,Id,Enrollments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollments-post-openapi.md
- name: Instructure Canvas Courses API Conclude or inactivate an enrollment
  x-api-slug: instructure-canvas-courses-api
  description: Conclude or inactivate an enrollment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/enrollments/id
  tags: Courses,Course,Id,Enrollments,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollmentsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollmentsid-delete-openapi.md
- name: Instructure Canvas Courses API Re-activate an enrollment
  x-api-slug: instructure-canvas-courses-api
  description: Re-activate an enrollment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/enrollments/id/reactivate
  tags: Courses,Course,Id,Enrollments,Id,Reactivate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollmentsidreactivate-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idenrollmentsidreactivate-put-openapi.md
- name: Instructure Canvas Courses API Lists submissions
  x-api-slug: instructure-canvas-courses-api
  description: Lists submissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/gradebook_history/date/graders/{grader_id}/assignments/assignment_id/submissions
  tags: Courses,Course,Id,Gradebook,History,Date,Graders,Grader,Id,Assignments,Assignment,Id,Submissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idgradebook-historydategradersgrader-idassignmentsassignment-idsubmissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idgradebook-historydategradersgrader-idassignmentsassignment-idsubmissions-get-openapi.md
- name: Instructure Canvas Courses API List live assessments
  x-api-slug: instructure-canvas-courses-api
  description: List live assessments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/live_assessments
  tags: Courses,Course,Id,Live,Assessments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessments-get-openapi.md
- name: Instructure Canvas Courses API Create or find a live assessment
  x-api-slug: instructure-canvas-courses-api
  description: Create or find a live assessment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/live_assessments
  tags: Courses,Course,Id,Live,Assessments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessments-post-openapi.md
- name: Instructure Canvas Courses API List live assessment results
  x-api-slug: instructure-canvas-courses-api
  description: List live assessment results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/live_assessments/assessment_id/results
  tags: Courses,Course,Id,Live,Assessments,Assessment,Id,Results
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessmentsassessment-idresults-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessmentsassessment-idresults-get-openapi.md
- name: Instructure Canvas Courses API Create live assessment results
  x-api-slug: instructure-canvas-courses-api
  description: Create live assessment results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/live_assessments/assessment_id/results
  tags: Courses,Course,Id,Live,Assessments,Assessment,Id,Results
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessmentsassessment-idresults-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idlive-assessmentsassessment-idresults-post-openapi.md
- name: Instructure Canvas Courses API Get all outcome groups for context
  x-api-slug: instructure-canvas-courses-api
  description: Get all outcome groups for context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups
  tags: Courses,Course,Id,Outcome,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groups-get-openapi.md
- name: Instructure Canvas Courses API Delete an outcome group
  x-api-slug: instructure-canvas-courses-api
  description: Delete an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id
  tags: Courses,Course,Id,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-delete-openapi.md
- name: Instructure Canvas Courses API Show an outcome group
  x-api-slug: instructure-canvas-courses-api
  description: Show an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id
  tags: Courses,Course,Id,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-get-openapi.md
- name: Instructure Canvas Courses API Update an outcome group
  x-api-slug: instructure-canvas-courses-api
  description: Update an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id
  tags: Courses,Course,Id,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsid-put-openapi.md
- name: Instructure Canvas Courses API Import an outcome group
  x-api-slug: instructure-canvas-courses-api
  description: Import an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/import
  tags: Courses,Course,Id,Outcome,Groups,Id,Import
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidimport-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidimport-post-openapi.md
- name: Instructure Canvas Courses API List linked outcomes
  x-api-slug: instructure-canvas-courses-api
  description: List linked outcomes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/outcomes
  tags: Courses,Course,Id,Outcome,Groups,Id,Outcomes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomes-get-openapi.md
- name: Instructure Canvas Courses API Create/link an outcome
  x-api-slug: instructure-canvas-courses-api
  description: Create/link an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/outcomes
  tags: Courses,Course,Id,Outcome,Groups,Id,Outcomes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomes-post-openapi.md
- name: Instructure Canvas Courses API Unlink an outcome
  x-api-slug: instructure-canvas-courses-api
  description: Unlink an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/outcomes/{outcome_id}
  tags: Courses,Course,Id,Outcome,Groups,Id,Outcomes,Outcome,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomesoutcome-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomesoutcome-id-delete-openapi.md
- name: Instructure Canvas Courses API Create/link an outcome
  x-api-slug: instructure-canvas-courses-api
  description: Create/link an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/outcomes/{outcome_id}
  tags: Courses,Course,Id,Outcome,Groups,Id,Outcomes,Outcome,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomesoutcome-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidoutcomesoutcome-id-put-openapi.md
- name: Instructure Canvas Courses API List subgroups
  x-api-slug: instructure-canvas-courses-api
  description: List subgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/subgroups
  tags: Courses,Course,Id,Outcome,Groups,Id,Subgroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidsubgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidsubgroups-get-openapi.md
- name: Instructure Canvas Courses API Create a subgroup
  x-api-slug: instructure-canvas-courses-api
  description: Create a subgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_groups/id/subgroups
  tags: Courses,Course,Id,Outcome,Groups,Id,Subgroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidsubgroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-groupsidsubgroups-post-openapi.md
- name: Instructure Canvas Courses API Get all outcome links for context
  x-api-slug: instructure-canvas-courses-api
  description: Get all outcome links for context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_group_links
  tags: Courses,Course,Id,Outcome,Group,Links
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-group-links-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-group-links-get-openapi.md
- name: Instructure Canvas Courses API Get outcome results
  x-api-slug: instructure-canvas-courses-api
  description: Get outcome results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_results
  tags: Courses,Course,Id,Outcome,Results
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-results-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-results-get-openapi.md
- name: Instructure Canvas Courses API Get outcome result rollups
  x-api-slug: instructure-canvas-courses-api
  description: Get outcome result rollups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/outcome_rollups
  tags: Courses,Course,Id,Outcome,Rollups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-rollups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idoutcome-rollups-get-openapi.md
- name: Instructure Canvas Courses API Retrieve assignment-overridden dates for quizzes
  x-api-slug: instructure-canvas-courses-api
  description: Retrieve assignment-overridden dates for quizzes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/quizzes/assignment_overrides
  tags: Courses,Course,Id,Quizzes,Assignment,Overrides
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesassignment-overrides-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesassignment-overrides-get-openapi.md
- name: Instructure Canvas Courses API Send a message to unsubmitted or submitted
    users for the quiz
  x-api-slug: instructure-canvas-courses-api
  description: Send a message to unsubmitted or submitted users for the quiz.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/quizzes/id/submission_users/message
  tags: Courses,Course,Id,Quizzes,Id,Submission,Users,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesidsubmission-usersmessage-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesidsubmission-usersmessage-post-openapi.md
- name: Instructure Canvas Courses API Get current quiz submission times.
  x-api-slug: instructure-canvas-courses-api
  description: Get current quiz submission times..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/quizzes/quiz_id/submissions/{id}/time
  tags: Courses,Course,Id,Quizzes,Quiz,Id,Submissions,Id,Time
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesquiz-idsubmissionsidtime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idquizzesquiz-idsubmissionsidtime-get-openapi.md
- name: Instructure Canvas Courses API Redirect to root outcome group for context
  x-api-slug: instructure-canvas-courses-api
  description: Redirect to root outcome group for context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//courses/{course_id}/root_outcome_group
  tags: Courses,Course,Id,Root,Outcome,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idroot-outcome-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/coursescourse-idroot-outcome-group-get-openapi.md
- name: Instructure Canvas Courses API
  x-api-slug: instructure-canvas-courses-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Global API Delete an outcome group
  x-api-slug: instructure-canvas-global-api
  description: Delete an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}
  tags: Global,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-delete-openapi.md
- name: Instructure Canvas Global API Show an outcome group
  x-api-slug: instructure-canvas-global-api
  description: Show an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}
  tags: Global,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-get-openapi.md
- name: Instructure Canvas Global API Update an outcome group
  x-api-slug: instructure-canvas-global-api
  description: Update an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}
  tags: Global,Outcome,Groups,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsid-put-openapi.md
- name: Instructure Canvas Global API Import an outcome group
  x-api-slug: instructure-canvas-global-api
  description: Import an outcome group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/import
  tags: Global,Outcome,Groups,Id,Import
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidimport-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidimport-post-openapi.md
- name: Instructure Canvas Global API List linked outcomes
  x-api-slug: instructure-canvas-global-api
  description: List linked outcomes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/outcomes
  tags: Global,Outcome,Groups,Id,Outcomes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomes-get-openapi.md
- name: Instructure Canvas Global API Create/link an outcome
  x-api-slug: instructure-canvas-global-api
  description: Create/link an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/outcomes
  tags: Global,Outcome,Groups,Id,Outcomes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomes-post-openapi.md
- name: Instructure Canvas Global API Unlink an outcome
  x-api-slug: instructure-canvas-global-api
  description: Unlink an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/outcomes/outcome_id
  tags: Global,Outcome,Groups,Id,Outcomes,Outcome,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomesoutcome-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomesoutcome-id-delete-openapi.md
- name: Instructure Canvas Global API Create/link an outcome
  x-api-slug: instructure-canvas-global-api
  description: Create/link an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/outcomes/outcome_id
  tags: Global,Outcome,Groups,Id,Outcomes,Outcome,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomesoutcome-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidoutcomesoutcome-id-put-openapi.md
- name: Instructure Canvas Global API List subgroups
  x-api-slug: instructure-canvas-global-api
  description: List subgroups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/subgroups
  tags: Global,Outcome,Groups,Id,Subgroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidsubgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidsubgroups-get-openapi.md
- name: Instructure Canvas Global API Create a subgroup
  x-api-slug: instructure-canvas-global-api
  description: Create a subgroup.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/outcome_groups/{id}/subgroups
  tags: Global,Outcome,Groups,Id,Subgroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidsubgroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globaloutcome-groupsidsubgroups-post-openapi.md
- name: Instructure Canvas Global API Redirect to root outcome group for context
  x-api-slug: instructure-canvas-global-api
  description: Redirect to root outcome group for context.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//global/root_outcome_group
  tags: Global,Root,Outcome,Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globalroot-outcome-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/globalroot-outcome-group-get-openapi.md
- name: Instructure Canvas Global API
  x-api-slug: instructure-canvas-global-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Groups API Redirect to the assignment override for a group
  x-api-slug: instructure-canvas-groups-api
  description: Redirect to the assignment override for a group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/assignments/assignment_id/override
  tags: Groups,Group,Id,Assignments,Assignment,Id,Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idassignmentsassignment-idoverride-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idassignmentsassignment-idoverride-get-openapi.md
- name: Instructure Canvas Groups API List group memberships
  x-api-slug: instructure-canvas-groups-api
  description: List group memberships.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/memberships
  tags: Groups,Group,Id,Memberships
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmemberships-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmemberships-get-openapi.md
- name: Instructure Canvas Groups API Create a membership
  x-api-slug: instructure-canvas-groups-api
  description: Create a membership.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/memberships
  tags: Groups,Group,Id,Memberships
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmemberships-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmemberships-post-openapi.md
- name: Instructure Canvas Groups API Leave a group
  x-api-slug: instructure-canvas-groups-api
  description: Leave a group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/memberships/membership_id
  tags: Groups,Group,Id,Memberships,Membership,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-delete-openapi.md
- name: Instructure Canvas Groups API Get a single group membership
  x-api-slug: instructure-canvas-groups-api
  description: Get a single group membership.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/memberships/membership_id
  tags: Groups,Group,Id,Memberships,Membership,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-get-openapi.md
- name: Instructure Canvas Groups API Update a membership
  x-api-slug: instructure-canvas-groups-api
  description: Update a membership.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//groups/{group_id}/memberships/membership_id
  tags: Groups,Group,Id,Memberships,Membership,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/groupsgroup-idmembershipsmembership-id-put-openapi.md
- name: Instructure Canvas Groups API Assign unassigned members
  x-api-slug: instructure-canvas-groups-api
  description: Assign unassigned members.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//group_categories/{group_category_id}/assign_unassigned_members
  tags: Group,Categories,Group,Category,Id,Assign,Unassigned,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/group-categoriesgroup-category-idassign-unassigned-members-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/group-categoriesgroup-category-idassign-unassigned-members-post-openapi.md
- name: Instructure Canvas Groups API
  x-api-slug: instructure-canvas-groups-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Sections API Redirect to the assignment override for a
    section
  x-api-slug: instructure-canvas-sections-api
  description: Redirect to the assignment override for a section.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{course_section_id}/assignments/assignment_id/override
  tags: Sections,Course,Section,Id,Assignments,Assignment,Id,Override
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionscourse-section-idassignmentsassignment-idoverride-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionscourse-section-idassignmentsassignment-idoverride-get-openapi.md
- name: Instructure Canvas Sections API Get all Peer Reviews
  x-api-slug: instructure-canvas-sections-api
  description: Get all peer reviews.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/peer_reviews
  tags: Sections,Section,Id,Assignments,Assignment,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idpeer-reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idpeer-reviews-get-openapi.md
- name: Instructure Canvas Sections API List assignment submissions
  x-api-slug: instructure-canvas-sections-api
  description: List assignment submissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissions-get-openapi.md
- name: Instructure Canvas Sections API Submit an assignment
  x-api-slug: instructure-canvas-sections-api
  description: Submit an assignment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissions-post-openapi.md
- name: Instructure Canvas Sections API Grade or comment on multiple submissions
  x-api-slug: instructure-canvas-sections-api
  description: Grade or comment on multiple submissions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/update_grades
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,Update,Grades
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsupdate-grades-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsupdate-grades-post-openapi.md
- name: Instructure Canvas Sections API Create Peer Review
  x-api-slug: instructure-canvas-sections-api
  description: Create peer review.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-delete-openapi.md
- name: Instructure Canvas Sections API Get all Peer Reviews
  x-api-slug: instructure-canvas-sections-api
  description: Get all peer reviews.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-get-openapi.md
- name: Instructure Canvas Sections API Create Peer Review
  x-api-slug: instructure-canvas-sections-api
  description: Create peer review.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{submission_id}/peer_reviews
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,Submission,Id,Peer,Reviews
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionssubmission-idpeer-reviews-post-openapi.md
- name: Instructure Canvas Sections API Get a single submission
  x-api-slug: instructure-canvas-sections-api
  description: Get a single submission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{user_id}
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-id-get-openapi.md
- name: Instructure Canvas Sections API Grade or comment on a submission
  x-api-slug: instructure-canvas-sections-api
  description: Grade or comment on a submission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{user_id}
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-id-put-openapi.md
- name: Instructure Canvas Sections API Upload a file
  x-api-slug: instructure-canvas-sections-api
  description: Upload a file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{user_id}/files
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,User,Id,Files
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idfiles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idfiles-post-openapi.md
- name: Instructure Canvas Sections API Mark submission as unread
  x-api-slug: instructure-canvas-sections-api
  description: Mark submission as unread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{user_id}/read
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,User,Id,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idread-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idread-delete-openapi.md
- name: Instructure Canvas Sections API Mark submission as read
  x-api-slug: instructure-canvas-sections-api
  description: Mark submission as read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/assignments/assignment_id/submissions/{user_id}/read
  tags: Sections,Section,Id,Assignments,Assignment,Id,Submissions,User,Id,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idread-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idassignmentsassignment-idsubmissionsuser-idread-put-openapi.md
- name: Instructure Canvas Sections API List enrollments
  x-api-slug: instructure-canvas-sections-api
  description: List enrollments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/enrollments
  tags: Sections,Section,Id,Enrollments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idenrollments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idenrollments-get-openapi.md
- name: Instructure Canvas Sections API Enroll a user
  x-api-slug: instructure-canvas-sections-api
  description: Enroll a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//sections/{section_id}/enrollments
  tags: Sections,Section,Id,Enrollments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idenrollments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/sectionssection-idenrollments-post-openapi.md
- name: Instructure Canvas Sections API
  x-api-slug: instructure-canvas-sections-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Users API Clear course nicknames
  x-api-slug: instructure-canvas-users-api
  description: Clear course nicknames.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/self/course_nicknames
  tags: Users,Self,Course,Nicknames
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknames-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknames-delete-openapi.md
- name: Instructure Canvas Users API List course nicknames
  x-api-slug: instructure-canvas-users-api
  description: List course nicknames.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/self/course_nicknames
  tags: Users,Self,Course,Nicknames
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknames-get-openapi.md
- name: Instructure Canvas Users API Remove course nickname
  x-api-slug: instructure-canvas-users-api
  description: Remove course nickname.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/self/course_nicknames/{course_id}
  tags: Users,Self,Course,Nicknames,Course,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-delete-openapi.md
- name: Instructure Canvas Users API Get course nickname
  x-api-slug: instructure-canvas-users-api
  description: Get course nickname.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/self/course_nicknames/{course_id}
  tags: Users,Self,Course,Nicknames,Course,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-get-openapi.md
- name: Instructure Canvas Users API Set course nickname
  x-api-slug: instructure-canvas-users-api
  description: Set course nickname.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/self/course_nicknames/{course_id}
  tags: Users,Self,Course,Nicknames,Course,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersselfcourse-nicknamescourse-id-put-openapi.md
- name: Instructure Canvas Users API Merge user into another user
  x-api-slug: instructure-canvas-users-api
  description: Merge user into another user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{id}/merge_into/accounts/destination_account_id/users/{destination_user_id}
  tags: Users,Id,Merge,Into,Accounts,Destination,Account,Id,Users,Destination,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersidmerge-intoaccountsdestination-account-idusersdestination-user-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersidmerge-intoaccountsdestination-account-idusersdestination-user-id-put-openapi.md
- name: Instructure Canvas Users API Merge user into another user
  x-api-slug: instructure-canvas-users-api
  description: Merge user into another user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{id}/merge_into/destination_user_id
  tags: Users,Id,Merge,Into,Destination,User,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersidmerge-intodestination-user-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersidmerge-intodestination-user-id-put-openapi.md
- name: Instructure Canvas Users API List assignments for user
  x-api-slug: instructure-canvas-users-api
  description: List assignments for user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/courses/course_id/assignments
  tags: Users,User,Id,Courses,Course,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersuser-idcoursescourse-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersuser-idcoursescourse-idassignments-get-openapi.md
- name: Instructure Canvas Users API List enrollments
  x-api-slug: instructure-canvas-users-api
  description: List enrollments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//users/{user_id}/enrollments
  tags: Users,User,Id,Enrollments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersuser-idenrollments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/usersuser-idenrollments-get-openapi.md
- name: Instructure Canvas Users API
  x-api-slug: instructure-canvas-users-api
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
- name: Instructure Canvas Utility APIs Retrieve assignments enabled for grade export
    to SIS
  x-api-slug: instructure-canvas-utility-apis
  description: Retrieve assignments enabled for grade export to sis.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//api/sis/accounts/{account_id}/assignments
  tags: Api,Sis,Accounts,Account,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/apisisaccountsaccount-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/apisisaccountsaccount-idassignments-get-openapi.md
- name: Instructure Canvas Utility APIs Retrieve assignments enabled for grade export
    to SIS
  x-api-slug: instructure-canvas-utility-apis
  description: Retrieve assignments enabled for grade export to sis.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//api/sis/courses/{course_id}/assignments
  tags: Api,Sis,Courses,Course,Id,Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/apisiscoursescourse-idassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/apisiscoursescourse-idassignments-get-openapi.md
- name: Instructure Canvas Utility APIs List members of a collaboration.
  x-api-slug: instructure-canvas-utility-apis
  description: List members of a collaboration..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//collaborations/{id}/members
  tags: Collaborations,Id,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/collaborationsidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/collaborationsidmembers-get-openapi.md
- name: Instructure Canvas Utility APIs List of CommMessages for a user
  x-api-slug: instructure-canvas-utility-apis
  description: List of commmessages for a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//comm_messages
  tags: Comm,Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/comm-messages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/comm-messages-get-openapi.md
- name: Instructure Canvas Utility APIs Show an outcome
  x-api-slug: instructure-canvas-utility-apis
  description: Show an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//outcomes/{id}
  tags: Outcomes,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/outcomesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/outcomesid-get-openapi.md
- name: Instructure Canvas Utility APIs Update an outcome
  x-api-slug: instructure-canvas-utility-apis
  description: Update an outcome.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1//outcomes/{id}
  tags: Outcomes,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/outcomesid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/outcomesid-put-openapi.md
- name: Instructure Canvas Utility APIs
  x-api-slug: instructure-canvas-utility-apis
  description: Instructure makes software that makes smarter people. Products include
    Canvas LMS, Bridge and Canvas Network.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/820-instructure.jpg
  humanURL: http://instructure.com
  baseURL: https://canvas.instructure.com//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/instructure/openapi.md
x-common:
- type: x-blog
  url: http://blog.instructure.com
- type: x-blog-rss
  url: http://voice.instructure.com/CMS/UI/Modules/BizBlogger/rss.aspx?tabid=772438&moduleid=1638884&maxcount=25&t=415c2e5d197a4d6f7cdcc81385b677f1
- type: x-crunchbase
  url: https://crunchbase.com/organization/instructure
- type: x-crunchbase
  url: http://www.crunchbase.com/company/instructure
- type: x-email
  url: info@instructure.com
- type: x-email
  url: jobs@instructure.com
- type: x-email
  url: privacy@instructure.com
- type: x-email
  url: legal@instructure.com
- type: x-github
  url: https://github.com/instructure
- type: x-twitter
  url: https://twitter.com/instructure
- type: x-website
  url: http://instructure.com
- type: x-website
  url: https://canvas.instructure.com/doc/api/index.html
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---