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
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: Google Identity and Access Management (IAM) - Query Roles
  x-api-slug: v1rolesquerygrantableroles-post
  description: |-
    Queries roles that can be granted on a particular resource.
    A role is grantable if it can be used as the role in a binding for a policy
    for that resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1rolesquerygrantableroles-post-openapi.md
- name: Google Identity and Access Management (IAM) - Delete Service Account Key
  x-api-slug: v1name-delete
  description: Deletes a ServiceAccountKey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-delete-openapi.md
- name: Google Identity and Access Management (IAM) - Get Service Account Key
  x-api-slug: v1name-get
  description: |-
    Gets the ServiceAccountKey
    by key id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-get-openapi.md
- name: Google Identity and Access Management (IAM) - Update Service Account Key
  x-api-slug: v1name-put
  description: |-
    Updates a ServiceAccount.

    Currently, only the following fields are updatable:
    `display_name` .
    The `etag` is mandatory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1name-put-openapi.md
- name: Google Identity and Access Management (IAM) - Get Service Account Keys
  x-api-slug: v1namekeys-get
  description: Lists ServiceAccountKeys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namekeys-get-openapi.md
- name: Google Identity and Access Management (IAM) - Create Service Account Key
  x-api-slug: v1namekeys-post
  description: |-
    Creates a ServiceAccountKey
    and returns it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namekeys-post-openapi.md
- name: Google Identity and Access Management (IAM) - Get Service Accounts
  x-api-slug: v1nameserviceaccounts-get
  description: Lists ServiceAccounts for a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1nameserviceaccounts-get-openapi.md
- name: Google Identity and Access Management (IAM) - Create Service Account
  x-api-slug: v1nameserviceaccounts-post
  description: |-
    Creates a ServiceAccount
    and returns it.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1nameserviceaccounts-post-openapi.md
- name: Google Identity and Access Management (IAM) - Sign Blob
  x-api-slug: v1namesignblob-post
  description: Signs a blob using a service account's system-managed private key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namesignblob-post-openapi.md
- name: Google Identity and Access Management (IAM) - Sign JWT
  x-api-slug: v1namesignjwt-post
  description: |-
    Signs a JWT using a service account's system-managed private key.

    If no expiry time (`exp`) is provided in the `SignJwtRequest`, IAM sets an
    an expiry time of one hour by default. If you request an expiry time of
    more than one hour, the request will fail.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1namesignjwt-post-openapi.md
- name: Google Identity and Access Management (IAM) - Return IAM Access Control Policy
  x-api-slug: v1resourcegetiampolicy-post
  description: |-
    Returns the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcegetiampolicy-post-openapi.md
- name: Google Identity and Access Management (IAM) - Set IAM Access Control Policy
  x-api-slug: v1resourcesetiampolicy-post
  description: |-
    Sets the IAM access control policy for a
    ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcesetiampolicy-post-openapi.md
- name: Google Identity and Access Management (IAM) - Tests Permissions
  x-api-slug: v1resourcetestiampermissions-post
  description: |-
    Tests the specified permissions against the IAM access control policy
    for a ServiceAccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/right-roles.png
  humanURL: https://cloud.google.com/iam/
  baseURL: ://iam.googleapis.com//
  tags: IAM, Authentication, Google APIs, Stack Network, API Service Provider, API
    Provider, Identities, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-identity-access-management/master/_listings/google-cloud-identity-access-management/v1resourcetestiampermissions-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.functions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.identity.access.management.stack.network
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