---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Book a Viewing.
  version: 1.0.0
  description: Book a viewing..
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
  /api/address/{id}/viewpoints/edit:
    put:
      summary: Edits one or more ViewPoints of an address
      description: Edits one or more viewpoints of an address.
      operationId: Address_EditViewPointsByidBypoints
      x-api-path-slug: apiaddressidviewpointsedit-put
      parameters:
      - in: path
        name: id
        description: The Id of the address to update
      - in: body
        name: points
        description: One or more ViewPoints to edit
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Edits
      - More
      - ViewPoints
      - Of
      - Address
  /api/address/{id}/viewpoints/remove:
    put:
      summary: Removes one or more ViewPoints of an address
      description: Removes one or more viewpoints of an address.
      operationId: Address_RemoveViewPointsByidByviewpointIds
      x-api-path-slug: apiaddressidviewpointsremove-put
      parameters:
      - in: path
        name: id
        description: The Id of the address to update
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: viewpointIds
        description: One or more ViewPoints Ids to remove
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Removes
      - More
      - ViewPoints
      - Of
      - Address
  /api/todo/assignleadstopredefinedteams:
    put:
      summary: Assign InboundLead Todos to the predefined neg teams. e.g. Sales Valuers,
        Sales Viewings, Lettings Viewings etc etc
      description: Assign inboundlead todos to the predefined neg teams. e.g. sales
        valuers, sales viewings, lettings viewings etc etc.
      operationId: DefaultToDo_AssignLeadsToPredefinedTeamsBytoDoId
      x-api-path-slug: apitodoassignleadstopredefinedteams-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: toDoId
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - Predefined
      - Neg
      - Teams
      - ""
      - E
      - G
      - ""
      - Sales
      - Valuers
      - ""
      - Sales
      - Viewings
      - ""
      - Lettings
      - Viewings
      - Etc
      - Etc
  /api/viewing/bookviewing:
    post:
      summary: Book a Viewing.
      description: Book a viewing..
      operationId: Viewing_BookViewingBybookViewingDataContract
      x-api-path-slug: apiviewingbookviewing-post
      parameters:
      - in: body
        name: bookViewingDataContract
        description: the viewing detail
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Book
      - Viewing
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