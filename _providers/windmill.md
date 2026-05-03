---
api_count: 1
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Windmill API
  slug: windmill-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/windmill-labs/windmill/main/backend/windmill-api/openapi.yaml
apis:
- description: The Windmill API provides programmatic access to the Windmill developer platform, enabling management of scripts, flows, apps, resources, variables, schedules, jobs, users, workspaces, and webhooks. I
  name: Windmill API
  slug: windmill-api
common:
- title: ''
  type: Portal
  url: https://www.windmill.dev
- title: ''
  type: Documentation
  url: https://www.windmill.dev/docs/intro
- title: ''
  type: GettingStarted
  url: https://www.windmill.dev/docs/getting_started/how_to_use_windmill
- title: ''
  type: Pricing
  url: https://www.windmill.dev/pricing
- title: ''
  type: Plans
  url: https://www.windmill.dev/docs/misc/plans_details
- title: ''
  type: Blog
  url: https://www.windmill.dev/blog
- title: ''
  type: Changelog
  url: https://www.windmill.dev/changelog
- title: ''
  type: Roadmap
  url: https://www.windmill.dev/roadmap
- title: ''
  type: Login
  url: https://app.windmill.dev/user/login
- title: ''
  type: GitHubOrg
  url: https://github.com/windmill-labs
- title: ''
  type: GitHubRepo
  url: https://github.com/windmill-labs/windmill
- title: ''
  type: IntegrationHub
  url: https://hub.windmill.dev
- title: ''
  type: StatusPage
  url: https://windmill.betteruptime.com/
- title: ''
  type: Discord
  url: https://discord.com/invite/V7PM2YHsPB
- title: ''
  type: CommunityForum
  url: https://questions.windmill.dev/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/windmill-labs/windmill/main/backend/windmill-api/openapi.yaml
- title: ''
  type: TermsOfService
  url: https://www.windmill.dev/terms_of_service
- title: ''
  type: PrivacyPolicy
  url: https://www.windmill.dev/privacy_policy
- title: ''
  type: LicenseTerms
  url: https://www.windmill.dev/terms
- title: ''
  type: TrustCenter
  url: https://trust.windmill.dev
- title: ''
  type: Careers
  url: https://www.windmill.dev/careers
- title: ''
  type: Partners
  url: https://www.windmill.dev/partners
- title: ''
  type: CaseStudies
  url: https://www.windmill.dev/case-studies
- title: ''
  type: Brand
  url: https://www.windmill.dev/brand
created: '2026-03-03'
description: Windmill is an open-source developer platform and workflow engine for turning scripts into webhooks, workflows, and internal apps. It supports TypeScript, Python, Go, PHP, Bash, C#, SQL, and Rust, and serves as an open-source alternative to Retool, Airflow, and Temporal for building comprehensive internal tools including endpoints, workflows, and UIs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-03'
name: Windmill
skills: []
slug: windmill
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: windmill\nname: Windmill\nsegments:\n  - ProCode_API_Composition\n  - Workflows\ndescription: >-\n  Windmill is an open-source developer platform and workflow engine for turning\n  scripts into webhooks, workflows, and internal apps. It supports TypeScript,\n  Python, Go, PHP, Bash, C#, SQL, and Rust, and serves as an open-source\n  alternative to Retool, Airflow, and Temporal for building comprehensive\n  internal tools including endpoints, workflows, and UIs.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Internal Tools\n  - Open Source\n  - ProCode_API_Composition\n  - Scripts\n  - Webhooks\n  - Workflow Engine\n  - Workflows\ncreated: '2026-03-03'\nmodified: '2026-03-03'\nurl: https://raw.githubusercontent.com/api-evangelist/windmill/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: windmill:windmill-api\n    name: Windmill API\n\
  \    description: >-\n      The Windmill API provides programmatic access to the Windmill developer\n      platform, enabling management of scripts, flows, apps, resources,\n      variables, schedules, jobs, users, workspaces, and webhooks. It follows\n      the OpenAPI 3.0.3 specification and powers all interactions with the\n      Windmill platform.\n    humanURL: https://www.windmill.dev/docs/intro\n    baseURL: https://app.windmill.dev/api\n    tags:\n      - Automation\n      - Internal Tools\n      - ProCode_API_Composition\n      - Scripts\n      - Webhooks\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://www.windmill.dev/docs/intro\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/windmill-labs/windmill/main/backend/windmill-api/openapi.yaml\n      - type: APIReferenceDocumentation\n        url: https://app.windmill.dev/openapi.html\n      - type: GettingStarted\n        url: https://www.windmill.dev/docs/getting_started/how_to_use_windmill\n\
  \      - type: Authentication\n        url: https://www.windmill.dev/docs/core_concepts/authentification\n      - type: HTTPRoutes\n        url: https://www.windmill.dev/docs/core_concepts/http_routing\n      - type: CLI\n        url: https://www.windmill.dev/docs/advanced/cli\n      - type: SelfHosting\n        url: https://www.windmill.dev/docs/advanced/self_host\n      - type: TypeScriptSDK\n        url: https://www.windmill.dev/docs/advanced/clients/ts_client\n      - type: PythonSDK\n        url: https://www.windmill.dev/docs/advanced/clients/python_client\ncommon:\n  - type: Portal\n    url: https://www.windmill.dev\n  - type: Documentation\n    url: https://www.windmill.dev/docs/intro\n  - type: GettingStarted\n    url: https://www.windmill.dev/docs/getting_started/how_to_use_windmill\n  - type: Pricing\n    url: https://www.windmill.dev/pricing\n  - type: Plans\n    url: https://www.windmill.dev/docs/misc/plans_details\n  - type: Blog\n    url: https://www.windmill.dev/blog\n \
  \ - type: Changelog\n    url: https://www.windmill.dev/changelog\n  - type: Roadmap\n    url: https://www.windmill.dev/roadmap\n  - type: Login\n    url: https://app.windmill.dev/user/login\n  - type: GitHubOrg\n    url: https://github.com/windmill-labs\n  - type: GitHubRepo\n    url: https://github.com/windmill-labs/windmill\n  - type: IntegrationHub\n    url: https://hub.windmill.dev\n  - type: StatusPage\n    url: https://windmill.betteruptime.com/\n  - type: Discord\n    url: https://discord.com/invite/V7PM2YHsPB\n  - type: CommunityForum\n    url: https://questions.windmill.dev/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/windmill-labs/windmill/main/backend/windmill-api/openapi.yaml\n  - type: TermsOfService\n    url: https://www.windmill.dev/terms_of_service\n  - type: PrivacyPolicy\n    url: https://www.windmill.dev/privacy_policy\n  - type: LicenseTerms\n    url: https://www.windmill.dev/terms\n  - type: TrustCenter\n    url: https://trust.windmill.dev\n  - type:\
  \ Careers\n    url: https://www.windmill.dev/careers\n  - type: Partners\n    url: https://www.windmill.dev/partners\n  - type: CaseStudies\n    url: https://www.windmill.dev/case-studies\n  - type: Brand\n    url: https://www.windmill.dev/brand\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/windmill/refs/heads/main/apis.yml
tags:
- Automation
- Internal Tools
- Open Source
- ProCode_API_Composition
- Scripts
- Webhooks
- Workflow Engine
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/windmill/refs/heads/main/apis.yml
use_cases: []
---
