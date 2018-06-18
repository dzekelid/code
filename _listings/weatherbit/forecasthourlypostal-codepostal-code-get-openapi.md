---
swagger: "2.0"
x-collection-name: Weatherbit
x-complete: 0
info:
  title: Weatherbit Get Forecast Hourly Postla Code Code
  description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
    where each point represents a one hour   period. Every point has a datetime string
    in the format "YYYY-MM-DD:HH". Time is UTC.'
  version: 2.0.0
host: api.weatherbit.io
basePath: /v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bulk/history/daily?postal_code={postal_code}:
    get:
      summary: Get Bulk History Daily Postal Code
      description: Returns Historical Observations - Given a Postal Code.
      operationId: returns-historical-observations--given-a-postal-code
      x-api-path-slug: bulkhistorydailypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Daily
      - Postal
      - Code
      - Postal
      - Code
  /bulk/history/hourly?postal_code={postal_code}:
    get:
      summary: Get Bulk History Hourly Postal Code
      description: Returns Historical Observations - Given a Postal Code.
      operationId: returns-historical-observations--given-a-postal-code-
      x-api-path-slug: bulkhistoryhourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Hourly
      - Postal
      - Code
      - Postal
      - Code
  /current?postal_code={postal_code}:
    get:
      summary: Get Current Postla Code Code
      description: Returns current weather observation - Given a Postal Code.
      operationId: returns-current-weather-observation--given-a-postal-code-
      x-api-path-slug: currentpostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback - Example - callback=func
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: marine
        description: Marine stations only (buoys, oil platforms, etc)
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Current
      - Postal
      - Code
      - Postal
      - Code
  /forecast/3hourly?postal_code={postal_code}:
    get:
      summary: Get Forecast 3hourly Postla Code Code
      description: Returns a 3-hourly forecast, where each point represents a three
        hour period. Every point has a datetime string in the format "YYYY-MM-DD:HH".
        Time is UTC.
      operationId: returns-a-3hourly-forecast-where-each-point-represents-a-three-hour-period-every-point-has-a-datetim
      x-api-path-slug: forecast3hourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - 3hourly
      - Postal
      - Code
      - Postal
      - Code
  /forecast/daily?postal_code={postal_code}:
    get:
      summary: Get Forecast Daily Postla Code Code
      description: '**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast,
        where each point represents one day (24hr) period. Every point has a datetime
        string in the format "YYYY-MM-DD". One day begins at 00:00 UTC, and ends at
        23:59 UTC.'
      operationId: required-basic-plan-or-higher-returns-a-daily-forecast-where-each-point-represents-one-day-24hr-peri
      x-api-path-slug: forecastdailypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: days
        description: Number of days to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Daily
      - Postal
      - Code
      - Postal
      - Code
  /forecast/hourly?postal_code={postal_code}:
    get:
      summary: Get Forecast Hourly Postla Code Code
      description: '**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast,
        where each point represents a one hour   period. Every point has a datetime
        string in the format "YYYY-MM-DD:HH". Time is UTC.'
      operationId: required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-
      x-api-path-slug: forecasthourlypostal-codepostal-code-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: query
        name: country
        description: Country Code (2 letter)
      - in: query
        name: hours
        description: Number of hours to return
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: path
        name: postal_code
        description: Postal Code
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Forecast
      - Hourly
      - Postal
      - Code
      - Postal
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