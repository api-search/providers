---
api_count: 8
api_specs:
- filename: qlik-sense-enterprise-repository-service-openapi.yml
  format: yaml
  label: Qlik Sense Repository Service
  slug: qlik-sense-repository-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-repository-service-openapi.yml
- filename: qlik-sense-enterprise-proxy-service-openapi.yml
  format: yaml
  label: Qlik Sense Proxy Service
  slug: qlik-sense-proxy-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-proxy-service-openapi.yml
- filename: qlik-sense-enterprise-about-service-openapi.yml
  format: yaml
  label: Qlik Sense About Service
  slug: qlik-sense-about-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-about-service-openapi.yml
- filename: qlik-sense-enterprise-data-connection-openapi.yml
  format: yaml
  label: Qlik Sense Data Connection
  slug: qlik-sense-data-connection
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-data-connection-openapi.yml
- filename: qlik-sense-enterprise-licenses-openapi.yml
  format: yaml
  label: Qlik Sense Licenses
  slug: qlik-sense-licenses
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-licenses-openapi.yml
- filename: qlik-sense-enterprise-odag-service-openapi.yml
  format: yaml
  label: Qlik Sense ODAG
  slug: qlik-sense-odag
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-odag-service-openapi.yml
apis:
- description: Core REST API for managing Qlik Sense Enterprise resources including apps, streams, users, security rules, and all configuration available through the Qlik Management Console.
  name: Qlik Sense Repository Service
  slug: qlik-sense-repository-service
- description: WebSocket protocol API using JSON-RPC for interacting with the Qlik Associative Engine.
  name: Qlik Sense Engine JSON API
  slug: qlik-sense-engine-json-api
- description: REST API for managing sessions, virtual proxies, and authentication in Qlik Sense Enterprise deployments.
  name: Qlik Sense Proxy Service
  slug: qlik-sense-proxy-service
- description: Service that exposes metadata about the running Qlik Sense Enterprise deployment including versions and supported APIs.
  name: Qlik Sense About Service
  slug: qlik-sense-about-service
- description: API for managing data connections and data sources.
  name: Qlik Sense Data Connection
  slug: qlik-sense-data-connection
- description: API for managing licenses, license allocations, and user access in Qlik Sense Enterprise.
  name: Qlik Sense Licenses
  slug: qlik-sense-licenses
- description: On-Demand App Generation service API for orchestrating dynamic app generation against large data sources.
  name: Qlik Sense ODAG
  slug: qlik-sense-odag
- description: High-level JavaScript API for embedding and extending Qlik Sense visualizations and mashups.
  name: Qlik Sense Capabilities
  slug: qlik-sense-capabilities
common:
- title: ''
  type: Portal
  url: https://qlik.dev/
- title: ''
  type: Documentation
  url: https://help.qlik.com/en-US/sense-developer/November2025/Content/Sense_Helpsites/APIs-and-SDKs.htm
- title: ''
  type: Authentication
  url: https://qlik.dev/toolkits/qlik-api/authentication/
- title: ''
  type: Blog
  url: https://www.qlik.com/blog
- title: ''
  type: Status
  url: https://status.qlikcloud.com/
- title: ''
  type: Support
  url: https://community.qlik.com/t5/Support/ct-p/qlikSupport
- title: ''
  type: TermsOfService
  url: https://www.qlik.com/us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.qlik.com/us/legal/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: Community
  url: https://community.qlik.com/
- title: ''
  type: Website
  url: https://www.qlik.com/
- title: ''
  type: Login
  url: https://qlikid.qlik.com/
- title: ''
  type: SignUp
  url: https://register.myqlik.qlik.com/
created: '2024-01-01'
description: Collection of APIs for Qlik Sense Enterprise, a modern analytics platform for business intelligence and data visualization.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Qlik Sense Enterprise Context
  property_count: 12
  slug: qlik-sense-enterprise-context
