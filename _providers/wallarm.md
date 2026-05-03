---
api_count: 1
api_specs:
- filename: wallarm-openapi.yml
  format: yaml
  label: Wallarm API
  slug: wallarm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/openapi/wallarm-openapi.yml
apis:
- description: The Wallarm API provides programmatic access to the Wallarm API Security Platform, enabling management of attacks, incidents, vulnerabilities, rules, IP lists, filter nodes, users, and integrations. T
  name: Wallarm API
  slug: wallarm-api
capabilities:
- description: Unified workflow for API security operations using the Wallarm platform. Enables security teams to monitor attacks, investigate vulnerabilities, manage IP blocklists, configure security rules, and coo
  name: Wallarm API Security Operations
  slug: api-security-operations
common:
- title: ''
  type: Website
  url: https://www.wallarm.com/
- title: ''
  type: Documentation
  url: https://docs.wallarm.com/
- title: ''
  type: Reference
  url: https://docs.wallarm.com/api/overview/
- title: ''
  type: Examples
  url: https://docs.wallarm.com/api/request-examples/
- title: ''
  type: Console
  url: https://apiconsole.us1.wallarm.com/
- title: ''
  type: Console
  url: https://apiconsole.eu1.wallarm.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/wallarm
- title: ''
  type: OpenSource
  url: https://github.com/wallarm/api-firewall
- title: ''
  type: SDK
  url: https://github.com/wallarm/wallarm-go
- title: ''
  type: TerraformProvider
  url: https://github.com/wallarm/terraform-provider-wallarm
- title: ''
  type: TerraformModule
  url: https://github.com/wallarm/terraform-aws-wallarm
- title: ''
  type: SDK
  url: https://github.com/wallarm/ingress
- title: ''
  type: HelmChart
  url: https://github.com/wallarm/helm-charts
- title: ''
  type: Tool
  url: https://github.com/wallarm/gotestwaf
created: '2025-01-08'
description: Wallarm provides advanced API security and protection solutions for APIs, web applications, and microservices. The platform includes API discovery, real-time attack protection, vulnerability testing, and an open-source API Firewall that enforces OpenAPI specifications as a positive security model. Wallarm supports deployment on Kubernetes, cloud environments, and as an NGINX-based proxy.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Wallarm Context
  property_count: 14
  slug: wallarm-context
layout: provider
modified: '2026-05-03'
name: Wallarm
rules:
- name: Wallarm API Rules
  rule_count: 12
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 7
  slug: wallarm-rules
