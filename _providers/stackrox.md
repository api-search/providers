---
api_count: 1
api_specs:
- filename: stackrox-openapi.yml
  format: yaml
  label: StackRox API
  slug: stackrox-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/openapi/stackrox-openapi.yml
apis:
- description: The StackRox REST API provides programmatic access to the StackRox Kubernetes Security Platform. Covers alerts, deployments, images, policies, compliance, clusters, network policies, roles, API tokens
  name: StackRox API
  slug: stackrox-api
capabilities:
- description: Unified workflow capability for Kubernetes security operations using StackRox. Combines alert triage, policy management, deployment risk analysis, container image vulnerability scanning, compliance ch
  name: StackRox Kubernetes Security
  slug: kubernetes-security
common:
- title: ''
  type: Website
  url: https://www.stackrox.io/
- title: ''
  type: Documentation
  url: https://www.stackrox.io/docs/
- title: ''
  type: Blog
  url: https://www.stackrox.io/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/stackrox
- title: ''
  type: GitHubRepository
  url: https://github.com/stackrox/stackrox
- title: ''
  type: RedHatProduct
  url: https://www.redhat.com/en/technologies/cloud-computing/openshift/advanced-cluster-security-kubernetes
- title: ''
  type: CommunitySlack
  url: https://cloud-native.slack.com/
created: '2026-03-26'
description: StackRox is the open source upstream project for Red Hat Advanced Cluster Security for Kubernetes. It provides risk analysis, visibility, runtime alerts, and recommendations to proactively improve security by hardening containerized environments across build, deploy, and runtime stages. The platform performs compliance checking against standards like CIS, NIST, and PCI-DSS, and manages security policies across Kubernetes clusters.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Stackrox Context
  property_count: 5
  slug: stackrox-context
layout: provider
modified: '2026-05-02'
name: StackRox
rules:
- name: StackRox API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 1
  slug: stackrox-rules
skills: []
slug: stackrox
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stackrox\nname: StackRox\ndescription: >-\n  StackRox is the open source upstream project for Red Hat Advanced Cluster\n  Security for Kubernetes. It provides risk analysis, visibility, runtime\n  alerts, and recommendations to proactively improve security by hardening\n  containerized environments across build, deploy, and runtime stages.\n  The platform performs compliance checking against standards like CIS, NIST,\n  and PCI-DSS, and manages security policies across Kubernetes clusters.\nurl: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Compliance\n  - Container Security\n  - Kubernetes\n  - Open Source\n  - Runtime Protection\n  - Security\ntype: Index\naccess: 3rd-Party\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stackrox:stackrox-api\n    name: StackRox API\n    description: >-\n    \
  \  The StackRox REST API provides programmatic access to the StackRox\n      Kubernetes Security Platform. Covers alerts, deployments, images,\n      policies, compliance, clusters, network policies, roles, API tokens,\n      vulnerability management, and system configuration.\n    humanURL: https://www.stackrox.io/docs/\n    tags:\n      - Compliance\n      - Container Security\n      - Kubernetes\n      - Runtime Protection\n      - Security\n    properties:\n      - type: Documentation\n        url: https://www.stackrox.io/docs/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/openapi/stackrox-openapi.yml\n      - type: GitHub\n        url: https://github.com/stackrox/stackrox\ncommon:\n  - type: Website\n    url: https://www.stackrox.io/\n    name: StackRox Community\n  - type: Documentation\n    url: https://www.stackrox.io/docs/\n    name: StackRox Documentation\n  - type: Blog\n    url: https://www.stackrox.io/blog/\n\
  \    name: StackRox Blog\n  - type: GitHubOrganization\n    url: https://github.com/stackrox\n    name: StackRox GitHub Organization\n  - type: GitHubRepository\n    url: https://github.com/stackrox/stackrox\n    name: StackRox Main Repository\n  - type: RedHatProduct\n    url: https://www.redhat.com/en/technologies/cloud-computing/openshift/advanced-cluster-security-kubernetes\n    name: Red Hat Advanced Cluster Security\n  - type: CommunitySlack\n    url: https://cloud-native.slack.com/\n    name: Cloud Native Slack #stackrox\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/apis.yml
tags:
- Compliance
- Container Security
- Kubernetes
- Open Source
- Runtime Protection
- Security
url: https://raw.githubusercontent.com/api-evangelist/stackrox/refs/heads/main/apis.yml
use_cases: []
---
