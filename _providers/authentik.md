---
api_count: 1
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
