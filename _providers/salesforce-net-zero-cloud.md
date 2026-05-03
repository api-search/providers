---
api_count: 3
api_specs:
- filename: salesforce-net-zero-cloud-rest-api-openapi.yml
  format: yaml
  label: Net Zero Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-net-zero-cloud/refs/heads/main/openapi/salesforce-net-zero-cloud-rest-api-openapi.yml
apis:
- description: 'REST API for managing carbon emissions data, sustainability records, and environmental impact tracking within Net Zero Cloud. Supports Scope 1, 2, and 3 emissions, energy consumption, waste disposal, '
  name: Net Zero Cloud REST API
  slug: ''
- description: API endpoints for carbon footprint calculations, emission factors, and sustainability metrics aggregation. Enables retrieval of emission factors and calculation of CO2e from activity data.
  name: Carbon Accounting API
  slug: ''
- description: API for accessing and managing sustainability data including energy consumption, waste management, water usage, and renewable energy tracking.
  name: Sustainability Data API
  slug: ''
capabilities:
- description: 'Unified workflow capability for carbon accounting and ESG reporting in Salesforce Net Zero Cloud. Combines carbon emission tracking, energy consumption monitoring, sustainability goal management, and '
  name: Salesforce Net Zero Cloud Carbon Accounting
  slug: carbon-accounting
common:
- title: ''
  type: Developer Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Getting Started
  url: https://trailhead.salesforce.com/content/learn/modules/net-zero-cloud-basics
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Trailhead Learning
  url: https://trailhead.salesforce.com/content/learn/trails/get-started-with-net-zero-cloud
- title: ''
  type: Release Notes
  url: https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/salesforce
- title: ''
  type: Spectral Rules
  url: rules/salesforce-net-zero-cloud-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/carbon-accounting.yaml
- title: Carbon Emission Schema
  type: JSON Schema
  url: json-schema/salesforce-net-zero-cloud-carbon-emission-schema.json
- title: Sustainability Goal Schema
  type: JSON Schema
  url: json-schema/salesforce-net-zero-cloud-sustainability-goal-schema.json
- title: ''
  type: JSON-LD Context
  url: json-ld/salesforce-net-zero-cloud-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-net-zero-cloud-vocabulary.yml
created: '2024'
description: The Salesforce Net Zero Cloud API enables organizations to track, analyze, and report on their carbon emissions and sustainability data. It provides programmatic access to environmental data, carbon accounting, and ESG reporting capabilities including Scope 1, 2, and 3 emissions tracking, energy consumption, waste management, water usage, and sustainability goal management.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/logo-salesforce.svg
integrations: []
jsonld:
- class_count: 0
  name: Salesforce Net Zero Cloud Context
  property_count: 26
  slug: salesforce-net-zero-cloud-context
layout: provider
modified: '2026-05-02'
name: Salesforce Net Zero Cloud
rules:
- name: Salesforce Net Zero Cloud API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 4
  slug: salesforce-net-zero-cloud-rules
skills: []
slug: salesforce-net-zero-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Net Zero Cloud\ndescription: >-\n  The Salesforce Net Zero Cloud API enables organizations to track, analyze, and report\n  on their carbon emissions and sustainability data. It provides programmatic access\n  to environmental data, carbon accounting, and ESG reporting capabilities including\n  Scope 1, 2, and 3 emissions tracking, energy consumption, waste management,\n  water usage, and sustainability goal management.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/logo-salesforce.svg\nurl: https://www.salesforce.com/products/net-zero-cloud/overview/\ncreated: '2024'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Carbon Accounting\n  - Carbon Emissions\n  - Climate\n  - Environmental\n  - ESG\n  - Net Zero\n  - Sustainability\napis:\n  - name: Net Zero Cloud REST API\n    description: >-\n      REST API for managing carbon emissions data, sustainability records, and environmental\n      impact tracking within Net Zero\
  \ Cloud. Supports Scope 1, 2, and 3 emissions,\n      energy consumption, waste disposal, water withdrawal, and sustainability goals.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/logo-salesforce.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\n    baseURL: https://yourinstance.my.salesforce.com/services/data/v59.0/\n    tags:\n      - Carbon Emissions\n      - Emissions Tracking\n      - REST\n      - Sustainability\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\n      - type: OpenAPI\n        url: openapi/salesforce-net-zero-cloud-rest-api-openapi.yml\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n      - type: Rate Limits\n        url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/\n\
  \    contact:\n      - type: Support\n        url: https://help.salesforce.com/\n  - name: Carbon Accounting API\n    description: >-\n      API endpoints for carbon footprint calculations, emission factors, and sustainability\n      metrics aggregation. Enables retrieval of emission factors and calculation of\n      CO2e from activity data.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\n    baseURL: https://yourinstance.my.salesforce.com/services/data/v59.0/\n    tags:\n      - Carbon Accounting\n      - Emission Factors\n      - Footprint Calculation\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\n  - name: Sustainability Data API\n    description: >-\n      API for accessing and managing sustainability data including energy consumption,\n      waste management, water usage, and renewable energy tracking.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\n\
  \    baseURL: https://yourinstance.my.salesforce.com/services/data/v59.0/\n    tags:\n      - Energy Consumption\n      - Sustainability Data\n      - Waste Management\n      - Water Usage\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.netzero_api.meta/netzero_api/\ncommon:\n  - type: Developer Portal\n    url: https://developer.salesforce.com/\n  - type: Getting Started\n    url: https://trailhead.salesforce.com/content/learn/modules/net-zero-cloud-basics\n  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: Trailhead Learning\n    url: https://trailhead.salesforce.com/content/learn/trails/get-started-with-net-zero-cloud\n\
  \  - type: Release Notes\n    url: https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: GitHub Organization\n    url: https://github.com/salesforce\n  - type: Spectral Rules\n    url: rules/salesforce-net-zero-cloud-rules.yml\n  - type: Capabilities\n    url: capabilities/carbon-accounting.yaml\n  - type: JSON Schema\n    url: json-schema/salesforce-net-zero-cloud-carbon-emission-schema.json\n    title: Carbon Emission Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-net-zero-cloud-sustainability-goal-schema.json\n    title: Sustainability Goal Schema\n  - type: JSON-LD Context\n    url: json-ld/salesforce-net-zero-cloud-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/salesforce-net-zero-cloud-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-net-zero-cloud/refs/heads/main/apis.yml
tags:
- Carbon Accounting
- Carbon Emissions
- Climate
- Environmental
- ESG
- Net Zero
- Sustainability
url: https://www.salesforce.com/products/net-zero-cloud/overview/
use_cases: []
---
