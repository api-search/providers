---
api_count: 6
api_specs:
- filename: amazon-selling-partner-api-openapi.yml
  format: yaml
  label: Amazon Selling Partner API
  slug: selling-partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-selling-partner-api-openapi.yml
- filename: amazon-advertising-api-openapi.yml
  format: yaml
  label: Amazon Advertising API
  slug: advertising-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-advertising-api-openapi.yml
- filename: amazon-pay-api-openapi.yml
  format: yaml
  label: Amazon Pay API
  slug: pay-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/openapi/amazon-pay-api-openapi.yml
apis:
- description: 'The Amazon Selling Partner API (SP-API) is a RESTful API that enables Amazon sellers and vendors to programmatically manage their marketplace operations including listings, orders, payments, reports, '
  name: Amazon Selling Partner API
  slug: selling-partner-api
- description: The Amazon Advertising API enables programmatic management of advertising campaigns on Amazon including Sponsored Products, Sponsored Brands, and Sponsored Display campaigns across various marketplace
  name: Amazon Advertising API
  slug: advertising-api
- description: The Amazon Creators API provides programmatic access to Amazon product data for publishers, influencers, and affiliate partners. It is the recommended replacement for the Product Advertising API and r
  name: Amazon Creators API
  slug: creators-api
- description: The Amazon Pay API enables merchants to integrate Amazon Pay for payment processing on their websites and mobile applications. It supports one-time purchases, subscriptions, and recurring payments wit
  name: Amazon Pay API
  slug: pay-api
- description: The Alexa Skills Kit (ASK) REST APIs enable developers to create, manage, test, and deploy custom voice skills for Alexa-enabled devices including skill manifest management, interaction model building
  name: Amazon Alexa Skills Kit API
  slug: alexa-skills-kit-api
- description: The Amazon Appstore Developer APIs provide tools for managing app submissions, testing, and monetization through in-app purchases on the Amazon Appstore for Android and Fire OS applications.
  name: Amazon Appstore API
  slug: appstore-api
capabilities:
- description: Unified workflow for Amazon sellers, advertisers, and merchants to manage marketplace listings and orders, run advertising campaigns, and process payments using Amazon Selling Partner API, Amazon Adve
  name: Amazon Seller and Commerce Workflow
  slug: amazon-seller-and-commerce
common:
- title: ''
  type: Portal
  url: https://developer.amazon.com/
- title: ''
  type: Website
  url: https://www.amazon.com/
- title: ''
  type: Documentation
  url: https://developer.amazon.com/docs/
- title: ''
  type: TermsOfService
  url: https://developer.amazon.com/support/legal/da
- title: ''
  type: PrivacyPolicy
  url: https://www.amazon.com/gp/help/customer/display.html?nodeId=468496
- title: ''
  type: Support
  url: https://developer.amazon.com/support
- title: ''
  type: GitHubOrganization
  url: https://github.com/amzn
- title: ''
  type: Console
  url: https://developer.amazon.com/dashboard
- title: ''
  type: SignUp
  url: https://www.amazon.com/ap/register?openid.assoc_handle=aws
- title: ''
  type: Login
  url: https://developer.amazon.com/login
- title: ''
  type: Blog
  url: https://developer.amazon.com/blogs/
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/AmazonDeveloper
- title: ''
  type: Contact
  url: https://www.amazon.com/gp/help/customer/contact-us
- title: ''
  type: JSONLD
  url: json-ld/amazon-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/amazon-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-seller-and-commerce.yaml
created: '2024-01-15'
description: Amazon is a global technology and e-commerce company offering a wide range of consumer and developer APIs including the Selling Partner API for marketplace sellers, Advertising API for campaign management, Amazon Pay for payments, Alexa Skills Kit for voice experiences, Amazon Appstore for mobile applications, and the Creators API for affiliate publishers. These APIs power Amazon's ecosystem of sellers, developers, advertisers, and content creators.
features:
- description: Full lifecycle management of Amazon marketplace seller operations including catalog, inventory, orders, shipping, and financial reporting.
  name: Marketplace Seller Operations
- description: Create and optimize Sponsored Products, Sponsored Brands, and Sponsored Display advertising campaigns with granular targeting and reporting.
  name: Programmatic Advertising
