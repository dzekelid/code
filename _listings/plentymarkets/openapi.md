swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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