{
  "info": {
    "name": "GIGANDCROWD Get Request Art Archive",
    "_postman_id": "59764a06-d490-40f2-9243-7330ef8fea71",
    "description": "Get request art archive.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Request",
      "item": [
        {
          "id": "2284359c-deb2-4762-b36e-664110d6b0ae",
          "name": "getApiV1RequestOrgArchive",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/request/org/archive",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get request org archive."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32bde8cf-e63a-4f39-8604-b78b971beb2e"
            }
          ]
        },
        {
          "id": "96c76cf4-9c59-45ca-bba5-f9d1bfc6d7aa",
          "name": "getApiV1RequestArtArchive",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/request/art/archive",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get request art archive."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ed11653-1572-47b3-a1ca-83eaaf9c0e86"
            }
          ]
        }
      ]
    }
  ]
}