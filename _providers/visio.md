---
api_count: 2
api_specs:
- filename: visio-javascript-openapi.yml
  format: yaml
  label: Visio JavaScript API
  slug: visio-javascript-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/openapi/visio-javascript-openapi.yml
apis:
- description: The Visio JavaScript API enables building Office Add-ins that interact with Visio diagrams embedded in classic SharePoint Online pages. The API provides access to document elements including pages, sh
  name: Visio JavaScript API
  slug: visio-javascript-api
- description: Access and manipulate Visio files stored in OneDrive and SharePoint through Microsoft Graph. While direct Visio-specific REST endpoints are limited, Microsoft Graph provides file management capabiliti
  name: Microsoft Graph Visio API
  slug: microsoft-graph-visio-api
capabilities:
- description: Workflow capability for automating Visio diagram inspection, data extraction, and visual presentation via the Visio JavaScript API embedded in SharePoint Online. Used by developers and business analys
  name: Visio Diagram Automation
  slug: diagram-automation
common:
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: Status Page
  url: https://status.office.com
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/javascript/api/overview/visio/release-notes
- title: ''
  type: OpenAPI
  url: openapi/visio-javascript-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/visio-shape-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/visio-page-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/visio-shape-structure.json
- title: ''
  type: JSONLD
  url: json-ld/visio-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/visio-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/visio-rules.yml
created: '2024'
description: Microsoft Visio provides APIs for creating, editing, and managing Visio diagrams and drawings. The Visio JavaScript API enables developers to build Office Add-ins that interact with Visio diagrams embedded in SharePoint Online pages, accessing document elements such as pages, shapes, hyperlinks, comments, and shape data. Visio APIs support programmatic diagram manipulation, visual overlay creation, mouse event handling, and data visualization workflows.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/visio/visio-logo.png
integrations: []
jsonld:
- class_count: 35
  name: Visio Context
  property_count: 8
  slug: visio-context
layout: provider
modified: '2026-05-03'
name: Microsoft Visio API
rules:
- name: Microsoft Visio API API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 6
  slug: visio-rules
skills: []
slug: visio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: visio\nname: Microsoft Visio API\ndescription: >-\n  Microsoft Visio provides APIs for creating, editing, and managing Visio diagrams\n  and drawings. The Visio JavaScript API enables developers to build Office Add-ins\n  that interact with Visio diagrams embedded in SharePoint Online pages, accessing\n  document elements such as pages, shapes, hyperlinks, comments, and shape data.\n  Visio APIs support programmatic diagram manipulation, visual overlay creation,\n  mouse event handling, and data visualization workflows.\nimage: https://www.microsoft.com/en-us/microsoft-365/visio/visio-logo.png\ntype: Index\ntags:\n  - Business Process\n  - Collaboration\n  - Diagrams\n  - Enterprise\n  - Flowcharts\n  - Microsoft 365\n  - Visualization\nurl: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml\ncreated: '2024'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: visio:visio-javascript-api\n    name: Visio JavaScript API\n  \
  \  description: >-\n      The Visio JavaScript API enables building Office Add-ins that interact with\n      Visio diagrams embedded in classic SharePoint Online pages. The API provides\n      access to document elements including pages, shapes, hyperlinks, comments,\n      shape data items, and shape views. Developers can create visual markup overlays,\n      register mouse event handlers, read shape text and shape data, and control\n      application toolbar visibility. The API uses a request context and proxy object\n      pattern with batch execution via Visio.run() and context.sync().\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview\n    baseURL: https://appsforoffice.microsoft.com/embedded/1.0\n    tags:\n      - Add-Ins\n      - Client-Side\n      - Diagrams\n      - JavaScript\n      - Office\n      - SharePoint\n      - Web\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/javascript/api/visio\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/visio-quickstart\n      - type: Samples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n      - type: OpenAPI\n        url: openapi/visio-javascript-openapi.yml\n    contact:\n      - FN: Microsoft Office Dev\n        email: officedevfeedback@microsoft.com\n        url: https://developer.microsoft.com/office\n  - aid: visio:microsoft-graph-visio-api\n    name: Microsoft Graph Visio API\n    description: >-\n      Access and manipulate Visio files stored in OneDrive and SharePoint through\n      Microsoft Graph. While direct Visio-specific REST endpoints are limited,\n      Microsoft Graph provides file management capabilities for Visio documents\n      through the DriveItem resource, enabling upload, download, and metadata\n      operations on .vsdx and .vsd files stored\
  \ in SharePoint and OneDrive.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/visio\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - Collaboration\n      - Diagrams\n      - Enterprise\n      - Microsoft Graph\n      - OneDrive\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/visio\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com\ncommon:\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Developer Portal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n\
  \  - type: Status Page\n    url: https://status.office.com\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options\n  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/javascript/api/overview/visio/release-notes\n  - type: OpenAPI\n    url: openapi/visio-javascript-openapi.yml\n  - type: JSONSchema\n    url: json-schema/visio-shape-schema.json\n  - type: JSONSchema\n    url: json-schema/visio-page-schema.json\n  - type: JSONStructure\n    url: json-structure/visio-shape-structure.json\n  - type: JSONLD\n    url: json-ld/visio-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/visio-vocabulary.yml\n  - type: SpectralRules\n    url: rules/visio-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml
tags:
- Business Process
- Collaboration
- Diagrams
- Enterprise
- Flowcharts
- Microsoft 365
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml
use_cases: []
---
