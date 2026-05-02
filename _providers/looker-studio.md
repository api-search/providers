---
api_count: 5
api_specs:
- filename: looker-studio-api-openapi.yml
  format: yaml
  label: Looker Studio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-api-openapi.yml
- filename: looker-studio-linking-api-openapi.yml
  format: yaml
  label: Looker Studio Linking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-linking-api-openapi.yml
- filename: looker-studio-embedding-api-openapi.yml
  format: yaml
  label: Looker Studio Embedding API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-embedding-api-openapi.yml
- filename: looker-studio-community-connector-api-openapi.yml
  format: yaml
  label: Looker Studio Community Connector API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-community-connector-api-openapi.yml
- filename: looker-studio-community-visualization-api-openapi.yml
  format: yaml
  label: Looker Studio Community Visualization API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-community-visualization-api-openapi.yml
apis:
- description: The Looker Studio API enables developers to programmatically manage reports, data sources, and permissions. It provides methods for searching assets and managing asset permissions including getting, u
  name: Looker Studio API
  slug: ''
- description: The Looker Studio Linking API enables the creation of dynamic URLs that link to pre-configured reports. It allows developers to define data sources, control report behavior, and customize settings thr
  name: Looker Studio Linking API
  slug: ''
- description: Embed Looker Studio reports in your applications using HTML iframe tags, oEmbed, and Open Graph Tags with customizable parameters and filtering options. Supports embedding on platforms like Medium and
  name: Looker Studio Embedding API
  slug: ''
- description: 'Build custom data connectors to bring data from any source into Looker Studio. Connectors are built using Google Apps Script and implement three core functions: getConfig(), getSchema(), and getData()'
  name: Looker Studio Community Connector API
  slug: ''
- description: Build and deploy custom visualizations for Looker Studio using any JavaScript visualization library. The dscc helper library simplifies development by providing functions for data subscriptions, compo
  name: Looker Studio Community Visualization API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://console.cloud.google.com
- title: ''
  type: Documentation
  url: https://docs.cloud.google.com/looker/docs/studio
- title: ''
  type: Getting Started
  url: https://support.google.com/looker-studio/answer/6283323
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/products/data-analytics
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: Support
  url: https://cloud.google.com/looker/docs/studio/contact-us
- title: ''
  type: Terms of Service
  url: https://policies.google.com/terms
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/looker-open-source
- title: ''
  type: Community
  url: https://www.googlecloudcommunity.com/gc/Looker-Looker-Studio/ct-p/looker
- title: ''
  type: Website
  url: https://lookerstudio.google.com
- title: ''
  type: Login
  url: https://lookerstudio.google.com/?requirelogin=1
- title: ''
  type: Sign Up
  url: https://lookerstudio.google.com
- title: ''
  type: Pricing
  url: https://support.google.com/looker-studio/answer/9171315
- title: ''
  type: Release Notes
  url: https://docs.cloud.google.com/looker-studio/docs/release-notes
- title: ''
  type: Errors
  url: https://developers.google.com/looker-studio/api/errors
- title: ''
  type: Developer Forum
  url: https://discuss.google.dev/c/looker/looker-q-a/looker-studio/214
- title: ''
  type: Developers
  url: https://developers.google.com/looker-studio
- title: ''
  type: Publishing
  url: https://developers.google.com/looker-studio/integrate
created: '2024-01-15'
description: Looker Studio (formerly Google Data Studio) is a free tool that turns your data into informative, easy to read, easy to share, and fully customizable dashboards and reports. The API allows developers to programmatically manage assets, build custom connectors and visualizations, embed reports, and automate workflows.
features: []
image: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg
integrations: []
jsonld:
- class_count: 0
  name: Looker Studio Context
  property_count: 40
  slug: looker-studio-context
