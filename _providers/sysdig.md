---
api_count: 2
api_specs:
- filename: sysdig-monitor-openapi.yml
  format: yaml
  label: Sysdig Monitor
  slug: sysdig-monitor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-monitor-openapi.yml
- filename: sysdig-secure-openapi.yml
  format: yaml
  label: Sysdig Secure
  slug: sysdig-secure
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-secure-openapi.yml
apis:
- description: The Sysdig Monitor API provides programmatic access to monitoring and observability capabilities including dashboards, alerts, events, metrics, teams, notification channels, and scanning results for c
  name: Sysdig Monitor
  slug: sysdig-monitor
- description: The Sysdig Secure API provides programmatic access to cloud and container security capabilities including vulnerability management, runtime policies, compliance checks, activity audit, incident respon
  name: Sysdig Secure
  slug: sysdig-secure
capabilities:
- description: 'Unified workflow capability combining Sysdig Monitor and Sysdig Secure for cloud and container security monitoring. Enables security teams to correlate runtime security events with monitoring alerts, '
  name: Sysdig Cloud Security Monitoring
  slug: cloud-security-monitoring
common:
- title: ''
  type: Website
  url: https://sysdig.com/
- title: ''
  type: Documentation
  url: https://docs.sysdig.com/
- title: ''
  type: Developer Portal
  url: https://docs.sysdig.com/en/developer-tools/
- title: ''
  type: Getting Started
  url: https://docs.sysdig.com/en/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/sysdiglabs
- title: ''
  type: Blog
  url: https://sysdig.com/blog/
- title: ''
  type: Pricing
  url: https://sysdig.com/pricing/
- title: ''
  type: Sign Up
  url: https://sysdig.com/company/free-trial/
- title: ''
  type: Terraform Provider
  url: https://registry.terraform.io/providers/sysdiglabs/sysdig/latest
- title: ''
  type: Python SDK
  url: https://github.com/sysdiglabs/sysdig-sdk-python
- title: ''
  type: CLI
  url: https://sysdiglabs.github.io/sysdig-platform-cli/
- title: ''
  type: Kubernetes Operator
  url: https://github.com/sysdiglabs/sysdig-operator
- title: ''
  type: Helm Charts
  url: https://github.com/sysdiglabs/charts
- title: ''
  type: Spectral Rules
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/rules/sysdig-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/capabilities/cloud-security-monitoring.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/vocabulary/sysdig-vocabulary.yml
- title: ''
  type: Change Log
  url: https://docs.sysdig.com/en/release-notes/
- title: ''
  type: Support
  url: https://sysdig.com/support/
- title: ''
  type: Status
  url: https://status.sysdig.com/
created: '2026-03-26'
description: Sysdig is a cloud and container security platform that provides runtime threat detection, vulnerability management, cloud security posture management (CSPM), compliance automation, and observability for containers, Kubernetes, and cloud environments. Sysdig Monitor offers full-stack monitoring and alerting while Sysdig Secure delivers runtime security, vulnerability scanning, policy enforcement, incident response, and compliance reporting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 31
  name: Sysdig Context
  property_count: 0
  slug: sysdig-context
