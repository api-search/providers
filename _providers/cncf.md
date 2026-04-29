---
api_count: 2
apis:
- description: The CNCF Cloud Native Interactive Landscape is the canonical map of the cloud-native ecosystem. The landscape is generated daily from landscape.yml and enriched with data from Crunchbase and GitHub. T
  name: CNCF Cloud Native Interactive Landscape
  slug: cncf-landscape
- description: CNCF stewards an open-source project portfolio whose APIs underpin much of modern cloud infrastructure - Kubernetes API, OpenTelemetry, CloudEvents, gRPC, CNI, CSI, OCI image and runtime specs, Promet
  name: CNCF Hosted Projects (Standards Steward)
  slug: cncf-projects
common:
- title: ''
  type: Website
  url: https://www.cncf.io/
- title: ''
  type: Landscape
  url: https://landscape.cncf.io/
- title: ''
  type: Catalog
  url: https://www.cncf.io/projects/
- title: ''
  type: Blog
  url: https://www.cncf.io/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cncf
- title: ''
  type: About
  url: https://www.cncf.io/all-cncf/
- title: ''
  type: PrivacyPolicy
  url: https://www.linuxfoundation.org/privacy/
- title: ''
  type: X
  url: https://twitter.com/CloudNativeFdn
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cloud-native-computing-foundation/
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/cloudnativefdn
created: '2025-01-01'
description: The Cloud Native Computing Foundation (CNCF) is part of the Linux Foundation and hosts critical components of the global cloud-native technology infrastructure - including Kubernetes, Prometheus, Envoy, etcd, OpenTelemetry, CloudEvents, gRPC, and CNI. CNCF stewards open-source project governance and publishes the Cloud Native Interactive Landscape, a community-curated dataset (landscape.yml) of cloud-native projects and products with metadata such as GitHub stars, contributor counts, funding, and headquarters location.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CNCF
skills: []
slug: cncf
solutions: []
source_filename: apis.yml
source_yaml: "aid: cncf\nurl: https://raw.githubusercontent.com/api-evangelist/cncf/refs/heads/main/apis.yml\nname: CNCF\nx-type: opensource\ntags:\n  - Cloud Native\n  - Containers\n  - Kubernetes\n  - Open Source\n  - Standards\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ndescription: >-\n  The Cloud Native Computing Foundation (CNCF) is part of the Linux Foundation\n  and hosts critical components of the global cloud-native technology\n  infrastructure - including Kubernetes, Prometheus, Envoy, etcd, OpenTelemetry,\n  CloudEvents, gRPC, and CNI. CNCF stewards open-source project governance and\n  publishes the Cloud Native Interactive Landscape, a community-curated dataset\n  (landscape.yml) of cloud-native projects and products with metadata such as\n  GitHub stars, contributor counts, funding, and headquarters location.\napis:\n  - aid:\
  \ cncf:cncf-landscape\n    name: CNCF Cloud Native Interactive Landscape\n    tags:\n      - Catalog\n      - Cloud Native\n      - Landscape\n      - Open Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://landscape.cncf.io/\n    properties:\n      - url: https://landscape.cncf.io/\n        type: Documentation\n      - url: https://github.com/cncf/landscape\n        type: GitHubRepository\n      - url: https://github.com/cncf/landscape/blob/master/landscape.yml\n        type: Dataset\n      - url: https://github.com/cncf/landscape2\n        type: GitHubRepository\n    description: >-\n      The CNCF Cloud Native Interactive Landscape is the canonical map of the\n      cloud-native ecosystem. The landscape is generated daily from\n      landscape.yml and enriched with data from Crunchbase and GitHub. The\n      underlying dataset (project name, category, maturity, GitHub repo,\n      Crunchbase entry, headquarters, etc.) is\
  \ published as YAML in the cncf/landscape\n      repo and rendered with the cncf/landscape2 generator, providing a\n      structured, machine-readable catalog of hundreds of cloud-native projects\n      and products.\n    x-features:\n      - name: Project Catalog\n        description: Hundreds of cloud-native projects and products with structured metadata.\n      - name: Maturity Levels\n        description: Graduated, Incubating, Sandbox, and Archived classifications.\n      - name: GitHub Metrics\n        description: GitHub stars, contributors, and commit activity per project.\n      - name: Categories and Subcategories\n        description: Provisioning, Runtime, Orchestration, App Definition, Observability, etc.\n    x-useCases:\n      - name: Tool Discovery\n        description: Help engineers find cloud-native tools that match their requirements.\n      - name: Landscape Analysis\n        description: Track ecosystem growth, project maturity, and adoption signals.\n      - name:\
  \ Procurement and Vendor Selection\n        description: Evaluate CNCF projects and vendors when standardizing tooling.\n  - aid: cncf:cncf-projects\n    name: CNCF Hosted Projects (Standards Steward)\n    tags:\n      - Kubernetes\n      - Open Source\n      - Standards\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cncf.io/projects/\n    properties:\n      - url: https://www.cncf.io/projects/\n        type: Documentation\n      - url: https://github.com/cncf\n        type: GitHubOrganization\n    description: >-\n      CNCF stewards an open-source project portfolio whose APIs underpin much of\n      modern cloud infrastructure - Kubernetes API, OpenTelemetry, CloudEvents,\n      gRPC, CNI, CSI, OCI image and runtime specs, Prometheus exposition format,\n      etcd, Envoy xDS, and many more. Each project owns its own API specs and\n      contracts; CNCF provides the governance and home for these\n      cloud-native standards.\n\
  \    x-features:\n      - name: Open Governance\n        description: Open governance for hosted cloud-native projects.\n      - name: Maturity Track\n        description: Sandbox to Incubating to Graduated maturity track.\n      - name: Standards Stewardship\n        description: Stewardship of foundational cloud-native API standards.\ncommon:\n  - url: https://www.cncf.io/\n    type: Website\n  - url: https://landscape.cncf.io/\n    name: CNCF Cloud Native Landscape\n    type: Landscape\n  - url: https://www.cncf.io/projects/\n    name: Graduated and Incubating Projects\n    type: Catalog\n  - url: https://www.cncf.io/blog/\n    name: CNCF Blog\n    type: Blog\n  - url: https://github.com/cncf\n    name: CNCF on GitHub\n    type: GitHubOrganization\n  - url: https://www.cncf.io/all-cncf/\n    name: All CNCF Sites\n    type: About\n  - url: https://www.linuxfoundation.org/privacy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://twitter.com/CloudNativeFdn\n    name:\
  \ CNCF on X\n    type: X\n  - url: https://www.linkedin.com/company/cloud-native-computing-foundation/\n    name: CNCF on LinkedIn\n    type: LinkedIn\n  - url: https://www.youtube.com/c/cloudnativefdn\n    name: CNCF on YouTube\n    type: YouTube\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cncf/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- Kubernetes
- Open Source
- Standards
url: https://raw.githubusercontent.com/api-evangelist/cncf/refs/heads/main/apis.yml
use_cases: []
---
