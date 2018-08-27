{
  "info": {
    "name": "Spotify",
    "_postman_id": "e6a78c61-2b63-44d2-8955-179e95bf15cb",
    "description": "Our Web API lets your applications fetch data from the Spotify music catalog and manage user&rsquo;s playlists and saved music. Based on simple REST principles, our Web API endpoints return metadata in JSON format about artists, albums, and tracks directly from the Spotify catalogue. The API also provides access to user-related data such as playlists and music saved in a &ldquo;Your Music&rdquo; library, subject to user&rsquo;s authorization.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "music",
      "item": [
        {
          "id": "e5124dd7-e434-4d7e-90f5-fb151a0a857c",
          "name": "get-several-artistshttpsdeveloperspotifycomwebapigetseveralartists",
          "request": {
            "url": "http://api.spotify.com/v1/artists?ids=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[Get Several Artists](https://developer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03b2e237-bdbb-4a31-b508-e18ece4266e9"
            }
          ]
        }
      ]
    }
  ]
}