---
name: Google Play
x-slug: google-play
description: 'The Google Play Developer API allows you to perform a number of publishing
  and app-management tasks. It includes two components: The Subscriptions and In-App
  Purchases API lets you manage in-app purchases and subscriptions. The Publishing
  API lets you upload and publish apps, and perform other publishing-related tasks.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/apis.md
specificationVersion: "0.14"
apis:
- name: Google Play Get Entitlements
  x-api-slug: google-play
  description: Lists the user's current inapp item or subscription entitlements
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///{packageName}/entitlements
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/packagenameentitlements-get-openapi.md
- name: Google Play Get Entitlements
  x-api-slug: google-play
  description: Lists all entitlements for the specified user. Only the ID is set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/users/{userId}/entitlements
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/enterprisesenterpriseidusersuseridentitlements-get-openapi.md
- name: Google Play Remove Entitlement
  x-api-slug: google-play
  description: Removes an entitlement to an app for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/enterprisesenterpriseidusersuseridentitlementsentitlementid-delete-openapi.md
- name: Google Play Get Entitlement
  x-api-slug: google-play
  description: Retrieves details of an entitlement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/enterprisesenterpriseidusersuseridentitlementsentitlementid-get-openapi.md
- name: Google Play Update Entitlement
  x-api-slug: google-play
  description: Adds or updates an entitlement to an app for a user. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/enterprisesenterpriseidusersuseridentitlementsentitlementid-patch-openapi.md
- name: Google Play Update Entitlement
  x-api-slug: google-play
  description: Adds or updates an entitlement to an app for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}
  tags: Entitlement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/enterprisesenterpriseidusersuseridentitlementsentitlementid-put-openapi.md
- name: Google Play Get Achievements
  x-api-slug: google-play
  description: Lists all the achievement definitions for your application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievements-get-openapi.md
- name: Google Play Update Multiple Achievements
  x-api-slug: google-play
  description: Updates multiple achievements for the currently authenticated player.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements/updateMultiple
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievementsupdatemultiple-post-openapi.md
- name: Google Play Increment Step Of Achievement
  x-api-slug: google-play
  description: Increments the steps of the achievement with the given ID for the currently
    authenticated player.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements/{achievementId}/increment
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievementsachievementidincrement-post-openapi.md
- name: Google Play Set State of Achievement
  x-api-slug: google-play
  description: Sets the state of the achievement with the given ID to REVEALED for
    the currently authenticated player.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements/{achievementId}/reveal
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievementsachievementidreveal-post-openapi.md
- name: Google Play Set Steps for Achievements
  x-api-slug: google-play
  description: Sets the steps for the currently authenticated player towards unlocking
    an achievement. If the steps parameter is less than the current number of steps
    that the player already gained for the achievement, the achievement is not modified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements/{achievementId}/setStepsAtLeast
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievementsachievementidsetstepsatleast-post-openapi.md
- name: Google Play Unlock Achievement
  x-api-slug: google-play
  description: Unlocks this achievement for the currently authenticated player.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///achievements/{achievementId}/unlock
  tags: Achievement
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/achievementsachievementidunlock-post-openapi.md
- name: Google Play Get Metagame Confirmation
  x-api-slug: google-play
  description: Return the metagame configuration data for the calling application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///metagameConfig
  tags: Game
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/metagameconfig-get-openapi.md
- name: Google Play
  x-api-slug: google-play
  description: 'The Google Play Developer API allows you to perform a number of publishing
    and app-management tasks. It includes two components: The Subscriptions and In-App
    Purchases API lets you manage in-app purchases and subscriptions. The Publishing
    API lets you upload and publish apps, and perform other publishing-related tasks.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-play/openapi.md
x-common:
- type: x-blog
  url: https://blog.google/products/google-play/
- type: x-blog-rss
  url: https://blog.google/products/google-play/rss
- type: x-developer
  url: https://developers.google.com/android-publisher/
- type: x-facebook
  url: https://www.facebook.com/GooglePlay
- type: x-getting-started
  url: https://developers.google.com/android-publisher/getting_started
- type: x-twitter
  url: https://twitter.com/GooglePlay
- type: x-website
  url: https://play.google.com/store
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---