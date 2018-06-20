---
name: AWS EC2 Systems Manager
x-slug: aws-ec2-systems-manager
description: Amazon EC2 Systems Manager is a management service that helps you automatically
  collect software inventory, apply OS patches, create system images, and configure
  Windows and Linux operating systems. These capabilities help you define and track
  system configurations, prevent drift, and maintain software compliance of your EC2
  and on-premises configurations. By providing a management approach that is designed
  for the scale and agility of the cloud but extends into your on-premises data center,
  EC2 Systems Manager makes it easier for you to seamlessly bridge your existing infrastructure
  with AWS.EC2 Systems Manager is easy to use. Simply access EC2 Systems Manager from
  the EC2 Management Console, select the instances you want to manage, and define
  the management tasks you want to perform. EC2 Systems Manager is available now at
  no cost to manage both your EC2 and on-premises resources.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon EC2 Systems Manager API Create Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Creates an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=CreateDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actioncreatedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actioncreatedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Deletes the SSM document and all instance associations to the document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondeletedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondeletedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Delete Parameter
  x-api-slug: amazon-ec2-systems-manager-api
  description: Delete a parameter from the system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DeleteParameter
  tags: Parameter
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondeleteparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondeleteparameter-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondescribedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Document Permission
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes the permissions for an SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeDocumentPermission
  tags: Document, Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondescribedocumentpermission-get-openapi.md
- name: Amazon EC2 Systems Manager API Describe Parameters
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get information about a parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=DescribeParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiondescribeparameters-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: Gets the contents of the specified SSM document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiongetdocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiongetdocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Parameter History
  x-api-slug: amazon-ec2-systems-manager-api
  description: Query a list of all parameters used by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetParameterHistory
  tags: Parameter, History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiongetparameterhistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiongetparameterhistory-get-openapi.md
- name: Amazon EC2 Systems Manager API Get Parameters
  x-api-slug: amazon-ec2-systems-manager-api
  description: Get a list of parameters used by the AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=GetParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actiongetparameters-get-openapi.md
- name: Amazon EC2 Systems Manager API List Documents
  x-api-slug: amazon-ec2-systems-manager-api
  description: Describes one or more of your SSM documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListDocuments
  tags: List, Documents
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionlistdocuments-get-openapi.md
- name: Amazon EC2 Systems Manager API List Document Versions
  x-api-slug: amazon-ec2-systems-manager-api
  description: List all versions for a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ListDocumentVersions
  tags: List, Document, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionlistdocumentversions-get-openapi.md
- name: Amazon EC2 Systems Manager API Modify Document Permission
  x-api-slug: amazon-ec2-systems-manager-api
  description: Share a document publicly or privately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=ModifyDocumentPermission
  tags: Modify, Document, Permission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionmodifydocumentpermission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionmodifydocumentpermission-get-openapi.md
- name: Amazon EC2 Systems Manager API Put Parameter
  x-api-slug: amazon-ec2-systems-manager-api
  description: Add one or more paramaters to the system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=PutParameter
  tags: Parameter
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionputparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionputparameter-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Document
  x-api-slug: amazon-ec2-systems-manager-api
  description: The document you want to update.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateDocument
  tags: Document
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionupdatedocument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionupdatedocument-get-openapi.md
- name: Amazon EC2 Systems Manager API Update Document Default Version
  x-api-slug: amazon-ec2-systems-manager-api
  description: Set the default version of a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: ://///?Action=UpdateDocumentDefaultVersion
  tags: Document, Default, Version
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionupdatedocumentdefaultversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/actionupdatedocumentdefaultversion-get-openapi.md
- name: Amazon EC2 Systems Manager API
  x-api-slug: amazon-ec2-systems-manager-api
  description: Amazon EC2 Systems Manager is a management service that helps you automatically
    collect software inventory, apply OS patches, create system images, and configure
    Windows and Linux operating systems. These capabilities help you define and track
    system configurations, prevent drift, and maintain software compliance of your
    EC2 and on-premises configurations. By providing a management approach that is
    designed for the scale and agility of the cloud but extends into your on-premises
    data center, EC2 Systems Manager makes it easier for you to seamlessly bridge
    your existing infrastructure with AWS.EC2 Systems Manager is easy to use. Simply
    access EC2 Systems Manager from the EC2 Management Console, select the instances
    you want to manage, and define the management tasks you want to perform. EC2 Systems
    Manager is available now at no cost to manage both your EC2 and on-premises resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/systems-manager/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2-systems-manager/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/ssm/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/systems-manager/faqs/
- type: x-getting-started
  url: http://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/systems-manager.html
- type: x-website
  url: https://aws.amazon.com/ec2/systems-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---