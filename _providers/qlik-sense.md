---
api_count: 6
api_specs:
- filename: qlik-sense-cloud-rest-api-openapi.yml
  format: yaml
  label: Qlik Cloud Platform REST API
  slug: qlik-cloud-platform-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/openapi/qlik-sense-cloud-rest-api-openapi.yml
apis:
- description: WebSocket-based API for interacting with the Qlik Associative Engine, including data modeling, selections, and visualizations.
  name: Qlik Sense Engine API
  slug: qlik-sense-engine-api
- description: REST API for managing Qlik Sense repository objects including apps, streams, users, and security rules.
  name: Qlik Sense Repository API
  slug: qlik-sense-repository-api
- description: REST API for Qlik Cloud services including apps, data connections, spaces, and tenant management.
  name: Qlik Cloud Platform REST API
  slug: qlik-cloud-platform-rest-api
- description: REST API for session management and authentication through the Qlik Sense Proxy Service.
  name: Qlik Sense Proxy API
  slug: qlik-sense-proxy-api
- description: REST API for managing data integration tasks, connections, and data pipelines.
  name: Qlik Data Integration API
  slug: qlik-data-integration-api
- description: JavaScript API for embedding Qlik Sense visualizations and mashups into web applications.
  name: Qlik Embedding API
  slug: qlik-embedding-api
common:
- title: ''
  type: Portal
  url: https://qlik.dev
- title: ''
  type: Website
  url: https://www.qlik.com
- title: ''
  type: Documentation
  url: https://help.qlik.com/en-US/sense-developer/
- title: ''
  type: Authentication
  url: https://qlik.dev/authenticate
- title: ''
  type: GettingStarted
  url: https://qlik.dev/get-started
- title: ''
  type: TermsOfService
  url: https://www.qlik.com/us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.qlik.com/us/legal/privacy-and-cookie-notice
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: Support
  url: https://community.qlik.com
- title: ''
  type: Status
  url: https://status.qlikcloud.com
- title: ''
  type: Blog
  url: https://www.qlik.com/blog
- title: ''
  type: SignUp
  url: https://www.qlik.com/us/trial/qlik-cloud-analytics
- title: ''
  type: Login
  url: https://myqlik.qlik.com
- title: ''
  type: SDKs
  url: https://qlik.dev/toolkits/qlik-api
- title: ''
  type: ChangeLog
  url: https://qlik.dev/changelog
- title: ''
  type: Pricing
  url: https://www.qlik.com/us/pricing/data-integration-products-pricing
created: '2024-01-15'
description: APIs for Qlik Sense, a business intelligence and data analytics platform providing engine, repository, cloud, embedding, and data integration capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Qlik Sense Context
  property_count: 6
  slug: qlik-sense-context
layout: provider
modified: '2026-04-28'
name: Qlik Sense
skills: []
slug: qlik-sense
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qlik-sense\nname: Qlik Sense\ndescription: >-\n  APIs for Qlik Sense, a business intelligence and data analytics platform\n  providing engine, repository, cloud, embedding, and data integration\n  capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Cloud\n  - Data Integration\n  - Visualization\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: qlik-sense:qlik-sense-engine-api\n    name: Qlik Sense Engine API\n    description: >-\n      WebSocket-based API for interacting with the Qlik Associative Engine,\n      including data modeling, selections, and visualizations.\n    humanURL: https://qlik.dev/apis/json-rpc/qix\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Data Engine\n      - WebSocket\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/json-rpc/qix\n      - type: Authentication\n        url: https://qlik.dev/authenticate\n      - type: ChangeLog\n        url: https://qlik.dev/changelog\n  - aid: qlik-sense:qlik-sense-repository-api\n    name: Qlik Sense Repository API\n    description: >-\n      REST API for managing Qlik Sense repository objects including apps,\n      streams, users, and security rules.\n    humanURL: https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html\n    tags:\n      - Repository\n      - Administration\n      - Security\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html\n  - aid: qlik-sense:qlik-cloud-platform-rest-api\n    name: Qlik Cloud Platform REST API\n    description: >-\n      REST API for Qlik Cloud services including apps, data connections, spaces,\n      and tenant management.\n    humanURL:\
  \ https://qlik.dev/apis/rest\n    tags:\n      - Cloud\n      - Platform\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/openapi/qlik-sense-cloud-rest-api-openapi.yml\n      - type: Authentication\n        url: https://qlik.dev/authenticate\n  - aid: qlik-sense:qlik-sense-proxy-api\n    name: Qlik Sense Proxy API\n    description: >-\n      REST API for session management and authentication through the Qlik Sense\n      Proxy Service.\n    humanURL: https://help.qlik.com/en-US/sense-developer/APIs/ProxyAPI/index.html\n    tags:\n      - Proxy\n      - Authentication\n      - Sessions\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/APIs/ProxyAPI/index.html\n  - aid: qlik-sense:qlik-data-integration-api\n    name: Qlik Data Integration API\n    description:\
  \ >-\n      REST API for managing data integration tasks, connections, and data\n      pipelines.\n    humanURL: https://qlik.dev/apis/rest/data-integration\n    tags:\n      - Data Integration\n      - ETL\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-integration\n  - aid: qlik-sense:qlik-embedding-api\n    name: Qlik Embedding API\n    description: >-\n      JavaScript API for embedding Qlik Sense visualizations and mashups into\n      web applications.\n    humanURL: https://qlik.dev/embed\n    tags:\n      - Embedding\n      - JavaScript\n      - Visualization\n      - Mashups\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/embed\n      - type: Tutorials\n        url: https://qlik.dev/tutorials/embed-analytics\ncommon:\n  - type: Portal\n    url: https://qlik.dev\n  - type: Website\n    url: https://www.qlik.com\n  - type: Documentation\n    url: https://help.qlik.com/en-US/sense-developer/\n \
  \ - type: Authentication\n    url: https://qlik.dev/authenticate\n  - type: GettingStarted\n    url: https://qlik.dev/get-started\n  - type: TermsOfService\n    url: https://www.qlik.com/us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.qlik.com/us/legal/privacy-and-cookie-notice\n  - type: GitHubOrganization\n    url: https://github.com/qlik-oss\n  - type: Support\n    url: https://community.qlik.com\n  - type: Status\n    url: https://status.qlikcloud.com\n  - type: Blog\n    url: https://www.qlik.com/blog\n  - type: SignUp\n    url: https://www.qlik.com/us/trial/qlik-cloud-analytics\n  - type: Login\n    url: https://myqlik.qlik.com\n  - type: SDKs\n    url: https://qlik.dev/toolkits/qlik-api\n  - type: ChangeLog\n    url: https://qlik.dev/changelog\n  - type: Pricing\n    url: https://www.qlik.com/us/pricing/data-integration-products-pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Cloud
- Data Integration
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/qlik-sense/refs/heads/main/apis.yml
use_cases: []
---
