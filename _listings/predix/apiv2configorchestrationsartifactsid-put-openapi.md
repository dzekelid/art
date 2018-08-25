---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Runtime Update an artifact by id.
  version: 1.0.0
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/config/orchestrations/artifacts:
    post:
      summary: Upload an artifact and attach it to an orchestration configuration
        entry.
      description: Upload a single artifact file in a multipart MIME structure and
        attach it to an orchestration configuration entry. The multipart MIME structure
        must have the orchestration entry id tagged as 'orchestrationEntryId',  the
        file contents tagged as 'file',  the artifact type tagged as 'type', and  the
        name of artifact tagged as 'name'.  A description (under 1024 characters)
        tagged as 'description' can be optionally specified. Artifact types can be
        either 'portToFieldMap', 'bpmn' or any.   If the artifact type is 'portToFieldMap',
        specify the orchestration step ID tagged as 'stepId'.   Otherwise, 'name'
        will be used as 'stepId'.  (See the documentation for more information regarding
        these files.)
      operationId: uploadOrchConfigArtifact
      x-api-path-slug: apiv2configorchestrationsartifacts-post
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: formData
        name: description
        description: Artifact description
      - in: formData
        name: file
        description: (Required) Artifact file
      - in: formData
        name: name
        description: (Required) Artifact name
      - in: formData
        name: orchestrationEntryId
        description: (Required) orchestration configuration entry id
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: formData
        name: stepId
        description: Orchestration Step ID
      - in: formData
        name: type
        description: (Required) Artifact type
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Upload
      - Artifact
      - Attach
      - It
      - To
      - Orchestration
      - Configuration
      - Entry
  /api/v2/config/orchestrations/artifacts/{id}:
    put:
      summary: Update an artifact by id.
      description: Update the artifact of the orchestration configuration with the
        contents of the supplied multipart MIME structure. The multipart MIME structure
        may have new file contents tagged as 'file',  new artifact type tagged as
        'type',  new name of artifact tagged as 'name',  new description (under 1024
        characters) tagged as 'description', and  new value of the orchestration step
        id tagged as 'stepId.   Artifact types can be either 'portToFieldMap', 'bpmn'
        or any.  (See the documentation for more information regarding these files.)
      operationId: updateOrchConfigArtifact
      x-api-path-slug: apiv2configorchestrationsartifactsid-put
      parameters:
      - in: header
        name: Authorization
        description: Authorization
      - in: formData
        name: description
        description: Artifact description
      - in: formData
        name: file
        description: Artifact file
      - in: path
        name: id
        description: Artifact id
      - in: formData
        name: name
        description: Artifact name
      - in: header
        name: Predix-Zone-Id
        description: Predix-Zone-Id
      - in: formData
        name: stepId
        description: Orchestration Step ID
      - in: formData
        name: type
        description: Artifact type
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Artifact
      - By
      - Id
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