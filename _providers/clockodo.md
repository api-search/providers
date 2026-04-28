---
api_count: 1
apis:
- description: The Clockodo API is a REST interface at my.clockodo.com that lets developers automate time tracking and project management. v2 endpoints under /api/v2 cover entries, customers, projects, services, use
  name: Clockodo API
  slug: clockodo-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.clockodo.com/en/
- title: ''
  type: Documentation
  url: https://www.clockodo.com/en/api/
- title: ''
  type: Blog
  url: https://www.clockodo.com/en/blog/
- title: ''
  type: Pricing
  url: https://www.clockodo.com/en/pricing/
- title: ''
  type: TermsOfService
  url: https://www.clockodo.com/en/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.clockodo.com/en/data-privacy/
- title: ''
  type: OpenAPI
  url: openapi/clockodo-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/clockodo-entry-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/clockodo-context.jsonld
- title: ''
  type: Spectral
  url: rules/clockodo-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clockodo-capabilities.yml
created: '2025-02-17'
description: 'Clockodo is a German-built, cloud-based time-tracking and project- management application used by service firms, agencies, and freelancers. In addition to its web and mobile apps, Clockodo exposes a REST API at my.clockodo.com that mirrors the objects in the UI: time entries, customers, projects, services, users, absences, holiday quotas, lump-sum services, and a real-time stop-clock. Authentication uses a per-user email plus per-user API key delivered as the X-ClockodoApiUser/X-ClockodoApiKey header pair (or HTTP Basic), and every call must include the X-Clockodo-External-Application header identifying the integrating application.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Clockodo Context
  property_count: 10
  slug: clockodo-context
layout: provider
modified: '2026-04-27'
name: Clockodo
rules:
- name: Clockodo API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: clockodo-rules
skills: []
slug: clockodo
solutions: []
tags:
- Absence Management
- Billing
- Project Management
- Stop Clock
- Time Tracking
- Timesheets
url: https://raw.githubusercontent.com/api-evangelist/clockodo/refs/heads/main/apis.yml
use_cases: []
---
