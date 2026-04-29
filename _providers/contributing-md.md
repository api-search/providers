---
api_count: 2
apis:
- description: 'The CONTRIBUTING.md format is an unstructured Markdown convention that documents how to contribute to a project. GitHub recognizes the file in three locations checked in priority order: the .github fo'
  name: CONTRIBUTING.md Format
  slug: format
- description: CONTRIBUTING.md is one of several community health files GitHub looks for when scoring a repository community profile. Sibling files include README.md, LICENSE, CODE_OF_CONDUCT.md, SECURITY.md, SUPPOR
  name: CONTRIBUTING.md Related Conventions
  slug: related-conventions
common:
- title: ''
  type: Documentation
  url: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors
- title: ''
  type: Reference
  url: https://contributing.md/
- title: ''
  type: Guide
  url: https://opensource.guide/how-to-contribute/
- title: ''
  type: Example
  url: https://github.com/github/docs/blob/main/CONTRIBUTING.md
created: '2025-01-01'
description: CONTRIBUTING.md is a community health convention used by open source projects on GitHub and other platforms to document how external contributors can participate. The file communicates contribution guidelines, pull request processes, issue reporting procedures, coding standards, development setup, testing expectations, and code of conduct references. GitHub recognizes CONTRIBUTING.md placed in the repository root, the .github folder, or the docs folder, and surfaces a link to it whenever a contributor opens a new issue or pull request.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: CONTRIBUTING.md
skills: []
slug: contributing-md
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: contributing-md\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/contributing-md/refs/heads/main/apis.yml\nname: CONTRIBUTING.md\nx-type: standard\ndescription: >-\n  CONTRIBUTING.md is a community health convention used by open source projects\n  on GitHub and other platforms to document how external contributors can\n  participate. The file communicates contribution guidelines, pull request\n  processes, issue reporting procedures, coding standards, development setup,\n  testing expectations, and code of conduct references. GitHub recognizes\n  CONTRIBUTING.md placed in the repository root, the .github folder, or the\n  docs folder, and surfaces a link to it whenever a contributor opens a new\n  issue or pull request.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code Of Conduct\n  - Collaboration\n  - Community Health\n  - Developer Guidelines\n  - Documentation\n  - GitHub\n  - Markdown\n  - Open Source\n\
  \  - Pull Requests\n  - Repository\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: contributing-md:format\n    name: CONTRIBUTING.md Format\n    tags:\n      - Community Health\n      - Convention\n      - Documentation\n      - Markdown\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors\n    properties:\n      - url: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors\n        type: Documentation\n      - url: https://contributing.md/\n        type: Reference\n      - url: https://opensource.guide/how-to-contribute/\n        type: Guide\n      - url: https://github.com/github/docs/blob/main/CONTRIBUTING.md\n        type: Example\n    description: >-\n      The CONTRIBUTING.md\
  \ format is an unstructured Markdown convention that\n      documents how to contribute to a project. GitHub recognizes the file in\n      three locations checked in priority order: the .github folder, the\n      repository root, and the docs folder. When a contributor opens an issue\n      or pull request, GitHub automatically links to the file. Typical sections\n      include contribution workflow, development setup, branch and commit\n      conventions, code style, testing, pull request review process, code of\n      conduct reference, and licensing terms.\n    x-features:\n      - Triggers contribution prompt on new issues and pull requests\n      - Recognized by GitHub, GitLab, Bitbucket, and Gitea\n      - Pairs with CODE_OF_CONDUCT.md, ISSUE_TEMPLATE, and PULL_REQUEST_TEMPLATE\n      - Can live in repository root, .github, or docs directory\n      - Often references a Developer Certificate of Origin or CLA process\n    x-useCases:\n      - Onboarding first-time contributors to an\
  \ open source project\n      - Documenting fork-and-pull workflow expectations\n      - Defining branch naming, commit message, and review conventions\n      - Specifying local development setup and required toolchains\n      - Linking to community resources such as Discord, mailing lists, or forums\n\n  - aid: contributing-md:related-conventions\n    name: CONTRIBUTING.md Related Conventions\n    tags:\n      - Community Health\n      - Convention\n      - GitHub\n      - Open Source\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions\n    properties:\n      - url: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories\n        type: Documentation\n      - url: https://www.contributor-covenant.org/\n        type: Reference\n      - url: https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests\n\
  \        type: Documentation\n    description: >-\n      CONTRIBUTING.md is one of several community health files GitHub looks for\n      when scoring a repository community profile. Sibling files include\n      README.md, LICENSE, CODE_OF_CONDUCT.md, SECURITY.md, SUPPORT.md, and\n      issue and pull request templates. Together these conventions establish a\n      well-formed, welcoming open source project that lowers the barrier for\n      new contributors.\n    x-features:\n      - Recognized as part of the GitHub community profile checklist\n      - Composable with CODE_OF_CONDUCT.md, SECURITY.md, and SUPPORT.md\n      - Compatible with All Contributors specification for recognition\n      - Often pairs with .github/ISSUE_TEMPLATE and PULL_REQUEST_TEMPLATE.md\n    x-useCases:\n      - Completing the GitHub community profile health checklist\n      - Defining the entire community health surface for an organization\n      - Standardizing contribution conventions across many repositories\n\
  \ncommon:\n  - type: Documentation\n    url: https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors\n  - type: Reference\n    url: https://contributing.md/\n  - type: Guide\n    url: https://opensource.guide/how-to-contribute/\n  - type: Example\n    url: https://github.com/github/docs/blob/main/CONTRIBUTING.md\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/contributing-md/refs/heads/main/apis.yml
tags:
- Code Of Conduct
- Collaboration
- Community Health
- Developer Guidelines
- Documentation
- GitHub
- Markdown
- Open Source
- Pull Requests
- Repository
url: https://raw.githubusercontent.com/api-evangelist/contributing-md/refs/heads/main/apis.yml
use_cases: []
---