layout: provider
modified: '2026-04-28'
name: Qlik Sense Enterprise
skills: []
slug: qlik-sense-enterprise
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qlik-sense-enterprise\nname: Qlik Sense Enterprise\ndescription: >-\n  Collection of APIs for Qlik Sense Enterprise, a modern analytics platform for\n  business intelligence and data visualization.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Data Visualization\n  - Enterprise\n  - REST API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: qlik-sense-enterprise:qlik-sense-repository-service\n    name: Qlik Sense Repository Service\n    description: >-\n      Core REST API for managing Qlik Sense Enterprise resources including\n      apps, streams, users, security rules, and all configuration available\n      through the Qlik Management Console.\n    humanURL: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Introduction.htm\n\
  \    tags:\n      - Management\n      - Repository\n      - Security\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Introduction.htm\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-repository-service-openapi.yml\n      - type: Authentication\n        url: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/RepositoryServiceAPI-Connect-API-Authenticate.htm\n  - aid: qlik-sense-enterprise:qlik-sense-engine-json-api\n    name: Qlik Sense Engine JSON API\n    description: >-\n      WebSocket protocol API using JSON-RPC for interacting with the Qlik\n      Associative Engine.\n    humanURL: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/EngineJSONAPI/Content/introduction.htm\n\
  \    tags:\n      - Engine\n      - JSON-RPC\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/EngineJSONAPI/Content/introduction.htm\n  - aid: qlik-sense-enterprise:qlik-sense-proxy-service\n    name: Qlik Sense Proxy Service\n    description: >-\n      REST API for managing sessions, virtual proxies, and authentication in\n      Qlik Sense Enterprise deployments.\n    humanURL: https://help.qlik.com/en-US/sense-developer/Subsystems/ProxyServiceAPI/Content/Sense_ProxyServiceAPI/ProxyServiceAPI-Introduction.htm\n    tags:\n      - Proxy\n      - Authentication\n      - Sessions\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/Subsystems/ProxyServiceAPI/Content/Sense_ProxyServiceAPI/ProxyServiceAPI-Introduction.htm\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-proxy-service-openapi.yml\n\
  \  - aid: qlik-sense-enterprise:qlik-sense-about-service\n    name: Qlik Sense About Service\n    description: >-\n      Service that exposes metadata about the running Qlik Sense Enterprise\n      deployment including versions and supported APIs.\n    humanURL: https://help.qlik.com/en-US/sense-developer/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/About-API/About-API-Introduction.htm\n    tags:\n      - Metadata\n      - Service\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/About-API/About-API-Introduction.htm\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-about-service-openapi.yml\n  - aid: qlik-sense-enterprise:qlik-sense-data-connection\n    name: Qlik Sense Data Connection\n    description: API for managing data connections and data\
  \ sources.\n    humanURL: https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html\n    tags:\n      - Data Connections\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/APIs/RepositoryServiceAPI/index.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-data-connection-openapi.yml\n  - aid: qlik-sense-enterprise:qlik-sense-licenses\n    name: Qlik Sense Licenses\n    description: >-\n      API for managing licenses, license allocations, and user access in Qlik\n      Sense Enterprise.\n    humanURL: https://help.qlik.com/en-US/sense-admin/Content/Sense_AdministerQSE/Licensing/Licensing.htm\n    tags:\n      - Licensing\n      - Allocation\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-admin/Content/Sense_AdministerQSE/Licensing/Licensing.htm\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-licenses-openapi.yml\n  - aid: qlik-sense-enterprise:qlik-sense-odag\n    name: Qlik Sense ODAG\n    description: >-\n      On-Demand App Generation service API for orchestrating dynamic app\n      generation against large data sources.\n    humanURL: https://help.qlik.com/en-US/sense/Content/Sense_Helpsites/On-demand-apps.htm\n    tags:\n      - ODAG\n      - On-Demand\n      - Apps\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense/Content/Sense_Helpsites/On-demand-apps.htm\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-odag-service-openapi.yml\n  - aid: qlik-sense-enterprise:qlik-sense-capabilities\n    name: Qlik Sense Capabilities\n    description: >-\n      High-level JavaScript API\
  \ for embedding and extending Qlik Sense\n      visualizations and mashups.\n    humanURL: https://help.qlik.com/en-US/sense-developer/APIs/CapabilityAPIs/index.html\n    tags:\n      - Visualization\n      - Mashup\n      - Embedding\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/sense-developer/APIs/CapabilityAPIs/index.html\ncommon:\n  - type: Portal\n    url: https://qlik.dev/\n  - type: Documentation\n    url: https://help.qlik.com/en-US/sense-developer/November2025/Content/Sense_Helpsites/APIs-and-SDKs.htm\n  - type: Authentication\n    url: https://qlik.dev/toolkits/qlik-api/authentication/\n  - type: Blog\n    url: https://www.qlik.com/blog\n  - type: Status\n    url: https://status.qlikcloud.com/\n  - type: Support\n    url: https://community.qlik.com/t5/Support/ct-p/qlikSupport\n  - type: TermsOfService\n    url: https://www.qlik.com/us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.qlik.com/us/legal/privacy\n  - type:\
  \ GitHubOrganization\n    url: https://github.com/qlik-oss\n  - type: Community\n    url: https://community.qlik.com/\n  - type: Website\n    url: https://www.qlik.com/\n  - type: Login\n    url: https://qlikid.qlik.com/\n  - type: SignUp\n    url: https://register.myqlik.qlik.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Enterprise
- REST API
url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/apis.yml
use_cases: []
---
