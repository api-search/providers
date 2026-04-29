---
api_count: 1
api_specs:
- filename: copper-developer-api-openapi.yml
  format: yaml
  label: Copper Developer API
  slug: developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/openapi/copper-developer-api-openapi.yml
apis:
- description: The Copper Developer API is a RESTful JSON API providing programmatic access to Copper CRM resources including people, companies, leads, opportunities, projects, tasks, activities, and webhooks. The A
  name: Copper Developer API
  slug: developer-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.copper.com
- title: ''
  type: DeveloperPortal
  url: https://developer.copper.com/
- title: ''
  type: Documentation
  url: https://developer.copper.com/
- title: ''
  type: Authentication
  url: https://developer.copper.com/introduction/requests.html
- title: ''
  type: GettingStarted
  url: https://developer.copper.com/introduction/quick-start.html
- title: ''
  type: RateLimits
  url: https://developer.copper.com/introduction/requests.html
- title: ''
  type: Errors
  url: https://developer.copper.com/introduction/responses.html
- title: ''
  type: Pricing
  url: https://www.copper.com/pricing
- title: ''
  type: Blog
  url: https://www.copper.com/blog
- title: ''
  type: PrivacyPolicy
  url: https://www.copper.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.copper.com/terms-of-service
- title: ''
  type: Status
  url: https://status.copper.com/
- title: ''
  type: Twitter
  url: https://twitter.com/copperinc
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/copperinc/
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/CopperCRM
created: '2025-01-07'
description: Copper is a CRM platform built natively for Google Workspace, designed to help teams cultivate enduring client relationships through purposeful collaboration. Copper offers a RESTful Developer API providing programmatic access to People, Companies, Leads, Opportunities, Projects, Tasks, Activities, Webhooks, and related resources for CRM integration and automation.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 44
  name: Copper Context
  property_count: 0
  slug: copper-context
layout: provider
modified: '2026-04-28'
name: Copper
rules:
- name: Copper API Rules
  rule_count: 14
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 7
  slug: copper-developer-api-rules
skills: []
slug: copper
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: copper\nname: Copper\nx-type: company\ndescription: >-\n  Copper is a CRM platform built natively for Google Workspace, designed to help\n  teams cultivate enduring client relationships through purposeful collaboration.\n  Copper offers a RESTful Developer API providing programmatic access to People,\n  Companies, Leads, Opportunities, Projects, Tasks, Activities, Webhooks, and\n  related resources for CRM integration and automation.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ntags:\n  - Activities\n  - Companies\n  - Contact Relationship Management\n  - Contacts\n  - CRM\n  - Customer Relationship Management\n  - Google Workspace\n  - Leads\n  - Opportunities\n  - People\n  - Projects\n  - Sales\n  - Tasks\ncreated: '2025-01-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n\
  \  - aid: copper:developer-api\n    name: Copper Developer API\n    description: >-\n      The Copper Developer API is a RESTful JSON API providing programmatic\n      access to Copper CRM resources including people, companies, leads,\n      opportunities, projects, tasks, activities, and webhooks. The API uses\n      token-based authentication with three required headers (X-PW-AccessToken,\n      X-PW-Application, X-PW-UserEmail) and supports full CRUD operations,\n      search, bulk actions, and lead conversion. Rate limits are 180 requests\n      per minute and 3 requests per second for bulk operations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.copper.com/\n    baseURL: https://api.copper.com/developer_api/v1\n    tags:\n      - Activities\n      - Companies\n      - CRM\n      - Leads\n      - Opportunities\n      - People\n      - Projects\n      - REST\n      - Tasks\n      - Webhooks\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.copper.com/\n      - type: Authentication\n        url: https://developer.copper.com/introduction/requests.html\n      - type: GettingStarted\n        url: https://developer.copper.com/introduction/quick-start.html\n      - type: OAuth\n        url: https://developer.copper.com/introduction/oauth-quickstart.html\n      - type: Webhooks\n        url: https://developer.copper.com/webhooks/general/list-of-webhook-events.html\n      - type: PostmanCollection\n        url: https://developer.copper.com/introduction/postman-collection.html\n      - type: People\n        url: https://developer.copper.com/people/\n      - type: Companies\n        url: https://developer.copper.com/companies/\n      - type: Leads\n        url: https://developer.copper.com/leads/\n      - type: Opportunities\n        url: https://developer.copper.com/opportunities/\n      - type: Projects\n        url: https://developer.copper.com/projects/\n      - type:\
  \ Tasks\n        url: https://developer.copper.com/tasks/\n      - type: Activities\n        url: https://developer.copper.com/activities/\n      - type: CustomFields\n        url: https://developer.copper.com/custom-fields/\n      - type: Tags\n        url: https://developer.copper.com/tags/\n      - type: OpenAPI\n        url: openapi/copper-developer-api-openapi.yml\n      - type: Rules\n        url: rules/copper-developer-api-rules.yml\n      - type: JSONLD\n        url: json-ld/copper-context.jsonld\n      - type: Vocabulary\n        url: vocabulary/copper-vocabulary.yml\n      - type: Capabilities\n        url: capabilities/copper-developer-api-capabilities.yml\n    contact:\n      - type: Support\n        url: https://www.copper.com/contact-us\ncommon:\n  - type: Website\n    url: https://www.copper.com\n  - type: DeveloperPortal\n    url: https://developer.copper.com/\n  - type: Documentation\n    url: https://developer.copper.com/\n  - type: Authentication\n    url: https://developer.copper.com/introduction/requests.html\n\
  \  - type: GettingStarted\n    url: https://developer.copper.com/introduction/quick-start.html\n  - type: RateLimits\n    url: https://developer.copper.com/introduction/requests.html\n  - type: Errors\n    url: https://developer.copper.com/introduction/responses.html\n  - type: Pricing\n    url: https://www.copper.com/pricing\n  - type: Blog\n    url: https://www.copper.com/blog\n  - type: PrivacyPolicy\n    url: https://www.copper.com/privacy-policy\n  - type: TermsOfService\n    url: https://www.copper.com/terms-of-service\n  - type: Status\n    url: https://status.copper.com/\n  - type: Twitter\n    url: https://twitter.com/copperinc\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/copperinc/\n  - type: YouTube\n    url: https://www.youtube.com/c/CopperCRM\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml
tags:
- Activities
- Companies
- Contact Relationship Management
- Contacts
- CRM
- Customer Relationship Management
- Google Workspace
- Leads
- Opportunities
- People
- Projects
- Sales
- Tasks
url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/apis.yml
use_cases: []
---
