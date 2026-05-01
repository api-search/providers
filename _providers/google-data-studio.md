---
api_count: 4
api_specs:
- filename: google-data-studio-api-openapi.yml
  format: yaml
  label: Google Data Studio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/openapi/google-data-studio-api-openapi.yml
- filename: google-data-studio-linking-api-openapi.yml
  format: yaml
  label: Looker Studio Linking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/openapi/google-data-studio-linking-api-openapi.yml
apis:
- description: The Looker Studio API enables programmatic management of Looker Studio assets, including searching for assets and managing permissions within Google Workspace or Cloud Identity organizations.
  name: Google Data Studio API
  slug: ''
- description: The Linking API provides a reliable interface to configure and forward users directly to a pre-configured Looker Studio report via URL parameters, enabling one-click report creation experiences.
  name: Looker Studio Linking API
  slug: ''
- description: Community Connectors enable direct connections from Looker Studio to any internet-accessible data source using Google Apps Script. Developers implement getAuthType, getConfig, getSchema, and getData f
  name: Looker Studio Community Connectors
  slug: ''
- description: 'Community Visualizations allow developers to build and share custom JavaScript visualizations in Looker Studio using the dscc helper library, extending the platform with custom chart types and visual '
  name: Looker Studio Community Visualizations
  slug: ''
common:
- title: ''
  type: OpenAPI
  url: openapi/google-data-studio-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/google-data-studio-linking-api-openapi.yml
- title: ''
  type: JSON Schema
  url: json-schema/google-data-studio-asset-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/google-data-studio-permissions-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/google-data-studio-connector-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/google-data-studio-report-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/google-data-studio-datasource-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/google-data-studio-context.jsonld
- title: ''
  type: Portal
  url: https://lookerstudio.google.com
- title: ''
  type: Documentation
  url: https://docs.cloud.google.com/looker/docs/studio
- title: ''
  type: Getting Started
  url: https://support.google.com/looker-studio/answer/6283323
- title: ''
  type: Authentication
  url: https://developers.google.com/looker-studio/integrate/api
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/products/data-analytics
- title: ''
  type: Status
  url: https://status.cloud.google.com/
- title: ''
  type: Support
  url: https://support.google.com/looker-studio
- title: ''
  type: Terms of Service
  url: https://support.google.com/looker-studio/answer/7019158
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/looker-open-source
- title: ''
  type: Community
  url: https://www.googlecloudcommunity.com/gc/Looker-Studio/bd-p/looker-studio
- title: ''
  type: Gallery
  url: https://lookerstudio.google.com/gallery
- title: ''
  type: Change Log
  url: https://docs.cloud.google.com/looker-studio/docs/release-notes
- title: ''
  type: Pricing
  url: https://cloud.google.com/looker/pricing
- title: ''
  type: Website
  url: https://cloud.google.com/looker-studio
- title: ''
  type: Login
  url: https://lookerstudio.google.com/?requirelogin=1
- title: ''
  type: Sign Up
  url: https://lookerstudio.google.com
created: '2024-01-01'
description: Google Data Studio, now rebranded as Looker Studio, is a free data visualization and business intelligence tool from Google that transforms data into customizable, shareable dashboards and reports. It connects to a wide range of data sources and supports community connectors and visualizations for extensibility.
features: []
image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg
integrations: []
jsonld:
- class_count: 0
  name: Google Data Studio Context
  property_count: 10
  slug: google-data-studio-context
