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
