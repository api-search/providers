---
api_count: 2
apis:
- description: Kestrel AI provides an AI-native cloud incident response platform that uses autonomous agents to detect, investigate, and remediate Kubernetes and cloud infrastructure incidents. The platform monitors
  name: Kestrel Platform
  slug: platform
- description: The Kestrel Kubernetes Operator is an open-source Go-based operator that connects Kubernetes clusters to the Kestrel AI platform. It communicates via bidirectional gRPC streaming over mTLS with OAuth2
  name: Kestrel Kubernetes Operator
  slug: kubernetes-operator
common:
- title: ''
  type: Website
  url: https://usekestrel.ai/
- title: ''
  type: Documentation
  url: https://docs.usekestrel.ai/
- title: ''
  type: SignUp
  url: https://platform.usekestrel.ai/register
- title: ''
  type: GitHubOrganization
  url: https://github.com/kestrelai
- title: ''
  type: Integration
  url: https://docs.usekestrel.ai/integrations/slack
- title: ''
  type: Integration
  url: https://docs.usekestrel.ai/integrations/pagerduty
- title: ''
  type: Integration
  url: https://docs.usekestrel.ai/integrations/cicd
- title: ''
  type: Integration
  url: https://docs.usekestrel.ai/cloud/aws
- title: ''
  type: SelfHosted
  url: https://docs.usekestrel.ai/on-premise/setup
- title: ''
  type: Status
  url: https://status.usekestrel.ai/
- title: ''
  type: Changelog
  url: https://usekestrel.ai/changelog
- title: ''
  type: Security
  url: https://trust.delve.co/kestrel-ai
- title: ''
  type: JSON-LD
  url: json-ld/kestrel-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/kestrel-incident-schema.json
created: '2026-03-26'
description: Kestrel AI is a YC-backed startup building an AI-native cloud incident response platform. Founded by former Illumio Kubernetes Security engineers, Kestrel uses autonomous AI agents to detect, investigate, and remediate infrastructure incidents across Kubernetes and cloud environments. The platform provides continuous monitoring, root cause analysis, and automated remediation through GitOps workflows, integrating with Slack, PagerDuty, GitHub, GitLab, AWS, and major observability platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kestrel Context
  property_count: 5
  slug: kestrel-context
layout: provider
modified: '2026-04-28'
name: Kestrel
skills: []
slug: kestrel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kestrel\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/apis.yml\napis:\n  - aid: kestrel:platform\n    name: Kestrel Platform\n    tags:\n      - AI Agents\n      - Cloud Security\n      - Incident Response\n      - Kubernetes\n    humanURL: https://docs.usekestrel.ai/\n    properties:\n      - url: https://docs.usekestrel.ai/\n        type: Documentation\n      - url: https://docs.usekestrel.ai/quickstart\n        type: GettingStarted\n      - url: https://platform.usekestrel.ai/register\n        type: SignUp\n    description: >-\n      Kestrel AI provides an AI-native cloud incident response platform that\n      uses autonomous agents to detect, investigate, and remediate Kubernetes\n      and cloud infrastructure incidents. The platform monitors clusters\n      continuously, identifies root causes, and generates production-ready\n      fixes delivered as pull requests via GitOps workflows. It integrates\n      with major cloud providers,\
  \ observability tools, and CI/CD platforms\n      to provide end-to-end incident management.\n  - aid: kestrel:kubernetes-operator\n    name: Kestrel Kubernetes Operator\n    tags:\n      - gRPC\n      - Helm\n      - Kubernetes\n      - Operators\n    humanURL: https://docs.usekestrel.ai/kubernetes/configuration\n    properties:\n      - url: https://docs.usekestrel.ai/kubernetes/configuration\n        type: Documentation\n      - url: https://github.com/KestrelAI/Kestrel-Operator\n        type: GitHubOrganization\n    description: >-\n      The Kestrel Kubernetes Operator is an open-source Go-based operator\n      that connects Kubernetes clusters to the Kestrel AI platform. It\n      communicates via bidirectional gRPC streaming over mTLS with OAuth2\n      authentication, streaming resource metadata, logs, events, and network\n      telemetry. The operator supports OpenTelemetry OTLP ingestion and\n      Istio Access Log Service integration for comprehensive observability.\n      It\
  \ is deployed via Helm chart from the GitHub Container Registry.\nname: Kestrel\ntags:\n  - AI Agents\n  - Cloud Security\n  - Incident Response\n  - Kubernetes\n  - Observability\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://usekestrel.ai/\n    name: Kestrel Website\n    type: Website\n    description: 'null'\n  - url: https://docs.usekestrel.ai/\n    name: Kestrel Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://platform.usekestrel.ai/register\n    name: Kestrel Sign Up\n    type: SignUp\n    description: 'null'\n  - url: https://github.com/kestrelai\n    name: Kestrel GitHub\n    type: GitHubOrganization\n    description: 'null'\n  - url: https://docs.usekestrel.ai/integrations/slack\n    name: Kestrel Slack Integration\n    type: Integration\n    description: 'null'\n  - url: https://docs.usekestrel.ai/integrations/pagerduty\n    name: Kestrel PagerDuty Integration\n\
  \    type: Integration\n    description: 'null'\n  - url: https://docs.usekestrel.ai/integrations/cicd\n    name: Kestrel CI/CD Integration\n    type: Integration\n    description: 'null'\n  - url: https://docs.usekestrel.ai/cloud/aws\n    name: Kestrel AWS Integration\n    type: Integration\n    description: 'null'\n  - url: https://docs.usekestrel.ai/on-premise/setup\n    name: Kestrel On-Premise Setup\n    type: SelfHosted\n    description: 'null'\n  - url: https://status.usekestrel.ai/\n    name: Kestrel Status\n    type: Status\n    description: 'null'\n  - url: https://usekestrel.ai/changelog\n    name: Kestrel Changelog\n    type: Changelog\n    description: 'null'\n  - url: https://trust.delve.co/kestrel-ai\n    name: Kestrel Trust Center\n    type: Security\n    description: 'null'\n  - url: json-ld/kestrel-context.jsonld\n    type: JSON-LD\n  - url: json-schema/kestrel-incident-schema.json\n    type: JSONSchema\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nposition: Consumer\n\
  segments:\n  - Incident Response\n  - Kubernetes\n  - Cloud Security\ndescription: >-\n  Kestrel AI is a YC-backed startup building an AI-native cloud incident response\n  platform. Founded by former Illumio Kubernetes Security engineers, Kestrel uses\n  autonomous AI agents to detect, investigate, and remediate infrastructure incidents\n  across Kubernetes and cloud environments. The platform provides continuous monitoring,\n  root cause analysis, and automated remediation through GitOps workflows, integrating\n  with Slack, PagerDuty, GitHub, GitLab, AWS, and major observability platforms.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/apis.yml
tags:
- AI Agents
- Cloud Security
- Incident Response
- Kubernetes
- Observability
url: https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/apis.yml
use_cases: []
---
