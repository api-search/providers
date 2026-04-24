---
api_count: 7
apis:
- description: ytt is a templating tool that understands YAML structure, letting you use familiar YAML constructs and Python-like language (Starlark) to template Kubernetes configuration. Supports overlays, data val
  name: ytt
  slug: ytt
- description: kapp is a CLI tool that installs, upgrades, and deletes multiple Kubernetes resources as a single application. It provides change set previews, resource ordering, and convergence detection for predict
  name: kapp
  slug: kapp
- description: kbld builds or references container images in Kubernetes configuration in an immutable way by resolving image tags to digests and optionally building images from source during the deployment pipeline.
  name: kbld
  slug: kbld
- description: imgpkg bundles and distributes application configuration and container images as OCI artifacts via Docker registries, enabling relocation across registries including air-gapped environments.
  name: imgpkg
  slug: imgpkg
- description: vendir declaratively states what files should be in a directory, syncing from upstream sources such as Git repositories, HTTP archives, Helm charts, and OCI images. Enables reproducible vendored confi
  name: vendir
  slug: vendir
- description: kapp-controller is a Kubernetes controller that provides GitOps-style continuous delivery for applications and packages using Carvel tools. It introduces PackageRepository, Package, PackageInstall, an
  name: kapp-controller
  slug: kapp-controller
- description: secretgen-controller provides CRDs to generate Kubernetes Secrets, export and import secrets across namespaces, and manage certificate and password creation declaratively.
  name: secretgen-controller
  slug: secretgen-controller
common:
- title: ''
  type: Website
  url: https://carvel.dev/
- title: ''
  type: Documentation
  url: https://carvel.dev/docs/latest/
- title: ''
  type: GitHub Organization
  url: https://github.com/carvel-dev
- title: ''
  type: Blog
  url: https://carvel.dev/blog/
- title: ''
  type: Slack
  url: https://kubernetes.slack.com/archives/CH8KCCKA5
- title: ''
  type: Community
  url: https://carvel.dev/community/
created: '2026-03-26'
description: Carvel is a set of reliable, single-purpose, composable command-line tools that help build, configure, and deploy applications to Kubernetes. The toolset includes ytt for YAML templating, kapp for application lifecycle management, kbld for immutable image references, imgpkg for OCI bundling, vendir for vendored configuration, and kapp-controller for GitOps-style continuous delivery.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Carvel
skills: []
slug: carvel
solutions: []
tags:
- CLI
- Configuration
- Containers
- Deployment
- GitOps
- Kubernetes
- Package Management
- Templating
url: https://raw.githubusercontent.com/api-evangelist/carvel/refs/heads/main/apis.yml
use_cases: []
---
