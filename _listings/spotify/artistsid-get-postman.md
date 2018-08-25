{
  "info": {
    "name": "Spotify",
    "_postman_id": "09844df1-7b6b-4848-8dad-a651014a665d",
    "description": "Our Web API lets your applications fetch data from the Spotify music catalog and manage user&rsquo;s playlists and saved music. Based on simple REST principles, our Web API endpoints return metadata in JSON format about artists, albums, and tracks directly from the Spotify catalogue. The API also provides access to user-related data such as playlists and music saved in a &ldquo;Your Music&rdquo; library, subject to user&rsquo;s authorization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "8f73f68d-d089-498e-bf42-ff8dd68bc719",
          "name": "get-an-artisthttpsdeveloperspotifycomwebapigetartist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.spotify.com",
              "path": [
                "v1",
                "artists/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "[Get an Artist](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4819ab1f-6960-4637-9c88-2649fd3f598c"
            }
          ]
        }
      ]
    }
  ]
}