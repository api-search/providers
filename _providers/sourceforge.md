---
api_count: 1
api_specs:
- filename: sourceforge-allura-openapi.yml
  format: yaml
  label: SourceForge Allura API
  slug: sourceforge-allura-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/openapi/sourceforge-allura-openapi.yml
apis:
- description: The SourceForge REST API built on Apache Allura provides programmatic access to project management, wiki pages, issue trackers, discussion forums, blogs, and administrative functions including webhook
  name: SourceForge Allura API
  slug: sourceforge-allura-api
capabilities:
- description: Unified capability for managing open source projects on SourceForge. Enables project maintainers, contributors, and community managers to programmatically manage issues, wikis, discussions, blogs, and
  name: SourceForge Project Management
  slug: project-management
common:
- title: ''
  type: Portal
  url: https://sourceforge.net/p/forge/documentation/API/
- title: ''
  type: Documentation
  url: https://sourceforge.net/p/forge/documentation/
- title: ''
  type: Website
  url: https://sourceforge.net/
- title: ''
  type: GitHub Org
  url: https://github.com/apache/allura
- title: ''
  type: API Documentation
  url: https://sourceforge.net/api-docs/
- title: ''
  type: OAuth Portal
  url: https://sourceforge.net/auth/oauth/
- title: ''
  type: Webhooks Documentation
  url: https://forge-allura.apache.org/p/allura/wiki/Webhooks/
- title: ''
  type: Support
  url: https://sourceforge.net/p/forge/site-support/
- title: ''
  type: Blog
  url: https://sourceforge.net/blog/
- title: ''
  type: Status
  url: https://sourceforge.net/p/forge/site-support/
- title: ''
  type: Terms of Use
  url: https://sourceforge.net/p/forge/documentation/Terms%20of%20Use/
created: '2026-03-16'
description: SourceForge is a web-based platform for hosting, managing, and distributing open source software projects. Built on the Apache Allura platform, SourceForge provides project management tools including wiki, issue tracking, discussion forums, blogs, file releases, code repositories (Git, SVN, Mercurial), and a REST API for programmatic access to all project resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Sourceforge Context
  property_count: 12
  slug: sourceforge-context
layout: provider
modified: '2026-05-02'
name: SourceForge
rules:
- name: SourceForge API Rules
  rule_count: 12
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 7
  slug: sourceforge-rules
skills: []
slug: sourceforge
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sourceforge\nname: SourceForge\ndescription: >-\n  SourceForge is a web-based platform for hosting, managing, and distributing\n  open source software projects. Built on the Apache Allura platform, SourceForge\n  provides project management tools including wiki, issue tracking, discussion forums,\n  blogs, file releases, code repositories (Git, SVN, Mercurial), and a REST API for\n  programmatic access to all project resources.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Open Source\n  - Developer Tools\n  - Project Management\n  - Code Hosting\n  - Collaboration\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sourceforge:sourceforge-allura-api\n    name: SourceForge Allura API\n    description: >-\n      The SourceForge REST API\
  \ built on Apache Allura provides programmatic access\n      to project management, wiki pages, issue trackers, discussion forums, blogs,\n      and administrative functions including webhooks. All endpoints follow the\n      /rest/p/{project}/{tool} path pattern with OAuth 2.0 and OAuth 1.0 authentication.\n    humanURL: https://sourceforge.net/p/forge/documentation/Allura%20API/\n    baseURL: https://sourceforge.net\n    tags:\n      - Projects\n      - Issues\n      - Wiki\n      - Discussions\n      - Blogs\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://sourceforge.net/p/forge/documentation/Allura%20API/\n      - type: Reference\n        url: https://sourceforge.net/api-docs/\n      - type: Release API\n        url: https://sourceforge.net/p/forge/documentation/Using%20the%20Release%20API/\n      - type: Download Stats API\n        url: https://sourceforge.net/p/forge/documentation/Download%20Stats%20API/\n      - type: OAuth\n        url: https://sourceforge.net/auth/oauth/\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/openapi/sourceforge-allura-openapi.yml\n    contact:\n      - FN: SourceForge Support\n        url: https://sourceforge.net/p/forge/documentation/\n        email: ''\ncommon:\n  - type: Portal\n    url: https://sourceforge.net/p/forge/documentation/API/\n  - type: Documentation\n    url: https://sourceforge.net/p/forge/documentation/\n  - type: Website\n    url: https://sourceforge.net/\n  - type: GitHub Org\n    url: https://github.com/apache/allura\n  - type: API Documentation\n    url: https://sourceforge.net/api-docs/\n  - type: OAuth Portal\n    url: https://sourceforge.net/auth/oauth/\n  - type: Webhooks Documentation\n    url: https://forge-allura.apache.org/p/allura/wiki/Webhooks/\n  - type: Support\n    url: https://sourceforge.net/p/forge/site-support/\n  - type: Blog\n    url: https://sourceforge.net/blog/\n  - type: Status\n    url: https://sourceforge.net/p/forge/site-support/\n\
  \  - type: Terms of Use\n    url: https://sourceforge.net/p/forge/documentation/Terms%20of%20Use/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/apis.yml
tags:
- Open Source
- Developer Tools
- Project Management
- Code Hosting
- Collaboration
url: https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/apis.yml
use_cases: []
---
