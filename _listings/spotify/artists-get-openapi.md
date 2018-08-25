---
swagger: "2.0"
x-collection-name: Spotify
x-complete: 0
info:
  title: Spotify Get Artists
  description: '[Get Several Artists](https://developer.spotify.com/web-api/get-several-artists/)'
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