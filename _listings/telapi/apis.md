---
name: TelAPI
x-slug: telapi
description: Zang offers business communications tools & voice app development platforms
  that bring innovation and ease to unified communications & collaboration solutions.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
x-kinRank: "9"
x-alexaRank: "1071695"
tags: Code
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/apis.md
specificationVersion: "0.14"
apis:
- name: hetras Hotel API Version 0 Get a list of codes for the specified hotel either
    filtered by type or code.
  x-api-slug: hetras-hotel-api-version-0
  description: "With this call you can find codes for a hotel by type or code. By
    default and without any filter criteria\r\n            defined it will return
    you all available codes."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/codes
  tags: Codesthe,Specified,Hotel,Either,Filtered,By,Type,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/apihotelv0hotelshotelidcodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/apihotelv0hotelshotelidcodes-get-openapi.md
- name: hetras Hotel API Version 0 Get all the details for a specific code available
    for the hotel.
  x-api-slug: hetras-hotel-api-version-0
  description: Read the details about a specific code available for the defined hotel.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/codes/{id}
  tags: Detailsa,Specific,Code,Availablethe,Hotel
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/apihotelv0hotelshotelidcodesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/apihotelv0hotelshotelidcodesid-get-openapi.md
- name: hetras Hotel API Version 0
  x-api-slug: hetras-hotel-api-version-0
  description: Zang offers business communications tools & voice app development platforms
    that bring innovation and ease to unified communications & collaboration solutions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net//
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/telapi/openapi.md
x-common:
- type: x-base
  url: https://api.telapi.com
- type: x-blog
  url: http://www.TelAPI.com/blog/
- type: x-blog-rss
  url: http://www.telapi.com/blog/feed/
- type: x-contact-form
  url: http://www.telapi.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/telapi
- type: x-crunchbase
  url: https://crunchbase.com/organization/zang-io
- type: x-developer
  url: http://www.telapi.com/docs/
- type: x-email
  url: support@telapi.com
- type: x-github
  url: https://github.com/TelAPI
- type: x-pricing
  url: http://www.telapi.com/pricing
- type: x-privacy
  url: https://www.telapi.com/legal/privacy-policy
- type: x-selfservice-registration
  url: https://www.telapi.com/signup
- type: x-status
  url: http://status.telapi.com/
- type: x-terms-of-service
  url: https://www.telapi.com/legal/tos
- type: x-twitter
  url: https://twitter.com/TelAPI
- type: x-twitter
  url: https://twitter.com/Zang_io
- type: x-website
  url: http://www.telapi.com
- type: x-website
  url: http://telapi.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---