---
api_count: 8
apis:
- description: The Casdoor REST API provides programmatic access to the IAM platform's core resources including users, organizations, applications, roles, groups, permissions, identity providers, tokens, sessions, c
  name: Casdoor REST API
  slug: casdoor-rest-api
- description: Casdoor implements an OAuth 2.0 authorization server and OpenID Connect identity provider, exposing the standard authorization, token, userinfo, revocation, introspection, JWKS, and OIDC discovery end
  name: Casdoor OAuth 2.0 / OIDC Provider
  slug: casdoor-oauth-oidc
- description: SAML 2.0 identity provider endpoints in Casdoor that issue SAML assertions to enterprise service providers, supporting SSO scenarios for legacy and enterprise SaaS applications via standard SAML metad
  name: Casdoor SAML 2.0 Identity Provider
  slug: casdoor-saml
- description: Casdoor exposes a CAS (Central Authentication Service) server compatible with CAS protocol versions 1.0, 2.0, and 3.0, providing single sign-on to applications that integrate via the CAS ticket-valida
  name: Casdoor CAS Server
  slug: casdoor-cas
- description: Casdoor provides an LDAP server interface so that legacy applications and infrastructure components requiring LDAP authentication can bind against Casdoor users and groups, and a sync engine that impo
  name: Casdoor LDAP Server
  slug: casdoor-ldap
- description: SCIM 2.0 (System for Cross-domain Identity Management) endpoints for automated user and group provisioning between Casdoor and downstream identity-aware systems.
  name: Casdoor SCIM 2.0 API
  slug: casdoor-scim
- description: Casdoor's MCP (Model Context Protocol) gateway and A2A (Agent-to-Agent) protocol surface, designed to broker authentication and authorization for AI agents and MCP-aware tooling using Casdoor as the i
  name: Casdoor MCP Gateway
  slug: casdoor-mcp-gateway
- description: Outbound webhook events that notify external systems of identity events such as user signup, login, logout, profile changes, password resets, and MFA enrollments.
  name: Casdoor Webhooks
  slug: casdoor-webhooks
common:
- title: ''
  type: Website
  url: https://casdoor.org
- title: ''
  type: Documentation
  url: https://casdoor.ai/docs/overview
- title: ''
  type: GettingStarted
  url: https://casdoor.ai/docs/basic/server-installation
- title: ''
  type: Authentication
  url: https://casdoor.ai/docs/basic/core-concepts
- title: ''
  type: Swagger
  url: https://door.casdoor.com/swagger/
- title: ''
  type: GitHub
  url: https://github.com/casdoor/casdoor
- title: ''
  type: GitHubOrganization
  url: https://github.com/casdoor
- title: ''
  type: SourceCode
  url: https://github.com/casdoor/casdoor
- title: ''
  type: IssueTracker
  url: https://github.com/casdoor/casdoor/issues
- title: ''
  type: Blog
  url: https://casdoor.org/blog
- title: ''
  type: Community
  url: https://casdoor.ai/docs/community/forum
- title: ''
  type: Discord
  url: https://discord.gg/5rPsrAzK7S
- title: ''
  type: License
  url: https://github.com/casdoor/casdoor/blob/master/LICENSE
- title: ''
  type: DockerHub
  url: https://hub.docker.com/r/casbin/casdoor
- title: ''
  type: Demo
  url: https://door.casdoor.com
- title: ''
  type: PrivacyPolicy
  url: https://casdoor.org/privacy
- title: ''
  type: Pricing
  url: https://casdoor.com/pricing
created: '2026-03-25'
description: Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO, WebAuthn / Passkeys, TOTP / MFA, SCIM 2.0 provisioning, social login, multi-tenant organizations, role-based access control, and an MCP Gateway plus A2A Protocol for agent-to-agent communication. The platform exposes a RESTful API documented via Swagger and ships SDKs for Go, Java, Python, Node.js, C#, C++, PHP, Ruby, JavaScript, Lua, and Haskell. Released under the Apache License 2.0.
features:
- name: OAuth 2.0 Server
- name: OIDC Provider
- name: SAML 2.0 IdP
- name: CAS Server
- name: LDAP Server
- name: SCIM 2.0 Provisioning
- name: WebAuthn / Passkeys
- name: TOTP MFA
- name: Face ID Biometrics
- name: Social Login
- name: RBAC
- name: ABAC
- name: ACL
- name: Multi-Tenancy
- name: Organizations
- name: Audit Logs
- name: Webhooks
- name: Identity Provider Federation
- name: MCP Gateway
- name: A2A Protocol
- name: Self-Hosted
- name: Apache 2.0 License
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: GitHub
- name: Google
- name: Azure AD
- name: WeChat
- name: QQ
- name: MySQL
- name: PostgreSQL
- name: SQL Server
- name: Redis
- name: Beego
- name: React
- name: Casbin
layout: provider
modified: '2026-04-23'
name: Casdoor
skills: []
slug: casdoor
solutions: []
tags:
- Authentication
- Authorization
- IAM
- Identity
- LDAP
- MCP
- MFA
- OAuth
- OIDC
- Open Source
- Passkeys
- SAML
- SCIM
- Single Sign-On
- SSO
- WebAuthn
url: https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml
use_cases:
- name: Single Sign-On
- name: Customer Identity (CIAM)
- name: Workforce Identity
- name: Passwordless Login
- name: Multi-Factor Authentication
- name: Enterprise SSO via SAML
- name: API Authorization
- name: Identity Provider for AI Agents
- name: User Provisioning Automation
- name: Self-Hosted Auth Server
---
