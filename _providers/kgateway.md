---
api_count: 1
api_specs:
- filename: kgateway-kubernetes-gateway-api-openapi.yml
  format: yaml
  label: Kgateway Kubernetes Gateway API
  slug: kgateway-kubernetes-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/openapi/kgateway-kubernetes-gateway-api-openapi.yml
apis:
- description: The kgateway Kubernetes Gateway API provides custom resource definitions (CRDs) under the gateway.kgateway.dev/v1alpha1 API group for managing traffic policies, backends, direct responses, gateway ext
  name: Kgateway Kubernetes Gateway API
  slug: kgateway-kubernetes-gateway-api
common:
- title: ''
  type: Website
  url: https://kgateway.dev/
- title: ''
  type: Videos
  url: https://kgateway.dev/resources/videos/
- title: ''
  type: Blog
  url: https://kgateway.dev/blog/
- title: ''
  type: Documentation
  url: https://kgateway.dev/docs/envoy/latest/
- title: ''
  type: GitHub
  url: https://github.com/kgateway-dev/kgateway
created: '2026-01-02'
description: kgateway is the most widely deployed gateway in Kubernetes for microservices and AI agents. It is a feature-rich, fast, and flexible Kubernetes-native ingress controller and next-generation API gateway built on top of Envoy proxy and the Kubernetes Gateway API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kgateway Context
  property_count: 7
  slug: kgateway-context
layout: provider
modified: '2026-04-28'
name: Kgateway
skills: []
slug: kgateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kgateway\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/apis.yml\napis:\n  - aid: kgateway:kgateway-kubernetes-gateway-api\n    name: Kgateway Kubernetes Gateway API\n    tags:\n      - AI Gateway\n      - API Gateway\n      - Envoy\n      - Gateways\n      - Kubernetes\n      - Traffic Management\n    humanURL: https://kgateway.dev/docs/envoy/latest/reference/api/\n    baseURL: https://kubernetes.default.svc/apis/gateway.kgateway.dev/v1alpha1\n    properties:\n      - url: https://kgateway.dev/docs/envoy/latest/reference/api/\n        type: Documentation\n      - url: openapi/kgateway-kubernetes-gateway-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/traffic-policy.json\n        type: JSONSchema\n      - url: json-schema/backend.json\n        type: JSONSchema\n      - url: json-schema/direct-response.json\n        type: JSONSchema\n      - url: json-schema/gateway-extension.json\n        type: JSONSchema\n      -\
  \ url: json-schema/gateway-parameters.json\n        type: JSONSchema\n      - url: json-schema/http-listener-policy.json\n        type: JSONSchema\n      - url: json-schema/ai-backend.json\n        type: JSONSchema\n      - url: json-ld/kgateway-context.jsonld\n        type: JSONLD\n    description: >-\n      The kgateway Kubernetes Gateway API provides custom resource definitions\n      (CRDs) under the gateway.kgateway.dev/v1alpha1 API group for managing\n      traffic policies, backends, direct responses, gateway extensions, gateway\n      parameters, HTTP listener policies, and AI backends. kgateway is built on\n      Envoy proxy and implements the Kubernetes Gateway API for microservices\n      and AI agent traffic management.\nname: Kgateway\ntags:\n  - Gateways\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-02'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  kgateway is the most\
  \ widely deployed gateway in Kubernetes for microservices and\n  AI agents. It is a feature-rich, fast, and flexible Kubernetes-native ingress controller\n  and next-generation API gateway built on top of Envoy proxy and the Kubernetes Gateway\n  API.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: kgateway\n    description: 'null'\n    url: https://kgateway.dev/\n    type: Website\n  - name: Videos – kgateway\n    description: 'null'\n    url: https://kgateway.dev/resources/videos/\n    type: Videos\n  - name: Blog – kgateway\n    description: 'null'\n    url: https://kgateway.dev/blog/\n    type: Blog\n  - name: Kgateway 2.1.x – kgateway\n    description: 'null'\n    url: https://kgateway.dev/docs/envoy/latest/\n    type: Documentation\n  - name: GitHub Repository\n    description: 'null'\n    url: https://github.com/kgateway-dev/kgateway\n    type: GitHub\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/apis.yml
tags:
- Gateways
url: https://raw.githubusercontent.com/api-evangelist/kgateway/refs/heads/main/apis.yml
use_cases: []
---
