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
source_yaml: "aid: casdoor\nname: Casdoor\ndescription: >-\n  Casdoor is an open-source, AI-first identity and access management (IAM) and\n  MCP gateway authentication server with a web UI. Built in Go (Beego) with a\n  React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP,\n  Kerberos/SPNEGO, WebAuthn / Passkeys, TOTP / MFA, SCIM 2.0 provisioning,\n  social login, multi-tenant organizations, role-based access control, and an\n  MCP Gateway plus A2A Protocol for agent-to-agent communication. The platform\n  exposes a RESTful API documented via Swagger and ships SDKs for Go, Java,\n  Python, Node.js, C#, C++, PHP, Ruby, JavaScript, Lua, and Haskell. Released\n  under the Apache License 2.0.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authentication\n  - Authorization\n  - IAM\n  - Identity\n  - LDAP\n  - MCP\n  - MFA\n  - OAuth\n  - OIDC\n  - Open Source\n  - Passkeys\n  - SAML\n  - SCIM\n  - Single Sign-On\n\
  \  - SSO\n  - WebAuthn\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: casdoor:casdoor-rest-api\n    name: Casdoor REST API\n    description: >-\n      The Casdoor REST API provides programmatic access to the IAM platform's\n      core resources including users, organizations, applications, roles,\n      groups, permissions, identity providers, tokens, sessions, certificates,\n      adapters, syncers, webhooks, products, payments, MFA enrollments, and\n      enforcers. The API follows RESTful conventions with JSON payloads and\n      is documented via a hosted Swagger UI.\n    humanURL: https://casdoor.ai/docs/basic/api\n    baseURL: https://door.casdoor.com\n    tags:\n      - Applications\n      - IAM\n      - Organizations\n      - REST\n      - Roles\n      - Sessions\n      - Tokens\n      - Users\n    properties:\n      - type: Documentation\n\
  \        url: https://casdoor.ai/docs/basic/api\n      - type: Swagger\n        url: https://door.casdoor.com/swagger/\n      - type: GitHub Repository\n        url: https://github.com/casdoor/casdoor\n      - type: Authentication\n        url: https://casdoor.ai/docs/basic/core-concepts\n  - aid: casdoor:casdoor-oauth-oidc\n    name: Casdoor OAuth 2.0 / OIDC Provider\n    description: >-\n      Casdoor implements an OAuth 2.0 authorization server and OpenID Connect\n      identity provider, exposing the standard authorization, token, userinfo,\n      revocation, introspection, JWKS, and OIDC discovery endpoints used by\n      web, mobile, native, and machine-to-machine clients to obtain ID tokens\n      and access tokens.\n    humanURL: https://casdoor.ai/docs/how-to-connect/oauth\n    tags:\n      - Authentication\n      - JWT\n      - OAuth\n      - OIDC\n      - SSO\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/how-to-connect/oauth\n\
  \      - type: Discovery\n        url: https://door.casdoor.com/.well-known/openid-configuration\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc6749\n  - aid: casdoor:casdoor-saml\n    name: Casdoor SAML 2.0 Identity Provider\n    description: >-\n      SAML 2.0 identity provider endpoints in Casdoor that issue SAML\n      assertions to enterprise service providers, supporting SSO scenarios for\n      legacy and enterprise SaaS applications via standard SAML metadata,\n      ACS, and SLO bindings.\n    humanURL: https://casdoor.ai/docs/how-to-connect/saml\n    tags:\n      - Enterprise SSO\n      - Federation\n      - SAML\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/how-to-connect/saml\n      - type: Specification\n        url: http://docs.oasis-open.org/security/saml/v2.0/\n  - aid: casdoor:casdoor-cas\n    name: Casdoor CAS Server\n    description: >-\n      Casdoor exposes a CAS (Central Authentication\
  \ Service) server compatible\n      with CAS protocol versions 1.0, 2.0, and 3.0, providing single sign-on\n      to applications that integrate via the CAS ticket-validation flow.\n    humanURL: https://casdoor.ai/docs/how-to-connect/cas\n    tags:\n      - Authentication\n      - CAS\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/how-to-connect/cas\n  - aid: casdoor:casdoor-ldap\n    name: Casdoor LDAP Server\n    description: >-\n      Casdoor provides an LDAP server interface so that legacy applications\n      and infrastructure components requiring LDAP authentication can bind\n      against Casdoor users and groups, and a sync engine that imports users\n      from external LDAP directories.\n    humanURL: https://casdoor.ai/docs/ldap/overview\n    tags:\n      - Directory\n      - LDAP\n      - Sync\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/ldap/overview\n  - aid: casdoor:casdoor-scim\n  \
  \  name: Casdoor SCIM 2.0 API\n    description: >-\n      SCIM 2.0 (System for Cross-domain Identity Management) endpoints for\n      automated user and group provisioning between Casdoor and downstream\n      identity-aware systems.\n    humanURL: https://casdoor.ai/docs/scim/overview\n    tags:\n      - Identity\n      - Provisioning\n      - SCIM\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/scim/overview\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc7644\n  - aid: casdoor:casdoor-mcp-gateway\n    name: Casdoor MCP Gateway\n    description: >-\n      Casdoor's MCP (Model Context Protocol) gateway and A2A (Agent-to-Agent)\n      protocol surface, designed to broker authentication and authorization\n      for AI agents and MCP-aware tooling using Casdoor as the identity\n      provider.\n    humanURL: https://casdoor.ai/docs/mcp/overview\n    tags:\n      - A2A\n      - Agents\n      - AI\n      - MCP\n    properties:\n\
  \      - type: Documentation\n        url: https://casdoor.ai/docs/mcp/overview\n  - aid: casdoor:casdoor-webhooks\n    name: Casdoor Webhooks\n    description: >-\n      Outbound webhook events that notify external systems of identity events\n      such as user signup, login, logout, profile changes, password resets,\n      and MFA enrollments.\n    humanURL: https://casdoor.ai/docs/integration/webhook\n    tags:\n      - Events\n      - Integration\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://casdoor.ai/docs/integration/webhook\ncommon:\n  - type: Website\n    url: https://casdoor.org\n  - type: Documentation\n    url: https://casdoor.ai/docs/overview\n  - type: GettingStarted\n    url: https://casdoor.ai/docs/basic/server-installation\n  - type: Authentication\n    url: https://casdoor.ai/docs/basic/core-concepts\n  - type: Swagger\n    url: https://door.casdoor.com/swagger/\n  - type: GitHub\n    url: https://github.com/casdoor/casdoor\n  -\
  \ type: GitHubOrganization\n    url: https://github.com/casdoor\n  - type: SourceCode\n    url: https://github.com/casdoor/casdoor\n  - type: IssueTracker\n    url: https://github.com/casdoor/casdoor/issues\n  - type: Blog\n    url: https://casdoor.org/blog\n  - type: Community\n    url: https://casdoor.ai/docs/community/forum\n  - type: Discord\n    url: https://discord.gg/5rPsrAzK7S\n  - type: License\n    url: https://github.com/casdoor/casdoor/blob/master/LICENSE\n  - type: DockerHub\n    url: https://hub.docker.com/r/casbin/casdoor\n  - type: Demo\n    url: https://door.casdoor.com\n  - type: PrivacyPolicy\n    url: https://casdoor.org/privacy\n  - type: Pricing\n    url: https://casdoor.com/pricing\n  - name: Features\n    type: Features\n    data:\n      - name: OAuth 2.0 Server\n      - name: OIDC Provider\n      - name: SAML 2.0 IdP\n      - name: CAS Server\n      - name: LDAP Server\n      - name: SCIM 2.0 Provisioning\n      - name: WebAuthn / Passkeys\n      - name: TOTP MFA\n\
  \      - name: Face ID Biometrics\n      - name: Social Login\n      - name: RBAC\n      - name: ABAC\n      - name: ACL\n      - name: Multi-Tenancy\n      - name: Organizations\n      - name: Audit Logs\n      - name: Webhooks\n      - name: Identity Provider Federation\n      - name: MCP Gateway\n      - name: A2A Protocol\n      - name: Self-Hosted\n      - name: Apache 2.0 License\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Single Sign-On\n      - name: Customer Identity (CIAM)\n      - name: Workforce Identity\n      - name: Passwordless Login\n      - name: Multi-Factor Authentication\n      - name: Enterprise SSO via SAML\n      - name: API Authorization\n      - name: Identity Provider for AI Agents\n      - name: User Provisioning Automation\n      - name: Self-Hosted Auth Server\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: GitHub\n      - name: Google\n      - name: Azure AD\n      - name: WeChat\n      - name: QQ\n      - name:\
  \ MySQL\n      - name: PostgreSQL\n      - name: SQL Server\n      - name: Redis\n      - name: Beego\n      - name: React\n      - name: Casbin\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml
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
