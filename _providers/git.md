---
api_count: 4
api_specs:
- filename: rest-api-description
  format: yaml
  label: GitHub API
  slug: github
  spec_type: OpenAPI
  url: https://github.com/github/rest-api-description
- filename: openapi.yaml
  format: yaml
  label: GitLab API
  slug: gitlab
  spec_type: OpenAPI
  url: https://docs.gitlab.com/ee/api/openapi/openapi.yaml
- filename: swagger
  format: yaml
  label: Gitea API
  slug: gitea
  spec_type: OpenAPI
  url: https://gitea.io/api/swagger
apis:
- description: Git command-line interface for version control operations.
  name: Git CLI
  slug: git-cli
- description: RESTful API for GitHub's Git hosting platform.
  name: GitHub API
  slug: github
- description: RESTful API for GitLab's Git repository management.
  name: GitLab API
  slug: gitlab
- description: RESTful API for Gitea's self-hosted Git service.
  name: Gitea API
  slug: gitea
common:
- title: ''
  type: Website
  url: https://git-scm.com/
- title: ''
  type: Documentation
  url: https://git-scm.com/doc
created: '2024-01-01'
description: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Git
skills: []
slug: git
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: git\nname: Git\ndescription: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nposition: Consumer\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/git/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ntags:\n  - Distributed\n  - Git\n  - Open Source\n  - Source Code Management\n  - Version Control\napis:\n  - aid: git:git-cli\n    name: Git CLI\n    description: >-\n      Git command-line interface for version control operations.\n    humanURL: https://git-scm.com/docs\n    tags:\n      - Version Control\n    properties:\n      - type: Documentation\n        url: https://git-scm.com/doc\n      - type: Reference\n        url:\
  \ https://git-scm.com/docs\n  - aid: git:github\n    name: GitHub API\n    description: >-\n      RESTful API for GitHub's Git hosting platform.\n    humanURL: https://docs.github.com/en/rest\n    baseURL: https://api.github.com\n    tags:\n      - Git\n      - GitHub\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest\n      - type: OpenAPI\n        url: https://github.com/github/rest-api-description\n      - type: Authentication\n        url: https://docs.github.com/en/rest/authentication\n  - aid: git:gitlab\n    name: GitLab API\n    description: >-\n      RESTful API for GitLab's Git repository management.\n    humanURL: https://docs.gitlab.com/ee/api/\n    baseURL: https://gitlab.com/api/v4\n    tags:\n      - Git\n      - GitLab\n    properties:\n      - type: Documentation\n        url: https://docs.gitlab.com/ee/api/\n      - type: OpenAPI\n        url: https://docs.gitlab.com/ee/api/openapi/openapi.yaml\n      - type: Authentication\n \
  \       url: https://docs.gitlab.com/ee/api/rest/index.html#authentication\n  - aid: git:gitea\n    name: Gitea API\n    description: >-\n      RESTful API for Gitea's self-hosted Git service.\n    humanURL: https://docs.gitea.io/en-us/api-usage/\n    tags:\n      - Git\n      - Gitea\n      - Self-hosted\n    properties:\n      - type: Documentation\n        url: https://docs.gitea.io/en-us/api-usage/\n      - type: OpenAPI\n        url: https://gitea.io/api/swagger\ncommon:\n  - type: Website\n    url: https://git-scm.com/\n  - type: Documentation\n    url: https://git-scm.com/doc\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/git/refs/heads/main/apis.yml
tags:
- Distributed
- Git
- Open Source
- Source Code Management
- Version Control
url: https://raw.githubusercontent.com/api-evangelist/git/refs/heads/main/apis.yml
use_cases: []
---
