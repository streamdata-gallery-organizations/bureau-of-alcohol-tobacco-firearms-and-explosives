---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 0
info:
  title: API for Importation Applications Importation Applications
  description: Importation Applications
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
  firearms-imports.json:
    get:
      summary: Firearms Imports
      description: Firearms Imports
      operationId: ""
      x-api-path-slug: firearmsimports-json-get
      parameters:
      - in: query
        name: calendar_year
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
  firearms-types-with-a-recovery.json:
    get:
      summary: Firearms Types
      description: Firearms Types
      operationId: ""
      x-api-path-slug: firearmstypeswitharecovery-json-get
      parameters:
      - in: query
        name: analytical_criteria_used_to_compile_the_enclosed_statistics
      - in: query
        name: notes_if_any
      - in: query
        name: number_of_recoveries
      - in: query
        name: state
      - in: query
        name: types
      - in: query
        name: year
      responses:
        200:
          description: OK
      tags:
      - ""
  importation-applications.json:
    get:
      summary: Importation Applications
      description: Importation Applications
      operationId: ""
      x-api-path-slug: importationapplications-json-get
      parameters:
      - in: query
        name: fiscal_year
      - in: query
        name: licensed_importer
      - in: query
        name: military
      - in: query
        name: other
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