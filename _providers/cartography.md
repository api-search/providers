---
api_count: 11
apis:
- description: Python tool that ingests infrastructure data from 30+ providers into a Neo4j graph for cross-provider security analysis.
  name: Cartography
  slug: cartography
- description: Cartography intel module that calls AWS APIs (EC2, IAM, S3, RDS, EKS, Lambda, ECS, DynamoDB, CloudWatch, ACM, KMS, CodeBuild, API Gateway, Bedrock, and more) to populate AWS nodes and relationships in
  name: Cartography AWS Intel Module
  slug: aws-ingest
- description: Cartography intel module that calls Google Cloud APIs (Compute, IAM, Cloud SQL, GKE, Cloud Functions, Artifact Registry, Vertex AI) to populate GCP nodes and relationships in the graph.
  name: Cartography Google Cloud Intel Module
  slug: gcp-ingest
- description: Cartography intel module that calls Azure APIs (App Service, AKS, CosmosDB, Container Instance, Key Vault, Storage, Virtual Machines) to populate Azure nodes and relationships in the graph.
  name: Cartography Azure Intel Module
  slug: azure-ingest
- description: Cartography intel module that calls Oracle Cloud Infrastructure APIs (starting with IAM) to populate OCI nodes and relationships.
  name: Cartography Oracle Cloud Intel Module
  slug: oci-ingest
- description: Ingests Okta users, groups, applications, and factors into the graph for identity-focused security analysis.
  name: Cartography Okta Intel Module
  slug: okta-ingest
- description: Ingests Microsoft Entra ID users, groups, applications, and role assignments into the graph.
  name: Cartography Entra ID Intel Module
  slug: entra-id-ingest
- description: Ingests GitHub organizations, repositories, users, and access relationships, enabling code-ownership and secret-exposure graph queries.
  name: Cartography GitHub Intel Module
  slug: github-ingest
- description: Ingests Kubernetes cluster objects (nodes, pods, services, service accounts) for graph-based cluster-security analysis.
  name: Cartography Kubernetes Intel Module
  slug: kubernetes-ingest
- description: Ingests CrowdStrike Falcon hosts and detections, connecting endpoint telemetry to the infrastructure graph.
  name: Cartography CrowdStrike Intel Module
  slug: crowdstrike-ingest
- description: Ingests Cloudflare zones, DNS, and security configurations into the graph for edge-exposure analysis.
  name: Cartography Cloudflare Intel Module
  slug: cloudflare-ingest
common:
- title: ''
  type: Website
  url: https://lyft.github.io/cartography/
- title: ''
  type: Documentation
  url: https://lyft.github.io/cartography/
- title: ''
  type: GitHubOrg
  url: https://github.com/lyft
- title: ''
  type: Repository
  url: https://github.com/lyft/cartography
- title: ''
  type: Issues
  url: https://github.com/lyft/cartography/issues
- title: ''
  type: GettingStarted
  url: https://lyft.github.io/cartography/install.html
- title: ''
  type: Tutorial
  url: https://lyft.github.io/cartography/usage/tutorial.html
- title: ''
  type: License
  url: https://github.com/lyft/cartography/blob/master/LICENSE
- title: ''
  type: Releases
  url: https://github.com/lyft/cartography/releases
- title: ''
  type: Community
  url: https://eng.lyft.com/open-sourcing-cartography-4611ba31a72
created: '2025-01-01'
description: Cartography is an open-source Python security-graph tool originally built at Lyft that consolidates infrastructure assets and the relationships between them into an intuitive Neo4j graph. It ingests data from 30+ cloud, identity, DevOps, and security providers (AWS, GCP, Azure, OCI, Okta, Entra ID, GitHub, Kubernetes, CrowdStrike, and more) and lets security teams answer cross-provider questions such as "which identities can reach which datastores," "which compute instances are exposed to the internet," and "what are the blast radii of a compromised credential."
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cartography Context
  property_count: 9
  slug: cartography-context
