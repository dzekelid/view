{
  "info": {
    "name": "Kentico Cloud View a content item by ID",
    "_postman_id": "85cd6dad-1f29-42a3-ab6c-19e64b75613a",
    "description": "Retrieve metadata information about a content item specified by its internal ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "890f8671-93f9-479a-866e-4045ca58e079",
          "name": "Items3120ec15A4a247ec8ccdC85ac8ac5ba5Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve metadata information about a content item specified by its internal ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9601b460-1419-44c3-a440-632d10057893"
            }
          ]
        }
      ]
    }
  ]
}