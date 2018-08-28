{
  "info": {
    "name": "Lloyds Bank Get Unsecured SME Loans",
    "_postman_id": "74d666e0-7949-4db0-a00b-b7cd038132f8",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Atms",
      "item": [
        {
          "id": "1941bc83-7dc0-4619-a791-37f1ed6ef288",
          "name": "getATMS",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/atms/",
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
              "id": "c97e21a9-5827-4911-aa68-0c5d51be94d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Branches",
      "item": [
        {
          "id": "f04dfea5-d3cf-4ff6-bed3-ea2fd2c45bfa",
          "name": "getBranches",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/branches/",
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
              "id": "b2e0a67a-a695-43e1-8101-63e12d0299be"
            }
          ]
        }
      ]
    },
    {
      "name": "Personal",
      "item": [
        {
          "id": "a0cb6fe9-5baa-422a-bc22-abc631261f64",
          "name": "getCurrentPersonalAccounts",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/personal-current-accounts/",
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
              "id": "62cb4661-03d0-483d-b919-42f0ef9ac5e1"
            }
          ]
        }
      ]
    },
    {
      "name": "Business",
      "item": [
        {
          "id": "1d06923e-692d-40ea-9385-e1151568fc92",
          "name": "getCurentBusinessAccounts",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/business-current-accounts/",
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
              "id": "4aa091c4-f216-4255-a474-181a7d06c368"
            }
          ]
        }
      ]
    },
    {
      "name": "Unsecured",
      "item": [
        {
          "id": "b80729db-75aa-4fc2-82a3-1bc4bd623398",
          "name": "pathOperation",
          "request": {
            "url": "http://api.lloydsbank.com/open-banking/v2.1/unsecured-sme-loans/",
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
              "id": "a29763cf-0cf2-4113-bd60-832ad493684b"
            }
          ]
        }
      ]
    }
  ]
}