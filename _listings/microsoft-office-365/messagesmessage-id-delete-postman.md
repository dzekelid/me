{
  "info": {
    "name": "Microsoft Office 365 Delete Messages Message",
    "_postman_id": "3022be59-02cb-45a2-b13b-c7c9977c212d",
    "description": "You can delete email by simply sending a DELETE request to t...",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "ac8d8db7-eb3d-4466-8048-abbac9ed816d",
          "name": "deleteMessagesMessage",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "You can delete email by simply sending a DELETE request to t"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fb92790-6db8-4fcf-9ee7-dcbbeae51e5a"
            }
          ]
        }
      ]
    }
  ]
}