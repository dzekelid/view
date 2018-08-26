---
swagger: "2.0"
x-collection-name: Mynewsdesk
x-complete: 0
info:
  title: My News Desk Pressroom List View News
  description: View News
  termsOfService: http://www.mynewsdesk.com/about/terms-and-conditions?locale=en
  version: v1
host: www.mynewsdesk.com
basePath: /services/pressroom/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  view/:
    get:
      summary: View News
      description: View News
      operationId: getView
      x-api-path-slug: view-get
      parameters:
      - in: query
        name: callback
        description: If format is JSON and callback is specified, the JSON response
          is wrapped in a function call with the specified callback name
      - in: query
        name: format
        description: 'Specify the format of the response: JSON or full XML'
      - in: query
        name: item_id
        description: ID of the material to be fetched
      - in: query
        name: type_of_media
        description: The type of material to be fetched
      - in: path
        name: unique key
        description: The MyNewsDesk API Key
      responses:
        200:
          description: OK
      tags:
      - View
      - News
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