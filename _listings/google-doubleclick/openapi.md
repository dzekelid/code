---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/postalCodes:
    get:
      summary: Get Postal Codes
      description: Retrieves a list of postal codes.
      operationId: dfareporting.postalCodes.list
      x-api-path-slug: userprofilesprofileidpostalcodes-get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Postal Code
  /userprofiles/{profileId}/postalCodes/{code}:
    get:
      summary: Get Postal Code
      description: Gets one postal code by ID.
      operationId: dfareporting.postalCodes.get
      x-api-path-slug: userprofilesprofileidpostalcodescode-get
      parameters:
      - in: path
        name: code
        description: Postal code ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Postal Code
---