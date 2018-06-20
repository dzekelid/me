{
  "info": {
    "name": "Microsoft Office 365 Add Messages Message Createreply",
    "_postman_id": "c4f91736-2dec-4b90-b894-9d5c85f3c081",
    "description": "Post messages message  createreply",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "05c3abfd-b6a9-4e24-9f39-5ebbb3131e8c",
          "name": "postMessagesMessageCreatereply",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Messages:message_id/CreateReply"
              ],
              "variable": [
                {
                  "id": "message_id",
                  "value": "message_id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post messages message  createreply"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23e8f227-e956-4a0b-a732-03c6f27b257b"
            }
          ]
        }
      ]
    }
  ]
}