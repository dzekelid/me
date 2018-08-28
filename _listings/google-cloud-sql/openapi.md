---
swagger: "2.0"
x-collection-name: Google Cloud SQL
x-complete: 1
info:
  title: Cloud SQL Administration
  description: creates-and-configures-cloud-sql-instances-which-provide-fullymanaged-mysql-databases-
  contact:
    name: Google
    url: https://google.com
  version: v1beta4
host: www.googleapis.com
basePath: /sql/v1beta4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{project}/instances/{instance}/createEphemeral:
    post:
      summary: Add Projects Project Instances Instance Createephemeral
      description: Generates a short-lived X509 certificate containing the provided
        public key and signed by a private key specific to the target instance. Users
        may use the certificate to authenticate as themselves when connecting to the
        database.
      operationId: sql.sslCerts.createEphemeral
      x-api-path-slug: projectsprojectinstancesinstancecreateephemeral-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: instance
        description: Cloud SQL instance ID
      - in: path
        name: project
        description: Project ID of the Cloud SQL project
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Project
      - Instances
      - Instance
      - Createephemeral
---