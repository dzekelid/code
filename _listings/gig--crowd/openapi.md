swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/promocode/{promoCodeId}:
    put:
      summary: Put Admin Promocode Promocodeid
      description: Put admin promocode promocodeid.
      operationId: putApiV1AdminPromocodePromocode
      x-api-path-slug: apiv1adminpromocodepromocodeid-put
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: promoCodeId
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Promocode
      - Promocodeid
    delete:
      summary: Delete Admin Promocode Promocodeid
      description: Delete admin promocode promocodeid.
      operationId: deleteApiV1AdminPromocodePromocode
      x-api-path-slug: apiv1adminpromocodepromocodeid-delete
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: promoCodeId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Promocode
      - Promocodeid