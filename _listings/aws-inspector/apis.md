---
name: AWS Inspector
x-slug: aws-inspector
description: Amazon Inspector is an automated security assessment service that helps
  improve the security and compliance of applications deployed on AWS. Amazon Inspector
  automatically assesses applications for vulnerabilities or deviations from best
  practices. After performing an assessment, Amazon Inspector produces a detailed
  list of security findings prioritized by level of severity.To help you get started
  quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
  to common security best practices and vulnerability definitions. Examples of built-in
  rules include checking for remote root login being enabled, or vulnerable software
  versions installed. These rules are regularly updated by AWS security researchers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Inspector API Create Assessment Target
  x-api-slug: aws-inspector-api
  description: |-
    Creates a new assessment target using the ARN of the resource group that is generated
             by.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=CreateAssessmentTarget
  tags: ' Assessment Targets'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actioncreateassessmenttarget-get-openapi.md
- name: AWS Inspector API Create Assessment Template
  x-api-slug: aws-inspector-api
  description: |-
    Creates an assessment template for the assessment target that is specified by the ARN
             of the assessment target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=CreateAssessmentTemplate
  tags: Assessment Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actioncreateassessmenttemplate-get-openapi.md
- name: AWS Inspector API Delete Assessment Run
  x-api-slug: aws-inspector-api
  description: |-
    Deletes the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DeleteAssessmentRun
  tags: Assessment Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondeleteassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondeleteassessmentrun-get-openapi.md
- name: AWS Inspector API Delete Assessment Target
  x-api-slug: aws-inspector-api
  description: |-
    Deletes the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DeleteAssessmentTarget
  tags: Assessment Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondeleteassessmenttarget-get-openapi.md
- name: AWS Inspector API Delete Assessment Template
  x-api-slug: aws-inspector-api
  description: |-
    Deletes the assessment template that is specified by the ARN of the assessment
             template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DeleteAssessmentTemplate
  tags: Assessment Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondeleteassessmenttemplate-get-openapi.md
- name: AWS Inspector API Describe Assessment Runs
  x-api-slug: aws-inspector-api
  description: |-
    Describes the assessment runs that are specified by the ARNs of the assessment
             runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DescribeAssessmentRuns
  tags: Assessment Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondescribeassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondescribeassessmentruns-get-openapi.md
- name: AWS Inspector API Describe Assessment Targets
  x-api-slug: aws-inspector-api
  description: |-
    Describes the assessment targets that are specified by the ARNs of the assessment
             targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DescribeAssessmentTargets
  tags: Assessment Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondescribeassessmenttargets-get-openapi.md
- name: AWS Inspector API Describe Assessment Templates
  x-api-slug: aws-inspector-api
  description: |-
    Describes the assessment templates that are specified by the ARNs of the assessment
             templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=DescribeAssessmentTemplates
  tags: Assessment Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiondescribeassessmenttemplates-get-openapi.md
- name: AWS Inspector API Get Telemetry Metadata
  x-api-slug: aws-inspector-api
  description: |-
    Information about the data that is collected for the specified assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=GetTelemetryMetadata
  tags: Telemetry Metadata
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actiongettelemetrymetadata-get-openapi.md
- name: AWS Inspector API List Assessment Run Agents
  x-api-slug: aws-inspector-api
  description: |-
    Lists the agents of the assessment runs that are specified by the ARNs of the
             assessment runs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=ListAssessmentRunAgents
  tags: Assessment Run Agents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionlistassessmentrunagents-get-openapi.md
- name: AWS Inspector API List Assessment Runs
  x-api-slug: aws-inspector-api
  description: |-
    Lists the assessment runs that correspond to the assessment templates that are
             specified by the ARNs of the assessment templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=ListAssessmentRuns
  tags: Assessment Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionlistassessmentruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionlistassessmentruns-get-openapi.md
- name: AWS Inspector API List Assessment Targets
  x-api-slug: aws-inspector-api
  description: Lists the ARNs of the assessment targets within this AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=ListAssessmentTargets
  tags: Assessment Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionlistassessmenttargets-get-openapi.md
- name: AWS Inspector API List Assessment Templates
  x-api-slug: aws-inspector-api
  description: |-
    Lists the assessment templates that correspond to the assessment targets that are
             specified by the ARNs of the assessment targets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=ListAssessmentTemplates
  tags: Assessment Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionlistassessmenttemplates-get-openapi.md
- name: AWS Inspector API Start Assessment Run
  x-api-slug: aws-inspector-api
  description: Starts the assessment run specified by the ARN of the assessment template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=StartAssessmentRun
  tags: Assessment Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionstartassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionstartassessmentrun-get-openapi.md
- name: AWS Inspector API Stop Assessment Run
  x-api-slug: aws-inspector-api
  description: |-
    Stops the assessment run that is specified by the ARN of the assessment
             run.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=StopAssessmentRun
  tags: Assessment Runs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionstopassessmentrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionstopassessmentrun-get-openapi.md
- name: AWS Inspector API Update Assessment Target
  x-api-slug: aws-inspector-api
  description: |-
    Updates the assessment target that is specified by the ARN of the assessment
             target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: ://///?Action=UpdateAssessmentTarget
  tags: Assessment Targets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/actionupdateassessmenttarget-get-openapi.md
- name: AWS Inspector API
  x-api-slug: aws-inspector-api
  description: Amazon Inspector is an automated security assessment service that helps
    improve the security and compliance of applications deployed on AWS. Amazon Inspector
    automatically assesses applications for vulnerabilities or deviations from best
    practices. After performing an assessment, Amazon Inspector produces a detailed
    list of security findings prioritized by level of severity.To help you get started
    quickly, Amazon Inspector includes a knowledge base of hundreds of rules mapped
    to common security best practices and vulnerability definitions. Examples of built-in
    rules include checking for remote root login being enabled, or vulnerable software
    versions installed. These rules are regularly updated by AWS security researchers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AmazonInspector.png
  humanURL: https://aws.amazon.com/inspector/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-inspector/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/inspector/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/inspector/faqs/
- type: x-getting-started
  url: https://docs.aws.amazon.com/inspector/latest/userguide/inspector_quickstart.html
- type: x-partners
  url: https://aws.amazon.com/inspector/partners/
- type: x-pricing
  url: https://aws.amazon.com/inspector/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/inspector/customers/
- type: x-website
  url: https://aws.amazon.com/inspector/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---