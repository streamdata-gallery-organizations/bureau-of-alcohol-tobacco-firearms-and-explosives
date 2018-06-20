---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for National Firearms Act Special Occupational Taxpayers By State National
    Firearms Act Special Occupational Taxpayers By State
  description: National Firearms Act Special Occupational Taxpayers By State
  version: v1
host: data.atf.gov
basePath: /resource/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  national-firearms-act-special-occupational-taxpayers-by-state.json:
    get:
      summary: National Firearms Act Special Occupational Taxpayers By State
      description: National Firearms Act Special Occupational Taxpayers By State
      operationId: ""
      x-api-path-slug: nationalfirearmsactspecialoccupationaltaxpayersbystate-json-get
      parameters:
      - in: query
        name: dealers
      - in: query
        name: importers
      - in: query
        name: location_1
      - in: query
        name: manufacturers
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - ""
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