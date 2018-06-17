---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 0
info:
  title: LH Public Airlines
  version: "1.0"
  description: List all airlines or one specific airline.
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /references/airlines/{airlineCode}:
    get:
      summary: Airlines
      description: List all airlines or one specific airline.
      operationId: ReferencesAirlinesByAirlineCodeGet
      x-api-path-slug: referencesairlinesairlinecode-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: airlineCode
        description: 2-character IATA airline/carrier code
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      responses:
        200:
          description: OK
      tags:
      - References
      - Airlines
      - AirlineCode
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