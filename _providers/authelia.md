---
api_count: 2
apis:
- description: The Authelia REST API provides endpoints for authentication flows including first-factor login, MFA challenges, password reset, session management, and authorization verification for reverse proxy int
  name: Authelia REST API
  slug: authelia-rest-api
- description: Authelia acts as an OpenID Certified OpenID Connect 1.0 Provider supporting Authorization Code, Implicit, and Hybrid flows with PKCE, PAR, and various token endpoint authentication methods.
  name: Authelia OpenID Connect 1.0 Provider
  slug: authelia-oidc-provider
common:
- title: ''
  type: Website
  url: https://www.authelia.com
- title: ''
  type: Documentation
  url: https://www.authelia.com/configuration/prologue/introduction/
- title: ''
  type: GitHubOrganization
  url: https://github.com/authelia
- title: ''
  type: GitHubRepository
  url: https://github.com/authelia/authelia
- title: ''
  type: ChangeLog
  url: https://github.com/authelia/authelia/releases
- title: ''
  type: Support
  url: https://github.com/authelia/authelia/discussions
- title: ''
  type: Community
  url: https://discord.gg/authelia
created: '2026-03-25'
description: Authelia is an open source authentication and authorization server providing multi-factor authentication and single sign-on for applications behind a reverse proxy. It supports OpenID Connect 1.0, OAuth 2.0, TOTP, WebAuthn, and Duo Push as authentication methods. Authelia exposes a REST API documented with an OpenAPI specification and integrates with nginx, Traefik, Caddy, and other reverse proxies.
features:
- description: Supports TOTP, WebAuthn/FIDO2, Duo Push, and mobile authenticator apps as second factors.
  name: Multi-Factor Authentication
- description: OpenID Certified identity provider supporting Authorization Code, Implicit, and Hybrid flows.
  name: OpenID Connect 1.0 Provider
- description: Session-based SSO across all applications behind the reverse proxy with configurable session lifetime.
  name: Single Sign-On
- description: User authentication against LDAP, Active Directory, and OpenLDAP directories with group-based access control.
  name: LDAP/Active Directory Integration
- description: Fine-grained access control policies based on domain, path, user, group, and network for precise authorization.
  name: Access Control Rules
- description: Native integration with nginx, Traefik, Caddy, HAProxy, Envoy, and Skipper via forward-auth and ExtAuthz endpoints.
  name: Reverse Proxy Integration
- description: Support for WebAuthn/FIDO2 passwordless login using hardware security keys and platform authenticators.
  name: Passwordless Authentication
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with nginx-based proxies including nginx, nginx-proxy-manager, and Swag via auth_request module.
  name: Nginx
- description: Native Traefik middleware integration via ForwardAuth for seamless authentication in Docker and Kubernetes environments.
  name: Traefik
- description: Caddy forward-auth integration for protecting applications behind the Caddy web server.
  name: Caddy
- description: User directory integration with LDAP, Active Directory, and FreeIPA for enterprise user management.
  name: LDAP/Active Directory
- description: Official Helm chart available at the authelia/chartrepo GitHub repository for Kubernetes deployment.
  name: Helm
layout: provider
modified: '2026-04-19'
name: Authelia
skills: []
slug: authelia
solutions:
- description: Complete self-hosted identity and access management solution for privacy-conscious deployments.
  name: Self-Hosted Identity
- description: Enforce zero trust network access policies for internal applications with per-request authentication verification.
  name: Zero Trust Security
tags:
- Authentication
- Authorization
- LDAP
- MFA
- Open Source
- OpenID Connect
- Self-Hosted
- SSO
url: https://raw.githubusercontent.com/api-evangelist/authelia/refs/heads/main/apis.yml
use_cases:
- description: Deploy a self-hosted SSO solution for internal web applications and services without relying on cloud identity providers.
  name: Self-Hosted SSO
- description: Protect self-hosted homelab applications with MFA and access control without exposing them to the internet unprotected.
  name: Homelab Security
- description: Provide centralized authentication for small business web applications using LDAP and access control policies.
  name: Small Business Identity
- description: Act as an OpenID Connect provider for applications requiring OAuth 2.0 and OIDC-based authentication flows.
  name: OIDC Provider
---
