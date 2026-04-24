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
