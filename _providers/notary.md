---
api_count: 4
apis:
- description: The Notary Project specification defines the signature envelope format, trust store and trust policy for container image signing and verification. It supports multiple signature formats and integrates
  name: Notary Project Signing Specification
  slug: notary-spec
- description: Notation is the command-line tool that implements the Notary Project specifications for signing and verifying OCI artifacts stored in container registries. It supports signing with certificates stored
  name: Notation CLI
  slug: notation-cli
- description: notation-go is the official Go library for signing and verifying OCI artifacts using the Notary Project specifications. It provides the programmatic interface used by the Notation CLI and enables Go a
  name: notation-go Library
  slug: notation-go
- description: The Notation plugin extensibility specification defines the interface that third-party plugins must implement to integrate with Notation for key management, signing, and verification operations. Plugi
  name: Notation Plugin Extensibility
  slug: notation-plugin-framework
common:
- title: ''
  type: Website
  url: https://notaryproject.dev
- title: ''
  type: Documentation
  url: https://notaryproject.dev/docs/
- title: ''
  type: Getting Started
  url: https://notaryproject.dev/docs/user-guides/installation/
- title: ''
  type: Blog
  url: https://notaryproject.dev/blog/
- title: ''
  type: FAQ
  url: https://notaryproject.dev/docs/faq/
- title: ''
  type: GitHubOrganization
  url: https://github.com/notaryproject
- title: ''
  type: GitHubRepository
  url: https://github.com/notaryproject/notation
- title: ''
  type: Change Log
  url: https://github.com/notaryproject/notation/releases
- title: ''
  type: JSONSchema
  url: json-schema/notary-trust-policy-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/notary-plugin-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/notary-plugin-protocol-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/notary-signature-envelope-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/notary-context.jsonld
created: '2026-03-16'
description: The Notary Project is a CNCF incubating set of specifications and tools for signing and verifying container images and other OCI artifacts. It provides Notation, a CLI and library for signing artifacts stored in OCI-compliant registries. The project defines standards for signature formats, trust policies, and verification workflows to secure software supply chains.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Notary Context
  property_count: 32
  slug: notary-context
layout: provider
modified: '2026-04-28'
name: Notary Project
skills: []
slug: notary
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: notary\nname: Notary Project\ndescription: >-\n  The Notary Project is a CNCF incubating set of specifications and tools\n  for signing and verifying container images and other OCI artifacts. It\n  provides Notation, a CLI and library for signing artifacts stored in\n  OCI-compliant registries. The project defines standards for signature\n  formats, trust policies, and verification workflows to secure software\n  supply chains.\nurl: https://notaryproject.dev\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Container Security\n  - Image Signing\n  - Incubating\n  - OCI\n  - Verification\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: notary:notary-spec\n    name: Notary Project Signing Specification\n    description: >-\n      The Notary Project specification defines the signature envelope format,\n      trust store and trust policy for container image\
  \ signing and verification.\n      It supports multiple signature formats and integrates with OCI distribution\n      registries for storing signatures alongside container images. The\n      specification enables end-to-end supply chain security from build to\n      deployment.\n    humanURL: https://notaryproject.dev/docs/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://notaryproject.dev/docs/\n      - type: Reference\n        url: https://github.com/notaryproject/specifications/blob/main/specs/trust-store-trust-policy.md\n      - type: GitHubRepository\n        url: https://github.com/notaryproject/specifications\n      - type: JSONSchema\n        url: json-schema/notary-trust-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/notary-signature-envelope-schema.json\n    tags:\n      - Signing\n      - Specification\n      - Verification\n  - aid: notary:notation-cli\n\
  \    name: Notation CLI\n    description: >-\n      Notation is the command-line tool that implements the Notary Project\n      specifications for signing and verifying OCI artifacts stored in\n      container registries. It supports signing with certificates stored in\n      trust stores, configuring trust policies for verification, and extends\n      to third-party key management systems via a plugin model.\n    humanURL: https://notaryproject.dev/docs/user-guides/installation/cli/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://notaryproject.dev/docs/user-guides/installation/cli/\n      - type: Getting Started\n        url: https://notaryproject.dev/docs/user-guides/installation/\n      - type: Reference\n        url: https://github.com/notaryproject/notation/blob/main/specs/notation-cli.md\n      - type: GitHubRepository\n        url: https://github.com/notaryproject/notation\n\
  \      - type: Change Log\n        url: https://github.com/notaryproject/notation/releases\n    tags:\n      - CLI\n      - OCI\n      - Signing\n      - Verification\n  - aid: notary:notation-go\n    name: notation-go Library\n    description: >-\n      notation-go is the official Go library for signing and verifying OCI\n      artifacts using the Notary Project specifications. It provides the\n      programmatic interface used by the Notation CLI and enables Go\n      applications to integrate artifact signing and verification into their\n      own workflows without invoking the CLI directly.\n    humanURL: https://github.com/notaryproject/notation-go\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://pkg.go.dev/github.com/notaryproject/notation-go\n      - type: GitHubRepository\n        url: https://github.com/notaryproject/notation-go\n    tags:\n      - Client Library\n      -\
  \ Go\n      - SDK\n      - Signing\n  - aid: notary:notation-plugin-framework\n    name: Notation Plugin Extensibility\n    description: >-\n      The Notation plugin extensibility specification defines the interface\n      that third-party plugins must implement to integrate with Notation for\n      key management, signing, and verification operations. Plugins allow\n      Notation to work with hardware security modules, cloud key management\n      services, and other external credential systems.\n    humanURL: https://github.com/notaryproject/specifications/blob/main/specs/plugin-extensibility.md\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://github.com/notaryproject/specifications/blob/main/specs/plugin-extensibility.md\n      - type: Reference\n        url: https://pkg.go.dev/github.com/notaryproject/notation-plugin-framework-go/plugin\n      - type: GitHubRepository\n      \
  \  url: https://github.com/notaryproject/notation-go\n      - type: JSONSchema\n        url: json-schema/notary-plugin-schema.json\n      - type: JSONSchema\n        url: json-schema/notary-plugin-protocol-schema.json\n    tags:\n      - Extensibility\n      - Key Management\n      - Plugin\n      - Signing\ncommon:\n  - type: Website\n    url: https://notaryproject.dev\n  - type: Documentation\n    url: https://notaryproject.dev/docs/\n  - type: Getting Started\n    url: https://notaryproject.dev/docs/user-guides/installation/\n  - type: Blog\n    url: https://notaryproject.dev/blog/\n  - type: FAQ\n    url: https://notaryproject.dev/docs/faq/\n  - type: GitHubOrganization\n    url: https://github.com/notaryproject\n  - type: GitHubRepository\n    url: https://github.com/notaryproject/notation\n  - type: Change Log\n    url: https://github.com/notaryproject/notation/releases\n  - type: JSONSchema\n    url: json-schema/notary-trust-policy-schema.json\n  - type: JSONSchema\n    url: json-schema/notary-plugin-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/notary-plugin-protocol-schema.json\n  - type: JSONSchema\n    url: json-schema/notary-signature-envelope-schema.json\n  - type: JSON-LD\n    url: json-ld/notary-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/notary/refs/heads/main/apis.yml
tags:
- Cloud Native
- Container Security
- Image Signing
- Incubating
- OCI
- Verification
url: https://notaryproject.dev
use_cases: []
---
