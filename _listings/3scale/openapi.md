swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/api/active_docs/{id}.xml:
    put:
      summary: ActiveDocs JSON Spec Update
      description: Activedocs json spec update.
      operationId: active_docs
      x-api-path-slug: adminapiactive-docsid-xml-put
      parameters:
      - in: query
        name: body
        description: JSON Spec of the ActiveDocs (based on the spec of Swagger)
      - in: path
        name: id
        description: id of the active doc
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - ActiveDocs
      - JSON
      - Spec