---
api_count: 2
api_specs:
- filename: xcel-energy-green-button-api.yaml
  format: yaml
  label: Xcel Energy Green Button Connect My Data API
  slug: xcel-energy-green-button-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/openapi/xcel-energy-green-button-api.yaml
- filename: xcel-energy-smart-meter-api.yaml
  format: yaml
  label: Xcel Energy Smart Meter IEEE 2030.5 API
  slug: xcel-energy-smart-meter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/openapi/xcel-energy-smart-meter-api.yaml
apis:
- description: Green Button Connect My Data API based on the ESPI (Energy Services Provider Interface) standard developed by NAESB. Enables authorized third-party applications to access customer electricity and natu
  name: Xcel Energy Green Button Connect My Data API
  slug: xcel-energy-green-button-api
- description: IEEE 2030.5 compliant API server built into Itron Gen 5 Riva smart meters deployed by Xcel Energy. Provides real-time and time-delineated energy usage data including solar production information direc
  name: Xcel Energy Smart Meter IEEE 2030.5 API
  slug: xcel-energy-smart-meter-api
capabilities: []
common:
- title: ''
  type: DeveloperPortal
  url: https://developer-apim.aws.xcelenergy.com/
- title: ''
  type: Portal
  url: https://developer-apim.aws.xcelenergy.com/
- title: ''
  type: SignUp
  url: https://developer-apim.aws.xcelenergy.com/register
- title: ''
  type: Login
  url: https://developer-apim.aws.xcelenergy.com/login
- title: ''
  type: TermsOfService
  url: https://developer-apim.aws.xcelenergy.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.xcelenergy.com/privacy_policy
- title: ''
  type: Support
  url: https://www.xcelenergy.com/contact_us
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/xcel-energy
- title: ''
  type: X
  url: https://twitter.com/xcelenergy
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/XcelEnergyVideo
created: '2024-01-01'
description: 'Xcel Energy is a major U.S. electricity and natural gas utility holding company headquartered in Minneapolis, Minnesota, providing service to approximately 3.7 million electricity customers and 2.1 million natural gas customers across eight Midwestern and Western states: Colorado, Minnesota, Texas, New Mexico, North Dakota, South Dakota, Michigan, and Wisconsin. Xcel Energy operates a developer portal at developer-apim.aws.xcelenergy.com that organizes APIs across customer account management, billing, payments, product and service offerings, and request service. The company provides Green Button Connect My Data APIs based on the ESPI (Energy Services Provider Interface) standard developed by NAESB, enabling authorized third-party applications to access customer energy usage data via OAuth 2.0. Xcel Energy also supports IEEE 2030.5 protocol on newer Itron Gen 5 Riva smart meters for direct local-network access to real-time energy data including solar production. Beyond data
  APIs, Xcel Energy is a Fortune 500 company investing in clean energy, grid modernization, electric vehicle programs, demand response, and renewable energy interconnection.'
features:
- description: OAuth 2.0 authorized API access to customer electricity and natural gas usage data following the ESPI standard.
  name: Green Button Connect My Data
- description: Direct local-network access to real-time energy data including solar production from Itron Gen 5 Riva meters.
  name: IEEE 2030.5 Smart Meter API
- description: API category covering customer account profile, preferences, and service management.
  name: Customer Account Management
- description: API category for billing data, statements, and billing account operations.
  name: Billing & Billing Account Management
- description: API category for payment processing and payment service operations against customer accounts.
  name: Payments & Payment Services
- description: API category covering Xcel Energy product and service catalog and program enrollment.
  name: Product & Service Offerings
- description: API category for service requests, support workflows, and customer help operations.
  name: Request Service & Help
- description: Interval and billing-quality energy usage data captured from Xcel Energy smart meters across electricity and natural gas.
  name: Smart Meter Data
- description: Programs that allow utilities and third parties to coordinate load reduction events with smart meter and DER endpoints.
  name: Demand Response Integration
