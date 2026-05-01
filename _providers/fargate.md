---
api_count: 2
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon ECS API (Fargate)
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/ecs/2014-11-13/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Amazon EKS API (Fargate)
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/eks/2017-11-01/openapi.yaml
apis:
- description: The Amazon ECS API provides programmatic access to manage Fargate tasks and services through Amazon Elastic Container Service. It supports creating and managing clusters, task definitions, services, a
  name: Amazon ECS API (Fargate)
  slug: ''
- description: The Amazon EKS API provides programmatic access to manage Fargate pods through Amazon Elastic Kubernetes Service. It supports creating Fargate profiles that define which Kubernetes pods run on Fargate
  name: Amazon EKS API (Fargate)
  slug: ''
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/fargate/
- title: ''
  type: Documentation
  url: https://aws.amazon.com/documentation-overview/fargate/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/fargate/pricing/
- title: ''
  type: Getting Started
  url: https://aws.amazon.com/fargate/getting-started/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/fargate/faqs/
- title: ''
  type: Customers
  url: https://aws.amazon.com/fargate/customers/
- title: ''
  type: Partners
  url: https://aws.amazon.com/fargate/partners/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ecs/
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html
- title: ''
  type: SDKs
  url: https://aws.amazon.com/tools/
- title: ''
  type: CLI
  url: https://aws.amazon.com/cli/
- title: ''
  type: Status
  url: https://status.aws.amazon.com/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/compute/aws-fargate/
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: SLA
  url: https://aws.amazon.com/ecs/sla/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Knowledge Center
  url: https://repost.aws/tags/TAd-wgX2x3QgSxyelEN6raFg/amazon-elastic-container-service
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-fargate.html
- title: ''
  type: Security Whitepaper
  url: https://d1.awsstatic.com/whitepapers/AWS_Fargate_Security_Overview_Whitepaper.pdf
- title: ''
  type: GitHub Organization
  url: https://github.com/aws-containers
- title: ''
  type: GitHub Repository
  url: https://github.com/aws/containers-roadmap
- title: ''
  type: Change Log
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-versions-changelog.html
- title: ''
  type: Service Quotas
  url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html
