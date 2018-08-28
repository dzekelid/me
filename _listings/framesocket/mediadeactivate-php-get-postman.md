{
  "info": {
    "name": "Framesocket Deactive Media",
    "_postman_id": "efd93d60-a16a-4731-b4a1-010419945612",
    "description": "Deactive Media",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Media",
      "item": [
        {
          "id": "51a2ec27-846e-4d30-9c26-f4238ab389df",
          "name": "getMediaActivate.php",
          "request": {
            "url": "http://www.framesocket.com/api/media/activate.php?customid=%7B%7D&hash=%7B%7D&key=%7B%7D&secret=%7B%7D&sig=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Activate Media"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa60ad2f-1b3a-43b2-8a86-a9ca104ecdf5"
            }
          ]
        },
        {
          "id": "1bf3e3c5-0773-4512-8c8b-4584a10c23bb",
          "name": "getMediaDeactivate.php",
          "request": {
            "url": "http://www.framesocket.com/api/media/deactivate.php?customid=%7B%7D&hash=%7B%7D&key=%7B%7D&secret=%7B%7D&sig=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactive Media"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e48c20fc-0d88-40f1-945b-0da697714676"
            }
          ]
        }
      ]
    }
  ]
}