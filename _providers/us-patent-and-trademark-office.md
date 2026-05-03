---
api_count: 2
api_specs:
- filename: swagger.yaml
  format: yaml
  label: USPTO Open Data Portal API
  slug: open-data-portal-api
  spec_type: OpenAPI
  url: https://data.uspto.gov/swagger/swagger.yaml
- filename: uspto-tsdr-openapi.yml
  format: yaml
  label: USPTO Trademark Status and Document Retrieval API
  slug: tsdr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-tsdr-openapi.yml
apis:
- description: The USPTO Open Data Portal (ODP) API allows public users to discover, search, and extract USPTO patent, trademark, PTAB trial, petition decision, and bulk dataset information at no cost. Requires an O
  name: USPTO Open Data Portal API
  slug: open-data-portal-api
- description: The Trademark Status and Document Retrieval (TSDR) REST API provides programmatic access to trademark case status, documents, case images, and related metadata. Requires an API key for bulk data downl
  name: USPTO Trademark Status and Document Retrieval API
  slug: tsdr-api
capabilities:
- description: Unified capability for intellectual property research, combining patent application search, PTAB trial proceedings, and trademark status retrieval. Supports IP attorneys, researchers, portfolio manage
  name: USPTO Intellectual Property Research
  slug: intellectual-property-research
common: []
created: '2024-12-03'
description: The US Patent and Trademark Office (USPTO) is responsible for granting patents and registering trademarks to protect intellectual property in the United States. The USPTO examines patent applications to determine if an invention is new, non-obvious, and useful, and grants patents to those that meet the criteria. They also register trademarks, which are words, phrases, symbols, or designs that distinguish goods or services of one entity from another. The USPTO Open Data Portal provides free programmatic access to patent applications, PTAB trial proceedings, petition decisions, trademark status, and bulk datasets.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Us Patent And Trademark Office Context
  property_count: 21
  slug: us-patent-and-trademark-office-context
layout: provider
modified: '2026-05-03'
name: US Patent and Trademark Office
rules:
- name: US Patent and Trademark Office API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: uspto-rules
skills: []
slug: us-patent-and-trademark-office
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-patent-and-trademark-office\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml\napis:\n  - aid: us-patent-and-trademark-office:open-data-portal-api\n    name: USPTO Open Data Portal API\n    tags:\n      - Patents\n      - Trademarks\n      - Intellectual Property\n      - Federal Government\n      - Open Data\n    humanURL: https://data.uspto.gov/apis/getting-started\n    properties:\n      - url: https://data.uspto.gov/apis/getting-started\n        type: Documentation\n      - url: https://data.uspto.gov/swagger/swagger.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-open-data-portal-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USPTO Open Data Portal (ODP) API allows public users to discover,\n      search, and extract USPTO patent, trademark, PTAB trial, petition\
  \ decision,\n      and bulk dataset information at no cost. Requires an ODP API key passed\n      via the X-API-KEY header.\n  - aid: us-patent-and-trademark-office:tsdr-api\n    name: USPTO Trademark Status and Document Retrieval API\n    tags:\n      - Trademarks\n      - Intellectual Property\n      - Federal Government\n      - Open Data\n    humanURL: https://developer.uspto.gov/api-catalog/tsdr-data-api\n    properties:\n      - url: https://developer.uspto.gov/api-catalog/tsdr-data-api\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/openapi/uspto-tsdr-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trademark Status and Document Retrieval (TSDR) REST API provides\n      programmatic access to trademark case status, documents, case images,\n      and related metadata. Requires an API key for bulk data downloads.\nname: US Patent and Trademark Office\ntags:\n\
  \  - Federal Government\n  - Patents\n  - Trademarks\n  - Intellectual Property\n  - Open Data\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Patent and Trademark Office (USPTO) is responsible for granting patents\n  and registering trademarks to protect intellectual property in the United\n  States. The USPTO examines patent applications to determine if an invention is\n  new, non-obvious, and useful, and grants patents to those that meet the\n  criteria. They also register trademarks, which are words, phrases, symbols, or\n  designs that distinguish goods or services of one entity from another. The\n  USPTO Open Data Portal provides free programmatic access to patent applications,\n  PTAB trial proceedings, petition decisions, trademark status, and bulk datasets.\nfeatures:\n  - Patent Application Search\n  - Patent File\
  \ Wrapper Access\n  - PTAB Trial Proceedings Search\n  - Petition Decision Search\n  - Trademark Status Retrieval\n  - Trademark Document Retrieval\n  - Bulk Dataset Downloads\nuseCases:\n  - Patent research and prior art searches\n  - Trademark availability checking\n  - PTAB trial monitoring\n  - IP portfolio management\n  - Legal and compliance research\n  - Academic and economic research\nintegrations:\n  - data.gov\n  - api.data.gov\nsolutions:\n  - Intellectual Property Management\n  - Patent Search and Analytics\n  - Trademark Monitoring\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml
tags:
- Federal Government
- Patents
- Trademarks
- Intellectual Property
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml
use_cases: []
---
