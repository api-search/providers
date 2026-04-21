---
api_count: 2
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
