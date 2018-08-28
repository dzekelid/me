---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 0
info:
  title: Google Analytics Get Experiment
  description: Returns an experiment to which the user has access.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /analytics/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /data/realtime:
    get:
      summary: Return Real Time Data
      description: Returns real time data for a view (profile).
      operationId: analytics.data.realtime.get
      x-api-path-slug: datarealtime-get
      parameters:
      - in: query
        name: dimensions
        description: A comma-separated list of real time dimensions
      - in: query
        name: filters
        description: A comma-separated list of dimension or metric filters to be applied
          to real time data
      - in: query
        name: ids
        description: Unique table ID for retrieving real time data
      - in: query
        name: max-results
        description: The maximum number of entries to include in this feed
      - in: query
        name: metrics
        description: A comma-separated list of real time metrics
      - in: query
        name: sort
        description: A comma-separated list of dimensions or metrics that determine
          the sort order for real time data
      responses:
        200:
          description: OK
      tags:
      - Real Time Data
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions:
    get:
      summary: Get Custom Dimensions
      description: Lists custom dimensions to which the user has access.
      operationId: analytics.management.customDimensions.list
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdimensions-get
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom dimensions to retrieve
      - in: query
        name: max-results
        description: The maximum number of custom dimensions to include in this response
      - in: query
        name: start-index
        description: An index of the first entity to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimensions to retrieve
      responses:
        200:
          description: OK
      tags:
      - Dimension
    post:
      summary: Create Custom Dimension
      description: Create a new custom dimension.
      operationId: analytics.management.customDimensions.insert
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdimensions-post
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom dimension to create
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimension to create
      responses:
        200:
          description: OK
      tags:
      - Dimension
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions/{customDimensionId}:
    get:
      summary: Get Custom Dimension
      description: Get a custom dimension to which the user has access.
      operationId: analytics.management.customDimensions.get
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-get
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom dimension to retrieve
      - in: path
        name: customDimensionId
        description: The ID of the custom dimension to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimension to retrieve
      responses:
        200:
          description: OK
      tags:
      - Dimension
    patch:
      summary: Update Custom Dimensions
      description: Updates an existing custom dimension. This method supports patch
        semantics.
      operationId: analytics.management.customDimensions.patch
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-patch
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom dimension to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customDimensionId
        description: Custom dimension ID for the custom dimension to update
      - in: query
        name: ignoreCustomDataSourceLinks
        description: Force the update and ignore any warnings related to the custom
          dimension being linked to a custom data source / data set
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimension to update
      responses:
        200:
          description: OK
      tags:
      - Dimension
    put:
      summary: Update Custom Dimensions
      description: Updates an existing custom dimension.
      operationId: analytics.management.customDimensions.update
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-put
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom dimension to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customDimensionId
        description: Custom dimension ID for the custom dimension to update
      - in: query
        name: ignoreCustomDataSourceLinks
        description: Force the update and ignore any warnings related to the custom
          dimension being linked to a custom data source / data set
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimension to update
      responses:
        200:
          description: OK
      tags:
      - Dimension
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics:
    get:
      summary: Get Custom Metrics
      description: Lists custom metrics to which the user has access.
      operationId: analytics.management.customMetrics.list
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustommetrics-get
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom metrics to retrieve
      - in: query
        name: max-results
        description: The maximum number of custom metrics to include in this response
      - in: query
        name: start-index
        description: An index of the first entity to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID for the custom metrics to retrieve
      responses:
        200:
          description: OK
      tags:
      - Metric
    post:
      summary: Create Custom Metric
      description: Create a new custom metric.
      operationId: analytics.management.customMetrics.insert
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustommetrics-post
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom metric to create
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: webPropertyId
        description: Web property ID for the custom dimension to create
      responses:
        200:
          description: OK
      tags:
      - Metric
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics/{customMetricId}:
    get:
      summary: Get Custom Metric
      description: Get a custom metric to which the user has access.
      operationId: analytics.management.customMetrics.get
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-get
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom metric to retrieve
      - in: path
        name: customMetricId
        description: The ID of the custom metric to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID for the custom metric to retrieve
      responses:
        200:
          description: OK
      tags:
      - Metric
    patch:
      summary: Update Custom Metric
      description: Updates an existing custom metric. This method supports patch semantics.
      operationId: analytics.management.customMetrics.patch
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-patch
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom metric to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customMetricId
        description: Custom metric ID for the custom metric to update
      - in: query
        name: ignoreCustomDataSourceLinks
        description: Force the update and ignore any warnings related to the custom
          metric being linked to a custom data source / data set
      - in: path
        name: webPropertyId
        description: Web property ID for the custom metric to update
      responses:
        200:
          description: OK
      tags:
      - Metric
    put:
      summary: Update Custom Metric
      description: Updates an existing custom metric.
      operationId: analytics.management.customMetrics.update
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-put
      parameters:
      - in: path
        name: accountId
        description: Account ID for the custom metric to update
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customMetricId
        description: Custom metric ID for the custom metric to update
      - in: query
        name: ignoreCustomDataSourceLinks
        description: Force the update and ignore any warnings related to the custom
          metric being linked to a custom data source / data set
      - in: path
        name: webPropertyId
        description: Web property ID for the custom metric to update
      responses:
        200:
          description: OK
      tags:
      - Metric
  /management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments:
    get:
      summary: List Experiments
      description: Lists experiments to which the user has access.
      operationId: analytics.management.experiments.list
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperiments-get
      parameters:
      - in: path
        name: accountId
        description: Account ID to retrieve experiments for
      - in: query
        name: max-results
        description: The maximum number of experiments to include in this response
      - in: path
        name: profileId
        description: View (Profile) ID to retrieve experiments for
      - in: query
        name: start-index
        description: An index of the first experiment to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID to retrieve experiments for
      responses:
        200:
          description: OK
      tags:
      - Experiment
    post:
      summary: Create Experiment
      description: Create a new experiment.
      operationId: analytics.management.experiments.insert
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperiments-post
      parameters:
      - in: path
        name: accountId
        description: Account ID to create the experiment for
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: View (Profile) ID to create the experiment for
      - in: path
        name: webPropertyId
        description: Web property ID to create the experiment for
      responses:
        200:
          description: OK
      tags:
      - Experiment
  /management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments/{experimentId}:
    delete:
      summary: Delete Experiment
      description: Delete an experiment.
      operationId: analytics.management.experiments.delete
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-delete
      parameters:
      - in: path
        name: accountId
        description: Account ID to which the experiment belongs
      - in: path
        name: experimentId
        description: ID of the experiment to delete
      - in: path
        name: profileId
        description: View (Profile) ID to which the experiment belongs
      - in: path
        name: webPropertyId
        description: Web property ID to which the experiment belongs
      responses:
        200:
          description: OK
      tags:
      - Experiment
    get:
      summary: Get Experiment
      description: Returns an experiment to which the user has access.
      operationId: analytics.management.experiments.get
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-get
      parameters:
      - in: path
        name: accountId
        description: Account ID to retrieve the experiment for
      - in: path
        name: experimentId
        description: Experiment ID to retrieve the experiment for
      - in: path
        name: profileId
        description: View (Profile) ID to retrieve the experiment for
      - in: path
        name: webPropertyId
        description: Web property ID to retrieve the experiment for
      responses:
        200:
          description: OK
      tags:
      - Experiment
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