---
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
  /api/v1/event/active:
    get:
      summary: Get Event Active
      description: Get event active.
      operationId: getApiV1EventActive
      x-api-path-slug: apiv1eventactive-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Event
      - Active
  /api/v1/finance/active:
    get:
      summary: Get Finance Active
      description: Get finance active.
      operationId: getApiV1FinanceActive
      x-api-path-slug: apiv1financeactive-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Finance
      - Active
  /api/v1/gigme/artist/searchActive:
    post:
      summary: Post Gigme Artist Searchactive
      description: Post gigme artist searchactive.
      operationId: postApiV1GigmeArtistSearchactive
      x-api-path-slug: apiv1gigmeartistsearchactive-post
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Artist
      - Searchactive
---