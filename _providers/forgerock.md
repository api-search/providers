---
api_count: 7
api_specs:
- filename: forgerock-identity-cloud-openapi.yml
  format: yaml
  label: ForgeRock Identity Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-cloud-openapi.yml
- filename: forgerock-access-management-openapi.yml
  format: yaml
  label: ForgeRock Access Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-access-management-openapi.yml
- filename: forgerock-identity-management-openapi.yml
  format: yaml
  label: ForgeRock Identity Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-management-openapi.yml
- filename: forgerock-identity-gateway-openapi.yml
  format: yaml
  label: ForgeRock Identity Gateway API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-gateway-openapi.yml
- filename: forgerock-directory-services-openapi.yml
  format: yaml
  label: ForgeRock Directory Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-directory-services-openapi.yml
- filename: forgerock-identity-governance-openapi.yml
  format: yaml
  label: ForgeRock Identity Governance API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-identity-governance-openapi.yml
- filename: forgerock-autonomous-identity-openapi.yml
  format: yaml
  label: ForgeRock Autonomous Identity API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/openapi/forgerock-autonomous-identity-openapi.yml
apis:
- description: REST API for managing identities, authentication, and authorization in ForgeRock Identity Cloud, providing access management and identity management endpoints for Advanced Identity Cloud tenant enviro
  name: ForgeRock Identity Cloud REST API
  slug: ''
- description: API for authentication, authorization, session management, and policy evaluation. Supports OAuth 2.0 and OpenID Connect flows for secure token-based access.
  name: ForgeRock Access Management API
  slug: ''
- description: REST API for CRUD operations on managed objects and identity lifecycle management. Supports provisioning, synchronization, reconciliation, and workflow-driven identity operations.
  name: ForgeRock Identity Management API
  slug: ''
- description: API for reverse proxy functionality, policy enforcement, and request transformation. Integrates web applications, APIs, and microservices with the ForgeRock Identity Platform.
  name: ForgeRock Identity Gateway API
  slug: ''
- description: LDAP and REST API for directory operations and data management. Provides HDAP endpoints for accessing directory data as JSON resources.
  name: ForgeRock Directory Services API
  slug: ''
- description: REST API for identity governance operations including access reviews, certifications, role management, and policy enforcement. Provides endpoints for managing entitlements and compliance workflows.
  name: ForgeRock Identity Governance API
  slug: ''
- description: REST API for the Autonomous Identity analytics platform that uses AI-driven analysis to determine confidence scores, predictions, and recommendations for entitlement assignments.
  name: ForgeRock Autonomous Identity API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://backstage.forgerock.com
- title: ''
  type: Documentation
  url: https://backstage.forgerock.com/docs
- title: ''
  type: Getting Started
  url: https://community.forgerock.com/c/getting-started-guides/36
- title: ''
  type: Authentication
  url: https://backstage.forgerock.com/docs/idcloud/latest/developer-docs/authenticate-to-rest-api-overview.html
- title: ''
  type: Blog
  url: https://www.forgerock.com/blog
- title: ''
  type: Status
  url: https://status.id.forgerock.io
- title: ''
  type: Support
  url: https://backstage.forgerock.com/support
- title: ''
  type: Terms of Service
  url: https://www.forgerock.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.forgerock.com/privacy-policy
- title: ''
  type: GitHub Organization
  url: https://github.com/ForgeRock
- title: ''
  type: Community
  url: https://community.forgerock.com/
- title: ''
  type: Website
  url: https://www.forgerock.com
- title: ''
  type: Login
  url: https://backstage.forgerock.com/account
- title: ''
  type: Sign Up
  url: https://backstage.forgerock.com/account/register
- title: ''
  type: SDKs
  url: https://docs.pingidentity.com/sdks/latest/index.html
- title: ''
  type: JSON-LD Context
  url: json-ld/forgerock-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-managed-user-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-session-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-policy-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-oauth2-token-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-managed-role-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-entitlement-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/forgerock-directory-entry-schema.json
created: '2024'
description: ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.
features: []
image: https://www.forgerock.com/themes/custom/forgerock/logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Forgerock Context
  property_count: 11
  slug: forgerock-context
