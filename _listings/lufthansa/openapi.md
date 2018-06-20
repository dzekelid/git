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
  /references/airports/nearest/{latitude},{longitude}:
    get:
      summary: Nearest Airports
      description: List the 5 closest airports to the given latitude and longitude,
        irrespective of the radius of the reference point.
      operationId: ReferencesAirportsNearestByLatitudeAndLongitudeGet
      x-api-path-slug: referencesairportsnearestlatitudelongitude-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: query
        name: lang
        description: 2 letter ISO 3166-1 language code
      - in: path
        name: latitude
        description: Latitude in decimal format to at most 3 decimal places
      - in: path
        name: longitude
        description: Longitude in decimal format to at most 3 decimal places
      responses:
        200:
          description: OK
      tags:
      - References
      - Airports
      - Nearest
      - Latitude
      - Longitude
---