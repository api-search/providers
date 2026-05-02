---
api_count: 1
api_specs:
- filename: swagger.json
  format: json
  label: Kubernetes API
  slug: kubernetes
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json
apis:
- description: The Kubernetes API lets you query and manipulate the state of objects in Kubernetes. The core of Kubernetes control plane is the API server and the HTTP API that it exposes. Users, the different parts
  name: Kubernetes API
  slug: kubernetes
asyncapis:
- description: The Kubernetes Watch API provides a streaming event interface for receiving real-time notifications about changes to cluster resources. Clients subscribe to resource types and receive a stream of ADDE
  name: Kubernetes Watch Events
  slug: kubernetes-watch-asyncapi
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/kubernetes
- title: ''
  type: GitHubRepository
  url: https://github.com/kubernetes/kubernetes
- title: ''
  type: GitHubRepository
  url: https://github.com/kubernetes/community
- title: ''
  type: GitHubRepository
  url: https://github.com/kubernetes/kube-openapi
- title: ''
  type: Bluesky
  url: https://bsky.app/profile/kubernetes.io
- title: ''
  type: X
  url: https://x.com/kubernetesio
- title: ''
  type: Website
  url: https://kubernetes.io/
- title: ''
  type: Documentation
  url: https://kubernetes.io/docs/home/
- title: ''
  type: APIReference
  url: https://kubernetes.io/docs/reference/kubernetes-api/
- title: ''
  type: Blog
  url: https://kubernetes.io/blog/
- title: ''
  type: Training
  url: https://kubernetes.io/training/
- title: ''
  type: Partners
  url: https://kubernetes.io/partners/
- title: ''
  type: ChangeLog
  url: https://kubernetes.io/releases/
- title: ''
  type: Community
  url: https://kubernetes.io/community/
- title: ''
  type: Forum
  url: https://discuss.kubernetes.io/
- title: ''
  type: Slack
  url: https://kubernetes.slack.com
- title: ''
  type: Signup
  url: https://slack.k8s.io
- title: ''
  type: YouTube
  url: https://www.youtube.com/@KubernetesCommunity
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/kubernetes
- title: ''
  type: License
  url: https://github.com/kubernetes/kubernetes/blob/master/LICENSE
- title: ''
  type: Security
  url: https://kubernetes.io/docs/concepts/security/
- title: ''
  type: SecurityPolicy
  url: https://github.com/kubernetes/kubernetes/security/policy
- title: ''
  type: Foundation
  url: https://www.cncf.io/projects/kubernetes/
- title: ''
  type: Newsletter
  url: https://www.cncf.io/kubeweekly/
- title: ''
  type: GettingStarted
  url: https://kubernetes.io/docs/setup/
- title: ''
  type: Tutorials
  url: https://kubernetes.io/docs/tutorials/
- title: ''
  type: CaseStudies
  url: https://kubernetes.io/case-studies/
- title: ''
  type: CodeOfConduct
  url: https://kubernetes.io/community/code-of-conduct/
- title: ''
  type: DeprecationPolicy
  url: https://kubernetes.io/docs/reference/using-api/deprecation-policy/
- title: ''
  type: JSONSchema
  url: json-schema/kubernetes-resource-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/kubernetes-context.jsonld
created: '2025-06-05'
description: Kubernetes, also known as K8s, is an open source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery. Kubernetes builds upon 15 years of experience of running production workloads at Google, combined with best-of-breed ideas and practices from the community.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kubernetes Context
  property_count: 36
  slug: kubernetes-context