layout: provider
modified: '2026-04-28'
name: Looker Studio
skills: []
slug: looker-studio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Looker Studio\ndescription: >-\n  Looker Studio (formerly Google Data Studio) is a free tool that turns your\n  data into informative, easy to read, easy to share, and fully customizable\n  dashboards and reports. The API allows developers to programmatically manage\n  assets, build custom connectors and visualizations, embed reports, and\n  automate workflows.\nimage: https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\nurl: https://lookerstudio.google.com\ncreated: '2024-01-15'\nmodified: '2026-04-28'\njsonLd:\n  - type: JSON-LD Context\n    url: json-ld/looker-studio-context.jsonld\nspecificationVersion: '0.18'\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data Visualization\n  - Google\n  - Reports\napis:\n  - name: Looker Studio API\n    description: >-\n      The Looker Studio API enables developers to programmatically manage\n      reports, data sources, and permissions. It provides methods for searching\n      assets\
  \ and managing asset permissions including getting, updating, adding,\n      and removing members.\n    image: >-\n      https://www.gstatic.com/analytics-suite/header/suite/v2/ic_data_studio.svg\n    humanURL: https://developers.google.com/looker-studio/integrate/api\n    baseURL: https://datastudio.googleapis.com/v1\n    tags:\n      - Assets\n      - Automation\n      - Data Sources\n      - Permissions\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/api\n      - type: Reference\n        url: https://developers.google.com/looker-studio/integrate/api/reference\n      - type: OpenAPI\n        url: openapi/looker-studio-api-openapi.yml\n      - type: OpenAPI\n        url: https://lookerstudio.googleapis.com/$discovery/rest?version=v1\n      - type: Authentication\n        url: https://developers.google.com/looker-studio/api/authentication\n      - type: Getting Started\n        url: https://developers.google.com/looker-studio/api/quickstart\n\
  \      - type: SDKs\n        url: https://developers.google.com/looker-studio/api/client-libraries\n      - type: Rate Limits\n        url: https://developers.google.com/looker-studio/api/quotas\n      - type: Errors\n        url: https://developers.google.com/looker-studio/api/errors\n      - type: JSON Schema\n        url: json-schema/looker-studio-asset-schema.json\n      - type: JSON Schema\n        url: json-schema/looker-studio-permissions-schema.json\n      - type: JSON Schema\n        url: json-schema/looker-studio-report-schema.json\n      - type: JSON Schema\n        url: json-schema/looker-studio-data-source-schema.json\n  - name: Looker Studio Linking API\n    description: >-\n      The Looker Studio Linking API enables the creation of dynamic URLs that\n      link to pre-configured reports. It allows developers to define data\n      sources, control report behavior, and customize settings through URL\n      parameters.\n    humanURL: https://developers.google.com/looker-studio/integrate/linking-api\n\
  \    baseURL: https://lookerstudio.google.com\n    tags:\n      - Data Sources\n      - Integration\n      - Linking\n      - Reports\n      - URL Parameters\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/linking-api\n      - type: OpenAPI\n        url: openapi/looker-studio-linking-api-openapi.yml\n  - name: Looker Studio Embedding API\n    description: >-\n      Embed Looker Studio reports in your applications using HTML iframe tags,\n      oEmbed, and Open Graph Tags with customizable parameters and filtering\n      options. Supports embedding on platforms like Medium and Reddit.\n    humanURL: https://developers.google.com/looker-studio/integrate/embed\n    baseURL: https://lookerstudio.google.com/embed\n    tags:\n      - Embedding\n      - Iframe\n      - Integration\n      - Reports\n      - Sharing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/integrate/embed\n\
  \      - type: OpenAPI\n        url: openapi/looker-studio-embedding-api-openapi.yml\n      - type: Getting Started\n        url: >-\n          https://developers.google.com/looker-studio/integrate/embedding-api/get-started\n      - type: Security\n        url: >-\n          https://developers.google.com/looker-studio/connector/embed-row-level-security\n  - name: Looker Studio Community Connector API\n    description: >-\n      Build custom data connectors to bring data from any source into Looker\n      Studio. Connectors are built using Google Apps Script and implement three\n      core functions: getConfig(), getSchema(), and getData().\n    humanURL: https://developers.google.com/looker-studio/connector\n    baseURL: https://datastudio.google.com/datasources/create\n    tags:\n      - Apps Script\n      - Connectors\n      - Custom Integration\n      - Data Sources\n      - ETL\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/connector\n\
  \      - type: Reference\n        url: https://developers.google.com/looker-studio/connector/reference\n      - type: OpenAPI\n        url: openapi/looker-studio-community-connector-api-openapi.yml\n      - type: Getting Started\n        url: https://developers.google.com/looker-studio/connector/build\n      - type: Examples\n        url: https://developers.google.com/looker-studio/connector/examples\n      - type: Gallery\n        url: https://lookerstudio.google.com/data\n      - type: Change Log\n        url: https://developers.google.com/looker-studio/connector/changelog\n      - type: Publishing\n        url: >-\n          https://developers.google.com/looker-studio/connector/publish-connector\n      - type: Sharing\n        url: https://developers.google.com/looker-studio/connector/share\n      - type: Direct Links\n        url: https://developers.google.com/looker-studio/connector/direct-links\n      - type: Codelabs\n        url: https://codelabs.developers.google.com/codelabs/community-connectors\n\
  \      - type: JSON Schema\n        url: json-schema/looker-studio-connector-schema.json\n  - name: Looker Studio Community Visualization API\n    description: >-\n      Build and deploy custom visualizations for Looker Studio using any\n      JavaScript visualization library. The dscc helper library simplifies\n      development by providing functions for data subscriptions, component\n      dimensions, and user interactions.\n    humanURL: https://developers.google.com/looker-studio/visualization\n    baseURL: https://lookerstudio.google.com/visualization\n    tags:\n      - Components\n      - Custom Charts\n      - Data Visualization\n      - JavaScript\n      - Visualizations\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/looker-studio/visualization\n      - type: Reference\n        url: >-\n          https://developers.google.com/looker-studio/visualization/library-reference\n      - type: OpenAPI\n        url: openapi/looker-studio-community-visualization-api-openapi.yml\n\
  \      - type: Getting Started\n        url: https://developers.google.com/looker-studio/visualization/write-viz\n      - type: SDKs\n        url: https://developers.google.com/looker-studio/visualization/library\n      - type: Local Development\n        url: https://developers.google.com/looker-studio/visualization/local-dev\n      - type: Open Source\n        url: >-\n          https://developers.google.com/looker-studio/visualization/open-source\n      - type: Interactions\n        url: >-\n          https://developers.google.com/looker-studio/visualization/interactions-guide\n      - type: Support\n        url: https://developers.google.com/looker-studio/visualization/support\n      - type: Codelabs\n        url: >-\n          https://codelabs.developers.google.com/codelabs/community-visualization\n      - type: JSON Schema\n        url: json-schema/looker-studio-visualization-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n\
  \    url: https://console.cloud.google.com\n  - type: Documentation\n    url: https://docs.cloud.google.com/looker/docs/studio\n  - type: Getting Started\n    url: https://support.google.com/looker-studio/answer/6283323\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: Blog\n    url: https://cloud.google.com/blog/products/data-analytics\n  - type: Status\n    url: https://status.cloud.google.com\n  - type: Support\n    url: https://cloud.google.com/looker/docs/studio/contact-us\n  - type: Terms of Service\n    url: https://policies.google.com/terms\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: GitHub Organization\n    url: https://github.com/looker-open-source\n  - type: Community\n    url: https://www.googlecloudcommunity.com/gc/Looker-Looker-Studio/ct-p/looker\n  - type: Website\n    url: https://lookerstudio.google.com\n  - type: Login\n    url: https://lookerstudio.google.com/?requirelogin=1\n\
  \  - type: Sign Up\n    url: https://lookerstudio.google.com\n  - type: Pricing\n    url: https://support.google.com/looker-studio/answer/9171315\n  - type: Release Notes\n    url: https://docs.cloud.google.com/looker-studio/docs/release-notes\n  - type: Errors\n    url: https://developers.google.com/looker-studio/api/errors\n  - type: Developer Forum\n    url: https://discuss.google.dev/c/looker/looker-q-a/looker-studio/214\n  - type: Developers\n    url: https://developers.google.com/looker-studio\n  - type: Publishing\n    url: https://developers.google.com/looker-studio/integrate\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Google
- Reports
url: https://lookerstudio.google.com
use_cases: []
---
