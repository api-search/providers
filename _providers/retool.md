---
api_count: 3
api_specs:
- filename: retool-management-api-openapi.yml
  format: yaml
  label: Retool Management API
  slug: retool-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/openapi/retool-management-api-openapi.yml
apis:
- description: 'The Retool Management API enables administrators to programmatically manage users, groups, permissions, apps, resources, workflows, folders, spaces, and source control integrations. Authenticated via '
  name: Retool Management API
  slug: retool-management-api
- description: Retool implements a subset of the SCIM 2.0 API for automated user provisioning and group mapping through identity providers like Okta and Azure Active Directory (Entra ID). Available on Enterprise pla
  name: Retool SCIM 2.0 API
  slug: retool-scim-api
- description: Retool's low-code platform provides a visual development environment with 100+ pre-built components, native connectors to 70+ data sources, AI-powered app generation (AppGen), workflow automation, bui
  name: Retool Platform
  slug: retool-platform
capabilities:
- description: 'Unified workflow capability for managing a Retool organization through the Management API. Enables IT administrators and platform teams to automate user provisioning, group membership, app lifecycle, '
  name: Retool Organization Administration
  slug: org-administration
common:
- title: ''
  type: Website
  url: https://retool.com/
- title: ''
  type: Documentation
  url: https://docs.retool.com/
- title: ''
  type: APIReference
  url: https://docs.retool.com/reference/api/v2
- title: ''
  type: Blog
  url: https://retool.com/blog
- title: ''
  type: Changelog
  url: https://retool.com/changelog
- title: ''
  type: Status
  url: https://status.retool.com
- title: ''
  type: Support
  url: https://support.retool.com
- title: ''
  type: Community
  url: https://community.retool.com
- title: ''
  type: GitHub
  url: https://github.com/tryretool
- title: ''
  type: Pricing
  url: https://retool.com/pricing
- title: ''
  type: Login
  url: https://login.retool.com
- title: ''
  type: Twitter
  url: https://twitter.com/retool
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tryretool
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/openapi/retool-management-api-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/vocabulary/retool-vocabulary.yml
created: '2025-01-08'
description: Retool is a low-code platform for building internal tools, dashboards, and admin panels quickly using pre-built UI components that connect to any database or API. Retool provides a management REST API for programmatically administering users, groups, apps, resources, permissions, and source control integrations. It supports enterprise features including SSO, SCIM 2.0 provisioning, self-hosting, and AI-powered app generation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Retool Context
  property_count: 13
  slug: retool-context
layout: provider
modified: '2026-05-02'
name: Retool
rules:
- name: Retool API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 2
    info: 0
    warn: 4
  slug: retool-management-api-rules
skills: []
slug: retool
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: retool\nname: Retool\ndescription: >-\n  Retool is a low-code platform for building internal tools, dashboards, and\n  admin panels quickly using pre-built UI components that connect to any database\n  or API. Retool provides a management REST API for programmatically administering\n  users, groups, apps, resources, permissions, and source control integrations.\n  It supports enterprise features including SSO, SCIM 2.0 provisioning, self-hosting,\n  and AI-powered app generation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Admin Panel\n  - Dashboard\n  - Internal Tools\n  - Low Code\n  - No Code\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: retool:retool-management-api\n    name: Retool Management API\n    description: >-\n      The Retool Management API enables administrators\
  \ to programmatically manage\n      users, groups, permissions, apps, resources, workflows, folders, spaces,\n      and source control integrations. Authenticated via Bearer token. Supports\n      both the native v1 API and SCIM 2.0 for enterprise identity provider integration.\n    humanURL: https://docs.retool.com/reference/api/v2\n    tags:\n      - Administration\n      - Apps\n      - Groups\n      - Permissions\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.retool.com/reference/api/v2\n      - type: Authentication\n        url: https://docs.retool.com/org-users/concepts/retool-api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/openapi/retool-management-api-openapi.yml\n  - aid: retool:retool-scim-api\n    name: Retool SCIM 2.0 API\n    description: >-\n      Retool implements a subset of the SCIM 2.0 API for automated user\n      provisioning and group mapping through identity providers\
  \ like Okta\n      and Azure Active Directory (Entra ID). Available on Enterprise plan.\n    humanURL: https://docs.retool.com/org-users/concepts/scim\n    tags:\n      - Enterprise\n      - Identity\n      - Okta\n      - Provisioning\n      - SCIM\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://docs.retool.com/org-users/concepts/scim\n  - aid: retool:retool-platform\n    name: Retool Platform\n    description: >-\n      Retool's low-code platform provides a visual development environment\n      with 100+ pre-built components, native connectors to 70+ data sources,\n      AI-powered app generation (AppGen), workflow automation, built-in database,\n      and mobile app support. Supports self-hosted and cloud deployment options\n      with ISO 27001 and SOC 2 compliance.\n    humanURL: https://retool.com/\n    tags:\n      - AI\n      - Dashboard\n      - Internal Tools\n      - Low Code\n      - Mobile\n      - Workflows\n    properties:\n      - type:\
  \ Documentation\n        url: https://docs.retool.com/\n      - type: GettingStarted\n        url: https://docs.retool.com/quickstarts\n      - type: Pricing\n        url: https://retool.com/pricing\ncommon:\n  - type: Website\n    url: https://retool.com/\n  - type: Documentation\n    url: https://docs.retool.com/\n  - type: APIReference\n    url: https://docs.retool.com/reference/api/v2\n  - type: Blog\n    url: https://retool.com/blog\n  - type: Changelog\n    url: https://retool.com/changelog\n  - type: Status\n    url: https://status.retool.com\n  - type: Support\n    url: https://support.retool.com\n  - type: Community\n    url: https://community.retool.com\n  - type: GitHub\n    url: https://github.com/tryretool\n  - type: Pricing\n    url: https://retool.com/pricing\n  - type: Login\n    url: https://login.retool.com\n  - type: Twitter\n    url: https://twitter.com/retool\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tryretool\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/openapi/retool-management-api-openapi.yml\n\
  \  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/vocabulary/retool-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/apis.yml
tags:
- Admin Panel
- Dashboard
- Internal Tools
- Low Code
- No Code
url: https://raw.githubusercontent.com/api-evangelist/retool/refs/heads/main/apis.yml
use_cases: []
---
