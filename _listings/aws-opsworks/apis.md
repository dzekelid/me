---
name: AWS OpsWorks
x-slug: aws-opsworks
description: AWS OpsWorks is a configuration management service that uses Chef, an
  automation platform that treats server configurations as code. OpsWorks uses Chef
  to automate how servers are configured, deployed, and managed across your Amazon
  Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
  OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/apis.md
specificationVersion: "0.14"
apis:
- name: AWS OpsWorks API Assign Volume
  x-api-slug: aws-opsworks-api
  description: Assigns one of the stack's registered Amazon EBS volumes to a specified
    instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=AssignVolume
  tags: Assign,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionassignvolume-get-openapi.md
- name: AWS OpsWorks API Create Deployment
  x-api-slug: aws-opsworks-api
  description: Runs deployment or stack commands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateDeployment
  tags: Deployment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actioncreatedeployment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actioncreatedeployment-get-openapi.md
- name: AWS OpsWorks API Deregister Volume
  x-api-slug: aws-opsworks-api
  description: Deregisters an Amazon EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterVolume
  tags: Deregister,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionderegistervolume-get-openapi.md
- name: AWS OpsWorks API Describe Deployments
  x-api-slug: aws-opsworks-api
  description: Requests a description of a specified set of deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeDeployments
  tags: Describe,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiondescribedeployments-get-openapi.md
- name: AWS OpsWorks API Describe Stack Provisioning Parameters
  x-api-slug: aws-opsworks-api
  description: Requests a description of a stack's provisioning parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeStackProvisioningParameters
  tags: Describe,Stack,Provisioning,Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiondescribestackprovisioningparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiondescribestackprovisioningparameters-get-openapi.md
- name: AWS OpsWorks API Describe Time Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Describes time-based auto scaling configurations for specified instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeTimeBasedAutoScaling
  tags: Describe,Time,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiondescribetimebasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Describe Volumes
  x-api-slug: aws-opsworks-api
  description: Describes an instance's Amazon EBS volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeVolumes
  tags: Describe,Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiondescribevolumes-get-openapi.md
- name: AWS OpsWorks API Get Hostname Suggestion
  x-api-slug: aws-opsworks-api
  description: Gets a generated host name for the specified layer, based on the current
    host name theme.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=GetHostnameSuggestion
  tags: Hostname,Suggestion
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiongethostnamesuggestion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actiongethostnamesuggestion-get-openapi.md
- name: AWS OpsWorks API Register Volume
  x-api-slug: aws-opsworks-api
  description: Registers an Amazon EBS volume with a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterVolume
  tags: Register,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionregistervolume-get-openapi.md
- name: AWS OpsWorks API Set Time Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Specify the time-based auto scaling configuration for a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=SetTimeBasedAutoScaling
  tags: Set,Time,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionsettimebasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Unassign Volume
  x-api-slug: aws-opsworks-api
  description: Unassigns an assigned Amazon EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UnassignVolume
  tags: Unassign,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionunassignvolume-get-openapi.md
- name: AWS OpsWorks API Update Volume
  x-api-slug: aws-opsworks-api
  description: Updates an Amazon EBS volume's name or mount point.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/actionupdatevolume-get-openapi.md
- name: AWS OpsWorks API
  x-api-slug: aws-opsworks-api
  description: AWS OpsWorks is a configuration management service that uses Chef,
    an automation platform that treats server configurations as code. OpsWorks uses
    Chef to automate how servers are configured, deployed, and managed across your
    Amazon Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
    OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-opsworks/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/opsworks/latest/APIReference/Welcome.html
- type: x-website
  url: https://aws.amazon.com/opsworks/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---