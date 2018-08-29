{
  "info": {
    "name": "Kentico Cloud View an asset by external ID",
    "_postman_id": "b5e43524-8a48-4b43-9e38-3010eacdff36",
    "description": "Retrieve information about a single asset specified by its external ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "98a88265-e4fe-487c-8f56-2fa49922f913",
          "name": "AssetsGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/assets",
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
            "description": "Retrieve a dynamically paginated list of assets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1beaec84-3707-481e-b5dd-cece470ef327"
            }
          ]
        }
      ]
    },
    {
      "name": "View",
      "item": [
        {
          "id": "3f5ac55d-fdc4-40fc-b9bb-69ef249eed59",
          "name": "AssetsExternalIdWhichBrewingFitsYouGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/assets/external-id/which-brewing-fits-you",
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
            "description": "Retrieve information about a single asset specified by its external ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d6da74d-176d-4f97-9152-f7a76ba2dda8"
            }
          ]
        }
      ]
    }
  ]
}