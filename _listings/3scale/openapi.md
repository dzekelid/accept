---
swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3Scale Account Management API
  description: the-api-for-managing-3scale-accounts-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/api/accounts/{account_id}/applications/{id}/accept.xml:
    put:
      summary: Application Accept
      description: Application accept.
      operationId: application
      x-api-path-slug: adminapiaccountsaccount-idapplicationsidaccept-xml-put
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: path
        name: id
        description: id of the application
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Application
      - Accept
---