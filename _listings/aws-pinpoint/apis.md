---
name: AWS Pinpoint
x-slug: aws-pinpoint
description: Amazon Pinpoint makes it easy to run targeted campaigns to drive user
  engagement in mobile apps. Amazon Pinpoint helps you understand user behavior, define
  which users to target, determine which messages to send, schedule the best time
  to deliver the messages, and then track the results of your campaign.Targeted push
  notifications based on app usage trends and user behavior have become a popular
  approach for mobile app user engagement because response rates are often several
  times higher than tradition email marketing campaigns. By using targeted push notifications,
  you can increase message relevance and effectiveness, measure engagement, and continually
  improve your campaigns.Getting started with Amazon Pinpoint is easy. First, AWS
  Mobile Hub guides you through the process to integrate the AWS Mobile SDK with your
  app. Next, you define your target segments, campaign message, and specify the delivery
  schedule. Once your campaign is running, Pinpoint provides metrics so you can run
  analytics and track the impact of your campaign.With Amazon Pinpoint, there are
  no upfront setup costs, and no fixed monthly cost. You only pay for the number of
  users your campaign targets, the messages you send, and the events you collect,
  so you can start small and scale as your application grows.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Pinpoint API Segments List
  x-api-slug: aws-pinpoint-api
  description: Use the GET method to request information about your segments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegments-get-openapi.md
- name: AWS Pinpoint API Segments List
  x-api-slug: aws-pinpoint-api
  description: Use the POST method to create or update a segment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegments-post-openapi.md
- name: AWS Pinpoint API Segment Instance
  x-api-slug: aws-pinpoint-api
  description: Use the GET method to request information about a segment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments/segment-id
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegmentssegmentid-get-openapi.md
- name: AWS Pinpoint API Segment Instance
  x-api-slug: aws-pinpoint-api
  description: Use the PUT method to update a segment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments/segment-id
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegmentssegmentid-put-openapi.md
- name: AWS Pinpoint API Segment Instance
  x-api-slug: aws-pinpoint-api
  description: Use the DELETE method to delete a segment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments/segment-id
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegmentssegmentid-delete-openapi.md
- name: AWS Pinpoint API Segment Versions List
  x-api-slug: aws-pinpoint-api
  description: Use the GET method to request information about your segment versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segment/versions
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegmentversions-get-openapi.md
- name: AWS Pinpoint API Segment Version Instance
  x-api-slug: aws-pinpoint-api
  description: Use the GET method to request information about a segment version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: ://///apps/application-id/segments/segment-id/versions/version
  tags: Segments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/appsapplicationidsegmentssegmentidversionsversion-get-openapi.md
- name: AWS Pinpoint API
  x-api-slug: aws-pinpoint-api
  description: Amazon Pinpoint makes it easy to run targeted campaigns to drive user
    engagement in mobile apps. Amazon Pinpoint helps you understand user behavior,
    define which users to target, determine which messages to send, schedule the best
    time to deliver the messages, and then track the results of your campaign.Targeted
    push notifications based on app usage trends and user behavior have become a popular
    approach for mobile app user engagement because response rates are often several
    times higher than tradition email marketing campaigns. By using targeted push
    notifications, you can increase message relevance and effectiveness, measure engagement,
    and continually improve your campaigns.Getting started with Amazon Pinpoint is
    easy. First, AWS Mobile Hub guides you through the process to integrate the AWS
    Mobile SDK with your app. Next, you define your target segments, campaign message,
    and specify the delivery schedule. Once your campaign is running, Pinpoint provides
    metrics so you can run analytics and track the impact of your campaign.With Amazon
    Pinpoint, there are no upfront setup costs, and no fixed monthly cost. You only
    pay for the number of users your campaign targets, the messages you send, and
    the events you collect, so you can start small and scale as your application grows.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-pinpoint.jpg
  humanURL: https://aws.amazon.com/pinpoint/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-pinpoint/openapi.md
x-common:
- type: x-blog
  url: https://aws.amazon.com/blogs/aws/amazon-pinpoint-hit-your-targets-with-aws/
- type: x-documentation
  url: http://docs.aws.amazon.com/pinpoint/latest/apireference/welcome.html
- type: x-faq
  url: https://aws.amazon.com/pinpoint/faqs/
- type: x-pricing
  url: https://aws.amazon.com/pinpoint/pricing/
- type: x-website
  url: https://aws.amazon.com/pinpoint/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---