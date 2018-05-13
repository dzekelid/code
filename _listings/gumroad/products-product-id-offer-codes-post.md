---
swagger: "2.0"
info:
  title: Gumroad Post Products Offer Codes
  description: Create a new offer code for a product. Default offer code is in cents.
    A universal offer code is one that applies to all products.
  termsOfService: https://gumroad.com/terms
  version: v1
host: api.gumroad.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/:product_id/offer_codes:
    post:
      summary: Post Products Offer Codes
      description: Create a new offer code for a product
      operationId: postProductsProductOfferCodes
      parameters:
      - in: query
        name: amount_off
      - in: query
        name: max_purchase_count
      - in: query
        name: name
      - in: query
        name: offer_code
      - in: query
        name: offer_type
      - in: query
        name: universal
      responses:
        200:
          description: OK
      tags:
      - products
      - offer
      - codes
definitions: []
x-collection-name: Gumroad
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