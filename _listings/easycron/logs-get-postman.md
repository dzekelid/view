{
  "info": {
    "name": "Easycron API View the latest 10 execution logs of a cron job.",
    "_postman_id": "9a786bd6-5341-4d84-bff7-3d032264a193",
    "description": "View the latest 10 execution logs of a cron job.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "a085bf1d-ae3a-4131-8904-c2c5f9b3d616",
          "name": "viewLast10Logs",
          "request": {
            "url": "http://www.easycron.com/rest/logs?id=%7B%7D&token=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "View the latest 10 execution logs of a cron job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d928bdb-92cd-49d7-893c-e103d59ea2d0"
            }
          ]
        }
      ]
    }
  ]
}