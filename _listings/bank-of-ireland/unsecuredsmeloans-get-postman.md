{
  "info": {
    "name": "Bank of Ireland Get Unsecured Sme Loans",
    "_postman_id": "d28b0de1-7112-4768-9571-213e83dda470",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "unsecured",
      "item": [
        {
          "id": "7d77cc8c-29a2-4746-a66e-958e7fcaf99f",
          "name": "pathOperation",
          "request": {
            "url": "http://openapi.bankofireland.com/open-banking/v2.1/unsecured-sme-loans/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a26b8f17-3055-4a26-b6b8-48f324f56cf5"
            }
          ]
        }
      ]
    }
  ]
}