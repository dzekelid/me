---
swagger: "2.0"
x-collection-name: AWS CodeDeploy
x-complete: 0
info:
  title: AWS CodeDeploy API Create Deployment Group
  version: 1.0.0
  description: |-
    Creates a deployment group to which application revisions will be
                deployed.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetDeploymentGroups:
    get:
      summary: Batch Get Deployment Groups
      description: Gets information about one or more deployment groups.
      operationId: batchGetDeploymentGroups
      x-api-path-slug: actionbatchgetdeploymentgroups-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      - in: query
        name: deploymentGroupNames
        description: The deployment groups names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment Groups
  /?Action=BatchGetDeploymentInstances:
    get:
      summary: Batch Get Deployment Instances
      description: |-
        Gets information about one or more instance that are part of a deployment
                    group.
      operationId: batchGetDeploymentInstances
      x-api-path-slug: actionbatchgetdeploymentinstances-get
      parameters:
      - in: query
        name: deploymentId
        description: The unique ID of a deployment
        type: string
      - in: query
        name: instanceIds
        description: The unique IDs of instances in the deployment group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment Instances
  /?Action=BatchGetDeployments:
    get:
      summary: Batch Get Deployments
      description: Gets information about one or more deployments.
      operationId: batchGetDeployments
      x-api-path-slug: actionbatchgetdeployments-get
      parameters:
      - in: query
        name: deploymentIds
        description: A list of deployment IDs, separated by spaces
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /?Action=CreateDeployment:
    get:
      summary: Create Deployment
      description: Deploys an application revision through the specified deployment
        group.
      operationId: createDeployment
      x-api-path-slug: actioncreatedeployment-get
      parameters:
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      - in: query
        name: autoRollbackConfiguration
        description: Configuration information for an automatic rollback that is added
          when a deployment            is created
        type: string
      - in: query
        name: deploymentConfigName
        description: The name of a deployment configuration associated with the applicable
          IAM user or            AWS account
        type: string
      - in: query
        name: deploymentGroupName
        description: The name of the deployment group
        type: string
      - in: query
        name: description
        description: A comment about the deployment
        type: string
      - in: query
        name: ignoreApplicationStopFailures
        description: If set to true, then if the deployment causes the ApplicationStop
          deployment            lifecycle event to an instance to fail, the deployment
          to that instance will not be            considered to have failed at that
          point and will continue on to the BeforeInstall            deployment lifecycle
          event
        type: string
      - in: query
        name: revision
        description: The type and location of the revision to deploy
        type: string
      - in: query
        name: updateOutdatedInstancesOnly
        description: Indicates whether to deploy to all instances or only to instances
          that are not            running the latest application revision
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /?Action=CreateDeploymentConfig:
    get:
      summary: Create Deployment Config
      description: Creates a deployment configuration.
      operationId: createDeploymentConfig
      x-api-path-slug: actioncreatedeploymentconfig-get
      parameters:
      - in: query
        name: deploymentConfigName
        description: The name of the deployment configuration to create
        type: string
      - in: query
        name: minimumHealthyHosts
        description: The minimum number of healthy instances that should be available
          at any time during            the deployment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /?Action=CreateDeploymentGroup:
    get:
      summary: Create Deployment Group
      description: |-
        Creates a deployment group to which application revisions will be
                    deployed.
      operationId: createDeploymentGroup
      x-api-path-slug: actioncreatedeploymentgroup-get
      parameters:
      - in: query
        name: alarmConfiguration
        description: Information to add about Amazon CloudWatch alarms when the deployment
          group is            created
        type: string
      - in: query
        name: applicationName
        description: The name of an AWS CodeDeploy application associated with the
          applicable IAM user            or AWS account
        type: string
      - in: query
        name: autoRollbackConfiguration
        description: Configuration information for an automatic rollback that is added
          when a deployment            group is created
        type: string
      - in: query
        name: autoScalingGroups
        description: A list of associated Auto Scaling groups
        type: string
      - in: query
        name: deploymentConfigName
        description: If specified, the deployment configuration name can be either
          one of the predefined            configurations provided with AWS CodeDeploy
          or a custom deployment configuration that            you create by calling
          the create deployment configuration operation
        type: string
      - in: query
        name: deploymentGroupName
        description: The name of a new deployment group for the specified application
        type: string
      - in: query
        name: ec2TagFilters
        description: The Amazon EC2 tags on which to filter
        type: string
      - in: query
        name: onPremisesInstanceTagFilters
        description: The on-premises instance tags on which to filter
        type: string
      - in: query
        name: serviceRoleArn
        description: A service role ARN that allows AWS CodeDeploy to act on the users
          behalf when            interacting with AWS services
        type: string
      - in: query
        name: triggerConfigurations
        description: Information about triggers to create when the deployment group
          is created
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment Groups
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