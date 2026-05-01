---
api_count: 1
api_specs:
- filename: schema_retrieve
  format: yaml
  label: Authentik REST API
  slug: authentik-rest-api
  spec_type: OpenAPI
  url: https://api.goauthentik.io/#/Schema/schema_retrieve
apis:
- description: The authentik REST API v3 provides complete management of the authentik identity platform including users, groups, tokens, flows, providers, sources, policies, outposts, events, and configuration. Eve
  name: Authentik REST API
  slug: authentik-rest-api
common:
- title: ''
  type: Website
  url: https://goauthentik.io
- title: ''
  type: Documentation
  url: https://docs.goauthentik.io
- title: ''
  type: GitHubOrganization
  url: https://github.com/goauthentik
- title: ''
  type: GitHubRepository
  url: https://github.com/goauthentik/authentik
- title: ''
  type: ChangeLog
  url: https://github.com/goauthentik/authentik/releases
- title: ''
  type: Support
  url: https://github.com/goauthentik/authentik/discussions
- title: ''
  type: Community
  url: https://discord.gg/jg33eMhnj6
- title: ''
  type: Pricing
  url: https://goauthentik.io/pricing
created: '2026-03-25'
description: Authentik is an open source identity provider with a comprehensive REST API for managing users, groups, flows, providers, sources, policies, and outposts. It supports OAuth2, OIDC, SAML, LDAP, SCIM, and RADIUS protocols with official client SDKs in TypeScript, Python, Go, Rust, Kotlin, and Swift.
features:
- description: Full REST API covering all authentik features with built-in Swagger UI at /api/v3/ on every instance.
  name: Comprehensive REST API
- description: Native support for OAuth2, OIDC, SAML, LDAP, SCIM, RADIUS, and SSTP protocols for broad integration coverage.
  name: Multi-Protocol Support
- description: Customizable authentication and enrollment flows with visual flow designer for configuring multi-step authentication processes.
  name: Flow Engine
- description: Official API client SDKs in TypeScript, Python, Go, Rust, Kotlin, and Swift auto-generated from the OpenAPI schema.
  name: Multi-Language SDKs
- description: Official Terraform provider for infrastructure-as-code management of authentik resources.
  name: Terraform Provider
- description: Official Helm chart for Kubernetes deployment with configurable replicas, persistence, and external database support.
  name: Helm Deployment
- description: Role-based access control for granular permission management across authentik resources and administrative functions.
  name: RBAC
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Forward auth integration with major reverse proxies for transparent application authentication.
  name: Nginx/Traefik/Caddy
- description: Native Kubernetes deployment via Helm chart with optional operator and RBAC integration.
  name: Kubernetes
- description: LDAP outpost that exposes authentik users to LDAP-compatible applications without a directory server.
  name: LDAP Directory
- description: Native OAuth2 integration with Grafana for unified authentication in monitoring stacks.
  name: Grafana
- description: OIDC or SAML integration with Nextcloud for unified login in self-hosted file storage.
  name: Nextcloud
layout: provider
modified: '2026-04-19'
name: Authentik
skills: []
slug: authentik
solutions:
- description: Complete identity and access management platform deployable on any infrastructure with no vendor lock-in.
  name: Self-Hosted IAM
