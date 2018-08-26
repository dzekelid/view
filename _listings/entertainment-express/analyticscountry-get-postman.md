{
  "info": {
    "name": "Entertainment Express Get Viewers by Country.",
    "_postman_id": "1483609f-1249-4831-83e6-77eef558c1a2",
    "description": "No required parameters, DateValue defaults to Today.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "5a03fa5f-4cf8-4541-ba29-fc3c78294da3",
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
              "id": "093f35dc-6ed4-4930-a7c9-be29970b1aeb"
            }
          ]
        },
        {
          "id": "01a9137e-0ddd-4766-b156-314e2211372f",
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
              "id": "c9223d0d-69f7-4b9d-8aa0-1930e1f6eaf2"
            }
          ]
        },
        {
          "id": "dfa9f263-1366-4908-b5ed-245df3af5839",
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
              "id": "1f86546a-0696-42fb-84d5-3af634a2b57c"
            }
          ]
        },
        {
          "id": "541ceb1b-6eda-4d29-9214-6a8d1fdfcb11",
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
              "id": "287b636e-437b-4548-9098-f3427ccf8f0c"
            }
          ]
        },
        {
          "id": "e8e4b77d-1f5c-4479-a735-6c130adb659f",
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
              "id": "678bdad4-114e-485e-95c3-510487ddd876"
            }
          ]
        },
        {
          "id": "554f5f09-a353-4c97-b325-619be8e17301",
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
              "id": "e9b4d711-b7e9-4e25-bf7a-1a08238159f2"
            }
          ]
        },
        {
          "id": "c9a1ef1f-8ca6-4a29-82fc-e0bf554dab83",
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
              "id": "bd3aeca3-6667-4960-b26f-33f6546d20f3"
            }
          ]
        },
        {
          "id": "db435100-fbdc-4eeb-8815-661cee188286",
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
              "id": "86d1ea76-e1eb-4b8f-9e40-81dfb8fbba85"
            }
          ]
        },
        {
          "id": "ef093763-516f-4a8e-9e60-ae8e9f2d7dff",
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
              "id": "71f278d3-29b7-4794-8aea-fe61acf1acce"
            }
          ]
        },
        {
          "id": "9d683d6d-e7ca-4d72-b33e-f6e5f166ceeb",
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
              "id": "0fa4f028-808f-4594-a443-e3d51a862742"
            }
          ]
        },
        {
          "id": "816d1566-63ea-4696-aaf1-7413901776ac",
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
              "id": "881f4120-d9ab-4907-9f21-5908c5b310f3"
            }
          ]
        },
        {
          "id": "c7face69-baec-4594-99a3-e99e193eb35b",
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
              "id": "2bc14176-f8da-4068-a597-384bac9ba70b"
            }
          ]
        },
        {
          "id": "636bd5cf-dff4-4be7-b4a1-220a9e31d1e6",
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
              "id": "24e5da3b-0c1e-451f-9b6b-5f813a25db1e"
            }
          ]
        },
        {
          "id": "fe922045-83f3-4b04-a7de-05cd14484a89",
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
              "id": "783a9d30-6e25-4f03-8881-d855847932a5"
            }
          ]
        },
        {
          "id": "996ead6b-65c5-4aba-8acd-fef18ba15717",
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
              "id": "fe82ee20-ed35-4207-a928-d9b9b6d245d4"
            }
          ]
        }
      ]
    }
  ]
}