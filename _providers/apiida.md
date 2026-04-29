---
api_count: 2
apis:
- description: REST API for the APIIDA API Control Plane, enabling programmatic management of APIs across multiple API gateways. Supports validation of proxy specifications, API version management, and deployment to
  name: APIIDA API Control Plane
  slug: api-control-plane
- description: REST API for the APIIDA API Gateway Manager, enabling programmatic management of Broadcom Layer7 API gateways. Supports gateway registration, API deployment and migration, monitoring and metrics colle
  name: APIIDA API Gateway Manager
  slug: api-gateway-manager
capabilities:
- description: Unified workflow for federated API management across multiple API gateways using APIIDA - validating specs, deploying APIs, monitoring gateways, and managing API lifecycle from a central control plane
  name: APIIDA Federated API Management
  slug: federated-api-management
common:
- title: ''
  type: Website
  url: https://apiida.com/
- title: ''
  type: Documentation
  url: https://apiida.atlassian.net/wiki/spaces/AAGM
- title: ''
  type: Support
  url: https://apiida.com/support/?lang=en
- title: ''
  type: GitHubOrganization
  url: https://github.com/apiida
created: '2025-01-08'
description: APIIDA provides market-leading solutions for multi-vendor, cross-platform federated API management. The APIIDA API Control Plane enables enterprises to discover, govern, and provision APIs from a central location, while the API Gateway Manager automates API operations for Broadcom Layer7 environments with comprehensive deployment, migration, monitoring, and alarming capabilities.
features:
- description: Centrally discover, govern, and provision APIs across multiple API gateway vendors from a single control plane.
  name: Federated API Control Plane
- description: Manage APIs across heterogeneous gateway environments including Broadcom Layer7, AWS API Gateway, Azure APIM, and others.
  name: Multi-Gateway Support
- description: Automate API deployments and migrations across gateway instances with version management and rollback.
  name: API Deployment Automation
- description: Collect gateway metrics and configure alarms for proactive API operations management.
  name: Monitoring and Alarming
- description: Validate API proxy specifications before deployment to ensure compatibility and standards compliance.
  name: Proxy Specification Validation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Apiida Context
  property_count: 5
  slug: apiida-context
layout: provider
modified: '2026-04-19'
name: APIIDA
rules:
- name: APIIDA API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: apiida-spectral-rules
skills: []
slug: apiida
solutions:
- description: Central API management and governance for multi-vendor API gateway environments.
  name: API Control Plane
- description: Automated operations management for Broadcom Layer7 API gateway environments.
  name: API Gateway Manager
- description: Custom licensing with dedicated support for large-scale federated API management deployments.
  name: Enterprise
source_yaml: "aid: apiida\nname: APIIDA\ndescription: >-\n  APIIDA provides market-leading solutions for multi-vendor, cross-platform\n  federated API management. The APIIDA API Control Plane enables enterprises\n  to discover, govern, and provision APIs from a central location, while the\n  API Gateway Manager automates API operations for Broadcom Layer7\n  environments with comprehensive deployment, migration, monitoring, and\n  alarming capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - Federated API Management\n  - Governance\n  - Layer7\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apiida:api-control-plane\n    name: APIIDA API Control Plane\n    description: >-\n      REST API for the APIIDA API Control Plane, enabling programmatic\n    \
  \  management of APIs across multiple API gateways. Supports validation\n      of proxy specifications, API version management, and deployment to\n      gateways from a central federated control plane.\n    humanURL: https://apiida.com/product/apiida-api-control-plane/\n    baseURL: https://api.apiida.com\n    tags:\n      - API Lifecycle\n      - API Management\n      - Federated Control Plane\n      - Governance\n    properties:\n      - type: Documentation\n        url: https://apiida.com/product/apiida-api-control-plane/\n      - type: OpenAPI\n        url: openapi/apiida-api-control-plane-openapi.yml\n      - type: JSONSchema\n        url: json-schema/apiida-api.json\n      - type: JSONSchema\n        url: json-schema/apiida-deployment.json\n      - type: JSON-LD\n        url: json-ld/apiida-context.jsonld\n  - aid: apiida:api-gateway-manager\n    name: APIIDA API Gateway Manager\n    description: >-\n      REST API for the APIIDA API Gateway Manager, enabling programmatic\n     \
  \ management of Broadcom Layer7 API gateways. Supports gateway\n      registration, API deployment and migration, monitoring and metrics\n      collection, and alarm configuration across managed gateway instances.\n    humanURL: https://apiida.com/product/apiida-api-gateway-manager/\n    baseURL: https://api.apiida.com\n    tags:\n      - API Deployments\n      - API Gateway\n      - Layer7\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://apiida.com/product/apiida-api-gateway-manager/\n      - type: Documentation\n        url: https://apiida.atlassian.net/wiki/spaces/AAGM\n      - type: OpenAPI\n        url: openapi/apiida-api-gateway-manager-openapi.yml\n      - type: JSONSchema\n        url: json-schema/apiida-gateway.json\n      - type: JSONSchema\n        url: json-schema/apiida-deployment.json\n      - type: JSON-LD\n        url: json-ld/apiida-context.jsonld\ncommon:\n  - type: Website\n    url: https://apiida.com/\n  - type: Documentation\n\
  \    url: https://apiida.atlassian.net/wiki/spaces/AAGM\n  - type: Support\n    url: https://apiida.com/support/?lang=en\n  - type: GitHubOrganization\n    url: https://github.com/apiida\n  - type: Features\n    data:\n      - name: Federated API Control Plane\n        description: Centrally discover, govern, and provision APIs across multiple API gateway vendors from a single control plane.\n      - name: Multi-Gateway Support\n        description: Manage APIs across heterogeneous gateway environments including Broadcom Layer7, AWS API Gateway, Azure APIM, and others.\n      - name: API Deployment Automation\n        description: Automate API deployments and migrations across gateway instances with version management and rollback.\n      - name: Monitoring and Alarming\n        description: Collect gateway metrics and configure alarms for proactive API operations management.\n      - name: Proxy Specification Validation\n        description: Validate API proxy specifications before deployment\
  \ to ensure compatibility and standards compliance.\n  - type: UseCases\n    data:\n      - name: Enterprise API Governance\n        description: Govern APIs across multiple teams and gateway technologies from a centralized control plane.\n      - name: Gateway Migration\n        description: Migrate APIs between gateway vendors with automated tooling and compatibility validation.\n      - name: Layer7 Operations Automation\n        description: Automate routine Broadcom Layer7 gateway operations including deployments, monitoring, and alarming.\n      - name: Multi-Vendor API Management\n        description: Unify API management operations across heterogeneous gateway infrastructure.\n  - type: Solutions\n    data:\n      - name: API Control Plane\n        description: Central API management and governance for multi-vendor API gateway environments.\n      - name: API Gateway Manager\n        description: Automated operations management for Broadcom Layer7 API gateway environments.\n  \
  \    - name: Enterprise\n        description: Custom licensing with dedicated support for large-scale federated API management deployments.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- Federated API Management
- Governance
- Layer7
url: https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/apis.yml
use_cases:
- description: Govern APIs across multiple teams and gateway technologies from a centralized control plane.
  name: Enterprise API Governance
- description: Migrate APIs between gateway vendors with automated tooling and compatibility validation.
  name: Gateway Migration
- description: Automate routine Broadcom Layer7 gateway operations including deployments, monitoring, and alarming.
  name: Layer7 Operations Automation
- description: Unify API management operations across heterogeneous gateway infrastructure.
  name: Multi-Vendor API Management
---