- description: Solar production data exposed through smart meter endpoints for customers with on-site photovoltaic systems.
  name: Solar Interconnection Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Certified Green Button Connect My Data implementation interoperable with the Green Button ecosystem.
  name: Green Button Alliance
- description: Implements the North American Energy Standards Board Energy Services Provider Interface standard for energy usage data.
  name: NAESB ESPI
- description: Smart Energy Profile 2.0 standard implemented on Itron Gen 5 Riva meters for local device APIs.
  name: IEEE 2030.5
- description: Smart meter deployments use Itron Gen 5 Riva devices that host the IEEE 2030.5 server.
  name: Itron
- description: Whole-building benchmarking workflows can consume Green Button data for commercial customers.
  name: ENERGY STAR Portfolio Manager
- description: Authorization framework used for customer-consented access to Green Button Connect My Data.
  name: OAuth 2.0
layout: provider
modified: '2026-05-03'
name: Xcel Energy
skills: []
slug: xcel-energy
solutions:
- description: Residential energy usage, billing, and program enrollment across electricity and natural gas service.
  name: Residential Customers
- description: Commercial and industrial customer programs, rates, and aggregated usage data.
  name: Business Customers
- description: Authorized energy management, demand response, and sustainability service providers consuming Green Button data.
  name: Third-Party Service Providers
- description: Contractors, installers, and program partners delivering energy efficiency and renewable installations.
  name: Trade Partners
