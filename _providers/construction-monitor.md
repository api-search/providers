---
api_count: 2
apis:
- description: REST + JSON service backed by Elasticsearch that lets partners search building permits, retrieve full permit detail records, and pull delta updates on a polling schedule. Authentication is handled wit
  name: Construction Monitor Permits API
  slug: permits-api
- description: Weekly bulk delivery of permit records over secure FTP for partners that prefer batch ingestion to live API polling. Suitable for warehousing millions of permits without operating a live integration.
  name: Construction Monitor Weekly Data Dump (SFTP)
  slug: weekly-ftp
common:
- title: ''
  type: Website
  url: https://www.constructionmonitor.com
- title: ''
  type: Data Products
  url: https://www.constructionmonitor.com/data
- title: ''
  type: Contact / API Access
  url: https://www.constructionmonitor.com/contact
- title: ''
  type: Blog
  url: https://www.constructionmonitor.com/blog
- title: ''
  type: Privacy Policy
  url: https://www.constructionmonitor.com/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.constructionmonitor.com/terms-of-use
created: '2025-02-08'
description: Construction Monitor aggregates building-permit data from county and municipal sources nationwide and resells it as construction leads, contractor intelligence, and historical permit research. Programmatic access is offered through a REST + JSON API backed by Elasticsearch and a weekly data-dump option delivered over secure FTP. Both channels are account-managed; partners receive credentials and a documented endpoint contract directly from Construction Monitor.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-29'
name: Construction Monitor
skills: []
slug: construction-monitor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: construction-monitor\nname: Construction Monitor\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/construction-monitor/refs/heads/main/apis.yml\ntags:\n  - Construction\n  - Contractors\n  - Lead Generation\n  - Permits\n  - Real Estate\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-08'\nmodified: '2026-04-29'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: company\ndescription: >-\n  Construction Monitor aggregates building-permit data from county and\n  municipal sources nationwide and resells it as construction leads,\n  contractor intelligence, and historical permit research. Programmatic\n  access is offered through a REST + JSON API backed by Elasticsearch and a\n  weekly data-dump option delivered over secure FTP. Both channels are\n  account-managed; partners receive credentials and a documented endpoint\n  contract directly from Construction Monitor.\n\
  apis:\n  - aid: construction-monitor:permits-api\n    name: Construction Monitor Permits API\n    tags:\n      - Elasticsearch\n      - JSON\n      - Permits\n      - REST\n    humanURL: https://www.constructionmonitor.com/data\n    properties:\n      - url: https://www.constructionmonitor.com/data\n        type: Documentation\n    description: >-\n      REST + JSON service backed by Elasticsearch that lets partners search\n      building permits, retrieve full permit detail records, and pull delta\n      updates on a polling schedule. Authentication is handled with a simple\n      API-key scheme provisioned per customer. Used to drive lead-generation\n      pipelines, populate CRM and BI tools, and power downstream construction\n      analytics.\n  - aid: construction-monitor:weekly-ftp\n    name: Construction Monitor Weekly Data Dump (SFTP)\n    tags:\n      - Bulk\n      - Data Dump\n      - Permits\n      - SFTP\n    humanURL: https://www.constructionmonitor.com/data\n    properties:\n\
  \      - url: https://www.constructionmonitor.com/data\n        type: Documentation\n    description: >-\n      Weekly bulk delivery of permit records over secure FTP for partners\n      that prefer batch ingestion to live API polling. Suitable for\n      warehousing millions of permits without operating a live integration.\ncommon:\n  - type: Website\n    url: https://www.constructionmonitor.com\n  - type: Data Products\n    url: https://www.constructionmonitor.com/data\n  - type: Contact / API Access\n    url: https://www.constructionmonitor.com/contact\n  - type: Blog\n    url: https://www.constructionmonitor.com/blog\n  - type: Privacy Policy\n    url: https://www.constructionmonitor.com/privacy-policy\n  - type: Terms of Service\n    url: https://www.constructionmonitor.com/terms-of-use\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/construction-monitor/refs/heads/main/apis.yml
tags:
- Construction
- Contractors
- Lead Generation
- Permits
- Real Estate
url: https://raw.githubusercontent.com/api-evangelist/construction-monitor/refs/heads/main/apis.yml
use_cases: []
---
