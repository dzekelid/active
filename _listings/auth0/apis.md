---
name: Auth0
x-slug: auth0
description: The new way to solve Identity
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11272-auth0.jpg
x-kinRank: "9"
x-alexaRank: "4820"
tags: Active
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/auth0/apis.md
specificationVersion: "0.14"
apis:
- name: Auth0 Stats API Get Active Users
  x-api-slug: auth0-stats-api
  description: Gets the active users count (logged in during the last 30 days).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11272-auth0.jpg
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com//stats//api/v2/stats/active-users
  tags: Stats,Active,Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/auth0/apiv2statsactiveusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/auth0/apiv2statsactiveusers-get-openapi.md
- name: Auth0 Stats API
  x-api-slug: auth0-stats-api
  description: The new way to solve Identity
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11272-auth0.jpg
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com//stats
  tags: Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/auth0/openapi.md
x-common:
- type: x-blog
  url: https://auth0.com/blog/
- type: x-blog-rss
  url: http://feeds.feedburner.com/auth0
- type: x-crunchbase
  url: https://crunchbase.com/organization/auth0
- type: x-developer
  url: https://auth0.com/docs/apiv2
- type: x-email
  url: privacy@auth0.com
- type: x-email
  url: legal@auth0.com
- type: x-email
  url: ricky@auth0.com
- type: x-github
  url: https://github.com/auth0
- type: x-pricing
  url: https://auth0.com/pricing
- type: x-service-level-agreement
  url: https://auth0.com/docs/sla
- type: x-twitter
  url: https://twitter.com/authzero
- type: x-twitter
  url: https://twitter.com/auth0
- type: x-website
  url: https://auth0.com/
- type: x-website
  url: http://auth0.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---