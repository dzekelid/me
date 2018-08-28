{
  "info": {
    "name": "Clarity Accounting X-related-model Reports Bankstatement",
    "_postman_id": "0364a1ff-d77a-461c-ae1c-80eb6034df3e",
    "description": "X-related-model reports bankstatement.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Reports",
      "item": [
        {
          "id": "96f1205a-b7b0-434c-a069-4a4198a442d4",
          "name": "getReportsBankstatement",
          "request": {
            "url": "http://api.xero.com/api.xro/2.0/Reports/BankStatement?bankAccountID=%7B%7D&fromDate=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get reports bankstatement."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e14c540c-4017-46cb-8424-a1d1a3a61298"
            }
          ]
        }
      ]
    }
  ]
}