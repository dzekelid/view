---
swagger: "2.0"
x-collection-name: EhrScape
x-complete: 0
info:
  title: Ehr Scape Electronic Health Record APIs Gets allergies for a patient
  description: Gets allergies for a patient.
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