- description: Anonymized and customer-authorized data access for academic and policy research.
  name: Researchers and Policy Analysts
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xcel-energy\nname: Xcel Energy\ndescription: >-\n  Xcel Energy is a major U.S. electricity and natural gas utility holding\n  company headquartered in Minneapolis, Minnesota, providing service to\n  approximately 3.7 million electricity customers and 2.1 million natural\n  gas customers across eight Midwestern and Western states: Colorado,\n  Minnesota, Texas, New Mexico, North Dakota, South Dakota, Michigan, and\n  Wisconsin. Xcel Energy operates a developer portal at\n  developer-apim.aws.xcelenergy.com that organizes APIs across customer\n  account management, billing, payments, product and service offerings,\n  and request service. The company provides Green Button Connect My Data\n  APIs based on the ESPI (Energy Services Provider Interface) standard\n  developed by NAESB, enabling authorized third-party applications to\n  access customer energy usage data via OAuth 2.0. Xcel Energy also\n  supports IEEE 2030.5 protocol on newer Itron Gen 5 Riva smart meters\n  for\
  \ direct local-network access to real-time energy data including\n  solar production. Beyond data APIs, Xcel Energy is a Fortune 500\n  company investing in clean energy, grid modernization, electric vehicle\n  programs, demand response, and renewable energy interconnection.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Electric Utility\n  - Energy\n  - Energy Data\n  - Green Button\n  - Natural Gas\n  - Smart Grid\n  - Smart Meter\n  - Utility\n  - ESPI\n  - IEEE 2030.5\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: xcel-energy:xcel-energy-green-button-api\n    name: Xcel Energy Green Button Connect My Data API\n    description: >-\n      Green Button Connect My Data API based on the ESPI (Energy Services\n      Provider Interface) standard developed by NAESB. Enables authorized\n \
  \     third-party applications to access customer electricity and natural\n      gas usage data from Xcel Energy smart meters. Supports RESTful\n      access to metered resource data including usage intervals, billing\n      data, and meter readings. Customer authorization is granted via\n      OAuth 2.0 and follows the Green Button Connect specification used\n      by utilities across North America.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer-apim.aws.xcelenergy.com/\n    baseURL: https://api.xcelenergy.com\n    tags:\n      - Energy Data\n      - Green Button\n      - ESPI\n      - Smart Meter\n      - Usage Data\n      - OAuth 2.0\n    properties:\n      - type: Documentation\n        url: https://developer-apim.aws.xcelenergy.com/\n      - type: DeveloperPortal\n        url: https://developer-apim.aws.xcelenergy.com/\n      - type: Authentication\n        url: https://developer-apim.aws.xcelenergy.com/login\n\
  \      - type: OpenAPI\n        url: openapi/xcel-energy-green-button-api.yaml\n    contact:\n      - type: Support\n        url: https://developer-apim.aws.xcelenergy.com/\n  - aid: xcel-energy:xcel-energy-smart-meter-api\n    name: Xcel Energy Smart Meter IEEE 2030.5 API\n    description: >-\n      IEEE 2030.5 compliant API server built into Itron Gen 5 Riva smart\n      meters deployed by Xcel Energy. Provides real-time and\n      time-delineated energy usage data including solar production\n      information directly from the meter device on the local network.\n      Supports meter reading, usage monitoring, and demand response\n      integration following the Smart Energy Profile 2.0 (IEEE 2030.5)\n      specification.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer-apim.aws.xcelenergy.com/\n    tags:\n      - IEEE 2030.5\n      - Smart Meter\n      - Energy Usage\n      - Solar\n      - Demand Response\n     \
  \ - Local Network\n    properties:\n      - type: Documentation\n        url: https://developer-apim.aws.xcelenergy.com/\n      - type: DeveloperPortal\n        url: https://developer-apim.aws.xcelenergy.com/\n      - type: OpenAPI\n        url: openapi/xcel-energy-smart-meter-api.yaml\ncommon:\n  - type: DeveloperPortal\n    url: https://developer-apim.aws.xcelenergy.com/\n  - type: Portal\n    url: https://developer-apim.aws.xcelenergy.com/\n  - type: SignUp\n    url: https://developer-apim.aws.xcelenergy.com/register\n  - type: Login\n    url: https://developer-apim.aws.xcelenergy.com/login\n  - type: TermsOfService\n    url: https://developer-apim.aws.xcelenergy.com/terms\n  - type: PrivacyPolicy\n    url: https://www.xcelenergy.com/privacy_policy\n  - type: Support\n    url: https://www.xcelenergy.com/contact_us\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/xcel-energy\n  - type: X\n    url: https://twitter.com/xcelenergy\n  - type: YouTube\n    url: https://www.youtube.com/user/XcelEnergyVideo\n\
  \  - type: Features\n    data:\n      - name: Green Button Connect My Data\n        description: >-\n          OAuth 2.0 authorized API access to customer electricity and\n          natural gas usage data following the ESPI standard.\n      - name: IEEE 2030.5 Smart Meter API\n        description: >-\n          Direct local-network access to real-time energy data including\n          solar production from Itron Gen 5 Riva meters.\n      - name: Customer Account Management\n        description: >-\n          API category covering customer account profile, preferences,\n          and service management.\n      - name: Billing & Billing Account Management\n        description: >-\n          API category for billing data, statements, and billing account\n          operations.\n      - name: Payments & Payment Services\n        description: >-\n          API category for payment processing and payment service\n          operations against customer accounts.\n      - name: Product & Service\
  \ Offerings\n        description: >-\n          API category covering Xcel Energy product and service catalog\n          and program enrollment.\n      - name: Request Service & Help\n        description: >-\n          API category for service requests, support workflows, and\n          customer help operations.\n      - name: Smart Meter Data\n        description: >-\n          Interval and billing-quality energy usage data captured from\n          Xcel Energy smart meters across electricity and natural gas.\n      - name: Demand Response Integration\n        description: >-\n          Programs that allow utilities and third parties to coordinate\n          load reduction events with smart meter and DER endpoints.\n      - name: Solar Interconnection Data\n        description: >-\n          Solar production data exposed through smart meter endpoints for\n          customers with on-site photovoltaic systems.\n  - type: UseCases\n    data:\n      - name: Energy Management Applications\n\
  \        description: >-\n          Third-party apps that help customers track and reduce\n          electricity and natural gas usage.\n      - name: Solar Monitoring\n        description: >-\n          Applications that track on-site solar production and\n          consumption from IEEE 2030.5 smart meters.\n      - name: Home Energy Automation\n        description: >-\n          Smart home and HVAC systems that automate energy use based on\n          real-time meter data.\n      - name: Sustainability Reporting\n        description: >-\n          Commercial customers reporting carbon and energy data for ESG\n          and sustainability disclosures.\n      - name: Building Performance Benchmarking\n        description: >-\n          Whole-building energy benchmarking for ENERGY STAR Portfolio\n          Manager and similar tools.\n      - name: Demand Response Programs\n        description: >-\n          Aggregators and DER providers integrating with utility\n          dispatch signals.\n\
  \      - name: Electric Vehicle Charging Optimization\n        description: >-\n          EV charging applications that schedule charging based on\n          time-of-use rates and grid conditions.\n      - name: Research and Policy Analysis\n        description: >-\n          Academic and policy research on energy consumption patterns and\n          decarbonization.\n  - type: Integrations\n    data:\n      - name: Green Button Alliance\n        description: >-\n          Certified Green Button Connect My Data implementation\n          interoperable with the Green Button ecosystem.\n      - name: NAESB ESPI\n        description: >-\n          Implements the North American Energy Standards Board Energy\n          Services Provider Interface standard for energy usage data.\n      - name: IEEE 2030.5\n        description: >-\n          Smart Energy Profile 2.0 standard implemented on Itron Gen 5\n          Riva meters for local device APIs.\n      - name: Itron\n        description: >-\n\
  \          Smart meter deployments use Itron Gen 5 Riva devices that host\n          the IEEE 2030.5 server.\n      - name: ENERGY STAR Portfolio Manager\n        description: >-\n          Whole-building benchmarking workflows can consume Green Button\n          data for commercial customers.\n      - name: OAuth 2.0\n        description: >-\n          Authorization framework used for customer-consented access to\n          Green Button Connect My Data.\n  - type: Solutions\n    data:\n      - name: Residential Customers\n        description: >-\n          Residential energy usage, billing, and program enrollment\n          across electricity and natural gas service.\n      - name: Business Customers\n        description: >-\n          Commercial and industrial customer programs, rates, and\n          aggregated usage data.\n      - name: Third-Party Service Providers\n        description: >-\n          Authorized energy management, demand response, and\n          sustainability service\
  \ providers consuming Green Button data.\n      - name: Trade Partners\n        description: >-\n          Contractors, installers, and program partners delivering\n          energy efficiency and renewable installations.\n      - name: Researchers and Policy Analysts\n        description: >-\n          Anonymized and customer-authorized data access for academic\n          and policy research.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/apis.yml
tags:
- Electric Utility
- Energy
- Energy Data
- Green Button
- Natural Gas
- Smart Grid
- Smart Meter
- Utility
- ESPI
- IEEE 2030.5
url: https://raw.githubusercontent.com/api-evangelist/xcel-energy/refs/heads/main/apis.yml
use_cases:
- description: Third-party apps that help customers track and reduce electricity and natural gas usage.
  name: Energy Management Applications
- description: Applications that track on-site solar production and consumption from IEEE 2030.5 smart meters.
  name: Solar Monitoring
- description: Smart home and HVAC systems that automate energy use based on real-time meter data.
  name: Home Energy Automation
- description: Commercial customers reporting carbon and energy data for ESG and sustainability disclosures.
  name: Sustainability Reporting
- description: Whole-building energy benchmarking for ENERGY STAR Portfolio Manager and similar tools.
  name: Building Performance Benchmarking
- description: Aggregators and DER providers integrating with utility dispatch signals.
  name: Demand Response Programs
- description: EV charging applications that schedule charging based on time-of-use rates and grid conditions.
  name: Electric Vehicle Charging Optimization
- description: Academic and policy research on energy consumption patterns and decarbonization.
  name: Research and Policy Analysis
---
