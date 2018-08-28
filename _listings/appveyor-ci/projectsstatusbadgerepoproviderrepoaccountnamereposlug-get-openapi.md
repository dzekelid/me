---
swagger: "2.0"
x-collection-name: AppVeyor CI
x-complete: 0
info:
  title: App Veyor Get Projects Status Badgerepoprover Repoaccountname Reposlug
  description: Get projects status badgerepoprover repoaccountname reposlug.
  termsOfService: https://www.appveyor.com/terms-of-service/
  contact:
    name: AppVeyor Team
    url: https://www.appveyor.com/about/
    email: team@appveyor.com
  version: 0.20170106.0
host: ci.appveyor.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /builds/{accountName}/{projectSlug}/{buildVersion}:
    delete:
      summary: Delete Builds Accountname Projectslug Buildversion
      description: Delete builds accountname projectslug buildversion.
      operationId: deleteBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-delete
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion
    parameters:
      summary: Parameters Builds Accountname Projectslug Buildversion
      description: Parameters builds accountname projectslug buildversion.
      operationId: parametersBuildsAccountnameProjectslugBuildversion
      x-api-path-slug: buildsaccountnameprojectslugbuildversion-parameters
      responses:
        200:
          description: OK
      tags:
      - Builds
      - AccountName
      - ProjectSlug
      - BuildVersion
  /deployments:
    post:
      summary: Post Deployments
      description: Post deployments.
      operationId: postDeployments
      x-api-path-slug: deployments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Deployments
  /deployments/stop:
    delete:
      summary: Delete Deployments Stop
      description: Delete deployments stop.
      operationId: deleteDeploymentsStop
      x-api-path-slug: deploymentsstop-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - Stop
  /deployments/{deploymentId}:
    get:
      summary: Get Deployments Deploymentid
      description: Get deployments deploymentid.
      operationId: getDeploymentsDeployment
      x-api-path-slug: deploymentsdeploymentid-get
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - DeploymentId
    parameters:
      summary: Parameters Deployments Deploymentid
      description: Parameters deployments deploymentid.
      operationId: parametersDeploymentsDeployment
      x-api-path-slug: deploymentsdeploymentid-parameters
      responses:
        200:
          description: OK
      tags:
      - Deployments
      - DeploymentId
  /environments:
    get:
      summary: Get Environments
      description: Get environments.
      operationId: getEnvironments
      x-api-path-slug: environments-get
      responses:
        200:
          description: OK
      tags:
      - Environments
    post:
      summary: Post Environments
      description: Post environments.
      operationId: postEnvironments
      x-api-path-slug: environments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
    put:
      summary: Put Environments
      description: Put environments.
      operationId: putEnvironments
      x-api-path-slug: environments-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Environments
  /environments/{deploymentEnvironmentId}:
    delete:
      summary: Delete Environments Deploymentenvironmentid
      description: Delete environments deploymentenvironmentid.
      operationId: deleteEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-delete
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
    parameters:
      summary: Parameters Environments Deploymentenvironmentid
      description: Parameters environments deploymentenvironmentid.
      operationId: parametersEnvironmentsDeploymentenvironment
      x-api-path-slug: environmentsdeploymentenvironmentid-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
  /environments/{deploymentEnvironmentId}/deployments:
    get:
      summary: Get Environments Deploymentenvironmentid Deployments
      description: Get environments deploymentenvironmentid deployments.
      operationId: getEnvironmentsDeploymentenvironmentDeployments
      x-api-path-slug: environmentsdeploymentenvironmentiddeployments-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Deployments
    parameters:
      summary: Parameters Environments Deploymentenvironmentid Deployments
      description: Parameters environments deploymentenvironmentid deployments.
      operationId: parametersEnvironmentsDeploymentenvironmentDeployments
      x-api-path-slug: environmentsdeploymentenvironmentiddeployments-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Deployments
  /environments/{deploymentEnvironmentId}/settings:
    get:
      summary: Get Environments Deploymentenvironmentid Settings
      description: Get environments deploymentenvironmentid settings.
      operationId: getEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-get
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
    parameters:
      summary: Parameters Environments Deploymentenvironmentid Settings
      description: Parameters environments deploymentenvironmentid settings.
      operationId: parametersEnvironmentsDeploymentenvironmentSettings
      x-api-path-slug: environmentsdeploymentenvironmentidsettings-parameters
      responses:
        200:
          description: OK
      tags:
      - Environments
      - DeploymentEnvironmentId
      - Settings
  /projects/status/{badgeRepoProvider}/{repoAccountName}/{repoSlug}:
    get:
      summary: Get Projects Status Badgerepoprover Repoaccountname Reposlug
      description: Get projects status badgerepoprover repoaccountname reposlug.
      operationId: getProjectsStatusBadgerepoproverRepoaccountnameReposlug
      x-api-path-slug: projectsstatusbadgerepoproviderrepoaccountnamereposlug-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Status
      - BadgeRepoProvider
      - RepoAccountName
      - RepoSlug
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