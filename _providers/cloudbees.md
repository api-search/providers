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
source_filename: apis.yml
source_yaml: "aid: cloudbees\nurl: https://raw.githubusercontent.com/api-evangelist/cloudbees/refs/heads/main/apis.yml\nname: CloudBees\ncreated: '2025-01-08'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - CI/CD\n  - Continuous Delivery\n  - Continuous Integration\n  - DevOps\n  - Feature Flags\n  - Feature Management\n  - Jenkins\n  - Release Orchestration\n  - Software Delivery\ndescription: >-\n  CloudBees provides software delivery automation across continuous\n  integration, continuous deployment, release orchestration, and feature\n  management. Their developer surface includes the CloudBees CI REST API\n  (an extension of the Jenkins REST API), the CloudBees CD/RO REST API for\n  release orchestration, the CloudBees Feature Management REST API\n  (formerly Rollout) for feature flags and environments, and the CloudBees\n\
  \  Unify Platform API for the modern unified delivery platform. APIs are\n  generally JSON, token-authenticated, and follow REST conventions.\napis:\n  - aid: cloudbees:ci\n    name: CloudBees CI REST API\n    tags:\n      - CI/CD\n      - Continuous Integration\n      - Jenkins\n      - Pipelines\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://example.cloudbees.com\n    humanURL: https://docs.cloudbees.com/docs/cloudbees-ci-kb/latest/best-practices/best-practice-for-using-jenkins-rest-api\n    properties:\n      - url: https://docs.cloudbees.com/docs/cloudbees-ci-kb/latest/best-practices/best-practice-for-using-jenkins-rest-api\n        type: Documentation\n      - url: https://docs.cloudbees.com/docs/release-notes/latest/cloudbees-ci/\n        type: Release Notes\n    description: >-\n      CloudBees CI is a hardened, enterprise distribution of Jenkins. The\n      REST API is the Jenkins remote access API exposed at /api on\
  \ every\n      controller and on individual jobs, runs, queues and nodes. Callers\n      authenticate with a username and API token in HTTP basic auth and can\n      list/create jobs, trigger builds, fetch build status and console logs,\n      manage credentials, and inspect operations centers. Responses are\n      available as JSON, XML, or Python.\n  - aid: cloudbees:cd-ro\n    name: CloudBees CD/RO REST API\n    tags:\n      - Continuous Delivery\n      - DevOps\n      - Pipelines\n      - Release Orchestration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://example-cd.cloudbees.com/rest/v1.0\n    humanURL: https://docs.cloudbees.com/docs/cloudbees-cd/latest/api/\n    properties:\n      - url: https://docs.cloudbees.com/docs/cloudbees-cd/latest/api/\n        type: Documentation\n      - url: https://docs.cloudbees.com/plugins/cd/ec-jenkins\n        type: Jenkins Plugin\n    description: >-\n      The CloudBees CD/RO (Continuous\
  \ Delivery / Release Orchestration) REST\n      API exposes resources for pipelines, releases, environments,\n      applications, deployments, projects and resources. Operations cover\n      modelling deployment pipelines, launching releases, tracking stages,\n      managing environments and inventories, and integrating with Jenkins\n      and other CI tools.\n  - aid: cloudbees:feature-management\n    name: CloudBees Feature Management REST API\n    tags:\n      - Experimentation\n      - Feature Flags\n      - Feature Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://x-api.rollout.io/public-api\n    humanURL: https://docs.cloudbees.com/docs/cloudbees-feature-management-rest-api/latest/introduction\n    properties:\n      - url: https://docs.cloudbees.com/docs/cloudbees-feature-management-rest-api/latest/introduction\n        type: Documentation\n      - url: https://docs.cloudbees.com/docs/cloudbees-feature-management-rest-api/latest/environments\n\
  \        type: Environments\n      - url: https://docs.cloudbees.com/docs/cloudbees-feature-management/latest/rest-api\n        type: Reference\n    description: >-\n      The CloudBees Feature Management REST API (formerly Rollout) provides\n      programmatic access to applications, environments, feature flags,\n      experiments, target groups, audit logs, and users. Authentication uses\n      a bearer token in the Authorization header. The API enforces a one\n      request per second rate limit per IP, returning HTTP 555 when\n      exceeded.\n  - aid: cloudbees:unify\n    name: CloudBees Unify Platform API\n    tags:\n      - DevOps\n      - Platform\n      - Software Delivery\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudbees.com/\n    properties:\n      - url: https://docs.cloudbees.com/\n        type: Documentation\n    description: >-\n      CloudBees Unify is the modern, opinionated software delivery platform\n\
  \      that unifies CI, CD, feature management, analytics, and security into\n      a single workflow. The platform exposes APIs for managing\n      organizations, components, workflows, environments, feature flags,\n      and analytics; authentication is via personal access tokens and the\n      surface is the recommended target for new integrations.\n  - aid: cloudbees:jenkins-plugin\n    name: CloudBees CD/RO Jenkins Plugin Steps\n    tags:\n      - Continuous Delivery\n      - Jenkins\n      - Plugin\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.jenkins.io/doc/pipeline/steps/electricflow/\n    properties:\n      - url: https://www.jenkins.io/doc/pipeline/steps/electricflow/\n        type: Documentation\n      - url: https://plugins.jenkins.io/electricflow\n        type: Plugin\n    description: >-\n      The CloudBees CD plugin for Jenkins exposes Jenkins pipeline steps\n      that call CloudBees CD/RO REST endpoints\
  \ — triggering pipelines,\n      running releases, deploying applications, and pulling artifacts from\n      Jenkins build outputs into CD/RO release flows.\ncommon:\n  - type: Website\n    url: https://www.cloudbees.com/\n  - type: Documentation\n    url: https://docs.cloudbees.com/\n  - type: Support\n    url: https://support.cloudbees.com/\n  - type: Privacy Policy\n    url: https://www.cloudbees.com/privacy\n  - type: Plugins\n    url: https://docs.cloudbees.com/plugins/ci\n  - type: JSON-LD\n    url: json-ld/cloudbees-context.jsonld\n  - type: Spectral\n    url: rules/cloudbees-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/feature-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudbees/refs/heads/main/apis.yml
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
