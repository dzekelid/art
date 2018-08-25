{
  "info": {
    "name": "GIGANDCROWD Post Managers Accept Artistid",
    "_postman_id": "1a0cfd83-861f-4c8a-94d7-405a61164cf1",
    "description": "Post managers accept artistid.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Managers",
      "item": [
        {
          "id": "01eacc97-93f8-4021-b2ef-38ee6451a747",
          "name": "postApiV1ManagersAcceptArtist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/managers/accept/:artistId"
              ],
              "variable": [
                {
                  "id": "artistId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
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
            "description": "Post managers accept artistid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7620e97-dbc8-43c2-9eec-e5bd86c16f2f"
            }
          ]
        }
      ]
    }
  ]
}