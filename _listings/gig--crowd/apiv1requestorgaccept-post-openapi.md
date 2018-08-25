---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Request Org Accept
  version: 1.0.0
  description: Post request org accept.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/managers/accept/{artistId}:
    post:
      summary: Post Managers Accept Artistid
      description: Post managers accept artistid.
      operationId: postApiV1ManagersAcceptArtist
      x-api-path-slug: apiv1managersacceptartistid-post
      parameters:
      - in: path
        name: artistId
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Managers
      - Accept
      - Artistid
  /api/v1/request/org/accept:
    post:
      summary: Post Request Org Accept
      description: Post request org accept.
      operationId: postApiV1RequestOrgAccept
      x-api-path-slug: apiv1requestorgaccept-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Request
      - Org
      - Accept
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