---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Redeem a coupon code
  description: Redeems a coupon code and applies it to an order. The ID of the order
    must be specified. If the coupon was successfully redeemed, the coupon data will
    be returned. If the coupon can not be redeemed, a validation exception will be
    thrown.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/orders/coupons/campaigns/codes/{code}:
    get:
      summary: Get coupon code information
      description: Gets coupon code information. The code must be specified.
      operationId: getRestOrdersCouponsCampaignsCodesCode
      x-api-path-slug: restorderscouponscampaignscodescode-get
      parameters:
      - in: path
        name: code
      - in: query
        name: with
        description: Load additional relations for a coupon code
      responses:
        200:
          description: OK
      tags:
      - Coupon
      - Code
      - Information
  /rest/orders/coupons/campaigns/{campaignId}/codes:
    post:
      summary: Create a coupon code
      description: Creates a coupon code. The ID of the campaign must be specified.
        A code can optionally be specified. A random code will be generated if the
        code is not specified. A coupon value can also be optionally specified. The
        value of the campaign will be used if no individual value is specified.
      operationId: postRestOrdersCouponsCampaignsCampaignCodes
      x-api-path-slug: restorderscouponscampaignscampaignidcodes-post
      parameters:
      - in: body
        name: /rest/orders/coupons/campaigns/{campaignId}/codes
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: campaignId
      responses:
        200:
          description: OK
      tags:
      - Coupon
      - Code
  /rest/orders/{orderId}/coupons/{coupon}:
    post:
      summary: Redeem a coupon code
      description: Redeems a coupon code and applies it to an order. The ID of the
        order must be specified. If the coupon was successfully redeemed, the coupon
        data will be returned. If the coupon can not be redeemed, a validation exception
        will be thrown.
      operationId: postRestOrdersOrderCouponsCoupon
      x-api-path-slug: restordersorderidcouponscoupon-post
      parameters:
      - in: path
        name: coupon
      - in: path
        name: orderId
      responses:
        200:
          description: OK
      tags:
      - Redeem
      - Coupon
      - Code
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