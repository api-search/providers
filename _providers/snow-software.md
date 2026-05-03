---
api_count: 4
api_specs:
- filename: snow-software-licenses-openapi.yml
  format: yaml
  label: Snow Atlas SAM Licenses API
  slug: snow-atlas-licenses-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-licenses-openapi.yml
- filename: snow-software-saas-applications-openapi.yml
  format: yaml
  label: Snow Atlas SaaS Applications API
  slug: snow-atlas-saas-applications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-applications-openapi.yml
- filename: snow-software-saas-subscriptions-openapi.yml
  format: yaml
  label: Snow Atlas SaaS Subscriptions API
  slug: snow-atlas-saas-subscriptions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-subscriptions-openapi.yml
- filename: snow-software-computers-openapi.json
  format: json
  label: Snow Atlas SAM Computers API
  slug: snow-atlas-computers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-computers-openapi.json
apis:
- description: The Snow Atlas SAM Licenses API provides programmatic access to software license data including license upgrades, application license transfers, computer license tracking, license policies, maintenanc
  name: Snow Atlas SAM Licenses API
  slug: snow-atlas-licenses-api
- description: The Snow Atlas SaaS Applications API provides visibility into SaaS applications in use across the organization. Enables listing, updating, and managing SaaS apps, application KPIs, users, and consumpt
  name: Snow Atlas SaaS Applications API
  slug: snow-atlas-saas-applications-api
- description: The Snow Atlas SaaS Subscriptions API manages SaaS subscription data including subscription details, costs, renewal dates, and vendor information for enterprise SaaS portfolio management.
  name: Snow Atlas SaaS Subscriptions API
  slug: snow-atlas-saas-subscriptions-api
- description: The Snow Atlas SAM Computers API provides access to computer inventory data including hardware assets, application metering per computer, installed software, update history, custom values, and bulk st
  name: Snow Atlas SAM Computers API
  slug: snow-atlas-computers-api
capabilities:
- description: Unified workflow capability for IT asset management using Snow Atlas APIs. Combines software license management and SaaS application visibility to support SAM analysts, IT procurement teams, and FinOp
  name: Snow Software IT Asset Management
  slug: it-asset-management
common:
- title: ''
  type: Website
  url: https://www.snowsoftware.com
- title: ''
  type: Documentation
  url: https://docs.snowsoftware.com/
- title: ''
  type: DeveloperPortal
  url: https://docs.flexera.com/snow-atlas/snow-atlas-api/get-started-with-apis
- title: ''
  type: GitHubOrganization
  url: https://github.com/SnowSoftware
- title: ''
  type: Blog
  url: https://www.snowsoftware.com/blog
- title: ''
  type: Support
  url: https://community.snowsoftware.com
- title: ''
  type: Login
  url: https://app.snowsoftware.io
- title: ''
  type: About
  url: https://www.snowsoftware.com/company
created: '2026-03-27'
description: Snow Software (now Flexera Snow) is an IT asset and SaaS management platform providing visibility into software licenses, cloud spend, SaaS usage, and hardware assets across the enterprise. Snow Atlas is the cloud-native platform offering SAM (Software Asset Management), SaaS Management, Cloud License Management, and Commander for hybrid IT. The Snow Atlas REST APIs enable programmatic access to licenses, computers, SaaS applications, subscriptions, user accounts, agreements, and audit logs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 6
  name: Snow Software Context
  property_count: 29
  slug: snow-software-context
layout: provider
modified: '2026-05-02'
name: Snow Software
rules:
- name: Snow Software API Rules
  rule_count: 9
  severity_counts:
    error: 0
    hint: 0
    info: 5
    warn: 4
  slug: snow-software-rules
