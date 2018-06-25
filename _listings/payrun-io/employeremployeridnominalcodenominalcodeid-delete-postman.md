{
  "info": {
    "name": "Pay Run.IO Deletes the nominal codes",
    "_postman_id": "70de9fda-2205-450c-85db-0129a0315861",
    "description": "Deletes the nominal code",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Nominal",
      "item": [
        {
          "id": "d2a657c0-d8b0-4cb3-8626-0d8ec622b360",
          "name": "DeleteNominalCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.test.payrun.io",
              "path": [
                "Employer/:EmployerId/NominalCode/:NominalCodeId"
              ],
              "variable": [
                {
                  "id": "EmployerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "NominalCodeId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the nominal code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c918ee4-f0ef-49b3-89b7-ac06a3b8a601"
            }
          ]
        }
      ]
    }
  ]
}