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
  actions-on-federal-firearms-license-applications.json:
    get:
      summary: Actions On Federal Firearms License Applications
      description: Actions On Federal Firearms License Applications
      operationId: getActionsOnFederalFirearmsLicenseApplications.json
      x-api-path-slug: actionsonfederalfirearmslicenseapplications-json-get
      parameters:
      - in: query
        name: applications_abandoned
      - in: query
        name: applications_denied
      - in: query
        name: applications_withdrawn
      - in: query
        name: fiscal_year
      - in: query
        name: original_applications_processed
      responses:
        200:
          description: OK
      tags:
      - Actions
      - "On"
      - Federal
      - Firearms
      - License
      - Applications
      - Json
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