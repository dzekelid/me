---
name: Google Analytics
x-slug: google-analytics
description: Google Analytics gives you the digital analytics tools you need to analyze
  data from all touchpoints in one place, for a deeper understanding of the customer
  experience. You can then share the insights that matter with your whole organization.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: Google Analytics Return Real Time Data
  x-api-slug: google-analytics
  description: Returns real time data for a view (profile).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//data/realtime
  tags: Real Time Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/datarealtime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/datarealtime-get-openapi.md
- name: Google Analytics Get Custom Dimensions
  x-api-slug: google-analytics
  description: Lists custom dimensions to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions
  tags: Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdimensions-get-openapi.md
- name: Google Analytics Create Custom Dimension
  x-api-slug: google-analytics
  description: Create a new custom dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions
  tags: Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdimensions-post-openapi.md
- name: Google Analytics Get Custom Dimension
  x-api-slug: google-analytics
  description: Get a custom dimension to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions/{customDimensionId}
  tags: Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-get-openapi.md
- name: Google Analytics Update Custom Dimensions
  x-api-slug: google-analytics
  description: Updates an existing custom dimension. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions/{customDimensionId}
  tags: Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-patch-openapi.md
- name: Google Analytics Update Custom Dimensions
  x-api-slug: google-analytics
  description: Updates an existing custom dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customDimensions/{customDimensionId}
  tags: Dimension
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustomdimensionscustomdimensionid-put-openapi.md
- name: Google Analytics Get Custom Metrics
  x-api-slug: google-analytics
  description: Lists custom metrics to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustommetrics-get-openapi.md
- name: Google Analytics Create Custom Metric
  x-api-slug: google-analytics
  description: Create a new custom metric.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustommetrics-post-openapi.md
- name: Google Analytics Get Custom Metric
  x-api-slug: google-analytics
  description: Get a custom metric to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics/{customMetricId}
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-get-openapi.md
- name: Google Analytics Update Custom Metric
  x-api-slug: google-analytics
  description: Updates an existing custom metric. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics/{customMetricId}
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-patch-openapi.md
- name: Google Analytics Update Custom Metric
  x-api-slug: google-analytics
  description: Updates an existing custom metric.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/customMetrics/{customMetricId}
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidcustommetricscustommetricid-put-openapi.md
- name: Google Analytics List Experiments
  x-api-slug: google-analytics
  description: Lists experiments to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperiments-get-openapi.md
- name: Google Analytics Create Experiment
  x-api-slug: google-analytics
  description: Create a new experiment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperiments-post-openapi.md
- name: Google Analytics Delete Experiment
  x-api-slug: google-analytics
  description: Delete an experiment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments/{experimentId}
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-delete-openapi.md
- name: Google Analytics Get Experiment
  x-api-slug: google-analytics
  description: Returns an experiment to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments/{experimentId}
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-get-openapi.md
- name: Google Analytics Update Experiment
  x-api-slug: google-analytics
  description: Update an existing experiment. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments/{experimentId}
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-patch-openapi.md
- name: Google Analytics Update Experiment
  x-api-slug: google-analytics
  description: Update an existing experiment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/accounts/{accountId}/webproperties/{webPropertyId}/profiles/{profileId}/experiments/{experimentId}
  tags: Experiment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementaccountsaccountidwebpropertieswebpropertyidprofilesprofileidexperimentsexperimentid-put-openapi.md
- name: Google Analytics Get Segments
  x-api-slug: google-analytics
  description: Lists segments to which the user has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3//management/segments
  tags: Segment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/managementsegments-get-openapi.md
- name: Google Analytics
  x-api-slug: google-analytics
  description: Google Analytics gives you the digital analytics tools you need to
    analyze data from all touchpoints in one place, for a deeper understanding of
    the customer experience. You can then share the insights that matter with your
    whole organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/logo_lockup_analytics_icon_vertical_black_2x.png
  humanURL: https://www.google.com/analytics/#?modal_active=none
  baseURL: https://www.googleapis.com//analytics/v3
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-analytics/openapi.md
x-common:
- type: x-blog
  url: https://analytics.googleblog.com/
- type: x-blog-rss
  url: https://analytics.googleblog.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/analytics/
- type: x-github
  url: https://github.com/googleanalytics/
- type: x-google-plus
  url: https://plus.google.com/+GoogleAnalytics
- type: x-partners
  url: https://developers.google.com/analytics/program/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/google-analytics
- type: x-support
  url: https://developers.google.com/analytics/help/
- type: x-twitter
  url: https://twitter.com/googleanalytics
- type: x-videos
  url: https://www.youtube.com/user/googleanalytics
- type: x-website
  url: https://www.google.com/analytics/#?modal_active=none
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---