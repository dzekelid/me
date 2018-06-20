---
swagger: "2.0"
x-collection-name: VictorOps
x-complete: 0
info:
  title: Victor Ops Remove a team member
  description: |-
    Remove a team from your organization.

    This API may be called a maximum of 15 times per minute.
  version: 0.0.2
host: api.victorops.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api-public/v1/policies/types/timeouts:
    get:
      summary: Get the available timeout values
      description: |-
        Get the available timeout values

        description: "If still unacked after 1 minute", type: 1
        description: "If still unacked after 5 minutes", type: 5
        description: "If still unacked after 10 minutes", type: 10
        description: "If still unacked after 15 minutes", type: 15
        description: "If still unacked after 20 minutes", type: 20
        description: "If still unacked after 25 minutes", type: 25
        description: "If still unacked after 30 minutes", type: 30
        description: "If still unacked after 45 minutes", type: 45
        description: "If still unacked after 60 minutes", type: 60

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.policies.types.timeouts.get
      x-api-path-slug: apipublicv1policiestypestimeouts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Policies
      - Types
      - Timeouts
  /api-public/v1/profile/{username}/policies:
    get:
      summary: Get the user's paging policy
      description: |-
        Get all the paging policy steps for the user on the org associated with the API key

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.get
      x-api-path-slug: apipublicv1profileusernamepolicies-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
    post:
      summary: Create a paging policy step
      description: |-
        Create a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.post
      x-api-path-slug: apipublicv1profileusernamepolicies-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
  /api-public/v1/profile/{username}/policies/{step}:
    get:
      summary: Get a paging policy step
      description: |-
        Get a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.get
      x-api-path-slug: apipublicv1profileusernamepoliciesstep-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
    post:
      summary: Create a rule for a paging policy step
      description: |-
        Create a rule for a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.post
      x-api-path-slug: apipublicv1profileusernamepoliciesstep-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
    put:
      summary: Update a paging policy step
      description: |-
        Update a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.put
      x-api-path-slug: apipublicv1profileusernamepoliciesstep-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
  /api-public/v1/profile/{username}/policies/{step}/{rule}:
    delete:
      summary: Delete a rule from a paging policy step
      description: |-
        Delete a rule from a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.rule.delete
      x-api-path-slug: apipublicv1profileusernamepoliciessteprule-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
      - Rule
    get:
      summary: Get a rule from a paging policy step
      description: |-
        Get a rule from a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.rule.get
      x-api-path-slug: apipublicv1profileusernamepoliciessteprule-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
      - Rule
    put:
      summary: Update a rule for a paging policy step
      description: |-
        Update a rule for a paging policy step

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.profile.username.policies.step.rule.put
      x-api-path-slug: apipublicv1profileusernamepoliciessteprule-put
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Username
      - Policies
      - Step
      - Rule
  /api-public/v1/team/{team}/members:
    get:
      summary: Retrieve a list of members for a team
      description: |-
        Get the members for the specified team.

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.team.team.members.get
      x-api-path-slug: apipublicv1teamteammembers-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: team
        description: The VictorOps team to fetch
      responses:
        200:
          description: OK
      tags:
      - Team
      - Team
      - Members
    post:
      summary: Add a team member
      description: |-
        Add a team member to your team.

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.team.team.members.post
      x-api-path-slug: apipublicv1teamteammembers-post
      parameters:
      - in: query
        name: No Name
      - in: path
        name: team
        description: The VictorOps team to fetch
      responses:
        200:
          description: OK
      tags:
      - Team
      - Team
      - Members
  /api-public/v1/team/{team}/members/{user}:
    delete:
      summary: Remove a team member
      description: |-
        Remove a team from your organization.

        This API may be called a maximum of 15 times per minute.
      operationId: api_public.v1.team.team.members.user.delete
      x-api-path-slug: apipublicv1teamteammembersuser-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: team
        description: The VictorOps team to be deleted
      - in: path
        name: user
        description: The team member username
      responses:
        200:
          description: OK
      tags:
      - Team
      - Team
      - Members
      - User
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