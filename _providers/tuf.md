---
api_count: 7
apis:
- description: The TUF specification defines the structure of update repositories including the root, targets, snapshot, and timestamp metadata files. Each metadata file has a defined schema with signatures, expirat
  name: TUF Repository Specification
  slug: tuf-spec
- description: The official Python reference implementation of The Update Framework (TUF) specification. Provides a metadata API for reading and writing TUF metadata files, an ngclient API implementing the TUF clien
  name: TUF Python Reference Implementation
  slug: python-tuf
- description: A Go implementation of The Update Framework (TUF), heavily influenced by python-tuf's design. Provides metadata, TrustedMetadata, and Updater packages implementing the TUF client workflow and specific
  name: TUF Go Implementation
  slug: go-tuf
- description: A Rust implementation of The Update Framework (TUF) specification providing a strongly-typed API for working with TUF metadata, verifying signatures, and implementing the TUF client update workflow.
  name: TUF Rust Implementation
  slug: rust-tuf
- description: A JavaScript/TypeScript implementation of The Update Framework (TUF) for use in Node.js environments and browser-based update systems. Enables TUF-compliant software update verification in the JavaScr
  name: TUF JavaScript Implementation
  slug: tuf-js
- description: 'A TUF repository management and signing tool designed for use in CI/CD pipelines. Enables teams to maintain a TUF repository using GitHub Actions and other CI systems for automated, policy-driven key '
  name: TUF on CI
  slug: tuf-on-ci
- description: The official TUF client conformance test suite for verifying that TUF client implementations correctly implement the TUF specification, including proper handling of all attack vectors and edge cases.
  name: TUF Conformance Test Suite
  slug: tuf-conformance
common:
- title: ''
  type: Website
  url: https://theupdateframework.io/
- title: ''
  type: Documentation
  url: https://theupdateframework.io/docs/
- title: ''
  type: GettingStarted
  url: https://theupdateframework.io/docs/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/theupdateframework
- title: ''
  type: GitHubRepository
  url: https://github.com/theupdateframework/python-tuf
- title: ''
  type: Specification
  url: https://theupdateframework.github.io/specification/latest/
- title: ''
  type: Blog
  url: https://theupdateframework.io/resources/news/
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/the-update-framework-tuf/
- title: ''
  type: Community
  url: https://github.com/theupdateframework/community
- title: ''
  type: JSON-LD
  url: json-ld/tuf-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tuf-root-metadata-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tuf-targets-metadata-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tuf-snapshot-metadata-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tuf-timestamp-metadata-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/tuf-vocabulary.yml
created: '2026-03-16'
description: TUF (The Update Framework) is a CNCF graduated framework for securing software update systems. It provides a specification for how software repositories should be structured and how clients should verify updates to protect against key compromise, rollback attacks, and mix-and-match attacks. TUF is used by many package managers and update systems including PyPI, Sigstore, and various Linux distributions. The framework defines a four-role metadata structure (root, targets, snapshot, timestamp) with threshold signing and delegation capabilities for scalable trust management.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Tuf Context
  property_count: 12
  slug: tuf-context
