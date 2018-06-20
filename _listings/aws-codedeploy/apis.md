---
name: AWS CodeDeploy
x-slug: aws-codedeploy
description: AWS CodeDeploy is a service that automates code deployments to any instance,
  including Amazon EC2 instances and instances running on-premises. AWS CodeDeploy
  makes it easier for you to rapidly release new features, helps you avoid downtime
  during application deployment, and handles the complexity of updating your applications.
  You can use AWS CodeDeploy to automate software deployments, eliminating the need
  for error-prone manual operations, and the service scales with your infrastructure
  so you can easily deploy to one instance or thousands.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeDeploy API Batch Get Deployment Groups
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more deployment groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeploymentGroups
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionbatchgetdeploymentgroups-get-openapi.md
- name: AWS CodeDeploy API Batch Get Deployment Instances
  x-api-slug: aws-codedeploy-api
  description: |-
    Gets information about one or more instance that are part of a deployment
                group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeploymentInstances
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionbatchgetdeploymentinstances-get-openapi.md
- name: AWS CodeDeploy API Batch Get Deployments
  x-api-slug: aws-codedeploy-api
  description: Gets information about one or more deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=BatchGetDeployments
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionbatchgetdeployments-get-openapi.md
- name: AWS CodeDeploy API Create Deployment
  x-api-slug: aws-codedeploy-api
  description: Deploys an application revision through the specified deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actioncreatedeployment-get-openapi.md
- name: AWS CodeDeploy API Create Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Creates a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actioncreatedeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Create Deployment Group
  x-api-slug: aws-codedeploy-api
  description: |-
    Creates a deployment group to which application revisions will be
                deployed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=CreateDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actioncreatedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Delete Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Deletes a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeleteDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiondeletedeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Delete Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Deletes a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=DeleteDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiondeletedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Get Deployment
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiongetdeployment-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Config
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentConfig
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiongetdeploymentconfig-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Gets information about a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiongetdeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API Get Deployment Instance
  x-api-slug: aws-codedeploy-api
  description: Gets information about an instance as part of a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=GetDeploymentInstance
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actiongetdeploymentinstance-get-openapi.md
- name: AWS CodeDeploy API List Deployment Configs
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployment configurations with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentConfigs
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionlistdeploymentconfigs-get-openapi.md
- name: AWS CodeDeploy API List Deployment Groups
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployment groups for an application registered with the applicable IAM
                user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentGroups
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionlistdeploymentgroups-get-openapi.md
- name: AWS CodeDeploy API List Deployment Instances
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the instance for a deployment associated with the applicable IAM user or AWS
                account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeploymentInstances
  tags: Deployment Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionlistdeploymentinstances-get-openapi.md
- name: AWS CodeDeploy API List Deployments
  x-api-slug: aws-codedeploy-api
  description: |-
    Lists the deployments in a deployment group for an application registered with the
                applicable IAM user or AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=ListDeployments
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionlistdeployments-get-openapi.md
- name: AWS CodeDeploy API Stop Deployment
  x-api-slug: aws-codedeploy-api
  description: Attempts to stop an ongoing deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=StopDeployment
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionstopdeployment-get-openapi.md
- name: AWS CodeDeploy API Update Deployment Group
  x-api-slug: aws-codedeploy-api
  description: Changes information about a deployment group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: ://///?Action=UpdateDeploymentGroup
  tags: Deployment Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/actionupdatedeploymentgroup-get-openapi.md
- name: AWS CodeDeploy API
  x-api-slug: aws-codedeploy-api
  description: AWS CodeDeploy is a service that automates code deployments to any
    instance, including Amazon EC2 instances and instances running on-premises. AWS
    CodeDeploy makes it easier for you to rapidly release new features, helps you
    avoid downtime during application deployment, and handles the complexity of updating
    your applications. You can use AWS CodeDeploy to automate software deployments,
    eliminating the need for error-prone manual operations, and the service scales
    with your infrastructure so you can easily deploy to one instance or thousands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-codedeploy.png
  humanURL: https://aws.amazon.com/codedeploy/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-codedeploy/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codedeploy
- type: x-documentation
  url: http://docs.aws.amazon.com/codedeploy/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/codedeploy/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=179
- type: x-getting-started
  url: https://aws.amazon.com/codedeploy/getting-started/
- type: x-integrations
  url: https://aws.amazon.com/codedeploy/product-integrations/
- type: x-partners
  url: https://aws.amazon.com/solutions/partners/dev-ops/
- type: x-pricing
  url: https://aws.amazon.com/codedeploy/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/codedeploy/developer-resources/#tutorials
- type: x-website
  url: https://aws.amazon.com/codedeploy/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---