---
api_count: 2
apis:
- description: The @yarnpkg/core programmatic JavaScript/TypeScript API that allows applications to interact with Yarn projects, workspaces, and dependency resolution. Used for building Yarn plugins and tooling inte
  name: YARN Core API
  slug: yarn-core-api
- description: The Yarn command-line interface built on @yarnpkg/cli, providing commands for package installation, workspace management, publishing, and more. Supports a plugin system for extensibility.
  name: YARN CLI
  slug: yarn-cli
common:
- title: ''
  type: Documentation
  url: https://yarnpkg.com/getting-started
- title: ''
  type: GettingStarted
  url: https://yarnpkg.com/getting-started/install
- title: ''
  type: Tutorials
  url: https://yarnpkg.com/getting-started/usage
- title: ''
  type: APIReference
  url: https://yarnpkg.com/api
- title: ''
  type: GitHubOrganization
  url: https://github.com/yarnpkg
- title: ''
  type: GitHubRepository
  url: https://github.com/yarnpkg/berry
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/yarn
- title: ''
  type: ChangeLog
  url: https://github.com/yarnpkg/berry/blob/master/CHANGELOG.md
- title: ''
  type: BestPractices
  url: https://yarnpkg.com/migration/guide
- title: ''
  type: Resources
  url: https://yarnpkg.com/configuration/yarnrc
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/yarn/main/json-schema/yarn-package-schema.json
created: '2025'
description: YARN (Yet Another Resource Negotiator in the original Hadoop context; also the JavaScript package manager) refers here to the yarnpkg.com JavaScript package manager. Yarn is a fast, reliable, and secure dependency management tool for JavaScript. Originally developed by Meta as an alternative to npm, Yarn offers deterministic dependency resolution, offline caching, parallel installation, and Plug'n'Play (PnP) module resolution. The project is actively maintained under the yarnpkg/berry repository (Yarn 2+) with a modular plugin architecture. Yarn provides a programmatic JavaScript/TypeScript API via @yarnpkg/core for building tools and plugins.
features:
- description: First-class monorepo support letting projects split into sub-components managed from a single root.
  name: Workspaces
- description: Alternative installation strategy that eliminates node_modules in favor of a single resolution map for faster, stricter installs.
  name: Plug'n'Play (PnP)
- description: Modular core with 25+ default plugins and a public API for building custom workflows and integrations.
  name: Plugin Architecture
- description: Local cache of downloaded packages enabling reproducible installs without network access.
  name: Offline Caching
- description: Concurrent dependency fetching and linking for faster installs versus serial package managers.
  name: Parallel Installation
- description: Lockfile-driven dependency resolution that produces identical installs across machines and CI runs.
  name: Deterministic Resolution
- description: Stricter install mode that verifies registry metadata against the lockfile to defend against supply-chain tampering.
  name: Hardened Mode
- description: Built-in shell interpreter so package scripts behave consistently across Linux, macOS, and Windows.
  name: Cross-platform Shell
- description: Declarative rules for enforcing dependency policies and conventions across a workspace.
  name: Constraints
- description: Search and upgrade UIs that let developers explore and manage dependencies interactively.
  name: Interactive Commands
- description: TypeScript-first @yarnpkg/core surface for building plugins, tooling, and CI integrations.
  name: Programmatic API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary package registry for installing and publishing JavaScript packages.
  name: npm Registry
- description: Runtime that executes Yarn-managed packages and the Yarn CLI itself.
  name: Node.js
- description: Yarn ships TypeScript type definitions and is itself written primarily in TypeScript.
  name: TypeScript
- description: Node.js shim that pins and provisions the Yarn version per project.
  name: Corepack
- description: Editor SDK integration that wires Yarn PnP-managed dependencies into VS Code's TypeScript and ESLint tooling.
  name: VS Code Editor SDK
- description: Editor SDK integration for IntelliJ-family IDEs to resolve PnP dependencies in editor tooling.
  name: JetBrains Editor SDK
