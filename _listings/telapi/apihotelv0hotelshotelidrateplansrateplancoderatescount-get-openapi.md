---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 0
info:
  title: hetras Hotel API Version 0 Get the count of all active and loaded daily rates
    for the defined rateplan in a specified time period.
  version: v0
  description: Get the count of all active and loaded daily rates for the defined
    rateplan in a specified time period..
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates/$count:
    get:
      summary: Get the count of all active and loaded daily rates for the defined
        rateplan in a specified time period.
      description: Get the count of all active and loaded daily rates for the defined
        rateplan in a specified time period..
      operationId: RatePlans_GetRatesCount
      x-api-path-slug: apihotelv0hotelshotelidrateplansrateplancoderatescount-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: query
        name: from
        description: Defines the last business day you would like to get rates for
      - in: path
        name: hotelId
        description: The hotel id the rateplan belongs to
      - in: path
        name: rateplanCode
        description: The code of the rateplan you want to count daily rates for
      - in: query
        name: to
        description: Defines the first business day you would like to get rates for
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        200:
          description: OK
      tags:
      - Count
      - Of
      - ""
      - Active
      - Loaded
      - Daily
      - Ratesthe
      - Defined
      - Rateplan
      - In
      - Specified
      - Time
      - Period
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