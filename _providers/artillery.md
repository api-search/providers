---
api_count: 1
apis:
- description: 'Artillery Cloud provides a hosted platform for running distributed load tests at scale, storing test results, team collaboration, and integrating with CI/CD pipelines. The Artillery Cloud API enables '
  name: Artillery Cloud API
  slug: artillery-cloud-api
common:
- title: Artillery Website
  type: Portal
  url: https://www.artillery.io/
- title: Documentation
  type: Documentation
  url: https://www.artillery.io/docs
- title: Artillery GitHub Organization
  type: GitHubOrganization
  url: https://github.com/artilleryio
- title: Artillery Source Repository
  type: GitHubRepository
  url: https://github.com/artilleryio/artillery
- title: Changelog
  type: ReleaseNotes
  url: https://github.com/artilleryio/artillery/blob/main/CHANGELOG.md
- title: Pricing
  type: Pricing
  url: https://www.artillery.io/pricing
created: '2026-03-25'
description: Artillery is an open source load testing and performance testing platform for APIs, microservices, and web applications. Built with Node.js and available as an npm package, Artillery supports HTTP/1, HTTP/2, WebSocket, Socket.IO, gRPC, and custom protocols through plugins. It includes a YAML-based test scenario definition language, a plugin ecosystem for extending functionality, and Artillery Cloud for distributed load testing, CI/CD integration, and centralized reporting. Artillery is used by developers, QA engineers, and SREs to run load tests, performance benchmarks, Playwright-based synthetic monitoring, and end-to-end tests at scale. The project is licensed under MPL-2.0 and maintained by Artilleryio.
features:
- description: Load test HTTP/1 and HTTP/2 REST APIs, GraphQL endpoints, and web applications with configurable virtual users, arrival rates, and scenario definitions.
  name: HTTP Load Testing
- description: Test real-time applications with WebSocket and Socket.IO protocol support, enabling load testing of chat, notifications, and streaming applications.
  name: WebSocket and Socket.IO Testing
- description: Run Playwright browser-based end-to-end scenarios under load, enabling realistic user simulation and synthetic monitoring from the same test framework.
  name: Playwright Integration
- description: Extensible plugin system with official plugins for gRPC, Kafka, AWS Lambda, Kinesis, and community plugins for many other protocols.
  name: Plugin Ecosystem
- description: Hosted cloud platform for running distributed load tests at massive scale across multiple cloud regions, with centralized results and team collaboration features.
  name: Artillery Cloud
- description: Human-readable YAML test scenario definitions supporting think time, loops, conditional logic, data CSV files, and custom JavaScript functions.
  name: YAML Test Scenarios
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Artillery GitHub Action for running load tests in CI/CD pipelines with automatic reporting and performance gate enforcement.
  name: GitHub Actions
- description: Artillery publishes metrics to Datadog for real-time monitoring and alerting during load test runs.
  name: Datadog
- description: Artillery can run distributed load tests using AWS Lambda as the execution backend, enabling serverless-scale testing.
  name: AWS Lambda
- description: Native Playwright integration for browser-based load testing and synthetic monitoring scenarios.
  name: Playwright
