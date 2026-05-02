---
api_count: 2
api_specs:
- filename: hetzner-openapi.yml
  format: yaml
  label: Hetzner Cloud API
  slug: hetzner-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hetzner/refs/heads/main/openapi/hetzner-openapi.yml
apis:
- description: The Hetzner Cloud API allows managing cloud servers, load balancers, networks, firewalls, volumes, and other cloud resources programmatically.
  name: Hetzner Cloud API
  slug: hetzner-cloud-api
- description: The Hetzner DNS API provides programmatic access to manage DNS zones, records, and configurations for domains hosted with Hetzner's DNS service.
  name: Hetzner DNS API
  slug: hetzner-dns-api
common:
- title: ''
  type: Website
  url: https://www.hetzner.com/
- title: ''
  type: Documentation
  url: https://docs.hetzner.com/
- title: ''
  type: Sign Up
  url: https://accounts.hetzner.com/signUp
- title: ''
  type: Login
  url: https://accounts.hetzner.com/login
- title: ''
  type: Status
  url: https://status.hetzner.com/
- title: ''
  type: Support
  url: https://www.hetzner.com/support
- title: ''
  type: Pricing
  url: https://www.hetzner.com/cloud
- title: ''
  type: Privacy Policy
  url: https://www.hetzner.com/legal/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.hetzner.com/legal/terms-and-conditions
created: '2025-02-09'
description: Hetzner Online is a German hosting provider offering cloud servers, dedicated servers, and domain services. Hetzner provides a Cloud API for programmatic management of cloud resources, as well as a DNS API for managing DNS zones and records.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Hetzner
skills: []
slug: hetzner
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hetzner\nname: Hetzner\ndescription: >-\n  Hetzner Online is a German hosting provider offering cloud servers, dedicated\n  servers, and domain services. Hetzner provides a Cloud API for programmatic\n  management of cloud resources, as well as a DNS API for managing DNS zones\n  and records.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Hosting\n  - DNS\n  - Infrastructure\n  - Servers\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/hetzner/refs/heads/main/apis.yml\ncreated: '2025-02-09'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hetzner:hetzner-cloud-api\n    name: Hetzner Cloud API\n    description: >-\n      The Hetzner Cloud API allows managing cloud servers, load balancers,\n      networks, firewalls, volumes, and other cloud resources programmatically.\n    humanURL: https://docs.hetzner.cloud/\n    baseURL: https://api.hetzner.cloud/v1\n    tags:\n      -\
  \ Cloud\n      - Infrastructure\n      - Servers\n    properties:\n      - type: Documentation\n        url: https://docs.hetzner.cloud/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/hetzner/refs/heads/main/openapi/hetzner-openapi.yml\n      - type: Getting Started\n        url: https://docs.hetzner.cloud/#getting-started\n  - aid: hetzner:hetzner-dns-api\n    name: Hetzner DNS API\n    description: >-\n      The Hetzner DNS API provides programmatic access to manage DNS zones,\n      records, and configurations for domains hosted with Hetzner's DNS\n      service.\n    humanURL: https://dns.hetzner.com/api-docs\n    baseURL: https://dns.hetzner.com/api/v1\n    tags:\n      - DNS\n      - Domain Management\n    properties:\n      - type: Documentation\n        url: https://dns.hetzner.com/api-docs\n      - type: Authentication\n        url: https://dns.hetzner.com/api-docs#section/Authentication\ncommon:\n  - type: Website\n    url:\
  \ https://www.hetzner.com/\n  - type: Documentation\n    url: https://docs.hetzner.com/\n  - type: Sign Up\n    url: https://accounts.hetzner.com/signUp\n  - type: Login\n    url: https://accounts.hetzner.com/login\n  - type: Status\n    url: https://status.hetzner.com/\n  - type: Support\n    url: https://www.hetzner.com/support\n  - type: Pricing\n    url: https://www.hetzner.com/cloud\n  - type: Privacy Policy\n    url: https://www.hetzner.com/legal/privacy-policy\n  - type: Terms of Service\n    url: https://www.hetzner.com/legal/terms-and-conditions\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hetzner/refs/heads/main/apis.yml
tags:
- Cloud Hosting
- DNS
- Infrastructure
- Servers
url: https://raw.githubusercontent.com/api-evangelist/hetzner/refs/heads/main/apis.yml
use_cases: []
---
