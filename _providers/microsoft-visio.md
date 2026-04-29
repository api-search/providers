---
api_count: 2
api_specs:
- filename: microsoft-visio-graph-api.yaml
  format: yaml
  label: Microsoft Graph Visio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/openapi/microsoft-visio-graph-api.yaml
apis:
- description: REST API for accessing and interacting with Visio files stored in SharePoint Online and OneDrive for Business through Microsoft Graph. Supports reading pages, shapes, shape data, comments, and hyperli
  name: Microsoft Graph Visio API
  slug: ''
- description: JavaScript API for building add-ins and extending Visio functionality in the browser with access to documents, pages, shapes, and comments.
  name: Visio JavaScript API
  slug: ''
capabilities:
- description: 'Workflow capability for analyzing Visio diagrams including reading pages, shapes, data items, comments, and hyperlinks. Used by business analysts and IT architects to programmatically inspect diagram '
  name: Microsoft Visio Diagram Analysis
  slug: diagram-analysis
common:
- title: ''
  type: Support
  url: https://support.microsoft.com/visio
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/visio-blog/bg-p/VisioBlog
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: StatusPage
  url: https://status.microsoft365.com/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev
- title: ''
  type: SpectralRules
  url: rules/microsoft-visio-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/diagram-analysis.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-visio-vocabulary.yaml
created: '2024'
description: APIs and resources for Microsoft Visio, a diagramming and vector graphics application that helps visualize data-connected business process flows. Provides programmatic access to diagrams, pages, shapes, data items, comments, and hyperlinks through Microsoft Graph and JavaScript APIs.
features:
- description: Render Visio diagrams in the browser via JavaScript API.
  name: Diagram Rendering
- description: Read data items attached to diagram shapes.
  name: Shape Data Access
- description: Navigate and list pages within Visio documents.
  name: Page Navigation
- description: Read and manage comments on shapes.
  name: Comment Support
- description: Access hyperlinks associated with diagram shapes.
  name: Hyperlink Management
image: https://learn.microsoft.com/en-us/graph/images/visio-logo.png
integrations:
- description: Access Visio files stored in SharePoint document libraries.
  name: SharePoint
- description: Work with Visio diagrams in OneDrive for Business.
  name: OneDrive
- description: Trigger workflows based on Visio diagram changes.
  name: Power Automate
jsonld:
- class_count: 7
  name: Microsoft Visio Graph Api Context
  property_count: 13
  slug: microsoft-visio-graph-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Visio
rules:
- name: Microsoft Visio API Rules
  rule_count: 16
  severity_counts:
    error: 12
    hint: 0
    info: 0
    warn: 4
  slug: microsoft-visio-spectral-rules
skills: []
slug: microsoft-visio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-visio\nname: Microsoft Visio\ndescription: >-\n  APIs and resources for Microsoft Visio, a diagramming and vector graphics\n  application that helps visualize data-connected business process flows.\n  Provides programmatic access to diagrams, pages, shapes, data items,\n  comments, and hyperlinks through Microsoft Graph and JavaScript APIs.\nimage: https://learn.microsoft.com/en-us/graph/images/visio-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/apis.yml\nhumanURL: https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Business Process\n  - Diagramming\n  - Flowcharts\n  - Microsoft 365\n  - Visualization\napis:\n  - name: Microsoft Graph Visio API\n    description: >-\n      REST API for accessing and interacting with Visio files stored in\n      SharePoint Online\
  \ and OneDrive for Business through Microsoft Graph.\n      Supports reading pages, shapes, shape data, comments, and hyperlinks.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/visio\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Microsoft Graph\n      - OneDrive\n      - REST API\n      - SharePoint\n      - Visio Files\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/visio\n      - type: OpenAPI\n        url: openapi/microsoft-visio-graph-api.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/api/resources/visio\n      - type: JSONSchema\n        url: json-schema/visio-graph-api-visio-page-schema.json\n      - type: JSONSchema\n        url: json-schema/visio-graph-api-visio-shape-schema.json\n      - type: JSONSchema\n        url: json-schema/visio-graph-api-shape-data-item-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/visio-graph-api-visio-comment-schema.json\n      - type: JSONSchema\n        url: json-schema/visio-graph-api-visio-hyperlink-schema.json\n      - type: JSONStructure\n        url: json-structure/visio-graph-api-visio-page-structure.json\n      - type: JSON-LD\n        url: json-ld/microsoft-visio-graph-api-context.jsonld\n      - type: Example\n        url: examples/visio-graph-api-visio-page-example.json\n      - type: Example\n        url: examples/visio-graph-api-visio-shape-example.json\n  - name: Visio JavaScript API\n    description: >-\n      JavaScript API for building add-ins and extending Visio functionality\n      in the browser with access to documents, pages, shapes, and comments.\n    humanURL: https://learn.microsoft.com/en-us/javascript/api/visio\n    baseURL: https://learn.microsoft.com/en-us/javascript/api/visio\n    tags:\n      - Add-Ins\n      - Browser\n      - JavaScript\n      - Office Add-Ins\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/visio\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/javascript/api/visio?view=visio-js-1.1\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-add-ins-overview\n      - type: CodeExamples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\ncommon:\n  - type: Support\n    url: https://support.microsoft.com/visio\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/visio-blog/bg-p/VisioBlog\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/servicesagreement\n  - type: StatusPage\n    url: https://status.microsoft365.com/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options\n  - type: GitHubOrganization\n\
  \    url: https://github.com/OfficeDev\n  - type: SpectralRules\n    url: rules/microsoft-visio-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/diagram-analysis.yaml\n  - type: Vocabulary\n    url: vocabulary/microsoft-visio-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Diagram Rendering\n        description: Render Visio diagrams in the browser via JavaScript API.\n      - name: Shape Data Access\n        description: Read data items attached to diagram shapes.\n      - name: Page Navigation\n        description: Navigate and list pages within Visio documents.\n      - name: Comment Support\n        description: Read and manage comments on shapes.\n      - name: Hyperlink Management\n        description: Access hyperlinks associated with diagram shapes.\n  - type: UseCases\n    data:\n      - name: Network Topology Analysis\n        description: Programmatically analyze network diagrams for infrastructure review.\n      - name: Business Process Review\n\
  \        description: Extract and analyze business process flow data from diagrams.\n      - name: Compliance Auditing\n        description: Inspect diagram shapes and data for compliance validation.\n  - type: Integrations\n    data:\n      - name: SharePoint\n        description: Access Visio files stored in SharePoint document libraries.\n      - name: OneDrive\n        description: Work with Visio diagrams in OneDrive for Business.\n      - name: Power Automate\n        description: Trigger workflows based on Visio diagram changes.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/apis.yml
tags:
- Business Process
- Diagramming
- Flowcharts
- Microsoft 365
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/microsoft-visio/refs/heads/main/apis.yml
use_cases:
- description: Programmatically analyze network diagrams for infrastructure review.
  name: Network Topology Analysis
- description: Extract and analyze business process flow data from diagrams.
  name: Business Process Review
- description: Inspect diagram shapes and data for compliance validation.
  name: Compliance Auditing
---
