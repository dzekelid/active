---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Sets members Active/Inactive system status
  version: 1.0.0
  description: Sets members active/inactive system status.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/branch/updatescheduledtaskstatus/{id}:
    post:
      summary: Update SystemStatus of ScheduledTask to Active, Inactive, Deleted or
        Archived.
      description: Update systemstatus of scheduledtask to active, inactive, deleted
        or archived..
      operationId: Branch_UpdateScheduledTaskStatusByidBysystemStatus
      x-api-path-slug: apibranchupdatescheduledtaskstatusid-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: systemStatus
      responses:
        200:
          description: OK
      tags:
      - SystemStatus
      - Of
      - ScheduledTask
      - To
      - Active
      - ""
      - Inactive
      - ""
      - D
      - Archived
  /api/todo/activetasks:
    get:
      summary: Get the list of active tasks of a Todo
      description: Get the list of active tasks of a todo.
      operationId: DefaultToDo_ActiveTasksBytoDoIdByignoreDueDateBypageSizeBypageNumber
      x-api-path-slug: apitodoactivetasks-get
      parameters:
      - in: query
        name: ignoreDueDate
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: toDoId
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Active
      - Tasks
      - Of
      - Todo
  /api/enlistedfeature/getvalidforagency:
    get:
      summary: Gets all the active features for an agency
      description: Gets all the active features for an agency.
      operationId: EnlistedFeature_GetAllValidEnlistedFeaturesForAgency
      x-api-path-slug: apienlistedfeaturegetvalidforagency-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Active
      - Featuresan
      - Agency
  /api/group/{id}/setgroupmemberstatus:
    put:
      summary: Sets members Active/Inactive system status
      description: Sets members active/inactive system status.
      operationId: Group_SetGroupMemberStatusByidBygroupMemberStatusDataContract
      x-api-path-slug: apigroupidsetgroupmemberstatus-put
      parameters:
      - in: body
        name: groupMemberStatusDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Members
      - Active
      - Inactive
      - System
      - Status
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