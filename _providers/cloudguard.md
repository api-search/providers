---
api_count: 5
api_specs:
- filename: swagger.json
  format: json
  label: CloudGuard CNAPP REST API
  slug: cloudguard-cnapp-api
  spec_type: OpenAPI
  url: https://api.dome9.com/v2/swagger.json
apis:
- description: The CloudGuard CNAPP REST API (formerly Dome9 v2) is used to onboard AWS, Azure, GCP, Kubernetes, and on-premises accounts; create and run compliance/posture rulesets; retrieve security findings and a
  name: CloudGuard CNAPP REST API
  slug: cloudguard-cnapp-api
- description: Workload protection capabilities exposed through the CloudGuard platform for Kubernetes admission control, image assurance/CI scanning, runtime protection, and serverless function security.
  name: CloudGuard Workload Protection (CWPP) API
  slug: cloudguard-workload-api
- description: CloudGuard Code Security (formerly Spectral) provides developer-first SAST, infrastructure-as-code scanning, secrets detection, and SCA via CLI and API integrations into CI/CD pipelines.
  name: CloudGuard Code Security (Spectral) API
  slug: cloudguard-code-security-api
- description: CloudGuard WAF (CloudGuard AppSec) protects web applications and APIs with contextual machine-learning-based threat prevention; the platform exposes management APIs for policy, asset, and event config
  name: CloudGuard WAF API
  slug: cloudguard-waf-api
- description: CloudGuard Network Security delivers cloud-native firewalling and threat prevention with management APIs for gateway provisioning, rule management, and integrations with CI/CD pipelines.
  name: CloudGuard Network Security API
  slug: cloudguard-network-security-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.checkpoint.com/cloudguard/
- title: ''
  type: Documentation
  url: https://docs.cgn.portal.checkpoint.com/
- title: ''
  type: Developer Portal
  url: https://docs.cgn.portal.checkpoint.com/reference
- title: ''
  type: Getting Started
  url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/Getting-Started/Getting-started-with-CloudGuard.htm
- title: ''
  type: Authentication
  url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/API-Authentication.html
- title: ''
  type: Support
  url: https://support.checkpoint.com/
- title: ''
  type: Community
  url: https://community.checkpoint.com/
- title: ''
  type: Status
  url: https://status.dome9.com/
- title: ''
  type: Privacy Policy
  url: https://www.checkpoint.com/privacy/
- title: ''
  type: Terraform Provider
  url: https://registry.terraform.io/providers/dome9/dome9/latest/docs
- title: ''
  type: JSON-LD
  url: json-ld/cloudguard-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudguard-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudguard-capabilities.yml
created: '2024-01-01'
description: Check Point CloudGuard is a Cloud Native Application Protection Platform (CNAPP) that delivers cloud security posture management (CSPM), cloud workload protection (CWPP), code security, network security, and intelligence/CDR capabilities across AWS, Azure, GCP, Alibaba, Oracle, Kubernetes, and on-premises environments. The CloudGuard public REST API (originally Dome9) is used to onboard cloud accounts, run posture assessments, manage compliance bundles, retrieve findings, and configure policies and alerts.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudguard Context
  property_count: 5
  slug: cloudguard-context
