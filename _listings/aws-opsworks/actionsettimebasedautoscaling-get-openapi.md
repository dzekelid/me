---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Set Time Based Auto Scaling
  version: 1.0.0
  description: Specify the time-based auto scaling configuration for a specified instance.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssignVolume:
    get:
      summary: Assign Volume
      description: Assigns one of the stack's registered Amazon EBS volumes to a specified
        instance.
      operationId: assignVolume
      x-api-path-slug: actionassignvolume-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: VolumeId
        description: The volume ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Volume
  /?Action=CreateDeployment:
    get:
      summary: Create Deployment
      description: Runs deployment or stack commands.
      operationId: createDeployment
      x-api-path-slug: actioncreatedeployment-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      - in: query
        name: Command
        description: A DeploymentCommand object that specifies the deployment command
          and any      associated arguments
        type: string
      - in: query
        name: Comment
        description: A user-defined comment
        type: string
      - in: query
        name: CustomJson
        description: A string that contains user-defined, custom JSON
        type: string
      - in: query
        name: InstanceIds
        description: The instance IDs for the deployment targets
        type: string
      - in: query
        name: LayerIds
        description: The layer IDs for the deployment targets
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deployment
  /?Action=DeregisterVolume:
    get:
      summary: Deregister Volume
      description: Deregisters an Amazon EBS volume.
      operationId: deregisterVolume
      x-api-path-slug: actionderegistervolume-get
      parameters:
      - in: query
        name: VolumeId
        description: The AWS OpsWorks Stacks volume ID, which is the GUID that AWS
          OpsWorks Stacks assigned to the instance when you registered the volume
          with the stack, not the Amazon EC2 volume ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deregister
      - Volume
  /?Action=DescribeDeployments:
    get:
      summary: Describe Deployments
      description: Requests a description of a specified set of deployments.
      operationId: describeDeployments
      x-api-path-slug: actiondescribedeployments-get
      parameters:
      - in: query
        name: AppId
        description: The app ID
        type: string
      - in: query
        name: DeploymentIds
        description: An array of deployment IDs to be described
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Deployments
  /?Action=DescribeStackProvisioningParameters:
    get:
      summary: Describe Stack Provisioning Parameters
      description: Requests a description of a stack's provisioning parameters.
      operationId: describeStackProvisioningParameters
      x-api-path-slug: actiondescribestackprovisioningparameters-get
      parameters:
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Stack
      - Provisioning
      - Parameters
  /?Action=DescribeTimeBasedAutoScaling:
    get:
      summary: Describe Time Based Auto Scaling
      description: Describes time-based auto scaling configurations for specified
        instances.
      operationId: describeTimeBasedAutoScaling
      x-api-path-slug: actiondescribetimebasedautoscaling-get
      parameters:
      - in: query
        name: InstanceIds
        description: An array of instance IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Time
      - Based
      - Auto
      - Scaling
  /?Action=DescribeVolumes:
    get:
      summary: Describe Volumes
      description: Describes an instance's Amazon EBS volumes.
      operationId: describeVolumes
      x-api-path-slug: actiondescribevolumes-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: RaidArrayId
        description: The RAID array ID
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      - in: query
        name: VolumeIds
        description: Am array of volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Volumes
  /?Action=GetHostnameSuggestion:
    get:
      summary: Get Hostname Suggestion
      description: Gets a generated host name for the specified layer, based on the
        current host name theme.
      operationId: getHostnameSuggestion
      x-api-path-slug: actiongethostnamesuggestion-get
      parameters:
      - in: query
        name: LayerId
        description: The layer ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hostname
      - Suggestion
  /?Action=RegisterVolume:
    get:
      summary: Register Volume
      description: Registers an Amazon EBS volume with a specified stack.
      operationId: registerVolume
      x-api-path-slug: actionregistervolume-get
      parameters:
      - in: query
        name: Ec2VolumeId
        description: The Amazon EBS volume ID
        type: string
      - in: query
        name: StackId
        description: The stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Register
      - Volume
  /?Action=SetTimeBasedAutoScaling:
    get:
      summary: Set Time Based Auto Scaling
      description: Specify the time-based auto scaling configuration for a specified
        instance.
      operationId: setTimeBasedAutoScaling
      x-api-path-slug: actionsettimebasedautoscaling-get
      parameters:
      - in: query
        name: AutoScalingSchedule
        description: An AutoScalingSchedule with the instance schedule
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Set
      - Time
      - Based
      - Auto
      - Scaling
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