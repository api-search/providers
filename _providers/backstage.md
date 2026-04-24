---
api_count: 7
apis:
- description: The Backstage Software Catalog REST API provides JSON-based endpoints for managing and querying catalog entities, locations, and related metadata. The catalog stores information about all software com
  name: Backstage Catalog API
  slug: catalog-api
- description: 'The Backstage Scaffolder (Software Templates) REST API provides endpoints for creating, managing, and monitoring scaffolder tasks. It enables programmatic execution of software templates to bootstrap '
  name: Backstage Scaffolder API
  slug: scaffolder-api
- description: The Backstage Auth API provides endpoints for authenticating users and services with the Backstage backend. It supports multiple authentication providers (GitHub, Google, Okta, SAML, etc.) and handles
  name: Backstage Auth API
  slug: auth-api
- description: The Backstage TechDocs API provides endpoints for generating, publishing, and serving technical documentation for catalog entities. TechDocs uses MkDocs under the hood to render Markdown documentation
  name: Backstage TechDocs API
  slug: techdocs-api
- description: The Backstage Search API provides endpoints for querying the Backstage search index. It enables full-text search across all indexed content including catalog entities, TechDocs pages, and any other co
  name: Backstage Search API
  slug: search-api
- description: The Backstage Permissions API provides endpoints for evaluating and managing authorization decisions within Backstage. It enables plugins to check whether a given user or service has permission to per
  name: Backstage Permissions API
  slug: permissions-api
- description: The Backstage Events system provides a publish-subscribe mechanism for broadcasting and consuming events within a Backstage instance. It enables plugins to emit events when significant actions occur (
  name: Backstage Events System
  slug: events-system
asyncapis:
- description: The Backstage Events system provides a publish-subscribe mechanism for broadcasting and consuming events within a Backstage instance. It enables plugins to emit events when significant actions occur (
  name: Backstage Events System
  slug: backstage-events-asyncapi
capabilities:
- description: Unified developer portal workflow combining the Backstage Software Catalog, Scaffolder, TechDocs, Search, Auth, and Permissions APIs. Serves platform engineers and developers managing internal develop
  name: Backstage Developer Portal
  slug: developer-portal
common:
- title: ''
  type: Website
  url: https://backstage.io/
- title: ''
  type: Documentation
  url: https://backstage.io/docs/
- title: ''
  type: Getting Started
  url: https://backstage.io/docs/getting-started/
- title: ''
  type: Blog
  url: https://backstage.io/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/backstage
- title: ''
  type: GitHubRepository
  url: https://github.com/backstage/backstage
- title: ''
  type: Change Log
  url: https://github.com/backstage/backstage/releases
- title: ''
  type: Community
  url: https://discord.gg/backstage-687207715902193673
- title: ''
  type: Developer Tools
  url: https://backstage.io/plugins/
- title: ''
  type: JSONSchema
  url: json-schema/backstage-entity-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/backstage-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/backstage-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/backstage-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/developer-portal.yaml
created: '2024-12-01'
description: Backstage is an open-source developer portal platform created by Spotify. It provides a centralized software catalog, software templates (scaffolder), TechDocs, and a plugin ecosystem for building customizable developer portals. Backstage helps organizations manage their software ecosystem by cataloging services, APIs, resources, and infrastructure, and provides tooling for creating new projects from templates.
features:
- description: Central inventory of all software components, APIs, resources, systems, domains, groups, and users.
  name: Software Catalog
- description: Bootstrap new projects, services, and components from customizable templates.
  name: Software Templates (Scaffolder)
- description: Render and serve MkDocs-based technical documentation alongside catalog entities.
  name: TechDocs
- description: Extensible plugin architecture with 100+ open-source plugins for CI/CD, monitoring, cloud, and more.
  name: Plugin Ecosystem
- description: Full-text search across catalog entities, TechDocs, and any other indexed content.
  name: Search
- description: Policy-based authorization with conditional rules for resource-level access control.
  name: Permissions Framework
- description: Model ownership, dependencies, and API consumption relationships between services.
  name: Entity Relations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Catalog ingestion from GitHub repos, GitHub Actions integration for CI/CD visibility.
  name: GitHub
- description: Show on-call information and incident status on catalog entity pages.
  name: PagerDuty
- description: Display Kubernetes workload status for catalog entities.
  name: Kubernetes
- description: Show metrics and alerts for services directly in the catalog.
  name: Prometheus
- description: Display security vulnerability information for catalog entities.
  name: Snyk
- description: Surface monitoring dashboards within Backstage.
  name: Datadog
jsonld:
- class_count: 16
  name: Backstage Context
  property_count: 48
  slug: backstage-context
layout: provider
modified: '2026-04-21'
name: Backstage
rules:
- name: Backstage API Rules
  rule_count: 21
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 10
  slug: backstage-spectral-rules
skills: []
slug: backstage
solutions: []
tags:
- Developer Portal
- Internal Developer Platform
- Software Catalog
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/apis.yml
use_cases:
- description: Build a unified portal for developers to discover services, read docs, and scaffold projects.
  name: Internal Developer Portal
- description: Maintain a complete, up-to-date inventory of all microservices, APIs, and infrastructure.
  name: Service Catalog
- description: Accelerate new developer onboarding with self-service project scaffolding and documentation.
  name: Developer Onboarding
- description: Track all internal and external APIs, their owners, and documentation in one place.
  name: API Governance
---
