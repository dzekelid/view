---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/Viewing/{id}:
    get:
      summary: Get an Viewing by its id.
      description: Get an viewing by its id..
      operationId: Viewing_GetByid
      x-api-path-slug: apiviewingid-get
      parameters:
      - in: path
        name: id
        description: The id of the Viewing to get
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Viewing
      - By
      - Its
      - Id
    delete:
      summary: Cancel a viewing appointment by id if it exists.
      description: Cancel a viewing appointment by id if it exists..
      operationId: Viewing_DeleteByidBycancelAppointmentDataContract
      x-api-path-slug: apiviewingid-delete
      parameters:
      - in: body
        name: cancelAppointmentDataContract
        description: The cancellation details, including reason of cancellation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the viewing appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Viewing
      - Appointment
      - By
      - Id
      - If
      - It
      - Exists
  /api/viewing/{id}/editfeedback:
    put:
      summary: Edit the feedback against a Viewing.
      description: Edit the feedback against a viewing..
      operationId: Viewing_EditFeedbackByidBycommand
      x-api-path-slug: apiviewingideditfeedback-put
      parameters:
      - in: body
        name: command
        description: Feedback details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Viewing id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Feedback
      - Against
      - Viewing
  /api/viewing/{id}/recordfeedback:
    post:
      summary: Record the feedback against a Viewing.
      description: Record the feedback against a viewing..
      operationId: Viewing_RecordFeedbackByidBycommand
      x-api-path-slug: apiviewingidrecordfeedback-post
      parameters:
      - in: body
        name: command
        description: Feedback details
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Viewing id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Record
      - Feedback
      - Against
      - Viewing
  /api/viewing/{viewingFeedbackId}/editfeedbacknotified:
    put:
      summary: Edit that the feedback for a Viewing was notified to the vendor.
      description: Edit that the feedback for a viewing was notified to the vendor..
      operationId: Viewing_EditFeedbackNotifiedByviewingFeedbackIdByvendorNotifiedIdBytypeBynotifiedDateBynegIds
      x-api-path-slug: apiviewingviewingfeedbackideditfeedbacknotified-put
      parameters:
      - in: query
        name: negIds
      - in: query
        name: notifiedDate
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: type
        description: Task type for how vendor was communicated e
      - in: query
        name: vendorNotifiedId
        description: vendor notified id
      - in: path
        name: viewingFeedbackId
        description: viewing feedback id
      responses:
        200:
          description: OK
      tags:
      - Edit
      - That
      - Feedbacka
      - Viewing
      - Was
      - Notified
      - To
      - Vendor
  /api/viewing/{viewingFeedbackId}/feedbacknotified:
    post:
      summary: Record that the feedback for a Viewing was notified to the vendor.
      description: Record that the feedback for a viewing was notified to the vendor..
      operationId: Viewing_FeedbackNotifiedByviewingFeedbackIdBytypeBynotifiedDateBynegIds
      x-api-path-slug: apiviewingviewingfeedbackidfeedbacknotified-post
      parameters:
      - in: query
        name: negIds
      - in: query
        name: notifiedDate
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: type
        description: Task type for how vendor was communicated e
      - in: path
        name: viewingFeedbackId
        description: viewing feedback id
      responses:
        200:
          description: OK
      tags:
      - Record
      - That
      - Feedbacka
      - Viewing
      - Was
      - Notified
      - To
      - Vendor
---