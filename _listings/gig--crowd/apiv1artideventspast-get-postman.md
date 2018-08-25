{
  "info": {
    "name": "GIGANDCROWD Get Art Events Past",
    "_postman_id": "6b44db16-0db7-415a-8888-058a78a8b201",
    "description": "Get art events past.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "c793a2c2-2dc9-47e8-adbb-54c1a21d6d43",
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
              "id": "c740816d-1308-499a-84a9-e9a40ee1b8bc"
            }
          ]
        }
      ]
    }
  ]
}