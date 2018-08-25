---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
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
---