---
api_count: 3
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
common:
- title: ''
  type: Website
  url: https://theupdateframework.io/
- title: ''
  type: Documentation
  url: https://theupdateframework.io/docs/
- title: ''
  type: Getting Started
  url: https://theupdateframework.io/docs/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/theupdateframework
- title: ''
  type: GitHubRepository
  url: https://github.com/theupdateframework/python-tuf
- title: ''
  type: Blog
  url: https://theupdateframework.io/resources/news/
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
created: '2026-03-16'
description: TUF (The Update Framework) is a CNCF graduated framework for securing software update systems. It provides a specification for how software repositories should be structured and how clients should verify updates to protect against key compromise, rollback attacks, and mix-and-match attacks. TUF is used by many package managers and update systems including PyPI, Sigstore, and various Linux distributions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Tuf Context
  property_count: 12
  slug: tuf-context
layout: provider
modified: '2026-03-18'
name: The Update Framework (TUF)
skills: []
slug: tuf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tuf\nname: The Update Framework (TUF)\ndescription: >-\n  TUF (The Update Framework) is a CNCF graduated framework for securing\n  software update systems. It provides a specification for how software\n  repositories should be structured and how clients should verify updates\n  to protect against key compromise, rollback attacks, and mix-and-match\n  attacks. TUF is used by many package managers and update systems including\n  PyPI, Sigstore, and various Linux distributions.\nurl: https://theupdateframework.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Graduated\n  - Security\n  - Software Updates\n  - Supply Chain\n  - Verification\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: tuf:tuf-spec\n    name: TUF Repository Specification\n    description: >-\n      The TUF specification defines the structure of update repositories\n      including\
  \ the root, targets, snapshot, and timestamp metadata files.\n      Each metadata file has a defined schema with signatures, expiration\n      dates, and delegation rules. Clients follow a defined verification\n      workflow to securely resolve and download updates while protecting\n      against various attack vectors.\n    humanURL: https://theupdateframework.github.io/specification/latest/\n    properties:\n      - type: Documentation\n        url: https://theupdateframework.github.io/specification/latest/\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/specification\n      - type: JSONSchema\n        url: json-schema/tuf-root-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/tuf-targets-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/tuf-snapshot-metadata-schema.json\n      - type: JSONSchema\n        url: json-schema/tuf-timestamp-metadata-schema.json\n    tags:\n      - Repository Metadata\n    \
  \  - Specification\n      - Verification\n  - aid: tuf:python-tuf\n    name: TUF Python Reference Implementation\n    description: >-\n      The official Python reference implementation of The Update Framework (TUF)\n      specification. Provides a metadata API for reading and writing TUF metadata\n      files, an ngclient API implementing the TUF client update workflow, and a\n      repository library for building TUF-compliant software repositories.\n    humanURL: https://theupdateframework.readthedocs.io/en/stable/\n    properties:\n      - type: Documentation\n        url: https://theupdateframework.readthedocs.io/en/stable/\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/python-tuf\n    tags:\n      - Client Library\n      - Python\n      - Security\n      - Software Updates\n      - Supply Chain\n  - aid: tuf:go-tuf\n    name: TUF Go Implementation\n    description: >-\n      A Go implementation of The Update Framework (TUF), heavily influenced\
  \ by\n      python-tuf's design. Provides metadata, TrustedMetadata, and Updater\n      packages implementing the TUF client workflow and specification-compliant\n      metadata handling, as well as multi-repository support via TAP 4.\n    humanURL: https://github.com/theupdateframework/go-tuf\n    properties:\n      - type: Documentation\n        url: https://github.com/theupdateframework/go-tuf\n      - type: GitHubRepository\n        url: https://github.com/theupdateframework/go-tuf\n    tags:\n      - Client Library\n      - Go\n      - Security\n      - Software Updates\n      - Supply Chain\ncommon:\n  - type: Website\n    url: https://theupdateframework.io/\n  - type: Documentation\n    url: https://theupdateframework.io/docs/\n  - type: Getting Started\n    url: https://theupdateframework.io/docs/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/theupdateframework\n  - type: GitHubRepository\n    url: https://github.com/theupdateframework/python-tuf\n\
  \  - type: Blog\n    url: https://theupdateframework.io/resources/news/\n  - type: JSON-LD\n    url: json-ld/tuf-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tuf-root-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-targets-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-snapshot-metadata-schema.json\n  - type: JSONSchema\n    url: json-schema/tuf-timestamp-metadata-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tuf/refs/heads/main/apis.yml
tags:
- Cloud Native
- Graduated
- Security
- Software Updates
- Supply Chain
- Verification
url: https://theupdateframework.io
use_cases: []
---
