---
name: Google Cloud Identity Access Management
x-slug: google-cloud-identity-access-management
description: Google Cloud Identity &amp; Access Management (IAM) lets administrators
  authorize who can take action on specific resources, giving you full control and
  visibility to manage cloud resources centrally. For established enterprises with
  complex organizational structures, hundreds of workgroups and potentially many more
  projects, Cloud IAM provides a unified view into security policy across your entire
  organization, with built-in auditing to ease compliance processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Identity Access Management
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Identity & Access Management API Query Roles
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Queries roles that can be granted on a particular resource.
    A role is grantable if it can be used as the role in a binding for a policy
    for that resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/roles:queryGrantableRoles
  tags: Role
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1rolesquerygrantableroles-post-openapi.md
- name: Google Cloud Identity & Access Management API Delete Service Account Key
  x-api-slug: google-cloud-identity--access-management-api
  description: Deletes a ServiceAccountKey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}
  tags: Service Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-delete-openapi.md
- name: Google Cloud Identity & Access Management API Get Service Account Key
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Gets the ServiceAccountKey
    by key id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}
  tags: Service Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-get-openapi.md
- name: Google Cloud Identity & Access Management API Update Service Account Key
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Updates a ServiceAccount.

    Currently, only the following fields are updatable:
    `display_name` .
    The `etag` is mandatory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}
  tags: Service Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-put-openapi.md
- name: Google Cloud Identity & Access Management API Get Service Account Keys
  x-api-slug: google-cloud-identity--access-management-api
  description: Lists ServiceAccountKeys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}/keys
  tags: Service Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namekeys-get-openapi.md
- name: Google Cloud Identity & Access Management API Create Service Account Key
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Creates a ServiceAccountKey
    and returns it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}/keys
  tags: Service Account Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namekeys-post-openapi.md
- name: Google Cloud Identity & Access Management API Get Service Accounts
  x-api-slug: google-cloud-identity--access-management-api
  description: Lists ServiceAccounts for a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}/serviceAccounts
  tags: Service Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1nameserviceaccounts-get-openapi.md
- name: Google Cloud Identity & Access Management API Create Service Account
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Creates a ServiceAccount
    and returns it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}/serviceAccounts
  tags: Service Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1nameserviceaccounts-post-openapi.md
- name: Google Cloud Identity & Access Management API Sign Blob
  x-api-slug: google-cloud-identity--access-management-api
  description: Signs a blob using a service account's system-managed private key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}:signBlob
  tags: Blob
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namesignblob-post-openapi.md
- name: Google Cloud Identity & Access Management API Sign JWT
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Signs a JWT using a service account's system-managed private key.

    If no expiry time (`exp`) is provided in the `SignJwtRequest`, IAM sets an
    an expiry time of one hour by default. If you request an expiry time of
    more than one hour, the request will fail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{name}:signJwt
  tags: JWT
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namesignjwt-post-openapi.md
- name: Google Cloud Identity & Access Management API Return IAM Access Control Policy
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Returns the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{resource}:getIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcegetiampolicy-post-openapi.md
- name: Google Cloud Identity & Access Management API Set IAM Access Control Policy
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Sets the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{resource}:setIamPolicy
  tags: IAM
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcesetiampolicy-post-openapi.md
- name: Google Cloud Identity & Access Management API Tests Permissions
  x-api-slug: google-cloud-identity--access-management-api
  description: |-
    Tests the specified permissions against the IAM access control policy
    for a ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com////v1/{resource}:testIamPermissions
  tags: Permission
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcetestiampermissions-post-openapi.md
- name: Google Cloud Identity & Access Management API
  x-api-slug: google-cloud-identity--access-management-api
  description: Google Cloud Identity &amp; Access Management (IAM) lets administrators
    authorize who can take action on specific resources, giving you full control and
    visibility to manage cloud resources centrally. For established enterprises with
    complex organizational structures, hundreds of workgroups and potentially many
    more projects, Cloud IAM provides a unified view into security policy across your
    entire organization, with built-in auditing to ease compliance processes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: Google Cloud Identity Access Management
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/openapi.md
x-common:
- type: x-concepts
  url: https://cloud.google.com/iam/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/iam/docs/
- type: x-faq
  url: https://cloud.google.com/iam/docs/faq
- type: x-getting-started
  url: https://cloud.google.com/iam/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/iam/docs/how-to
- type: x-website
  url: https://cloud.google.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---