- description: Secure and authenticate any application using forward auth with optional MFA and per-user access policies.
  name: Application Gateway
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: authentik\nname: Authentik\ndescription: |\n  Authentik is an open source identity provider with a comprehensive REST API for managing users, groups, flows, providers, sources, policies, and outposts. It supports OAuth2, OIDC, SAML, LDAP, SCIM, and RADIUS protocols with official client SDKs in TypeScript, Python, Go, Rust, Kotlin, and Swift.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authentication\n- Authorization\n- Identity Provider\n- LDAP\n- OAuth\n- Open Source\n- OpenID Connect\n- SAML\n- SCIM\n- Self-Hosted\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/authentik/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: authentik:authentik-rest-api\n  name: Authentik REST API\n  description: |\n    The authentik REST API v3 provides complete management of the authentik identity platform including users, groups, tokens, flows, providers,\
  \ sources, policies, outposts, events, and configuration. Every authentik instance includes a built-in API browser at /api/v3/.\n  humanURL: https://api.goauthentik.io/\n  baseURL: https://your-authentik-instance.example.com/api/v3\n  tags:\n  - Authentication\n  - Identity\n  - REST\n  - Users\n  properties:\n  - type: Documentation\n    url: https://docs.goauthentik.io/developer-docs/api/\n  - type: OpenAPI\n    url: https://api.goauthentik.io/#/Schema/schema_retrieve\n  - type: APIReference\n    url: https://api.goauthentik.io/\n  - type: SDK\n    url: https://pypi.org/project/authentik-client/\n  - type: SDK\n    url: https://www.npmjs.com/package/@goauthentik/api\n  - type: GitHubRepository\n    url: https://github.com/goauthentik/authentik\ncommon:\n- type: Website\n  url: https://goauthentik.io\n- type: Documentation\n  url: https://docs.goauthentik.io\n- type: GitHubOrganization\n  url: https://github.com/goauthentik\n- type: GitHubRepository\n  url: https://github.com/goauthentik/authentik\n\
  - type: ChangeLog\n  url: https://github.com/goauthentik/authentik/releases\n- type: Support\n  url: https://github.com/goauthentik/authentik/discussions\n- type: Community\n  url: https://discord.gg/jg33eMhnj6\n- type: Pricing\n  url: https://goauthentik.io/pricing\n- type: Features\n  data:\n  - name: Comprehensive REST API\n    description: Full REST API covering all authentik features with built-in Swagger UI at /api/v3/ on every instance.\n  - name: Multi-Protocol Support\n    description: Native support for OAuth2, OIDC, SAML, LDAP, SCIM, RADIUS, and SSTP protocols for broad integration coverage.\n  - name: Flow Engine\n    description: Customizable authentication and enrollment flows with visual flow designer for configuring multi-step authentication processes.\n  - name: Multi-Language SDKs\n    description: Official API client SDKs in TypeScript, Python, Go, Rust, Kotlin, and Swift auto-generated from the OpenAPI schema.\n  - name: Terraform Provider\n    description: Official\
  \ Terraform provider for infrastructure-as-code management of authentik resources.\n  - name: Helm Deployment\n    description: Official Helm chart for Kubernetes deployment with configurable replicas, persistence, and external database support.\n  - name: RBAC\n    description: Role-based access control for granular permission management across authentik resources and administrative functions.\n- type: UseCases\n  data:\n  - name: Self-Hosted Identity Provider\n    description: Deploy a complete identity provider on-premises or in private cloud with full data sovereignty.\n  - name: SSO Gateway\n    description: Provide single sign-on for all internal applications using OIDC, SAML, or LDAP protocol support.\n  - name: B2C Identity\n    description: Build customer-facing registration and authentication flows with customizable enrollment and recovery processes.\n  - name: Zero Trust Access\n    description: Implement zero trust application access with forward auth proxy integration and\
  \ per-application policies.\n- type: Integrations\n  data:\n  - name: Nginx/Traefik/Caddy\n    description: Forward auth integration with major reverse proxies for transparent application authentication.\n  - name: Kubernetes\n    description: Native Kubernetes deployment via Helm chart with optional operator and RBAC integration.\n  - name: LDAP Directory\n    description: LDAP outpost that exposes authentik users to LDAP-compatible applications without a directory server.\n  - name: Grafana\n    description: Native OAuth2 integration with Grafana for unified authentication in monitoring stacks.\n  - name: Nextcloud\n    description: OIDC or SAML integration with Nextcloud for unified login in self-hosted file storage.\n- type: Solutions\n  data:\n  - name: Self-Hosted IAM\n    description: Complete identity and access management platform deployable on any infrastructure with no vendor lock-in.\n  - name: Application Gateway\n    description: Secure and authenticate any application using\
  \ forward auth with optional MFA and per-user access policies.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/authentik/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Identity Provider
- LDAP
- OAuth
- Open Source
- OpenID Connect
- SAML
- SCIM
- Self-Hosted
url: https://raw.githubusercontent.com/api-evangelist/authentik/refs/heads/main/apis.yml
use_cases:
- description: Deploy a complete identity provider on-premises or in private cloud with full data sovereignty.
  name: Self-Hosted Identity Provider
- description: Provide single sign-on for all internal applications using OIDC, SAML, or LDAP protocol support.
  name: SSO Gateway
- description: Build customer-facing registration and authentication flows with customizable enrollment and recovery processes.
  name: B2C Identity
- description: Implement zero trust application access with forward auth proxy integration and per-application policies.
  name: Zero Trust Access
---
