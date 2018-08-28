{
  "info": {
    "name": "Mailjet Messages API Message State",
    "_postman_id": "9ddf6f23-3342-4318-b11f-fbfa21e7eaef",
    "description": "Returns message state.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "737b1036-ed37-4313-b574-0040115ea5fe",
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
              "id": "7376dba6-362a-49ef-a0ed-209b30235ee3"
            }
          ]
        },
        {
          "id": "d5080f70-458e-4e8e-b682-cae019760102",
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
              "id": "f6de00c1-4814-4a6a-a382-d68d52b602cd"
            }
          ]
        },
        {
          "id": "5df970ac-c874-4aae-bf68-63570cf0f7f8",
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
              "id": "4eeb0146-5ed5-42bf-b320-7b397c60ef5e"
            }
          ]
        },
        {
          "id": "99537671-6955-4859-8aac-a16f00871b7e",
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
              "id": "6864f861-be12-4a0f-a3a2-ff98c840fe82"
            }
          ]
        },
        {
          "id": "623a1464-0a5d-4857-b19b-6518d9616c21",
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
              "id": "340ee784-4c82-4281-951d-be346b129fae"
            }
          ]
        },
        {
          "id": "1113e163-b98d-47c3-961e-46d1f2ad5a67",
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
              "id": "55f4c46b-5891-4eb8-b9c1-365a67164c31"
            }
          ]
        },
        {
          "id": "e1da05a3-3d0a-4e7e-b987-6d5c99c0c549",
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
              "id": "b0fa2549-606e-42a4-9ac5-9569b611faf8"
            }
          ]
        },
        {
          "id": "8a49ffa0-7bc7-4c03-ab1f-b0d68edd0cde",
          "name": "getMessagestate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.mailjet.com",
              "path": [
                "v3",
                "REST",
                "messagestate/:id"
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
            "description": "Returns message state."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2322a29f-5800-4273-82b3-ae61e9812243"
            }
          ]
        }
      ]
    }
  ]
}