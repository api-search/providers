---
api_count: 4
api_specs:
- filename: old-dominion-freight-line-bill-of-lading-api-openapi.yml
  format: yaml
  label: ODFL Bill of Lading API
  slug: bill-of-lading-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-bill-of-lading-api-openapi.yml
- filename: old-dominion-freight-line-pickup-api-openapi.yml
  format: yaml
  label: ODFL Pickup API
  slug: pickup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-pickup-api-openapi.yml
- filename: old-dominion-freight-line-tracking-api-openapi.yml
  format: yaml
  label: ODFL Tracking API
  slug: tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-tracking-api-openapi.yml
- filename: old-dominion-freight-line-document-api-openapi.yml
  format: yaml
  label: ODFL Document API
  slug: document-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-document-api-openapi.yml
apis:
- description: Submits electronic bills of lading to the Old Dominion Freight Line billing system, generating shipping labels and BOL documents. Used by shippers to programmatically create freight documentation.
  name: ODFL Bill of Lading API
  slug: bill-of-lading-api
- description: Processes electronic pickup requests for one or more shipments. Returns pickup numbers and PPIDs that shippers use to confirm and track pickup requests with Old Dominion Freight Line.
  name: ODFL Pickup API
  slug: pickup-api
- description: Provides shipment status information for ODFL freight movements. Used to integrate real-time and historical freight tracking data into shipper and partner systems.
  name: ODFL Tracking API
  slug: tracking-api
- description: Retrieves PDF documents associated with shipments, including bills of lading and delivery receipts, by PRO number. Used to programmatically pull shipment documentation from Old Dominion Freight Line.
  name: ODFL Document API
  slug: document-api
common:
- title: ''
  type: Website
  url: https://www.odfl.com
- title: ''
  type: Developer
  url: https://www.odfl.com/us/en/resources/shipping-api-integrations.html
- title: ''
  type: Support
  url: mailto:api@odfl.com
- title: ''
  type: Tools
  url: https://www.odfl.com/us/en/resources.html
created: '2026-03-24'
description: Old Dominion Freight Line is a leading less-than-truckload (LTL) motor carrier providing regional, inter-regional, and national freight services in the United States. ODFL offers a suite of REST web services for shippers and partners to integrate freight booking, pickup, tracking, document retrieval, and electronic bill of lading capabilities directly into their systems.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-28'
name: Old Dominion Freight Line
skills: []
slug: old-dominion-freight-line
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: old-dominion-freight-line\nname: Old Dominion Freight Line\nurl: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/apis.yml\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - Freight\n  - Less-Than-Truckload\n  - Logistics\n  - Shipping\n  - Transportation\ncreated: '2026-03-24'\nmodified: '2026-04-28'\ndescription: >-\n  Old Dominion Freight Line is a leading less-than-truckload (LTL) motor carrier\n  providing regional, inter-regional, and national freight services in the\n  United States. ODFL offers a suite of REST web services for shippers and\n  partners to integrate freight booking, pickup, tracking, document retrieval,\n  and electronic bill of lading capabilities directly into their systems.\napis:\n  - aid: old-dominion-freight-line:bill-of-lading-api\n    name: ODFL Bill of Lading API\n    description: >-\n      Submits electronic bills of lading to the Old Dominion Freight Line\n      billing system, generating\
  \ shipping labels and BOL documents. Used by\n      shippers to programmatically create freight documentation.\n    humanURL: https://www.odfl.com/us/en/resources/shipping-api-integrations.html\n    baseURL: https://www.odfl.com\n    tags:\n      - Bill of Lading\n      - Documents\n      - Freight\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Bill%20of%20Lading%20API%20Development%20Guide.pdf\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-bill-of-lading-api-openapi.yml\n  - aid: old-dominion-freight-line:pickup-api\n    name: ODFL Pickup API\n    description: >-\n      Processes electronic pickup requests for one or more shipments. Returns\n      pickup numbers and PPIDs that shippers use to confirm and track pickup\n      requests with Old Dominion Freight Line.\n    humanURL:\
  \ https://www.odfl.com/us/en/resources/shipping-api-integrations.html\n    baseURL: https://www.odfl.com\n    tags:\n      - Freight\n      - Logistics\n      - Pickup\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Pickup%20API%20Development%20Guide.pdf\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-pickup-api-openapi.yml\n  - aid: old-dominion-freight-line:tracking-api\n    name: ODFL Tracking API\n    description: >-\n      Provides shipment status information for ODFL freight movements. Used to\n      integrate real-time and historical freight tracking data into shipper and\n      partner systems.\n    humanURL: https://www.odfl.com/us/en/resources/shipping-api-integrations.html\n    baseURL: https://www.odfl.com\n    tags:\n      - Freight\n      - Shipping\n      - Tracking\n\
  \    properties:\n      - type: Documentation\n        url: https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Tracking%20API%20Development%20Guide.pdf\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-tracking-api-openapi.yml\n  - aid: old-dominion-freight-line:document-api\n    name: ODFL Document API\n    description: >-\n      Retrieves PDF documents associated with shipments, including bills of\n      lading and delivery receipts, by PRO number. Used to programmatically\n      pull shipment documentation from Old Dominion Freight Line.\n    humanURL: https://www.odfl.com/us/en/resources/shipping-api-integrations.html\n    baseURL: https://www.odfl.com\n    tags:\n      - Documents\n      - Freight\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Document%20API%20Development%20Guide.pdf\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-document-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.odfl.com\n  - type: Developer\n    url: https://www.odfl.com/us/en/resources/shipping-api-integrations.html\n  - type: Support\n    url: mailto:api@odfl.com\n  - type: Tools\n    url: https://www.odfl.com/us/en/resources.html\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/apis.yml
tags:
- Freight
- Less-Than-Truckload
- Logistics
- Shipping
- Transportation
url: https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/apis.yml
use_cases: []
---
