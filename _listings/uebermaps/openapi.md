---
swagger: "2.0"
x-collection-name: uebermaps
x-complete: 1
info:
  title: uebermaps
  description: enable-people-to-store-spots-on-public-and-private-maps
  termsOfService: https://uebermaps.com/terms/
  contact:
    name: uebermaps API Team
  version: "2.0"
host: uebermaps.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collaborator_invitations/{id}:
    patch:
      summary: Accept collaborator invitation.
      description: Accept collaborator invitation.
      operationId: collaborator_invitations.id.patch
      x-api-path-slug: collaborator-invitationsid-patch
      parameters:
      - in: path
        name: id
        description: Collaborator invitation id
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Accept
      - Collaborator
      - Invitation
---