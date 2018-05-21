---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Currencies
  description: provide-realtime-currency-foreign-exchange-information-and-calculations
  version: 1.0.0
host: www.xignite.com/xCurrencies.json
basePath: /XigniteCurrencies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListActiveCurrencies:
    post:
      summary: List Active Currencies
      description: List supported currencies.
      operationId: postListactivecurrencies
      x-api-path-slug: listactivecurrencies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Active
      - Currencies
---