---
api_count: 5
apis:
- description: The CircleCI REST API v2 provides programmatic access to CircleCI services for managing pipelines, projects, workflows, jobs, and users. Developers can trigger pipelines, retrieve build status, manage
  name: CircleCI REST API V2
  slug: rest-api-v2
- description: The CircleCI REST API v1 is the legacy API that provides access to build information, project details, and user data. While still available, CircleCI recommends migrating to the v2 API for newer featu
  name: CircleCI REST API V1
  slug: rest-api-v1
- description: The CircleCI Self-Hosted Runner API enables management and execution of jobs on self-hosted runner infrastructure. It provides endpoints for listing available runners, managing runner tasks, and query
  name: CircleCI Self-Hosted Runner API
  slug: runner-api
- description: CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings to notify ext
  name: CircleCI Webhooks
  slug: webhooks
- description: CircleCI Orbs are shareable, reusable packages of CircleCI configuration that simplify build setup and integration with third-party tools. The Orbs Registry on the CircleCI Developer Hub provides a se
  name: CircleCI Orbs Registry
  slug: orbs
asyncapis:
- description: CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings or the API to
  name: CircleCI Webhooks
  slug: circleci-webhooks-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://circleci.com/
- title: ''
  type: Portal
  url: https://circleci.com/developer
- title: ''
  type: Documentation
  url: https://circleci.com/docs/
- title: ''
  type: Status
  url: https://status.circleci.com/
- title: ''
  type: Support
  url: https://support.circleci.com/
- title: ''
  type: Blog
  url: https://circleci.com/blog/
- title: ''
  type: Privacy Policy
  url: https://circleci.com/privacy/
- title: ''
  type: Terms of Service
  url: https://circleci.com/terms-of-service/
- title: ''
  type: Login
  url: https://app.circleci.com/
- title: ''
  type: JSON-LD
  url: json-ld/circleci-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/circleci-pipeline-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/circleci-workflow-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/circleci-webhook-event-schema.json
- title: ''
  type: Spectral
  url: rules/circleci-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/circleci-capabilities.yml
created: '2025-03-05'
description: CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer surface includes the REST API v2 (the recommended modern interface), the legacy v1 REST API, a Self-Hosted Runner API, webhooks for real-time event notifications, and the Orbs Registry of reusable configuration packages. Authentication is via a personal or project Circle-Token sent in the Circle-Token header; responses are JSON.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Circleci Context
  property_count: 10
  slug: circleci-context
layout: provider
modified: '2026-04-23'
name: CircleCI
rules:
- name: CircleCI API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: circleci-rules
skills: []
slug: circleci
solutions: []
tags:
- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml
use_cases: []
---
