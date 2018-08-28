---
name: Google Tasks
x-slug: google-tasks
description: The Google Tasks API lets you search, read, and update Google Tasks content
  and metadata. This document describes how to use a RESTful calling style and client
  libraries for various programming languages (currently Java, Python, and PHP) to
  access and edit Google Tasks data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-tasks/apis.md
specificationVersion: "0.14"
apis:
- name: Tasks - Get Users @me Lists
  x-api-slug: usersmelists-get
  description: Returns all the authenticated user's task lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
  humanURL: https://developers.google.com/google-apps/tasks/
  baseURL: ://www.googleapis.com//tasks/v1
  tags: Google APIs, Tasks, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-tasks/usersmelists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-tasks/usersmelists-get-openapi.md
- name: Tasks - Add Users @me Lists
  x-api-slug: usersmelists-post
  description: Creates a new task list and adds it to the authenticated user's task
    lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-tasks-icon.png
  humanURL: https://developers.google.com/google-apps/tasks/
  baseURL: ://www.googleapis.com//tasks/v1
  tags: Google APIs, Tasks, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-tasks/usersmelists-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.task.queue.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.tasks.stack.network
- type: x-code
  url: https://developers.google.com/google-apps/tasks/setup
- type: x-concepts
  url: https://developers.google.com/google-apps/tasks/concepts
- type: x-documentation
  url: https://developers.google.com/google-apps/tasks/v1/reference/
- type: x-website
  url: https://developers.google.com/google-apps/tasks/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---