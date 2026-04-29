---
api_count: 3
apis:
- description: The Buildpack API defines the contract between a buildpack and the lifecycle that executes it. It specifies detect, build, and export phases, layer contribution formats, environment variable handling,
  name: Buildpack API Specification
  slug: buildpack-api
- description: The Platform API defines the contract between a platform (such as pack or kpack) and the CNB lifecycle. It covers builder configuration, build inputs and outputs, stack definitions, and run image mana
  name: Platform API Specification
  slug: platform-api
- description: The Distribution API defines the OCI-based format for packaging and distributing buildpacks and builders via container registries, including the buildpackage format.
  name: Distribution API Specification
  slug: distribution-api
common:
- title: ''
  type: Website
  url: https://buildpacks.io
- title: ''
  type: Documentation
  url: https://buildpacks.io/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/buildpacks
- title: ''
  type: Blog
  url: https://medium.com/buildpacks
- title: ''
  type: Community
  url: https://buildpacks.io/community/
- title: ''
  type: Registry
  url: https://registry.buildpacks.io/
- title: ''
  type: Specification
  url: https://github.com/buildpacks/spec/blob/main/buildpack.md
- title: ''
  type: MailingList
  url: https://lists.cncf.io/g/cncf-buildpacks/join
- title: ''
  type: Slack
  url: https://slack.cncf.io
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/buildpacks/
- title: ''
  type: DevStats
  url: https://buildpacks.devstats.cncf.io/
created: '2025-01-01'
description: Cloud Native Buildpacks (CNBs) transform application source code into OCI-compliant container images that can run on any cloud, without requiring Dockerfiles. Initiated by Pivotal and Heroku in January 2018, CNBs are a CNCF incubating project licensed under Apache-2.0. They centralize container expertise through composable buildpacks, enable layer rebasing for efficient OS updates, and generate Software Bills of Materials (SBOM). The pack CLI and kpack platform operator are primary integration points.
features:
- features:
  - Source-to-Image Conversion
  - Builder Selection
  - Environment Variable Injection
  - Volume Mount Support
  - Cache Integration
  name: pack build
  url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/
- features:
  - Create Custom Builders
  - Inspect Builder Contents
  - Trust Builder Configuration
  - Suggest Default Builders
  name: pack builder
  url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/
- features:
  - Update Base Image Layers
  - No Source Rebuild Required
  - Fast Security Patching
  name: pack rebase
  url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/
- features:
  - Software Bill of Materials
  - Dependency Inventory
  - Security Auditing
  - License Tracking
  name: pack sbom download
  url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/
