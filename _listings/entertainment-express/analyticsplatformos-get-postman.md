{
  "info": {
    "name": "Entertainment Express Get Viewers by Platform OS.",
    "_postman_id": "6f70bf99-97f1-4ebc-abb1-1078fd7f680f",
    "description": "No required parameters, DateValue defaults to Today.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "98ce02d3-e1b3-49e1-98e7-edacaf436a6c",
          "name": "GetAnalyticsViewersByCity",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/City/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd23fded-5b62-471c-b4c8-7992c7b6c30a"
            }
          ]
        },
        {
          "id": "75f5f3e2-9ca7-460c-9842-6b0383dc840c",
          "name": "GetAnalyticsViewersByCountry",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Country/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d59c522-4f2b-4dd4-8f93-2c59a409957f"
            }
          ]
        },
        {
          "id": "899a8d92-d362-4963-a526-e7f6f4eb181f",
          "name": "GetAnalyticEngagementActions",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementActions/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d4e984c-4a61-48ff-8452-b177d9091685"
            }
          ]
        },
        {
          "id": "038535a8-83bc-4028-876e-65c7b8a616b6",
          "name": "GetAnalyticsEngagementTimes",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementTimes/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10b46272-7991-4c1a-9607-0c9b52c24471"
            }
          ]
        },
        {
          "id": "8c701030-be15-42d0-9e83-67b0f1563ae8",
          "name": "GetAnalyticsGBUsage",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/GBUsage/?Month=%7B%7D&ReportTag=%7B%7D&Year=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19586a8c-e4a5-4bd3-b9ad-875a82aaa2b5"
            }
          ]
        },
        {
          "id": "60eb7d7d-2135-4961-91c9-0a4beb2568fa",
          "name": "GetAnalyticsMostActive",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/MostActive/?DateValue=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aaede0db-f7d1-4eef-9999-ea17d5700c73"
            }
          ]
        },
        {
          "id": "09a3dc8a-809c-4d68-8a44-0f53e269cedb",
          "name": "GetAnalyticsViewersByPlatformHardware",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformHardware/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c090c0ca-ef4e-4bef-8aaf-f8c679a4d62e"
            }
          ]
        },
        {
          "id": "ecfb2be8-489a-4020-a977-b828edfff833",
          "name": "GetAnalyticsViewersByPlatformOS",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformOS/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3e1abf6-9507-4f9c-b520-32c254b8a203"
            }
          ]
        },
        {
          "id": "4a17515f-76ca-451e-b91f-54b0ca48b2bd",
          "name": "GetAnalyticsRecentVisitors",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/RecentVisitors/?Limit=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d5b048c-9df3-4b1c-91cf-30d431239631"
            }
          ]
        },
        {
          "id": "02df1659-a459-4f4e-9e0d-53f4fe96c995",
          "name": "GetAnalyticsSummary",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Summary/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c4b7826-3e91-4cea-bb08-2e0d1efdbb08"
            }
          ]
        },
        {
          "id": "2dad6b1f-477b-48cc-9bc5-6679d7498563",
          "name": "GetAnalyticsTitleReport",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/TitleReport/?End=%7B%7D&PublishedId=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Requires a valid published ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea0dd664-d26e-4b92-8275-400123bdb526"
            }
          ]
        },
        {
          "id": "4d267fa4-19f9-4a57-b4c9-c7ea687cc2fe",
          "name": "GetAnalyticsViewsByVideoLog",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/VideoLog/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6c96061-e786-4ea9-9325-ce51f29a5891"
            }
          ]
        },
        {
          "id": "d8fd5074-6174-493e-925f-e961bbcbc7e5",
          "name": "GetAnalyticsViewers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Viewers/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03e4c905-5a66-4912-ab72-9e142dc75c31"
            }
          ]
        },
        {
          "id": "63f5bf06-8eb0-44f4-8d91-f718ddaff2ee",
          "name": "GetAnalyticsViews",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Views/?DateValue=%7B%7D&ReportTag=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1996ef7-dd64-4fdd-86a7-0e75278cf2a6"
            }
          ]
        },
        {
          "id": "f3f0b74f-6f2b-40fb-bb0c-4da1f9778177",
          "name": "GetAnalyticsViewersByWebBrowsers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/WebBrowsers/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4025fc9c-9fe4-48c9-9bc2-89136cadb878"
            }
          ]
        }
      ]
    }
  ]
}