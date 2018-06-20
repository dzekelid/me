{
  "info": {
    "name": "Datumbox Classifies the Document as commercial or nocommercial",
    "_postman_id": "a7878848-db95-47fd-a757-c7f0dfade771",
    "description": "The Commercial Detection function labels the documents as commercial or non-commercial based on their keywords and expressions. It can be used to detect whether a website is commercial or not.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commercial",
      "item": [
        {
          "id": "34f30b24-13e1-4a4b-b0af-2d107eb15ec9",
          "name": "CommercialDetection",
          "request": {
            "url": "http://api.datumbox.com/1.0/CommercialDetection.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Commercial Detection function labels the documents as commercial or non-commercial based on their keywords and expressions. It can be used to detect whether a website is commercial or not."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8795166-576c-49d0-a1e4-d8f2ad9369ec"
            }
          ]
        }
      ]
    }
  ]
}