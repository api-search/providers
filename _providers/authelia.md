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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: authelia\nname: Authelia\ndescription: |\n  Authelia is an open source authentication and authorization server providing multi-factor authentication and single sign-on for applications behind a reverse proxy. It supports OpenID Connect 1.0, OAuth 2.0, TOTP, WebAuthn, and Duo Push as authentication methods. Authelia exposes a REST API documented with an OpenAPI specification and integrates with nginx, Traefik, Caddy, and other reverse proxies.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authentication\n- Authorization\n- LDAP\n- MFA\n- Open Source\n- OpenID Connect\n- Self-Hosted\n- SSO\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/authelia/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: authelia:authelia-rest-api\n  name: Authelia REST API\n  description: |\n    The Authelia REST API provides endpoints for authentication flows\
  \ including first-factor login, MFA challenges, password reset, session management, and authorization verification for reverse proxy integration.\n  humanURL: https://www.authelia.com/reference/\n  baseURL: https://your-authelia-instance.example.com/api\n  tags:\n  - Authentication\n  - Authorization\n  - MFA\n  - REST\n  - SSO\n  properties:\n  - type: Documentation\n    url: https://www.authelia.com/reference/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/authelia/authelia/master/api/openapi.yml\n  - type: GitHubRepository\n    url: https://github.com/authelia/authelia\n- aid: authelia:authelia-oidc-provider\n  name: Authelia OpenID Connect 1.0 Provider\n  description: |\n    Authelia acts as an OpenID Certified OpenID Connect 1.0 Provider supporting Authorization Code, Implicit, and Hybrid flows with PKCE, PAR, and various token endpoint authentication methods.\n  humanURL: https://www.authelia.com/configuration/identity-providers/openid-connect/provider/\n  baseURL:\
  \ https://your-authelia-instance.example.com\n  tags:\n  - Authentication\n  - OAuth\n  - OIDC\n  - OpenID Connect\n  properties:\n  - type: Documentation\n    url: https://www.authelia.com/configuration/identity-providers/openid-connect/provider/\ncommon:\n- type: Website\n  url: https://www.authelia.com\n- type: Documentation\n  url: https://www.authelia.com/configuration/prologue/introduction/\n- type: GitHubOrganization\n  url: https://github.com/authelia\n- type: GitHubRepository\n  url: https://github.com/authelia/authelia\n- type: ChangeLog\n  url: https://github.com/authelia/authelia/releases\n- type: Support\n  url: https://github.com/authelia/authelia/discussions\n- type: Community\n  url: https://discord.gg/authelia\n- type: Features\n  data:\n  - name: Multi-Factor Authentication\n    description: Supports TOTP, WebAuthn/FIDO2, Duo Push, and mobile authenticator apps as second factors.\n  - name: OpenID Connect 1.0 Provider\n    description: OpenID Certified identity provider\
  \ supporting Authorization Code, Implicit, and Hybrid flows.\n  - name: Single Sign-On\n    description: Session-based SSO across all applications behind the reverse proxy with configurable session lifetime.\n  - name: LDAP/Active Directory Integration\n    description: User authentication against LDAP, Active Directory, and OpenLDAP directories with group-based access control.\n  - name: Access Control Rules\n    description: Fine-grained access control policies based on domain, path, user, group, and network for precise authorization.\n  - name: Reverse Proxy Integration\n    description: Native integration with nginx, Traefik, Caddy, HAProxy, Envoy, and Skipper via forward-auth and ExtAuthz endpoints.\n  - name: Passwordless Authentication\n    description: Support for WebAuthn/FIDO2 passwordless login using hardware security keys and platform authenticators.\n- type: UseCases\n  data:\n  - name: Self-Hosted SSO\n    description: Deploy a self-hosted SSO solution for internal web applications\
  \ and services without relying on cloud identity providers.\n  - name: Homelab Security\n    description: Protect self-hosted homelab applications with MFA and access control without exposing them to the internet unprotected.\n  - name: Small Business Identity\n    description: Provide centralized authentication for small business web applications using LDAP and access control policies.\n  - name: OIDC Provider\n    description: Act as an OpenID Connect provider for applications requiring OAuth 2.0 and OIDC-based authentication flows.\n- type: Integrations\n  data:\n  - name: Nginx\n    description: Integration with nginx-based proxies including nginx, nginx-proxy-manager, and Swag via auth_request module.\n  - name: Traefik\n    description: Native Traefik middleware integration via ForwardAuth for seamless authentication in Docker and Kubernetes environments.\n  - name: Caddy\n    description: Caddy forward-auth integration for protecting applications behind the Caddy web server.\n \
  \ - name: LDAP/Active Directory\n    description: User directory integration with LDAP, Active Directory, and FreeIPA for enterprise user management.\n  - name: Helm\n    description: Official Helm chart available at the authelia/chartrepo GitHub repository for Kubernetes deployment.\n- type: Solutions\n  data:\n  - name: Self-Hosted Identity\n    description: Complete self-hosted identity and access management solution for privacy-conscious deployments.\n  - name: Zero Trust Security\n    description: Enforce zero trust network access policies for internal applications with per-request authentication verification.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/authelia/refs/heads/main/apis.yml
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
