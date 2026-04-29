---
api_count: 3
api_specs:
- filename: comeet-careers-api-openapi.yml
  format: yaml
  label: Comeet Careers API
  slug: comeet-careers-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/openapi/comeet-careers-api-openapi.yml
apis:
- description: Public, tokenized REST API that returns the list of published positions for a Comeet customer (and details for a single position). Used to power custom-branded careers websites, embed jobs into market
  name: Comeet Careers API
  slug: comeet-careers-api
- description: The Recruiting API is a partner-scoped REST API for building on top of Spark Hire Recruit (Comeet). It supports listing companies, positions, candidates, and pipeline events, and is the underlying int
  name: Comeet Recruiting API
  slug: comeet-recruiting-api
- description: The Hires API captures new-hire data from Comeet and pushes employee profile information into downstream HRIS, onboarding, and provisioning systems. It is typically used to trigger an onboarding workf
  name: Comeet Hires API
  slug: comeet-hires-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.comeet.com/
- title: ''
  type: Portal
  url: https://developers.comeet.com/
- title: ''
  type: HelpCenter
  url: https://recruit-support.sparkhire.com/hc/en-us
- title: ''
  type: ParentCompany
  url: https://www.sparkhire.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.comeet.com/privacy-policy/
- title: ''
  type: JSON-LD
  url: json-ld/comeet-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/comeet-position-schema.json
- title: ''
  type: Spectral
  url: rules/comeet-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/comeet-careers-website-capabilities.yml
created: '2025-01-07'
description: Comeet (now Spark Hire Recruit, after Spark Hire's acquisition of Comeet) is a collaborative talent acquisition platform that helps companies post jobs, source and screen candidates, schedule interviews, and coordinate hiring teams. Comeet exposes a public Careers API (used to embed published positions on a custom careers website), a Recruiting API (used by integration partners to manage candidates and pipeline events), and a Hires API (used to push new-hire data into HRIS/onboarding systems).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Comeet Context
  property_count: 3
  slug: comeet-context
layout: provider
modified: '2026-04-26'
name: Comeet
rules:
- name: Comeet API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: comeet-rules
skills: []
slug: comeet
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: comeet\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml\nname: Comeet\ntags:\n  - ATS\n  - Candidates\n  - Careers\n  - Interviews\n  - Jobs\n  - Recruiting\n  - Talent Acquisition\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2025-01-07'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Comeet (now Spark Hire Recruit, after Spark Hire's acquisition of Comeet)\n  is a collaborative talent acquisition platform that helps companies post\n  jobs, source and screen candidates, schedule interviews, and coordinate\n  hiring teams. Comeet exposes a public Careers API (used to embed published\n  positions on a custom careers website), a Recruiting API (used by\n  integration partners to manage candidates and pipeline events), and a\n  Hires API (used to push new-hire data into HRIS/onboarding systems).\napis:\n  - aid: comeet:comeet-careers-api\n\
  \    name: Comeet Careers API\n    tags:\n      - Careers\n      - Jobs\n      - Recruiting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.comeet.co/careers-api/2.0\n    humanURL: https://developers.comeet.com/reference/careers-api-overview\n    properties:\n      - url: https://developers.comeet.com/reference/careers-api-overview\n        type: Documentation\n      - url: openapi/comeet-careers-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      Public, tokenized REST API that returns the list of published\n      positions for a Comeet customer (and details for a single position).\n      Used to power custom-branded careers websites, embed jobs into\n      marketing pages, and syndicate openings to third-party job boards.\n      Each company's data is scoped by a company UID and a public company\n      token issued by Comeet.\n    x-features:\n      - Public company-token authentication via query parameter\n\
  \      - List and retrieve published positions\n      - Optional details=true expansion for description and requirements\n      - JSON responses with stable position UIDs\n      - Backs Comeet's official Careers Website Widget\n    x-use-cases:\n      - Embedding live job listings on a corporate careers site\n      - Syndicating jobs to aggregators and job boards\n      - Generating sitemaps and SEO landing pages per position\n      - Powering \"we're hiring\" components in marketing apps\n  - aid: comeet:comeet-recruiting-api\n    name: Comeet Recruiting API\n    tags:\n      - ATS\n      - Candidates\n      - Pipeline\n      - Recruiting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.comeet.com/reference/recruiting-api-overview\n    properties:\n      - url: https://developers.comeet.com/reference/recruiting-api-overview\n        type: Documentation\n    description: >-\n      The Recruiting API is a partner-scoped\
  \ REST API for building on top of\n      Spark Hire Recruit (Comeet). It supports listing companies, positions,\n      candidates, and pipeline events, and is the underlying interface used\n      by ATS unification platforms (Merge, Finch, etc.) to integrate Comeet\n      data into HR tooling. Access is granted to approved integration\n      partners.\n    x-features:\n      - Partner-scoped authentication\n      - Companies, positions, candidates, and pipeline event endpoints\n      - Used by Merge, Finch, and other ATS unification platforms\n      - Webhooks for candidate status changes (via partner integrations)\n    x-use-cases:\n      - Building ATS integrations with HRIS and onboarding tools\n      - Bidirectional candidate sync with sourcing platforms\n      - Reporting/analytics across hiring pipelines\n  - aid: comeet:comeet-hires-api\n    name: Comeet Hires API\n    tags:\n      - HRIS\n      - Hiring\n      - Onboarding\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://developers.comeet.com/reference/hires-api-overview\n    properties:\n      - url: https://developers.comeet.com/reference/hires-api-overview\n        type: Documentation\n    description: >-\n      The Hires API captures new-hire data from Comeet and pushes employee\n      profile information into downstream HRIS, onboarding, and provisioning\n      systems. It is typically used to trigger an onboarding workflow the\n      moment a candidate is marked as hired.\n    x-features:\n      - New-hire payloads scoped to a Comeet customer\n      - Triggered when a candidate moves to the Hired stage\n      - Designed for HRIS, onboarding, and IT-provisioning consumers\n    x-use-cases:\n      - Auto-creating employee profiles in BambooHR, Workday, ADP, etc.\n      - Triggering laptop and SaaS-account provisioning at hire time\n      - Synchronizing offer-letter and start-date data into onboarding tools\ncommon:\n  - type: Website\n    url: https://www.comeet.com/\n  - type:\
  \ Portal\n    url: https://developers.comeet.com/\n  - type: HelpCenter\n    url: https://recruit-support.sparkhire.com/hc/en-us\n  - type: ParentCompany\n    url: https://www.sparkhire.com/\n  - type: PrivacyPolicy\n    url: https://www.comeet.com/privacy-policy/\n  - url: json-ld/comeet-context.jsonld\n    type: JSON-LD\n  - url: json-schema/comeet-position-schema.json\n    type: JSONSchema\n  - url: rules/comeet-rules.yml\n    type: Spectral\n  - url: capabilities/comeet-careers-website-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml
tags:
- ATS
- Candidates
- Careers
- Interviews
- Jobs
- Recruiting
- Talent Acquisition
url: https://raw.githubusercontent.com/api-evangelist/comeet/refs/heads/main/apis.yml
use_cases: []
---
