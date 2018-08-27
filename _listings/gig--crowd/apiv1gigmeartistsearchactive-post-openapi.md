---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Post Gigme Artist Searchactive
  version: 1.0.0
  description: Post gigme artist searchactive.
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