{
  "info": {
    "name": "Barclays Get Unsecured SME Loans",
    "_postman_id": "836b3124-4eee-4b23-96f5-2c8aab62dbb4",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Atms",
      "item": [
        {
          "id": "3c49bbaf-7356-4fca-a8a8-df466ae0edf1",
          "name": "getATMS",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/atms/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ddb717ce-d2f8-4587-abdc-504cba925a49"
            }
          ]
        }
      ]
    },
    {
      "name": "Branches",
      "item": [
        {
          "id": "d21c237d-cd39-4254-9e2c-e99dbafb6124",
          "name": "getBranches",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/branches/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "185c853d-ccf3-4116-9f6e-b719b3622881"
            }
          ]
        }
      ]
    },
    {
      "name": "Personal",
      "item": [
        {
          "id": "9db15dbc-cab4-4ab3-872f-7484b7bb54d6",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/personal-current-accounts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f3ca69c-9d24-498a-ab5a-21b8f5ceb3b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Business",
      "item": [
        {
          "id": "b07e7f7a-31c7-4f1b-9364-92940fb06512",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/business-current-accounts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "252baab8-8471-4055-a6ea-24379737c44f"
            }
          ]
        }
      ]
    },
    {
      "name": "Unsecured",
      "item": [
        {
          "id": "b3b11bc1-bb5c-47a3-9092-89b72b47a7c6",
          "name": "pathOperation",
          "request": {
            "url": "http://atlas.api.barclays/open-banking/v2.1/unsecured-sme-loans/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58c99dfd-cab6-4174-82e6-4baa3dbc2f00"
            }
          ]
        }
      ]
    }
  ]
}