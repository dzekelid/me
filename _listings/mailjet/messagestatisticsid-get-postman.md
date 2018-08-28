{
  "info": {
    "name": "Mailjet Messages API Message Statistics",
    "_postman_id": "15d38034-48f3-4202-891e-c858dde8437c",
    "description": "Message Statistics",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Message",
      "item": [
        {
          "id": "132667d0-b7af-4b56-9cdd-05594b74049d",
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
              "id": "de776d8f-49d1-4042-a7ca-5a3e57770d9e"
            }
          ]
        },
        {
          "id": "b9a916fb-5433-4b5a-90ae-cc70c644cd6e",
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
              "id": "a25a225b-0dc2-4774-af21-6b510f6fe757"
            }
          ]
        },
        {
          "id": "08b50b20-a483-4dd7-831d-2014840208ce",
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
              "id": "ef10e2b2-fdbc-4301-ab1c-9625053953b2"
            }
          ]
        },
        {
          "id": "9aed2b6e-bc4c-41af-a8aa-f10b783bb662",
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
              "id": "e899bab3-5c78-44b4-9f40-a1d1afb4d2a2"
            }
          ]
        },
        {
          "id": "afab9c02-68d2-4da9-b3f6-63d1abc12106",
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
              "id": "86f1a05d-1ced-4458-86b5-e3616d9978d0"
            }
          ]
        },
        {
          "id": "a0b3b254-26bd-40f7-8862-a9fee28199d7",
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
              "id": "51a0f504-8c69-40f3-87d7-27c514d91007"
            }
          ]
        },
        {
          "id": "f59353d4-1011-4112-adc2-92a09ea0b31b",
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
              "id": "2bb008be-3b0d-45f2-9602-7b138cdb1d58"
            }
          ]
        },
        {
          "id": "477aee4a-80b8-4e1b-a7d9-3f5c9be7a165",
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
              "id": "6ca64593-1c2e-429d-8f07-0e4b4b848575"
            }
          ]
        },
        {
          "id": "e13a3637-8556-407a-bb26-ffe9826c1f65",
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
              "id": "156b4af3-1523-45c1-98e5-f359fe73d45f"
            }
          ]
        },
        {
          "id": "50f2be34-c5d4-40d9-9eaf-b848f89f91e7",
          "name": "getMessagestatistics",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.mailjet.com",
              "path": [
                "v3",
                "REST",
                "messagestatistics/:id"
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
            "description": "Message Statistics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6bbf7d2-5b8a-4087-9f43-57a5f49be79c"
            }
          ]
        }
      ]
    }
  ]
}