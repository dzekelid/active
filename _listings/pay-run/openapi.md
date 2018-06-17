---
swagger: "2.0"
x-collection-name: Pay Run
x-complete: 1
info:
  title: Pay Run.IO
  description: open-scableable-transparent-payroll-api-
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Report/ACTPAYINS/run:
    get:
      summary: Runs the active pay instructions report
      description: Returns the result of the executed active pay instructions report
        for the given query parameters
      operationId: GetActivePayInstructionsReportOutput
      x-api-path-slug: reportactpayinsrun-get
      parameters:
      - in: query
        name: ActiveOn
        description: The active date to consider
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: query
        name: EmployeeKey
        description: The employee unique key
      - in: query
        name: EmployerKey
        description: The employer unique key
      - in: query
        name: Type
        description: the data type to filter on
      responses:
        200:
          description: OK
      tags:
      - Runs
      - Active
      - Pay
      - Instructions
      - Report
---