layout: provider
modified: '2026-05-03'
name: Sysdig
rules:
- name: Sysdig API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: sysdig-rules
skills: []
slug: sysdig
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sysdig\nname: Sysdig\ndescription: >-\n  Sysdig is a cloud and container security platform that provides runtime threat\n  detection, vulnerability management, cloud security posture management (CSPM),\n  compliance automation, and observability for containers, Kubernetes, and cloud\n  environments. Sysdig Monitor offers full-stack monitoring and alerting while\n  Sysdig Secure delivers runtime security, vulnerability scanning, policy\n  enforcement, incident response, and compliance reporting.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Security\n  - Containers\n  - Kubernetes\n  - Runtime Security\n  - Security\n  - Vulnerability Management\n  - Monitoring\n  - Observability\n  - CSPM\n  - Compliance\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: sysdig:sysdig-monitor\n\
  \    name: Sysdig Monitor\n    description: >-\n      The Sysdig Monitor API provides programmatic access to monitoring and\n      observability capabilities including dashboards, alerts, events, metrics,\n      teams, notification channels, and scanning results for cloud-native\n      environments.\n    humanURL: https://docs.sysdig.com/en/developer-tools/sysdig-api/\n    baseURL: https://api.us1.sysdig.com\n    tags:\n      - Monitoring\n      - Observability\n      - Alerts\n      - Dashboards\n      - Metrics\n      - Events\n    properties:\n      - type: Documentation\n        url: https://docs.sysdig.com/en/developer-tools/sysdig-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-monitor-openapi.yml\n      - type: Getting Started\n        url: https://docs.sysdig.com/en/getting-started/\n      - type: Authentication\n        url: https://docs.sysdig.com/en/developer-tools/sysdig-api/\n  \
  \  contact:\n      - FN: Sysdig Support\n        url: https://sysdig.com/support/\n\n  - aid: sysdig:sysdig-secure\n    name: Sysdig Secure\n    description: >-\n      The Sysdig Secure API provides programmatic access to cloud and container\n      security capabilities including vulnerability management, runtime policies,\n      compliance checks, activity audit, incident response, image scanning,\n      SBOM retrieval, and Falco rules management.\n    humanURL: https://docs.sysdig.com/en/developer-tools/sysdig-api/\n    baseURL: https://api.us1.sysdig.com\n    tags:\n      - Security\n      - Vulnerability Management\n      - Compliance\n      - Runtime Security\n      - Falco\n      - Scanning\n      - CSPM\n    properties:\n      - type: Documentation\n        url: https://docs.sysdig.com/en/developer-tools/sysdig-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/openapi/sysdig-secure-openapi.yml\n      -\
  \ type: Getting Started\n        url: https://docs.sysdig.com/en/getting-started/\n    contact:\n      - FN: Sysdig Support\n        url: https://sysdig.com/support/\n\ncommon:\n  - type: Website\n    url: https://sysdig.com/\n  - type: Documentation\n    url: https://docs.sysdig.com/\n  - type: Developer Portal\n    url: https://docs.sysdig.com/en/developer-tools/\n  - type: Getting Started\n    url: https://docs.sysdig.com/en/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/sysdiglabs\n  - type: Blog\n    url: https://sysdig.com/blog/\n  - type: Pricing\n    url: https://sysdig.com/pricing/\n  - type: Sign Up\n    url: https://sysdig.com/company/free-trial/\n  - type: Terraform Provider\n    url: https://registry.terraform.io/providers/sysdiglabs/sysdig/latest\n  - type: Python SDK\n    url: https://github.com/sysdiglabs/sysdig-sdk-python\n  - type: CLI\n    url: https://sysdiglabs.github.io/sysdig-platform-cli/\n  - type: Kubernetes Operator\n    url: https://github.com/sysdiglabs/sysdig-operator\n\
  \  - type: Helm Charts\n    url: https://github.com/sysdiglabs/charts\n  - type: Spectral Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/rules/sysdig-rules.yml\n  - type: Naftiko Capabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/capabilities/cloud-security-monitoring.yaml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/vocabulary/sysdig-vocabulary.yml\n  - type: Change Log\n    url: https://docs.sysdig.com/en/release-notes/\n  - type: Support\n    url: https://sysdig.com/support/\n  - type: Status\n    url: https://status.sysdig.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/apis.yml
tags:
- Cloud Security
- Containers
- Kubernetes
- Runtime Security
- Security
- Vulnerability Management
- Monitoring
- Observability
- CSPM
- Compliance
url: https://raw.githubusercontent.com/api-evangelist/sysdig/refs/heads/main/apis.yml
use_cases: []
---
