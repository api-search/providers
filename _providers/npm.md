---
api_count: 5
api_specs:
- filename: npm-registry-api-openapi.yml
  format: yaml
  label: npm Registry API
  slug: registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-registry-api-openapi.yml
- filename: npm-public-api-openapi.yml
  format: yaml
  label: npm Public API
  slug: public
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-public-api-openapi.yml
- filename: npm-hooks-api-openapi.yml
  format: yaml
  label: npm Hooks API
  slug: hooks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-hooks-api-openapi.yml
apis:
- description: The npm Registry API provides programmatic access to the npm package registry, the largest software registry in the world hosting over two million JavaScript packages. Developers can query package met
  name: npm Registry API
  slug: registry
- description: The npm Public API provides authenticated endpoints for managing npm access tokens, configuring trusted publishers, and exchanging OIDC tokens for short-lived registry access. It supports creating, li
  name: npm Public API
  slug: public
- description: The npm Hooks API allows developers to subscribe to notifications about changes in the npm registry. Hooks send HTTP POST payloads to a configured URI whenever a package is changed, enabling developer
  name: npm Hooks API
  slug: hooks
- description: 'The npm CLI is the official command-line interface for the npm package manager, providing developers with tools to install, publish, and manage JavaScript packages and their dependencies. It supports '
  name: npm CLI
  slug: cli
- description: npm Provenance provides supply chain security for JavaScript packages by establishing a verifiable link between a published package and its source code repository and build environment. When a package
  name: npm Provenance
  slug: provenance
asyncapis:
- description: The npm Hooks event system delivers HTTP POST payloads to subscriber endpoints whenever changes occur in the npm registry. Hooks can be configured to watch for changes to individual packages, all pack
  name: npm Hooks Events
  slug: npm-hooks-asyncapi
common:
- title: ''
  type: Portal
  url: https://www.npmjs.com/
- title: ''
  type: Documentation
  url: https://docs.npmjs.com/
- title: ''
  type: Blog
  url: https://blog.npmjs.org/
- title: ''
  type: Login
  url: https://www.npmjs.com/login
- title: ''
  type: Support
  url: https://www.npmjs.com/support
- title: ''
  type: PrivacyPolicy
  url: https://docs.npmjs.com/policies/privacy
- title: ''
  type: TermsOfService
  url: https://docs.npmjs.com/policies/terms
- title: ''
  type: Website
  url: https://www.npmjs.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/npm
- title: ''
  type: StatusPage
  url: https://status.npmjs.org/
created: '2026-03-20'
description: npm is the world's largest software registry, hosting over two million JavaScript packages for the Node.js ecosystem. Their developer platform provides APIs for searching and retrieving package metadata, managing access tokens, subscribing to registry event webhooks, and publishing packages with supply chain provenance verification.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Npm Context
  property_count: 8
  slug: npm-context
