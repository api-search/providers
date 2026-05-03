---
api_count: 12
api_specs:
- filename: united-states-postal-service-addresses-openapi.yml
  format: yaml
  label: USPS Addresses API
  slug: usps-addresses-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-addresses-openapi.yml
- filename: united-states-postal-service-tracking-openapi.yml
  format: yaml
  label: USPS Tracking API
  slug: usps-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-tracking-openapi.yml
- filename: united-states-postal-service-domestic-prices-openapi.yml
  format: yaml
  label: USPS Domestic Prices API
  slug: usps-domestic-prices-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-domestic-prices-openapi.yml
- filename: united-states-postal-service-carrier-pickup-openapi.yml
  format: yaml
  label: USPS Carrier Pickup API
  slug: usps-carrier-pickup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/openapi/united-states-postal-service-carrier-pickup-openapi.yml
apis:
- description: 'Validates and corrects address information to USPS specifications, eliminating errors and improving package delivery. Supports full address standardization, city and state lookup by ZIP Code, and ZIP '
  name: USPS Addresses API
  slug: usps-addresses-api
- description: Returns tracking status and related details for a given USPS package, including scan events with date, time, and location. Supports single and batch package tracking. Version 3.2 includes enhanced sca
  name: USPS Tracking API
  slug: usps-tracking-api