created: '2024-01-01'
description: AWS Fargate is a serverless, pay-as-you-go compute engine for containers that works with Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). It removes the need to provision and manage servers, letting you focus on building and running applications without managing infrastructure.
features: []
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
layout: provider
modified: '2026-04-28'
name: AWS Fargate
skills: []
slug: fargate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fargate\nname: AWS Fargate\ndescription: >-\n  AWS Fargate is a serverless, pay-as-you-go compute engine for containers that\n  works with Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes\n  Service (EKS). It removes the need to provision and manage servers, letting you\n  focus on building and running applications without managing infrastructure.\nurl: https://aws.amazon.com/fargate/\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Compute\n  - Containers\n  - Docker\n  - Kubernetes\n  - Serverless\napis:\n  - name: Amazon ECS API (Fargate)\n    description: >-\n      The Amazon ECS API provides programmatic access to manage Fargate tasks and\n      services through Amazon Elastic Container Service. It supports creating and\n      managing clusters, task definitions, services, and container instances using\n      the Fargate launch\
  \ type for serverless container execution.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    baseURL: https://ecs.{region}.amazonaws.com\n    humanURL: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/ecs/2014-11-13/openapi.yaml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/fargate/refs/heads/main/openapi/fargate-ecs-openapi.yml\n      - type: API Reference\n        url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/Welcome.html\n      - type: API Operations\n        url: https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_Operations.html\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started-fargate.html\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/fargate/pricing/\n      - type: Developer Guide\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html\n      - type: CLI Reference\n        url: https://docs.aws.amazon.com/cli/latest/reference/ecs/\n      - type: SDKs\n        url: https://aws.amazon.com/tools/\n      - type: Platform Versions\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-fargate.html\n      - type: Change Log\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-versions-changelog.html\n      - type: Service Quotas\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html\n      - type: Security\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-fargate.html\n      - type: Monitoring\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/monitoring-fargate-usage.html\n      -\
  \ type: Container Insights\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cloudwatch-container-insights.html\n      - type: Troubleshooting\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/troubleshooting.html\n      - type: Best Practices\n        url: https://docs.aws.amazon.com/AmazonECS/latest/bestpracticesguide/intro.html\n      - type: Windows Containers\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/windows-considerations.html\n      - type: ECS Exec\n        url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-exec.html\n    tags:\n      - Containers\n      - ECS\n      - Fargate\n      - Orchestration\n      - Serverless\n  - name: Amazon EKS API (Fargate)\n    description: >-\n      The Amazon EKS API provides programmatic access to manage Fargate pods through\n      Amazon Elastic Kubernetes Service. It supports creating Fargate profiles that\n      define which Kubernetes pods run\
  \ on Fargate infrastructure, enabling serverless\n      Kubernetes workloads without managing nodes.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    baseURL: https://eks.{region}.amazonaws.com\n    humanURL: https://docs.aws.amazon.com/eks/latest/APIReference/\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/eks/latest/userguide/fargate.html\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/eks/2017-11-01/openapi.yaml\n      - type: API Reference\n        url: https://docs.aws.amazon.com/eks/latest/APIReference/Welcome.html\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/eks/latest/userguide/fargate-getting-started.html\n      - type: Pricing\n        url: https://aws.amazon.com/fargate/pricing/\n      - type: Fargate Profiles\n        url: https://docs.aws.amazon.com/eks/latest/userguide/fargate-profile.html\n      - type: Pod Configuration\n   \
  \     url: https://docs.aws.amazon.com/eks/latest/userguide/fargate-pod-configuration.html\n      - type: Pod Execution Role\n        url: https://docs.aws.amazon.com/eks/latest/userguide/pod-execution-role.html\n      - type: CLI Reference\n        url: https://docs.aws.amazon.com/cli/latest/reference/eks/create-fargate-profile.html\n      - type: SDKs\n        url: https://aws.amazon.com/tools/\n    tags:\n      - Containers\n      - EKS\n      - Fargate\n      - Kubernetes\n      - Serverless\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/fargate/\n  - type: Documentation\n    url: https://aws.amazon.com/documentation-overview/fargate/\n  - type: Features\n    url: https://aws.amazon.com/fargate/features/\n  - type: Pricing\n    url: https://aws.amazon.com/fargate/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/fargate/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/fargate/faqs/\n  - type: Customers\n    url: https://aws.amazon.com/fargate/customers/\n\
  \  - type: Partners\n    url: https://aws.amazon.com/fargate/partners/\n  - type: Console\n    url: https://console.aws.amazon.com/ecs/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/general/latest/gr/signature-version-4.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: CLI\n    url: https://aws.amazon.com/cli/\n  - type: Status\n    url: https://status.aws.amazon.com/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/compute/category/compute/aws-fargate/\n  - type: Terms of Service\n    url: https://aws.amazon.com/service-terms/\n  - type: Privacy Policy\n    url: https://aws.amazon.com/privacy/\n  - type: SLA\n    url: https://aws.amazon.com/ecs/sla/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Knowledge Center\n    url: https://repost.aws/tags/TAd-wgX2x3QgSxyelEN6raFg/amazon-elastic-container-service\n  - type: Security\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/security-fargate.html\n\
  \  - type: Security Whitepaper\n    url: https://d1.awsstatic.com/whitepapers/AWS_Fargate_Security_Overview_Whitepaper.pdf\n  - type: GitHub Organization\n    url: https://github.com/aws-containers\n  - type: GitHub Repository\n    url: https://github.com/aws/containers-roadmap\n  - type: Change Log\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/platform-versions-changelog.html\n  - type: Service Quotas\n    url: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fargate/refs/heads/main/apis.yml
tags:
- Compute
- Containers
- Docker
- Kubernetes
- Serverless
url: https://aws.amazon.com/fargate/
use_cases: []
---
