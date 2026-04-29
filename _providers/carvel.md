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
source_filename: apis.yml
source_yaml: "aid: carvel\nname: Carvel\ndescription: >-\n  Carvel is a set of reliable, single-purpose, composable command-line tools\n  that help build, configure, and deploy applications to Kubernetes. The toolset\n  includes ytt for YAML templating, kapp for application lifecycle management,\n  kbld for immutable image references, imgpkg for OCI bundling, vendir for\n  vendored configuration, and kapp-controller for GitOps-style continuous\n  delivery.\ntype: Index\nx-type: opensource\nposition: Consumer\naccess: Open Source\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CLI\n  - Configuration\n  - Containers\n  - Deployment\n  - GitOps\n  - Kubernetes\n  - Package Management\n  - Templating\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carvel/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: carvel:ytt\n    name: ytt\n    description: >-\n      ytt is a\
  \ templating tool that understands YAML structure, letting you use\n      familiar YAML constructs and Python-like language (Starlark) to template\n      Kubernetes configuration. Supports overlays, data values, and functions\n      without text-based substitution.\n    humanURL: https://carvel.dev/ytt/\n    tags:\n      - Configuration\n      - Kubernetes\n      - Templating\n      - YAML\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/ytt/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/ytt\n      - type: Playground\n        url: https://carvel.dev/ytt/#playground\n    x-features:\n      - YAML-structure-aware templating\n      - Starlark-based programming model\n      - Overlays to patch existing YAML\n      - Data values for parameterization\n      - Schema validation for data values\n      - Reusable functions and libraries\n    x-use-cases:\n      - Parameterizing Kubernetes manifests\n      - Patching third-party\
  \ YAML without forking\n      - Generating multi-environment configuration\n      - Creating reusable configuration libraries\n  - aid: carvel:kapp\n    name: kapp\n    description: >-\n      kapp is a CLI tool that installs, upgrades, and deletes multiple\n      Kubernetes resources as a single application. It provides change set\n      previews, resource ordering, and convergence detection for predictable\n      deployments.\n    humanURL: https://carvel.dev/kapp/\n    tags:\n      - Deployment\n      - Kubernetes\n      - Lifecycle\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/kapp/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/kapp\n    x-features:\n      - Change-set preview before apply\n      - Resource ordering and waiting\n      - Label-based application grouping\n      - Convergence detection on deploy\n      - Garbage collection of removed resources\n    x-use-cases:\n      - Deploying Kubernetes applications\
  \ atomically\n      - Previewing infrastructure changes before apply\n      - Managing application lifecycle without Helm\n  - aid: carvel:kbld\n    name: kbld\n    description: >-\n      kbld builds or references container images in Kubernetes configuration in\n      an immutable way by resolving image tags to digests and optionally\n      building images from source during the deployment pipeline.\n    humanURL: https://carvel.dev/kbld/\n    tags:\n      - Container Images\n      - Immutable\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/kbld/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/kbld\n    x-features:\n      - Resolve image tags to digests\n      - Build images from source with Docker/pack\n      - Push to registries during deploy\n      - Integration with ytt and kapp\n    x-use-cases:\n      - Ensuring immutable image references\n      - Building and deploying images in one pipeline\n\
  \      - Auditing which images are actually deployed\n  - aid: carvel:imgpkg\n    name: imgpkg\n    description: >-\n      imgpkg bundles and distributes application configuration and container\n      images as OCI artifacts via Docker registries, enabling relocation across\n      registries including air-gapped environments.\n    humanURL: https://carvel.dev/imgpkg/\n    tags:\n      - Bundles\n      - Container Images\n      - OCI\n      - Registry\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/imgpkg/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/imgpkg\n    x-features:\n      - OCI-compliant bundles\n      - Bundle relocation between registries\n      - Air-gapped deployment support\n      - Lock files for reproducibility\n    x-use-cases:\n      - Distributing Kubernetes app bundles\n      - Air-gapped deployments\n      - Registry-to-registry mirroring\n  - aid: carvel:vendir\n    name: vendir\n    description:\
  \ >-\n      vendir declaratively states what files should be in a directory, syncing\n      from upstream sources such as Git repositories, HTTP archives, Helm\n      charts, and OCI images. Enables reproducible vendored configuration.\n    humanURL: https://carvel.dev/vendir/\n    tags:\n      - Configuration\n      - Vendoring\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/vendir/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/vendir\n    x-features:\n      - Declarative sync from Git, HTTP, Helm, OCI\n      - Lock files for reproducibility\n      - Selective inclusion of files\n      - Integration with overlays via ytt\n    x-use-cases:\n      - Vendoring third-party Kubernetes configuration\n      - Pinning upstream Helm charts\n      - Reproducible configuration builds\n  - aid: carvel:kapp-controller\n    name: kapp-controller\n    description: >-\n      kapp-controller is a Kubernetes controller that provides\
  \ GitOps-style\n      continuous delivery for applications and packages using Carvel tools. It\n      introduces PackageRepository, Package, PackageInstall, and App custom\n      resources for package management.\n    humanURL: https://carvel.dev/kapp-controller/\n    tags:\n      - CRD\n      - GitOps\n      - Kubernetes\n      - Package Management\n    properties:\n      - type: Documentation\n        url: https://carvel.dev/kapp-controller/docs/latest/\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/kapp-controller\n    x-features:\n      - App and Package CRDs\n      - PackageRepository for distribution\n      - GitOps continuous reconciliation\n      - ytt, kbld, and kapp integration\n      - Versioning and constraints for packages\n    x-use-cases:\n      - Kubernetes package management\n      - GitOps-driven continuous delivery\n      - Distributing internal platform packages\n  - aid: carvel:secretgen-controller\n    name: secretgen-controller\n   \
  \ description: >-\n      secretgen-controller provides CRDs to generate Kubernetes Secrets, export\n      and import secrets across namespaces, and manage certificate and password\n      creation declaratively.\n    humanURL: https://github.com/carvel-dev/secretgen-controller\n    tags:\n      - CRD\n      - Kubernetes\n      - Secrets\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/carvel-dev/secretgen-controller\n    x-features:\n      - Generate Certificates, Passwords, RSA Keys, SSH Keys\n      - Cross-namespace secret export/import\n      - Declarative secret management via CRDs\n    x-use-cases:\n      - Generating bootstrap credentials\n      - Sharing secrets across namespaces\n      - Declarative certificate management\ncommon:\n  - type: Website\n    url: https://carvel.dev/\n  - type: Documentation\n    url: https://carvel.dev/docs/latest/\n  - type: GitHub Organization\n    url: https://github.com/carvel-dev\n  - type: Blog\n    url: https://carvel.dev/blog/\n\
  \  - type: Slack\n    url: https://kubernetes.slack.com/archives/CH8KCCKA5\n  - type: Community\n    url: https://carvel.dev/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carvel/refs/heads/main/apis.yml
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
