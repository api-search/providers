---
api_count: 2
api_specs:
- filename: apache-jmeter-rest-api.yaml
  format: yaml
  label: Apache JMeter REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/openapi/apache-jmeter-rest-api.yaml
apis:
- description: The JMeter REST API provides HTTP endpoints for remotely starting, stopping, and monitoring load tests, as well as retrieving test results and status information.
  name: Apache JMeter REST API
  slug: rest-api
- description: JMeter command-line interface for running load tests in non-GUI mode for CI/CD integration, including options for test plan execution, result reporting, and distributed testing.
  name: Apache JMeter CLI
  slug: cli
capabilities:
- description: Workflow capability for QA engineers and performance engineers to manage and monitor Apache JMeter load tests via the REST API.
  name: Apache JMeter Load Test Management
  slug: load-test-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/jmeter
- title: ''
  type: Documentation
  url: https://jmeter.apache.org/usermanual/
- title: ''
  type: GettingStarted
  url: https://jmeter.apache.org/usermanual/get-started.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Blog
  url: https://blogs.apache.org/jmeter/
- title: ''
  type: Versioning
  url: https://jmeter.apache.org/changes.html
- title: ''
  type: ReleaseNotes
  url: https://jmeter.apache.org/changes.html
- title: ''
  type: SpectralRules
  url: rules/apache-jmeter-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-jmeter-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/load-test-management.yaml
created: '2026-03-16'
description: Apache JMeter is an open-source Java application designed for load testing functional behavior and measuring performance. It supports web applications, REST APIs, databases, LDAP, FTP, and other protocols. Licensed under Apache 2.0 and governed by the Apache Software Foundation.
features:
- description: Test web applications and REST APIs with configurable thread groups and ramp-up.
  name: HTTP Load Testing
- description: Support for HTTP, HTTPS, FTP, JDBC, LDAP, SMTP, TCP, and JMS.
  name: Protocol Support
- description: Distributed load generation using JMeter remote testing architecture.
  name: Distributed Testing
- description: Built-in listeners and HTML dashboard reporting for test results.
  name: Rich Reporting
- description: Extensive plugin marketplace for additional samplers, listeners, and functions.
  name: Plugin Ecosystem
- description: Non-GUI mode and REST API for integration with Jenkins, GitHub Actions, and more.
  name: CI/CD Integration
- description: Response assertion engine for functional validation during load tests.
  name: Assertions
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: JMeter Performance Plugin for integrating load tests in Jenkins pipelines.
  name: Jenkins
- description: Run JMeter tests via CLI in GitHub Actions workflows.
  name: GitHub Actions
- description: Stream JMeter results to InfluxDB for real-time Grafana dashboards.
  name: Grafana and InfluxDB
- description: JMeter Maven Plugin for running tests as part of Maven builds.
  name: Maven
jsonld:
- class_count: 4
  name: Apache Jmeter Rest Api Context
  property_count: 15
  slug: apache-jmeter-rest-api-context
layout: provider
modified: '2026-04-19'
name: Apache JMeter
rules:
- name: Apache JMeter API Rules
  rule_count: 12
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 2
  slug: apache-jmeter-spectral-rules
skills: []
slug: apache-jmeter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-jmeter\nname: Apache JMeter\ndescription: >-\n  Apache JMeter is an open-source Java application designed for load testing functional behavior and measuring performance. It supports web applications, REST APIs, databases, LDAP, FTP, and other protocols. Licensed under Apache 2.0 and governed by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Testing\n  - Java\n  - Load Testing\n  - Open Source\n  - Performance Testing\n  - Stress Testing\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-jmeter:rest-api\n    name: Apache JMeter REST API\n    description: >-\n      The JMeter REST API provides HTTP endpoints for remotely starting, stopping, and monitoring load tests, as well as retrieving\
  \ test results and status information.\n    humanURL: https://jmeter.apache.org/usermanual/remote-test.html\n    tags:\n      - Performance Testing\n      - REST\n      - Test Control\n    properties:\n      - type: Documentation\n        url: https://jmeter.apache.org/usermanual/remote-test.html\n      - type: OpenAPI\n        url: openapi/apache-jmeter-rest-api.yaml\n\n  - aid: apache-jmeter:cli\n    name: Apache JMeter CLI\n    description: >-\n      JMeter command-line interface for running load tests in non-GUI mode for CI/CD integration, including options for test plan execution, result reporting, and distributed testing.\n    humanURL: https://jmeter.apache.org/usermanual/get-started.html#non_gui\n    tags:\n      - CLI\n      - Performance Testing\n    properties:\n      - type: Documentation\n        url: https://jmeter.apache.org/usermanual/get-started.html#non_gui\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url:\
  \ https://github.com/apache/jmeter\n  - type: Documentation\n    url: https://jmeter.apache.org/usermanual/\n  - type: GettingStarted\n    url: https://jmeter.apache.org/usermanual/get-started.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Blog\n    url: https://blogs.apache.org/jmeter/\n  - type: Versioning\n    url: https://jmeter.apache.org/changes.html\n  - type: ReleaseNotes\n    url: https://jmeter.apache.org/changes.html\n  - type: SpectralRules\n    url: rules/apache-jmeter-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-jmeter-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/load-test-management.yaml\n  - type: Features\n    data:\n      - name: HTTP Load Testing\n        description: Test web applications and REST APIs with configurable thread groups and ramp-up.\n      - name: Protocol Support\n        description: Support for HTTP, HTTPS, FTP, JDBC, LDAP, SMTP, TCP, and JMS.\n      - name:\
  \ Distributed Testing\n        description: Distributed load generation using JMeter remote testing architecture.\n      - name: Rich Reporting\n        description: Built-in listeners and HTML dashboard reporting for test results.\n      - name: Plugin Ecosystem\n        description: Extensive plugin marketplace for additional samplers, listeners, and functions.\n      - name: CI/CD Integration\n        description: Non-GUI mode and REST API for integration with Jenkins, GitHub Actions, and more.\n      - name: Assertions\n        description: Response assertion engine for functional validation during load tests.\n  - type: UseCases\n    data:\n      - name: API Performance Testing\n        description: Measure REST API response times and throughput under load.\n      - name: Web Application Load Testing\n        description: Simulate concurrent users on web applications to find performance bottlenecks.\n      - name: CI/CD Performance Gates\n        description: Integrate performance\
  \ testing into CI/CD pipelines with automated pass/fail criteria.\n      - name: Stress Testing\n        description: Determine system breaking points through progressive load increase.\n  - type: Integrations\n    data:\n      - name: Jenkins\n        description: JMeter Performance Plugin for integrating load tests in Jenkins pipelines.\n      - name: GitHub Actions\n        description: Run JMeter tests via CLI in GitHub Actions workflows.\n      - name: Grafana and InfluxDB\n        description: Stream JMeter results to InfluxDB for real-time Grafana dashboards.\n      - name: Maven\n        description: JMeter Maven Plugin for running tests as part of Maven builds.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/apis.yml
tags:
- API Testing
- Java
- Load Testing
- Open Source
- Performance Testing
- Stress Testing
url: https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/apis.yml
use_cases:
- description: Measure REST API response times and throughput under load.
  name: API Performance Testing
- description: Simulate concurrent users on web applications to find performance bottlenecks.
  name: Web Application Load Testing
- description: Integrate performance testing into CI/CD pipelines with automated pass/fail criteria.
  name: CI/CD Performance Gates
- description: Determine system breaking points through progressive load increase.
  name: Stress Testing
---
