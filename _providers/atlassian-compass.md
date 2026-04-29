---
api_count: 2
apis:
- description: 'The Compass GraphQL API enables programmatic management of software components, scorecards, metrics, relationships, custom fields, and event ingestion within the Compass developer experience platform '
  name: Atlassian Compass GraphQL API
  slug: atlassian-compass-graphql-api
- description: The Compass REST API v1 provides operations for component management, scorecard configuration, and webhook registration via standard HTTP REST conventions with OAuth 2.0 authentication.
  name: Atlassian Compass REST API
  slug: atlassian-compass-rest-api
common:
- title: ''
  type: Website
  url: https://www.atlassian.com/software/compass
- title: ''
  type: Portal
  url: https://developer.atlassian.com/cloud/compass/
- title: ''
  type: Documentation
  url: https://developer.atlassian.com/cloud/compass/
- title: ''
  type: GettingStarted
  url: https://developer.atlassian.com/cloud/compass/getting-started/
- title: ''
  type: Authentication
  url: https://developer.atlassian.com/cloud/compass/getting-started/
- title: ''
  type: SignUp
  url: https://www.atlassian.com/software/compass
- title: ''
  type: GitHubOrganization
  url: https://github.com/atlassian
- title: ''
  type: StatusPage
  url: https://status.atlassian.com/
- title: ''
  type: Support
  url: https://support.atlassian.com/
- title: ''
  type: Community
  url: https://community.atlassian.com/
- title: ''
  type: TermsOfService
  url: https://www.atlassian.com/legal/cloud-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.atlassian.com/legal/privacy-policy
- title: ''
  type: Pricing
  url: https://www.atlassian.com/software/compass/pricing
- title: ''
  type: Blog
  url: https://www.atlassian.com/blog/
- title: ''
  type: ReleaseNotes
  url: https://developer.atlassian.com/cloud/compass/changelog/
created: '2026-03-16'
description: Atlassian Compass is a developer experience platform that helps engineering teams understand, manage, and improve the health of their software components and services. It provides a centralized catalog of software components with scorecards, metrics, dependency tracking, and event ingestion to improve developer productivity and software quality. Compass exposes a GraphQL API for querying and mutating component data and a REST Operations API for integrations.
features:
- description: Central catalog of all software components with metadata, ownership, and lifecycle tracking across teams.
  name: Component Catalog
- description: Configurable scorecards that evaluate components against engineering standards and best practices to measure health.
  name: Scorecards
- description: Ingest build, deployment, incident, and vulnerability events from CI/CD pipelines and monitoring tools via webhooks and REST.
  name: Event Ingestion
- description: Track relationships and dependencies between software components to understand blast radius and system topology.
  name: Dependency Tracking
- description: Extend component metadata with custom text, number, boolean, and user fields to capture team-specific data.
  name: Custom Fields
- description: Build custom Compass apps using the Atlassian Forge platform with the GraphQL toolkit for deep platform integration.
  name: Forge Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Jira for linking components to project tracking and incident management workflows.
  name: Jira
- description: Connect Bitbucket repositories to Compass components for automated code health and deployment event tracking.
  name: Bitbucket
- description: Integrate GitHub repositories and GitHub Actions CI/CD pipelines with Compass component events.
  name: GitHub
- description: Ingest PagerDuty incident events into Compass for on-call and incident tracking scorecard criteria.
  name: PagerDuty
- description: Connect Datadog monitoring data and deployment events to Compass component metrics.
  name: Datadog
- description: Manage Compass resources via the Atlassian Operations Terraform provider for infrastructure-as-code workflows.
  name: Terraform
layout: provider
modified: '2026-04-19'
name: Atlassian Compass
skills: []
slug: atlassian-compass
solutions:
- description: Provide engineering teams with a centralized platform to understand, manage, and improve the health of their software systems.
  name: Developer Experience Platform
- description: Enable platform engineering teams to enforce standards, track compliance, and improve developer productivity at scale.
  name: Platform Engineering
