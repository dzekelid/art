---
swagger: "2.0"
x-collection-name: eMuseum API docs
x-complete: 1
info:
  title: eMuseum API
  description: developed-in-partnership-with-museums-the-museum-system-makes-capturing-managing-and-accessing-collection-information-quick-and-easy--emuseum-is-a-webbased-software-program-that-integrates-seamlessly-with-tms-and-other-collection-management-systems-to-dynamically-publish-information-to-your-website-intranet-and-kiosks--this-api-delivers-search-information-and-images-from-tms--emuseum-to-gsa-gov-
  version: 1.0.0
host: gsafinearts.pbs.gsa.gov
basePath: /emuseum/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /id/objects/{id}:
    get:
      summary: Art
      description: Get Art
      operationId: getArt
      x-api-path-slug: idobjectsid-get
      responses:
        200:
          description: OK
      tags:
      - Art
  /search/objects:
    get:
      summary: Art
      description: Seart for art by object
      operationId: searchARt
      x-api-path-slug: searchobjects-get
      responses:
        200:
          description: OK
      tags:
      - Art
---