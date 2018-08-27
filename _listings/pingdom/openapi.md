swagger: "2.0"
x-collection-name: Pingdom
x-complete: 1
info:
  title: Traceroute API
  description: the-traceroute-api-
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.pingdom.com
basePath: /
paths:
  ? |2-

        /api/{version}/summary.probes/{checkid}
  : ? |2-

          get
    : summary: Get Active Probes For A Period
      description: Get a list of probes that performed tests for a specified check
        during a specified period.
      operationId: get-active-probes-for-a-period
      x-api-path-slug: apiversionsummary-probescheckid-get
      parameters:
      - in: query
        name: from
        description: Start time of period
        type: <td>integer</td>
      - in: query
        name: to
        description: End time of period
        type: <td>integer</td>
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
      tags:
      - Summary