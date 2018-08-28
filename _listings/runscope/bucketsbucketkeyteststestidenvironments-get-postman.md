{
  "info": {
    "name": "Runscope Get Buckets Tests Environments",
    "_postman_id": "ad66e0aa-5032-4173-9424-bde23ad40cce",
    "description": "Return details of the test's environments (only those that belong to the specified test)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "buckets",
      "item": [
        {
          "id": "e2f94521-e819-4e35-a067-9aceb9cfe733",
          "name": "buckets.bucketKey.tests.testId.environments.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.runscope.com",
              "path": [
                "buckets/:bucketKey/tests/:testId/environments"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "bucketKey",
                  "value": "bucketKey",
                  "type": "string"
                },
                {
                  "id": "testId",
                  "value": "testId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return details of the test's environments (only those that belong to the specified test)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79e3009b-6b9b-4f7a-9356-bb3492855af0"
            }
          ]
        }
      ]
    }
  ]
}