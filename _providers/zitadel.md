---
api_count: 5
api_specs:
- filename: zitadel-management-openapi.yml
  format: yaml
  label: Zitadel Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/openapi/zitadel-management-openapi.yml
apis:
- description: The Zitadel Management API provides administrative operations for managing users, organizations, projects, applications, roles, policies, and identity providers within a Zitadel instance. Accessible v
  name: Zitadel Management API
  slug: management-api
- description: The Zitadel Auth API provides endpoints for authenticated users to perform operations on their own accounts, including profile management, session handling, MFA setup, and personal data management. Ac
  name: Zitadel Auth API
  slug: auth-api
- description: The Zitadel Admin API provides instance-level configuration for Zitadel administrators. Used to configure instance-wide settings, default policies, SMTP, SMS providers, and manage identity providers a
  name: Zitadel Admin API
  slug: admin-api
- description: Zitadel implements the OpenID Connect and OAuth 2.0 standards for authentication and authorization flows. Provides authorization code flow, client credentials, device code, token introspection, and us
  name: Zitadel OIDC / OAuth 2.0
  slug: oidc-oauth
- description: Zitadel provides SAML 2.0 single sign-on support, enabling enterprises to integrate with Zitadel using SAML identity federation. Accessible at /saml/v2/.
  name: Zitadel SAML API
  slug: saml-api
capabilities:
- description: 'A workflow capability for an Identity Administrator onboarding new organizations, projects, applications, and human users into Zitadel. Combines Zitadel Management operations to automate provisioning '
  name: Identity Onboarding
  slug: identity-onboarding
common:
- title: ''
  type: Website
  url: https://zitadel.com
- title: ''
  type: Documentation
  url: https://zitadel.com/docs
- title: ''
  type: GitHubOrganization
  url: https://github.com/zitadel
- title: ''
  type: SDK
  url: https://github.com/zitadel/zitadel-go
- title: ''
  type: SDK
  url: https://github.com/zitadel/zitadel-java
- title: ''
  type: Tools
  url: https://github.com/zitadel/terraform-provider-zitadel
- title: ''
  type: Tools
  url: https://github.com/zitadel/zitadel-charts
- title: ''
  type: SignUp
  url: https://zitadel.cloud/ui/register
- title: ''
  type: Pricing
  url: https://zitadel.com/pricing
- title: ''
  type: PrivacyPolicy
  url: https://zitadel.com/legal/privacy-policy
- title: ''
  type: TermsOfService
  url: https://zitadel.com/legal/terms-of-service
- title: ''
  type: License
  url: https://github.com/zitadel/zitadel/blob/main/LICENSE
- title: ''
  type: JSONLD
  url: json-ld/zitadel-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/zitadel-spectral.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/identity-onboarding.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/zitadel-vocabulary.yaml
created: '2026-03-25'
description: Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained authorization, and a comprehensive management API for building and operating identity-first applications. Available as cloud-hosted and self-hosted deployments.
features:
- description: Native multi-tenant architecture with organizations and projects.
  name: Multi-Tenancy
- description: Standards-compliant OAuth 2.0 and OpenID Connect support.
  name: OAuth 2.0 / OIDC
- description: Enterprise SAML 2.0 single sign-on for identity federation.
  name: SAML 2.0
- description: SCIM-based user provisioning from upstream identity providers.
  name: SCIM
- description: Passwordless authentication with FIDO2 and passkeys.
  name: FIDO2 / Passkeys
- description: Multi-factor authentication including TOTP, U2F, and FIDO2.
  name: MFA
- description: Deploy as a managed cloud service or self-hosted on Kubernetes.
  name: Self-Hosted or Cloud
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Terraform provider for declarative Zitadel resource management.
  name: Terraform
- description: Helm charts for Zitadel deployment on Kubernetes.
  name: Kubernetes
- description: External identity provider integration with Google.
  name: Google Login
- description: External identity provider integration with GitHub.
  name: GitHub Login
- description: Federation with SAML identity providers.
  name: SAML IdPs
jsonld:
- class_count: 6
  name: Zitadel Context
  property_count: 15
  slug: zitadel-context