layout: provider
modified: '2026-04-28'
name: Google Data Studio
skills: []
slug: google-data-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-data-studio\nname: Google Data Studio\ndescription: >-\n  Google Data Studio, now rebranded as Looker Studio, is a free data\n  visualization and business intelligence tool from Google that transforms data\n  into customizable, shareable dashboards and reports. It connects to a wide\n  range of data sources and supports community connectors and visualizations for\n  extensibility.\nimage: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\nurl: https://lookerstudio.google.com\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data\n  - Reporting\n  - Visualization\napis:\n  - name: Google Data Studio API\n    description: >-\n      The Looker Studio API enables programmatic management of Looker Studio\n      assets, including searching for assets and managing permissions within Google\n      Workspace or Cloud Identity organizations.\n\
  \    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\n    humanURL: https://developers.google.com/looker-studio/integrate/api\n    baseURL: https://datastudio.googleapis.com\n    tags:\n      - Assets\n      - Data Sources\n      - Permissions\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/api\n      - type: OpenAPI\n        url: openapi/google-data-studio-api-openapi.yml\n      - type: OpenAPI\n        url: https://datastudio.googleapis.com/$discovery/rest?version=v1\n      - type: Reference\n        url: https://developers.google.com/looker-studio/integrate/api/reference\n      - type: Authentication\n        url: https://developers.google.com/looker-studio/integrate/api\n      - type: Change Log\n        url: https://developers.google.com/looker-studio/integrate/api/changelog\n  - name: Looker Studio Linking API\n    description: >-\n      The Linking API provides a\
  \ reliable interface to configure and forward users\n      directly to a pre-configured Looker Studio report via URL parameters,\n      enabling one-click report creation experiences.\n    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\n    humanURL: https://developers.google.com/looker-studio/integrate/linking-api\n    tags:\n      - Embedding\n      - Integration\n      - Linking\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/linking-api\n      - type: OpenAPI\n        url: openapi/google-data-studio-linking-api-openapi.yml\n  - name: Looker Studio Community Connectors\n    description: >-\n      Community Connectors enable direct connections from Looker Studio to any\n      internet-accessible data source using Google Apps Script. Developers\n      implement getAuthType, getConfig, getSchema, and getData functions to build\n      custom connectors.\n    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\n\
  \    humanURL: https://developers.google.com/looker-studio/connector\n    tags:\n      - Apps Script\n      - Connectors\n      - Data Sources\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/connector\n      - type: Reference\n        url: https://developers.google.com/looker-studio/connector/reference\n      - type: Getting Started\n        url: https://developers.google.com/looker-studio/connector/build\n      - type: Change Log\n        url: https://developers.google.com/looker-studio/connector/changelog\n      - type: Codelabs\n        url: https://codelabs.developers.google.com/codelabs/community-connectors\n  - name: Looker Studio Community Visualizations\n    description: >-\n      Community Visualizations allow developers to build and share custom\n      JavaScript visualizations in Looker Studio using the dscc helper library,\n      extending the platform with custom chart types and visual components.\n\
  \    image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\n    humanURL: https://developers.google.com/looker-studio/visualization\n    tags:\n      - Charts\n      - Custom Components\n      - JavaScript\n      - Visualizations\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/visualization\n      - type: Getting Started\n        url: https://developers.google.com/looker-studio/visualization/get-started\n      - type: Reference\n        url: https://developers.google.com/looker-studio/visualization/library-reference\n      - type: Libraries\n        url: https://developers.google.com/looker-studio/visualization/library\n      - type: Codelabs\n        url: https://codelabs.developers.google.com/codelabs/community-visualization\n      - type: Open Source\n        url: https://developers.google.com/looker-studio/visualization/open-source\ncommon:\n  - type: OpenAPI\n    url: openapi/google-data-studio-api-openapi.yml\n\
  \  - type: OpenAPI\n    url: openapi/google-data-studio-linking-api-openapi.yml\n  - type: JSON Schema\n    url: json-schema/google-data-studio-asset-schema.json\n  - type: JSON Schema\n    url: json-schema/google-data-studio-permissions-schema.json\n  - type: JSON Schema\n    url: json-schema/google-data-studio-connector-schema.json\n  - type: JSON Schema\n    url: json-schema/google-data-studio-report-schema.json\n  - type: JSON Schema\n    url: json-schema/google-data-studio-datasource-schema.json\n  - type: JSON-LD\n    url: json-ld/google-data-studio-context.jsonld\n  - type: Portal\n    url: https://lookerstudio.google.com\n  - type: Documentation\n    url: https://docs.cloud.google.com/looker/docs/studio\n  - type: Getting Started\n    url: https://support.google.com/looker-studio/answer/6283323\n  - type: Authentication\n    url: https://developers.google.com/looker-studio/integrate/api\n  - type: Blog\n    url: https://cloud.google.com/blog/products/data-analytics\n  - type: Status\n\
  \    url: https://status.cloud.google.com/\n  - type: Support\n    url: https://support.google.com/looker-studio\n  - type: Terms of Service\n    url: https://support.google.com/looker-studio/answer/7019158\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: GitHub Organization\n    url: https://github.com/looker-open-source\n  - type: Community\n    url: https://www.googlecloudcommunity.com/gc/Looker-Studio/bd-p/looker-studio\n  - type: Gallery\n    url: https://lookerstudio.google.com/gallery\n  - type: Change Log\n    url: https://docs.cloud.google.com/looker-studio/docs/release-notes\n  - type: Pricing\n    url: https://cloud.google.com/looker/pricing\n  - type: Website\n    url: https://cloud.google.com/looker-studio\n  - type: Login\n    url: https://lookerstudio.google.com/?requirelogin=1\n  - type: Sign Up\n    url: https://lookerstudio.google.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-data-studio/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data
- Reporting
- Visualization
url: https://lookerstudio.google.com
use_cases: []
---
