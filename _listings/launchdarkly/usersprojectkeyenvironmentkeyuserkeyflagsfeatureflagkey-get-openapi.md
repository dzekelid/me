---
swagger: "2.0"
x-collection-name: LaunchDarkly
x-complete: 0
info:
  title: Launch Darkly Get a user by key.
  description: Get a user by key..
  termsOfService: https://launchdarkly.com/terms
  contact:
    name: LaunchDarkly Support
    url: https://support.launchdarkly.com
    email: support@launchdarkly.com
  version: 2.0.0
host: app.launchdarkly.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /environments/{projectKey}:
    post:
      summary: Create an environment
      description: Create an environment.
      operationId: postEnvironment
      x-api-path-slug: environmentsprojectkey-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
  /environments/{projectKey}/{environmentKey}:
    delete:
      summary: Delete an environment by ID
      description: Delete an environment by id.
      operationId: deleteEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
    get:
      summary: Get an environment by key.
      description: Get an environment by key..
      operationId: getEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
    patch:
      summary: Modify an environment by ID
      description: Modify an environment by id.
      operationId: patchEnvironment
      x-api-path-slug: environmentsprojectkeyenvironmentkey-patch
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environments
      - Projects
      - Keys
      - EnvironmentKey
  /flag-statuses/{projectKey}/{environmentKey}:
    get:
      summary: Get a list of statuses for all feature flags
      description: Get a list of statuses for all feature flags.
      operationId: getFeatureFlagStatus
      x-api-path-slug: flagstatusesprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flag-statuses
      - Projects
      - Keys
      - EnvironmentKey
  /flag-statuses/{projectKey}/{environmentKey}/{featureFlagKey}:
    get:
      summary: Get a list of statuses for all feature flags
      description: Get a list of statuses for all feature flags.
      operationId: getFeatureFlagStatuses
      x-api-path-slug: flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Flag-statuses
      - Projects
      - Keys
      - EnvironmentKey
      - FeatureFlagKey
  /user-search/{projectKey}/{environmentKey}:
    get:
      summary: Search users in LaunchDarkly based on their last active date, or a
        search query.
      description: Search users in launchdarkly based on their last active date, or
        a search query..
      operationId: getSearchUsers
      x-api-path-slug: usersearchprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - User-search
      - Projects
      - Keys
      - EnvironmentKey
  /users/{projectKey}/{environmentKey}:
    get:
      summary: List all users in the environment.
      description: List all users in the environment..
      operationId: getUsers
      x-api-path-slug: usersprojectkeyenvironmentkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
  /users/{projectKey}/{environmentKey}/{userKey}:
    delete:
      summary: Delete a user by ID
      description: Delete a user by id.
      operationId: deleteUser
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkey-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
    get:
      summary: Get a user by key.
      description: Get a user by key..
      operationId: getUser
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
  /users/{projectKey}/{environmentKey}/{userKey}/flags:
    get:
      summary: Lists the current flag settings for a given user.
      description: Lists the current flag settings for a given user..
      operationId: getUserFlagSettings
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkeyflags-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
      - Flags
  /users/{projectKey}/{environmentKey}/{userKey}/flags/{featureFlagKey}:
    get:
      summary: Get a user by key.
      description: Get a user by key..
      operationId: getUserFlagSetting
      x-api-path-slug: usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
      - Projects
      - Keys
      - EnvironmentKey
      - UserKey
      - Flags
      - FeatureFlagKey
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