layout: provider
modified: '2026-04-28'
name: npm
skills: []
slug: npm
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: npm\nname: npm\ndescription: >-\n  npm is the world's largest software registry, hosting over two million\n  JavaScript packages for the Node.js ecosystem. Their developer platform\n  provides APIs for searching and retrieving package metadata, managing access\n  tokens, subscribing to registry event webhooks, and publishing packages with\n  supply chain provenance verification.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Packages\n  - JavaScript\n  - Node.js\n  - Package Management\n  - Registry\n  - Security\nurl: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/apis.yml\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: npm:registry\n    name: npm Registry API\n    description: >-\n      The npm Registry API provides programmatic access to the npm package\n      registry, the largest software registry\
  \ in the world hosting over two\n      million JavaScript packages. Developers can query package metadata,\n      download tarballs, search for packages, and retrieve version-specific\n      information. The API follows CouchDB-based conventions and serves package\n      manifests in JSON format, enabling tools and services to integrate with\n      the npm ecosystem for dependency resolution, package discovery, and\n      automated workflows.\n    humanURL: https://github.com/npm/registry/blob/main/docs/REGISTRY-API.md\n    baseURL: https://registry.npmjs.org\n    tags:\n      - Packages\n      - JavaScript\n      - Registry\n      - Package Management\n      - Node.js\n    properties:\n      - type: Documentation\n        url: https://github.com/npm/registry/blob/main/docs/REGISTRY-API.md\n      - type: OpenAPI\n        url: openapi/npm-registry-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/npm-package-schema.json\n  - aid: npm:public\n    name: npm Public API\n\
  \    description: >-\n      The npm Public API provides authenticated endpoints for managing npm\n      access tokens, configuring trusted publishers, and exchanging OIDC tokens\n      for short-lived registry access. It supports creating, listing, and\n      deleting npm access tokens with customizable permissions, scope\n      restrictions, expiration settings, and CIDR IP range limitations. The API\n      also enables CI/CD providers like GitHub Actions, GitLab CI, and CircleCI\n      to publish packages securely through OIDC token exchange without\n      requiring long-lived npm tokens.\n    humanURL: https://api-docs.npmjs.com/\n    baseURL: https://npm.pkg.github.com\n    tags:\n      - Packages\n      - Tokens\n      - Authentication\n      - Security\n      - OIDC\n      - Access Control\n    properties:\n      - type: Documentation\n        url: https://api-docs.npmjs.com/\n      - type: OpenAPI\n        url: openapi/npm-public-api-openapi.yml\n  - aid: npm:hooks\n    name: npm\
  \ Hooks API\n    description: >-\n      The npm Hooks API allows developers to subscribe to notifications about\n      changes in the npm registry. Hooks send HTTP POST payloads to a configured\n      URI whenever a package is changed, enabling developers to build\n      integrations that respond to registry events in real time. Users can add\n      hooks to follow specific packages, track all activity of given npm users,\n      or monitor all packages within an organization or user scope. The API\n      provides endpoints for creating, listing, updating, and deleting hook\n      subscriptions.\n    humanURL: https://blog.npmjs.org/post/145260155635/introducing-hooks-get-notifications-of-npm\n    tags:\n      - Webhooks\n      - Notifications\n      - Events\n      - Automation\n      - Packages\n    properties:\n      - type: Documentation\n        url: https://blog.npmjs.org/post/145260155635/introducing-hooks-get-notifications-of-npm\n      - type: OpenAPI\n        url: openapi/npm-hooks-api-openapi.yml\n\
  \      - type: AsyncAPI\n        url: asyncapi/npm-hooks-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/npm-hook-event-schema.json\n  - aid: npm:cli\n    name: npm CLI\n    description: >-\n      The npm CLI is the official command-line interface for the npm package\n      manager, providing developers with tools to install, publish, and manage\n      JavaScript packages and their dependencies. It supports package\n      publishing with provenance attestation via Sigstore, workspace management\n      for monorepos, script execution, semantic versioning, and comprehensive\n      dependency tree management. The CLI is bundled with Node.js and serves\n      as the primary developer interface for interacting with the npm registry.\n    humanURL: https://docs.npmjs.com/cli\n    tags:\n      - Command Line\n      - Package Management\n      - JavaScript\n      - Node.js\n      - Developer Tools\n    properties:\n      - type: Documentation\n        url: https://docs.npmjs.com/cli\n\
  \      - type: SourceCode\n        url: https://github.com/npm/cli\n  - aid: npm:provenance\n    name: npm Provenance\n    description: >-\n      npm Provenance provides supply chain security for JavaScript packages\n      by establishing a verifiable link between a published package and its\n      source code repository and build environment. When a package is published\n      with provenance, it is signed using Sigstore public good servers and the\n      attestation is logged in a public transparency ledger. This allows\n      developers to verify where and how a package was built before downloading\n      it, helping to protect against supply chain attacks and ensuring the\n      integrity of the npm ecosystem.\n    humanURL: https://docs.npmjs.com/generating-provenance-statements\n    tags:\n      - Security\n      - Supply Chain\n      - Verification\n      - Sigstore\n      - Transparency\n      - CI/CD\n    properties:\n      - type: Documentation\n        url: https://docs.npmjs.com/generating-provenance-statements\n\
  \      - type: Documentation\n        url: https://github.blog/security/supply-chain-security/introducing-npm-package-provenance/\ncommon:\n  - url: https://www.npmjs.com/\n    name: npm Portal\n    type: Portal\n  - url: https://docs.npmjs.com/\n    name: npm Documentation\n    type: Documentation\n  - url: https://blog.npmjs.org/\n    name: npm Blog\n    type: Blog\n  - url: https://www.npmjs.com/login\n    name: Login\n    type: Login\n  - url: https://www.npmjs.com/support\n    name: Support\n    type: Support\n  - url: https://docs.npmjs.com/policies/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://docs.npmjs.com/policies/terms\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.npmjs.com/\n    name: Website\n    type: Website\n  - url: https://github.com/npm\n    name: GitHub Organization\n    type: GitHubOrg\n  - url: https://status.npmjs.org/\n    name: Status\n    type: StatusPage\nmaintainers:\n  - FN: API Evangelist\n    email:\
  \ info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/apis.yml
tags:
- Packages
- JavaScript
- Node.js
- Package Management
- Registry
- Security
url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/apis.yml
use_cases: []
---
