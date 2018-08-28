---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
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
  /api/sis/accounts/{account_id}/assignments:
    get:
      summary: Retrieve assignments enabled for grade export to SIS
      description: Retrieve assignments enabled for grade export to sis.
      operationId: retrieve-assignments-enabled-for-grade-export-to-sis
      x-api-path-slug: apisisaccountsaccount-idassignments-get
      parameters:
      - in: query
        name: account_id
        description: The ID of the account to query
      - in: query
        name: course_id
        description: The ID of the course to query
      - in: query
        name: ends_after
        description: When searching on an account, restricts to courses that end after
          this daten(if they have an end date)
      - in: query
        name: starts_before
        description: When searching on an account, restricts to courses that start
          before thisndate (if they have a start date)
      responses:
        200:
          description: OK
      tags:
      - Api
      - Sis
      - Accounts
      - Account
      - Id
      - Assignments
  /api/sis/courses/{course_id}/assignments:
    get:
      summary: Retrieve assignments enabled for grade export to SIS
      description: Retrieve assignments enabled for grade export to sis.
      operationId: retrieve-assignments-enabled-for-grade-export-to-sis
      x-api-path-slug: apisiscoursescourse-idassignments-get
      parameters:
      - in: query
        name: account_id
        description: The ID of the account to query
      - in: query
        name: course_id
        description: The ID of the course to query
      - in: query
        name: ends_after
        description: When searching on an account, restricts to courses that end after
          this daten(if they have an end date)
      - in: query
        name: starts_before
        description: When searching on an account, restricts to courses that start
          before thisndate (if they have a start date)
      responses:
        200:
          description: OK
      tags:
      - Api
      - Sis
      - Courses
      - Course
      - Id
      - Assignments
  /collaborations/{id}/members:
    get:
      summary: List members of a collaboration.
      description: List members of a collaboration..
      operationId: list-members-of-a-collaboration
      x-api-path-slug: collaborationsidmembers-get
      responses:
        200:
          description: OK
      tags:
      - Collaborations
      - Id
      - Members
  /comm_messages:
    get:
      summary: List of CommMessages for a user
      description: List of commmessages for a user.
      operationId: list-of-commmessages-for-a-user
      x-api-path-slug: comm-messages-get
      parameters:
      - in: query
        name: end_time
        description: The end of the time range you want to retrieve messages for
      - in: query
        name: start_time
        description: The beginning of the time range you want to retrieve message
          from
      - in: query
        name: user_id
        description: The user id for whom you want to retrieve CommMessages
      responses:
        200:
          description: OK
      tags:
      - Comm
      - Messages
  /outcomes/{id}:
    get:
      summary: Show an outcome
      description: Show an outcome.
      operationId: show-an-outcome
      x-api-path-slug: outcomesid-get
      responses:
        200:
          description: OK
      tags:
      - Outcomes
      - Id
    put:
      summary: Update an outcome
      description: Update an outcome.
      operationId: update-an-outcome
      x-api-path-slug: outcomesid-put
      parameters:
      - in: query
        name: calculation_int
        description: The new calculation int
      - in: query
        name: calculation_method
        description: The new calculation method
      - in: query
        name: description
        description: The new outcome description
      - in: query
        name: display_name
        description: A friendly name shown in reports for outcomes with cryptic titles,
          such asncommon core standards names
      - in: query
        name: mastery_points
        description: The new mastery threshold for the embedded rubric criterion
      - in: query
        name: ratings[][description]
        description: The description of a new rating level for the embedded rubric
          criterion
      - in: query
        name: ratings[][points]
        description: The points corresponding to a new rating level for the embedded
          rubricncriterion
      - in: query
        name: title
        description: The new outcome title
      - in: query
        name: vendor_guid
        description: A custom GUID for the learning standard
      responses:
        200:
          description: OK
      tags:
      - Outcomes
      - Id
---