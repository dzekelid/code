---
swagger: "2.0"
x-collection-name: Gumroad
x-complete: 1
info:
  title: Gumroad
  description: api-for-selling-of-digital-goods-and-media-
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
  /products/:product_id/offer_codes/:id:
    get:
      summary: Get Products Offer Codes
      description: Retrieve the details of a specific offer code of a product
      operationId: getProductsProductOfferCodes
      x-api-path-slug: productsproduct-idoffer-codesid-get
      responses:
        200:
          description: OK
      tags:
      - Products
      - Offer
      - Codes
    put:
      summary: Put Products Offer Codes
      description: Edit an existing products offer code.
      operationId: putProductsProductOfferCodes
      x-api-path-slug: productsproduct-idoffer-codesid-put
      parameters:
      - in: query
        name: max_purchase_count
      - in: query
        name: offer_code
      responses:
        200:
          description: OK
      tags:
      - Products
      - Offer
      - Codes
---