layout: provider
modified: '2026-04-26'
name: CloudGuard
rules:
- name: CloudGuard API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: cloudguard-rules
skills: []
slug: cloudguard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudguard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cloudguard/refs/heads/main/apis.yml\nname: CloudGuard\ntags:\n  - Check Point\n  - CNAPP\n  - Cloud Security\n  - Compliance\n  - CSPM\n  - CWPP\n  - Posture Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-26'\nposition: Consumer\nx-type: company\nx-company: Check Point Software Technologies\ndescription: >-\n  Check Point CloudGuard is a Cloud Native Application Protection Platform\n  (CNAPP) that delivers cloud security posture management (CSPM), cloud\n  workload protection (CWPP), code security, network security, and\n  intelligence/CDR capabilities across AWS, Azure, GCP, Alibaba, Oracle,\n  Kubernetes, and on-premises environments. The CloudGuard public REST API\n  (originally Dome9) is used to onboard cloud accounts, run posture\n  assessments, manage compliance bundles, retrieve\
  \ findings, and configure\n  policies and alerts.\napis:\n  - aid: cloudguard:cloudguard-cnapp-api\n    name: CloudGuard CNAPP REST API\n    tags:\n      - CNAPP\n      - Cloud Security\n      - Compliance\n      - Posture\n    humanURL: https://docs.cgn.portal.checkpoint.com/reference\n    properties:\n      - url: https://docs.cgn.portal.checkpoint.com/reference\n        type: Documentation\n      - url: https://api.dome9.com/v2/swagger.json\n        type: OpenAPI\n      - url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/API-Authentication.html\n        type: Authentication\n      - url: https://registry.terraform.io/providers/dome9/dome9/latest/docs\n        type: Terraform Provider\n    description: >-\n      The CloudGuard CNAPP REST API (formerly Dome9 v2) is used to onboard\n      AWS, Azure, GCP, Kubernetes, and on-premises accounts; create and run\n      compliance/posture rulesets; retrieve security findings and alerts;\n      manage IAM safety, network\
  \ policies, and exclusions; and configure\n      notifications and integrations. Authentication is via API key and\n      secret over HTTP Basic.\n  - aid: cloudguard:cloudguard-workload-api\n    name: CloudGuard Workload Protection (CWPP) API\n    tags:\n      - Container Security\n      - CWPP\n      - Image Assurance\n      - Kubernetes\n    humanURL: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/Workload/Overview.htm\n    properties:\n      - url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/Workload/Overview.htm\n        type: Documentation\n    description: >-\n      Workload protection capabilities exposed through the CloudGuard\n      platform for Kubernetes admission control, image assurance/CI scanning,\n      runtime protection, and serverless function security.\n  - aid: cloudguard:cloudguard-code-security-api\n    name: CloudGuard Code Security (Spectral) API\n    tags:\n      - Code Security\n      - Secrets Detection\n      -\
  \ SAST\n    humanURL: https://docs.spectralops.io/\n    properties:\n      - url: https://docs.spectralops.io/\n        type: Documentation\n    description: >-\n      CloudGuard Code Security (formerly Spectral) provides developer-first\n      SAST, infrastructure-as-code scanning, secrets detection, and SCA via\n      CLI and API integrations into CI/CD pipelines.\n  - aid: cloudguard:cloudguard-waf-api\n    name: CloudGuard WAF API\n    tags:\n      - API Security\n      - WAF\n      - Web Application Firewall\n    humanURL: https://sc1.checkpoint.com/documents/CloudGuard_AppSec/Documentation/Default.htm\n    properties:\n      - url: https://sc1.checkpoint.com/documents/CloudGuard_AppSec/Documentation/Default.htm\n        type: Documentation\n    description: >-\n      CloudGuard WAF (CloudGuard AppSec) protects web applications and APIs\n      with contextual machine-learning-based threat prevention; the platform\n      exposes management APIs for policy, asset, and event configuration.\n\
  \  - aid: cloudguard:cloudguard-network-security-api\n    name: CloudGuard Network Security API\n    tags:\n      - Cloud Firewall\n      - Network Security\n    humanURL: https://www.checkpoint.com/cloudguard/cloud-network-security/\n    properties:\n      - url: https://www.checkpoint.com/cloudguard/cloud-network-security/\n        type: Documentation\n    description: >-\n      CloudGuard Network Security delivers cloud-native firewalling and\n      threat prevention with management APIs for gateway provisioning, rule\n      management, and integrations with CI/CD pipelines.\ncommon:\n  - type: Website\n    url: https://www.checkpoint.com/cloudguard/\n  - type: Documentation\n    url: https://docs.cgn.portal.checkpoint.com/\n  - type: Developer Portal\n    url: https://docs.cgn.portal.checkpoint.com/reference\n  - type: Getting Started\n    url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/Getting-Started/Getting-started-with-CloudGuard.htm\n  - type: Authentication\n\
  \    url: https://sc1.checkpoint.com/documents/CloudGuard_Dome9/Documentation/API-Authentication.html\n  - type: Support\n    url: https://support.checkpoint.com/\n  - type: Community\n    url: https://community.checkpoint.com/\n  - type: Status\n    url: https://status.dome9.com/\n  - type: Privacy Policy\n    url: https://www.checkpoint.com/privacy/\n  - type: Terraform Provider\n    url: https://registry.terraform.io/providers/dome9/dome9/latest/docs\n  - type: JSON-LD\n    url: json-ld/cloudguard-context.jsonld\n  - type: Spectral\n    url: rules/cloudguard-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudguard-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudguard/refs/heads/main/apis.yml
tags:
- Check Point
- CNAPP
- Cloud Security
- Compliance
- CSPM
- CWPP
- Posture Management
url: https://raw.githubusercontent.com/api-evangelist/cloudguard/refs/heads/main/apis.yml
use_cases: []
---
