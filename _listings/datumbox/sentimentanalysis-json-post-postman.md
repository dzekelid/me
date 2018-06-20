{
  "info": {
    "name": "Datumbox Identifies the Sentiment of the Document",
    "_postman_id": "fbdfae46-88ba-4b10-b1f7-d237eb9dd207",
    "description": "The Sentiment Analysis function classifies documents as positive, negative or neutral (lack of sentiment) depending on whether they express a positive, negative or neutral opinion.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sentiment",
      "item": [
        {
          "id": "d813eff4-1427-41cd-98c5-61299e19670c",
          "name": "SentimentAnalysis",
          "request": {
            "url": "http://api.datumbox.com/1.0/SentimentAnalysis.json",
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
            "description": "The Sentiment Analysis function classifies documents as positive, negative or neutral (lack of sentiment) depending on whether they express a positive, negative or neutral opinion."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71ee4d99-5279-49bd-8975-463ce73aba21"
            }
          ]
        }
      ]
    }
  ]
}