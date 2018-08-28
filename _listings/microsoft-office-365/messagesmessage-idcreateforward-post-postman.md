{
  "info": {
    "name": "Microsoft Office 365 Add Messages Message Createforward",
    "_postman_id": "c3a99200-7384-42fe-92c4-9d9f66607826",
    "description": "Post messages message  createforward",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "c1b9473a-f700-4081-ac97-0ee3955fb470",
          "name": "postMessagesMessageCreateforward",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Messages:message_id/CreateForward"
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
            "description": "Post messages message  createforward"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d62215e4-6594-42c9-a2a4-5bce4a409e35"
            }
          ]
        }
      ]
    }
  ]
}