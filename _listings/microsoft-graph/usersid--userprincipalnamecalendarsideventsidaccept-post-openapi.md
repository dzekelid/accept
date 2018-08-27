---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Accept
  description: 'event: accept Accept the specified event.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: meeventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnameeventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /groups/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: groupsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /me/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /groups/{id}/calendar/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: groupsidcalendareventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /me/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: mecalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Accept
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/accept:
    post:
      summary: Event Accept
      description: 'event: accept Accept the specified event.'
      operationId: Event:Accept
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidaccept-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        description: Nature of the data in the body of an entity
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
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