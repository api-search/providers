---
api_count: 3
api_specs:
- filename: lincoln-national-openapi.yml
  format: yaml
  label: Lincoln Financial LincSmart Enrollment API
  slug: lincsmart-enrollment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml
- filename: lincoln-national-openapi.yml
  format: yaml
  label: Lincoln Financial LincSmart EOI Solution API
  slug: lincsmart-eoi-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml
- filename: lincoln-national-openapi.yml
  format: yaml
  label: Lincoln Financial LincSmart Plan Design API
  slug: lincsmart-plan-design-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml
apis:
- description: The LincSmart Enrollment API ensures that employee elections and demographic information are synced in real time, eliminating lengthy setup time for weekly batch files.
  name: Lincoln Financial LincSmart Enrollment API
  slug: lincsmart-enrollment-api
- description: The LincSmart EOI Solution API sends benefits enrollment decisions to employee platforms in real time, eliminating manual work and paper forms for evidence of insurability.
  name: Lincoln Financial LincSmart EOI Solution API
  slug: lincsmart-eoi-api
- description: The LincSmart Plan Design API allows plan information like rules and rates to flow from Lincoln to benefits administration platforms automatically.
  name: Lincoln Financial LincSmart Plan Design API
  slug: lincsmart-plan-design-api
common:
- title: ''
  type: Website
  url: https://www.lincolnfinancial.com
- title: ''
  type: LincSmartPlatform
  url: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/index.html
- title: ''
  type: Portal
  url: https://www.mylincolnportal.com
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml
created: '2026-03-21'
description: Lincoln National Corporation, operating as Lincoln Financial Group, is a diversified financial services company offering annuities, retirement plan services, life insurance, and group protection products. The company provides solutions for employers, brokers, and retirement professionals through its LincSmart platform of API integrations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Lincoln National
skills: []
slug: lincoln-national
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lincoln-national\nname: Lincoln National\ndescription: >-\n  Lincoln National Corporation, operating as Lincoln Financial Group, is a\n  diversified financial services company offering annuities, retirement plan\n  services, life insurance, and group protection products. The company\n  provides solutions for employers, brokers, and retirement professionals\n  through its LincSmart platform of API integrations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Annuities\n  - Benefits\n  - Enrollment\n  - HR\n  - Insurance\n  - Retirement\nurl: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: lincoln-national:lincsmart-enrollment-api\n    name: Lincoln Financial LincSmart Enrollment API\n    description: >-\n      The LincSmart Enrollment API ensures that employee elections and\n \
  \     demographic information are synced in real time, eliminating lengthy\n      setup time for weekly batch files.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/index.html\n    baseURL: https://www.lincolnfinancial.com\n    tags:\n      - Benefits\n      - Enrollment\n      - HR\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/index.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml\n  - aid: lincoln-national:lincsmart-eoi-api\n    name: Lincoln Financial LincSmart EOI Solution API\n    description: >-\n      The LincSmart EOI Solution API sends benefits enrollment decisions\n      to employee platforms in real time, eliminating manual work and\
  \ paper\n      forms for evidence of insurability.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/assets/resources/info/eoi.html\n    baseURL: https://www.lincolnfinancial.com\n    tags:\n      - Benefits\n      - Evidence of Insurability\n      - HR\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/assets/resources/info/eoi.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml\n  - aid: lincoln-national:lincsmart-plan-design-api\n    name: Lincoln Financial LincSmart Plan Design API\n    description: >-\n      The LincSmart Plan Design API allows plan information like rules and\n      rates to flow from Lincoln to benefits administration platforms\n\
  \      automatically.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/assets/resources/info/plan.html\n    baseURL: https://www.lincolnfinancial.com\n    tags:\n      - Benefits\n      - HR\n      - Insurance\n      - Plan Design\n    properties:\n      - type: Documentation\n        url: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/assets/resources/info/plan.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.lincolnfinancial.com\n  - type: LincSmartPlatform\n    url: https://www.lincolnfinancial.com/public/static/digitalbrochure/gp/lincsmart/index.html\n  - type: Portal\n    url: https://www.mylincolnportal.com\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/openapi/lincoln-national-openapi.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/apis.yml
tags:
- Annuities
- Benefits
- Enrollment
- HR
- Insurance
- Retirement
url: https://raw.githubusercontent.com/api-evangelist/lincoln-national/refs/heads/main/apis.yml
use_cases: []
---
