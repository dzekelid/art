{
  "info": {
    "name": "GIGANDCROWD Get Gigme Artist Events Future",
    "_postman_id": "c572bb96-8b05-4b45-8b3c-1f70a504744e",
    "description": "Get gigme artist events future.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "ce1c5fd1-b3d2-46ce-8b3a-fc848c2c6290",
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
              "id": "a172357c-ed73-4600-ae81-75cc27456c7f"
            }
          ]
        }
      ]
    },
    {
      "name": "City",
      "item": [
        {
          "id": "b802480a-0a7b-4f4b-944a-333c64f63779",
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
              "id": "97d7951a-8dd5-4799-81e9-66f335dacf92"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "66808b53-62cb-4705-9460-ba348fca9f95",
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
              "id": "7fcb975b-48f8-4d73-8cb9-020acb815a71"
            }
          ]
        },
        {
          "id": "0c993bd0-dfbd-499a-9869-57061f61b5d4",
          "name": "getApiV1GigmeArtistEventsFuture",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/artist/:id/events/future"
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
            "description": "Get gigme artist events future."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a04081d-b8e9-44d9-906b-50660eee7e4b"
            }
          ]
        }
      ]
    }
  ]
}