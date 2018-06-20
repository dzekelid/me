---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 1
info:
  title: AWS Identity and Access Management API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateAssumeRolePolicy:
    get:
      summary: Update Assume Role Policy
      description: Updates the policy that grants an IAM entity permission to assume
        a role.
      operationId: updateAssumeRolePolicy
      x-api-path-slug: actionupdateassumerolepolicy-get
      parameters:
      - in: query
        name: PolicyDocument
        description: The policy that grants an entity permission to assume the role
        type: string
      - in: query
        name: RoleName
        description: The name of the role to update with the new policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assume Role Policy
---