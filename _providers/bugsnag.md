---
api_count: 5
apis:
- description: The Bugsnag Data Access API provides programmatic access to information about your organization, projects, errors, events, and more. It allows developers to build custom integrations and dashboards us
  name: Bugsnag Data Access API
  slug: data-access-api
- description: The Bugsnag Error Reporting API allows applications to report error and exception details directly to the Bugsnag dashboard. If there is no official SDK available for your platform, you can use this A
  name: Bugsnag Error Reporting API
  slug: error-reporting-api
- description: The Bugsnag Session Tracking API enables applications to report session data, which is used to calculate release stability scores in the Bugsnag dashboard. By tracking when user sessions start and end
  name: Bugsnag Session Tracking API
  slug: session-tracking-api
- description: The Bugsnag Build API allows you to provide information about your application builds, releases, and deployments. By notifying Bugsnag when you deploy, you can track which releases introduced new erro
  name: Bugsnag Build API
  slug: build-api
- description: 'The Bugsnag Trace API allows applications to send OpenTelemetry span data to Bugsnag for performance monitoring and analysis. It enables developers to track request latency, identify slow operations, '
  name: Bugsnag Trace API
  slug: trace-api
asyncapis:
- description: 'Bugsnag webhooks deliver real-time notifications about error events to a configured callback URL via HTTP POST. The webhook integration sends JSON payloads containing information about the triggering '
  name: Bugsnag Webhook Events
  slug: bugsnag-webhooks-asyncapi
common:
- title: ''
  type: AsyncAPI
  url: asyncapi/bugsnag-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/bugsnag-error-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/bugsnag-build-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/bugsnag-context.jsonld
created: ''
description: Bugsnag is an application stability monitoring platform that helps software teams detect, diagnose, and fix errors in web, mobile, and back-end applications.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Bugsnag Context
  property_count: 7
  slug: bugsnag-context
layout: provider
modified: '2026-03-20'
name: bugsnag
skills: []
slug: bugsnag
solutions: []
tags: []
url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/apis.yml
use_cases: []
---
