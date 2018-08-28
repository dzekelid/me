{
  "info": {
    "name": "Pay Run.IO Deletes the DPS message",
    "_postman_id": "b44a5992-a073-4edc-b362-e637548d18f4",
    "description": "Deletes the DPS message",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "DPMessage",
      "item": [
        {
          "id": "902a2b80-ed5d-4d0b-b967-e9839db38363",
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
              "id": "355df4e2-7f24-481e-bf71-0056088e7cda"
            }
          ]
        }
      ]
    }
  ]
}