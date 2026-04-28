---
api_count: 5
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
