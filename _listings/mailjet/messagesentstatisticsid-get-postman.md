{
  "info": {
    "name": "Mailjet Messages API Message Statistics",
    "_postman_id": "ff82571f-724c-488e-b8da-4c9051eddfb0",
    "description": "List message statistics.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "dbb5f8b4-b2c5-4428-b96e-58b77795b010",
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
              "id": "8a5f3bf4-dfd3-4ed2-8a48-407755fdaa01"
            }
          ]
        },
        {
          "id": "aeb304af-32c8-48d0-b928-49d526391cfe",
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
              "id": "f3c493b2-9099-45c5-b018-b8d05c31fe37"
            }
          ]
        },
        {
          "id": "ff00bfba-7f7d-4ee8-bb20-ba59a056eda5",
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
              "id": "d03537d6-cd42-4957-8bfa-8ce09859f6f3"
            }
          ]
        },
        {
          "id": "6a602893-21d8-45d5-9c84-3d534316dc6e",
          "name": "getMessageinformation",
          "request": {
            "url": "http://api.mailjet.com/v3/REST/messageinformation/?CampaignID=%7B%7D&CampaignStatus=%7B%7D&ContactsList=%7B%7D&CustomCampaign=%7B%7D&From=%7B%7D&FromDomain=%7B%7D&FromID=%7B%7D&FromTS=%7B%7D&FromType=%7B%7D&IsDeleted=%7B%7D&IsNewsletterTool=%7B%7D&IsStarred=%7B%7D&MessageStatus=%7B%7D&Period=%7B%7D&ToTS=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the information about a message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f491e07-d4b7-4786-833f-68098e94adfd"
            }
          ]
        },
        {
          "id": "3a8f6ab3-f9f7-4ddb-a9c1-ab13c099ba4f",
          "name": "getMessageinformation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.mailjet.com",
              "path": [
                "v3",
                "REST",
                "messageinformation/:id"
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
            "description": "Lists a message informaiton."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5963029c-dce4-4392-a252-69432ddcbd46"
            }
          ]
        },
        {
          "id": "b92e4909-eca5-4c51-a0a8-8d4c839a4f53",
          "name": "getMessagesentstatistics",
          "request": {
            "url": "http://api.mailjet.com/v3/REST/messagesentstatistics/?AllMessages=%7B%7D&CampaignID=%7B%7D&CampaignStatus=%7B%7D&Contact=%7B%7D&ContactsList=%7B%7D&CustomCampaign=%7B%7D&From=%7B%7D&FromDomain=%7B%7D&FromID=%7B%7D&FromTS=%7B%7D&FromType=%7B%7D&IsDeleted=%7B%7D&IsNewsletterTool=%7B%7D&IsStarred=%7B%7D&MessageStatus=%7B%7D&Period=%7B%7D&ShowExtraData=%7B%7D&ToTS=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the message statistics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50238f0c-d781-4cce-bd9d-7457d76fc60a"
            }
          ]
        },
        {
          "id": "4ab23cd2-e6fe-4ac3-8c27-346da140e2c8",
          "name": "getMessagesentstatistics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.mailjet.com",
              "path": [
                "v3",
                "REST",
                "messagesentstatistics/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List message statistics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75045b79-1335-4b2e-b3f6-df8584e6558e"
            }
          ]
        }
      ]
    }
  ]
}