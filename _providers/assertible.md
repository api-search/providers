---
api_count: 1
apis:
- description: The Assertible API enables programmatic management of API tests, test suites, and monitoring configurations for automated quality assurance. It allows triggering test runs, managing webhooks, and acce
  name: Assertible API
  slug: assertible-api
common:
- title: Assertible Website
  type: Portal
  url: https://assertible.com/
- title: Documentation
  type: Documentation
  url: https://assertible.com/docs
- title: Blog
  type: Blog
  url: https://assertible.com/blog
- title: Sign Up
  type: SignUp
  url: https://assertible.com/signup
- title: Login
  type: Login
  url: https://assertible.com/login
- title: Assertible GitHub Organization
  type: GitHubOrganization
  url: https://github.com/assertible
created: '2025-01-08'
description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body content, and performance, with integrations for CI/CD pipelines and notifications. Assertible supports scheduled API monitoring, deployment testing triggered via webhooks, and team collaboration for API quality assurance workflows. The platform integrates with GitHub, Slack, PagerDuty, and other tools for seamless notification and incident management.
features:
- description: Define assertions on API response status codes, headers, response body content, JSON Schema compliance, and response time to validate API behavior.
  name: API Test Assertions
- description: Run API tests on a scheduled basis (hourly, daily, etc.) to continuously monitor production APIs for availability and correctness.
  name: Scheduled Monitoring
- description: Trigger Assertible test suites automatically after deployments via webhooks, ensuring API quality gates are enforced in CI/CD pipelines.
  name: Deployment Testing
- description: Validate API responses against JSON Schema definitions to ensure response payloads match expected data structures.
  name: JSON Schema Validation
- description: Share test suites and API monitoring configurations across teams with role-based access and shared notification channels.
  name: Team Collaboration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with GitHub for triggering tests on pull requests and deployment events through GitHub Actions and webhooks.
  name: GitHub
- description: Slack notifications for test failures, alerts, and monitoring events from Assertible test runs.
  name: Slack
- description: PagerDuty integration for escalating API monitoring failures to on-call teams for incident response.
  name: PagerDuty
- description: Integration with CircleCI pipelines for running Assertible test suites as part of continuous integration workflows.
  name: CircleCI
layout: provider
modified: '2026-04-19'
name: Assertible
skills: []
slug: assertible
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: assertible\nname: Assertible\ndescription: >-\n  Assertible provides a reliable first line of defense against web service\n  failures by providing simple and powerful assertions to test and monitor APIs.\n  It enables automated API testing with assertions on response status, headers,\n  body content, and performance, with integrations for CI/CD pipelines and\n  notifications. Assertible supports scheduled API monitoring, deployment\n  testing triggered via webhooks, and team collaboration for API quality\n  assurance workflows. The platform integrates with GitHub, Slack, PagerDuty,\n  and other tools for seamless notification and incident management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Testing\n  - Monitoring\n  - Quality Assurance\n  - Testing\n  - CI/CD\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/assertible/refs/heads/main/apis.yml\n\
  apis:\n  - aid: assertible:assertible-api\n    name: Assertible API\n    description: >-\n      The Assertible API enables programmatic management of API tests, test\n      suites, and monitoring configurations for automated quality assurance.\n      It allows triggering test runs, managing webhooks, and accessing test\n      results programmatically for CI/CD integration.\n    humanURL: https://assertible.com/\n    baseURL: https://api.assertible.com\n    tags:\n      - API Testing\n      - Monitoring\n      - Quality Assurance\n    properties:\n      - type: Documentation\n        url: https://assertible.com/docs\n      - type: GettingStarted\n        url: https://assertible.com/docs/guide/getting-started\n      - type: Authentication\n        url: https://assertible.com/docs/guide/authentication\ncommon:\n  - type: Portal\n    url: https://assertible.com/\n    title: Assertible Website\n  - type: Documentation\n    url: https://assertible.com/docs\n    title: Documentation\n  - type:\
  \ Blog\n    url: https://assertible.com/blog\n    title: Blog\n  - type: SignUp\n    url: https://assertible.com/signup\n    title: Sign Up\n  - type: Login\n    url: https://assertible.com/login\n    title: Login\n  - type: GitHubOrganization\n    url: https://github.com/assertible\n    title: Assertible GitHub Organization\n  - type: Features\n    data:\n      - name: API Test Assertions\n        description: >-\n          Define assertions on API response status codes, headers, response\n          body content, JSON Schema compliance, and response time to validate\n          API behavior.\n      - name: Scheduled Monitoring\n        description: >-\n          Run API tests on a scheduled basis (hourly, daily, etc.) to\n          continuously monitor production APIs for availability and correctness.\n      - name: Deployment Testing\n        description: >-\n          Trigger Assertible test suites automatically after deployments via\n          webhooks, ensuring API quality gates are\
  \ enforced in CI/CD pipelines.\n      - name: JSON Schema Validation\n        description: >-\n          Validate API responses against JSON Schema definitions to ensure\n          response payloads match expected data structures.\n      - name: Team Collaboration\n        description: >-\n          Share test suites and API monitoring configurations across teams\n          with role-based access and shared notification channels.\n  - type: UseCases\n    data:\n      - name: Post-Deployment Validation\n        description: >-\n          Development teams trigger Assertible test suites after each deployment\n          to verify APIs are functioning correctly before traffic shifts.\n      - name: API Uptime Monitoring\n        description: >-\n          Operations teams use scheduled Assertible tests to monitor API\n          availability and receive alerts when endpoints fail.\n      - name: API Contract Testing\n        description: >-\n          QA teams use JSON Schema assertions to\
  \ validate that API responses\n          match documented contracts and catch breaking changes.\n  - type: Integrations\n    data:\n      - name: GitHub\n        description: >-\n          Integration with GitHub for triggering tests on pull requests and\n          deployment events through GitHub Actions and webhooks.\n      - name: Slack\n        description: >-\n          Slack notifications for test failures, alerts, and monitoring events\n          from Assertible test runs.\n      - name: PagerDuty\n        description: >-\n          PagerDuty integration for escalating API monitoring failures to\n          on-call teams for incident response.\n      - name: CircleCI\n        description: >-\n          Integration with CircleCI pipelines for running Assertible test\n          suites as part of continuous integration workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/assertible/refs/heads/main/apis.yml
tags:
- API Testing
- Monitoring
- Quality Assurance
- Testing
- CI/CD
url: https://raw.githubusercontent.com/api-evangelist/assertible/refs/heads/main/apis.yml
use_cases:
- description: Development teams trigger Assertible test suites after each deployment to verify APIs are functioning correctly before traffic shifts.
  name: Post-Deployment Validation
- description: Operations teams use scheduled Assertible tests to monitor API availability and receive alerts when endpoints fail.
  name: API Uptime Monitoring
- description: QA teams use JSON Schema assertions to validate that API responses match documented contracts and catch breaking changes.
  name: API Contract Testing
---
