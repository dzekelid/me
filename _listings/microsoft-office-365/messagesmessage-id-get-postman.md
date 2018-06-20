{
  "info": {
    "name": "Microsoft Office 365 Get Messages Message",
    "_postman_id": "19036ecf-bfad-4e10-aa36-544b2f9c11f0",
    "description": "You can request information about a specific email or meetin...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "d4b524ef-a2a5-4459-a87a-c6d8174477a1",
          "name": "getMessagesMessage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Messages:message_id"
              ],
              "variable": [
                {
                  "id": "message_id",
                  "value": "message_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can request information about a specific email or meetin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e095f5f-1a9a-4cd3-8494-8a816e24c15b"
            }
          ]
        }
      ]
    }
  ]
}