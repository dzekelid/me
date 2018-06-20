---
name: AWS Simple Queue Service
x-slug: aws-simple-queue-service
description: Amazon Simple Queue Service (SQS) is a fast, reliable, scalable, fully
  managed message queuing service. Amazon SQS makes it simple and cost-effective to
  decouple the components of a cloud application. You can use Amazon SQS to transmit
  any volume of data, without losing messages or requiring other services to be always
  available. Amazon SQS includesstandard queueswith high throughput and at-least-once
  processing, andFIFO queuesthat provide FIFO (first-in, first-out) delivery and exactly-once
  processing. With Amazon SQS, you can offload the administrative burden of operating
  and scaling a highly available messaging cluster, while paying a low price for only
  what you use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Queue Service API Change Message Visibility
  x-api-slug: aws-simple-queue-service-api
  description: Changes the visibility timeout of a specified message in a queue to
    a new value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=ChangeMessageVisibility
  tags: 'Message Visibility '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionchangemessagevisibility-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionchangemessagevisibility-get-openapi.md
- name: AWS Simple Queue Service API Change Message Visibility Batch
  x-api-slug: aws-simple-queue-service-api
  description: Changes the visibility timeout of multiple messages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=ChangeMessageVisibilityBatch
  tags: 'Message Visibility '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionchangemessagevisibilitybatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionchangemessagevisibilitybatch-get-openapi.md
- name: AWS Simple Queue Service API Delete Message
  x-api-slug: aws-simple-queue-service-api
  description: Deletes the specified message from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=DeleteMessage
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actiondeletemessage-get-openapi.md
- name: AWS Simple Queue Service API Delete Message Batch
  x-api-slug: aws-simple-queue-service-api
  description: Deletes up to ten messages from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=DeleteMessageBatch
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actiondeletemessagebatch-get-openapi.md
- name: AWS Simple Queue Service API Receive Message
  x-api-slug: aws-simple-queue-service-api
  description: Retrieves one or more messages (up to 10), from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=ReceiveMessage
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionreceivemessage-get-openapi.md
- name: AWS Simple Queue Service API Send Message
  x-api-slug: aws-simple-queue-service-api
  description: Delivers a message to the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=SendMessage
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionsendmessage-get-openapi.md
- name: AWS Simple Queue Service API Send Message Batch
  x-api-slug: aws-simple-queue-service-api
  description: Delivers up to ten messages to the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: ://///?Action=SendMessageBatch
  tags: Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/actionsendmessagebatch-get-openapi.md
- name: AWS Simple Queue Service API
  x-api-slug: aws-simple-queue-service-api
  description: Amazon Simple Queue Service (SQS) is a fast, reliable, scalable, fully
    managed message queuing service. Amazon SQS makes it simple and cost-effective
    to decouple the components of a cloud application. You can use Amazon SQS to transmit
    any volume of data, without losing messages or requiring other services to be
    always available. Amazon SQS includesstandard queueswith high throughput and at-least-once
    processing, andFIFO queuesthat provide FIFO (first-in, first-out) delivery and
    exactly-once processing. With Amazon SQS, you can offload the administrative burden
    of operating and scaling a highly available messaging cluster, while paying a
    low price for only what you use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-simple-queue-service/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SQ
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sqs/index.html
- type: x-console
  url: https://console.aws.amazon.com/sqs/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSSimpleQueueService/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/sqs/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=12
- type: x-getting-started
  url: https://aws.amazon.com/sqs/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/sqs/pricing/
- type: x-website
  url: https://aws.amazon.com/sqs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---