layout: provider
modified: '2026-05-03'
name: The Update Framework (TUF)
skills: []
slug: tuf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tuf\nname: The Update Framework (TUF)\ndescription: >-\n  TUF (The Update Framework) is a CNCF graduated framework for securing\n  software update systems. It provides a specification for how software\n  repositories should be structured and how clients should verify updates\n  to protect against key compromise, rollback attacks, and mix-and-match\n  attacks. TUF is used by many package managers and update systems including\n  PyPI, Sigstore, and various Linux distributions. The framework defines\n  a four-role metadata structure (root, targets, snapshot, timestamp) with\n  threshold signing and delegation capabilities for scalable trust management.\nurl: https://theupdateframework.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CNCF\n  - Cloud Native\n  - Graduated\n  - Security\n  - Software Supply Chain\n  - Software Updates\n  - Verification\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\n\
  type: Index\napis:\n  - aid: tuf:tuf-spec\n    name: TUF Repository Specification\n    description: >-\n      The TUF specification defines the structure of update repositories\n      including the root, targets, snapshot, and timestamp metadata files.\n      Each metadata file has a defined schema with signatures, expiration\n      dates, and delegation rules. Clients follow a defined verification\n      workflow to securely resolve and download updates while protecting\n      against various attack vectors including key compromise, rollback attacks,\n      freeze attacks, and mix-and-match attacks. The specification is version 1.0.31.\n    humanURL: https://theupdateframework.github.io/specification/latest/\n    properties:\n      - type: Documentation\n        url: https://theupdateframework.github.io/specification/latest/\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/specification\n      - type: JSONSchema\n        url: json-schema/tuf-root-metadata-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/tuf-targets-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/tuf-snapshot-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/tuf-timestamp-metadata-schema.json\n    tags:\n      - Metadata\n      - Repository Metadata\n      - Specification\n      - Verification\n  - aid: tuf:python-tuf\n    name: TUF Python Reference Implementation\n    description: >-\n      The official Python reference implementation of The Update Framework (TUF)\n      specification. Provides a metadata API for reading and writing TUF metadata\n      files, an ngclient API implementing the TUF client update workflow, and a\n      repository library for building TUF-compliant software repositories.\n      Available on PyPI as the 'tuf' package.\n    humanURL: https://theupdateframework.readthedocs.io/en/stable/\n    properties:\n      - type: Documentation\n        url: https://theupdateframework.readthedocs.io/en/stable/\n\
  \      - type: GitHubRepository\n        url: https://github.com/theupdateframework/python-tuf\n      - type: PackageRegistry\n        url: https://pypi.org/project/tuf/\n    tags:\n      - Client Library\n      - Python\n      - Security\n      - Software Updates\n      - Supply Chain\n  - aid: tuf:go-tuf\n    name: TUF Go Implementation\n    description: >-\n      A Go implementation of The Update Framework (TUF), heavily influenced by\n      python-tuf's design. Provides metadata, TrustedMetadata, and Updater\n      packages implementing the TUF client workflow and specification-compliant\n      metadata handling, as well as multi-repository support via TAP 4.\n    humanURL: https://github.com/theupdateframework/go-tuf\n    properties:\n      - type: Documentation\n        url: https://github.com/theupdateframework/go-tuf\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/go-tuf\n    tags:\n      - Client Library\n      - Go\n      - Security\n     \
  \ - Software Updates\n      - Supply Chain\n  - aid: tuf:rust-tuf\n    name: TUF Rust Implementation\n    description: >-\n      A Rust implementation of The Update Framework (TUF) specification providing\n      a strongly-typed API for working with TUF metadata, verifying signatures,\n      and implementing the TUF client update workflow.\n    humanURL: https://github.com/theupdateframework/rust-tuf\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/rust-tuf\n    tags:\n      - Client Library\n      - Rust\n      - Security\n      - Software Updates\n  - aid: tuf:tuf-js\n    name: TUF JavaScript Implementation\n    description: >-\n      A JavaScript/TypeScript implementation of The Update Framework (TUF) for\n      use in Node.js environments and browser-based update systems. Enables\n      TUF-compliant software update verification in the JavaScript ecosystem.\n    humanURL: https://github.com/theupdateframework/tuf-js\n    properties:\n\
  \      - type: GitHubRepository\n        url: https://github.com/theupdateframework/tuf-js\n    tags:\n      - Client Library\n      - JavaScript\n      - Security\n      - Software Updates\n      - TypeScript\n  - aid: tuf:tuf-on-ci\n    name: TUF on CI\n    description: >-\n      A TUF repository management and signing tool designed for use in CI/CD\n      pipelines. Enables teams to maintain a TUF repository using GitHub Actions\n      and other CI systems for automated, policy-driven key management and metadata\n      signing workflows.\n    humanURL: https://github.com/theupdateframework/tuf-on-ci\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/tuf-on-ci\n    tags:\n      - CI/CD\n      - Key Management\n      - Repository Management\n      - Security\n  - aid: tuf:tuf-conformance\n    name: TUF Conformance Test Suite\n    description: >-\n      The official TUF client conformance test suite for verifying that TUF client\n     \
  \ implementations correctly implement the TUF specification, including proper\n      handling of all attack vectors and edge cases.\n    humanURL: https://github.com/theupdateframework/tuf-conformance\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/tuf-conformance\n    tags:\n      - Compliance\n      - Conformance Testing\n      - Security\n      - Testing\ncommon:\n  - type: Website\n    url: https://theupdateframework.io/\n  - type: Documentation\n    url: https://theupdateframework.io/docs/\n  - type: GettingStarted\n    url: https://theupdateframework.io/docs/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/theupdateframework\n  - type: GitHubRepository\n    url: https://github.com/theupdateframework/python-tuf\n  - type: Specification\n    url: https://theupdateframework.github.io/specification/latest/\n  - type: Blog\n    url: https://theupdateframework.io/resources/news/\n  - type: CNCF\n    url: https://www.cncf.io/projects/the-update-framework-tuf/\n\
  \  - type: Community\n    url: https://github.com/theupdateframework/community\n  - type: JSON-LD\n    url: json-ld/tuf-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tuf-root-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-targets-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-snapshot-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-timestamp-metadata-schema.json\n  - type: Vocabulary\n    url: vocabulary/tuf-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tuf/refs/heads/main/apis.yml
tags:
- CNCF
- Cloud Native
- Graduated
- Security
- Software Supply Chain
- Software Updates
- Verification
url: https://theupdateframework.io
use_cases: []
---