layout: provider
modified: '2026-04-23'
name: Cartography
skills: []
slug: cartography
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cartography\nname: Cartography\ndescription: >-\n  Cartography is an open-source Python security-graph tool originally built\n  at Lyft that consolidates infrastructure assets and the relationships\n  between them into an intuitive Neo4j graph. It ingests data from 30+\n  cloud, identity, DevOps, and security providers (AWS, GCP, Azure, OCI,\n  Okta, Entra ID, GitHub, Kubernetes, CrowdStrike, and more) and lets\n  security teams answer cross-provider questions such as \"which identities\n  can reach which datastores,\" \"which compute instances are exposed to the\n  internet,\" and \"what are the blast radii of a compromised credential.\"\ntype: Standard\nposition: Consumer\naccess: Open\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Security\n  - Cloud Security\n  - Graph\n  - CSPM\n  - Neo4j\n  - Open Source\n  - Lyft\n  - Asset Inventory\n  - Identity\ncreated: '2025-01-01'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cartography/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: cartography:cartography\n    name: Cartography\n    description: >-\n      Python tool that ingests infrastructure data from 30+ providers into a\n      Neo4j graph for cross-provider security analysis.\n    humanURL: https://lyft.github.io/cartography/\n    tags:\n      - Security\n      - Cloud Security\n      - Graph\n      - Neo4j\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/\n      - type: Repository\n        url: https://github.com/lyft/cartography\n      - type: QueryLanguage\n        name: Cypher (Neo4j)\n        url: https://neo4j.com/docs/cypher-manual/current/\n  - aid: cartography:aws-ingest\n    name: Cartography AWS Intel Module\n    description: >-\n      Cartography intel module that calls AWS APIs (EC2, IAM, S3, RDS, EKS,\n      Lambda, ECS, DynamoDB, CloudWatch, ACM, KMS, CodeBuild, API Gateway,\n      Bedrock, and more) to populate AWS nodes and relationships in the graph.\n\
  \    humanURL: https://lyft.github.io/cartography/modules/aws/index.html\n    tags:\n      - AWS\n      - Cloud\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/aws/index.html\n  - aid: cartography:gcp-ingest\n    name: Cartography Google Cloud Intel Module\n    description: >-\n      Cartography intel module that calls Google Cloud APIs (Compute, IAM,\n      Cloud SQL, GKE, Cloud Functions, Artifact Registry, Vertex AI) to\n      populate GCP nodes and relationships in the graph.\n    humanURL: https://lyft.github.io/cartography/modules/gcp/index.html\n    tags:\n      - GCP\n      - Cloud\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/gcp/index.html\n  - aid: cartography:azure-ingest\n    name: Cartography Azure Intel Module\n    description: >-\n      Cartography intel module that calls Azure APIs (App Service, AKS,\n      CosmosDB, Container\
  \ Instance, Key Vault, Storage, Virtual Machines) to\n      populate Azure nodes and relationships in the graph.\n    humanURL: https://lyft.github.io/cartography/modules/azure/index.html\n    tags:\n      - Azure\n      - Cloud\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/azure/index.html\n  - aid: cartography:oci-ingest\n    name: Cartography Oracle Cloud Intel Module\n    description: >-\n      Cartography intel module that calls Oracle Cloud Infrastructure APIs\n      (starting with IAM) to populate OCI nodes and relationships.\n    humanURL: https://lyft.github.io/cartography/modules/oci/index.html\n    tags:\n      - OCI\n      - Cloud\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/oci/index.html\n  - aid: cartography:okta-ingest\n    name: Cartography Okta Intel Module\n    description: >-\n      Ingests Okta users, groups, applications,\
  \ and factors into the graph\n      for identity-focused security analysis.\n    humanURL: https://lyft.github.io/cartography/modules/okta/index.html\n    tags:\n      - Identity\n      - Okta\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/okta/index.html\n  - aid: cartography:entra-id-ingest\n    name: Cartography Entra ID Intel Module\n    description: >-\n      Ingests Microsoft Entra ID users, groups, applications, and role\n      assignments into the graph.\n    humanURL: https://lyft.github.io/cartography/modules/entra/index.html\n    tags:\n      - Identity\n      - Entra ID\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/entra/index.html\n  - aid: cartography:github-ingest\n    name: Cartography GitHub Intel Module\n    description: >-\n      Ingests GitHub organizations, repositories, users, and access\n      relationships, enabling code-ownership\
  \ and secret-exposure graph\n      queries.\n    humanURL: https://lyft.github.io/cartography/modules/github/index.html\n    tags:\n      - GitHub\n      - SCM\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/github/index.html\n  - aid: cartography:kubernetes-ingest\n    name: Cartography Kubernetes Intel Module\n    description: >-\n      Ingests Kubernetes cluster objects (nodes, pods, services, service\n      accounts) for graph-based cluster-security analysis.\n    humanURL: https://lyft.github.io/cartography/modules/kubernetes/index.html\n    tags:\n      - Kubernetes\n      - Containers\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/kubernetes/index.html\n  - aid: cartography:crowdstrike-ingest\n    name: Cartography CrowdStrike Intel Module\n    description: >-\n      Ingests CrowdStrike Falcon hosts and detections, connecting endpoint\n \
  \     telemetry to the infrastructure graph.\n    humanURL: https://lyft.github.io/cartography/modules/crowdstrike/index.html\n    tags:\n      - EDR\n      - CrowdStrike\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/crowdstrike/index.html\n  - aid: cartography:cloudflare-ingest\n    name: Cartography Cloudflare Intel Module\n    description: >-\n      Ingests Cloudflare zones, DNS, and security configurations into the\n      graph for edge-exposure analysis.\n    humanURL: https://lyft.github.io/cartography/modules/cloudflare/index.html\n    tags:\n      - DNS\n      - Edge\n      - Ingest\n    properties:\n      - type: Documentation\n        url: https://lyft.github.io/cartography/modules/cloudflare/index.html\ncommon:\n  - type: Website\n    url: https://lyft.github.io/cartography/\n  - type: Documentation\n    url: https://lyft.github.io/cartography/\n  - type: GitHubOrg\n    name: Lyft GitHub\n    url: https://github.com/lyft\n\
  \  - type: Repository\n    url: https://github.com/lyft/cartography\n  - type: Issues\n    url: https://github.com/lyft/cartography/issues\n  - type: GettingStarted\n    url: https://lyft.github.io/cartography/install.html\n  - type: Tutorial\n    url: https://lyft.github.io/cartography/usage/tutorial.html\n  - type: License\n    name: Apache 2.0\n    url: https://github.com/lyft/cartography/blob/master/LICENSE\n  - type: Releases\n    url: https://github.com/lyft/cartography/releases\n  - type: Community\n    name: Lyft Engineering Blog\n    url: https://eng.lyft.com/open-sourcing-cartography-4611ba31a72\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cartography/refs/heads/main/apis.yml
tags:
- Security
- Cloud Security
- Graph
- CSPM
- Neo4j
- Open Source
- Lyft
- Asset Inventory
- Identity
url: https://raw.githubusercontent.com/api-evangelist/cartography/refs/heads/main/apis.yml
use_cases: []
---
