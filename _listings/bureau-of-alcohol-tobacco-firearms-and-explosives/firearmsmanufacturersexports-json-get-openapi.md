---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Firearms Manufacturers Exports Firearms Manufacturers Exports
  description: Firearms Manufacturers Exports
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
  firearms-manufacturers-exports.json:
    get:
      summary: Firearms Manufacturers Exports
      description: Firearms Manufacturers Exports
      operationId: ""
      x-api-path-slug: firearmsmanufacturersexports-json-get
      parameters:
      - in: query
        name: calendar_year
      - in: query
        name: misc_firearms
      - in: query
        name: pistols
      - in: query
        name: revolvers
      - in: query
        name: rifles
      - in: query
        name: shotguns
      - in: query
        name: total_firearms
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