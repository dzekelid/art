{
  "info": {
    "name": "GIGANDCROWD Get Gigme Artist Events Past",
    "_postman_id": "7a451e08-6101-48eb-bc25-63e8e0055daa",
    "description": "Get gigme artist events past.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "cb8181d7-e78a-4053-bedc-3a5b9c5a3c32",
          "name": "getApiV1ArtEventsPast",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/art/:id/events/past"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get art events past."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "284f351b-28a4-4a53-ba54-11b8ba13409e"
            }
          ]
        }
      ]
    },
    {
      "name": "City",
      "item": [
        {
          "id": "0c743f0f-d715-4ff8-b26a-1831ad9685fa",
          "name": "getApiV1CityEvents",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/city/events",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get city events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "059e0c28-bdd9-4671-b3e7-c9ad36c7c50d"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "79776979-156d-42b9-b488-ddcc4622af14",
          "name": "getApiV1GigmeArtistEventsPast",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/artist/:id/events/past"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get gigme artist events past."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "957235d5-a8b0-40fb-83c6-5431270b2514"
            }
          ]
        }
      ]
    }
  ]
}