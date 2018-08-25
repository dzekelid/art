---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 1
info:
  title: AWS Device Farm API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListArtifacts:
    get:
      summary: List Artifacts
      description: Gets information about artifacts.
      operationId: listArtifacts
      x-api-path-slug: actionlistartifacts-get
      parameters:
      - in: query
        name: arn
        description: The Run, Job, Suite, or Test ARN
        type: string
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous call to this
          operation, which can be used to return the next set of items in the list
        type: string
      - in: query
        name: type
        description: The artifacts type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Artifacts
---