layout: provider
modified: '2026-04-19'
name: Artillery
skills: []
slug: artillery
solutions: []
source_yaml: "aid: artillery\nname: Artillery\ndescription: >-\n  Artillery is an open source load testing and performance testing platform for\n  APIs, microservices, and web applications. Built with Node.js and available\n  as an npm package, Artillery supports HTTP/1, HTTP/2, WebSocket, Socket.IO,\n  gRPC, and custom protocols through plugins. It includes a YAML-based test\n  scenario definition language, a plugin ecosystem for extending functionality,\n  and Artillery Cloud for distributed load testing, CI/CD integration, and\n  centralized reporting. Artillery is used by developers, QA engineers, and\n  SREs to run load tests, performance benchmarks, Playwright-based synthetic\n  monitoring, and end-to-end tests at scale. The project is licensed under\n  MPL-2.0 and maintained by Artilleryio.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/artillery/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  tags:\n  - Load Testing\n  - Performance Testing\n  - Open Source\n  - Testing\n  - DevOps\n  - Node.js\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: artillery:artillery-cloud-api\n    name: Artillery Cloud API\n    description: >-\n      Artillery Cloud provides a hosted platform for running distributed load\n      tests at scale, storing test results, team collaboration, and integrating\n      with CI/CD pipelines. The Artillery Cloud API enables programmatic\n      triggering of test runs, retrieval of test results, and management of\n      test configurations.\n    humanURL: https://www.artillery.io/docs/reference/cli/run-test\n    baseURL: https://app.artillery.io/api\n    tags:\n      - Load Testing\n      - Cloud\n      - CI/CD\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://www.artillery.io/docs/reference/cli/run-test\n      - type: GettingStarted\n        url: https://www.artillery.io/docs/get-started/get-artillery\n\
  common:\n  - type: Portal\n    url: https://www.artillery.io/\n    title: Artillery Website\n  - type: Documentation\n    url: https://www.artillery.io/docs\n    title: Documentation\n  - type: GitHubOrganization\n    url: https://github.com/artilleryio\n    title: Artillery GitHub Organization\n  - type: GitHubRepository\n    url: https://github.com/artilleryio/artillery\n    title: Artillery Source Repository\n  - type: ReleaseNotes\n    url: https://github.com/artilleryio/artillery/blob/main/CHANGELOG.md\n    title: Changelog\n  - type: Pricing\n    url: https://www.artillery.io/pricing\n    title: Pricing\n  - type: Features\n    data:\n      - name: HTTP Load Testing\n        description: >-\n          Load test HTTP/1 and HTTP/2 REST APIs, GraphQL endpoints, and web\n          applications with configurable virtual users, arrival rates, and\n          scenario definitions.\n      - name: WebSocket and Socket.IO Testing\n        description: >-\n          Test real-time applications\
  \ with WebSocket and Socket.IO protocol\n          support, enabling load testing of chat, notifications, and streaming\n          applications.\n      - name: Playwright Integration\n        description: >-\n          Run Playwright browser-based end-to-end scenarios under load, enabling\n          realistic user simulation and synthetic monitoring from the same\n          test framework.\n      - name: Plugin Ecosystem\n        description: >-\n          Extensible plugin system with official plugins for gRPC, Kafka, AWS\n          Lambda, Kinesis, and community plugins for many other protocols.\n      - name: Artillery Cloud\n        description: >-\n          Hosted cloud platform for running distributed load tests at massive\n          scale across multiple cloud regions, with centralized results and\n          team collaboration features.\n      - name: YAML Test Scenarios\n        description: >-\n          Human-readable YAML test scenario definitions supporting think time,\n \
  \         loops, conditional logic, data CSV files, and custom JavaScript\n          functions.\n  - type: UseCases\n    data:\n      - name: API Load Testing\n        description: >-\n          Backend developers and QA engineers run load tests against REST and\n          GraphQL APIs to identify performance bottlenecks and ensure stability\n          under expected traffic volumes.\n      - name: CI/CD Performance Gates\n        description: >-\n          Engineering teams integrate Artillery into CI/CD pipelines to run\n          performance tests on every pull request, failing builds that exceed\n          latency or error rate thresholds.\n      - name: Synthetic Monitoring\n        description: >-\n          SREs use Artillery with Playwright to run synthetic monitors that\n          continuously validate critical user journeys from multiple cloud\n          regions.\n      - name: Pre-Launch Stress Testing\n        description: >-\n          Product teams run stress tests before\
  \ major launches or sales events\n          to identify the maximum capacity of their infrastructure.\n  - type: Integrations\n    data:\n      - name: GitHub Actions\n        description: >-\n          Official Artillery GitHub Action for running load tests in CI/CD\n          pipelines with automatic reporting and performance gate enforcement.\n      - name: Datadog\n        description: >-\n          Artillery publishes metrics to Datadog for real-time monitoring and\n          alerting during load test runs.\n      - name: AWS Lambda\n        description: >-\n          Artillery can run distributed load tests using AWS Lambda as the\n          execution backend, enabling serverless-scale testing.\n      - name: Playwright\n        description: >-\n          Native Playwright integration for browser-based load testing and\n          synthetic monitoring scenarios.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/artillery/refs/heads/main/apis.yml
tags:
- Load Testing
- Performance Testing
- Open Source
- Testing
- DevOps
- Node.js
url: https://raw.githubusercontent.com/api-evangelist/artillery/refs/heads/main/apis.yml
use_cases:
- description: Backend developers and QA engineers run load tests against REST and GraphQL APIs to identify performance bottlenecks and ensure stability under expected traffic volumes.
  name: API Load Testing
- description: Engineering teams integrate Artillery into CI/CD pipelines to run performance tests on every pull request, failing builds that exceed latency or error rate thresholds.
  name: CI/CD Performance Gates
- description: SREs use Artillery with Playwright to run synthetic monitors that continuously validate critical user journeys from multiple cloud regions.
  name: Synthetic Monitoring
- description: Product teams run stress tests before major launches or sales events to identify the maximum capacity of their infrastructure.
  name: Pre-Launch Stress Testing
---
