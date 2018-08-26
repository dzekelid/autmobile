---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/globalsearch/suggest:
    get:
      summary: Auto complete global search
      description: Auto complete global search.
      operationId: GlobalSearch_SuggestBytextBysuggestSize
      x-api-path-slug: apiglobalsearchsuggest-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: suggestSize
      - in: query
        name: text
        description: Text to search on
      responses:
        200:
          description: OK
      tags:
      - Auto
      - Complete
      - Global
      - Search
  /api/appointment/suggest:
    post:
      summary: Auto-picks attendees and the next available appointment slot given
        the parameters in the request.
      description: Auto-picks attendees and the next available appointment slot given
        the parameters in the request..
      operationId: Appointment_SuggestAppointmentSlotByrequest
      x-api-path-slug: apiappointmentsuggest-post
      parameters:
      - in: body
        name: request
        description: An appointment suggest request containing information about the
          desired appointment
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Auto-picks
      - Attendees
      - Next
      - Available
      - Appointment
      - Slot
      - Given
      - Parameters
      - In
      - Request
---