- description: Source repository, issue tracker, and release distribution for the yarnpkg organization.
  name: GitHub
- description: Community chat for support, contributor coordination, and announcements.
  name: Discord
layout: provider
modified: '2026-05-03'
name: YARN
skills: []
slug: yarn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: yarn\nname: YARN\ndescription: >-\n  YARN (Yet Another Resource Negotiator in the original Hadoop context; also the JavaScript package manager) refers here to the yarnpkg.com JavaScript\n  package manager. Yarn is a fast, reliable, and secure dependency management tool for JavaScript. Originally developed by Meta as an alternative to npm,\n  Yarn offers deterministic dependency resolution, offline caching, parallel installation, and Plug'n'Play (PnP) module resolution. The project is\n  actively maintained under the yarnpkg/berry repository (Yarn 2+) with a modular plugin architecture. Yarn provides a programmatic JavaScript/TypeScript\n  API via @yarnpkg/core for building tools and plugins.\ntype: Index\nurl: https://github.com/yarnpkg/berry\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - JavaScript\n  - Node.js\n  - Package Manager\n  - YARN\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: yarn:yarn-core-api\n    name: YARN Core API\n    description: >-\n      The @yarnpkg/core programmatic JavaScript/TypeScript API that allows\n      applications to interact with Yarn projects, workspaces, and dependency\n      resolution. Used for building Yarn plugins and tooling integrations.\n    humanURL: https://yarnpkg.com/api\n    baseURL: https://yarnpkg.com\n    tags:\n      - API\n      - JavaScript\n      - Package Manager\n      - Plugin\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://yarnpkg.com/api\n      - type: APIReference\n        url: https://yarnpkg.com/api\n      - type: GitHubRepository\n        url: https://github.com/yarnpkg/berry\n      - type: GettingStarted\n        url: https://yarnpkg.com/advanced/plugin-tutorial\n      - type: Tutorials\n        url: https://yarnpkg.com/advanced/plugin-tutorial\n\n  - aid: yarn:yarn-cli\n    name: YARN CLI\n    description: >-\n      The Yarn command-line interface built on\
  \ @yarnpkg/cli, providing commands\n      for package installation, workspace management, publishing, and more. Supports\n      a plugin system for extensibility.\n    humanURL: https://yarnpkg.com/cli\n    baseURL: https://yarnpkg.com\n    tags:\n      - CLI\n      - JavaScript\n      - Package Manager\n    properties:\n      - type: Documentation\n        url: https://yarnpkg.com/cli\n      - type: APIReference\n        url: https://yarnpkg.com/cli\n      - type: CLI\n        url: https://yarnpkg.com/cli\n      - type: GettingStarted\n        url: https://yarnpkg.com/getting-started/install\n\ncommon:\n  - type: Documentation\n    url: https://yarnpkg.com/getting-started\n  - type: GettingStarted\n    url: https://yarnpkg.com/getting-started/install\n  - type: Tutorials\n    url: https://yarnpkg.com/getting-started/usage\n  - type: APIReference\n    url: https://yarnpkg.com/api\n  - type: GitHubOrganization\n    url: https://github.com/yarnpkg\n  - type: GitHubRepository\n    url: https://github.com/yarnpkg/berry\n\
  \  - type: SDK\n    url: https://www.npmjs.com/package/yarn\n  - type: ChangeLog\n    url: https://github.com/yarnpkg/berry/blob/master/CHANGELOG.md\n  - type: BestPractices\n    url: https://yarnpkg.com/migration/guide\n  - type: Resources\n    url: https://yarnpkg.com/configuration/yarnrc\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/yarn/main/json-schema/yarn-package-schema.json\n  - type: Features\n    data:\n      - name: Workspaces\n        description: First-class monorepo support letting projects split into sub-components managed from a single root.\n      - name: Plug'n'Play (PnP)\n        description: Alternative installation strategy that eliminates node_modules in favor of a single resolution map for faster, stricter installs.\n      - name: Plugin Architecture\n        description: Modular core with 25+ default plugins and a public API for building custom workflows and integrations.\n      - name: Offline Caching\n        description: Local\
  \ cache of downloaded packages enabling reproducible installs without network access.\n      - name: Parallel Installation\n        description: Concurrent dependency fetching and linking for faster installs versus serial package managers.\n      - name: Deterministic Resolution\n        description: Lockfile-driven dependency resolution that produces identical installs across machines and CI runs.\n      - name: Hardened Mode\n        description: Stricter install mode that verifies registry metadata against the lockfile to defend against supply-chain tampering.\n      - name: Cross-platform Shell\n        description: Built-in shell interpreter so package scripts behave consistently across Linux, macOS, and Windows.\n      - name: Constraints\n        description: Declarative rules for enforcing dependency policies and conventions across a workspace.\n      - name: Interactive Commands\n        description: Search and upgrade UIs that let developers explore and manage dependencies interactively.\n\
  \      - name: Programmatic API\n        description: TypeScript-first @yarnpkg/core surface for building plugins, tooling, and CI integrations.\n  - type: UseCases\n    data:\n      - name: Monorepo Management\n        description: Coordinate dependencies, scripts, and releases across many packages in a single repository.\n      - name: Dependency Management\n        description: Install, upgrade, and audit JavaScript and TypeScript dependencies for libraries and applications.\n      - name: Plugin Development\n        description: Build and distribute plugins that extend the Yarn CLI with project-specific commands and behaviors.\n      - name: Reproducible CI Builds\n        description: Use the lockfile, offline cache, and hardened mode to keep CI installs deterministic and tamper-resistant.\n      - name: Package Publishing\n        description: Publish packages to npm and other registries via the npm-related CLI commands and release workflows.\n      - name: Workspace Coordination\n\
  \        description: Run scripts across workspaces, share dependencies, and enforce constraints in large multi-package projects.\n  - type: Integrations\n    data:\n      - name: npm Registry\n        description: Primary package registry for installing and publishing JavaScript packages.\n      - name: Node.js\n        description: Runtime that executes Yarn-managed packages and the Yarn CLI itself.\n      - name: TypeScript\n        description: Yarn ships TypeScript type definitions and is itself written primarily in TypeScript.\n      - name: Corepack\n        description: Node.js shim that pins and provisions the Yarn version per project.\n      - name: VS Code Editor SDK\n        description: Editor SDK integration that wires Yarn PnP-managed dependencies into VS Code's TypeScript and ESLint tooling.\n      - name: JetBrains Editor SDK\n        description: Editor SDK integration for IntelliJ-family IDEs to resolve PnP dependencies in editor tooling.\n      - name: GitHub\n    \
  \    description: Source repository, issue tracker, and release distribution for the yarnpkg organization.\n      - name: Discord\n        description: Community chat for support, contributor coordination, and announcements.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/yarn/refs/heads/main/apis.yml
tags:
- JavaScript
- Node.js
- Package Manager
- YARN
url: https://github.com/yarnpkg/berry
use_cases:
- description: Coordinate dependencies, scripts, and releases across many packages in a single repository.
  name: Monorepo Management
- description: Install, upgrade, and audit JavaScript and TypeScript dependencies for libraries and applications.
  name: Dependency Management
- description: Build and distribute plugins that extend the Yarn CLI with project-specific commands and behaviors.
  name: Plugin Development
- description: Use the lockfile, offline cache, and hardened mode to keep CI installs deterministic and tamper-resistant.
  name: Reproducible CI Builds
- description: Publish packages to npm and other registries via the npm-related CLI commands and release workflows.
  name: Package Publishing
- description: Run scripts across workspaces, share dependencies, and enforce constraints in large multi-package projects.
  name: Workspace Coordination
---
