{
  "info": {
    "name": "Buffer Get Updates Interactions Mediatypeextension",
    "_postman_id": "c40ead55-1f8b-41e2-aec7-a7f2bf8a03fb",
    "description": "Returns the detailed information on individual interactions with the social media update such as favorites, retweets and likes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Updates",
      "item": [
        {
          "id": "c45454de-f1c6-4734-bda5-cf2da119546d",
          "name": "returns-the-detailed-information-on-individual-interactions-with-the-social-media-update-such-as-fav",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/:id/interactions:mediaTypeExtension"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "event",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the detailed information on individual interactions with the social media update such as favorites, retweets and likes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89bdd22f-d207-48c9-a338-56fb54a2b891"
            }
          ]
        }
      ]
    }
  ]
}