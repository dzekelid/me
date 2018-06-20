{
  "info": {
    "name": "Pay Run.IO Gets the DPS message",
    "_postman_id": "5d9b892b-c789-4923-8786-6ccf65b9fa57",
    "description": "Gets the DPS message",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "DPMessage",
      "item": [
        {
          "id": "dc1b8417-fe2c-40b0-b4bc-3eaf8a4999a1",
          "name": "GetDpsMessageFromEmployer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.test.payrun.io",
              "path": [
                "Employer/:EmployerId/DpsMessage/:DpsMessageId"
              ],
              "variable": [
                {
                  "id": "DpsMessageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "EmployerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the DPS message"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32a6cc76-7c27-4c5b-b416-d9828b9dd500"
            }
          ]
        },
        {
          "id": "2a4b32ff-d9bb-4213-8f43-7d745ee84b4a",
          "name": "DeleteDpsMessage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.test.payrun.io",
              "path": [
                "Employer/:EmployerId/DpsMessage/:DpsMessageId"
              ],
              "variable": [
                {
                  "id": "DpsMessageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "EmployerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the DPS message"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9eca3c10-af52-4dd2-b8ba-9a3f4d5d566a"
            }
          ]
        }
      ]
    }
  ]
}