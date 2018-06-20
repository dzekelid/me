{
  "info": {
    "name": "AWS OpsWorks API Describe Stack Provisioning Parameters",
    "_postman_id": "ad31888f-7cf3-45c5-8a58-900e1c7d362b",
    "description": "Requests a description of a stack's provisioning parameters.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Instances",
      "item": [
        {
          "id": "de356dc3-5d8d-4026-96e1-b3ba2fe41be1",
          "name": "assignInstance",
          "request": {
            "url": "http://example.com/api/?Action=AssignInstance?InstanceId=InstanceId&LayerIds=LayerIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assign a registered instance to a layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "558fd2f2-c956-4a06-be4b-f963ef6c4263"
            }
          ]
        },
        {
          "id": "4ed57fe0-be76-40b7-b53b-e2df1ee0c571",
          "name": "createInstance",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstance?AgentVersion=AgentVersion&AmiId=AmiId&Architecture=Architecture&AutoScalingType=AutoScalingType&AvailabilityZone=AvailabilityZone&BlockDeviceMappings=BlockDeviceMappings&EbsOptimized=EbsOptimized&Hostname=Hostname&InstallUpdatesOnBoot=InstallUpdatesOnBoot&InstanceType=InstanceType&LayerIds=LayerIds&Os=Os&RootDeviceType=RootDeviceType&SshKeyName=SshKeyName&StackId=StackId&SubnetId=SubnetId&Tenancy=Tenancy&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an instance in a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c940eceb-6d3b-482a-b3e2-72d4b2690866"
            }
          ]
        },
        {
          "id": "a6b7cdde-4ce1-4d22-a371-2398f1bac07c",
          "name": "deleteInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstance?DeleteElasticIp=DeleteElasticIp&DeleteVolumes=DeleteVolumes&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified instance, which terminates the associated Amazon EC2 instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27d5bf42-92ad-4c07-bec5-36a7ad539214"
            }
          ]
        },
        {
          "id": "5d2529ed-8fea-452c-b806-b0560d8979a8",
          "name": "deregisterInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterInstance?InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregister a registered Amazon EC2 or on-premises instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b2c4575-befa-4e63-9913-4becb23f3689"
            }
          ]
        },
        {
          "id": "c855c369-7c80-4d1e-841b-b54875fcc18c",
          "name": "deregisterRdsDbInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterRdsDbInstance?RdsDbInstanceArn=RdsDbInstanceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters an Amazon RDS instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15f044be-fcda-4b7d-83be-8809a9d72d79"
            }
          ]
        },
        {
          "id": "ec7ec57a-0b70-49f9-90df-b562448dcda5",
          "name": "describeInstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?InstanceIds=InstanceIds&LayerId=LayerId&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a set of instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a8e0079-b523-4ca5-9f8e-6dbad8750b07"
            }
          ]
        },
        {
          "id": "49a712e9-2c2e-415d-af5e-20b044ae9765",
          "name": "describeRdsDbInstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRdsDbInstances?RdsDbInstanceArns=RdsDbInstanceArns&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Amazon RDS instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94404039-e955-4bc0-b4b4-e5f08e2de20a"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "9f64ca74-f313-4e95-8da8-002439239aea",
          "name": "assignVolume",
          "request": {
            "url": "http://example.com/api/?Action=AssignVolume?InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one of the stack's registered Amazon EBS volumes to a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a77d4b15-fc6a-4e16-a78a-47b45af51257"
            }
          ]
        },
        {
          "id": "64921afb-a9c2-4a85-8cdc-c5afd265bfa0",
          "name": "deregisterVolume",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterVolume?VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters an Amazon EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1687a443-4b80-41b5-a2a6-99be4df8dbb3"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "bf7427e3-298b-46aa-b023-2be525ea0586",
          "name": "associateElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=AssociateElasticIp?ElasticIp=ElasticIp&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates one of the stack's registered Elastic IP addresses with a specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91665ac9-2da9-43aa-8eb6-9bf04851a0b1"
            }
          ]
        },
        {
          "id": "1689ec77-dcc9-409e-9398-74a6582518ee",
          "name": "deregisterElasticIp",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterElasticIp?ElasticIp=ElasticIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters a specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4abaea93-6b59-4f23-bdaa-5d021e4adc87"
            }
          ]
        },
        {
          "id": "96285833-9039-4dc1-b7a6-1e3b1a069726",
          "name": "describeElasticIps",
          "request": {
            "url": "http://example.com/api/?Action=DescribeElasticIps?InstanceId=InstanceId&Ips=Ips&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Elastic IPs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d0dd9ad-8fac-4514-95c3-a8928416e0ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "e9ee95f5-73c1-4f0d-aa9d-ac0aac1d229f",
          "name": "attachElasticLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=AttachElasticLoadBalancer?ElasticLoadBalancerName=ElasticLoadBalancerName&LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an Elastic Load Balancing load balancer to a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16aed0f8-21bb-4e31-a725-80f4a047f8dd"
            }
          ]
        },
        {
          "id": "2004862e-31fa-43fc-a0aa-ec85326556e2",
          "name": "describeElasticLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeElasticLoadBalancers?LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a stack's Elastic Load Balancing instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "597daaa0-5dc9-4dd2-ad17-a3fe5529e720"
            }
          ]
        }
      ]
    },
    {
      "name": "Stacks",
      "item": [
        {
          "id": "bad0bb65-8d91-4e8a-841a-39f3c6b31883",
          "name": "cloneStack",
          "request": {
            "url": "http://example.com/api/?Action=CloneStack?AgentVersion=AgentVersion&Attributes=Attributes&ChefConfiguration=ChefConfiguration&CloneAppIds=CloneAppIds&ClonePermissions=ClonePermissions&ConfigurationManager=ConfigurationManager&CustomCookbooksSource=CustomCookbooksSource&CustomJson=CustomJson&DefaultAvailabilityZone=DefaultAvailabilityZone&DefaultInstanceProfileArn=DefaultInstanceProfileArn&DefaultOs=DefaultOs&DefaultRootDeviceType=DefaultRootDeviceType&DefaultSshKeyName=DefaultSshKeyName&DefaultSubnetId=DefaultSubnetId&HostnameTheme=HostnameTheme&Name=Name&Region=Region&ServiceRoleArn=ServiceRoleArn&SourceStackId=SourceStackId&UseCustomCookbooks=UseCustomCookbooks&UseOpsworksSecurityGroups=UseOpsworksSecurityGroups&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a clone of a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe82d9f4-b426-4d89-94c1-2dee41962240"
            }
          ]
        },
        {
          "id": "c357bd1e-bf91-42ff-a225-3afc0328fe56",
          "name": "describeStackProvisioningParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackProvisioningParameters?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a stack's provisioning parameters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d69d236a-31f0-4f8f-8bb7-08bc6c7bd63c"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "131da5f9-8cfd-4d8b-9574-68f4a263a609",
          "name": "createApp",
          "request": {
            "url": "http://example.com/api/?Action=CreateApp?AppSource=AppSource&Attributes=Attributes&DataSources=DataSources&Description=Description&Domains=Domains&EnableSsl=EnableSsl&Environment=Environment&Name=Name&Shortname=Shortname&SslConfiguration=SslConfiguration&StackId=StackId&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an app for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f7fff87-61fd-4de6-84b0-e0069a500a80"
            }
          ]
        },
        {
          "id": "d4030fe3-33ad-41fa-a96b-d25f8b5a0bf9",
          "name": "deleteApp",
          "request": {
            "url": "http://example.com/api/?Action=DeleteApp?AppId=AppId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48ba204f-3b71-46f5-a010-cfddd2c627ee"
            }
          ]
        },
        {
          "id": "1e2917be-67d8-4800-9df4-5e181472fe81",
          "name": "describeApps",
          "request": {
            "url": "http://example.com/api/?Action=DescribeApps?AppIds=AppIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a specified set of apps."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d06b922-a7d7-454d-95e0-a05980be9a88"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "8d2458cc-7855-48c1-aaa2-fc91c842b565",
          "name": "createDeployment",
          "request": {
            "url": "http://example.com/api/?Action=CreateDeployment?AppId=AppId&Command=Command&Comment=Comment&CustomJson=CustomJson&InstanceIds=InstanceIds&LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Runs deployment or stack commands."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fa092f9-eb51-4b91-88d0-f4223431eac7"
            }
          ]
        },
        {
          "id": "c08c7ef1-9ec7-4076-b3ae-38590431ab68",
          "name": "createLayer",
          "request": {
            "url": "http://example.com/api/?Action=CreateLayer?Attributes=Attributes&AutoAssignElasticIps=AutoAssignElasticIps&AutoAssignPublicIps=AutoAssignPublicIps&CustomInstanceProfileArn=CustomInstanceProfileArn&CustomJson=CustomJson&CustomRecipes=CustomRecipes&CustomSecurityGroupIds=CustomSecurityGroupIds&EnableAutoHealing=EnableAutoHealing&InstallUpdatesOnBoot=InstallUpdatesOnBoot&LifecycleEventConfiguration=LifecycleEventConfiguration&Name=Name&Packages=Packages&Shortname=Shortname&StackId=StackId&Type=Type&UseEbsOptimizedInstances=UseEbsOptimizedInstances&VolumeConfigurations=VolumeConfigurations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6baa95b-9a6e-4ffc-b278-a92a778e485c"
            }
          ]
        },
        {
          "id": "c2decd4f-e380-43c9-88d0-4fa4aa7a5af8",
          "name": "createStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?AgentVersion=AgentVersion&Attributes=Attributes&ChefConfiguration=ChefConfiguration&ConfigurationManager=ConfigurationManager&CustomCookbooksSource=CustomCookbooksSource&CustomJson=CustomJson&DefaultAvailabilityZone=DefaultAvailabilityZone&DefaultInstanceProfileArn=DefaultInstanceProfileArn&DefaultOs=DefaultOs&DefaultRootDeviceType=DefaultRootDeviceType&DefaultSshKeyName=DefaultSshKeyName&DefaultSubnetId=DefaultSubnetId&HostnameTheme=HostnameTheme&Name=Name&Region=Region&ServiceRoleArn=ServiceRoleArn&UseCustomCookbooks=UseCustomCookbooks&UseOpsworksSecurityGroups=UseOpsworksSecurityGroups&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13d8cbaa-0729-4996-97bb-4af5427a1480"
            }
          ]
        },
        {
          "id": "7384bbe2-d18b-4e78-af98-6aa09005ccec",
          "name": "createUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserProfile?AllowSelfManagement=AllowSelfManagement&IamUserArn=IamUserArn&SshPublicKey=SshPublicKey&SshUsername=SshUsername",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36a494d6-a1c0-4467-a173-1660f6fc6a66"
            }
          ]
        },
        {
          "id": "a4202937-f607-4f52-b5be-c448b56a42cc",
          "name": "deleteLayer",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLayer?LayerId=LayerId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified layer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c8b2de3-4220-445b-b996-47da39e60bd4"
            }
          ]
        },
        {
          "id": "115a456b-8795-495b-af71-8d876c57a3c5",
          "name": "deleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c98543f-8516-4cff-a9b2-24bc477dacba"
            }
          ]
        },
        {
          "id": "0425ed4d-6bef-4788-9f78-3ddb8a819aa1",
          "name": "deleteUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserProfile?IamUserArn=IamUserArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4fc90a5-edfe-4bb6-ac42-fa6d1587aa7c"
            }
          ]
        },
        {
          "id": "c92cdb4d-a328-4562-a5a8-7289766579a9",
          "name": "deregisterEcsCluster",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterEcsCluster?EcsClusterArn=EcsClusterArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters a specified Amazon ECS cluster from a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4df4e225-3dc3-42bc-b69a-c09e0259596f"
            }
          ]
        }
      ]
    },
    {
      "name": "Agent Versions",
      "item": [
        {
          "id": "64240435-4906-43cc-8e8a-b23d4878dd25",
          "name": "describeAgentVersions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAgentVersions?ConfigurationManager=ConfigurationManager&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the available AWS OpsWorks Stacks agent versions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b65030fb-a17c-4ed1-9d4a-42a065f2d9bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Commands",
      "item": [
        {
          "id": "306449d2-8714-43dc-9075-76f5b9906854",
          "name": "describeCommands",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCommands?CommandIds=CommandIds&DeploymentId=DeploymentId&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the results of specified commands."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e45418c-1f22-46e8-bf81-fde1b20b16d3"
            }
          ]
        }
      ]
    },
    {
      "name": "Deployments",
      "item": [
        {
          "id": "d261886c-49a3-475d-8aa9-480b431a8410",
          "name": "describeDeployments",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDeployments?AppId=AppId&DeploymentIds=DeploymentIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of a specified set of deployments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2546cf22-317f-4963-ad87-3a1079d193fd"
            }
          ]
        }
      ]
    },
    {
      "name": "ECS Clusters",
      "item": [
        {
          "id": "9ae7f4f4-06d7-40a5-8007-265e0970e814",
          "name": "describeEcsClusters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEcsClusters?EcsClusterArns=EcsClusterArns&MaxResults=MaxResults&NextToken=NextToken&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Amazon ECS clusters that are registered with a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32df13b0-ae1d-4d3c-bd95-662a8e1b1401"
            }
          ]
        }
      ]
    },
    {
      "name": "Layers",
      "item": [
        {
          "id": "b3d32364-f6ce-4dbb-b8ce-7fcd4b479633",
          "name": "describeLayers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLayers?LayerIds=LayerIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a description of one or more layers in a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fe4e842-2832-473b-ab41-ec2bc2f018df"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling",
      "item": [
        {
          "id": "e3610e4e-b04b-4b07-9572-27bf7469dbe6",
          "name": "describeLoadBasedAutoScaling",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBasedAutoScaling?LayerIds=LayerIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes load-based auto scaling configurations for specified layers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0274406-1765-4d5f-87f0-2553ea80847d"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "72eb6f6d-30ac-4801-91dc-5f182f1c405b",
          "name": "describeMyUserProfile",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMyUserProfile?UserProfile=UserProfile",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a user's SSH information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7ca3236-5203-4a3a-a467-a7d5a1a27182"
            }
          ]
        }
      ]
    },
    {
      "name": "Permissions",
      "item": [
        {
          "id": "d0d356d9-4a18-4c18-a8a0-5d835e96bc62",
          "name": "describePermissions",
          "request": {
            "url": "http://example.com/api/?Action=DescribePermissions?IamUserArn=IamUserArn&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the permissions for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "009013cd-3147-42dc-ad96-c7080a141118"
            }
          ]
        }
      ]
    },
    {
      "name": "Raid Arrays",
      "item": [
        {
          "id": "a7705afa-65a9-4d6d-a518-98d1d510f4f6",
          "name": "describeRaidArrays",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRaidArrays?InstanceId=InstanceId&RaidArrayIds=RaidArrayIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describe an instance's RAID arrays."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef039e70-97b5-47fb-90ca-1900f79a598b"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Errors",
      "item": [
        {
          "id": "b4c26311-3848-4fea-9374-bbc2053e3e8c",
          "name": "describeServiceErrors",
          "request": {
            "url": "http://example.com/api/?Action=DescribeServiceErrors?InstanceId=InstanceId&ServiceErrorIds=ServiceErrorIds&StackId=StackId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes AWS OpsWorks Stacks service errors."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2a6054d-1dc7-44c4-811c-b2493daf3ee9"
            }
          ]
        }
      ]
    }
  ]
}