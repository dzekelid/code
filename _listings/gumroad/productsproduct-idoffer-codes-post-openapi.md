---
swagger: "2.0"
x-collection-name: Gumroad
x-complete: 0
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
    get:
      summary: Get Products Offer Codes
      description: Retrieve all of the existing offer codes for a product. Either
        amount_cents or percent_off will be returned depending if the offer code is
        a fixed amount off or a percentage off. A universal offer code is one that
        applies to all products.
      operationId: getProductsProductOfferCodes
      x-api-path-slug: productsproduct-idoffer-codes-get
      responses:
        200:
          description: OK
      tags:
      - Products
      - Offer
      - Codes
    post:
      summary: Post Products Offer Codes
      description: Create a new offer code for a product. Default offer code is in
        cents. A universal offer code is one that applies to all products.
      operationId: postProductsProductOfferCodes
      x-api-path-slug: productsproduct-idoffer-codes-post
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
      - Products
      - Offer
      - Codes
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