---
api_count: 1
api_specs:
- filename: ngrok-api-openapi.yml
  format: yaml
  label: ngrok API
  slug: ngrok
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/openapi/ngrok-api-openapi.yml
apis:
- description: The ngrok API provides programmatic access to all of ngrok's resources. The API is REST-ish, follows most REST conventions, and listens only on port 443 to avoid accidental unencrypted requests. All A
  name: ngrok API
  slug: ngrok
common:
- title: ''
  type: Website
  url: https://ngrok.com
- title: ''
  type: Documentation
  url: https://ngrok.com/docs
- title: ''
  type: APIReference
  url: https://ngrok.com/docs/api
- title: ''
  type: GettingStarted
  url: https://ngrok.com/docs/getting-started
- title: ''
  type: Blog
  url: https://ngrok.com/blog
- title: ''
  type: ChangeLog
  url: https://ngrok.com/docs/changelog
- title: ''
  type: Pricing
  url: https://ngrok.com/pricing
- title: ''
  type: Support
  url: https://ngrok.com/support
- title: ''
  type: StatusPage
  url: https://status.ngrok.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/ngrok
- title: Go SDK
  type: SDK
  url: https://github.com/ngrok/ngrok-go
- title: Rust SDK
  type: SDK
  url: https://github.com/ngrok/ngrok-rust
- title: JavaScript SDK
  type: SDK
  url: https://github.com/ngrok/ngrok-javascript
- title: Python SDK
  type: SDK
  url: https://github.com/ngrok/ngrok-python
- title: Terraform Provider
  type: Terraform
  url: https://registry.terraform.io/providers/ngrok/ngrok/latest
- title: Kubernetes Operator
  type: KubernetesOperator
  url: https://github.com/ngrok/ngrok-operator
- title: ''
  type: X
  url: https://x.com/ngrokHQ
created: '2025-01-08'
description: ngrok is a unified application delivery network for developers, providing secure tunnels, ingress-as-a-service, API gateway, and AI gateway capabilities. It enables developers to expose local services on the public internet, manage edge ingress, and route traffic to AI providers without redeploying applications. ngrok provides a unique URL for each tunnel, traffic policy controls, and a comprehensive REST API for programmatic management of all resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Ngrok Context
  property_count: 12
  slug: ngrok-context
layout: provider
modified: '2026-04-28'
name: ngrok
skills: []
slug: ngrok
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ngrok\nname: ngrok\ndescription: >-\n  ngrok is a unified application delivery network for developers, providing secure\n  tunnels, ingress-as-a-service, API gateway, and AI gateway capabilities. It enables\n  developers to expose local services on the public internet, manage edge ingress,\n  and route traffic to AI providers without redeploying applications. ngrok provides\n  a unique URL for each tunnel, traffic policy controls, and a comprehensive REST\n  API for programmatic management of all resources.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Gateway\n  - API Gateway\n  - Compute\n  - Developer Tools\n  - Gateways\n  - Ingress\n  - Platform\n  - Proxies\n  - Servers\n  - Tunnels\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ ngrok:ngrok\n    name: ngrok API\n    description: >-\n      The ngrok API provides programmatic access to all of ngrok's resources. The\n      API is REST-ish, follows most REST conventions, and listens only on port 443\n      to avoid accidental unencrypted requests. All API access requires an API key.\n      Resources include endpoints, tunnels, edges (HTTPS, TCP, TLS), backends,\n      reserved domains and addresses, IP policies and restrictions, TLS and SSH\n      certificates, event subscriptions, API keys, and credentials.\n    humanURL: https://ngrok.com/docs/api\n    baseURL: https://api.ngrok.com\n    tags:\n      - API Gateway\n      - Compute\n      - Demonstration\n      - Gateways\n      - Platform\n      - Proxies\n      - Servers\n      - Testing\n      - Tunnels\n    properties:\n      - type: Documentation\n        url: https://ngrok.com/docs/api\n      - type: APIReference\n        url: https://ngrok.com/docs/api\n      - type: OpenAPI\n        url: openapi/ngrok-api-openapi.yml\n\
  \      - type: JSONLD\n        url: json-ld/ngrok-context.jsonld\n      - type: JSONSchema\n        url: json-schema/tunnel.json\n      - type: JSONSchema\n        url: json-schema/endpoint.json\n      - type: JSONSchema\n        url: json-schema/https-edge.json\n      - type: JSONSchema\n        url: json-schema/tcp-edge.json\n      - type: JSONSchema\n        url: json-schema/tls-edge.json\n      - type: JSONSchema\n        url: json-schema/reserved-domain.json\n      - type: JSONSchema\n        url: json-schema/reserved-addr.json\n      - type: JSONSchema\n        url: json-schema/api-key.json\n      - type: JSONSchema\n        url: json-schema/ip-policy.json\n      - type: JSONSchema\n        url: json-schema/tls-certificate.json\n      - type: JSONSchema\n        url: json-schema/event-subscription.json\n      - type: JSONSchema\n        url: json-schema/tunnel-session.json\n      - type: GitHubRepository\n        url: https://github.com/ngrok/ngrok-openapi\n        title: ngrok-openapi\n\
  common:\n  - type: Website\n    url: https://ngrok.com\n  - type: Documentation\n    url: https://ngrok.com/docs\n  - type: APIReference\n    url: https://ngrok.com/docs/api\n  - type: GettingStarted\n    url: https://ngrok.com/docs/getting-started\n  - type: Blog\n    url: https://ngrok.com/blog\n  - type: ChangeLog\n    url: https://ngrok.com/docs/changelog\n  - type: Pricing\n    url: https://ngrok.com/pricing\n  - type: Support\n    url: https://ngrok.com/support\n  - type: StatusPage\n    url: https://status.ngrok.com\n  - type: GitHubOrganization\n    url: https://github.com/ngrok\n  - type: SDK\n    url: https://github.com/ngrok/ngrok-go\n    title: Go SDK\n  - type: SDK\n    url: https://github.com/ngrok/ngrok-rust\n    title: Rust SDK\n  - type: SDK\n    url: https://github.com/ngrok/ngrok-javascript\n    title: JavaScript SDK\n  - type: SDK\n    url: https://github.com/ngrok/ngrok-python\n    title: Python SDK\n  - type: Terraform\n    url: https://registry.terraform.io/providers/ngrok/ngrok/latest\n\
  \    title: Terraform Provider\n  - type: KubernetesOperator\n    url: https://github.com/ngrok/ngrok-operator\n    title: Kubernetes Operator\n  - type: X\n    url: https://x.com/ngrokHQ\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml
tags:
- AI Gateway
- API Gateway
- Compute
- Developer Tools
- Gateways
- Ingress
- Platform
- Proxies
- Servers
- Tunnels
url: https://raw.githubusercontent.com/api-evangelist/ngrok/refs/heads/main/apis.yml
use_cases: []
---
