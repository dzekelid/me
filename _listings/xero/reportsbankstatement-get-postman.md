{
  "info": {
    "name": "Clarity Accounting Get Reports Bankstatement",
    "_postman_id": "d2510fbe-0bc6-424a-9588-665f91dbdede",
    "description": "Get reports bankstatement.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Reports",
      "item": [
        {
          "id": "9b65ebed-c3a8-4a85-9aae-f824cff9066e",
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
              "id": "21e97b47-b3e3-4b5a-95c8-770a1547bb37"
            }
          ]
        }
      ]
    }
  ]
}