- description: Enable Amazon Pay on external websites and mobile apps with checkout session management, one-time charges, subscriptions, and refunds.
  name: Amazon Pay Integration
- description: Build Alexa voice skills for Echo devices, Fire TV, and third-party Alexa-enabled hardware with the Alexa Skills Kit.
  name: Voice Experience Development
- description: Access Amazon product data for affiliate marketing and content creation through the Creators API with product search and deep linking.
  name: Affiliate and Creator Commerce
- description: Publish and monetize apps on the Amazon Appstore with in-app purchasing for digital goods, subscriptions, and consumables.
  name: Mobile App Monetization
- description: Access North America, Europe, and Far East marketplaces through region-specific SP-API endpoints.
  name: Multi-Region Marketplace Support
- description: Sandbox environments, developer consoles, and testing tools for building and validating Amazon integrations before going live.
  name: Developer Console and Testing Tools
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: SP-API is the modern replacement for the deprecated Amazon Marketplace Web Service (MWS) for all seller operations.
  name: Amazon MWS Legacy Migration
- description: Integrate smart home devices and services with Alexa voice control using the Smart Home Skill API.
  name: Alexa Smart Home
- description: OAuth 2.0 authentication for all Amazon developer APIs including SP-API, Advertising API, and ASK via Login with Amazon (LWA).
  name: Login with Amazon
- description: Affiliate program integration for the Creators API and Product Advertising API for commission-based product promotion.
  name: Amazon Associates Program
- description: Amazon Appstore SDK for Fire OS and Android apps with in-app purchasing and device targeting capabilities.
  name: Fire OS and Android
jsonld:
- class_count: 53
  name: Amazon Context
  property_count: 113
  slug: amazon-context
layout: provider
modified: '2026-04-19'
name: Amazon
rules:
- name: Amazon API Rules
  rule_count: 15
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 6
  slug: amazon-spectral-rules
