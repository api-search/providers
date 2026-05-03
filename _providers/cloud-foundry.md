---
api_count: 5
apis:
- description: The Cloud Controller API v3 is the primary REST control plane for Cloud Foundry. It manages organizations, spaces, applications, processes, builds, droplets, packages, routes, domains, service instanc
  name: Cloud Foundry Cloud Controller API v3
  slug: cloud-controller-api-v3
- description: The User Account and Authentication (UAA) server is Cloud Foundry's identity provider and OAuth 2.0 authorization server. It issues tokens consumed by the Cloud Controller, brokers, and operator tooli
  name: Cloud Foundry UAA
  slug: uaa
- description: Loggregator is Cloud Foundry's distributed log and metric pipeline that aggregates application logs, platform component logs, and metrics for streaming consumption by users and external sinks. It expo
  name: Cloud Foundry Loggregator
  slug: loggregator
- description: The Open Service Broker API is the open specification originally developed by Cloud Foundry and now used by Kubernetes and other platforms to provision and manage backing services through a common HTT
  name: Open Service Broker API
  slug: open-service-broker-api
- description: BOSH is Cloud Foundry's release engineering tool for packaging, deploying, and managing distributed software. The BOSH Director API exposes deployment, stemcell, release, task, and VM lifecycle operat
  name: BOSH Director API
  slug: bosh
capabilities:
- description: ''
  name: Cloud Foundry
  slug: cloud-foundry
common:
- title: ''
  type: Website
  url: https://www.cloudfoundry.org/
- title: ''
  type: Documentation
  url: https://docs.cloudfoundry.org/
- title: ''
  type: GitHub
  url: https://github.com/cloudfoundry
- title: ''
  type: Foundation
  url: https://www.cloudfoundry.org/foundation/
- title: ''
  type: Community
  url: https://www.cloudfoundry.org/community/
- title: ''
  type: Slack
  url: https://slack.cloudfoundry.org/
- title: ''
  type: Blog
  url: https://www.cloudfoundry.org/blog/
- title: ''
  type: Events
  url: https://www.cloudfoundry.org/events/
- title: ''
  type: Privacy Policy
  url: https://www.cloudfoundry.org/privacy-policy/
- title: ''
  type: Trademark
  url: https://www.cloudfoundry.org/trademark-policy/
- title: ''
  type: JSON-LD
  url: json-ld/cloud-foundry-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloud-foundry-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloud-foundry.yaml
created: '2024-01-01'
description: Cloud Foundry is an open-source, multi-cloud Platform as a Service (PaaS) governed by the Cloud Foundry Foundation. It provides a developer-friendly application platform where operators push source code or container images and Cloud Foundry handles staging, routing, scaling, and lifecycle management. The CF API (api.cloudfoundry.org) is the primary control plane and is documented at v3.cloudfoundry.org/version/release-candidate. The ecosystem also includes the User Account and Authentication (UAA) OAuth 2.0 server, the Loggregator log and metric pipeline, the Diego container scheduler, the Open Service Broker API for marketplace services, and the Eirini Kubernetes-based scheduler.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloud Foundry Context
  property_count: 11
  slug: cloud-foundry-context
