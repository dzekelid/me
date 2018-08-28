{
  "info": {
    "name": "Mailjet Messages API Message Statistics",
    "_postman_id": "db5be02c-ce18-4280-a825-00f0f1eaf9c6",
    "description": "Message Statistics",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "57c5b555-b884-4717-858a-4daceae14b78",
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
              "id": "28e56d64-0aca-49ac-878a-43638aa6f08f"
            }
          ]
        },
        {
          "id": "d9d57dac-975e-4220-b4e5-8be95b849876",
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
              "id": "8ebd42f2-398f-404e-9ade-b2b91f417bca"
            }
          ]
        },
        {
          "id": "2ad3b6b5-934c-4262-bf99-1d8c2bae9561",
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
              "id": "47ab3899-6e3e-41f1-a907-fddbab275de0"
            }
          ]
        },
        {
          "id": "693a3688-09d2-41e0-a46c-75d349dbf1c0",
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
              "id": "c386f2f4-cad2-4e95-84f8-b75fb9a315aa"
            }
          ]
        },
        {
          "id": "cdad91f5-8d41-434c-bd23-79707b5553d0",
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
              "id": "1b233bbc-7d5b-4b46-9a6d-cc5ced7af20f"
            }
          ]
        },
        {
          "id": "d32889e8-2ef6-4cef-9e8b-7408617754db",
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
              "id": "c7df13b2-23f8-41be-96c7-92127b5fea67"
            }
          ]
        },
        {
          "id": "75840041-3adf-4f15-b155-686a830dad8e",
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
              "id": "b44c6461-5a8d-434a-8e38-df3e13d2bf3d"
            }
          ]
        },
        {
          "id": "991c8c26-d70f-4b74-8ddd-fdb609d9767f",
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
              "id": "2ddeada3-a070-47ec-ad6b-fea281fa6048"
            }
          ]
        },
        {
          "id": "d2a8978b-d55d-4997-a977-3a4c97a2debb",
          "name": "getMessagestatistics",
          "request": {
            "url": "http://api.mailjet.com/v3/REST/messagestatistics/?CampaignID=%7B%7D&CampaignStatus=%7B%7D&ContactEmail=%7B%7D&ContactID=%7B%7D&ContactListID=%7B%7D&CustomCampaign=%7B%7D&From=%7B%7D&FromDomain=%7B%7D&FromID=%7B%7D&FromTS=%7B%7D&FromType=%7B%7D&IsDeleted=%7B%7D&IsNewsletterTool=%7B%7D&IsStarred=%7B%7D&MessageStatus=%7B%7D&Period=%7B%7D&ToTS=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Message Statistics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd37d4ba-a0e3-4de6-9532-12ad80f86fdb"
            }
          ]
        }
      ]
    }
  ]
}