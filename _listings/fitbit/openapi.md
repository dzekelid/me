---
swagger: "2.0"
x-collection-name: Fitbit
x-complete: 1
info:
  title: Fitbit
  description: bring-fitbit-health-data-into-your-apps-including-user-activities-sleep-heart-glucose-and-blood-pressure-information-
  version: 1.0.0
host: api.fitbit.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/-/meals.json:
    get:
      summary: Get User Meals.json
      description: Get a list of meals user created in his food log in the format
        requested.
      operationId: getUserMeals.json
      x-api-path-slug: usermeals-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Meals.json
---