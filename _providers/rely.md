---
api_count: 1
api_specs:
- filename: rely-openapi.yml
  format: yaml
  label: Rely.io Public API
  slug: public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/openapi/rely-openapi.yml
apis:
- description: Full CRUD REST API for managing blueprints, entities, scorecards, self-service actions, and automations in the Rely.io internal developer portal. Authentication uses a long-lived Bearer API key.
  name: Rely.io Public API
  slug: public-api
capabilities:
- description: 'Unified workflow capability for platform engineering teams using Rely.io. Combines catalog management, scorecard evaluation, self-service action configuration, and automation management into a single '
  name: Rely.io Platform Engineering
  slug: platform-engineering
common:
- title: ''
  type: Website
  url: https://www.rely.io
- title: ''
  type: Documentation
  url: https://docs.rely.io
- title: ''
  type: GitHub Organization
  url: https://github.com/Rely-io
- title: ''
  type: GitHub SDK
  url: https://github.com/Rely-io/galaxy-oss
- title: ''
  type: Sign Up
  url: https://app.rely.io/register
- title: ''
  type: Demo
  url: https://demo.rely.io
- title: ''
  type: Support
  url: mailto:support@rely.io
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/rely-io
created: '2026-03-27'
description: Rely.io is an internal developer portal that aggregates engineering data, provides software catalogs with blueprints and entities, engineering scorecards, self-service developer actions, and workflow automation for platform engineering teams. The platform integrates with CI/CD pipelines, incident management, observability, and cloud providers to create a centralized service catalog with real-time data. Rely.io's Public REST API provides full CRUD access to blueprints, entities, scorecards, self-service actions, and automations using Bearer token authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Rely Context
  property_count: 13
  slug: rely-context
layout: provider
modified: '2026-05-02'
name: Rely.io
rules:
- name: Rely.io API Rules
  rule_count: 10
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 4
  slug: rely-rules
skills: []
slug: rely
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rely\nname: Rely.io\ndescription: >-\n  Rely.io is an internal developer portal that aggregates engineering data,\n  provides software catalogs with blueprints and entities, engineering\n  scorecards, self-service developer actions, and workflow automation for\n  platform engineering teams. The platform integrates with CI/CD pipelines,\n  incident management, observability, and cloud providers to create a\n  centralized service catalog with real-time data. Rely.io's Public REST API\n  provides full CRUD access to blueprints, entities, scorecards, self-service\n  actions, and automations using Bearer token authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Experience\n  - Internal Developer Portal\n  - Platform Engineering\n  - Software Catalog\n  - Service Catalog\n  - Engineering Scorecards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/apis.yml\ncreated:\
  \ '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rely:public-api\n    name: Rely.io Public API\n    description: >-\n      Full CRUD REST API for managing blueprints, entities, scorecards,\n      self-service actions, and automations in the Rely.io internal developer\n      portal. Authentication uses a long-lived Bearer API key.\n    humanURL: https://docs.rely.io/public-api\n    baseURL: https://api.rely.io\n    tags:\n      - Developer Experience\n      - Internal Developer Portal\n      - Platform Engineering\n      - Software Catalog\n      - Scorecards\n      - Self-Service Actions\n    properties:\n      - type: Documentation\n        url: https://docs.rely.io/public-api\n      - type: OpenAPI\n        url: openapi/rely-openapi.yml\n      - type: Getting Started\n        url: https://docs.rely.io/getting-started\n\ncommon:\n  - type: Website\n    url: https://www.rely.io\n  - type: Documentation\n    url: https://docs.rely.io\n  - type: GitHub\
  \ Organization\n    url: https://github.com/Rely-io\n  - type: GitHub SDK\n    url: https://github.com/Rely-io/galaxy-oss\n  - type: Sign Up\n    url: https://app.rely.io/register\n  - type: Demo\n    url: https://demo.rely.io\n  - type: Support\n    url: mailto:support@rely.io\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/rely-io\nfeatures:\n  - name: Software Catalog\n    description: >-\n      Centralized service catalog powered by blueprints and entities tracking\n      ownership, dependencies, documentation, and deployments.\n  - name: Engineering Scorecards\n    description: >-\n      Define and track production readiness, DORA metrics, and observability\n      standards across all services with automated scoring.\n  - name: Self-Service Actions\n    description: >-\n      Enable developers to scaffold services, provision cloud resources,\n      and trigger deployments via UI or API without platform team involvement.\n  - name: Automation Workflows\n    description:\
  \ >-\n      Create automation rules that respond to catalog changes and trigger\n      actions in integrated tools automatically.\n  - name: Plugin Integrations\n    description: >-\n      Galaxy-based plugin framework for connecting to GitHub, GitLab,\n      PagerDuty, Datadog, AWS, and other tools via self-hosted or managed agents.\n  - name: GitOps Support\n    description: >-\n      Manage blueprints, entities, scorecards, and actions as code in\n      Git repositories for version-controlled portal configuration.\nsolutions:\n  - name: Platform Engineering Portal\n    description: >-\n      Build an internal developer portal that gives developers self-service\n      access to infrastructure and eliminates toil from platform engineering teams.\n  - name: Service Ownership Tracking\n    description: >-\n      Track service ownership, runbooks, SLOs, and dependencies in a\n      centralized catalog updated automatically via CI/CD integrations.\n  - name: Engineering Standards Enforcement\n\
  \    description: >-\n      Define and enforce engineering standards via scorecards with leaderboards\n      that drive adoption across engineering teams.\n  - name: Developer Onboarding Automation\n    description: >-\n      Automate new service scaffolding, repository creation, and tool\n      provisioning via self-service actions tied to golden path templates.\nuseCases:\n  - name: Service Catalog Management\n    description: >-\n      Aggregate services, libraries, infrastructure resources, and teams into\n      a searchable catalog with real-time data from CI/CD and observability tools.\n  - name: Production Readiness Scoring\n    description: >-\n      Score services on production readiness criteria (on-call coverage,\n      SLO definitions, runbooks, deployment frequency) and track improvement.\n  - name: Self-Service Provisioning\n    description: >-\n      Allow developers to provision cloud infrastructure, create repositories,\n      and onboard new services without opening platform\
  \ team tickets.\nintegrations:\n  - name: GitHub Integration\n    description: Sync repositories, workflows, and deployment data to the catalog\n  - name: GitLab Integration\n    description: Sync GitLab projects, pipelines, and deployment visibility\n  - name: PagerDuty Integration\n    description: Surface on-call rotations and incident data in service catalog\n  - name: Datadog Integration\n    description: Pull monitoring metrics and SLO data into service scorecards\n  - name: AWS Integration\n    description: Track cloud resources and infrastructure entities in the catalog\n  - name: Kubernetes Integration\n    description: Discover and catalog Kubernetes workloads and deployments\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/apis.yml
tags:
- Developer Experience
- Internal Developer Portal
- Platform Engineering
- Software Catalog
- Service Catalog
- Engineering Scorecards
url: https://raw.githubusercontent.com/api-evangelist/rely/refs/heads/main/apis.yml
use_cases: []
---
