---
api_count: 2
apis:
- description: The CONTRIBUTORS.md format is a Markdown convention that lists project contributors and the kinds of contribution they have made. Many projects adopt the All Contributors specification, which uses emo
  name: CONTRIBUTORS.md Format
  slug: format
- description: 'The All Contributors specification defines a JSON schema (in .all-contributorsrc) plus a Markdown rendering convention that captures every contributor name, GitHub login, avatar URL, profile URL, and '
  name: All Contributors Specification
  slug: all-contributors-spec
common:
- title: ''
  type: Reference
  url: https://allcontributors.org/
- title: ''
  type: Specification
  url: https://allcontributors.org/docs/en/specification
- title: ''
  type: Documentation
  url: https://allcontributors.org/docs/en/emoji-key
- title: ''
  type: Repository
  url: https://github.com/all-contributors/all-contributors
created: '2025-01-01'
description: CONTRIBUTORS.md is an open source convention used to recognize the people and organizations that have contributed to a project. The file lists contributors by name, GitHub handle, and contribution type, ranging from code and documentation to design, testing, accessibility, and community organization. CONTRIBUTORS.md is often paired with the All Contributors specification, which standardizes contribution categories using emoji keys and supports automated table generation through the All Contributors bot.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: CONTRIBUTORS.md
skills: []
slug: contributors-md
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: contributors-md\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/contributors-md/refs/heads/main/apis.yml\nname: CONTRIBUTORS.md\nx-type: standard\ndescription: >-\n  CONTRIBUTORS.md is an open source convention used to recognize the people\n  and organizations that have contributed to a project. The file lists\n  contributors by name, GitHub handle, and contribution type, ranging from\n  code and documentation to design, testing, accessibility, and community\n  organization. CONTRIBUTORS.md is often paired with the All Contributors\n  specification, which standardizes contribution categories using emoji keys\n  and supports automated table generation through the All Contributors bot.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - All Contributors\n  - Attribution\n  - Community\n  - Documentation\n  - GitHub\n  - Markdown\n  - Open Source\n  - Recognition\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: contributors-md:format\n    name: CONTRIBUTORS.md Format\n    tags:\n      - Attribution\n      - Convention\n      - Markdown\n      - Recognition\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://allcontributors.org/\n    properties:\n      - url: https://allcontributors.org/\n        type: Reference\n      - url: https://allcontributors.org/docs/en/specification\n        type: Specification\n      - url: https://allcontributors.org/docs/en/emoji-key\n        type: Documentation\n      - url: https://github.com/all-contributors/all-contributors\n        type: Repository\n    description: >-\n      The CONTRIBUTORS.md format is a Markdown convention that lists project\n      contributors and the kinds of contribution they have made. Many projects\n      adopt the All Contributors specification, which uses emoji keys to\n      classify contributions, an embedded HTML table to render the\n      contributor\
  \ list, and a .all-contributorsrc JSON config file consumed\n      by the All Contributors bot to automate updates.\n    x-features:\n      - Recognizes non-code contributions including design, docs, and review\n      - Compatible with the All Contributors emoji key specification\n      - Automatable through the All Contributors GitHub App or CLI\n      - Renders as an HTML table with avatars and contribution badges\n      - Pairs with CONTRIBUTING.md and CODE_OF_CONDUCT.md\n    x-useCases:\n      - Public attribution of every project contributor\n      - Recognizing accessibility, translation, and design contributions\n      - Automating contributor table updates via @all-contributors bot\n      - Demonstrating an inclusive open source community to sponsors\n      - Tracking contribution categories beyond commit history\n\n  - aid: contributors-md:all-contributors-spec\n    name: All Contributors Specification\n    tags:\n      - Attribution\n      - Specification\n      - Standardization\n\
  \    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://allcontributors.org/docs/en/specification\n    properties:\n      - url: https://allcontributors.org/docs/en/specification\n        type: Specification\n      - url: https://allcontributors.org/docs/en/emoji-key\n        type: Documentation\n      - url: https://github.com/all-contributors/all-contributors-cli\n        type: Repository\n      - url: https://allcontributors.org/docs/en/cli/usage\n        type: Documentation\n    description: >-\n      The All Contributors specification defines a JSON schema (in\n      .all-contributorsrc) plus a Markdown rendering convention that captures\n      every contributor name, GitHub login, avatar URL, profile URL, and the\n      list of contribution types using a defined emoji key. Tooling can\n      regenerate the contributor table on demand and synchronize updates back\n      into both .all-contributorsrc and CONTRIBUTORS.md or README.md.\n\
  \    x-features:\n      - Defines a contribution type emoji key with 30+ categories\n      - JSON config schema in .all-contributorsrc as machine readable source\n      - CLI plus GitHub bot for adding contributors with a comment command\n      - Backed by an OSS community since 2017\n    x-useCases:\n      - Standardizing contributor recognition across multiple projects\n      - Auditing contribution categories programmatically\n      - Generating contributor tables in README or CONTRIBUTORS files\n      - Recognizing accessibility, infrastructure, and security contributions\n\ncommon:\n  - type: Reference\n    url: https://allcontributors.org/\n  - type: Specification\n    url: https://allcontributors.org/docs/en/specification\n  - type: Documentation\n    url: https://allcontributors.org/docs/en/emoji-key\n  - type: Repository\n    url: https://github.com/all-contributors/all-contributors\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/contributors-md/refs/heads/main/apis.yml
tags:
- All Contributors
- Attribution
- Community
- Documentation
- GitHub
- Markdown
- Open Source
- Recognition
url: https://raw.githubusercontent.com/api-evangelist/contributors-md/refs/heads/main/apis.yml
use_cases: []
---
