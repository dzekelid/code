---
name: Gumroad
x-slug: gumroad
description: Sell music, comics, software, books, and films directly to your audience.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
x-kinRank: "8"
x-alexaRank: "4658"
tags: Code
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/apis.md
specificationVersion: "0.14"
apis:
- name: Gumroad Get Products Offer Codes
  x-api-slug: gumroad
  description: Retrieve all of the existing offer codes for a product. Either amount_cents
    or percent_off will be returned depending if the offer code is a fixed amount
    off or a percentage off. A universal offer code is one that applies to all products.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/productsproduct-idoffer-codes-get-openapi.md
- name: Gumroad Post Products Offer Codes
  x-api-slug: gumroad
  description: Create a new offer code for a product. Default offer code is in cents.
    A universal offer code is one that applies to all products.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/productsproduct-idoffer-codes-post-openapi.md
- name: Gumroad Get Products Offer Codes
  x-api-slug: gumroad
  description: Retrieve the details of a specific offer code of a product
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes/:id
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/productsproduct-idoffer-codesid-get-openapi.md
- name: Gumroad Put Products Offer Codes
  x-api-slug: gumroad
  description: Edit an existing products offer code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes/:id
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/productsproduct-idoffer-codesid-put-openapi.md
- name: Gumroad
  x-api-slug: gumroad
  description: Share and sell exclusive videos directly to your followers. Selling
    stuff has always been a pain. No longer! Get back to creating.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/gumroad/openapi.md
x-common:
- type: x-application-management
  url: https://gumroad.com/settings/developer
- type: x-base
  url: https://api.gumroad.com/
- type: x-blog
  url: http://blog.gumroad.com
- type: x-blog-rss
  url: http://blog.gumroad.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/gumroad
- type: x-developer
  url: https://gumroad.com/developers
- type: x-email
  url: partners@gumroad.com
- type: x-email
  url: support@gumroad.com
- type: x-embeddable
  url: https://gumroad.com/embed
- type: x-github
  url: https://github.com/gumroad
- type: x-pricing
  url: https://gumroad.com/features/pricing
- type: x-privacy
  url: https://gumroad.com/privacy
- type: x-terms-of-service
  url: https://gumroad.com/terms
- type: x-twitter
  url: https://twitter.com/gumroad
- type: x-webhooks
  url: https://gumroad.com/webhooks
- type: x-website
  url: http://gumroad.com
- type: x-website
  url: https://gumroad.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---