---
api_count: 2
api_specs:
- filename: solo-io-gloo-portal-server-api-openapi.yml
  format: yaml
  label: Solo.io Gloo Portal Server API
  slug: gloo-portal-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/openapi/solo-io-gloo-portal-server-api-openapi.yml
- filename: solo-io-gloo-gateway-management-api-openapi.yml
  format: yaml
  label: Solo.io Gloo Gateway Management API
  slug: gloo-gateway-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/openapi/solo-io-gloo-gateway-management-api-openapi.yml
apis:
- description: The Gloo Platform Portal Server API provides REST endpoints to manage user access to the developer portal and API resources. It enables developers to discover available APIs, view API schemas and docu
  name: Solo.io Gloo Portal Server API
  slug: gloo-portal-server-api
- description: The Gloo Gateway Management API provides administrative REST endpoints for managing and monitoring Gloo Gateway deployments. Gloo Gateway is a cloud-native API gateway and AI gateway built on Envoy Pr
  name: Solo.io Gloo Gateway Management API
  slug: gloo-gateway-management-api
common:
- title: ''
  type: Customers
  url: https://www.solo.io/customers
- title: ''
  type: CaseStudies
  url: https://www.solo.io/resources/case-study
- title: ''
  type: Blog
  url: https://www.solo.io/blog
- title: ''
  type: Documentation
  url: https://www.solo.io/docs
- title: ''
  type: WhitePapers
  url: https://www.solo.io/resources/white-paper
- title: ''
  type: Videos
  url: https://www.solo.io/resources/video
- title: ''
  type: Webinars
  url: https://www.solo.io/resources/webinar
- title: ''
  type: eBooks
  url: https://www.solo.io/resources/ebook
- title: ''
  type: Partners
  url: https://www.solo.io/partners
- title: ''
  type: Support
  url: https://www.solo.io/company/get-support
- title: ''
  type: Pricing
  url: https://www.solo.io/pricing
created: '2025-01-08'
description: Cloud-native API management and service connectivity to automate security, observability, resiliency, and traffic control for any API or workload in any environment.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Solo Io Context
  property_count: 13
  slug: solo-io-context
layout: provider
modified: '2026-03-16'
name: Solo.io
skills: []
slug: solo-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: solo-io\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/apis.yml\napis:\n  - aid: solo-io:gloo-portal-server-api\n    name: Solo.io Gloo Portal Server API\n    tags:\n      - API Gateway\n      - API Keys\n      - API Management\n      - Developer Portal\n    humanURL: https://docs.solo.io/gloo-mesh-gateway/latest/portal/openapi/\n    properties:\n      - url: https://docs.solo.io/gloo-mesh-gateway/latest/portal/openapi/\n        type: Documentation\n      - url: openapi/solo-io-gloo-portal-server-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/api-product.json\n        type: JSONSchema\n      - url: json-schema/api-version.json\n        type: JSONSchema\n      - url: json-schema/usage-plan.json\n        type: JSONSchema\n      - url: json-schema/api-key.json\n        type: JSONSchema\n      - url: json-ld/solo-io-context.jsonld\n        type: JSONLD\n  \
  \  description: >-\n      The Gloo Platform Portal Server API provides REST endpoints to manage user\n      access to the developer portal and API resources. It enables developers to\n      discover available APIs, view API schemas and documentation, manage API\n      keys, and review usage plans for the Gloo developer portal.\n  - aid: solo-io:gloo-gateway-management-api\n    name: Solo.io Gloo Gateway Management API\n    tags:\n      - API Gateway\n      - Cloud Native\n      - Envoy Proxy\n      - Service Mesh\n      - Traffic Management\n    humanURL: https://docs.solo.io/gloo-edge/latest/reference/api/\n    properties:\n      - url: https://docs.solo.io/gloo-edge/latest/reference/api/\n        type: Documentation\n      - url: openapi/solo-io-gloo-gateway-management-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/upstream.json\n        type: JSONSchema\n      - url: json-schema/virtual-service.json\n        type: JSONSchema\n      - url: json-schema/route.json\n \
  \       type: JSONSchema\n      - url: json-schema/route-table.json\n        type: JSONSchema\n      - url: json-schema/gateway.json\n        type: JSONSchema\n      - url: json-schema/proxy.json\n        type: JSONSchema\n      - url: json-schema/resource-metadata.json\n        type: JSONSchema\n      - url: json-schema/resource-status.json\n        type: JSONSchema\n      - url: json-ld/solo-io-context.jsonld\n        type: JSONLD\n    description: >-\n      The Gloo Gateway Management API provides administrative REST endpoints for\n      managing and monitoring Gloo Gateway deployments. Gloo Gateway is a\n      cloud-native API gateway and AI gateway built on Envoy Proxy that provides\n      ingress control, traffic management, security, observability, and\n      function-level routing for Kubernetes environments.\nname: Solo.io\ntags:\n  - AI Gateway\n  - Analytics\n  - Automation\n  - Gateways\n  - Management\n  - Monetization\n  - Observability\n  - Platform\n  - Resiliency\n  -\
  \ Security\n  - Service Mesh\n  - Traffic Control\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-03-16'\nposition: Consuming\ndescription: >-\n  Cloud-native API management and service connectivity to automate security,\n  observability, resiliency, and traffic control for any API or workload in any\n  environment.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Customers | Solo.io\n    description: 'null'\n    url: https://www.solo.io/customers\n    type: Customers\n  - name: Case Studies | Solo.io\n    description: 'null'\n    url: https://www.solo.io/resources/case-study\n    type: CaseStudies\n  - name: Blog | Solo.io\n    description: 'null'\n    url: https://www.solo.io/blog\n    type: Blog\n  - name: Docs | Solo.io\n    description: 'null'\n    url: https://www.solo.io/docs\n    type: Documentation\n  -\
  \ name: White Papers | Solo.io\n    description: 'null'\n    url: https://www.solo.io/resources/white-paper\n    type: WhitePapers\n  - name: Videos | Solo.io\n    description: 'null'\n    url: https://www.solo.io/resources/video\n    type: Videos\n  - name: Webinars | Solo.io\n    description: 'null'\n    url: https://www.solo.io/resources/webinar\n    type: Webinars\n  - name: eBooks | Solo.io\n    description: 'null'\n    url: https://www.solo.io/resources/ebook\n    type: eBooks\n  - name: Partners | Solo.io\n    description: 'null'\n    url: https://www.solo.io/partners\n    type: Partners\n  - name: Get Support | Solo.io\n    description: 'null'\n    url: https://www.solo.io/company/get-support\n    type: Support\n  - name: Pricing | Solo.io\n    description: 'null'\n    url: https://www.solo.io/pricing\n    type: Pricing\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/apis.yml
tags:
- AI Gateway
- Analytics
- Automation
- Gateways
- Management
- Monetization
- Observability
- Platform
- Resiliency
- Security
- Service Mesh
- Traffic Control
url: https://raw.githubusercontent.com/api-evangelist/solo-io/refs/heads/main/apis.yml
use_cases: []
---
