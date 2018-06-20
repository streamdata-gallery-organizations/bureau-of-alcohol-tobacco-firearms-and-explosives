---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Firearms Imported Into The United States By Country Firearms Imported
    Into The United States By Country
  description: Firearms Imported Into The United States By Country
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
  firearms-imported-into-the-united-states-by-country.json:
    get:
      summary: Firearms Imported Into The United States By Country
      description: Firearms Imported Into The United States By Country
      operationId: ""
      x-api-path-slug: firearmsimportedintotheunitedstatesbycountry-json-get
      parameters:
      - in: query
        name: country
      - in: query
        name: handguns
      - in: query
        name: rifles
      - in: query
        name: shotguns
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