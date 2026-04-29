---
api_count: 5
api_specs:
- filename: bugsnag-data-access-openapi.yml
  format: yaml
  label: Bugsnag Data Access API
  slug: data-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-data-access-openapi.yml
- filename: bugsnag-error-reporting-openapi.yml
  format: yaml
  label: Bugsnag Error Reporting API
  slug: error-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-error-reporting-openapi.yml
- filename: bugsnag-session-tracking-openapi.yml
  format: yaml
  label: Bugsnag Session Tracking API
  slug: session-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-session-tracking-openapi.yml
- filename: bugsnag-build-openapi.yml
  format: yaml
  label: Bugsnag Build API
  slug: build-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-build-openapi.yml
- filename: bugsnag-trace-openapi.yml
  format: yaml
  label: Bugsnag Trace API
  slug: trace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/openapi/bugsnag-trace-openapi.yml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bugsnag\nurl: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/apis.yml\napis:\n  - aid: bugsnag:data-access-api\n    name: Bugsnag Data Access API\n    tags:\n      - Analytics\n      - Application Stability\n      - Data Access\n      - Error Monitoring\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.bugsnag.com\n    humanURL: https://docs.bugsnag.com/api/data-access/\n    properties:\n      - url: https://docs.bugsnag.com/api/data-access/\n        type: Documentation\n      - url: openapi/bugsnag-data-access-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bugsnag Data Access API provides programmatic access to information\n      about your organization, projects, errors, events, and more. It allows\n      developers to build custom integrations and dashboards using their\n      Bugsnag data. The REST API uses JSON and requires authentication via an\n      API\
  \ token, which can be found in Bugsnag account settings. It supports\n      querying error trends, project configurations, collaborators, and\n      release information.\n  - aid: bugsnag:error-reporting-api\n    name: Bugsnag Error Reporting API\n    tags:\n      - Error Monitoring\n      - Error Reporting\n      - Events\n      - Notifications\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://notify.bugsnag.com\n    humanURL: https://docs.bugsnag.com/api/error-reporting/\n    properties:\n      - url: https://docs.bugsnag.com/api/error-reporting/\n        type: Documentation\n      - url: openapi/bugsnag-error-reporting-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bugsnag Error Reporting API allows applications to report error and\n      exception details directly to the Bugsnag dashboard. If there is no\n      official SDK available for your platform, you can use this API to send\n      error payloads manually.\
  \ The API accepts structured JSON payloads\n      containing exception details, stack traces, device information, and\n      application metadata. It is the underlying mechanism used by all\n      official Bugsnag notifier SDKs to deliver error data.\n  - aid: bugsnag:session-tracking-api\n    name: Bugsnag Session Tracking API\n    tags:\n      - Application Monitoring\n      - Sessions\n      - Stability\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://sessions.bugsnag.com\n    humanURL: https://docs.bugsnag.com/api/sessions/\n    properties:\n      - url: https://docs.bugsnag.com/api/sessions/\n        type: Documentation\n      - url: openapi/bugsnag-session-tracking-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bugsnag Session Tracking API enables applications to report session\n      data, which is used to calculate release stability scores in the\n      Bugsnag dashboard. By tracking when user sessions\
  \ start and end,\n      Bugsnag can determine crash rates and overall application stability.\n      This API works in conjunction with the Error Reporting API to provide\n      a complete picture of application health. Session data is required for\n      accurate stability metrics and crash-free user percentages.\n  - aid: bugsnag:build-api\n    name: Bugsnag Build API\n    tags:\n      - Builds\n      - CI/CD\n      - Deployments\n      - Releases\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://build.bugsnag.com\n    humanURL: https://docs.bugsnag.com/api/build/\n    properties:\n      - url: https://docs.bugsnag.com/api/build/\n        type: Documentation\n      - url: openapi/bugsnag-build-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bugsnag Build API allows you to provide information about your\n      application builds, releases, and deployments. By notifying Bugsnag\n      when you deploy, you can\
  \ track which releases introduced new errors,\n      view error trends across releases, and identify regressions. The API\n      accepts build metadata including version numbers, source control\n      information, and release stages. It integrates with CI/CD pipelines\n      to automate release tracking.\n  - aid: bugsnag:trace-api\n    name: Bugsnag Trace API\n    tags:\n      - Observability\n      - OpenTelemetry\n      - Performance\n      - Tracing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://otlp.bugsnag.com\n    humanURL: https://docs.bugsnag.com/api/\n    properties:\n      - url: https://docs.bugsnag.com/api/\n        type: Documentation\n      - url: openapi/bugsnag-trace-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Bugsnag Trace API allows applications to send OpenTelemetry span\n      data to Bugsnag for performance monitoring and analysis. It enables\n      developers to track request latency,\
  \ identify slow operations, and\n      monitor application performance alongside error data. The API accepts\n      trace data in the OpenTelemetry format, making it compatible with\n      existing instrumentation libraries and observability tooling. Performance\n      data is displayed in the Bugsnag dashboard alongside error information.\ncommon:\n  - type: AsyncAPI\n    url: asyncapi/bugsnag-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/bugsnag-error-event-schema.json\n  - type: JSONSchema\n    url: json-schema/bugsnag-build-schema.json\n  - type: JSON-LD\n    url: json-ld/bugsnag-context.jsonld\nmodified: '2026-03-20'\ndescription: >-\n  Bugsnag is an application stability monitoring platform that helps software teams\n  detect, diagnose, and fix errors in web, mobile, and back-end applications.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/bugsnag/refs/heads/main/apis.yml
use_cases: []
---
