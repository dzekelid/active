---
swagger: "2.0"
x-collection-name: Steem
x-complete: 1
info:
  title: Interactive Steem API
  description: interactive-steem-api-lets-you-interact-with-steem-blockchain-and-make-a-request-get-output-and-start-implementing-new-apps-apis-have-default-parameters-set-to-get-you-started-and-see-how-request-works--api-list-is-compiled-from-steem-githubhttpsgithub-comsteemitsteem-1httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappapi-hpp-and-2httpsgithub-comsteemitsteemtreemasterlibrariesappincludesteemitappdatabase-api-hpp--if-you-want-to-contribute-documenting-detail-of-properties-and-output-contact-goodkarmahttpssteemit-chatdirectgoodkarma--you-can-also-check-full-list-here-steem-jshttpssteemjs-com
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
  /get_active_categories:
    get:
      summary: get active categories
      description: get tags
      operationId: get-tags
      x-api-path-slug: get-active-categories-get
      parameters:
      - in: query
        name: after
        description: after string
      - in: query
        name: limit
        description: limit size
      responses:
        200:
          description: OK
      tags:
      - Get
      - Active
      - Categories
  /get_active_votes:
    get:
      summary: get_active_votes
      description: get_active_votes
      operationId: get-active-votes
      x-api-path-slug: get-active-votes-get
      parameters:
      - in: query
        name: author
        description: account name
      - in: query
        name: permlink
        description: permlink of post
      responses:
        200:
          description: OK
      tags:
      - Get
      - Active
      - Votes
---