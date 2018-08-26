---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 0
info:
  title: hetras Hotel API Version 0 Get all the details for a specific rateplan in
    the hotel.
  version: v0
  description: Read the details about a specific rateplan for the defined hotel.
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}:
    get:
      summary: Get all the details for a specific rateplan in the hotel.
      description: Read the details about a specific rateplan for the defined hotel.
      operationId: RatePlans_GetRateplan
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancode-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to see details for
      responses:
        200:
          description: OK
      tags:
      - Detailsa
      - Specific
      - Rateplan
      - In
      - Hotel
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