---
api_count: 2
api_specs:
- filename: watttime-openapi.yml
  format: yaml
  label: WattTime API
  slug: watttime
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/openapi/watttime-openapi.yml
apis:
- description: 'The WattTime Data API v3 provides access to real-time, forecast, and historical marginal emissions data for electric grids worldwide. Key signals include CO2 MOER (Marginal Operating Emissions Rate), '
  name: WattTime API
  slug: watttime
- description: Official Python SDK for the WattTime API providing simplified access to real-time, forecast, and historical emissions data.
  name: WattTime Python Client
  slug: watttime-python-client
capabilities:
- description: Workflow capability combining WattTime's real-time, forecast, and historical emissions data to enable carbon-aware scheduling, sustainability reporting, and clean energy procurement decisions. Used by
  name: WattTime Carbon-Aware Computing
  slug: carbon-aware-computing
common:
- title: WattTime Website
  type: Portal
  url: https://watttime.org/
- title: API Documentation
  type: Documentation
  url: https://docs.watttime.org/
- title: API Release Notes
  type: ReleaseNotes
  url: https://watttime.org/data-science/release-notes/
- title: API Status Page
  type: StatusPage
  url: http://status.watttime.org/
- title: WattTime GitHub Organization
  type: GitHubOrganization
  url: https://github.com/WattTime
- title: Support Email
  type: Support
  url: mailto:support@watttime.org
- title: WattTime Spectral Rules
  type: SpectralRules
  url: rules/watttime-spectral-rules.yml
- title: Carbon-Aware Computing Capability
  type: NaftikoCapability
  url: capabilities/carbon-aware-computing.yaml
- title: WattTime Vocabulary
  type: Vocabulary
  url: vocabulary/watttime-vocabulary.yml
- title: WattTime JSON-LD Context
  type: JSON-LD
  url: json-ld/watttime-context.jsonld
created: '2025-05-02'
description: WattTime is a nonprofit organization that provides real-time, forecast, and historical data for electric grids around the world, enabling carbon-aware computing and clean energy procurement decisions. The WattTime API delivers marginal emissions data (CO2 MOER), health damage signals, average emissions rates, and renewable energy forecasts for 342 grid regions across 210 countries and territories. Developers and organizations use the API to schedule workloads during low-carbon windows, measure actual emissions reductions from clean energy procurement, and meet sustainability reporting requirements.
features:
- description: CO2 MOER signal providing real-time marginal carbon intensity for local grid regions, updated every 5 minutes via the forecast endpoint.
  name: Real-Time Marginal Emissions
- description: 24-72 hour ahead emissions forecasts enabling applications to schedule energy-intensive workloads during low-carbon grid windows.
  name: Emissions Forecasting
- description: Historical MOER data available for up to 32 days via the data endpoint, and multi-year historical datasets downloadable as CSV files.
  name: Historical Data Access
- description: Estimates the damage to human life and health caused by emissions from electricity generation based on time and location of consumption.
  name: Health Damage Signal
- description: Coverage across 342 grid regions in 210 countries and territories, including North America, Europe, and global expansion with synthetic demand proxy models.
  name: Global Grid Coverage
- description: Identify the relevant balancing authority for any geographic coordinates and retrieve the list of accessible grid regions.
  name: Grid Region Discovery
- description: Date-based model versioning (e.g., 2026-03-01) allowing unique versions per region and signal for reproducibility and comparison.
  name: Model Versioning
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: WattTime provides the carbon intensity data underlying the Green Software Foundation's Software Carbon Intensity (SCI) specification.
  name: Green Software Foundation
- description: WattTime contributes emissions data and modeling to the Climate TRACE global emissions inventory.
  name: Climate TRACE
- description: Official Green Software Foundation Impact Framework plugin available for integrating WattTime data into software sustainability measurements.
  name: Impact Framework
jsonld:
- class_count: 13
  name: Watttime Context
  property_count: 25
  slug: watttime-context
layout: provider
modified: '2026-05-03'
name: WattTime
rules:
- name: WattTime API Rules
  rule_count: 31
  severity_counts:
    error: 13
    hint: 0
    info: 1
    warn: 17
  slug: watttime-spectral-rules
