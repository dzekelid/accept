---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Accept
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/meeventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/meeventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendareventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidcalendareventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidcalendareventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Accept
  x-api-slug: microsoft-graph
  description: 'event: accept Accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/accept
  tags: Event, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/meeventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/meeventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidcalendareventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidcalendareventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Event Tentatively Accept
  x-api-slug: microsoft-graph
  description: 'event: tentativelyAccept Tentatively accept the specified event.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/tentativelyAccept
  tags: Event, Tentatively, Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidtentativelyaccept-post-openapi.md
- name: Microsoft Graph Remove Accepted Sender
  x-api-slug: microsoft-graph
  description: Remove acceptedSender Remove a user or group from the acceptedSenders
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders/$ref
  tags: Remove, Accepted, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsendersref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsendersref-delete-openapi.md
- name: Microsoft Graph List Accepted Senders
  x-api-slug: microsoft-graph
  description: List acceptedSenders Get a list of users or groups that are in the
    acceptedSenders list for this group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders
  tags: List, Accepted, Senders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsenders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsenders-get-openapi.md
- name: Microsoft Graph Create Accepted Sender
  x-api-slug: microsoft-graph
  description: Create acceptedSender Add a new user or group to the acceptedSender
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/acceptedSenders/$ref
  tags: Accepted, Sender
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsendersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/groupsidacceptedsendersref-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Accept
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/accept/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---