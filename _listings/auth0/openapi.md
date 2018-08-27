swagger: "2.0"
x-collection-name: Auth0
x-complete: 1
info:
  title: Auth0 Users API
  version: v1
host: login.auth0.com
basePath: /users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v2/stats/active-users:
    get:
      summary: Get Active Users
      description: Gets the active users count (logged in during the last 30 days).
      operationId: get_active-users
      x-api-path-slug: apiv2statsactiveusers-get
      responses:
        200:
          description: OK
      tags:
      - Stats
      - Active
      - Users