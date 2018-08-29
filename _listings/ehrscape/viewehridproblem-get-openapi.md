---
swagger: "2.0"
x-collection-name: EhrScape
x-complete: 0
info:
  title: Ehr Scape Electronic Health Record APIs Gets problems/diagnoses for a patient
  description: Gets problems/diagnoses for a patient.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: rest.ehrscape.com
basePath: /rest/v1
paths:
  /view/{ehrId}/allergy:
    get:
      summary: Gets allergies for a patient
      description: Gets allergies for a patient.
      operationId: get_allergy
      x-api-path-slug: viewehridallergy-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Ergy
  /view/{ehrId}/blood_pressure:
    get:
      summary: Gets recorded blood pressures for a patient
      description: Gets recorded blood pressures for a patient.
      operationId: get_blood_pressure
      x-api-path-slug: viewehridblood-pressure-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Blood
      - Pressure
  /view/{ehrId}/body_temperature:
    get:
      summary: Gets recorded body temperatures for a patient
      description: Gets recorded body temperatures for a patient.
      operationId: get_body_temperature
      x-api-path-slug: viewehridbody-temperature-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Body
      - Temperature
  /view/{ehrId}/height:
    get:
      summary: Gets recorded heights for a patient
      description: Gets recorded heights for a patient.
      operationId: get_height
      x-api-path-slug: viewehridheight-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Height
  /view/{ehrId}/labs:
    get:
      summary: Lab results
      description: Lab results.
      operationId: get_labs
      x-api-path-slug: viewehridlabs-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Labs
  /view/{ehrId}/medication:
    get:
      summary: Gets medications prescribed for a a patient
      description: Gets medications prescribed for a a patient.
      operationId: get_medication
      x-api-path-slug: viewehridmedication-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Medication
  /view/{ehrId}/problem:
    get:
      summary: Gets problems/diagnoses for a patient
      description: Gets problems/diagnoses for a patient.
      operationId: get_problem
      x-api-path-slug: viewehridproblem-get
      parameters:
      - in: path
        name: ehrId
        description: EHR ID
      - in: query
        name: from
        description: Limit by date from
      - in: query
        name: limit
        description: Maximum number of results to return (default = 10, max = 100)
      - in: query
        name: to
        description: Limit by date to
      responses:
        200:
          description: OK
      tags:
      - View
      - EhrId
      - Problem
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