layout: provider
modified: '2026-05-03'
name: Zitadel
rules:
- name: Zitadel API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: zitadel-spectral
skills: []
slug: zitadel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zitadel\nname: Zitadel\ndescription: >-\n  Zitadel is an open source identity infrastructure platform providing secure\n  authentication and user management with built-in support for OAuth 2.0, OpenID\n  Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained\n  authorization, and a comprehensive management API for building and operating\n  identity-first applications. Available as cloud-hosted and self-hosted deployments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Authorization\n  - Identity Management\n  - Open Source\n  - OAuth 2.0\n  - OIDC\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zitadel:management-api\n    name: Zitadel Management API\n    description: >-\n      The Zitadel Management API provides administrative\
  \ operations for managing\n      users, organizations, projects, applications, roles, policies, and identity\n      providers within a Zitadel instance. Accessible via REST at /management/v1/\n      and via gRPC. Supports comprehensive CRUD operations for all identity\n      management resources.\n    humanURL: https://zitadel.com/docs/reference/api/management\n    tags:\n      - Identity Management\n      - Authentication\n      - User Management\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://zitadel.com/docs/reference/api/management\n      - type: GitHubRepository\n        url: https://github.com/zitadel/zitadel\n      - type: OpenAPI\n        url: openapi/zitadel-management-openapi.yml\n      - type: JSONSchema\n        url: json-schema/zitadel-management-user-schema.json\n      - type: JSONSchema\n        url: json-schema/zitadel-management-human-user-schema.json\n      - type: JSONSchema\n        url: json-schema/zitadel-management-machine-user-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/zitadel-management-organization-schema.json\n      - type: JSONSchema\n        url: json-schema/zitadel-management-project-schema.json\n      - type: JSONSchema\n        url: json-schema/zitadel-management-application-schema.json\n      - type: JSONSchema\n        url: json-schema/zitadel-management-object-details-schema.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-user-structure.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-human-user-structure.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-machine-user-structure.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-organization-structure.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-project-structure.json\n      - type: JSONStructure\n        url: json-structure/zitadel-management-application-structure.json\n    \
  \  - type: Example\n        url: examples/zitadel-management-list-users-example.json\n      - type: Example\n        url: examples/zitadel-management-create-human-user-example.json\n      - type: Example\n        url: examples/zitadel-management-create-organization-example.json\n      - type: Example\n        url: examples/zitadel-management-create-project-example.json\n  - aid: zitadel:auth-api\n    name: Zitadel Auth API\n    description: >-\n      The Zitadel Auth API provides endpoints for authenticated users to perform\n      operations on their own accounts, including profile management, session\n      handling, MFA setup, and personal data management. Accessible at /auth/v1/.\n    humanURL: https://zitadel.com/docs/apis/introduction\n    tags:\n      - Authentication\n      - User Profile\n      - Session Management\n      - MFA\n    properties:\n      - type: Documentation\n        url: https://zitadel.com/docs/apis/introduction\n  - aid: zitadel:admin-api\n    name: Zitadel Admin\
  \ API\n    description: >-\n      The Zitadel Admin API provides instance-level configuration for Zitadel\n      administrators. Used to configure instance-wide settings, default policies,\n      SMTP, SMS providers, and manage identity providers at the system level.\n      Accessible at /admin/v1/.\n    humanURL: https://zitadel.com/docs/apis/introduction\n    tags:\n      - Administration\n      - Identity Management\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://zitadel.com/docs/apis/introduction\n  - aid: zitadel:oidc-oauth\n    name: Zitadel OIDC / OAuth 2.0\n    description: >-\n      Zitadel implements the OpenID Connect and OAuth 2.0 standards for authentication\n      and authorization flows. Provides authorization code flow, client credentials,\n      device code, token introspection, and userinfo endpoints. Available at\n      /oauth/v2/ and /oidc/v1/.\n    humanURL: https://zitadel.com/docs/guides/integrate/login/oidc\n    tags:\n\
  \      - OAuth 2.0\n      - OpenID Connect\n      - Authentication\n      - Authorization\n    properties:\n      - type: Documentation\n        url: https://zitadel.com/docs/guides/integrate/login/oidc\n  - aid: zitadel:saml-api\n    name: Zitadel SAML API\n    description: >-\n      Zitadel provides SAML 2.0 single sign-on support, enabling enterprises to\n      integrate with Zitadel using SAML identity federation. Accessible at /saml/v2/.\n    humanURL: https://zitadel.com/docs/guides/integrate/login/saml\n    tags:\n      - SAML\n      - Single Sign-On\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://zitadel.com/docs/guides/integrate/login/saml\ncommon:\n  - type: Website\n    url: https://zitadel.com\n  - type: Documentation\n    url: https://zitadel.com/docs\n  - type: GitHubOrganization\n    url: https://github.com/zitadel\n  - type: SDK\n    url: https://github.com/zitadel/zitadel-go\n    name: zitadel-go (Go)\n  - type: SDK\n    url:\
  \ https://github.com/zitadel/zitadel-java\n    name: zitadel-java (Java)\n  - type: Tools\n    url: https://github.com/zitadel/terraform-provider-zitadel\n    name: Terraform Provider for Zitadel\n  - type: Tools\n    url: https://github.com/zitadel/zitadel-charts\n    name: Zitadel Helm Charts\n  - type: SignUp\n    url: https://zitadel.cloud/ui/register\n  - type: Pricing\n    url: https://zitadel.com/pricing\n  - type: PrivacyPolicy\n    url: https://zitadel.com/legal/privacy-policy\n  - type: TermsOfService\n    url: https://zitadel.com/legal/terms-of-service\n  - type: License\n    url: https://github.com/zitadel/zitadel/blob/main/LICENSE\n    name: GNU AGPLv3\n  - type: JSONLD\n    url: json-ld/zitadel-context.jsonld\n  - type: SpectralRules\n    url: rules/zitadel-spectral.yaml\n  - type: NaftikoCapability\n    url: capabilities/identity-onboarding.yaml\n  - type: Vocabulary\n    url: vocabulary/zitadel-vocabulary.yaml\n  - data:\n      - name: Multi-Tenancy\n        description:\
  \ Native multi-tenant architecture with organizations and projects.\n      - name: OAuth 2.0 / OIDC\n        description: Standards-compliant OAuth 2.0 and OpenID Connect support.\n      - name: SAML 2.0\n        description: Enterprise SAML 2.0 single sign-on for identity federation.\n      - name: SCIM\n        description: SCIM-based user provisioning from upstream identity providers.\n      - name: FIDO2 / Passkeys\n        description: Passwordless authentication with FIDO2 and passkeys.\n      - name: MFA\n        description: Multi-factor authentication including TOTP, U2F, and FIDO2.\n      - name: Self-Hosted or Cloud\n        description: Deploy as a managed cloud service or self-hosted on Kubernetes.\n    name: Features\n    type: Features\n  - data:\n      - name: Customer Identity\n        description: B2C identity for customer-facing applications and portals.\n      - name: Workforce Identity\n        description: B2B/B2E identity for employees, contractors, and partners.\n\
  \      - name: Machine Identity\n        description: Service account identity and OAuth client credentials flow.\n      - name: SaaS Multi-Tenancy\n        description: Tenant-isolated identity for multi-tenant SaaS applications.\n    name: UseCases\n    type: UseCases\n  - data:\n      - name: Terraform\n        description: Terraform provider for declarative Zitadel resource management.\n      - name: Kubernetes\n        description: Helm charts for Zitadel deployment on Kubernetes.\n      - name: Google Login\n        description: External identity provider integration with Google.\n      - name: GitHub Login\n        description: External identity provider integration with GitHub.\n      - name: SAML IdPs\n        description: Federation with SAML identity providers.\n    name: Integrations\n    type: Integrations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity Management
- Open Source
- OAuth 2.0
- OIDC
url: https://raw.githubusercontent.com/api-evangelist/zitadel/refs/heads/main/apis.yml
use_cases:
- description: B2C identity for customer-facing applications and portals.
  name: Customer Identity
- description: B2B/B2E identity for employees, contractors, and partners.
  name: Workforce Identity
- description: Service account identity and OAuth client credentials flow.
  name: Machine Identity
- description: Tenant-isolated identity for multi-tenant SaaS applications.
  name: SaaS Multi-Tenancy
---