skills: []
slug: wallarm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wallarm\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/apis.yml\napis:\n  - aid: wallarm:wallarm-api\n    name: Wallarm API\n    tags:\n      - API Security\n      - Attack Detection\n      - Vulnerability Management\n      - WAF\n      - Rules\n      - IP Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://us1.api.wallarm.com\n    humanURL: https://docs.wallarm.com/api/overview/\n    properties:\n      - url: https://docs.wallarm.com/api/overview/\n        type: Documentation\n      - url: https://apiconsole.us1.wallarm.com/\n        type: SwaggerUI\n      - url: https://apiconsole.eu1.wallarm.com/\n        type: SwaggerUI\n      - url: openapi/wallarm-openapi.yml\n        type: OpenAPI\n      - url: rules/wallarm-rules.yml\n        type: SpectralRules\n      - url: capabilities/api-security-operations.yaml\n        type: NaftikoCapabilities\n      - url: json-schema/wallarm-attack-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/wallarm-vulnerability-schema.json\n        type: JSONSchema\n      - url: json-ld/wallarm-context.jsonld\n        type: JSONLDContext\n      - url: vocabulary/wallarm-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The Wallarm API provides programmatic access to the Wallarm API Security\n      Platform, enabling management of attacks, incidents, vulnerabilities,\n      rules, IP lists, filter nodes, users, and integrations. The API is\n      available on both the US Cloud (us1.api.wallarm.com) and EU Cloud\n      (api.wallarm.com), and uses API token authentication via the\n      X-WallarmApi-Token header.\nname: Wallarm\ntags:\n  - API Security\n  - Security Testing\n  - WAF\n  - Cybersecurity\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Wallarm provides advanced\
  \ API security and protection solutions for APIs,\n  web applications, and microservices. The platform includes API discovery,\n  real-time attack protection, vulnerability testing, and an open-source API\n  Firewall that enforces OpenAPI specifications as a positive security model.\n  Wallarm supports deployment on Kubernetes, cloud environments, and as an\n  NGINX-based proxy.\ncommon:\n  - url: https://www.wallarm.com/\n    name: Wallarm - Advanced API Security\n    type: Website\n  - url: https://docs.wallarm.com/\n    name: Wallarm Documentation\n    type: Documentation\n  - url: https://docs.wallarm.com/api/overview/\n    name: Wallarm API Reference\n    type: Reference\n  - url: https://docs.wallarm.com/api/request-examples/\n    name: Wallarm API Request Examples\n    type: Examples\n  - url: https://apiconsole.us1.wallarm.com/\n    name: Wallarm API Console (US)\n    type: Console\n  - url: https://apiconsole.eu1.wallarm.com/\n    name: Wallarm API Console (EU)\n    type: Console\n\
  \  - url: https://github.com/wallarm\n    name: Wallarm GitHub Organization\n    type: GitHubOrganization\n  - url: https://github.com/wallarm/api-firewall\n    name: Wallarm API Firewall\n    type: OpenSource\n  - url: https://github.com/wallarm/wallarm-go\n    name: Wallarm Go SDK\n    type: SDK\n  - url: https://github.com/wallarm/terraform-provider-wallarm\n    name: Wallarm Terraform Provider\n    type: TerraformProvider\n  - url: https://github.com/wallarm/terraform-aws-wallarm\n    name: Wallarm Terraform AWS Module\n    type: TerraformModule\n  - url: https://github.com/wallarm/ingress\n    name: Wallarm Kubernetes Ingress Controller\n    type: SDK\n  - url: https://github.com/wallarm/helm-charts\n    name: Wallarm Helm Charts\n    type: HelmChart\n  - url: https://github.com/wallarm/gotestwaf\n    name: GoTestWAF - WAF Security Testing Tool\n    type: Tool\n  - url: https://www.wallarm.com/product/integrations\n    name: Wallarm Integrations\n    type: Integrations\nfeatures:\n\
  \  - API Discovery and Inventory\n  - Real-Time Attack Detection and Blocking\n  - Vulnerability Assessment and Management\n  - API Firewall (OpenAPI-based positive security model)\n  - Shadow and Zombie API Detection\n  - IP List Management (allowlist, denylist, graylist)\n  - Custom Security Rules Engine\n  - SIEM and SOAR Integrations\n  - Kubernetes-Native Deployment (sidecar, ingress)\n  - Multi-Cloud and Hybrid Deployment Support\nuseCases:\n  - Protect APIs from OWASP Top 10 attacks\n  - Discover and inventory all APIs in a microservices environment\n  - Enforce API contract compliance with OpenAPI specifications\n  - Detect and respond to zero-day API vulnerabilities\n  - Manage IP reputation lists and block malicious traffic\n  - Automate security testing in CI/CD pipelines\nintegrations:\n  - Splunk\n  - PagerDuty\n  - Slack\n  - Jira\n  - Microsoft Teams\n  - OpsGenie\n  - DataDog\n  - Sumo Logic\n  - AWS\n  - Azure\n  - Google Cloud\n  - Kubernetes\n  - Terraform\nsolutions:\n\
  \  - API Security\n  - Web Application Firewall\n  - API Discovery\n  - DevSecOps\n  - Cloud Security\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/apis.yml
tags:
- API Security
- Security Testing
- WAF
- Cybersecurity
url: https://raw.githubusercontent.com/api-evangelist/wallarm/refs/heads/main/apis.yml
use_cases: []
---
