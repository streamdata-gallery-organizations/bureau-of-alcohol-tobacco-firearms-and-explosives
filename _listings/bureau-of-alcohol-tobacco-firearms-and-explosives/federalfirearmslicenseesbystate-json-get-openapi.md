---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Federal Firearms Licensees By State Federal Firearms Licensees
  description: Federal Firearms Licensees
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
  federal-firearms-licensees-by-state.json:
    get:
      summary: Federal Firearms Licensees
      description: Federal Firearms Licensees
      operationId: ""
      x-api-path-slug: federalfirearmslicenseesbystate-json-get
      parameters:
      - in: query
        name: ffl_population
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