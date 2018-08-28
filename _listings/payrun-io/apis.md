---
name: PayRun.io
x-slug: payrun-io
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO Deletes the DPS message
  x-api-slug: pay-run-io
  description: Deletes the DPS message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-delete-openapi.md
- name: Pay Run.IO Gets the DPS message
  x-api-slug: pay-run-io
  description: Gets the DPS message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-get-openapi.md
- name: Pay Run.IO Patches the DPS message
  x-api-slug: pay-run-io
  description: Patches the specified DPS message with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessage/{DpsMessageId}
  tags: Patches,DPMessage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessagedpsmessageid-patch-openapi.md
- name: Pay Run.IO Gets the DPS messages
  x-api-slug: pay-run-io
  description: Gets the DPS message links
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/DpsMessages
  tags: DPMessages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeriddpsmessages-get-openapi.md
- name: Pay Run.IO Delete auto enrolment assessment
  x-api-slug: pay-run-io
  description: Deletes an existing auto enrolment assessment for the employee. Used
    to remove historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Auto,Enrolment,Assessment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-delete-openapi.md
- name: Pay Run.IO Get the auto enrolment assessment
  x-api-slug: pay-run-io
  description: Gets the auto enrolment assessment from the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Auto,Enrolment,Assessment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-get-openapi.md
- name: Pay Run.IO Insert new auto enrolment assessment
  x-api-slug: pay-run-io
  description: Creates a new auto enrolment assessment for the employee. Used to insert
    historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessment/{AEAssessmentId}
  tags: Insert,New,Auto,Enrolment,Assessment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessmentaeassessmentid-put-openapi.md
- name: Pay Run.IO Get the auto enrolment assessments
  x-api-slug: pay-run-io
  description: Gets all auto enrolment assessments from the specified employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessments
  tags: Auto,Enrolment,Assessments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessments-get-openapi.md
- name: Pay Run.IO Insert new auto enrolment assessment
  x-api-slug: pay-run-io
  description: Creates a new auto enrolment assessment for the employee. Used to insert
    historical assessments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/AEAssessments
  tags: Insert,New,Auto,Enrolment,Assessment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidaeassessments-post-openapi.md
- name: Pay Run.IO Get links to all commentaries for the specified employee
  x-api-slug: pay-run-io
  description: Get links to all commentaries for the specified employee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Commentaries
  tags: Links,To,,Commentariesthe,Specified,Employee
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidcommentaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidcommentaries-get-openapi.md
- name: Pay Run.IO Get commentary from employee
  x-api-slug: pay-run-io
  description: Gets the specified commentary report from the employee
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/Employee/{EmployeeId}/Commentary/{CommentaryId}
  tags: Commentary,From,Employee
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridemployeeemployeeidcommentarycommentaryid-get-openapi.md
- name: Pay Run.IO Get the auto enrolment assessments
  x-api-slug: pay-run-io
  description: Gets all auto enrolment assessments from the specified pay run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PaySchedule/{PayScheduleId}/PayRun/{PayRunId}/AEAssessments
  tags: Auto,Enrolment,Assessments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/employeremployeridpayschedulepayscheduleidpayrunpayrunidaeassessments-get-openapi.md
- name: Pay Run.IO Runs the DPS message report
  x-api-slug: pay-run-io
  description: Returns the result of the executed DPS message report for the given
    query parameters
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Report/DPSMSG/run
  tags: Runs,DPMessage,Report
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/reportdpsmsgrun-get-openapi.md
- name: Pay Run.IO Get the NiAdjustmentPayInstruction schema
  x-api-slug: pay-run-io
  description: Returns the NiAdjustmentPayInstruction schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/NiAdjustmentPayInstruction.xsd
  tags: NiAdjustmentPayInstruction,Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/schemasniadjustmentpayinstruction-xsd-get-openapi.md
- name: Pay Run.IO Gets the commentary template
  x-api-slug: pay-run-io
  description: Return the commentary data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/commentary
  tags: Commentary,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/templatescommentary-get-openapi.md
- name: Pay Run.IO Gets the NI adjustment pay instruction template
  x-api-slug: pay-run-io
  description: Return the NI adjustment pay instruction data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/niadjustmentpayinstruction
  tags: NI,Adjustment,Pay,Instruction,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/templatesniadjustmentpayinstruction-get-openapi.md
- name: Pay Run.IO
  x-api-slug: pay-run-io
  description: An open, scalable, transparent and HMRC accredited payroll API. Put
    the power of payroll into your application today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/payrun-io/openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---