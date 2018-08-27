{
  "info": {
    "name": "GIGANDCROWD Post Managers Approve Artistid",
    "_postman_id": "61a17de9-d0e8-464d-9b1e-a56018b19e42",
    "description": "Post managers approve artistid.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Admin",
      "item": [
        {
          "id": "9713d8f0-d4c4-4388-a7bc-fa40b2615159",
          "name": "postApiV1AdminEventApproveEvent",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/admin/event/approve/:eventId"
              ],
              "variable": [
                {
                  "id": "eventId",
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
            "description": "Post admin event approve eventid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6052ebf5-ebbe-4760-b24a-5e2f87bf9e84"
            }
          ]
        }
      ]
    },
    {
      "name": "Managers",
      "item": [
        {
          "id": "0cecbae9-77c1-4878-ae35-97b00f133c59",
          "name": "postApiV1ManagersApproveArtist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/managers/approve/:artistId"
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
            "description": "Post managers approve artistid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c38c0dad-78aa-407c-ab99-252058a280c6"
            }
          ]
        }
      ]
    }
  ]
}