skills: []
slug: snow-software
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: snow-software\nname: Snow Software\ndescription: >-\n  Snow Software (now Flexera Snow) is an IT asset and SaaS management platform\n  providing visibility into software licenses, cloud spend, SaaS usage, and\n  hardware assets across the enterprise. Snow Atlas is the cloud-native platform\n  offering SAM (Software Asset Management), SaaS Management, Cloud License\n  Management, and Commander for hybrid IT. The Snow Atlas REST APIs enable\n  programmatic access to licenses, computers, SaaS applications, subscriptions,\n  user accounts, agreements, and audit logs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud License Management\n  - FinOps\n  - IT Asset Management\n  - SaaS Management\n  - Software Asset Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ snow-software:snow-atlas-licenses-api\n    name: Snow Atlas SAM Licenses API\n    description: >-\n      The Snow Atlas SAM Licenses API provides programmatic access to software\n      license data including license upgrades, application license transfers,\n      computer license tracking, license policies, maintenance periods, purchase\n      orders, and license metrics. Supports filtering and pagination.\n    humanURL: https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis\n    tags:\n      - IT Asset Management\n      - License Management\n      - Software Asset Management\n    properties:\n      - type: Documentation\n        url: https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-licenses-openapi.yml\n  - aid: snow-software:snow-atlas-saas-applications-api\n    name: Snow Atlas SaaS Applications API\n    description: >-\n\
  \      The Snow Atlas SaaS Applications API provides visibility into SaaS\n      applications in use across the organization. Enables listing, updating,\n      and managing SaaS apps, application KPIs, users, and consumption data\n      for SaaS spend optimization.\n    humanURL: https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis\n    tags:\n      - SaaS Management\n      - Software Asset Management\n      - Spend Optimization\n    properties:\n      - type: Documentation\n        url: https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-applications-openapi.yml\n  - aid: snow-software:snow-atlas-saas-subscriptions-api\n    name: Snow Atlas SaaS Subscriptions API\n    description: >-\n      The Snow Atlas SaaS Subscriptions API manages SaaS subscription data\n      including subscription details, costs, renewal dates, and vendor\n\
  \      information for enterprise SaaS portfolio management.\n    humanURL: https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis\n    tags:\n      - Contract Management\n      - SaaS Management\n      - Subscription Management\n    properties:\n      - type: Documentation\n        url: https://docs.flexera.com/snow-atlas/snow-atlas-api/saas-apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-saas-subscriptions-openapi.yml\n  - aid: snow-software:snow-atlas-computers-api\n    name: Snow Atlas SAM Computers API\n    description: >-\n      The Snow Atlas SAM Computers API provides access to computer inventory\n      data including hardware assets, application metering per computer,\n      installed software, update history, custom values, and bulk status\n      management for IT asset lifecycle management.\n    humanURL: https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis\n    tags:\n\
  \      - Hardware Asset Management\n      - IT Asset Management\n      - Inventory\n    properties:\n      - type: Documentation\n        url: https://docs.flexera.com/snow-atlas/snow-atlas-api/sam-core-apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/openapi/snow-software-computers-openapi.json\ncommon:\n  - type: Website\n    url: https://www.snowsoftware.com\n  - type: Documentation\n    url: https://docs.snowsoftware.com/\n  - type: DeveloperPortal\n    url: https://docs.flexera.com/snow-atlas/snow-atlas-api/get-started-with-apis\n  - type: GitHubOrganization\n    url: https://github.com/SnowSoftware\n  - type: Integrations\n    url: https://github.com/SnowSoftware/snowatlas-integrations\n  - type: Blog\n    url: https://www.snowsoftware.com/blog\n  - type: Support\n    url: https://community.snowsoftware.com\n  - type: Login\n    url: https://app.snowsoftware.io\n  - type: About\n    url: https://www.snowsoftware.com/company\n\
  segments:\n  - ITAM\n  - FinOps\n  - Enterprise Software\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/apis.yml
tags:
- Cloud License Management
- FinOps
- IT Asset Management
- SaaS Management
- Software Asset Management
url: https://raw.githubusercontent.com/api-evangelist/snow-software/refs/heads/main/apis.yml
use_cases: []
---
