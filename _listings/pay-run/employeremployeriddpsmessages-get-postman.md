{
  "info": {
    "name": "Pay Run.IO Gets the DPS messages",
    "_postman_id": "3e548097-0163-428f-a479-70c5199a0786",
    "description": "Gets the DPS message links",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "DPMessages",
      "item": [
        {
          "id": "bc434bdc-5ccd-47c0-bf1c-598cc10c20c5",
          "name": "GetDpsMessagesFromEmployer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.test.payrun.io",
              "path": [
                "Employer/:EmployerId/DpsMessages"
              ],
              "variable": [
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
            "description": "Gets the DPS message links"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fcfe8fc-4e36-4f2a-a24f-06f128d49268"
            }
          ]
        }
      ]
    }
  ]
}