source_filename: apis.yml
source_yaml: "aid: atlassian-compass\nname: Atlassian Compass\ndescription: |\n  Atlassian Compass is a developer experience platform that helps engineering teams understand, manage, and improve the health of their software components and services. It provides a centralized catalog of software components with scorecards, metrics, dependency tracking, and event ingestion to improve developer productivity and software quality. Compass exposes a GraphQL API for querying and mutating component data and a REST Operations API for integrations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Atlassian\n- Component Management\n- Developer Experience\n- Software Catalog\n- GraphQL\nurl: https://raw.githubusercontent.com/api-evangelist/atlassian-compass/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: atlassian-compass:atlassian-compass-graphql-api\n  name: Atlassian Compass\
  \ GraphQL API\n  description: |\n    The Compass GraphQL API enables programmatic management of software components, scorecards, metrics, relationships, custom fields, and event ingestion within the Compass developer experience platform using OAuth 2.0 authentication.\n  humanURL: https://developer.atlassian.com/cloud/compass/graphql/\n  baseURL: https://api.atlassian.com/graphql\n  tags:\n  - Components\n  - Developer Experience\n  - GraphQL\n  - Software Catalog\n  properties:\n  - type: Documentation\n    url: https://developer.atlassian.com/cloud/compass/graphql/\n  - type: Authentication\n    url: https://developer.atlassian.com/cloud/compass/getting-started/\n  - type: GettingStarted\n    url: https://developer.atlassian.com/cloud/compass/getting-started/\n- aid: atlassian-compass:atlassian-compass-rest-api\n  name: Atlassian Compass REST API\n  description: |\n    The Compass REST API v1 provides operations for component management, scorecard configuration, and webhook registration\
  \ via standard HTTP REST conventions with OAuth 2.0 authentication.\n  humanURL: https://developer.atlassian.com/cloud/compass/rest/\n  baseURL: https://api.atlassian.com/compass/v1\n  tags:\n  - Components\n  - Developer Experience\n  - REST\n  - Software Catalog\n  properties:\n  - type: Documentation\n    url: https://developer.atlassian.com/cloud/compass/rest/\n  - type: Authentication\n    url: https://developer.atlassian.com/cloud/compass/getting-started/\ncommon:\n- type: Website\n  url: https://www.atlassian.com/software/compass\n- type: Portal\n  url: https://developer.atlassian.com/cloud/compass/\n- type: Documentation\n  url: https://developer.atlassian.com/cloud/compass/\n- type: GettingStarted\n  url: https://developer.atlassian.com/cloud/compass/getting-started/\n- type: Authentication\n  url: https://developer.atlassian.com/cloud/compass/getting-started/\n- type: SignUp\n  url: https://www.atlassian.com/software/compass\n- type: GitHubOrganization\n  url: https://github.com/atlassian\n\
  - type: StatusPage\n  url: https://status.atlassian.com/\n- type: Support\n  url: https://support.atlassian.com/\n- type: Community\n  url: https://community.atlassian.com/\n- type: TermsOfService\n  url: https://www.atlassian.com/legal/cloud-terms-of-service\n- type: PrivacyPolicy\n  url: https://www.atlassian.com/legal/privacy-policy\n- type: Pricing\n  url: https://www.atlassian.com/software/compass/pricing\n- type: Blog\n  url: https://www.atlassian.com/blog/\n- type: ReleaseNotes\n  url: https://developer.atlassian.com/cloud/compass/changelog/\n- type: Features\n  data:\n  - name: Component Catalog\n    description: Central catalog of all software components with metadata, ownership, and lifecycle tracking across teams.\n  - name: Scorecards\n    description: Configurable scorecards that evaluate components against engineering standards and best practices to measure health.\n  - name: Event Ingestion\n    description: Ingest build, deployment, incident, and vulnerability events from\
  \ CI/CD pipelines and monitoring tools via webhooks and REST.\n  - name: Dependency Tracking\n    description: Track relationships and dependencies between software components to understand blast radius and system topology.\n  - name: Custom Fields\n    description: Extend component metadata with custom text, number, boolean, and user fields to capture team-specific data.\n  - name: Forge Integration\n    description: Build custom Compass apps using the Atlassian Forge platform with the GraphQL toolkit for deep platform integration.\n- type: UseCases\n  data:\n  - name: Software Catalog Management\n    description: Register and track all microservices, libraries, and software components with ownership and lifecycle metadata.\n  - name: Engineering Health Monitoring\n    description: Create scorecards to measure and improve engineering standards like on-call coverage, documentation, and security posture.\n  - name: DORA Metrics Tracking\n    description: Ingest deployment and incident events\
  \ to track DORA metrics including deployment frequency and change failure rate.\n  - name: Dependency Mapping\n    description: Map dependencies between services to identify coupling, blast radius, and architectural debt.\n  - name: Developer Portal Integration\n    description: Integrate Compass with internal developer portals and CI/CD pipelines for automated component registration and event tracking.\n- type: Integrations\n  data:\n  - name: Jira\n    description: Native integration with Jira for linking components to project tracking and incident management workflows.\n  - name: Bitbucket\n    description: Connect Bitbucket repositories to Compass components for automated code health and deployment event tracking.\n  - name: GitHub\n    description: Integrate GitHub repositories and GitHub Actions CI/CD pipelines with Compass component events.\n  - name: PagerDuty\n    description: Ingest PagerDuty incident events into Compass for on-call and incident tracking scorecard criteria.\n\
  \  - name: Datadog\n    description: Connect Datadog monitoring data and deployment events to Compass component metrics.\n  - name: Terraform\n    description: Manage Compass resources via the Atlassian Operations Terraform provider for infrastructure-as-code workflows.\n- type: Solutions\n  data:\n  - name: Developer Experience Platform\n    description: Provide engineering teams with a centralized platform to understand, manage, and improve the health of their software systems.\n  - name: Platform Engineering\n    description: Enable platform engineering teams to enforce standards, track compliance, and improve developer productivity at scale.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atlassian-compass/refs/heads/main/apis.yml
tags:
- Atlassian
- Component Management
- Developer Experience
- Software Catalog
- GraphQL
url: https://raw.githubusercontent.com/api-evangelist/atlassian-compass/refs/heads/main/apis.yml
use_cases:
- description: Register and track all microservices, libraries, and software components with ownership and lifecycle metadata.
  name: Software Catalog Management
- description: Create scorecards to measure and improve engineering standards like on-call coverage, documentation, and security posture.
  name: Engineering Health Monitoring
- description: Ingest deployment and incident events to track DORA metrics including deployment frequency and change failure rate.
  name: DORA Metrics Tracking
- description: Map dependencies between services to identify coupling, blast radius, and architectural debt.
  name: Dependency Mapping
- description: Integrate Compass with internal developer portals and CI/CD pipelines for automated component registration and event tracking.
  name: Developer Portal Integration
---
