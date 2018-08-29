---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Adds one or more View Points for an Address
  version: 1.0.0
  description: Adds one or more view points for an address.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/address/{id}/viewpoints/add:
    put:
      summary: Adds one or more View Points for an Address
      description: Adds one or more view points for an address.
      operationId: Address_AddViewPointsByidByviewPoints
      x-api-path-slug: apiaddressidviewpointsadd-put
      parameters:
      - in: path
        name: id
        description: The Id of the address to update
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: viewPoints
        description: One or more viewpoints to add
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - S
      - More
      - View
      - Pointsan
      - Ress
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