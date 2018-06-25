{
  "info": {
    "name": "Pay Run.IO Gets the nominal code",
    "_postman_id": "db33567c-07d1-4c2a-b436-dbc5aa543f91",
    "description": "Gets the nominal code",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Nominal",
      "item": [
        {
          "id": "4ec8c9da-44f1-4c9b-a88e-15362097a00e",
          "name": "GetNominalCodeFromEmployer",
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
            "method": "GET",
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
            "description": "Gets the nominal code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cd2fcc4-e3bd-4575-ba82-6dbc6e13cb89"
            }
          ]
        },
        {
          "id": "a25456d9-8940-4439-9ebd-350bf7fccf20",
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
              "id": "b8d249cd-4eaf-4970-b86e-b7f555d3d26c"
            }
          ]
        }
      ]
    }
  ]
}