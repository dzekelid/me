{
  "info": {
    "name": "Mailjet Messages API Message History",
    "_postman_id": "878c2fce-17a9-4a18-af1d-b559cede683e",
    "description": "Get the history of a message.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "55846962-4e97-4f7a-be0a-b752333a06c3",
          "name": "getMessage",
          "request": {
            "url": "http://api.mailjet.com/v3/REST/message/?Campaign=%7B%7D&Contact=%7B%7D&MessageState=%7B%7D&PlanSubscription=%7B%7D&Sender=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to list messages."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36dbfc66-da7d-426e-9c5e-25b036cb04d1"
            }
          ]
        },
        {
          "id": "8273cea6-3ef9-4b19-99ec-14a0615f360a",
          "name": "getMessagehistory",
          "request": {
            "url": "http://api.mailjet.com/v3/REST/messagehistory/?Message=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List message history resources"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1716c30-6ce6-4a9f-b21d-7e6c8495e8c7"
            }
          ]
        },
        {
          "id": "2c00fd37-3e09-4ec2-b316-b28daba90413",
          "name": "getMessagehistory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.mailjet.com",
              "path": [
                "v3",
                "REST",
                "messagehistory/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the history of a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb4d5ab4-406b-43c8-8827-685300f3ec6a"
            }
          ]
        }
      ]
    }
  ]
}