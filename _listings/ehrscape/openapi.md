swagger: "2.0"
x-collection-name: EhrScape
x-complete: 1
info:
  title: EhrScape Terminology APIs
  description: validates-and-resolves-terminology-codes
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: rest.ehrscape.com
basePath: /terminology-adapter/rest
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
  /view/{ehrId}/pulse:
    get:
      summary: Gets pulse measurements for a patient
      description: Gets pulse measurements for a patient.
      operationId: get_pulse
      x-api-path-slug: viewehridpulse-get
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
      - Pulse
  /view/{ehrId}/spO2:
    get:
      summary: Gets SpO2 measurements for a patient
      description: Gets spo2 measurements for a patient.
      operationId: get_spO2
      x-api-path-slug: viewehridspo2-get
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
      - SpO2
  /view/{ehrId}/weight:
    get:
      summary: Gets recorded weights for a patient
      description: Gets recorded weights for a patient.
      operationId: get_weight
      x-api-path-slug: viewehridweight-get
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
      - Weight