- features:
  - Community Buildpack Discovery
  - Namespace Registration
  - Version Tracking
  - Verified Buildpacks
  name: Buildpack Registry
  url: https://registry.buildpacks.io/
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Cloud Native Buildpacks
skills: []
slug: buildpacks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: buildpacks\nname: Cloud Native Buildpacks\ndescription: >-\n  Cloud Native Buildpacks (CNBs) transform application source code into\n  OCI-compliant container images that can run on any cloud, without requiring\n  Dockerfiles. Initiated by Pivotal and Heroku in January 2018, CNBs are a CNCF\n  incubating project licensed under Apache-2.0. They centralize container\n  expertise through composable buildpacks, enable layer rebasing for efficient\n  OS updates, and generate Software Bills of Materials (SBOM). The pack CLI and\n  kpack platform operator are primary integration points.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/buildpacks/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n  - Build Tools\n  - CI/CD\n  - Cloud Native\n  - CNCF\n  - Container Images\n  - Containers\n  - OCI\n  - Open Source\napis:\n\
  \  - aid: buildpacks:buildpack-api\n    name: Buildpack API Specification\n    description: >-\n      The Buildpack API defines the contract between a buildpack and the\n      lifecycle that executes it. It specifies detect, build, and export phases,\n      layer contribution formats, environment variable handling, and SBOM\n      generation interfaces.\n    humanURL: https://buildpacks.io/docs/reference/spec/buildpack-api/\n    tags:\n      - API Specification\n      - Buildpacks\n      - Container Images\n      - OCI\n    properties:\n      - type: Documentation\n        url: https://buildpacks.io/docs/reference/spec/buildpack-api/\n      - type: GitHubRepository\n        url: https://github.com/buildpacks/spec\n  - aid: buildpacks:platform-api\n    name: Platform API Specification\n    description: >-\n      The Platform API defines the contract between a platform (such as pack or\n      kpack) and the CNB lifecycle. It covers builder configuration, build\n      inputs and outputs,\
  \ stack definitions, and run image management.\n    humanURL: https://buildpacks.io/docs/reference/spec/platform-api/\n    tags:\n      - API Specification\n      - Container Images\n      - Platforms\n    properties:\n      - type: Documentation\n        url: https://buildpacks.io/docs/reference/spec/platform-api/\n      - type: GitHubRepository\n        url: https://github.com/buildpacks/spec\n  - aid: buildpacks:distribution-api\n    name: Distribution API Specification\n    description: >-\n      The Distribution API defines the OCI-based format for packaging and\n      distributing buildpacks and builders via container registries, including\n      the buildpackage format.\n    humanURL: https://buildpacks.io/docs/reference/spec/distribution-api/\n    tags:\n      - API Specification\n      - Distribution\n      - OCI\n      - Packaging\n    properties:\n      - type: Documentation\n        url: https://buildpacks.io/docs/reference/spec/distribution-api/\n      - type: GitHubRepository\n\
  \        url: https://github.com/buildpacks/spec\ncommon:\n  - type: Website\n    url: https://buildpacks.io\n  - type: Documentation\n    url: https://buildpacks.io/docs/\n  - type: GitHubOrganization\n    url: https://github.com/buildpacks\n  - type: Blog\n    url: https://medium.com/buildpacks\n  - type: Community\n    url: https://buildpacks.io/community/\n  - type: Registry\n    url: https://registry.buildpacks.io/\n  - type: Specification\n    url: https://github.com/buildpacks/spec/blob/main/buildpack.md\n  - type: MailingList\n    url: https://lists.cncf.io/g/cncf-buildpacks/join\n  - type: Slack\n    url: https://slack.cncf.io\n  - type: CNCF\n    url: https://www.cncf.io/projects/buildpacks/\n  - type: DevStats\n    url: https://buildpacks.devstats.cncf.io/\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: App Developer Image Building\n        url: https://buildpacks.io/docs/for-app-developers/\n        features:\n          - No Dockerfile Required\n        \
  \  - Automatic Dependency Detection\n          - Multi-Language Support\n          - Reproducible Builds\n          - ARM Container Support\n          - Windows Container Support\n      - name: Platform Operator Integration\n        url: https://buildpacks.io/docs/for-platform-operators/\n        features:\n          - CI/CD Pipeline Integration\n          - pack CLI Integration\n          - kpack Kubernetes Operator\n          - Tekton Pipeline Support\n          - CircleCI Integration\n          - GitLab CI Integration\n          - Custom Builder Creation\n      - name: Buildpack Authoring\n        url: https://buildpacks.io/docs/for-buildpack-authors/\n        features:\n          - Custom Language Support\n          - Framework-Specific Buildpacks\n          - Buildpack Packaging\n          - Registry Distribution\n          - Extension Authoring\n          - Composable Buildpack Groups\n      - name: OS-Level Security Patching\n        url: https://buildpacks.io/docs/reference/spec/platform-api/\n\
  \        features:\n          - Layer Rebasing\n          - Base Image Updates Without Rebuild\n          - Minimal Rebuild Surface\n          - Stack Switching\n  - name: Features\n    type: Features\n    data:\n      - name: pack build\n        url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/\n        features:\n          - Source-to-Image Conversion\n          - Builder Selection\n          - Environment Variable Injection\n          - Volume Mount Support\n          - Cache Integration\n      - name: pack builder\n        url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/\n        features:\n          - Create Custom Builders\n          - Inspect Builder Contents\n          - Trust Builder Configuration\n          - Suggest Default Builders\n      - name: pack rebase\n        url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/\n        features:\n          - Update Base Image Layers\n\
  \          - No Source Rebuild Required\n          - Fast Security Patching\n      - name: pack sbom download\n        url: https://buildpacks.io/docs/for-platform-operators/how-to/integrate-ci/pack/cli/\n        features:\n          - Software Bill of Materials\n          - Dependency Inventory\n          - Security Auditing\n          - License Tracking\n      - name: Buildpack Registry\n        url: https://registry.buildpacks.io/\n        features:\n          - Community Buildpack Discovery\n          - Namespace Registration\n          - Version Tracking\n          - Verified Buildpacks\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/buildpacks/refs/heads/main/apis.yml
tags:
- Build Tools
- CI/CD
- Cloud Native
- CNCF
- Container Images
- Containers
- OCI
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/buildpacks/refs/heads/main/apis.yml
use_cases:
- features:
  - No Dockerfile Required
  - Automatic Dependency Detection
  - Multi-Language Support
  - Reproducible Builds
  - ARM Container Support
  - Windows Container Support
  name: App Developer Image Building
  url: https://buildpacks.io/docs/for-app-developers/
- features:
  - CI/CD Pipeline Integration
  - pack CLI Integration
  - kpack Kubernetes Operator
  - Tekton Pipeline Support
  - CircleCI Integration
  - GitLab CI Integration
  - Custom Builder Creation
  name: Platform Operator Integration
  url: https://buildpacks.io/docs/for-platform-operators/
- features:
  - Custom Language Support
  - Framework-Specific Buildpacks
  - Buildpack Packaging
  - Registry Distribution
  - Extension Authoring
  - Composable Buildpack Groups
  name: Buildpack Authoring
  url: https://buildpacks.io/docs/for-buildpack-authors/
- features:
  - Layer Rebasing
  - Base Image Updates Without Rebuild
  - Minimal Rebuild Surface
  - Stack Switching
  name: OS-Level Security Patching
  url: https://buildpacks.io/docs/reference/spec/platform-api/
---
