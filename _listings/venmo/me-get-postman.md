{
  "info": {
    "name": "Venmo API Get Me",
    "_postman_id": "721bad23-c677-4ab6-b65e-4d3087b38a69",
    "description": "Get me.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Me",
      "item": [
        {
          "id": "3e148f35-a1da-442d-82f1-1fb651201628",
          "name": "getMe",
          "request": {
            "url": "http://api.venmo.com/v1/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b55a82d1-de50-4b45-bb4d-a2e10982e5b3"
            }
          ]
        }
      ]
    }
  ]
}