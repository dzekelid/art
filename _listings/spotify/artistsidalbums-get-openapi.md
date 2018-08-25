---
swagger: "2.0"
x-collection-name: Spotify
x-complete: 0
info:
  title: Spotify Get Artist Albums
  description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
  version: v1
host: api.spotify.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /artists:
    get:
      summary: Get Artists
      description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
      operationId: get-several-artistshttpsdeveloperspotifycomwebapigetseveralartists
      x-api-path-slug: artists-get
      parameters:
      - in: query
        name: ids
        description: A comma-separated list of IDs
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}:
    get:
      summary: Get Artist
      description: '[Get an Artist](https://developer.spotify.com/web-api/get-artist/)'
      operationId: get-an-artisthttpsdeveloperspotifycomwebapigetartist
      x-api-path-slug: artistsid-get
      parameters:
      - in: path
        name: id
        description: The Spotify ID for the artist
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
  /artists/{id}/albums:
    get:
      summary: Get Artist Albums
      description: '[Get an Artist''s Albums](https://developer.spotify.com/web-api/get-artists-albums/)'
      operationId: get-an-artists-albumshttpsdeveloperspotifycomwebapigetartistsalbums
      x-api-path-slug: artistsidalbums-get
      parameters:
      - in: query
        name: album_type
        description: Filter by album types
      - in: path
        name: id
        description: The Spotify ID for the artist
      - in: query
        name: limit
        description: The maximum number of items to return
      - in: query
        name: market
        description: The market (an ISO 3166-1 alpha-2 country code)
      - in: query
        name: offset
        description: The index of the first item to return
      responses:
        200:
          description: OK
      tags:
      - Music
      - Artists
      - Albums
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---