- description: Provides postage pricing for domestic USPS shipments based on origin and destination ZIP Codes, weight, dimensions, and mail class. Supports base rate lookups, extra service rates (insurance, signatur
  name: USPS Domestic Prices API
  slug: usps-domestic-prices-api
- description: 'Enables free carrier pickup scheduling for next-day service, Monday through Saturday, excluding federal holidays. Supports creating, retrieving, updating, and canceling pickup requests at residential '
  name: USPS Carrier Pickup API
  slug: usps-carrier-pickup-api
- description: Provides pricing for international USPS products based on shipment characteristics including destination country, weight, dimensions, and service class.
  name: USPS International Prices API
  slug: usps-international-prices-api
- description: Creates domestic shipping labels with barcodes in multiple formats and generates Shipping Services Files. Requires USPS Ship enrollment and Enterprise Payment Account.
  name: USPS Domestic Labels API
  slug: usps-domestic-labels-api
- description: Creates international shipping labels and generates required Shipping Services Files for customs compliance.
  name: USPS International Labels API
  slug: usps-international-labels-api
- description: Identifies drop-off facilities and destination entry points for various USPS services. Supports post office locator and drop-off location finder.
  name: USPS Locations API
  slug: usps-locations-api
- description: Provides delivery benchmarks showing expected transit times between origin and destination ZIP Codes for USPS mail classes.
  name: USPS Service Standards API
  slug: usps-service-standards-api
- description: Returns a comprehensive list of pricing, service standards, and shipping options for USPS products in a single API call, eliminating the need to query multiple APIs separately.
  name: USPS Shipping Options API
  slug: usps-shipping-options-api
- description: Links multiple domestic and international labels through a single electronic file number, creating Shipment Confirmation Acceptance Notice forms for batch shipping operations.
  name: USPS SCAN Forms API
  slug: usps-scan-forms-api
- description: Industry-standard OAuth 2.0 Client Credentials authentication protecting access to all USPS APIs. Returns Bearer Tokens used in the Authorization header for all USPS API calls.
  name: USPS OAuth API
  slug: usps-oauth-api
capabilities:
- description: 'Unified workflow capability for e-commerce shipping operations. Combines the USPS Addresses, Domestic Prices, and Carrier Pickup APIs to support the complete shipping lifecycle: address validation at '
  name: USPS E-Commerce Shipping
  slug: ecommerce-shipping
- description: Workflow capability for package tracking and delivery status monitoring. Combines the USPS Tracking API with address validation to support customer service teams and logistics operations tracking USPS
  name: USPS Package Tracking
  slug: package-tracking
common:
- title: ''
  type: Portal
  url: https://developers.usps.com/
- title: ''
  type: GettingStarted
  url: https://developers.usps.com/getting-started
- title: ''
  type: Documentation
  url: https://developers.usps.com/apis
- title: ''
  type: TermsOfService
  url: https://developers.usps.com/terms-and-conditions
- title: ''
  type: FAQ
  url: https://developers.usps.com/faq
- title: ''
  type: Support
  url: https://emailus.usps.com/s/web-tools-inquiry
- title: ''
  type: GitHubOrganization
  url: https://github.com/USPS
- title: ''
  type: GitHubRepository
  url: https://github.com/USPS/api-examples
- title: ''
  type: SpectralRules
  url: rules/united-states-postal-service-spectral-rules.yml
- title: E-Commerce Shipping
  type: NaftikoCapability
  url: capabilities/ecommerce-shipping.yaml
- title: Package Tracking
  type: NaftikoCapability
  url: capabilities/package-tracking.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/united-states-postal-service-vocabulary.yaml
created: 2024/01/01
description: The United States Postal Service (USPS) provides a modern REST API platform at developers.usps.com that gives ecommerce websites, shipping software, and logistics systems access to postal data and services. APIs cover address validation, package tracking, domestic and international shipping labels, pricing, carrier pickup scheduling, location finding, and Informed Delivery campaign management. The legacy Web Tools platform was retired January 25, 2026, with all functionality migrated to the new OAuth 2.0-secured API platform.
features:
- description: Secure API access using industry-standard OAuth 2.0 Client Credentials flow with Bearer Token authentication.
  name: OAuth 2.0 Authentication
- description: All APIs follow RESTful conventions with JSON request and response bodies.
  name: RESTful Architecture
- description: Testing Environment for Mailers (TEM) at apis-tem.usps.com for safe API testing before going to production.
  name: Sandbox Testing Environment
- description: USPS Coding Accuracy Support System (CASS) compliant address validation and standardization.
  name: Address Standardization
- description: DPV confirmation codes ensure packages can be delivered to the validated address.
  name: Delivery Point Validation
- description: Live package tracking with scan events, timestamps, and location details from USPS systems.
  name: Real-Time Tracking
- description: Event-driven subscription APIs for tracking events, adjustments, and disputes delivered via webhooks.
  name: Webhook Subscriptions
- description: Support for bulk operations including multiple tracking lookups and SCAN Form generation.
  name: Batch Processing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: USPS shipping integration available through Shopify Shipping for label generation and rate calculation.
  name: Shopify
- description: WooCommerce shipping plugins integrate USPS APIs for rate calculation and label printing.
  name: WooCommerce
- description: Adobe Commerce and Magento integrate USPS for shipping rate display and fulfillment.
  name: Magento
- description: ShipStation multi-carrier shipping platform integrates USPS APIs for ecommerce fulfillment.
  name: ShipStation
- description: EasyPost shipping API aggregator provides access to USPS services alongside other carriers.
  name: EasyPost
- description: Stamps.com and Pitney Bowes shipping platforms integrate USPS APIs for postage and label printing.
  name: Stamps.com
jsonld:
- class_count: 3
  name: United States Postal Service Addresses Context
  property_count: 16
  slug: united-states-postal-service-addresses-context
- class_count: 5
  name: United States Postal Service Carrier Context
  property_count: 17
  slug: united-states-postal-service-carrier-context
- class_count: 8
  name: United States Postal Service Domestic Context
  property_count: 19
  slug: united-states-postal-service-domestic-context
- class_count: 4
  name: United States Postal Service Tracking Context
  property_count: 18
  slug: united-states-postal-service-tracking-context
layout: provider
modified: '2026-05-03'
name: United States Postal Service
rules:
- name: United States Postal Service API Rules
  rule_count: 33
  severity_counts:
    error: 13
    hint: 0
    info: 1
    warn: 19
  slug: united-states-postal-service-spectral-rules
skills: []
slug: united-states-postal-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: United States Postal Service\ndescription: >-\n  The United States Postal Service (USPS) provides a modern REST API platform at\n  developers.usps.com that gives ecommerce websites, shipping software, and logistics\n  systems access to postal data and services. APIs cover address validation, package\n  tracking, domestic and international shipping labels, pricing, carrier pickup\n  scheduling, location finding, and Informed Delivery campaign management. The legacy\n  Web Tools platform was retired January 25, 2026, with all functionality migrated\n  to the new OAuth 2.0-secured API platform.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/apis.yml\ncreated: '2024/01/01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Government\n  - Postal Service\n  - Shipping\n  - Logistics\n  - Address Validation\n  - Package Tracking\n\
  apis:\n  - name: USPS Addresses API\n    description: >-\n      Validates and corrects address information to USPS specifications, eliminating\n      errors and improving package delivery. Supports full address standardization,\n      city and state lookup by ZIP Code, and ZIP Code lookup by address.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/addressesv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Addresses\n      - Address Validation\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/addressesv3\n      - type: OpenAPI\n        url: openapi/united-states-postal-service-addresses-openapi.yml\n      - type: JSONSchema\n        url: json-schema/addresses-address-schema.json\n        title: Address Schema\n      - type: JSONSchema\n        url: json-schema/addresses-city-state-schema.json\n        title: City State Schema\n      - type:\
  \ JSONStructure\n        url: json-structure/addresses-address-structure.json\n        title: Address Structure\n      - type: JSON-LD\n        url: json-ld/united-states-postal-service-addresses-context.jsonld\n      - type: Example\n        url: examples/addresses-address-example.json\n        title: Address Example\n    aid: united-states-postal-service:usps-addresses-api\n  - name: USPS Tracking API\n    description: >-\n      Returns tracking status and related details for a given USPS package, including\n      scan events with date, time, and location. Supports single and batch package\n      tracking. Version 3.2 includes enhanced scan event extract notifications.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/trackingv3r2\n    baseURL: https://apis.usps.com\n    tags:\n      - Tracking\n      - Package Tracking\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/trackingv3r2\n\
  \      - type: OpenAPI\n        url: openapi/united-states-postal-service-tracking-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tracking-tracking-event-schema.json\n        title: Tracking Event Schema\n      - type: JSONStructure\n        url: json-structure/tracking-tracking-event-structure.json\n        title: Tracking Event Structure\n      - type: JSON-LD\n        url: json-ld/united-states-postal-service-tracking-context.jsonld\n      - type: Example\n        url: examples/tracking-tracking-event-example.json\n        title: Tracking Event Example\n    aid: united-states-postal-service:usps-tracking-api\n  - name: USPS Domestic Prices API\n    description: >-\n      Provides postage pricing for domestic USPS shipments based on origin and\n      destination ZIP Codes, weight, dimensions, and mail class. Supports base rate\n      lookups, extra service rates (insurance, signature confirmation, etc.), and\n      total rate calculations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://developers.usps.com/domesticpricesv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Pricing\n      - Postage\n      - Shipping\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/domesticpricesv3\n      - type: OpenAPI\n        url: openapi/united-states-postal-service-domestic-prices-openapi.yml\n      - type: JSONSchema\n        url: json-schema/domestic-prices-base-rate-request-schema.json\n        title: Base Rate Request Schema\n      - type: JSONStructure\n        url: json-structure/domestic-prices-base-rate-request-structure.json\n        title: Base Rate Request Structure\n      - type: JSON-LD\n        url: json-ld/united-states-postal-service-domestic-context.jsonld\n      - type: Example\n        url: examples/domestic-prices-base-rate-request-example.json\n        title: Base Rate Request Example\n    aid: united-states-postal-service:usps-domestic-prices-api\n  - name: USPS Carrier Pickup\
  \ API\n    description: >-\n      Enables free carrier pickup scheduling for next-day service, Monday through\n      Saturday, excluding federal holidays. Supports creating, retrieving, updating,\n      and canceling pickup requests at residential and commercial addresses.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/carrierpickupv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Carrier Pickup\n      - Shipping\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/carrierpickupv3\n      - type: OpenAPI\n        url: openapi/united-states-postal-service-carrier-pickup-openapi.yml\n      - type: JSONSchema\n        url: json-schema/carrier-pickup-pickup-request-schema.json\n        title: Pickup Request Schema\n      - type: JSONStructure\n        url: json-structure/carrier-pickup-pickup-request-structure.json\n        title: Pickup Request\
  \ Structure\n      - type: JSON-LD\n        url: json-ld/united-states-postal-service-carrier-context.jsonld\n      - type: Example\n        url: examples/carrier-pickup-pickup-request-example.json\n        title: Pickup Request Example\n    aid: united-states-postal-service:usps-carrier-pickup-api\n  - name: USPS International Prices API\n    description: >-\n      Provides pricing for international USPS products based on shipment\n      characteristics including destination country, weight, dimensions, and\n      service class.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/internationalpricesv3\n    baseURL: https://apis.usps.com\n    tags:\n      - International\n      - Pricing\n      - Postage\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/internationalpricesv3\n    aid: united-states-postal-service:usps-international-prices-api\n  - name:\
  \ USPS Domestic Labels API\n    description: >-\n      Creates domestic shipping labels with barcodes in multiple formats and\n      generates Shipping Services Files. Requires USPS Ship enrollment and\n      Enterprise Payment Account.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/domesticlabelsv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Labels\n      - Shipping\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/domesticlabelsv3\n    aid: united-states-postal-service:usps-domestic-labels-api\n  - name: USPS International Labels API\n    description: >-\n      Creates international shipping labels and generates required Shipping\n      Services Files for customs compliance.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/internationallabelsv3\n    baseURL:\
  \ https://apis.usps.com\n    tags:\n      - International\n      - Labels\n      - Shipping\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/internationallabelsv3\n    aid: united-states-postal-service:usps-international-labels-api\n  - name: USPS Locations API\n    description: >-\n      Identifies drop-off facilities and destination entry points for various\n      USPS services. Supports post office locator and drop-off location finder.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/locationsv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Locations\n      - Post Offices\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/locationsv3\n    aid: united-states-postal-service:usps-locations-api\n  - name: USPS Service Standards API\n    description: >-\n      Provides delivery benchmarks\
  \ showing expected transit times between origin\n      and destination ZIP Codes for USPS mail classes.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/standardsv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Service Standards\n      - Delivery\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/standardsv3\n    aid: united-states-postal-service:usps-service-standards-api\n  - name: USPS Shipping Options API\n    description: >-\n      Returns a comprehensive list of pricing, service standards, and shipping\n      options for USPS products in a single API call, eliminating the need to\n      query multiple APIs separately.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/shippingoptionsv3\n    baseURL: https://apis.usps.com\n    tags:\n      - Shipping\n     \
  \ - Pricing\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/shippingoptionsv3\n    aid: united-states-postal-service:usps-shipping-options-api\n  - name: USPS SCAN Forms API\n    description: >-\n      Links multiple domestic and international labels through a single\n      electronic file number, creating Shipment Confirmation Acceptance Notice\n      forms for batch shipping operations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/scanv3\n    baseURL: https://apis.usps.com\n    tags:\n      - SCAN Forms\n      - Shipping\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/scanv3\n    aid: united-states-postal-service:usps-scan-forms-api\n  - name: USPS OAuth API\n    description: >-\n      Industry-standard OAuth 2.0 Client Credentials authentication protecting\n      access to all USPS\
  \ APIs. Returns Bearer Tokens used in the Authorization\n      header for all USPS API calls.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.usps.com/Oauth\n    baseURL: https://apis.usps.com\n    tags:\n      - Authentication\n      - OAuth\n      - Government\n    properties:\n      - type: Documentation\n        url: https://developers.usps.com/Oauth\n      - type: Authentication\n        url: https://developers.usps.com/getting-started\n    aid: united-states-postal-service:usps-oauth-api\ncommon:\n  - type: Portal\n    url: https://developers.usps.com/\n  - type: GettingStarted\n    url: https://developers.usps.com/getting-started\n  - type: Documentation\n    url: https://developers.usps.com/apis\n  - type: TermsOfService\n    url: https://developers.usps.com/terms-and-conditions\n  - type: FAQ\n    url: https://developers.usps.com/faq\n  - type: Support\n    url: https://emailus.usps.com/s/web-tools-inquiry\n\
  \  - type: GitHubOrganization\n    url: https://github.com/USPS\n  - type: GitHubRepository\n    url: https://github.com/USPS/api-examples\n  - type: Features\n    data:\n      - name: OAuth 2.0 Authentication\n        description: Secure API access using industry-standard OAuth 2.0 Client Credentials flow with Bearer Token authentication.\n      - name: RESTful Architecture\n        description: All APIs follow RESTful conventions with JSON request and response bodies.\n      - name: Sandbox Testing Environment\n        description: Testing Environment for Mailers (TEM) at apis-tem.usps.com for safe API testing before going to production.\n      - name: Address Standardization\n        description: USPS Coding Accuracy Support System (CASS) compliant address validation and standardization.\n      - name: Delivery Point Validation\n        description: DPV confirmation codes ensure packages can be delivered to the validated address.\n      - name: Real-Time Tracking\n        description:\
  \ Live package tracking with scan events, timestamps, and location details from USPS systems.\n      - name: Webhook Subscriptions\n        description: Event-driven subscription APIs for tracking events, adjustments, and disputes delivered via webhooks.\n      - name: Batch Processing\n        description: Support for bulk operations including multiple tracking lookups and SCAN Form generation.\n  - type: UseCases\n    data:\n      - name: E-Commerce Shipping Integration\n        description: Calculate shipping rates, generate labels, and provide package tracking directly within e-commerce checkout flows.\n      - name: Address Verification at Checkout\n        description: Validate and standardize customer addresses during checkout to reduce failed deliveries and return rates.\n      - name: Shipping Label Generation\n        description: Programmatically create domestic and international USPS shipping labels with barcodes for fulfillment operations.\n      - name: Carrier Pickup Automation\n\
  \        description: Schedule and manage USPS carrier pickups automatically based on order fulfillment triggers.\n      - name: Logistics Rate Shopping\n        description: Compare USPS service options and pricing to select the most cost-effective shipping method.\n      - name: Delivery Time Estimation\n        description: Display accurate expected delivery dates to customers using USPS service standards data.\n      - name: Post Office Finder\n        description: Help customers locate the nearest USPS facility for drop-offs or in-person services.\n      - name: Informed Delivery Campaigns\n        description: Enhance customer engagement by adding digital content to mail pieces viewed through Informed Delivery.\n  - type: Integrations\n    data:\n      - name: Shopify\n        description: USPS shipping integration available through Shopify Shipping for label generation and rate calculation.\n      - name: WooCommerce\n        description: WooCommerce shipping plugins integrate USPS\
  \ APIs for rate calculation and label printing.\n      - name: Magento\n        description: Adobe Commerce and Magento integrate USPS for shipping rate display and fulfillment.\n      - name: ShipStation\n        description: ShipStation multi-carrier shipping platform integrates USPS APIs for ecommerce fulfillment.\n      - name: EasyPost\n        description: EasyPost shipping API aggregator provides access to USPS services alongside other carriers.\n      - name: Stamps.com\n        description: Stamps.com and Pitney Bowes shipping platforms integrate USPS APIs for postage and label printing.\n  - type: SpectralRules\n    url: rules/united-states-postal-service-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/ecommerce-shipping.yaml\n    title: E-Commerce Shipping\n  - type: NaftikoCapability\n    url: capabilities/package-tracking.yaml\n    title: Package Tracking\n  - type: Vocabulary\n    url: vocabulary/united-states-postal-service-vocabulary.yaml\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\naid: united-states-postal-service\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/apis.yml
tags:
- Government
- Postal Service
- Shipping
- Logistics
- Address Validation
- Package Tracking
url: https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/apis.yml
use_cases:
- description: Calculate shipping rates, generate labels, and provide package tracking directly within e-commerce checkout flows.
  name: E-Commerce Shipping Integration
- description: Validate and standardize customer addresses during checkout to reduce failed deliveries and return rates.
  name: Address Verification at Checkout
- description: Programmatically create domestic and international USPS shipping labels with barcodes for fulfillment operations.
  name: Shipping Label Generation
- description: Schedule and manage USPS carrier pickups automatically based on order fulfillment triggers.
  name: Carrier Pickup Automation
- description: Compare USPS service options and pricing to select the most cost-effective shipping method.
  name: Logistics Rate Shopping
- description: Display accurate expected delivery dates to customers using USPS service standards data.
  name: Delivery Time Estimation
- description: Help customers locate the nearest USPS facility for drop-offs or in-person services.
  name: Post Office Finder
- description: Enhance customer engagement by adding digital content to mail pieces viewed through Informed Delivery.
  name: Informed Delivery Campaigns
---
