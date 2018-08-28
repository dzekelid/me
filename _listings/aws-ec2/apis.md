---
name: AWS EC2
x-slug: aws-ec2
description: Amazon Elastic Compute Cloud is a web service that provides resizable
  compute capacity in the cloud. It is designed to make web-scale cloud computing
  easier for developers. Amazon EC2s simple web service interface allows you to obtain
  and configure capacity with minimal friction. It provides you with complete control
  of your computing resources and lets you run on Amazon&rsquo;s proven computing
  environment. Amazon EC2 reduces the time required to obtain and boot new server
  instances to minutes, allowing you to quickly scale capacity, both up and down,
  as your computing requirements change. Amazon EC2 changes the economics of computing
  by allowing you to pay only for capacity that you actually use. Amazon EC2 provides
  developers the tools to build failure resilient applications and isolate themselves
  from common failure scenarios.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API Delete Customer Gateway
  x-api-slug: aws-ec2-api
  description: Deletes the specified customer gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteCustomerGateway
  tags: Customer Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondeletecustomergateway-get-openapi.md
- name: AWS EC2 API Describe Customer Gateways
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPN customer gateways.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeCustomerGateways
  tags: Customer Gateways
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribecustomergateways-get-openapi.md
- name: AWS EC2 API Attach Volume
  x-api-slug: aws-ec2-api
  description: |-
    Attaches an EBS volume to a running or stopped instance and exposes it to the instance with
          the specified device name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachVolume
  tags: Drive Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionattachvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionattachvolume-get-openapi.md
- name: AWS EC2 API Create Volume
  x-api-slug: aws-ec2-api
  description: Creates an EBS volume that can be attached to an instance in the same
    Availability Zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actioncreatevolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actioncreatevolume-get-openapi.md
- name: AWS EC2 API Delete Volume
  x-api-slug: aws-ec2-api
  description: Deletes the specified EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondeletevolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondeletevolume-get-openapi.md
- name: AWS EC2 API Describe Volume Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumeAttribute
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribevolumeattribute-get-openapi.md
- name: AWS EC2 API Describe Volumes
  x-api-slug: aws-ec2-api
  description: Describes the specified EBS volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumes
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribevolumes-get-openapi.md
- name: AWS EC2 API Describe Volume Status
  x-api-slug: aws-ec2-api
  description: Describes the status of the specified volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVolumeStatus
  tags: Volume Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribevolumestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribevolumestatus-get-openapi.md
- name: AWS EC2 API Detach Volume
  x-api-slug: aws-ec2-api
  description: Detaches an EBS volume from an instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondetachvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondetachvolume-get-openapi.md
- name: AWS EC2 API Enable Volume I O
  x-api-slug: aws-ec2-api
  description: |-
    Enables I/O operations for a volume that had I/O operations disabled because the data on the
          volume was potentially inconsistent.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVolumeIO
  tags: Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionenablevolumeio-get-openapi.md
- name: AWS EC2 API Modify Volume Attribute
  x-api-slug: aws-ec2-api
  description: Modifies a volume attribute.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVolumeAttribute
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionmodifyvolumeattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionmodifyvolumeattribute-get-openapi.md
- name: AWS EC2 API Create Placement Group
  x-api-slug: aws-ec2-api
  description: Creates a placement group that you launch cluster instances into.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreatePlacementGroup
  tags: Placement Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actioncreateplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actioncreateplacementgroup-get-openapi.md
- name: AWS EC2 API Delete Placement Group
  x-api-slug: aws-ec2-api
  description: Deletes the specified placement group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeletePlacementGroup
  tags: Placement Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondeleteplacementgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondeleteplacementgroup-get-openapi.md
- name: AWS EC2 API Describe Placement Groups
  x-api-slug: aws-ec2-api
  description: Describes one or more of your placement groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribePlacementGroups
  tags: Placement Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actiondescribeplacementgroups-get-openapi.md
- name: AWS EC2 API Import Volume
  x-api-slug: aws-ec2-api
  description: Creates an import volume task using metadata from the specified disk
    image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ImportVolume
  tags: Volume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionimportvolume-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/actionimportvolume-get-openapi.md
- name: AWS EC2 API
  x-api-slug: aws-ec2-api
  description: Amazon Elastic Compute Cloud is a web service that provides resizable
    compute capacity in the cloud. It is designed to make web-scale cloud computing
    easier for developers. Amazon EC2s simple web service interface allows you to
    obtain and configure capacity with minimal friction. It provides you with complete
    control of your computing resources and lets you run on Amazon&rsquo;s proven
    computing environment. Amazon EC2 reduces the time required to obtain and boot
    new server instances to minutes, allowing you to quickly scale capacity, both
    up and down, as your computing requirements change. Amazon EC2 changes the economics
    of computing by allowing you to pay only for capacity that you actually use. Amazon
    EC2 provides developers the tools to build failure resilient applications and
    isolate themselves from common failure scenarios.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-ec2/openapi.md
x-common:
- type: x-code
  url: http://aws.amazon.com/code/Amazon-EC2/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ec2/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ec2/pricing/
- type: x-sla
  url: https://aws.amazon.com/ec2/sla/
- type: x-website
  url: https://aws.amazon.com/ec2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---