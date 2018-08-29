---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 0
info:
  title: Google Analytics List Views
  description: Lists views (profiles) to which the user has access.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /analytics/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /management/accounts/{accountId}/webproperties/{webPropertyId}/profiles:
    get:
      summary: List Views
      description: Lists views (profiles) to which the user has access.
      operationId: analytics.management.profiles.list
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidprofiles-get
      parameters:
      - in: path
        name: accountId
        description: Account ID for the view (profiles) to retrieve
      - in: query
        name: max-results
        description: The maximum number of views (profiles) to include in this response
      - in: query
        name: start-index
        description: An index of the first entity to retrieve
      - in: path
        name: webPropertyId
        description: Web property ID for the views (profiles) to retrieve
      responses:
        200:
          description: OK
      tags:
      - View
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---