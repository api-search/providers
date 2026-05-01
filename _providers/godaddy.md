---
api_count: 9
apis:
- description: Purchase, renew, transfer, and manage domains, DNS records, contacts, and privacy settings programmatically.
  name: GoDaddy Domains API
  slug: domains
- description: Issue, validate, renew, and manage SSL/TLS certificates for domains.
  name: GoDaddy Certificates API
  slug: certificates
- description: Create, retrieve, update, and delete shopper accounts and subaccounts.
  name: GoDaddy Shoppers API
  slug: shoppers
- description: Manage subscription products including listing, canceling, and updating subscription billing settings.
  name: GoDaddy Subscriptions API
  slug: subscriptions
- description: Retrieve order history, line items, and order details for shopper purchases.
  name: GoDaddy Orders API
  slug: orders
- description: List, manage, and remove domains for sale on the GoDaddy aftermarket auction platform.
  name: GoDaddy Aftermarket API
  slug: aftermarket
- description: Submit and track abuse reports related to domains and hosted content.
  name: GoDaddy Abuse API
  slug: abuse
- description: Retrieve legal agreements required for purchasing or registering products.
  name: GoDaddy Agreements API
  slug: agreements
- description: Retrieve supported countries, states, and markets used across GoDaddy APIs.
  name: GoDaddy Countries API
  slug: countries
common:
- title: ''
  type: Website
  url: https://www.godaddy.com/
- title: ''
  type: Documentation
  url: https://developer.godaddy.com/doc
- title: ''
  type: Getting Started
  url: https://developer.godaddy.com/getstarted
- title: ''
  type: Terms of Service
  url: https://www.godaddy.com/legal/agreements/developer-api-terms
- title: ''
  type: Support
  url: https://developer.godaddy.com/support
created: '2026-03-16'
description: GoDaddy is a domain registrar and web hosting company offering REST APIs for domain registration, DNS management, certificates, shopper accounts, subscriptions, aftermarket auctions, and abuse reporting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: GoDaddy
skills: []
slug: godaddy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: godaddy\nname: GoDaddy\ndescription: >-\n  GoDaddy is a domain registrar and web hosting company offering REST APIs for domain\n  registration, DNS management, certificates, shopper accounts, subscriptions,\n  aftermarket auctions, and abuse reporting.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Aftermarket\n  - Certificates\n  - DNS\n  - Domains\n  - Hosting\n  - Registrar\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: godaddy:domains\n    name: GoDaddy Domains API\n    description: >-\n      Purchase, renew, transfer, and manage domains, DNS records, contacts, and\n      privacy settings programmatically.\n    humanURL: https://developer.godaddy.com/doc/endpoint/domains\n    baseURL: https://api.godaddy.com\n    tags:\n      - Domains\n\
  \      - DNS\n      - Registrar\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/domains\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-domains-openapi.json\n  - aid: godaddy:certificates\n    name: GoDaddy Certificates API\n    description: >-\n      Issue, validate, renew, and manage SSL/TLS certificates for domains.\n    humanURL: https://developer.godaddy.com/doc/endpoint/certificates\n    baseURL: https://api.godaddy.com\n    tags:\n      - Certificates\n      - SSL\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/certificates\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-certificates-openapi.json\n  - aid: godaddy:shoppers\n    name: GoDaddy Shoppers API\n    description: >-\n      Create,\
  \ retrieve, update, and delete shopper accounts and subaccounts.\n    humanURL: https://developer.godaddy.com/doc/endpoint/shoppers\n    baseURL: https://api.godaddy.com\n    tags:\n      - Shoppers\n      - Accounts\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/shoppers\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-shoppers-openapi.json\n  - aid: godaddy:subscriptions\n    name: GoDaddy Subscriptions API\n    description: >-\n      Manage subscription products including listing, canceling, and updating\n      subscription billing settings.\n    humanURL: https://developer.godaddy.com/doc/endpoint/subscriptions\n    baseURL: https://api.godaddy.com\n    tags:\n      - Subscriptions\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/subscriptions\n      - type: OpenAPI\n\
  \        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-subscriptions-openapi.json\n  - aid: godaddy:orders\n    name: GoDaddy Orders API\n    description: >-\n      Retrieve order history, line items, and order details for shopper purchases.\n    humanURL: https://developer.godaddy.com/doc/endpoint/orders\n    baseURL: https://api.godaddy.com\n    tags:\n      - Orders\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/orders\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-orders-openapi.json\n  - aid: godaddy:aftermarket\n    name: GoDaddy Aftermarket API\n    description: >-\n      List, manage, and remove domains for sale on the GoDaddy aftermarket auction\n      platform.\n    humanURL: https://developer.godaddy.com/doc/endpoint/aftermarket\n    baseURL: https://api.godaddy.com\n\
  \    tags:\n      - Aftermarket\n      - Auctions\n      - Domains\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/aftermarket\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-aftermarket-openapi.json\n  - aid: godaddy:abuse\n    name: GoDaddy Abuse API\n    description: >-\n      Submit and track abuse reports related to domains and hosted content.\n    humanURL: https://developer.godaddy.com/doc/endpoint/abuse\n    baseURL: https://api.godaddy.com\n    tags:\n      - Abuse\n      - Trust and Safety\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/abuse\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-abuse-openapi.json\n  - aid: godaddy:agreements\n    name: GoDaddy Agreements API\n    description:\
  \ >-\n      Retrieve legal agreements required for purchasing or registering products.\n    humanURL: https://developer.godaddy.com/doc/endpoint/agreements\n    baseURL: https://api.godaddy.com\n    tags:\n      - Agreements\n      - Legal\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/agreements\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-agreements-openapi.json\n  - aid: godaddy:countries\n    name: GoDaddy Countries API\n    description: >-\n      Retrieve supported countries, states, and markets used across GoDaddy APIs.\n    humanURL: https://developer.godaddy.com/doc/endpoint/countries\n    baseURL: https://api.godaddy.com\n    tags:\n      - Countries\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://developer.godaddy.com/doc/endpoint/countries\n      - type: OpenAPI\n        url: >-\n  \
  \        https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/openapi/godaddy-countries-openapi.json\ncommon:\n  - type: Website\n    url: https://www.godaddy.com/\n  - type: Documentation\n    url: https://developer.godaddy.com/doc\n  - type: Getting Started\n    url: https://developer.godaddy.com/getstarted\n  - type: Terms of Service\n    url: https://www.godaddy.com/legal/agreements/developer-api-terms\n  - type: Support\n    url: https://developer.godaddy.com/support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/apis.yml
tags:
- Aftermarket
- Certificates
- DNS
- Domains
- Hosting
- Registrar
url: https://raw.githubusercontent.com/api-evangelist/godaddy/refs/heads/main/apis.yml
use_cases: []
---
