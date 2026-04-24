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
