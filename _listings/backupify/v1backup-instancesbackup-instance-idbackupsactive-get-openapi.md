---
swagger: "2.0"
x-collection-name: Backupify
x-complete: 0
info:
  title: Backupify Retrieve the active backup for the specified backup_instance if
    one exists
  description: Only backups belonging to backup_instances you have permission to access
    can be retrieved
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/backup_instances/{backup_instance_id}/backups/active:
    get:
      summary: Retrieve the active backup for the specified backup_instance if one
        exists
      description: Only backups belonging to backup_instances you have permission
        to access can be retrieved
      operationId: getV1BackupInstancesBackupInstanceBackupsActive
      x-api-path-slug: v1backup-instancesbackup-instance-idbackupsactive-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance the requested backup belongs to
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Backups
      - Active
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