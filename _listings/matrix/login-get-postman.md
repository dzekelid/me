{
  "info": {
    "name": "Matrix Login Operations API Get the login mechanism to use when logging in.",
    "_postman_id": "73c1f7d1-c9b9-4211-81fe-779660d269e7",
    "description": "All login stages MUST be mentioned if there is >1 login type.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Login",
      "item": [
        {
          "id": "a64bb326-ee80-452b-9ae5-f4414b923183",
          "name": "get_login_info",
          "request": {
            "url": "http:///login/http://localhost:8008/_matrix/client/api/v1/login",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "All login stages MUST be mentioned if there is >1 login type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60f347b2-b674-42a7-81af-f90942ad7d98"
            }
          ]
        }
      ]
    }
  ]
}