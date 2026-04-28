---
api_count: 5
apis:
- description: CloudBees CI is a hardened, enterprise distribution of Jenkins. The REST API is the Jenkins remote access API exposed at /api on every controller and on individual jobs, runs, queues and nodes. Caller
  name: CloudBees CI REST API
  slug: ci
- description: 'The CloudBees CD/RO (Continuous Delivery / Release Orchestration) REST API exposes resources for pipelines, releases, environments, applications, deployments, projects and resources. Operations cover '
  name: CloudBees CD/RO REST API
  slug: cd-ro
- description: The CloudBees Feature Management REST API (formerly Rollout) provides programmatic access to applications, environments, feature flags, experiments, target groups, audit logs, and users. Authenticatio
  name: CloudBees Feature Management REST API
  slug: feature-management
- description: CloudBees Unify is the modern, opinionated software delivery platform that unifies CI, CD, feature management, analytics, and security into a single workflow. The platform exposes APIs for managing or
  name: CloudBees Unify Platform API
  slug: unify
- description: The CloudBees CD plugin for Jenkins exposes Jenkins pipeline steps that call CloudBees CD/RO REST endpoints — triggering pipelines, running releases, deploying applications, and pulling artifacts from
  name: CloudBees CD/RO Jenkins Plugin Steps
  slug: jenkins-plugin
capabilities:
- description: ''
  name: Feature Management
  slug: feature-management
common:
- title: ''
  type: Website
  url: https://www.cloudbees.com/
- title: ''
  type: Documentation
  url: https://docs.cloudbees.com/
- title: ''
  type: Support
  url: https://support.cloudbees.com/
- title: ''
  type: Privacy Policy
  url: https://www.cloudbees.com/privacy
- title: ''
  type: Plugins
  url: https://docs.cloudbees.com/plugins/ci
- title: ''
  type: JSON-LD
  url: json-ld/cloudbees-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudbees-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/feature-management.yaml
created: '2025-01-08'
description: CloudBees provides software delivery automation across continuous integration, continuous deployment, release orchestration, and feature management. Their developer surface includes the CloudBees CI REST API (an extension of the Jenkins REST API), the CloudBees CD/RO REST API for release orchestration, the CloudBees Feature Management REST API (formerly Rollout) for feature flags and environments, and the CloudBees Unify Platform API for the modern unified delivery platform. APIs are generally JSON, token-authenticated, and follow REST conventions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudbees Context
  property_count: 11
  slug: cloudbees-context
layout: provider
modified: '2026-04-23'
name: CloudBees
rules:
- name: CloudBees API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 6
  slug: cloudbees-rules
skills: []
slug: cloudbees
solutions: []
tags:
- CI/CD
- Continuous Delivery
- Continuous Integration
- DevOps
- Feature Flags
- Feature Management
- Jenkins
- Release Orchestration
- Software Delivery
url: https://raw.githubusercontent.com/api-evangelist/cloudbees/refs/heads/main/apis.yml
use_cases: []
---
