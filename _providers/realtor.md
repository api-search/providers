---
api_count: 3
api_specs:
- filename: realtor-connections-plus-asyncapi.yml
  format: yaml
  label: Realtor.com Connections Plus API
  slug: connections-plus-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/asyncapi/realtor-connections-plus-asyncapi.yml
- filename: realtor-lead-delivery-asyncapi.yml
  format: yaml
  label: Realtor.com Lead Delivery API
  slug: lead-delivery-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/asyncapi/realtor-lead-delivery-asyncapi.yml
- filename: realtor-property-data-openapi.yml
  format: yaml
  label: Realtor.com Property Data API
  slug: property-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/openapi/realtor-property-data-openapi.yml
apis:
- description: The Realtor.com Connections Plus API provides a direct connection between the Realtor.com lead delivery system and supporting CRM platforms. It enables real estate agents, brokers, and offices to rece
  name: Realtor.com Connections Plus API
  slug: connections-plus-api
- description: The Realtor.com Lead Delivery API is an end-to-end integration layer that delivers real estate leads directly from Realtor.com to third-party CRM systems. It provides faster and more secure lead deliv
  name: Realtor.com Lead Delivery API
  slug: lead-delivery-api
- description: The Realtor.com Property Data API provides programmatic access to real estate listing data from Realtor.com, one of the largest property listing platforms in the United States. It offers endpoints for
  name: Realtor.com Property Data API
  slug: property-data-api
asyncapis:
- description: The Realtor.com Connections Plus API provides a direct connection between the Realtor.com lead delivery system and supporting CRM platforms. It enables real estate agents, brokers, and offices to rece
  name: Realtor.com Connections Plus Events
  slug: realtor-connections-plus-asyncapi
- description: The Realtor.com Lead Delivery API is an end-to-end integration layer that delivers real estate leads directly from Realtor.com to third-party CRM systems. It provides faster and more secure lead deliv
  name: Realtor.com Lead Delivery Events
  slug: realtor-lead-delivery-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/realtor-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/realtor-lead-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/realtor-property-schema.json
created: ''
description: Realtor.com is an online real estate marketplace operated by Move, Inc., providing home listings, neighborhood information, and tools for buyers, sellers, and renters.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Realtor Context
  property_count: 8
  slug: realtor-context
layout: provider
modified: '2026-04-28'
name: realtor
skills: []
slug: realtor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: realtor\nurl: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: realtor:connections-plus-api\n    name: Realtor.com Connections Plus API\n    tags:\n      - Agents\n      - Brokers\n      - CRM\n      - Leads\n      - Real Estate\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://www.realtor.com/marketing/connections/\n    properties:\n      - url: https://www.realtor.com/marketing/connections/\n        type: Documentation\n      - url: asyncapi/realtor-connections-plus-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Realtor.com Connections Plus API provides a direct connection between the\n      Realtor.com lead delivery system and supporting CRM platforms. It enables real\n      estate agents, brokers, and offices to receive buyer and seller leads in real\n      time via API rather\
  \ than email. The API delivers richer lead data including\n      listing URLs, geographic coordinates, dates, and MLS information that are not\n      available through standard email delivery.\n  - aid: realtor:lead-delivery-api\n    name: Realtor.com Lead Delivery API\n    tags:\n      - CRM Integration\n      - Delivery\n      - Leads\n      - Notifications\n      - Real Estate\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://www.realtor.com/marketing/connections/\n    properties:\n      - url: https://www.realtor.com/marketing/connections/\n        type: Documentation\n      - url: asyncapi/realtor-lead-delivery-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Realtor.com Lead Delivery API is an end-to-end integration layer that delivers\n      real estate leads directly from Realtor.com to third-party CRM systems. It provides\n      faster and more secure lead delivery\
  \ compared to traditional email-based methods,\n      with consistent formatting and additional data fields.\n  - aid: realtor:property-data-api\n    name: Realtor.com Property Data API\n    tags:\n      - MLS\n      - Property Data\n      - Property Listings\n      - Real Estate\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://realtor.p.rapidapi.com\n    humanURL: https://rapidapi.com/apidojo/api/realty-in-us\n    properties:\n      - url: https://rapidapi.com/apidojo/api/realty-in-us\n        type: Documentation\n      - url: openapi/realtor-property-data-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Realtor.com Property Data API provides programmatic access to real estate\n      listing data from Realtor.com, one of the largest property listing platforms\n      in the United States. It offers endpoints for searching properties by location,\n      price range, bedrooms, bathrooms, and other\
  \ criteria, as well as retrieving\n      detailed property information including listing status, photos, and neighborhood\n      data.\ncommon:\n  - type: JSON-LD\n    url: json-ld/realtor-context.jsonld\n  - type: JSONSchema\n    url: json-schema/realtor-lead-schema.json\n  - type: JSONSchema\n    url: json-schema/realtor-property-schema.json\ndescription: >-\n  Realtor.com is an online real estate marketplace operated by Move, Inc., providing\n  home listings, neighborhood information, and tools for buyers, sellers, and renters.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/apis.yml
use_cases: []
---
