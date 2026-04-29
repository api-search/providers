---
api_count: 2
api_specs:
- filename: completedns-v2-openapi.yml
  format: yaml
  label: CompleteDNS API v2
  slug: dns-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/openapi/completedns-v2-openapi.yml
- filename: completedns-v1-openapi.yml
  format: yaml
  label: CompleteDNS API v1
  slug: ns-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/openapi/completedns-v1-openapi.yml
apis:
- description: The CompleteDNS API v2 returns the historical nameserver record for a domain, including counts of changes and drops, years of history, and a chronologically ordered list of events. Authentication uses
  name: CompleteDNS API v2
  slug: dns-history-api
- description: The CompleteDNS API v1 (legacy) returns the historical nameserver record for a domain. Includes drop and change counts, TLD support indicator, and chronologically ordered events with added/removed nam
  name: CompleteDNS API v1
  slug: ns-history-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://completedns.com/
- title: ''
  type: Documentation
  url: https://completedns.com/api/documentation/v2
- title: ''
  type: Sign Up
  url: https://completedns.com/register
- title: ''
  type: Login
  url: https://completedns.com/login
- title: ''
  type: Pricing
  url: https://completedns.com/pricing
- title: ''
  type: Contact
  url: https://completedns.com/contact
- title: ''
  type: Terms of Service
  url: https://completedns.com/terms
- title: ''
  type: Privacy Policy
  url: https://completedns.com/privacy
- title: ''
  type: JSON-LD
  url: json-ld/completedns-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/completedns-dns-history-schema.json
created: '2025-02-09'
description: CompleteDNS is a DNS research platform that tracks nameserver modifications and domain drops, with over twenty years of history and billions of recorded changes. The CompleteDNS API exposes domain-scoped lookups that return the chronological history of nameserver changes, drop events, and parking status for a given domain. Both a current v2 API and a legacy v1 API are available, authenticated by API key.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Completedns Context
  property_count: 3
  slug: completedns-context
layout: provider
modified: '2026-04-28'
name: CompleteDNS
rules:
- name: CompleteDNS API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: completedns-rules
skills: []
slug: completedns
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: completedns\nname: CompleteDNS\ndescription: >-\n  CompleteDNS is a DNS research platform that tracks nameserver modifications\n  and domain drops, with over twenty years of history and billions of recorded\n  changes. The CompleteDNS API exposes domain-scoped lookups that return the\n  chronological history of nameserver changes, drop events, and parking\n  status for a given domain. Both a current v2 API and a legacy v1 API are\n  available, authenticated by API key.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml\ntags:\n  - DNS\n  - DNS History\n  - Domain Intelligence\n  - Domains\n  - Nameservers\n  - Threat Intelligence\ncreated: '2025-02-09'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: company\napis:\n  - aid: completedns:dns-history-api\n    name: CompleteDNS API v2\n\
  \    description: >-\n      The CompleteDNS API v2 returns the historical nameserver record for a\n      domain, including counts of changes and drops, years of history, and\n      a chronologically ordered list of events. Authentication uses an API\n      key passed as a query parameter.\n    humanURL: https://completedns.com/api/documentation/v2\n    baseURL: https://api.completedns.com/v2\n    tags:\n      - DNS History\n      - Domains\n      - Lookup\n      - Nameservers\n    properties:\n      - type: Documentation\n        url: https://completedns.com/api/documentation/v2\n      - type: OpenAPI\n        url: openapi/completedns-v2-openapi.yml\n      - type: Spectral Rules\n        url: rules/completedns-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/completedns-dns-history-lookup.yml\n    features:\n      - title: Domain DNS History\n        description: Retrieve the full nameserver history for a domain by name.\n      - title: Drop Tracking\n        description:\
  \ Surface domain drop events captured by CompleteDNS.\n      - title: Parking Detection\n        description: Indicates whether a domain was parked at any point in its history.\n      - title: API Key Authentication\n        description: Authentication via API key passed as a query parameter.\n    useCases:\n      - title: Threat Intelligence\n        description: Investigate suspicious domains by reviewing nameserver pivots over time.\n      - title: Brand Protection\n        description: Track unauthorized nameserver changes on monitored domains.\n      - title: Domain Acquisition Research\n        description: Analyze the historical reliability of a domain prior to acquisition.\n  - aid: completedns:ns-history-api\n    name: CompleteDNS API v1\n    description: >-\n      The CompleteDNS API v1 (legacy) returns the historical nameserver\n      record for a domain. Includes drop and change counts, TLD support\n      indicator, and chronologically ordered events with added/removed\n  \
  \    nameservers. CompleteDNS recommends migrating to v2.\n    humanURL: https://completedns.com/api/documentation/v1\n    baseURL: https://api.completedns.com/v1\n    tags:\n      - DNS History\n      - Legacy\n      - Lookup\n      - Nameservers\n    properties:\n      - type: Documentation\n        url: https://completedns.com/api/documentation/v1\n      - type: OpenAPI\n        url: openapi/completedns-v1-openapi.yml\n      - type: Spectral Rules\n        url: rules/completedns-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/completedns-dns-history-lookup.yml\n    features:\n      - title: Legacy Nameserver History\n        description: Returns nameserver history events with added/removed nameserver records.\n      - title: Quota Header\n        description: requestsLeft response header surfaces remaining API quota.\n    useCases:\n      - title: Legacy Integrations\n        description: Maintain compatibility with existing tooling that consumes the v1 API.\n\
  common:\n  - type: Portal\n    url: https://completedns.com/\n  - type: Documentation\n    url: https://completedns.com/api/documentation/v2\n  - type: Sign Up\n    url: https://completedns.com/register\n  - type: Login\n    url: https://completedns.com/login\n  - type: Pricing\n    url: https://completedns.com/pricing\n  - type: Contact\n    url: https://completedns.com/contact\n  - type: Terms of Service\n    url: https://completedns.com/terms\n  - type: Privacy Policy\n    url: https://completedns.com/privacy\n  - type: JSON-LD\n    url: json-ld/completedns-context.jsonld\n  - type: JSONSchema\n    url: json-schema/completedns-dns-history-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml
tags:
- DNS
- DNS History
- Domain Intelligence
- Domains
- Nameservers
- Threat Intelligence
url: https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml
use_cases: []
---