layout: provider
modified: '2026-04-28'
name: ForgeRock
skills: []
slug: forgerock
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "specificationVersion: '0.18'\nname: ForgeRock\ndescription: ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.\nurl: https://www.forgerock.com\ntype: Index\nimage: https://www.forgerock.com/themes/custom/forgerock/logo.svg\ntags:\n  - Access Management\n  - Authentication\n  - Authorization\n  - Identity Governance\n  - Identity Management\n  - OAuth\n  - OpenID Connect\ncreated: '2024'\nmodified: '2026-04-28'\napis:\n  - name: ForgeRock Identity Cloud REST API\n    description: REST API for managing identities, authentication, and authorization in ForgeRock Identity Cloud, providing access management and identity management endpoints for Advanced Identity Cloud tenant environments.\n    baseURL: https://{tenant}.forgeblocks.com\n    humanURL: https://backstage.forgerock.com/docs/idcloud/latest\n    tags:\n      - Access Management\n\
  \      - Authentication\n      - Cloud\n      - Identity\n      - REST\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/idcloud/latest/\n      - type: OpenAPI\n        url: openapi/forgerock-identity-cloud-openapi.yml\n      - type: OpenAPI\n        url: https://backstage.forgerock.com/docs/idcloud/latest/openapi/\n      - type: API Reference\n        url: https://apidocs.id.forgerock.io/\n      - type: Getting Started\n        url: https://backstage.forgerock.com/docs/idcloud/latest/home.html\n      - type: Authentication\n        url: https://backstage.forgerock.com/docs/idcloud/latest/developer-docs/authenticate-to-rest-api-overview.html\n      - type: SDKs\n        url: https://backstage.forgerock.com/docs/idcloud/latest/end-user/sdks.html\n  - name: ForgeRock Access Management API\n    description: API for authentication, authorization, session management, and policy evaluation. Supports OAuth 2.0 and OpenID Connect flows for secure\
  \ token-based access.\n    baseURL: https://{deployment}/am\n    humanURL: https://backstage.forgerock.com/docs/am/7.3\n    tags:\n      - Access Management\n      - Authentication\n      - Authorization\n      - OAuth\n      - Sessions\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/am/7.3/\n      - type: OpenAPI\n        url: openapi/forgerock-access-management-openapi.yml\n      - type: API Reference\n        url: https://backstage.forgerock.com/docs/am/7.3/apidocs/\n      - type: Authentication\n        url: https://backstage.forgerock.com/docs/am/7/authentication-guide/\n      - type: Getting Started\n        url: https://backstage.forgerock.com/docs/am/7.1/REST-guide/basic-rest-authentication.html\n      - type: Change Log\n        url: https://backstage.forgerock.com/docs/am/7/release-notes/\n  - name: ForgeRock Identity Management API\n    description: REST API for CRUD operations on managed objects and identity lifecycle management.\
  \ Supports provisioning, synchronization, reconciliation, and workflow-driven identity operations.\n    baseURL: https://{deployment}/openidm\n    humanURL: https://backstage.forgerock.com/docs/idm/7.4\n    tags:\n      - Identity Management\n      - Lifecycle Management\n      - Provisioning\n      - Synchronization\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/idm/7.4/\n      - type: OpenAPI\n        url: openapi/forgerock-identity-management-openapi.yml\n      - type: REST API Guide\n        url: https://backstage.forgerock.com/docs/idm/7.4/rest-api-reference/\n      - type: Getting Started\n        url: https://backstage.forgerock.com/docs/idm/7.4/getting-started/\n      - type: Change Log\n        url: https://backstage.forgerock.com/docs/idm/7.4/release-notes/preface.html\n  - name: ForgeRock Identity Gateway API\n    description: API for reverse proxy functionality, policy enforcement, and request transformation. Integrates web\
  \ applications, APIs, and microservices with the ForgeRock Identity Platform.\n    baseURL: https://{deployment}/ig\n    humanURL: https://backstage.forgerock.com/docs/ig/7.3\n    tags:\n      - API Security\n      - Gateway\n      - Policy Enforcement\n      - Reverse Proxy\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/ig/7.3/\n      - type: OpenAPI\n        url: openapi/forgerock-identity-gateway-openapi.yml\n      - type: Reference\n        url: https://backstage.forgerock.com/docs/ig/7.3/reference/\n      - type: Getting Started\n        url: https://backstage.forgerock.com/docs/ig/7/gateway-guide/\n  - name: ForgeRock Directory Services API\n    description: LDAP and REST API for directory operations and data management. Provides HDAP endpoints for accessing directory data as JSON resources.\n    baseURL: https://{deployment}/ds\n    humanURL: https://backstage.forgerock.com/docs/ds/7.4\n    tags:\n      - Data Storage\n      - Directory\n\
  \      - HDAP\n      - LDAP\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/ds/7.4/\n      - type: OpenAPI\n        url: openapi/forgerock-directory-services-openapi.yml\n      - type: REST API\n        url: https://backstage.forgerock.com/docs/ds/7.4/rest-guide/\n      - type: Getting Started\n        url: https://backstage.forgerock.com/docs/ds/7.4/getting-started/rest.html\n      - type: Reference\n        url: https://backstage.forgerock.com/docs/ds/7.4/rest-guide/rest-operations.html\n  - name: ForgeRock Identity Governance API\n    description: REST API for identity governance operations including access reviews, certifications, role management, and policy enforcement. Provides endpoints for managing entitlements and compliance workflows.\n    baseURL: https://{deployment}/iga\n    humanURL: https://backstage.forgerock.com/docs/identity-governance/7.1/api-guide/preface.html\n    tags:\n      - Access Reviews\n      - Compliance\n \
  \     - Entitlements\n      - Identity Governance\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/identity-governance/7.1/api-guide/preface.html\n      - type: OpenAPI\n        url: openapi/forgerock-identity-governance-openapi.yml\n      - type: API Reference\n        url: https://backstage.forgerock.com/docs/idcloud/latest/identity-governance/rest-api/endpoints/rest-iga.html\n  - name: ForgeRock Autonomous Identity API\n    description: REST API for the Autonomous Identity analytics platform that uses AI-driven analysis to determine confidence scores, predictions, and recommendations for entitlement assignments.\n    baseURL: https://{deployment}/autoid\n    humanURL: https://backstage.forgerock.com/docs/autonomous-identity/2022.11.0/api-guide/preface.html\n    tags:\n      - Analytics\n      - Artificial Intelligence\n      - Autonomous Identity\n      - Entitlements\n    properties:\n      - type: Documentation\n        url: https://backstage.forgerock.com/docs/autonomous-identity/2022.11.0/api-guide/preface.html\n\
  \      - type: OpenAPI\n        url: openapi/forgerock-autonomous-identity-openapi.yml\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://backstage.forgerock.com\n  - type: Documentation\n    url: https://backstage.forgerock.com/docs\n  - type: Getting Started\n    url: https://community.forgerock.com/c/getting-started-guides/36\n  - type: Authentication\n    url: https://backstage.forgerock.com/docs/idcloud/latest/developer-docs/authenticate-to-rest-api-overview.html\n  - type: Blog\n    url: https://www.forgerock.com/blog\n  - type: Status\n    url: https://status.id.forgerock.io\n  - type: Support\n    url: https://backstage.forgerock.com/support\n  - type: Terms of Service\n    url: https://www.forgerock.com/terms\n  - type: Privacy Policy\n    url: https://www.forgerock.com/privacy-policy\n  - type: GitHub Organization\n    url: https://github.com/ForgeRock\n  - type: Community\n    url:\
  \ https://community.forgerock.com/\n  - type: Website\n    url: https://www.forgerock.com\n  - type: Login\n    url: https://backstage.forgerock.com/account\n  - type: Sign Up\n    url: https://backstage.forgerock.com/account/register\n  - type: SDKs\n    url: https://docs.pingidentity.com/sdks/latest/index.html\n  - type: JSON-LD Context\n    url: json-ld/forgerock-context.jsonld\n  - type: JSON Schema\n    url: json-schema/forgerock-managed-user-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-session-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-policy-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-oauth2-token-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-managed-role-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-entitlement-schema.json\n  - type: JSON Schema\n    url: json-schema/forgerock-directory-entry-schema.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/forgerock/refs/heads/main/apis.yml
tags:
- Access Management
- Authentication
- Authorization
- Identity Governance
- Identity Management
- OAuth
- OpenID Connect
url: https://www.forgerock.com
use_cases: []
---
