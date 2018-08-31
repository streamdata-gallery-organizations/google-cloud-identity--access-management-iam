---
swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 0
info:
  title: Google Cloud Identity & Access Management API Create Service Account
  description: |-
    Creates a ServiceAccount
    and returns it.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: iam.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/roles:queryGrantableRoles:
    post:
      summary: Query Roles
      description: |-
        Queries roles that can be granted on a particular resource.
        A role is grantable if it can be used as the role in a binding for a policy
        for that resource.
      operationId: iam.roles.queryGrantableRoles
      x-api-path-slug: v1rolesquerygrantableroles-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Role
  /v1/{name}:
    delete:
      summary: Delete Service Account Key
      description: Deletes a ServiceAccountKey.
      operationId: iam.projects.serviceAccounts.keys.delete
      x-api-path-slug: v1name-delete
      parameters:
      - in: path
        name: name
        description: The resource name of the service account key in the following
          format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}/keys/{key}`
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
    get:
      summary: Get Service Account Key
      description: |-
        Gets the ServiceAccountKey
        by key id.
      operationId: iam.projects.serviceAccounts.keys.get
      x-api-path-slug: v1name-get
      parameters:
      - in: path
        name: name
        description: The resource name of the service account key in the following
          format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}/keys/{key}`
      - in: query
        name: publicKeyType
        description: The output format of the public key requested
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
    put:
      summary: Update Service Account Key
      description: |-
        Updates a ServiceAccount.

        Currently, only the following fields are updatable:
        `display_name` .
        The `etag` is mandatory.
      operationId: iam.projects.serviceAccounts.update
      x-api-path-slug: v1name-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The resource name of the service account in the following format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}`
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
  /v1/{name}/keys:
    get:
      summary: Get Service Account Keys
      description: Lists ServiceAccountKeys.
      operationId: iam.projects.serviceAccounts.keys.list
      x-api-path-slug: v1namekeys-get
      parameters:
      - in: query
        name: keyTypes
        description: Filters the types of keys the user wants to include in the listresponse
      - in: path
        name: name
        description: The resource name of the service account in the following format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}`
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
    post:
      summary: Create Service Account Key
      description: |-
        Creates a ServiceAccountKey
        and returns it.
      operationId: iam.projects.serviceAccounts.keys.create
      x-api-path-slug: v1namekeys-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The resource name of the service account in the following format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}`
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
  /v1/{name}/serviceAccounts:
    get:
      summary: Get Service Accounts
      description: Lists ServiceAccounts for a project.
      operationId: iam.projects.serviceAccounts.list
      x-api-path-slug: v1nameserviceaccounts-get
      parameters:
      - in: path
        name: name
        description: Required
      - in: query
        name: pageSize
        description: Optional limit on the number of service accounts to include in
          theresponse
      - in: query
        name: pageToken
        description: Optional pagination token returned in an earlierListServiceAccountsResponse
      responses:
        200:
          description: OK
      tags:
      - Service Account
    post:
      summary: Create Service Account
      description: |-
        Creates a ServiceAccount
        and returns it.
      operationId: iam.projects.serviceAccounts.create
      x-api-path-slug: v1nameserviceaccounts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Service Account
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