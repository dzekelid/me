---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{packageName}/entitlements:
    get:
      summary: Get Entitlements
      description: Lists the user's current inapp item or subscription entitlements
      operationId: androidpublisher.entitlements.list
      x-api-path-slug: packagenameentitlements-get
      parameters:
      - in: query
        name: maxResults
      - in: path
        name: packageName
        description: The package name of the application the inapp product was sold
          in (for example, com
      - in: query
        name: productId
        description: The product id of the inapp product (for example, sku1)
      - in: query
        name: startIndex
      - in: query
        name: token
      responses:
        200:
          description: OK
      tags:
      - Entitlement
  /enterprises/{enterpriseId}/users/{userId}/entitlements:
    get:
      summary: Get Entitlements
      description: Lists all entitlements for the specified user. Only the ID is set.
      operationId: androidenterprise.entitlements.list
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlements-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
  /enterprises/{enterpriseId}/users/{userId}/entitlements/{entitlementId}:
    delete:
      summary: Remove Entitlement
      description: Removes an entitlement to an app for a user.
      operationId: androidenterprise.entitlements.delete
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-delete
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    get:
      summary: Get Entitlement
      description: Retrieves details of an entitlement.
      operationId: androidenterprise.entitlements.get
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    patch:
      summary: Update Entitlement
      description: Adds or updates an entitlement to an app for a user. This method
        supports patch semantics.
      operationId: androidenterprise.entitlements.patch
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: query
        name: install
        description: Set to true to also install the product on all the users devices
          where possible
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
    put:
      summary: Update Entitlement
      description: Adds or updates an entitlement to an app for a user.
      operationId: androidenterprise.entitlements.update
      x-api-path-slug: enterprisesenterpriseidusersuseridentitlementsentitlementid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: entitlementId
        description: The ID of the entitlement (a product ID), e
      - in: query
        name: install
        description: Set to true to also install the product on all the users devices
          where possible
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Entitlement
  /achievements:
    get:
      summary: Get Achievements
      description: Lists all the achievement definitions for your application.
      operationId: games.achievementDefinitions.list
      x-api-path-slug: achievements-get
      parameters:
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: language
        description: The preferred language to use for strings returned by this method
      - in: query
        name: maxResults
        description: The maximum number of achievement resources to return in the
          response, used for paging
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/updateMultiple:
    post:
      summary: Update Multiple Achievements
      description: Updates multiple achievements for the currently authenticated player.
      operationId: games.achievements.updateMultiple
      x-api-path-slug: achievementsupdatemultiple-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/{achievementId}/increment:
    post:
      summary: Increment Step Of Achievement
      description: Increments the steps of the achievement with the given ID for the
        currently authenticated player.
      operationId: games.achievements.increment
      x-api-path-slug: achievementsachievementidincrement-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: requestId
        description: A randomly generated numeric ID for each request specified by
          the caller
      - in: query
        name: stepsToIncrement
        description: The number of steps to increment
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/{achievementId}/reveal:
    post:
      summary: Set State of Achievement
      description: Sets the state of the achievement with the given ID to REVEALED
        for the currently authenticated player.
      operationId: games.achievements.reveal
      x-api-path-slug: achievementsachievementidreveal-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/{achievementId}/setStepsAtLeast:
    post:
      summary: Set Steps for Achievements
      description: Sets the steps for the currently authenticated player towards unlocking
        an achievement. If the steps parameter is less than the current number of
        steps that the player already gained for the achievement, the achievement
        is not modified.
      operationId: games.achievements.setStepsAtLeast
      x-api-path-slug: achievementsachievementidsetstepsatleast-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      - in: query
        name: steps
        description: The minimum value to set the steps to
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /achievements/{achievementId}/unlock:
    post:
      summary: Unlock Achievement
      description: Unlocks this achievement for the currently authenticated player.
      operationId: games.achievements.unlock
      x-api-path-slug: achievementsachievementidunlock-post
      parameters:
      - in: path
        name: achievementId
        description: The ID of the achievement used by this method
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      responses:
        200:
          description: OK
      tags:
      - Achievement
  /metagameConfig:
    get:
      summary: Get Metagame Confirmation
      description: Return the metagame configuration data for the calling application.
      operationId: games.metagame.getMetagameConfig
      x-api-path-slug: metagameconfig-get
      parameters:
      - in: query
        name: consistencyToken
        description: The last-seen mutation timestamp
      responses:
        200:
          description: OK
      tags:
      - Game
---