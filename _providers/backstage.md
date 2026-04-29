---
api_count: 7
api_specs:
- filename: backstage-catalog-openapi.yml
  format: yaml
  label: Backstage Catalog API
  slug: catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-catalog-openapi.yml
- filename: backstage-scaffolder-openapi.yml
  format: yaml
  label: Backstage Scaffolder API
  slug: scaffolder-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-scaffolder-openapi.yml
- filename: backstage-auth-openapi.yml
  format: yaml
  label: Backstage Auth API
  slug: auth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-auth-openapi.yml
- filename: backstage-techdocs-openapi.yml
  format: yaml
  label: Backstage TechDocs API
  slug: techdocs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-techdocs-openapi.yml
- filename: backstage-search-openapi.yml
  format: yaml
  label: Backstage Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-search-openapi.yml
- filename: backstage-permissions-openapi.yml
  format: yaml
  label: Backstage Permissions API
  slug: permissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/openapi/backstage-permissions-openapi.yml
- filename: backstage-events-asyncapi.yml
  format: yaml
  label: Backstage Events System
  slug: events-system
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/asyncapi/backstage-events-asyncapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: backstage\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/apis.yml\napis:\n- aid: backstage:catalog-api\n  name: Backstage Catalog API\n  tags:\n  - Developer Portal\n  - Entities\n  - Software Catalog\n  humanURL: https://backstage.io/docs/features/software-catalog/software-catalog-api/\n  properties:\n  - url: https://backstage.io/docs/features/software-catalog/software-catalog-api/\n    type: Documentation\n  - url: openapi/backstage-catalog-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Backstage Software Catalog REST API provides JSON-based endpoints for\n    managing and querying catalog entities, locations, and related metadata.\n    The catalog stores information about all software components, APIs,\n    resources, systems, domains, groups, and users in an organization. Supports\n    entity CRUD, filtering, full-text search, cursor-based pagination, faceted\n    queries, location management, entity validation,\
  \ and ancestry lookups.\n- aid: backstage:scaffolder-api\n  name: Backstage Scaffolder API\n  tags:\n  - Developer Portal\n  - Scaffolding\n  - Software Templates\n  humanURL: https://backstage.io/docs/features/software-templates/\n  properties:\n  - url: https://backstage.io/docs/features/software-templates/\n    type: Documentation\n  - url: openapi/backstage-scaffolder-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Backstage Scaffolder (Software Templates) REST API provides endpoints\n    for creating, managing, and monitoring scaffolder tasks. It enables\n    programmatic execution of software templates to bootstrap new projects,\n    components, and other software assets. Supports task creation and\n    cancellation, real-time event streaming, log retrieval, template parameter\n    schema inspection, available action listing, and dry-run execution for\n    template validation.\n- aid: backstage:auth-api\n  name: Backstage Auth API\n  tags:\n  - Authentication\n  - Developer\
  \ Portal\n  - OAuth\n  humanURL: https://backstage.io/docs/auth/\n  properties:\n  - url: https://backstage.io/docs/auth/\n    type: Documentation\n  - url: openapi/backstage-auth-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Backstage Auth API provides endpoints for authenticating users and\n    services with the Backstage backend. It supports multiple authentication\n    providers (GitHub, Google, Okta, SAML, etc.) and handles OAuth flows,\n    token issuance, token refresh, and session management. The Auth API is\n    used by the Backstage frontend to initiate login flows and by backend\n    plugins to verify caller identity via Backstage tokens.\n- aid: backstage:techdocs-api\n  name: Backstage TechDocs API\n  tags:\n  - Developer Portal\n  - Documentation\n  - TechDocs\n  humanURL: https://backstage.io/docs/features/techdocs/\n  properties:\n  - url: https://backstage.io/docs/features/techdocs/\n    type: Documentation\n  - url: openapi/backstage-techdocs-openapi.yml\n\
  \    type: OpenAPI\n  description: >-\n    The Backstage TechDocs API provides endpoints for generating, publishing,\n    and serving technical documentation for catalog entities. TechDocs uses\n    MkDocs under the hood to render Markdown documentation into static HTML\n    pages. The API supports fetching rendered documentation, syncing docs\n    from external storage, retrieving metadata, and managing documentation\n    lifecycle.\n- aid: backstage:search-api\n  name: Backstage Search API\n  tags:\n  - Developer Portal\n  - Discovery\n  - Search\n  humanURL: https://backstage.io/docs/features/search/\n  properties:\n  - url: https://backstage.io/docs/features/search/\n    type: Documentation\n  - url: openapi/backstage-search-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Backstage Search API provides endpoints for querying the Backstage\n    search index. It enables full-text search across all indexed content\n    including catalog entities, TechDocs pages, and any other\
  \ content indexed\n    by search collators. The API supports filtering by document type,\n    pagination via cursors, and term-based queries.\n- aid: backstage:permissions-api\n  name: Backstage Permissions API\n  tags:\n  - Authorization\n  - Developer Portal\n  - Permissions\n  humanURL: https://backstage.io/docs/permissions/overview\n  properties:\n  - url: https://backstage.io/docs/permissions/overview\n    type: Documentation\n  - url: openapi/backstage-permissions-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Backstage Permissions API provides endpoints for evaluating and\n    managing authorization decisions within Backstage. It enables plugins to\n    check whether a given user or service has permission to perform a specific\n    action. The framework supports policy-based authorization with conditional\n    rules that can be applied to resources.\n- aid: backstage:events-system\n  name: Backstage Events System\n  tags:\n  - Developer Portal\n  - Events\n  - Webhooks\n\
  \  humanURL: https://backstage.io/docs/plugins/backends-and-plugins/\n  properties:\n  - url: https://backstage.io/docs/plugins/backends-and-plugins/\n    type: Documentation\n  - url: asyncapi/backstage-events-asyncapi.yml\n    type: AsyncAPI\n  description: >-\n    The Backstage Events system provides a publish-subscribe mechanism for\n    broadcasting and consuming events within a Backstage instance. It enables\n    plugins to emit events when significant actions occur (such as catalog\n    entity changes, scaffolder task completions, or permission policy updates)\n    and allows other plugins or external systems to subscribe to those events\n    via HTTP webhooks or the internal event bus.\nname: Backstage\ntags:\n- Developer Portal\n- Internal Developer Platform\n- Software Catalog\n- Open Source\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n- url: https://backstage.io/\n  name: Backstage Website\n  type:\
  \ Website\n  description: 'null'\n- url: https://backstage.io/docs/\n  name: Backstage Documentation\n  type: Documentation\n  description: 'null'\n- url: https://backstage.io/docs/getting-started/\n  name: Backstage Getting Started\n  type: Getting Started\n  description: 'null'\n- url: https://backstage.io/blog/\n  name: Backstage Blog\n  type: Blog\n  description: 'null'\n- url: https://github.com/backstage\n  name: Backstage GitHub Organization\n  type: GitHub Organization\n  description: 'null'\n- url: https://github.com/backstage/backstage\n  name: Backstage GitHub Repository\n  type: GitHubRepository\n  description: 'null'\n- url: https://github.com/backstage/backstage/releases\n  name: Backstage Releases\n  type: Change Log\n  description: 'null'\n- url: https://discord.gg/backstage-687207715902193673\n  name: Backstage Discord Community\n  type: Community\n  description: 'null'\n- url: https://backstage.io/plugins/\n  name: Backstage Plugin Directory\n  type: Developer Tools\n\
  \  description: 'null'\n- type: JSONSchema\n  url: json-schema/backstage-entity-schema.json\n  name: Backstage Entity JSON Schema\n  description: 'null'\n- type: JSON-LD\n  url: json-ld/backstage-context.jsonld\n  name: Backstage JSON-LD Context\n  description: 'null'\n- type: SpectralRules\n  url: rules/backstage-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/backstage-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/developer-portal.yaml\n- name: Features\n  type: Features\n  data:\n  - name: Software Catalog\n    description: Central inventory of all software components, APIs, resources, systems, domains, groups, and users.\n  - name: Software Templates (Scaffolder)\n    description: Bootstrap new projects, services, and components from customizable templates.\n  - name: TechDocs\n    description: Render and serve MkDocs-based technical documentation alongside catalog entities.\n  - name: Plugin Ecosystem\n    description: Extensible plugin architecture with\
  \ 100+ open-source plugins for CI/CD, monitoring, cloud, and more.\n  - name: Search\n    description: Full-text search across catalog entities, TechDocs, and any other indexed content.\n  - name: Permissions Framework\n    description: Policy-based authorization with conditional rules for resource-level access control.\n  - name: Entity Relations\n    description: Model ownership, dependencies, and API consumption relationships between services.\n- name: UseCases\n  type: UseCases\n  data:\n  - name: Internal Developer Portal\n    description: Build a unified portal for developers to discover services, read docs, and scaffold projects.\n  - name: Service Catalog\n    description: Maintain a complete, up-to-date inventory of all microservices, APIs, and infrastructure.\n  - name: Developer Onboarding\n    description: Accelerate new developer onboarding with self-service project scaffolding and documentation.\n  - name: API Governance\n    description: Track all internal and external APIs,\
  \ their owners, and documentation in one place.\n- name: Integrations\n  type: Integrations\n  data:\n  - name: GitHub\n    description: Catalog ingestion from GitHub repos, GitHub Actions integration for CI/CD visibility.\n  - name: PagerDuty\n    description: Show on-call information and incident status on catalog entity pages.\n  - name: Kubernetes\n    description: Display Kubernetes workload status for catalog entities.\n  - name: Prometheus\n    description: Show metrics and alerts for services directly in the catalog.\n  - name: Snyk\n    description: Display security vulnerability information for catalog entities.\n  - name: Datadog\n    description: Surface monitoring dashboards within Backstage.\ncreated: '2024-12-01'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  Backstage is an open-source developer portal platform created by Spotify. It\n  provides a centralized software catalog, software templates (scaffolder),\n  TechDocs, and a plugin ecosystem for building\
  \ customizable developer portals.\n  Backstage helps organizations manage their software ecosystem by cataloging\n  services, APIs, resources, and infrastructure, and provides tooling for\n  creating new projects from templates.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/backstage/refs/heads/main/apis.yml
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
