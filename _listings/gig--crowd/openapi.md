swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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
  /api/v1/request/art/accept:
    post:
      summary: Post Request Art Accept
      description: Post request art accept.
      operationId: postApiV1RequestArtAccept
      x-api-path-slug: apiv1requestartaccept-post
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
      - Art
      - Accept
  /api/v1/request/art/accept/performanceDate:
    post:
      summary: Post Request Art Accept Performancedate
      description: Post request art accept performancedate.
      operationId: postApiV1RequestArtAcceptPerformancedate
      x-api-path-slug: apiv1requestartacceptperformancedate-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: request
        description: /
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Request
      - Art
      - Accept
      - Performancedate