skills: []
slug: amazon
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon\nname: Amazon\ndescription: >-\n  Amazon is a global technology and e-commerce company offering a wide range of\n  consumer and developer APIs including the Selling Partner API for marketplace\n  sellers, Advertising API for campaign management, Amazon Pay for payments,\n  Alexa Skills Kit for voice experiences, Amazon Appstore for mobile\n  applications, and the Creators API for affiliate publishers. These APIs power\n  Amazon's ecosystem of sellers, developers, advertisers, and content creators.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Amazon\n  - Advertising\n  - Alexa\n  - E-Commerce\n  - Marketplace\n  - Payments\n  - Voice\napis:\n  - aid: amazon:selling-partner-api\n    name: Amazon Selling Partner API\n    tags:\n      - E-Commerce\n\
  \      - Fulfillment\n      - Marketplace\n      - Orders\n      - Sellers\n    humanURL: https://developer-docs.amazon.com/sp-api\n    baseURL: https://sellingpartnerapi-na.amazon.com\n    properties:\n      - type: Documentation\n        url: https://developer-docs.amazon.com/sp-api\n      - type: OpenAPI\n        url: openapi/amazon-selling-partner-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/selling-partner-order-schema.json\n    description: >-\n      The Amazon Selling Partner API (SP-API) is a RESTful API that enables\n      Amazon sellers and vendors to programmatically manage their marketplace\n      operations including listings, orders, payments, reports, and fulfillment.\n      It replaces the deprecated Amazon Marketplace Web Service (MWS) and\n      provides access to region-specific endpoints for North America, Europe,\n      and Far East marketplaces.\n\n  - aid: amazon:advertising-api\n    name: Amazon Advertising API\n    tags:\n      - Advertising\n\
  \      - Campaigns\n      - Marketing\n      - Sponsored Products\n    humanURL: https://advertising.amazon.com/API/docs/en-us/reference/api-overview\n    baseURL: https://advertising-api.amazon.com\n    properties:\n      - type: Documentation\n        url: https://advertising.amazon.com/API/docs/en-us/reference/api-overview\n      - type: OpenAPI\n        url: openapi/amazon-advertising-api-openapi.yml\n    description: >-\n      The Amazon Advertising API enables programmatic management of advertising\n      campaigns on Amazon including Sponsored Products, Sponsored Brands, and\n      Sponsored Display campaigns across various marketplaces. Developers can\n      create, manage, and optimize campaigns, access reporting data, and manage\n      budgets and targeting.\n\n  - aid: amazon:creators-api\n    name: Amazon Creators API\n    tags:\n      - Affiliates\n      - Content Creators\n      - E-Commerce\n      - Products\n    humanURL: https://affiliate-program.amazon.com/creatorsapi/docs/en-us/introduction\n\
  \    baseURL: https://affiliate-program.amazon.com/creatorsapi\n    properties:\n      - type: Documentation\n        url: https://affiliate-program.amazon.com/creatorsapi/docs/en-us/introduction\n    description: >-\n      The Amazon Creators API provides programmatic access to Amazon product data\n      for publishers, influencers, and affiliate partners. It is the recommended\n      replacement for the Product Advertising API and requires Amazon Associates\n      membership with qualifying sales history.\n\n  - aid: amazon:pay-api\n    name: Amazon Pay API\n    tags:\n      - Checkout\n      - E-Commerce\n      - Payments\n      - Subscriptions\n    humanURL: https://developer.amazon.com/docs/amazon-pay-api-v2/introduction.html\n    baseURL: https://pay-api.amazon.com\n    properties:\n      - type: Documentation\n        url: https://developer.amazon.com/docs/amazon-pay-api-v2/introduction.html\n      - type: OpenAPI\n        url: openapi/amazon-pay-api-openapi.yml\n    description:\
  \ >-\n      The Amazon Pay API enables merchants to integrate Amazon Pay for payment\n      processing on their websites and mobile applications. It supports one-time\n      purchases, subscriptions, and recurring payments with checkout session\n      management, charge operations, and refund capabilities.\n\n  - aid: amazon:alexa-skills-kit-api\n    name: Amazon Alexa Skills Kit API\n    tags:\n      - Alexa\n      - Skills\n      - Smart Home\n      - Voice\n    humanURL: https://developer.amazon.com/en-US/docs/alexa/rest-apis/rest-apis.html\n    baseURL: https://api.amazonalexa.com\n    properties:\n      - type: Documentation\n        url: https://developer.amazon.com/en-US/docs/alexa/rest-apis/rest-apis.html\n    description: >-\n      The Alexa Skills Kit (ASK) REST APIs enable developers to create, manage,\n      test, and deploy custom voice skills for Alexa-enabled devices including\n      skill manifest management, interaction model building, and hosted skill\n      management\
  \ for voice experiences and smart home integrations.\n\n  - aid: amazon:appstore-api\n    name: Amazon Appstore API\n    tags:\n      - App Store\n      - Apps\n      - In-App Purchases\n      - Mobile\n    humanURL: https://www.developer.amazon.com/docs/apps-and-games/documentation.html\n    baseURL: https://developer.amazon.com/api/appstore\n    properties:\n      - type: Documentation\n        url: https://www.developer.amazon.com/docs/apps-and-games/documentation.html\n    description: >-\n      The Amazon Appstore Developer APIs provide tools for managing app\n      submissions, testing, and monetization through in-app purchases on the\n      Amazon Appstore for Android and Fire OS applications.\n\ncommon:\n  - type: Portal\n    url: https://developer.amazon.com/\n  - type: Website\n    url: https://www.amazon.com/\n  - type: Documentation\n    url: https://developer.amazon.com/docs/\n  - type: TermsOfService\n    url: https://developer.amazon.com/support/legal/da\n  - type: PrivacyPolicy\n\
  \    url: https://www.amazon.com/gp/help/customer/display.html?nodeId=468496\n  - type: Support\n    url: https://developer.amazon.com/support\n  - type: GitHubOrganization\n    url: https://github.com/amzn\n  - type: Console\n    url: https://developer.amazon.com/dashboard\n  - type: SignUp\n    url: https://www.amazon.com/ap/register?openid.assoc_handle=aws\n  - type: Login\n    url: https://developer.amazon.com/login\n  - type: Blog\n    url: https://developer.amazon.com/blogs/\n  - type: YouTube\n    url: https://www.youtube.com/c/AmazonDeveloper\n  - type: Contact\n    url: https://www.amazon.com/gp/help/customer/contact-us\n  - type: JSONLD\n    url: json-ld/amazon-context.jsonld\n  - type: SpectralRules\n    url: rules/amazon-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-seller-and-commerce.yaml\n  - type: Features\n    data:\n      - name: Marketplace Seller Operations\n        description:\
  \ >-\n          Full lifecycle management of Amazon marketplace seller operations\n          including catalog, inventory, orders, shipping, and financial reporting.\n      - name: Programmatic Advertising\n        description: >-\n          Create and optimize Sponsored Products, Sponsored Brands, and Sponsored\n          Display advertising campaigns with granular targeting and reporting.\n      - name: Amazon Pay Integration\n        description: >-\n          Enable Amazon Pay on external websites and mobile apps with checkout\n          session management, one-time charges, subscriptions, and refunds.\n      - name: Voice Experience Development\n        description: >-\n          Build Alexa voice skills for Echo devices, Fire TV, and third-party\n          Alexa-enabled hardware with the Alexa Skills Kit.\n      - name: Affiliate and Creator Commerce\n        description: >-\n          Access Amazon product data for affiliate marketing and content creation\n          through the\
  \ Creators API with product search and deep linking.\n      - name: Mobile App Monetization\n        description: >-\n          Publish and monetize apps on the Amazon Appstore with in-app purchasing\n          for digital goods, subscriptions, and consumables.\n      - name: Multi-Region Marketplace Support\n        description: >-\n          Access North America, Europe, and Far East marketplaces through\n          region-specific SP-API endpoints.\n      - name: Developer Console and Testing Tools\n        description: >-\n          Sandbox environments, developer consoles, and testing tools for\n          building and validating Amazon integrations before going live.\n  - type: UseCases\n    data:\n      - name: Marketplace Seller Automation\n        description: >-\n          Automate product listing creation, price updates, inventory management,\n          and order fulfillment for Amazon marketplace sellers.\n      - name: Advertising Campaign Optimization\n        description:\
  \ >-\n          Build automated bid management and campaign optimization tools using\n          the Amazon Advertising API and performance reporting.\n      - name: E-Commerce Payment Integration\n        description: >-\n          Add Amazon Pay as a payment option for external e-commerce sites to\n          reduce checkout friction and increase conversion rates.\n      - name: Voice Commerce and Smart Home\n        description: >-\n          Create Alexa skills for voice-driven shopping, home automation, and\n          customer service interactions.\n      - name: Affiliate Content Monetization\n        description: >-\n          Build product recommendation engines and affiliate content sites using\n          the Creators API for real-time Amazon product data.\n  - type: Integrations\n    data:\n      - name: Amazon MWS Legacy Migration\n        description: >-\n          SP-API is the modern replacement for the deprecated Amazon Marketplace\n          Web Service (MWS) for all seller\
  \ operations.\n      - name: Alexa Smart Home\n        description: >-\n          Integrate smart home devices and services with Alexa voice control\n          using the Smart Home Skill API.\n      - name: Login with Amazon\n        description: >-\n          OAuth 2.0 authentication for all Amazon developer APIs including\n          SP-API, Advertising API, and ASK via Login with Amazon (LWA).\n      - name: Amazon Associates Program\n        description: >-\n          Affiliate program integration for the Creators API and Product\n          Advertising API for commission-based product promotion.\n      - name: Fire OS and Android\n        description: >-\n          Amazon Appstore SDK for Fire OS and Android apps with in-app\n          purchasing and device targeting capabilities.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/apis.yml
tags:
- Amazon
- Advertising
- Alexa
- E-Commerce
- Marketplace
- Payments
- Voice
url: https://raw.githubusercontent.com/api-evangelist/amazon/refs/heads/main/apis.yml
use_cases:
- description: Automate product listing creation, price updates, inventory management, and order fulfillment for Amazon marketplace sellers.
  name: Marketplace Seller Automation
- description: Build automated bid management and campaign optimization tools using the Amazon Advertising API and performance reporting.
  name: Advertising Campaign Optimization
- description: Add Amazon Pay as a payment option for external e-commerce sites to reduce checkout friction and increase conversion rates.
  name: E-Commerce Payment Integration
- description: Create Alexa skills for voice-driven shopping, home automation, and customer service interactions.
  name: Voice Commerce and Smart Home
- description: Build product recommendation engines and affiliate content sites using the Creators API for real-time Amazon product data.
  name: Affiliate Content Monetization
---
