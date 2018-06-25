---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Active
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify Retrieve the active backup for the specified backup_instance if
    one exists
  x-api-slug: backupify
  description: Only backups belonging to backup_instances you have permission to access
    can be retrieved
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/backups/active
  tags: V1,Backup,Instances,Backup,Instance,Id,Backups,Active
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsactive-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/backupify/v1backup-instancesbackup-instance-idbackupsactive-get-openapi.md
- name: Backupify
  x-api-slug: backupify
  description: 'Backupify is a backup service for SaaS accounts. Backupify can help
    users backup their SaaS accounts and restore if and when needed. Backupify offers
    a developers program for developers to access and integrate the functionality
    of Backupify with other applications. Public documentation is not available; interested
    developers should sign up here for more information on the developers program:
    https://www.backupify.com/solutions/developers or email developerprogram@backupify.com.'
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: Active
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/active/master/_listings/backupify/openapi.md
x-common:
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---