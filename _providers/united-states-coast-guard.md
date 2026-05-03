---
api_count: 2
api_specs:
- filename: cgmix-maritime-information-exchange-openapi.yml
  format: yaml
  label: CGMIX Maritime Information Exchange API
  slug: cgmix-maritime-information-exchange
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/openapi/cgmix-maritime-information-exchange-openapi.yml
apis:
- description: The Coast Guard Maritime Information Exchange (CGMIX) provides XML web services for accessing Coast Guard maritime information including vessel documentation, Port State Information Exchange (PSIX) da
  name: CGMIX Maritime Information Exchange API
  slug: cgmix-maritime-information-exchange
- description: The Vessel Information Verification Service (VIVS) is a NAVCEN web service that allows retrieval of a vessel's broadcasted AIS static data, including Maritime Mobile Service Identity (MMSI), call sign
  name: NAVCEN AIS Vessel Information Verification Service
  slug: navcen-ais-vessel-information
capabilities:
- description: Unified capability for maritime safety compliance workflows combining USCG CGMIX vessel documentation, Port State Control inspection records, equipment certifications, and incident investigation data.
  name: USCG Maritime Safety and Compliance
  slug: maritime-safety
common: []
created: '2024-12-03'
description: The United States Coast Guard is a branch of the military responsible for enforcing maritime laws, protecting the nation's waterways and coastlines, and ensuring the safety and security of seafarers. They conduct search and rescue operations, respond to environmental disasters, combat illegal drug trafficking and immigration, and conduct security patrols to thwart terrorism threats. The USCG provides public APIs and data services through the CGMIX Maritime Information Exchange, the Navigation Center (NAVCEN), and the National Vessel Documentation Center (NVDC).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: United States Coast Guard Context
  property_count: 19
  slug: united-states-coast-guard-context
layout: provider
modified: '2026-05-03'
name: United States Coast Guard
rules:
- name: United States Coast Guard API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: cgmix-maritime-information-exchange-rules
skills: []
slug: united-states-coast-guard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-coast-guard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml\napis:\n  - aid: united-states-coast-guard:cgmix-maritime-information-exchange\n    name: CGMIX Maritime Information Exchange API\n    tags:\n      - Maritime\n      - Vessel Documentation\n      - Safety\n      - Federal Government\n    humanURL: https://cgmix.uscg.mil/xml/default.aspx\n    baseURL: https://cgmix.uscg.mil\n    properties:\n      - url: https://cgmix.uscg.mil/xml/default.aspx\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/openapi/cgmix-maritime-information-exchange-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/rules/cgmix-maritime-information-exchange-rules.yml\n        type: SpectralRules\n      - url: >-\n   \
  \       https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/capabilities/maritime-safety.yaml\n        type: NaftikoCapability\n    description: >-\n      The Coast Guard Maritime Information Exchange (CGMIX) provides XML web\n      services for accessing Coast Guard maritime information including vessel\n      documentation, Port State Information Exchange (PSIX) data, equipment\n      certifications, and Incident Investigation Reports (IIR). Data originates\n      from the Marine Information for Safety and Law Enforcement (MISLE) system\n      and is updated weekly.\n    contact:\n      FN: U.S. Coast Guard\n      url: https://cgmix.uscg.mil/\n\n  - aid: united-states-coast-guard:navcen-ais-vessel-information\n    name: NAVCEN AIS Vessel Information Verification Service\n    tags:\n      - Maritime\n      - AIS\n      - Vessel Tracking\n      - Federal Government\n    humanURL: https://www.navcen.uscg.gov/ais-vivs-home\n    baseURL: https://www.navcen.uscg.gov\n\
  \    properties:\n      - url: https://www.navcen.uscg.gov/ais-vivs-home\n        type: Documentation\n      - url: https://www.navcen.uscg.gov/ais-vessel-information-verification-service\n        type: Documentation\n    description: >-\n      The Vessel Information Verification Service (VIVS) is a NAVCEN web\n      service that allows retrieval of a vessel's broadcasted AIS static data,\n      including Maritime Mobile Service Identity (MMSI), call sign, vessel name,\n      official number, dimensions, draft, vessel type, and positioning source.\n      Provided by the U.S. Coast Guard Navigation Center.\n\nname: United States Coast Guard\ntags:\n  - Federal Government\n  - Maritime Safety\n  - Vessel Documentation\n  - Emergency Response\n  - Law Enforcement\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The United States Coast\
  \ Guard is a branch of the military responsible for\n  enforcing maritime laws, protecting the nation's waterways and coastlines,\n  and ensuring the safety and security of seafarers. They conduct search and\n  rescue operations, respond to environmental disasters, combat illegal drug\n  trafficking and immigration, and conduct security patrols to thwart\n  terrorism threats. The USCG provides public APIs and data services through\n  the CGMIX Maritime Information Exchange, the Navigation Center (NAVCEN),\n  and the National Vessel Documentation Center (NVDC).\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml
tags:
- Federal Government
- Maritime Safety
- Vessel Documentation
- Emergency Response
- Law Enforcement
url: https://raw.githubusercontent.com/api-evangelist/united-states-coast-guard/refs/heads/main/apis.yml
use_cases: []
---
