---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API List assignment overrides
  description: List assignment overrides.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/analytics/assignments:
    get:
      summary: Get course-level assignment data
      description: Get course-level assignment data.
      operationId: get-courselevel-assignment-data
      x-api-path-slug: coursescourse-idanalyticsassignments-get
      parameters:
      - in: query
        name: async
        description: If async is true, then the course_assignments call can happen
          asynch-nronously and MAY return a response containing a progress_url key
          instead ofnan assignments array
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Analytics
      - Assignments
  /courses/{course_id}/analytics/users/student_id/assignments:
    get:
      summary: Get user-in-a-course-level assignment data
      description: Get user-in-a-course-level assignment data.
      operationId: get-userinacourselevel-assignment-data
      x-api-path-slug: coursescourse-idanalyticsusersstudent-idassignments-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Analytics
      - Users
      - Student
      - Id
      - Assignments
  /courses/{course_id}/assignments:
    get:
      summary: List assignments
      description: List assignments.
      operationId: list-assignments
      x-api-path-slug: coursescourse-idassignments-get
      parameters:
      - in: query
        name: bucket
        description: If included, only return certain assignments depending on due
          date andnsubmission status
      - in: query
        name: include[]
        description: Associations to include with the assignment
      - in: query
        name: needs_grading_count_by_section
        description: Split up u201cneeds_grading_countu201d by sections into thenu201cneeds_grading_count_by_sectionu201d
          key, defaults to false
      - in: query
        name: override_assignment_dates
        description: Apply assignment overrides for each assignment, defaults to true
      - in: query
        name: search_term
        description: The partial title of the assignments to match and return
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
    post:
      summary: Create an assignment
      description: Create an assignment.
      operationId: create-an-assignment
      x-api-path-slug: coursescourse-idassignments-post
      parameters:
      - in: query
        name: assignment[allowed_extensions][]
        description: 'Allowed extensions if submission_types includes u201conline_uploadu201dnnExample:nnallowed_extensions:
          [&quot;docx&quot;,&quot;ppt&quot;]'
      - in: query
        name: assignment[assignment_group_id]
        description: The assignment group id to put the assignment in
      - in: query
        name: assignment[assignment_overrides][]
        description: List of overrides for the assignment
      - in: query
        name: assignment[automatic_peer_reviews]
        description: Whether peer reviews will be assigned automatically by Canvas
          or ifnteachers must manually assign peer reviews
      - in: query
        name: assignment[description]
        description: The assignment&#39;s description, supports HTML
      - in: query
        name: assignment[due_at]
        description: The day/time the assignment is due
      - in: query
        name: assignment[external_tool_tag_attributes]
        description: 'Hash of attributes if submission_types is [u201cexternal_toolu201d]
          Example:nnexternal_tool_tag_attributes: {n  %r/ url to the external tooln  url:
          &quot;http://instructure'
      - in: query
        name: assignment[grade_group_students_individually]
        description: If this is a group assignment, teachers have the options to grade
          studentsnindividually
      - in: query
        name: assignment[grading_standard_id]
        description: The grading standard id to set for the course
      - in: query
        name: assignment[grading_type]
        description: The strategy used for grading the assignment
      - in: query
        name: assignment[group_category_id]
        description: If present, the assignment will become a group assignment assigned
          to thengroup
      - in: query
        name: assignment[integration_data]
        description: Data related to third party integrations, JSON string required
      - in: query
        name: assignment[integration_id]
        description: Unique ID from third party integrations
      - in: query
        name: assignment[lock_at]
        description: The day/time the assignment is locked after
      - in: query
        name: assignment[muted]
        description: Whether this assignment is muted
      - in: query
        name: assignment[name]
        description: The assignment name
      - in: query
        name: assignment[notify_of_update]
        description: If true, Canvas will send a notification to students in the class
          notifyingnthem that the content has changed
      - in: query
        name: assignment[only_visible_to_overrides]
        description: Whether this assignment is only visible to overrides (Only useful
          ifn&#39;differentiated assignments&#39; account setting is on)
      - in: query
        name: assignment[peer_reviews]
        description: If submission_types does not include external_tool,discussion_topic,nonline_quiz,
          or on_paper, determines whether or not peer reviews will benturned on for
          the assignment
      - in: query
        name: assignment[points_possible]
        description: The maximum points possible on the assignment
      - in: query
        name: assignment[position]
        description: The position of this assignment in the group when displaying
          assignmentnlists
      - in: query
        name: assignment[published]
        description: Whether this assignment is published
      - in: query
        name: assignment[submission_types][]
        description: List of supported submission types for the assignment
      - in: query
        name: assignment[turnitin_enabled]
        description: Only applies when the Turnitin plugin is enabled for a course
          and thensubmission_types array includes u201conline_uploadu201d
      - in: query
        name: assignment[turnitin_settings]
        description: Settings to send along to turnitin
      - in: query
        name: assignment[unlock_at]
        description: The day/time the assignment is unlocked
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
  /courses/{course_id}/assignments/assignment_id/gradeable_students:
    get:
      summary: List gradeable students
      description: List gradeable students.
      operationId: list-gradeable-students
      x-api-path-slug: coursescourse-idassignmentsassignment-idgradeable-students-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
      - Assignment
      - Id
      - Gradeable
      - Students
  /courses/{course_id}/assignments/assignment_id/moderated_students:
    get:
      summary: List students selected for moderation
      description: List students selected for moderation.
      operationId: list-students-selected-for-moderation
      x-api-path-slug: coursescourse-idassignmentsassignment-idmoderated-students-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
      - Assignment
      - Id
      - Moderated
      - Students
    post:
      summary: Select students for moderation
      description: Select students for moderation.
      operationId: select-students-for-moderation
      x-api-path-slug: coursescourse-idassignmentsassignment-idmoderated-students-post
      parameters:
      - in: query
        name: student_ids[]
        description: user ids for students to select for moderation
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
      - Assignment
      - Id
      - Moderated
      - Students
  /courses/{course_id}/assignments/assignment_id/overrides:
    get:
      summary: List assignment overrides
      description: List assignment overrides.
      operationId: list-assignment-overrides
      x-api-path-slug: coursescourse-idassignmentsassignment-idoverrides-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Assignments
      - Assignment
      - Id
      - Overrides
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