---
api_count: 4
apis:
- description: 'The Power BI REST API enables programmatic access to Power BI resources including datasets, reports, dashboards, workspaces, and dataflows. Developers can automate report deployment, manage workspace '
  name: Power BI REST API
  slug: rest-api
- description: Power BI Embedded enables developers to embed interactive Power BI reports, dashboards, and tiles into custom applications. It provides client-side JavaScript APIs for rendering and interacting with e
  name: Power BI Embedded API
  slug: embedded-api
- description: 'The Power BI Admin REST API provides tenant-level administrative capabilities for managing Power BI across an organization. It enables administrators to audit user activities, manage workspaces, scan '
  name: Power BI Admin REST API
  slug: admin-api
- description: The Power BI Push Datasets API enables real-time data streaming into Power BI datasets. Developers can push rows of data directly to streaming datasets for real-time dashboard visualizations, supporti
  name: Power BI Push Datasets API
  slug: push-datasets-api
common:
- title: ''
  type: Portal
  url: https://app.powerbi.com/
- title: ''
  type: Website
  url: https://powerbi.microsoft.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-bi/
- title: ''
  type: Pricing
  url: https://powerbi.microsoft.com/en-us/pricing/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/
- title: ''
  type: Community
  url: https://community.fabric.microsoft.com/t5/Power-BI-forums/ct-p/pbi_english
- title: ''
  type: Blog
  url: https://powerbi.microsoft.com/en-us/blog/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Status
  url: https://status.powerplatform.microsoft.com/
created: '2024-01-01'
description: Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides REST APIs for accessing and managing Power BI resources including reports, dashboards, datasets, and workspaces programmatically.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Power BI
skills: []
slug: microsoft-power-bi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-power-bi\nname: Microsoft Power BI\ndescription: >-\n  Microsoft Power BI is a business analytics service that delivers insights\n  to enable fast, informed decisions. It provides REST APIs for accessing\n  and managing Power BI resources including reports, dashboards, datasets,\n  and workspaces programmatically.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Microsoft\n  - Reports\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-power-bi/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-power-bi:rest-api\n    name: Power BI REST API\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Dashboards\n      - Reports\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.powerbi.com/v1.0/myorg/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/power-bi/\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/power-bi/\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/rest/api/power-bi/datasets\n        type: Reference\n    description: >-\n      The Power BI REST API enables programmatic access to Power BI\n      resources including datasets, reports, dashboards, workspaces,\n      and dataflows. Developers can automate report deployment, manage\n      workspace permissions, refresh datasets, export reports, and\n      embed Power BI content in custom applications.\n  - aid: microsoft-power-bi:embedded-api\n    name: Power BI Embedded API\n    tags:\n      - Business Intelligence\n      - Embedded Analytics\n      - White Label\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.powerbi.com/v1.0/myorg/\n    humanURL: https://learn.microsoft.com/en-us/power-bi/developer/embedded/\n\
  \    properties:\n      - url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/\n        type: Documentation\n    description: >-\n      Power BI Embedded enables developers to embed interactive Power BI\n      reports, dashboards, and tiles into custom applications. It provides\n      client-side JavaScript APIs for rendering and interacting with\n      embedded content, supporting scenarios like white-label analytics,\n      custom filtering, and programmatic report navigation.\n  - aid: microsoft-power-bi:admin-api\n    name: Power BI Admin REST API\n    tags:\n      - Administration\n      - Governance\n      - Tenant Management\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.powerbi.com/v1.0/myorg/admin/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-bi/admin\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/power-bi/admin\n        type: Documentation\n    description:\
  \ >-\n      The Power BI Admin REST API provides tenant-level administrative\n      capabilities for managing Power BI across an organization. It\n      enables administrators to audit user activities, manage workspaces,\n      scan datasets for governance, retrieve tenant settings, and monitor\n      capacity usage and performance metrics.\n  - aid: microsoft-power-bi:push-datasets-api\n    name: Power BI Push Datasets API\n    tags:\n      - Datasets\n      - Real-Time Data\n      - Streaming\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.powerbi.com/v1.0/myorg/\n    humanURL: https://learn.microsoft.com/en-us/power-bi/developer/automation/api-automatic-retention-policy-for-real-time-data\n    properties:\n      - url: https://learn.microsoft.com/en-us/power-bi/developer/automation/api-automatic-retention-policy-for-real-time-data\n        type: Documentation\n    description: >-\n      The Power BI Push Datasets API enables\
  \ real-time data streaming\n      into Power BI datasets. Developers can push rows of data directly\n      to streaming datasets for real-time dashboard visualizations,\n      supporting IoT scenarios, live monitoring, and event-driven\n      analytics without requiring scheduled data refreshes.\ncommon:\n  - type: Portal\n    url: https://app.powerbi.com/\n  - type: Website\n    url: https://powerbi.microsoft.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-bi/\n  - type: Pricing\n    url: https://powerbi.microsoft.com/en-us/pricing/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/get-azuread-access-token\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/\n  - type: Community\n    url: https://community.fabric.microsoft.com/t5/Power-BI-forums/ct-p/pbi_english\n  - type: Blog\n    url: https://powerbi.microsoft.com/en-us/blog/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n\
  \  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Status\n    url: https://status.powerplatform.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-bi/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Microsoft
- Reports
url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-bi/refs/heads/main/apis.yml
use_cases: []
---
