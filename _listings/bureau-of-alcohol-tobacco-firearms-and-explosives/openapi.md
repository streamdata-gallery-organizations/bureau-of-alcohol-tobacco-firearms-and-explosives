---
swagger: "2.0"
x-collection-name: Bureau of Alcohol, Tobacco, Firearms, and Explosives
x-complete: 1
info:
  title: API Time To Crime Rates For Firearms With A Recovery
  description: a-key-component-of-the-bureau-of-alcohol-tobacco-firearms-and-explosivesu2019-atf-enforcement-mission-is-the-tracing-of-firearms-on-behalf-of-thousands-of-federal-state-local-and-foreign-law-enforcement-agencies--firearms-trace-data-is-critically-important-information-developed-by-atf--atf-has-prepared-the-following-statebystate-trace-data-which-is-intended-to-provide-the-public-with-insight-into-firearms-recoveries-
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
  time-to-crime-rates-for-firearms-with-a-recovery.json:
    get:
      summary: Crime Rates For Firearms
      description: Crime Rates For Firearms
      operationId: ""
      x-api-path-slug: timetocrimeratesforfirearmswitharecovery-json-get
      parameters:
      - in: query
        name: average_time_to_crime
      - in: query
        name: state
      - in: query
        name: under_3_months
      - in: query
        name: year
      - in: query
        name: _1_year_to_under_3_years
      - in: query
        name: _2_years_to_under_3_years
      - in: query
        name: _3_months_to_under_7_months
      - in: query
        name: _3_years_and_over
      - in: query
        name: _7_months_to_under_1_year
      responses:
        200:
          description: OK
      tags:
      - ""
---