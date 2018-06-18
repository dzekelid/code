---
name: Weatherbit
x-slug: weatherbit
description: Our mission at Weatherbit.io is pretty simple. It is to provide the highest
  quality weather forecasts, observations, and historical weather data at the best
  price. We constantly improve our platform every day. Our Weather APIs grow with
  you. Have a feature request? Let us know on our Support Forum! Our commitment to
  data quality is unparalleled. Our forecast system uses global forecast models (GFS/ECMWF),
  in combination with local short range high resolution models to derive the most
  accurate, and relevant forecast apis on the web.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Code
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/apis.md
specificationVersion: "0.14"
apis:
- name: Weatherbit Get Bulk History Daily Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/daily?postal_code={postal_code}
  tags: Weather,Bulk, History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/bulkhistorydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Bulk History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//bulk/history/hourly?postal_code={postal_code}
  tags: Weather,Bulk, History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/bulkhistoryhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Current Postla Code Code
  x-api-slug: weatherbit
  description: Returns current weather observation - Given a Postal Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//current?postal_code={postal_code}
  tags: Weather,Current, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/currentpostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/currentpostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast 3hourly Postla Code Code
  x-api-slug: weatherbit
  description: Returns a 3-hourly forecast, where each point represents a three hour
    period. Every point has a datetime string in the format "YYYY-MM-DD:HH". Time
    is UTC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/3hourly?postal_code={postal_code}
  tags: Weather,Forecast, 3hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecast3hourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Daily Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where
    each point represents one day (24hr) period. Every point has a datetime string
    in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at 23:59 UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/daily?postal_code={postal_code}
  tags: Weather,Forecast, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecastdailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get Forecast Hourly Postla Code Code
  x-api-slug: weatherbit
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//forecast/hourly?postal_code={postal_code}
  tags: Weather,Forecast, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/forecasthourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Daily Postla Code Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/daily?postal_code={postal_code}
  tags: Weather,History, Daily, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/historydailypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/historydailypostal-codepostal-code-get-openapi.md
- name: Weatherbit Get History Hourly Postal Code
  x-api-slug: weatherbit
  description: Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day
    for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0//history/hourly?postal_code={postal_code}
  tags: Weather,History, Hourly, Postal, Code, Postal, Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/historyhourlypostal-codepostal-code-get-openapi.md
- name: Weatherbit
  x-api-slug: weatherbit
  description: Our mission at Weatherbit.io is pretty simple. It is to provide the
    highest quality weather forecasts, observations, and historical weather data at
    the best price. We constantly improve our platform every day. Our Weather APIs
    grow with you. Have a feature request? Let us know on our Support Forum! Our commitment
    to data quality is unparalleled. Our forecast system uses global forecast models
    (GFS/ECMWF), in combination with local short range high resolution models to derive
    the most accurate, and relevant forecast apis on the web.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/weatherbit-logo.png
  humanURL: http://weatherbit.io
  baseURL: https://api.weatherbit.io//v2.0
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/weatherbit/openapi.md
x-common:
- type: x-blog
  url: https://www.weatherbit.io/blog
- type: x-contact-form
  url: https://www.weatherbit.io/contact
- type: x-documentation
  url: https://www.weatherbit.io/api
- type: x-github
  url: https://github.com/weatherbit
- type: x-pricing
  url: https://www.weatherbit.io/pricing
- type: x-twitter
  url: https://twitter.com/weatherbitio
- type: x-website
  url: http://weatherbit.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---