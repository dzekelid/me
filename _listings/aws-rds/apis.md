---
name: AWS RDS
x-slug: aws-rds
description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
  up, operate, and scale arelational databasein the cloud. It provides cost-efficient
  and resizable capacity while managing time-consuming database administration tasks,
  freeing you up to focus on your applications and business. Amazon RDS provides you
  six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
  andMicrosoft SQL Server.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/apis.md
specificationVersion: "0.14"
apis:
- name: Amazon RDS API Copy D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Copies the specified DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actioncopydbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Copy D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Copies the specified DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CopyDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actioncopydbparametergroup-get-openapi.md
- name: Amazon RDS API Create D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actioncreatedbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Create D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Creates a new DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=CreateDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actioncreatedbparametergroup-get-openapi.md
- name: Amazon RDS API Delete D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Deletes a specified DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondeletedbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Delete D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Deletes a specified DBParameterGroup.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DeleteDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondeletedbparametergroup-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Parameter Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBClusterParameterGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterParameterGroups
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribedbclusterparametergroups-get-openapi.md
- name: Amazon RDS API Describe D B Cluster Parameters
  x-api-slug: amazon-rds-api
  description: Returns the detailed parameter list for a particular DB cluster parameter
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBClusterParameters
  tags: Cluster Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribedbclusterparameters-get-openapi.md
- name: Amazon RDS API Describe D B Parameter Groups
  x-api-slug: amazon-rds-api
  description: Returns a list of DBParameterGroup descriptions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBParameterGroups
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribedbparametergroups-get-openapi.md
- name: Amazon RDS API Describe D B Parameters
  x-api-slug: amazon-rds-api
  description: Returns the detailed parameter list for a particular DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeDBParameters
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribedbparameters-get-openapi.md
- name: Amazon RDS API Describe Engine Default Cluster Parameters
  x-api-slug: amazon-rds-api
  description: Returns the default engine and system parameter information for the
    cluster database engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEngineDefaultClusterParameters
  tags: Default Cluster Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribeenginedefaultclusterparameters-get-openapi.md
- name: Amazon RDS API Describe Engine Default Parameters
  x-api-slug: amazon-rds-api
  description: Returns the default engine and system parameter information for the
    specified database engine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=DescribeEngineDefaultParameters
  tags: Default Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actiondescribeenginedefaultparameters-get-openapi.md
- name: Amazon RDS API Modify D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB cluster parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actionmodifydbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Modify D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB parameter group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ModifyDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actionmodifydbparametergroup-get-openapi.md
- name: Amazon RDS API Reset D B Cluster Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB cluster parameter group to the default
    value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ResetDBClusterParameterGroup
  tags: Cluster Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actionresetdbclusterparametergroup-get-openapi.md
- name: Amazon RDS API Reset D B Parameter Group
  x-api-slug: amazon-rds-api
  description: Modifies the parameters of a DB parameter group to the engine/system
    default value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: ://///?Action=ResetDBParameterGroup
  tags: Parameter Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/actionresetdbparametergroup-get-openapi.md
- name: Amazon RDS API
  x-api-slug: amazon-rds-api
  description: Amazon Relational Database Service (Amazon RDS) makes it easy to set
    up, operate, and scale arelational databasein the cloud. It provides cost-efficient
    and resizable capacity while managing time-consuming database administration tasks,
    freeing you up to focus on your applications and business. Amazon RDS provides
    you six familiar database engines to choose from, includingAmazon Aurora,PostgreSQL,MySQL,MariaDB,Oracle,
    andMicrosoft SQL Server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AmazonRDS.png
  humanURL: https://aws.amazon.com/rds/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-rds/openapi.md
x-common:
- type: x-articles
  url: https://aws.amazon.com/articles/Amazon-RDS
- type: x-blog
  url: https://aws.amazon.com/blogs/database/
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=291
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=293
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/AmazonRDS/latest/CommandLineReference/
- type: x-customer-highlights
  url: https://aws.amazon.com/rds/customers/
- type: x-documentation
  url: http://docs.aws.amazon.com/AmazonRDS/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/rds/faqs/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=60
- type: x-getting-started
  url: https://aws.amazon.com/rds/getting-started/
- type: x-partners
  url: https://aws.amazon.com/rds/partners/
- type: x-pricing
  url: https://aws.amazon.com/rds/pricing/
- type: x-service-level-agreement
  url: https://aws.amazon.com/rds/sla/
- type: x-tools
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=294
- type: x-website
  url: https://aws.amazon.com/rds/
- type: x-whats-new
  url: https://aws.amazon.com/rds/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---