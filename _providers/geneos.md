---
api_count: 4
apis:
- description: RESTful API exposed by the Geneos Gateway for retrieving monitoring data and managing dataviews, samplers, entities, and snooze states programmatically. Authenticated and typically deployed inside ent
  name: Geneos Gateway REST API
  slug: gateway-rest
- description: XML-RPC interface for programmatic control of Geneos Gateway including executing commands, managing configuration, publishing data into Gateways from external samplers, and retrieving monitoring data.
  name: Geneos XML-RPC API
  slug: xml-rpc
- description: API for integrating with the Geneos Web Dashboard, enabling custom dashboards, data visualization, and user interface extensions on top of Geneos monitoring data.
  name: Geneos Web Dashboard API
  slug: web-dashboard
- description: Java and Python APIs delivered through the Geneos Toolkit for building custom integrations, samplers, plugins, and automation scripts that publish data into and pull data out of Geneos.
  name: Geneos Toolkit API
  slug: toolkit
common:
- title: ''
  type: Website
  url: https://www.itrsgroup.com/
- title: ''
  type: ProductPage
  url: https://www.itrsgroup.com/products/geneos
- title: ''
  type: Documentation
  url: https://docs.itrsgroup.com/docs/geneos/
- title: ''
  type: Support
  url: https://www.itrsgroup.com/support
- title: ''
  type: Community
  url: https://community.itrsgroup.com/
- title: ''
  type: KnowledgeBase
  url: https://kb.itrsgroup.com/
- title: ''
  type: Training
  url: https://www.itrsgroup.com/training
- title: ''
  type: Contact
  url: https://www.itrsgroup.com/contact
- title: ''
  type: TermsOfService
  url: https://www.itrsgroup.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.itrsgroup.com/privacy
- title: ''
  type: GitHubOrganization
  url: https://github.com/ITRS-Group
created: '2024-01-15'
description: Geneos is ITRS Group's real-time monitoring platform that provides comprehensive observability for trading systems, applications, and infrastructure. Widely deployed across investment banks, hedge funds, and exchanges, Geneos collects high-frequency telemetry from custom samplers and toolkits, aggregates it through Gateways, and exposes that data through REST, XML-RPC, streaming, and SDK interfaces for programmatic access, automation, and dashboarding.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Geneos
skills: []
slug: geneos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: geneos\nname: Geneos\ndescription: >-\n  Geneos is ITRS Group's real-time monitoring platform that provides\n  comprehensive observability for trading systems, applications, and\n  infrastructure. Widely deployed across investment banks, hedge funds, and\n  exchanges, Geneos collects high-frequency telemetry from custom samplers and\n  toolkits, aggregates it through Gateways, and exposes that data through\n  REST, XML-RPC, streaming, and SDK interfaces for programmatic access,\n  automation, and dashboarding.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nposition: Consumer\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/geneos/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ntags:\n  - APM\n  - Capital Markets\n  - Infrastructure\n  - ITRS\n  - Monitoring\n  - Observability\n  - Real-Time\n  - Trading Systems\napis:\n  - aid: geneos:gateway-rest\n\
  \    name: Geneos Gateway REST API\n    description: >-\n      RESTful API exposed by the Geneos Gateway for retrieving monitoring data\n      and managing dataviews, samplers, entities, and snooze states\n      programmatically. Authenticated and typically deployed inside\n      enterprise networks.\n    humanURL: >-\n      https://docs.itrsgroup.com/docs/geneos/current/Gateway_Reference_Guide/gateway_rest_api.html\n    tags:\n      - Monitoring\n      - REST\n    properties:\n      - type: Documentation\n        url: >-\n          https://docs.itrsgroup.com/docs/geneos/current/Gateway_Reference_Guide/gateway_rest_api.html\n      - type: Authentication\n        url: >-\n          https://docs.itrsgroup.com/docs/geneos/current/Gateway_Reference_Guide/rest_api_authentication.html\n  - aid: geneos:xml-rpc\n    name: Geneos XML-RPC API\n    description: >-\n      XML-RPC interface for programmatic control of Geneos Gateway including\n      executing commands, managing configuration, publishing\
  \ data into\n      Gateways from external samplers, and retrieving monitoring data.\n    humanURL: >-\n      https://docs.itrsgroup.com/docs/geneos/current/Gateway_Reference_Guide/geneos_xml-rpc_api.html\n    tags:\n      - Automation\n      - XML-RPC\n    properties:\n      - type: Documentation\n        url: >-\n          https://docs.itrsgroup.com/docs/geneos/current/Gateway_Reference_Guide/geneos_xml-rpc_api.html\n  - aid: geneos:web-dashboard\n    name: Geneos Web Dashboard API\n    description: >-\n      API for integrating with the Geneos Web Dashboard, enabling custom\n      dashboards, data visualization, and user interface extensions on top of\n      Geneos monitoring data.\n    humanURL: >-\n      https://docs.itrsgroup.com/docs/geneos/current/Web_Dashboard/web-dashboard.html\n    tags:\n      - Dashboard\n      - UI\n      - Visualization\n      - Web\n    properties:\n      - type: Documentation\n        url: >-\n          https://docs.itrsgroup.com/docs/geneos/current/Web_Dashboard/web-dashboard.html\n\
  \  - aid: geneos:toolkit\n    name: Geneos Toolkit API\n    description: >-\n      Java and Python APIs delivered through the Geneos Toolkit for building\n      custom integrations, samplers, plugins, and automation scripts that\n      publish data into and pull data out of Geneos.\n    humanURL: >-\n      https://docs.itrsgroup.com/docs/geneos/current/Toolkit/toolkit.html\n    tags:\n      - Java\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: >-\n          https://docs.itrsgroup.com/docs/geneos/current/Toolkit/toolkit.html\n      - type: SDK\n        url: https://github.com/ITRS-Group/geneos-toolkit\n      - type: GitHubOrganization\n        url: https://github.com/ITRS-Group\ncommon:\n  - type: Website\n    url: https://www.itrsgroup.com/\n  - type: ProductPage\n    url: https://www.itrsgroup.com/products/geneos\n  - type: Documentation\n    url: https://docs.itrsgroup.com/docs/geneos/\n  - type: Support\n    url: https://www.itrsgroup.com/support\n\
  \  - type: Community\n    url: https://community.itrsgroup.com/\n  - type: KnowledgeBase\n    url: https://kb.itrsgroup.com/\n  - type: Training\n    url: https://www.itrsgroup.com/training\n  - type: Contact\n    url: https://www.itrsgroup.com/contact\n  - type: TermsOfService\n    url: https://www.itrsgroup.com/terms\n  - type: PrivacyPolicy\n    url: https://www.itrsgroup.com/privacy\n  - type: GitHubOrganization\n    url: https://github.com/ITRS-Group\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/geneos/refs/heads/main/apis.yml
tags:
- APM
- Capital Markets
- Infrastructure
- ITRS
- Monitoring
- Observability
- Real-Time
- Trading Systems
url: https://raw.githubusercontent.com/api-evangelist/geneos/refs/heads/main/apis.yml
use_cases: []
---
