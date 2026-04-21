---
api_count: 1
apis:
- description: Apiman is an open source API management platform with a developer portal, API gateway, and management UI supporting policies, plans, organizations, multi-tenancy, and extensible Java-based plugin arch
  name: Apiman
  slug: apiman
common:
- title: ''
  type: Website
  url: https://www.apiman.io
- title: ''
  type: Documentation
  url: https://www.apiman.io/api-manager/latest/index.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apiman
- title: ''
  type: GitHubRepository
  url: https://github.com/apiman/apiman
created: '2026-03-25'
description: Apiman is an open source API management platform featuring a REST API, manager UI, and standalone developer portal with multi-tenancy, events, notifications, permissions, and approval workflows. It provides extensible API gateway capabilities through a simple Java plugin architecture with support for policies, plans, organizations, and client management.
features:
- description: Full REST API for managing organizations, APIs, plans, clients, and policies programmatically.
  name: REST API Manager
- description: Extensible API gateway that enforces policies at runtime for authentication, rate limiting, and transformation.
  name: API Gateway
- description: Standalone developer portal for API discovery, documentation, and self-service subscription management.
  name: Developer Portal
- description: Pluggable Java-based policy engine supporting rate limiting, quotas, IP whitelisting, authentication, and custom policies.
  name: Policy Engine
- description: Organization-based multi-tenancy allowing separate API management namespaces within a single platform.
  name: Multi-Tenancy
- description: Configurable approval workflows for API subscriptions with notification and event support.
  name: Approval Workflows
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Apiman Context
  property_count: 1
  slug: apiman-context
layout: provider
modified: '2026-04-19'
name: Apiman
skills: []
slug: apiman
solutions:
- description: Free, Apache-licensed API management platform deployable on any JVM-based infrastructure.
  name: Open Source
- description: High-performance async API gateway implementation using Eclipse Vert.x.
  name: Vert.x Gateway
- description: Apiman overlay for WildFly/EAP application server deployments.
  name: WildFly Overlay
tags:
- API Gateway
- API Management
- Developer Portal
- Java
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apiman/refs/heads/main/apis.yml
use_cases:
- description: Deploy Apiman on-premise to manage APIs across internal services with full control over infrastructure.
  name: On-Premise API Management
- description: Provide developers with a self-service portal for discovering and subscribing to APIs.
  name: Developer Portal Hosting
- description: Enforce security, rate limiting, and transformation policies on API traffic through the gateway.
  name: API Policy Enforcement
- description: Use organizations and plans to provide isolated API management environments for multiple teams.
  name: Multi-Team API Governance
---
