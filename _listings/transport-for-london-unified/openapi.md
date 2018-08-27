swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 1
info:
  title: Transport for London Unified
  description: our-unified-api-brings-together-data-across-all-modes-of-transport-into-a-single-restful-api--this-api-provides-access-to-the-most-highly-requested-realtime-and-status-infomation-across-all-the-modes-of-transport-in-a-single-and-consistent-way--access-to-the-developer-documentation-is-available-at-httpsapi-tfl-gov-uk
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Mode/ActiveServiceTypes:
    get:
      summary: Mode  Active Service Types
      description: "Returns the service type active for a mode.\r\n            currently
        only supports tube."
      operationId: Mode_GetActiveServiceTypes
      x-api-path-slug: modeactiveservicetypes-get
      responses:
        200:
          description: OK
      tags:
      - Mode
      - ""
      - Active
      - Service
      - Types