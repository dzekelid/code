{
  "info": {
    "name": "Weatherbit Get History Daily Postla Code Code",
    "_postman_id": "2ff4ad17-4e59-4c2e-a8c3-6d5728c6dd37",
    "description": "Returns Historical Observations - Given a Postal Code. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "898d32c1-fcd0-4444-841b-568b36cb36af",
          "name": "returns-historical-observations--given-a-postal-code-limit-1-day-for-low-volume-plans-limit-7-days-f",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "history/daily?postal_code=:postal_code"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "country",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "end_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "postal_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns Historical Observations - Given a Postal Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2dcdd561-83c0-4a5a-abfc-00c4dfa5d8c4"
            }
          ]
        }
      ]
    }
  ]
}