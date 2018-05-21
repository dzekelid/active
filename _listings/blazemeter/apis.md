---
name: BlazeMeter
x-slug: blazemeter
description: BlazeMeter is a self-service, load testing platform (PaaS) for developers
  providing an enterprise grade, out-of-the-box load testing solution. Start testing
  in under five minutes. BlazeMeter significantly simplifies the load testing process
  by providing developers easy integration into their native development environment.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blaze_meter.png
x-kinRank: "8"
x-alexaRank: ""
tags: Active
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/blazemeter/apis.md
specificationVersion: "0.14"
apis:
- name: Blazemeter Get User Active Sessions
  x-api-slug: blazemeter
  description: Get user active sessions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blaze_meter.png
  humanURL: http://blazemeter.com/
  baseURL: https://a.blazemeter.com//api/v4//user/active/sessions
  tags: Monitoring,User,Active,Sessions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/blazemeter/useractivesessions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/blazemeter/useractivesessions-get-openapi.md
- name: Blazemeter Post User Active Terminate
  x-api-slug: blazemeter
  description: Post user active terminate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blaze_meter.png
  humanURL: http://blazemeter.com/
  baseURL: https://a.blazemeter.com//api/v4//user/active/terminate
  tags: Monitoring,User,Active,Terminate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/blazemeter/useractiveterminate-post-openapi.md
- name: Blazemeter
  x-api-slug: blazemeter
  description: BlazeMeter is a self-service, load testing platform (PaaS) for developers
    providing an enterprise grade, out-of-the-box load testing solution. Start testing
    in under five minutes. BlazeMeter significantly simplifies the load testing process
    by providing developers easy integration into their native development environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/blaze_meter.png
  humanURL: http://blazemeter.com/
  baseURL: https://a.blazemeter.com//api/v4
  tags: Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/blazemeter/openapi.md
x-common:
- type: x-blog
  url: http://blazemeter.com/blog
- type: x-blog-rss
  url: http://feedburner.google.com/fb/a/mailverify?uri=JmeterCloudBlog
- type: x-crunchbase
  url: http://www.crunchbase.com/company/blazemeter
- type: x-github
  url: https://github.com/Blazemeter
- type: x-twitter
  url: https://twitter.com/BlazeMeter
- type: x-website
  url: http://blazemeter.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---