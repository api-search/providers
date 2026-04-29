---
api_count: 2
api_specs:
- filename: charter-communications-spectrum-enterprise-api-openapi.yml
  format: yaml
  label: Charter Communications Spectrum Enterprise API
  slug: spectrum-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/openapi/charter-communications-spectrum-enterprise-api-openapi.yml
- filename: charter-communications-bryte-iq-api-openapi.yml
  format: yaml
  label: Charter Communications Bryte IQ API
  slug: bryte-iq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/openapi/charter-communications-bryte-iq-api-openapi.yml
apis:
- description: The Spectrum Enterprise Open API exposes REST endpoints that let enterprise clients integrate their systems with Spectrum Enterprise portal features including service ticket management and carrier ser
  name: Charter Communications Spectrum Enterprise API
  slug: spectrum-enterprise-api
- description: Bryte IQ is a Network-as-a-Service (NaaS) API platform from Charter Communications and CableLabs that provides developers with secure, privacy-friendly access to connected device and network capabilit
  name: Charter Communications Bryte IQ API
  slug: bryte-iq-api
common:
- title: ''
  type: Website
  url: https://corporate.charter.com/
- title: ''
  type: ConsumerSite
  url: https://www.spectrum.com/
- title: ''
  type: EnterpriseSite
  url: https://enterprise.spectrum.com/
- title: ''
  type: Newsroom
  url: https://corporate.charter.com/newsroom
- title: ''
  type: InvestorRelations
  url: https://ir.charter.com/
- title: ''
  type: Careers
  url: https://jobs.spectrum.com/
- title: ''
  type: Support
  url: https://www.spectrum.net/support/
- title: ''
  type: TermsOfService
  url: https://www.spectrum.com/policies/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.spectrum.com/policies/your-privacy-rights
- title: ''
  type: JSONLD
  url: json-ld/charter-communications-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/charter-communications-ticket-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/charter-communications-serviceability-schema.json
created: '2026-03-21'
description: Charter Communications, Inc. is a leading broadband connectivity company and cable operator serving more than 32 million customers in 41 states through its Spectrum brand. Charter offers internet, TV, mobile, and voice services to residential and business customers, and exposes developer APIs through the Spectrum Enterprise portal for service ticketing and carrier serviceability, and through the Bryte IQ Network-as-a-Service platform built on the Linux Foundation CAMARA project.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Charter Communications Context
  property_count: 4
  slug: charter-communications-context
layout: provider
modified: '2026-04-23'
name: Charter Communications
skills: []
slug: charter-communications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: charter-communications\nname: Charter Communications\ndescription: >-\n  Charter Communications, Inc. is a leading broadband connectivity company and\n  cable operator serving more than 32 million customers in 41 states through its\n  Spectrum brand. Charter offers internet, TV, mobile, and voice services to\n  residential and business customers, and exposes developer APIs through the\n  Spectrum Enterprise portal for service ticketing and carrier serviceability,\n  and through the Bryte IQ Network-as-a-Service platform built on the Linux\n  Foundation CAMARA project.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Broadband\n  - Cable\n  - CAMARA\n  - Enterprise\n  - Network as a Service\n  - NaaS\n  - Spectrum\n  - Telecommunications\n  - Ticketing\ncreated: '2026-03-21'\n\
  modified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: charter-communications:spectrum-enterprise-api\n    name: Charter Communications Spectrum Enterprise API\n    description: >-\n      The Spectrum Enterprise Open API exposes REST endpoints that let\n      enterprise clients integrate their systems with Spectrum Enterprise\n      portal features including service ticket management and carrier\n      serviceability lookups. The API uses OAuth 2.0 authentication.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://enterprise.spectrum.com/\n    baseURL: https://enterprise.spectrum.com/api\n    tags:\n      - Enterprise\n      - Networking\n      - Telecommunications\n      - Ticketing\n    properties:\n      - type: Documentation\n        url: https://enterprise.spectrum.com/\n      - type: OpenAPI\n        url: openapi/charter-communications-spectrum-enterprise-api-openapi.yml\n      - type: Spectral\n        url:\
  \ spectral/charter-communications-spectral.yml\n  - aid: charter-communications:bryte-iq-api\n    name: Charter Communications Bryte IQ API\n    description: >-\n      Bryte IQ is a Network-as-a-Service (NaaS) API platform from Charter\n      Communications and CableLabs that provides developers with secure,\n      privacy-friendly access to connected device and network capabilities.\n      It is built on the Linux Foundation CAMARA project.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://corporate.charter.com/newsroom/charter-and-cablelabs-launch-bryte-iq-network-as-a-service-platform\n    baseURL: https://api.charter.com\n    tags:\n      - CAMARA\n      - NaaS\n      - Network as a Service\n      - Telecommunications\n    properties:\n      - type: Documentation\n        url: https://corporate.charter.com/newsroom/charter-and-cablelabs-launch-bryte-iq-network-as-a-service-platform\n      - type: OpenAPI\n        url: openapi/charter-communications-bryte-iq-api-openapi.yml\n\
  \      - type: CAMARA\n        url: https://camaraproject.org/\ncommon:\n  - type: Website\n    url: https://corporate.charter.com/\n  - type: ConsumerSite\n    url: https://www.spectrum.com/\n  - type: EnterpriseSite\n    url: https://enterprise.spectrum.com/\n  - type: Newsroom\n    url: https://corporate.charter.com/newsroom\n  - type: InvestorRelations\n    url: https://ir.charter.com/\n  - type: Careers\n    url: https://jobs.spectrum.com/\n  - type: Support\n    url: https://www.spectrum.net/support/\n  - type: TermsOfService\n    url: https://www.spectrum.com/policies/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.spectrum.com/policies/your-privacy-rights\n  - type: JSONLD\n    url: json-ld/charter-communications-context.jsonld\n  - type: JSONSchema\n    url: json-schema/charter-communications-ticket-schema.json\n  - type: JSONSchema\n    url: json-schema/charter-communications-serviceability-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/apis.yml
tags:
- Broadband
- Cable
- CAMARA
- Enterprise
- Network as a Service
- NaaS
- Spectrum
- Telecommunications
- Ticketing
url: https://raw.githubusercontent.com/api-evangelist/charter-communications/refs/heads/main/apis.yml
use_cases: []
---