skills: []
slug: watttime
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: watttime\nname: WattTime\ndescription: >-\n  WattTime is a nonprofit organization that provides real-time, forecast, and\n  historical data for electric grids around the world, enabling carbon-aware\n  computing and clean energy procurement decisions. The WattTime API delivers\n  marginal emissions data (CO2 MOER), health damage signals, average emissions\n  rates, and renewable energy forecasts for 342 grid regions across 210\n  countries and territories. Developers and organizations use the API to\n  schedule workloads during low-carbon windows, measure actual emissions\n  reductions from clean energy procurement, and meet sustainability reporting\n  requirements.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml\ntags:\n  - Emissions\n  - Climate\n  - Carbon\n  - Energy\n  - Electricity Grid\n  -\
  \ Sustainability\n  - Clean Energy\ncreated: '2025-05-02'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: watttime:watttime\n    name: WattTime API\n    description: >-\n      The WattTime Data API v3 provides access to real-time, forecast, and\n      historical marginal emissions data for electric grids worldwide. Key\n      signals include CO2 MOER (Marginal Operating Emissions Rate), health\n      damage estimates, and CO2 AOER (Average Operating Emissions Rate). The\n      API covers 342 grid regions in 210 countries and territories, with\n      real-time data updated every five minutes via the forecast endpoint.\n    humanURL: https://docs.watttime.org/\n    baseURL: https://api.watttime.org/v3\n    tags:\n      - Emissions\n      - Carbon\n      - Electricity Grid\n      - Marginal Emissions\n      - Forecasting\n      - Climate\n    properties:\n      - type: Documentation\n        url: https://docs.watttime.org/\n      - type: Documentation\n        url:\
  \ https://legacy-docs.watttime.org/\n        title: Legacy API v2 Documentation\n      - type: OpenAPI\n        url: openapi/watttime-openapi.yml\n      - type: JSONSchema\n        url: json-schema/watttime-data-point-schema.json\n        title: Data Point Schema\n      - type: JSONSchema\n        url: json-schema/watttime-data-response-schema.json\n        title: Data Response Schema\n      - type: JSONSchema\n        url: json-schema/watttime-forecast-response-schema.json\n        title: Forecast Response Schema\n      - type: JSONSchema\n        url: json-schema/watttime-region-response-schema.json\n        title: Region Response Schema\n      - type: JSONStructure\n        url: json-structure/watttime-data-point-structure.json\n        title: Data Point Structure\n      - type: JSONStructure\n        url: json-structure/watttime-data-response-structure.json\n        title: Data Response Structure\n  - aid: watttime:watttime-python-client\n    name: WattTime Python Client\n    description:\
  \ >-\n      Official Python SDK for the WattTime API providing simplified access to\n      real-time, forecast, and historical emissions data.\n    humanURL: https://github.com/WattTime/watttime-python-client\n    tags:\n      - Python\n      - SDK\n      - Client Library\n    properties:\n      - type: SDK\n        url: https://pypi.org/project/watttime/\n        title: Python SDK (PyPI)\n      - type: CodeExamples\n        url: https://github.com/WattTime/watttime-python-client\n        title: Python Client Examples\ncommon:\n  - type: Portal\n    url: https://watttime.org/\n    title: WattTime Website\n  - type: Documentation\n    url: https://docs.watttime.org/\n    title: API Documentation\n  - type: ReleaseNotes\n    url: https://watttime.org/data-science/release-notes/\n    title: API Release Notes\n  - type: StatusPage\n    url: http://status.watttime.org/\n    title: API Status Page\n  - type: GitHubOrganization\n    url: https://github.com/WattTime\n    title: WattTime GitHub\
  \ Organization\n  - type: Support\n    url: mailto:support@watttime.org\n    title: Support Email\n  - type: SpectralRules\n    url: rules/watttime-spectral-rules.yml\n    title: WattTime Spectral Rules\n  - type: NaftikoCapability\n    url: capabilities/carbon-aware-computing.yaml\n    title: Carbon-Aware Computing Capability\n  - type: Vocabulary\n    url: vocabulary/watttime-vocabulary.yml\n    title: WattTime Vocabulary\n  - type: JSON-LD\n    url: json-ld/watttime-context.jsonld\n    title: WattTime JSON-LD Context\n  - type: Features\n    data:\n      - name: Real-Time Marginal Emissions\n        description: >-\n          CO2 MOER signal providing real-time marginal carbon intensity for\n          local grid regions, updated every 5 minutes via the forecast\n          endpoint.\n      - name: Emissions Forecasting\n        description: >-\n          24-72 hour ahead emissions forecasts enabling applications to schedule\n          energy-intensive workloads during low-carbon grid\
  \ windows.\n      - name: Historical Data Access\n        description: >-\n          Historical MOER data available for up to 32 days via the data\n          endpoint, and multi-year historical datasets downloadable as CSV\n          files.\n      - name: Health Damage Signal\n        description: >-\n          Estimates the damage to human life and health caused by emissions from\n          electricity generation based on time and location of consumption.\n      - name: Global Grid Coverage\n        description: >-\n          Coverage across 342 grid regions in 210 countries and territories,\n          including North America, Europe, and global expansion with\n          synthetic demand proxy models.\n      - name: Grid Region Discovery\n        description: >-\n          Identify the relevant balancing authority for any geographic\n          coordinates and retrieve the list of accessible grid regions.\n      - name: Model Versioning\n        description: >-\n          Date-based model\
  \ versioning (e.g., 2026-03-01) allowing unique\n          versions per region and signal for reproducibility and comparison.\n  - type: UseCases\n    data:\n      - name: Carbon-Aware Computing\n        description: >-\n          Technology companies and cloud providers schedule compute workloads,\n          data transfers, and batch jobs to run during periods of low marginal\n          carbon intensity.\n      - name: Clean Energy Procurement\n        description: >-\n          Organizations measure the actual emissions reductions from renewable\n          energy procurement and power purchase agreements using marginal\n          emissions data.\n      - name: Sustainability Reporting\n        description: >-\n          Enterprises report Scope 2 emissions more accurately using marginal\n          emissions rates rather than average grid emission factors.\n      - name: Smart Building Optimization\n        description: >-\n          Building energy management systems shift heating, cooling,\
  \ and EV\n          charging to low-emission grid windows to reduce carbon footprint.\n      - name: Grid Research and Analysis\n        description: >-\n          Researchers, utilities, and policy makers analyze historical and\n          forecast emissions data to study grid decarbonization trends.\n  - type: Integrations\n    data:\n      - name: Green Software Foundation\n        description: >-\n          WattTime provides the carbon intensity data underlying the Green\n          Software Foundation's Software Carbon Intensity (SCI) specification.\n      - name: Climate TRACE\n        description: >-\n          WattTime contributes emissions data and modeling to the Climate TRACE\n          global emissions inventory.\n      - name: Impact Framework\n        description: >-\n          Official Green Software Foundation Impact Framework plugin available\n          for integrating WattTime data into software sustainability\n          measurements.\nmaintainers:\n  - FN: Kin Lane\n \
  \   email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml
tags:
- Emissions
- Climate
- Carbon
- Energy
- Electricity Grid
- Sustainability
- Clean Energy
url: https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml
use_cases:
- description: Technology companies and cloud providers schedule compute workloads, data transfers, and batch jobs to run during periods of low marginal carbon intensity.
  name: Carbon-Aware Computing
- description: Organizations measure the actual emissions reductions from renewable energy procurement and power purchase agreements using marginal emissions data.
  name: Clean Energy Procurement
- description: Enterprises report Scope 2 emissions more accurately using marginal emissions rates rather than average grid emission factors.
  name: Sustainability Reporting
- description: Building energy management systems shift heating, cooling, and EV charging to low-emission grid windows to reduce carbon footprint.
  name: Smart Building Optimization
- description: Researchers, utilities, and policy makers analyze historical and forecast emissions data to study grid decarbonization trends.
  name: Grid Research and Analysis
---
