{
  "info": {
    "name": "Mailjet Messages API Message History",
    "_postman_id": "5e925879-07bc-4c28-96b7-30d96155056a",
    "description": "List message history resources",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "1607063f-0237-4203-b55c-921df51d4a57",
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
              "id": "58950215-8a5c-4f26-8a74-943f54dac5c7"
            }
          ]
        },
        {
          "id": "4321ee64-114a-4c25-9418-686a29e9b8b8",
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
              "id": "16b6f060-17a1-4dbc-9da2-61a95fc95e80"
            }
          ]
        }
      ]
    }
  ]
}