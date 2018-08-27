---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get_active_witnesses
  description: get_active_witnesses
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_active_witnesses:
    get:
      summary: get_active_witnesses
      description: get_active_witnesses
      operationId: get-active-witnesses
      x-api-path-slug: get-active-witnesses-get
      responses:
        200:
          description: OK
      tags:
      - Get
      - Active
      - Witnesses
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