layout: provider
modified: '2026-04-28'
name: Kubernetes
skills: []
slug: kubernetes
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubernetes\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/apis.yml\napis:\n  - aid: kubernetes:kubernetes\n    name: Kubernetes API\n    tags:\n      - Automation\n      - Cloud Native\n      - CNCF\n      - Containers\n      - Deployment\n      - Orchestration\n      - Scaling\n    humanURL: https://kubernetes.io/docs/concepts/overview/kubernetes-api/\n    baseURL: https://kubernetes.default.svc\n    properties:\n      - url: https://kubernetes.io/docs/concepts/overview/kubernetes-api/\n        type: Documentation\n      - url: https://kubernetes.io/docs/reference/kubernetes-api/\n        type: APIReference\n      - url: >-\n          https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json\n        type: OpenAPI\n      - url: https://github.com/kubernetes/kubernetes/tree/master/api/openapi-spec\n        type: OpenAPIRepository\n      - url: https://kubernetes.io/docs/reference/access-authn-authz/\n\
  \        type: Authentication\n      - url: https://kubernetes.io/docs/reference/using-api/client-libraries/\n        type: Client Libraries\n      - url: https://kubernetes.io/docs/reference/using-api/deprecation-guide/\n        type: Migration Guide\n      - type: OpenAPI\n        url: openapi/kubernetes-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/kubernetes-watch-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/kubernetes-resource-schema.json\n    description: >-\n      The Kubernetes API lets you query and manipulate the state of objects in\n      Kubernetes. The core of Kubernetes control plane is the API server and the\n      HTTP API that it exposes. Users, the different parts of your cluster, and\n      external components all communicate with one another through the API\n      server.\nname: Kubernetes\ntags:\n  - Automation\n  - Cloud Native\n  - CNCF\n  - Containers\n  - Deployment\n  - Open Source\n  - Orchestration\n  - Scaling\ntype: Contract\n\
  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://github.com/kubernetes\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://github.com/kubernetes/kubernetes\n    name: GitHub Repository\n    type: GitHubRepository\n  - url: https://github.com/kubernetes/community\n    name: Community Repository\n    type: GitHubRepository\n  - url: https://github.com/kubernetes/kube-openapi\n    name: OpenAPI Generation Repository\n    type: GitHubRepository\n  - url: https://bsky.app/profile/kubernetes.io\n    name: Bluesky\n    type: Bluesky\n  - url: https://x.com/kubernetesio\n    name: X (Twitter)\n    type: X\n  - url: https://kubernetes.io/\n    name: Website\n    type: Website\n    description: >-\n      Official Kubernetes website with documentation, tutorials, and community\n      resources.\n  - url: https://kubernetes.io/docs/home/\n    name: Documentation\n    type: Documentation\n    description:\
  \ >-\n      Comprehensive documentation covering Kubernetes concepts, tasks,\n      tutorials, and reference information.\n  - url: https://kubernetes.io/docs/reference/kubernetes-api/\n    name: API Reference\n    type: APIReference\n    description: >-\n      Complete reference documentation for the Kubernetes API including all\n      resource types and operations.\n  - url: https://kubernetes.io/blog/\n    name: Blog\n    type: Blog\n    description: >-\n      Official Kubernetes blog featuring release announcements, community\n      updates, and technical articles.\n  - url: https://kubernetes.io/training/\n    name: Training\n    type: Training\n    description: >-\n      Training resources and certification programs for Kubernetes including\n      CKA, CKAD, and CKS.\n  - url: https://kubernetes.io/partners/\n    name: Partners\n    type: Partners\n    description: >-\n      Directory of Kubernetes partners including cloud providers, vendors, and\n      service providers.\n  - url:\
  \ https://kubernetes.io/releases/\n    name: Releases\n    type: ChangeLog\n    description: >-\n      Kubernetes release information including version history, release notes,\n      and support timeline.\n  - url: https://kubernetes.io/community/\n    name: Community\n    type: Community\n    description: >-\n      Information about the Kubernetes community including how to get involved\n      and communication channels.\n  - url: https://discuss.kubernetes.io/\n    name: Discussion Forum\n    type: Forum\n    description: >-\n      Official Kubernetes community forum for discussions, announcements, and\n      user support.\n  - url: https://kubernetes.slack.com\n    name: Slack\n    type: Slack\n    description: >-\n      Kubernetes Slack workspace with 170+ channels for real-time community\n      communication.\n  - url: https://slack.k8s.io\n    name: Slack Signup\n    type: Signup\n    description: Invitation link to join the Kubernetes Slack workspace.\n  - url: https://www.youtube.com/@KubernetesCommunity\n\
  \    name: YouTube\n    type: YouTube\n    description: >-\n      Official Kubernetes Community YouTube channel with SIG meetings,\n      tutorials, and conference talks.\n  - url: https://stackoverflow.com/questions/tagged/kubernetes\n    name: Stack Overflow\n    type: StackOverflow\n    description: Kubernetes-related questions and answers on Stack Overflow.\n  - url: https://github.com/kubernetes/kubernetes/blob/master/LICENSE\n    name: License\n    type: License\n    description: Kubernetes is licensed under the Apache License 2.0.\n  - url: https://kubernetes.io/docs/concepts/security/\n    name: Security\n    type: Security\n    description: >-\n      Kubernetes security concepts including pod security, network policies, and\n      RBAC.\n  - url: https://github.com/kubernetes/kubernetes/security/policy\n    name: Security Policy\n    type: SecurityPolicy\n    description: Information about reporting security vulnerabilities in Kubernetes.\n  - url: https://www.cncf.io/projects/kubernetes/\n\
  \    name: CNCF Project Page\n    type: Foundation\n    description: >-\n      Kubernetes graduated project page on the Cloud Native Computing Foundation\n      website.\n  - url: https://www.cncf.io/kubeweekly/\n    name: KubeWeekly Newsletter\n    type: Newsletter\n    description: >-\n      Weekly curated newsletter with Kubernetes news, articles, and community\n      updates.\n  - url: https://kubernetes.io/docs/setup/\n    name: Getting Started\n    type: GettingStarted\n    description: Documentation for setting up and configuring Kubernetes clusters.\n  - url: https://kubernetes.io/docs/tutorials/\n    name: Tutorials\n    type: Tutorials\n    description: Hands-on tutorials covering various Kubernetes topics and use cases.\n  - url: https://kubernetes.io/case-studies/\n    name: Case Studies\n    type: CaseStudies\n    description: Real-world case studies of organizations using Kubernetes in production.\n  - url: https://kubernetes.io/community/code-of-conduct/\n    name: Code\
  \ of Conduct\n    type: CodeOfConduct\n    description: >-\n      Kubernetes community code of conduct based on the CNCF Code of Conduct,\n      governing participation in Kubernetes project spaces.\n  - url: https://kubernetes.io/docs/reference/using-api/deprecation-policy/\n    name: Deprecation Policy\n    type: DeprecationPolicy\n    description: >-\n      Kubernetes deprecation policy describing the rules for deprecating and\n      removing APIs, features, and flags across versions.\n  - type: JSONSchema\n    url: json-schema/kubernetes-resource-schema.json\n  - type: JSON-LD\n    url: json-ld/kubernetes-context.jsonld\ncreated: '2025-06-05'\nmodified: '2026-04-28'\nposition: Consuming\ndescription: >-\n  Kubernetes, also known as K8s, is an open source system for automating deployment,\n  scaling, and management of containerized applications. It groups containers that\n  make up an application into logical units for easy management and discovery. Kubernetes\n  builds upon 15 years\
  \ of experience of running production workloads at Google, combined\n  with best-of-breed ideas and practices from the community.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/apis.yml
tags:
- Automation
- Cloud Native
- CNCF
- Containers
- Deployment
- Open Source
- Orchestration
- Scaling
url: https://raw.githubusercontent.com/api-evangelist/kubernetes/refs/heads/main/apis.yml
use_cases: []
---
