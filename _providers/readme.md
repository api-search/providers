---
api_count: 2
api_specs:
- filename: readme-openapi.yml
  format: yaml
  label: ReadMe API
  slug: readme-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/openapi/readme-openapi.yml
- filename: readme-developer-metrics-openapi.yml
  format: yaml
  label: ReadMe Developer Metrics API
  slug: developer-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/openapi/readme-developer-metrics-openapi.yml
apis:
- description: The ReadMe API lets you programmatically control your ReadMe developer hub. You can manage API definitions, API reference pages, guides, changelogs, custom pages, categories, branches, images, recipes
  name: ReadMe API
  slug: readme-api
- description: The ReadMe Developer Metrics API provides endpoints for sending API logs and retrieving analytics data including page quality scores, page view statistics, and search analytics. It powers the Develope
  name: ReadMe Developer Metrics API
  slug: developer-metrics-api
common:
- title: ''
  type: Portal
  url: https://readme.com
- title: ''
  type: GettingStarted
  url: https://docs.readme.com/main/docs/quickstart
- title: ''
  type: Documentation
  url: https://docs.readme.com
- title: ''
  type: Pricing
  url: https://readme.com/pricing
- title: ''
  type: SignUp
  url: https://dash.readme.com/signup
- title: ''
  type: Login
  url: https://dash.readme.com/login
- title: ''
  type: Blog
  url: https://readme.com/blog
- title: ''
  type: ChangeLog
  url: https://docs.readme.com/main/changelog
- title: ''
  type: About
  url: https://readme.com/about
- title: ''
  type: Status
  url: https://www.readmestatus.com
- title: ''
  type: TermsOfService
  url: https://readme.com/tos
- title: ''
  type: PrivacyPolicy
  url: https://readme.com/privacy
- title: ''
  type: GitHubOrg
  url: https://github.com/readmeio
created: '2025-01-08'
description: ReadMe is a platform that helps companies create and manage their API documentation. With ReadMe, companies can easily create interactive and informative documentation that is user-friendly and visually appealing. By providing tools for developers to easily access and understand API documentation, ReadMe helps companies improve developer onboarding, increase API adoption, and drive developer satisfaction.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: ReadMe
skills: []
slug: readme
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: readme\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/apis.yml\napis:\n  - aid: readme:readme-api\n    name: ReadMe API\n    tags:\n      - Documentation\n      - Developer Hub\n      - Content Management\n    humanURL: https://docs.readme.com/main/reference/intro-to-the-readme-api\n    baseURL: https://api.readme.com/v2\n    properties:\n      - url: https://docs.readme.com/main/reference/intro-to-the-readme-api\n        type: Documentation\n      - url: https://docs.readme.com/main/reference/authentication\n        type: Authentication\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/openapi/readme-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ReadMe API lets you programmatically control your ReadMe developer\n      hub. You can manage API definitions, API reference pages, guides,\n      changelogs, custom pages, categories, branches, images, recipes, and\n  \
  \    search. Authentication uses a Bearer API key.\n  - aid: readme:developer-metrics-api\n    name: ReadMe Developer Metrics API\n    tags:\n      - Analytics\n      - Metrics\n      - Logging\n    humanURL: https://readme.com/developer-dashboard\n    baseURL: https://metrics.readme.io/v1\n    properties:\n      - url: https://readme.com/developer-dashboard\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/openapi/readme-developer-metrics-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ReadMe Developer Metrics API provides endpoints for sending API logs\n      and retrieving analytics data including page quality scores, page view\n      statistics, and search analytics. It powers the Developer Dashboard\n      where you can investigate API usage by key or email and debug requests\n      in real time.\nname: ReadMe\ntags:\n  - Documentation\n  - Platform\n  - Portals\n  - Developer Hub\n \
  \ - Analytics\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nposition: Consumer\nsegments:\n  - Documentation\ndescription: >-\n  ReadMe is a platform that helps companies create and manage their API\n  documentation. With ReadMe, companies can easily create interactive and\n  informative documentation that is user-friendly and visually appealing. By\n  providing tools for developers to easily access and understand API\n  documentation, ReadMe helps companies improve developer onboarding, increase\n  API adoption, and drive developer satisfaction.\ncommon:\n  - url: https://readme.com\n    type: Portal\n  - url: https://docs.readme.com/main/docs/quickstart\n    type: GettingStarted\n  - url: https://docs.readme.com\n    type: Documentation\n  - url: https://readme.com/pricing\n    type: Pricing\n  - url: https://dash.readme.com/signup\n    type: SignUp\n  - url: https://dash.readme.com/login\n\
  \    type: Login\n  - url: https://readme.com/blog\n    type: Blog\n  - url: https://docs.readme.com/main/changelog\n    type: ChangeLog\n  - url: https://readme.com/about\n    type: About\n  - url: https://www.readmestatus.com\n    type: Status\n  - url: https://readme.com/tos\n    type: TermsOfService\n  - url: https://readme.com/privacy\n    type: PrivacyPolicy\n  - url: https://github.com/readmeio\n    type: GitHubOrg\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/apis.yml
tags:
- Documentation
- Platform
- Portals
- Developer Hub
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/readme/refs/heads/main/apis.yml
use_cases: []
---
