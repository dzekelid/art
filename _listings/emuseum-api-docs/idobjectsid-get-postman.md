{
  "info": {
    "name": "eMuseum API Art",
    "_postman_id": "dddcce63-169e-4988-8979-68d7dd947c4f",
    "description": "Get Art",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Artists",
      "item": [
        {
          "id": "2ed3a20c-b4c6-4408-acd5-fcfd9641b003",
          "name": "searchArtists",
          "request": {
            "url": "http://gsafinearts.pbs.gsa.gov/emuseum/api/search/people",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search for an artist"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4da77e74-8e12-49c7-b208-c380ef13c56f"
            }
          ]
        },
        {
          "id": "87abde4f-2990-42ff-a710-e632f1ecb0a9",
          "name": "getArtist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gsafinearts.pbs.gsa.gov",
              "path": [
                "emuseum",
                "api",
                "id/people/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Request an artist"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44131afa-199c-474c-a252-45b5068dd65f"
            }
          ]
        }
      ]
    },
    {
      "name": "Art",
      "item": [
        {
          "id": "edf50b35-37ee-4a38-8a44-dd430fb9f3a8",
          "name": "getArt",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gsafinearts.pbs.gsa.gov",
              "path": [
                "emuseum",
                "api",
                "id/objects/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Art"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b97700aa-9cca-4133-8cea-7651319ce706"
            }
          ]
        }
      ]
    }
  ]
}