layout: provider
modified: '2026-04-23'
name: Cloud Foundry
rules:
- name: Cloud Foundry API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: cloud-foundry-rules
skills: []
slug: cloud-foundry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloud-foundry\nname: Cloud Foundry\ndescription: >-\n  Cloud Foundry is an open-source, multi-cloud Platform as a Service\n  (PaaS) governed by the Cloud Foundry Foundation. It provides a\n  developer-friendly application platform where operators push source\n  code or container images and Cloud Foundry handles staging,\n  routing, scaling, and lifecycle management. The CF API\n  (api.cloudfoundry.org) is the primary control plane and is\n  documented at v3.cloudfoundry.org/version/release-candidate. The\n  ecosystem also includes the User Account and Authentication\n  (UAA) OAuth 2.0 server, the Loggregator log and metric pipeline,\n  the Diego container scheduler, the Open Service Broker API for\n  marketplace services, and the Eirini Kubernetes-based scheduler.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloud-foundry/refs/heads/main/apis.yml\ncreated: '2024-01-01'\n\
  modified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: opensource\ntags:\n  - Cloud Foundry Foundation\n  - Containers\n  - Multi-Cloud\n  - Open Source\n  - PaaS\n  - Platform\napis:\n  - aid: cloud-foundry:cloud-controller-api-v3\n    name: Cloud Foundry Cloud Controller API v3\n    tags:\n      - Apps\n      - PaaS\n      - Platform\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://v3-apidocs.cloudfoundry.org/\n    properties:\n      - url: https://v3-apidocs.cloudfoundry.org/\n        type: Documentation\n      - url: https://github.com/cloudfoundry/cloud_controller_ng\n        type: Source Code\n      - url: openapi/cloud-foundry-cloud-controller-api-v3-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cloud Controller API v3 is the primary REST control plane\n      for Cloud Foundry. It manages organizations, spaces,\n      applications, processes, builds, droplets, packages, routes,\n\
  \      domains, service instances, service brokers, tasks, users,\n      roles, and platform metadata. Authentication is delegated to\n      UAA via OAuth 2.0 bearer tokens.\n  - aid: cloud-foundry:uaa\n    name: Cloud Foundry UAA\n    tags:\n      - Authentication\n      - Identity\n      - OAuth 2.0\n      - Security\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudfoundry.org/uaa/\n    properties:\n      - url: https://docs.cloudfoundry.org/uaa/\n        type: Documentation\n      - url: https://github.com/cloudfoundry/uaa\n        type: Source Code\n      - url: https://docs.cloudfoundry.org/api/uaa/\n        type: Reference\n    description: >-\n      The User Account and Authentication (UAA) server is Cloud\n      Foundry's identity provider and OAuth 2.0 authorization server.\n      It issues tokens consumed by the Cloud Controller, brokers, and\n      operator tooling, and supports SAML and LDAP federation,\n\
  \      multifactor authentication, and SCIM-style user and group\n      management.\n  - aid: cloud-foundry:loggregator\n    name: Cloud Foundry Loggregator\n    tags:\n      - Logs\n      - Metrics\n      - Observability\n      - Streaming\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cloudfoundry.org/loggregator/\n    properties:\n      - url: https://docs.cloudfoundry.org/loggregator/\n        type: Documentation\n      - url: https://github.com/cloudfoundry/loggregator-release\n        type: Source Code\n      - url: asyncapi/cloud-foundry-loggregator-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Loggregator is Cloud Foundry's distributed log and metric\n      pipeline that aggregates application logs, platform component\n      logs, and metrics for streaming consumption by users and\n      external sinks. It exposes a WebSocket Firehose, a v2 gRPC\n      egress API, and the Reverse Log Proxy.\n\
  \  - aid: cloud-foundry:open-service-broker-api\n    name: Open Service Broker API\n    tags:\n      - Marketplace\n      - Open Standard\n      - Service Broker\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.openservicebrokerapi.org/\n    properties:\n      - url: https://www.openservicebrokerapi.org/\n        type: Documentation\n      - url: https://github.com/openservicebrokerapi/servicebroker\n        type: Specification\n    description: >-\n      The Open Service Broker API is the open specification originally\n      developed by Cloud Foundry and now used by Kubernetes and other\n      platforms to provision and manage backing services through a\n      common HTTP interface. Brokers expose a catalog and lifecycle\n      operations for service instances and bindings.\n  - aid: cloud-foundry:bosh\n    name: BOSH Director API\n    tags:\n      - Deployment\n      - Infrastructure\n      - Lifecycle\n      - Releases\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://bosh.io/docs/director-api-v1/\n    properties:\n      - url: https://bosh.io/docs/director-api-v1/\n        type: Documentation\n      - url: https://github.com/cloudfoundry/bosh\n        type: Source Code\n    description: >-\n      BOSH is Cloud Foundry's release engineering tool for packaging,\n      deploying, and managing distributed software. The BOSH Director\n      API exposes deployment, stemcell, release, task, and VM\n      lifecycle operations used by operators and CI tooling to\n      manage Cloud Foundry itself and the workloads it depends on.\ncommon:\n  - type: Website\n    url: https://www.cloudfoundry.org/\n  - type: Documentation\n    url: https://docs.cloudfoundry.org/\n  - type: GitHub\n    url: https://github.com/cloudfoundry\n  - type: Foundation\n    url: https://www.cloudfoundry.org/foundation/\n  - type: Community\n    url: https://www.cloudfoundry.org/community/\n\
  \  - type: Slack\n    url: https://slack.cloudfoundry.org/\n  - type: Blog\n    url: https://www.cloudfoundry.org/blog/\n  - type: Events\n    url: https://www.cloudfoundry.org/events/\n  - type: Privacy Policy\n    url: https://www.cloudfoundry.org/privacy-policy/\n  - type: Trademark\n    url: https://www.cloudfoundry.org/trademark-policy/\n  - type: JSON-LD\n    url: json-ld/cloud-foundry-context.jsonld\n  - type: Spectral\n    url: rules/cloud-foundry-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloud-foundry.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud-foundry/refs/heads/main/apis.yml
tags:
- Cloud Foundry Foundation
- Containers
- Multi-Cloud
- Open Source
- PaaS
- Platform
url: https://raw.githubusercontent.com/api-evangelist/cloud-foundry/refs/heads/main/apis.yml
use_cases: []
---
