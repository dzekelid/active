swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 1
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateTrust:
    get:
      summary: Create Trust
      description: AWS Directory Service for Microsoft Active Directory allows you
        to configure trust relationships.
      operationId: createTrust
      x-api-path-slug: actioncreatetrust-get
      parameters:
      - in: query
        name: ConditionalForwarderIpAddrs
        description: The IP addresses of the remote DNS server associated with RemoteDomainName
        type: string
      - in: query
        name: DirectoryId
        description: The Directory ID of the Microsoft AD in the AWS cloud for which
          to establish the trust relationship
        type: string
      - in: query
        name: RemoteDomainName
        description: The Fully Qualified Domain Name (FQDN) of the external domain
          for which to create the trust relationship
        type: string
      - in: query
        name: TrustDirection
        description: The direction of the trust relationship
        type: string
      - in: query
        name: TrustPassword
        description: The trust password
        type: string
      - in: query
        name: TrustType
        description: The trust relationship type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust
  /?Action=VerifyTrust:
    get:
      summary: Verify Trust
      description: AWS Directory Service for Microsoft Active Directory allows you
        to configure and verify trust relationships.
      operationId: verifyTrust
      x-api-path-slug: actionverifytrust-get
      parameters:
      - in: query
        name: TrustId
        description: The unique Trust ID of the trust relationship to verify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust