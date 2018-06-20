{
  "info": {
    "name": "Microsoft Office 365 Add Messages Message Create Reply All",
    "_postman_id": "874903df-68b0-4798-92db-ec23c91c7a67",
    "description": "Post messages message  createreplyall",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "messages",
      "item": [
        {
          "id": "1dba9755-9db6-4b7f-af75-d493acffa4ee",
          "name": "postMessagesMessageCreatereplyall",
          "request": {
            "url": {
              "protocol": "http",
              "host": "outlook.office365.com",
              "path": [
                "ews",
                "odata",
                "Me",
                "Messages:message_id/CreateReplyAll"
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
            "description": "Post messages message  createreplyall"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7331df38-df97-4899-a00c-e2bfc60926eb"
            }
          ]
        }
      ]
    }
  ]
}