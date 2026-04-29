---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Apps Script API
  slug: google-apps-script
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/openapi/openapi.yml
apis:
- description: The Apps Script API manages Google Apps Script projects, deployments, versions, and processes. It supports creating script projects, updating content, managing deployments, monitoring execution proces
  name: Google Apps Script API
  slug: google-apps-script
capabilities:
- description: Workflow capability for managing Google Apps Script projects, deployments, versions, and script execution. Enables developers and IT admins to automate Google Workspace workflows, manage script lifecy
  name: Google Workspace Automation
  slug: workspace-automation
common:
- title: ''
  type: GettingStarted
  url: https://developers.google.com/apps-script/api/concepts
- title: ''
  type: Pricing
  url: https://developers.google.com/apps-script/guides/services/quotas
- title: ''
  type: JSONLD
  url: json-ld/json-ld.jsonld
- title: ''
  type: GitHubOrganization
  url: https://github.com/googleworkspace
- title: ''
  type: SDK
  url: https://developers.google.com/apps-script/api/quickstart/nodejs
- title: ''
  type: CLI
  url: https://developers.google.com/apps-script/guides/clasp
- title: ''
  type: Documentation
  url: https://developers.google.com/apps-script/reference
- title: ''
  type: Support
  url: https://developers.google.com/apps-script/support
- title: ''
  type: Blog
  url: https://developers.google.com/apps-script/updates
- title: ''
  type: Rules
  url: rules/google-apps-script-spectral-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/shared/apps-script.yaml
- title: ''
  type: Capabilities
  url: capabilities/workspace-automation.yaml
created: '2026-03-13'
description: The Apps Script API provides programmatic access to manage Google Apps Script projects, deployments, and executions. It enables creating and updating script projects, managing project versions and deployments, monitoring script processes, and remotely executing Apps Script functions. The API is essential for automating Apps Script project management and integrating script execution into external applications.
features:
- Create and manage Apps Script projects programmatically
- Deploy script projects as web apps, add-ons, and API executables
- Remotely execute Apps Script functions from external applications
- Monitor script execution processes and metrics
- Version management with immutable snapshots of script code
image: /assets/icons/google-apps-script.png
integrations:
- Google Workspace apps including Sheets, Docs, Slides, Gmail, and Calendar
- Google Cloud Platform services for extended functionality
- External REST APIs via Apps Script UrlFetchApp service
- Google Drive for document and file management automation
- clasp CLI for local development and version control workflows
jsonld:
- class_count: 4
  name: Json Ld Context
  property_count: 5
  slug: json-ld
- class_count: 0
  name: Openapi Context
  property_count: 0
  slug: openapi-context
layout: provider
modified: '2026-04-18'
name: Google Apps Script
rules:
- name: Google Apps Script API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-apps-script-spectral-rules
skills: []
slug: google-apps-script
solutions: []
source_filename: apis.yml
source_yaml: "aid: google-apps-script\nname: Google Apps Script\ndescription: >-\n  The Apps Script API provides programmatic access to manage Google Apps Script\n  projects, deployments, and executions. It enables creating and updating script\n  projects, managing project versions and deployments, monitoring script\n  processes, and remotely executing Apps Script functions. The API is essential\n  for automating Apps Script project management and integrating script execution\n  into external applications.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Apps Script\n  - Automation\n  - Deployments\n  - Google\n  - Google Workspace\n  - Scripting\napis:\n  - aid: google-apps-script:google-apps-script\n    name: Google Apps Script API\n    description: >-\n\
  \      The Apps Script API manages Google Apps Script projects, deployments,\n      versions, and processes. It supports creating script projects, updating\n      content, managing deployments, monitoring execution processes, and remotely\n      running script functions.\n    humanURL: https://developers.google.com/apps-script/api/concepts\n    baseURL: https://script.googleapis.com\n    properties:\n      - type: OpenAPI\n        url: openapi/openapi.yml\n      - type: JSONSchema\n        url: json-schema/json-schema.yml\n      - type: JSONLD\n        url: json-ld/json-ld.jsonld\n    tags:\n      - Automation\n      - Deployments\n      - Projects\n      - Scripting\ncommon:\n  - type: GettingStarted\n    url: https://developers.google.com/apps-script/api/concepts\n  - type: Pricing\n    url: https://developers.google.com/apps-script/guides/services/quotas\n  - type: JSONLD\n    url: json-ld/json-ld.jsonld\n  - type: GitHubOrganization\n    url: https://github.com/googleworkspace\n  -\
  \ type: SDK\n    url: https://developers.google.com/apps-script/api/quickstart/nodejs\n  - type: CLI\n    url: https://developers.google.com/apps-script/guides/clasp\n  - type: Documentation\n    url: https://developers.google.com/apps-script/reference\n  - type: Support\n    url: https://developers.google.com/apps-script/support\n  - type: Blog\n    url: https://developers.google.com/apps-script/updates\n  - type: Features\n    data:\n      - Create and manage Apps Script projects programmatically\n      - Deploy script projects as web apps, add-ons, and API executables\n      - Remotely execute Apps Script functions from external applications\n      - Monitor script execution processes and metrics\n      - Version management with immutable snapshots of script code\n  - type: UseCases\n    data:\n      - Automating Google Workspace workflows across Sheets, Docs, and Gmail\n      - Building custom add-ons and integrations for Google Workspace\n      - Managing script deployments across\
  \ development and production environments\n      - Monitoring script execution health and performance metrics\n      - Integrating Apps Script automation into CI/CD pipelines\n  - type: Integrations\n    data:\n      - Google Workspace apps including Sheets, Docs, Slides, Gmail, and Calendar\n      - Google Cloud Platform services for extended functionality\n      - External REST APIs via Apps Script UrlFetchApp service\n      - Google Drive for document and file management automation\n      - clasp CLI for local development and version control workflows\n  - type: Rules\n    url: rules/google-apps-script-spectral-rules.yml\n  - type: Capabilities\n    url: capabilities/shared/apps-script.yaml\n  - type: Capabilities\n    url: capabilities/workspace-automation.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/apis.yml
tags:
- Apps Script
- Automation
- Deployments
- Google
- Google Workspace
- Scripting
url: https://raw.githubusercontent.com/api-evangelist/google-apps-script/refs/heads/main/apis.yml
use_cases:
- Automating Google Workspace workflows across Sheets, Docs, and Gmail
- Building custom add-ons and integrations for Google Workspace
- Managing script deployments across development and production environments
- Monitoring script execution health and performance metrics
- Integrating Apps Script automation into CI/CD pipelines
---
