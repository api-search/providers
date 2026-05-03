---
api_count: 7
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
apis:
- description: 'The Toast Orders API enables retrieval of restaurant orders, checks, and payment information. Supports bulk order queries by date range and individual order retrieval by GUID. Used for building order '
  name: Toast Orders API
  slug: toast-orders
- description: The Toast Menus API provides complete menu data retrieval including items, modifiers, prices, and availability. Enables POS-synchronized menu display for online ordering and third-party menu managemen
  name: Toast Menus API
  slug: toast-menus
- description: The Toast Labor API manages employee records, schedules, and shift data for restaurant locations. Supports employee CRUD operations, time entry management, and payroll integration workflows.
  name: Toast Labor API
  slug: toast-labor
- description: The Toast Restaurants API provides location configuration data including restaurant settings, hours, payment options, and management group restaurant discovery for multi-location operations.
  name: Toast Restaurants API
  slug: toast-restaurants
- description: The Toast Stock API manages inventory for menu items and modifiers, allowing integration with inventory management systems to track stock levels and trigger restocking alerts for restaurant operations
  name: Toast Stock API
  slug: toast-stock
- description: The Toast Partners API provides partner accounts with access to list connected restaurants, enabling multi-restaurant management and partner-level operations across restaurant locations.
  name: Toast Partners API
  slug: toast-partners
- description: The Toast Authentication API implements OAuth 2.0 client credentials flow for obtaining access tokens used across all Toast platform APIs. Tokens are scoped to restaurant GUIDs and expire after a conf
  name: Toast Authentication API
  slug: toast-authentication
capabilities:
- description: Unified workflow capability combining Toast Orders and Labor APIs for day-to-day restaurant operations management. Enables operators to monitor orders, manage payments, and oversee staff from a single
  name: Toast Restaurant Operations
  slug: restaurant-operations
common:
- title: ''
  type: Website
  url: https://pos.toasttab.com/
- title: ''
  type: Documentation
  url: https://doc.toasttab.com/doc/devguide/index.html
- title: ''
  type: Portal
  url: https://doc.toasttab.com/openapi/
- title: ''
  type: SignUp
  url: https://developers.toasttab.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/toasttab
- title: ''
  type: SpectralRules
  url: rules/toast-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/toast-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/restaurant-operations.yaml
created: '2025-02-08'
description: Toast is a restaurant technology platform providing cloud-based point-of-sale, payment processing, and business management tools for the restaurant industry. The Toast platform exposes REST APIs enabling technology partners to build integrations for orders, menus, labor management, restaurant configuration, inventory/stock management, authentication, and partner ecosystem access. APIs use OAuth 2.0 client credentials authentication with GUIDs for resource identification. Toast serves 120,000+ restaurant locations and offers both partner integrations (requiring formal partnership) and custom integrations via the developer portal.
features:
- description: Retrieve restaurant orders, checks, and payment data by GUID or bulk date queries.
  name: Orders API
- description: Full menu data retrieval including items, modifiers, prices, and availability.
  name: Menus API
- description: Employee CRUD operations, shift management, and payroll integration support.
  name: Labor Management API
- description: Location settings, payment options, and management group restaurant discovery.
  name: Restaurant Configuration API
- description: Inventory management for menu items and modifiers with stock level tracking.
  name: Stock and Inventory API
- description: Client credentials OAuth flow with GUID-scoped tokens for secure API access.
  name: OAuth 2.0 Authentication
- description: Formal partner program enabling multi-restaurant access and ecosystem integrations.
  name: Partner Integration Program
- description: Outbound integration webhooks for real-time event delivery (gift cards, loyalty, tender).
  name: Webhook Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Third-party delivery platform integrated with Toast for order injection.
  name: DoorDash
- description: Delivery platform integration for menu sync and order management.
  name: UberEats
- description: Accounting integration for restaurant financial data via Toast reporting APIs.
  name: QuickBooks
- description: Payroll platform integration using Toast Labor API data.
  name: ADP
- description: Reservation system integration with Toast for guest management.
  name: OpenTable
jsonld:
- class_count: 3
  name: Toast Authentication Context
  property_count: 11
  slug: toast-authentication-context
- class_count: 9
  name: Toast Labor Context
  property_count: 15
  slug: toast-labor-context
- class_count: 29
  name: Toast Menus Context
  property_count: 100
  slug: toast-menus-context
- class_count: 31
  name: Toast Orders Context
  property_count: 46
  slug: toast-orders-context
- class_count: 2
  name: Toast Partners Context
  property_count: 22
  slug: toast-partners-context
- class_count: 17
  name: Toast Restaurants Context
  property_count: 77
  slug: toast-restaurants-context
- class_count: 2
  name: Toast Stock Context
  property_count: 9
  slug: toast-stock-context
layout: provider
modified: '2026-05-03'
name: Toast
rules:
- name: Toast API Rules
  rule_count: 29
  severity_counts:
    error: 10
    hint: 0
    info: 13
    warn: 6
  slug: toast-spectral-rules
skills: []
slug: toast
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toast\nname: Toast\ndescription: >-\n  Toast is a restaurant technology platform providing cloud-based point-of-sale,\n  payment processing, and business management tools for the restaurant industry.\n  The Toast platform exposes REST APIs enabling technology partners to build\n  integrations for orders, menus, labor management, restaurant configuration,\n  inventory/stock management, authentication, and partner ecosystem access.\n  APIs use OAuth 2.0 client credentials authentication with GUIDs for resource\n  identification. Toast serves 120,000+ restaurant locations and offers both\n  partner integrations (requiring formal partnership) and custom integrations\n  via the developer portal.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Food Service\n  - Point of Sale\n  - Restaurants\n  - Hospitality\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: toast:toast-orders\n    name: Toast Orders API\n    description: >-\n      The Toast Orders API enables retrieval of restaurant orders, checks, and\n      payment information. Supports bulk order queries by date range and\n      individual order retrieval by GUID. Used for building order management,\n      reporting, and delivery integrations.\n    humanURL: https://doc.toasttab.com/openapi/orders/overview/\n    tags:\n      - Orders\n      - Payments\n      - Point of Sale\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/orders/overview/\n      - type: OpenAPI\n        url: openapi/toast-orders-openapi.yaml\n\n  - aid: toast:toast-menus\n    name: Toast Menus API\n    description: >-\n      The Toast Menus API provides complete menu data retrieval including items,\n      modifiers, prices, and availability. Enables POS-synchronized menu display\n      for online ordering and third-party menu management\
  \ integrations.\n    humanURL: https://doc.toasttab.com/openapi/menus/overview/\n    tags:\n      - Menus\n      - Food Service\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/menus/overview/\n      - type: OpenAPI\n        url: openapi/toast-menus-openapi.yaml\n\n  - aid: toast:toast-labor\n    name: Toast Labor API\n    description: >-\n      The Toast Labor API manages employee records, schedules, and shift data\n      for restaurant locations. Supports employee CRUD operations, time entry\n      management, and payroll integration workflows.\n    humanURL: https://doc.toasttab.com/openapi/labor/overview/\n    tags:\n      - Labor\n      - Employees\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/labor/overview/\n      - type: OpenAPI\n        url: openapi/toast-labor-openapi.yaml\n\n  - aid: toast:toast-restaurants\n    name: Toast Restaurants API\n    description: >-\n   \
  \   The Toast Restaurants API provides location configuration data including\n      restaurant settings, hours, payment options, and management group\n      restaurant discovery for multi-location operations.\n    humanURL: https://doc.toasttab.com/openapi/restaurants/overview/\n    tags:\n      - Restaurants\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/restaurants/overview/\n      - type: OpenAPI\n        url: openapi/toast-restaurants-openapi.yaml\n\n  - aid: toast:toast-stock\n    name: Toast Stock API\n    description: >-\n      The Toast Stock API manages inventory for menu items and modifiers,\n      allowing integration with inventory management systems to track stock\n      levels and trigger restocking alerts for restaurant operations.\n    humanURL: https://doc.toasttab.com/openapi/stock/overview/\n    tags:\n      - Stock\n      - Inventory\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/stock/overview/\n\
  \      - type: OpenAPI\n        url: openapi/toast-stock-openapi.yaml\n\n  - aid: toast:toast-partners\n    name: Toast Partners API\n    description: >-\n      The Toast Partners API provides partner accounts with access to list\n      connected restaurants, enabling multi-restaurant management and\n      partner-level operations across restaurant locations.\n    humanURL: https://doc.toasttab.com/openapi/partners/overview/\n    tags:\n      - Partners\n      - Multi-Location\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/partners/overview/\n      - type: OpenAPI\n        url: openapi/toast-partners-openapi.yaml\n\n  - aid: toast:toast-authentication\n    name: Toast Authentication API\n    description: >-\n      The Toast Authentication API implements OAuth 2.0 client credentials\n      flow for obtaining access tokens used across all Toast platform APIs.\n      Tokens are scoped to restaurant GUIDs and expire after a configurable\n     \
  \ period.\n    humanURL: https://doc.toasttab.com/openapi/authentication/overview/\n    tags:\n      - Authentication\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://doc.toasttab.com/openapi/authentication/overview/\n      - type: OpenAPI\n        url: openapi/toast-authentication-openapi.yaml\n\ncommon:\n  - type: Website\n    url: https://pos.toasttab.com/\n  - type: Documentation\n    url: https://doc.toasttab.com/doc/devguide/index.html\n  - type: Portal\n    url: https://doc.toasttab.com/openapi/\n  - type: SignUp\n    url: https://developers.toasttab.com/\n  - type: GitHubOrganization\n    url: https://github.com/toasttab\n  - type: SpectralRules\n    url: rules/toast-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/toast-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/restaurant-operations.yaml\n    name: Restaurant Operations\n  - type: Features\n    data:\n      - name: Orders API\n        description: Retrieve\
  \ restaurant orders, checks, and payment data by GUID or bulk date queries.\n      - name: Menus API\n        description: Full menu data retrieval including items, modifiers, prices, and availability.\n      - name: Labor Management API\n        description: Employee CRUD operations, shift management, and payroll integration support.\n      - name: Restaurant Configuration API\n        description: Location settings, payment options, and management group restaurant discovery.\n      - name: Stock and Inventory API\n        description: Inventory management for menu items and modifiers with stock level tracking.\n      - name: OAuth 2.0 Authentication\n        description: Client credentials OAuth flow with GUID-scoped tokens for secure API access.\n      - name: Partner Integration Program\n        description: Formal partner program enabling multi-restaurant access and ecosystem integrations.\n      - name: Webhook Support\n        description: Outbound integration webhooks for real-time\
  \ event delivery (gift cards, loyalty, tender).\n  - type: UseCases\n    data:\n      - name: Online Ordering Integration\n        description: Connect third-party online ordering platforms to Toast POS for order injection and menu sync.\n      - name: Payroll and Labor Integration\n        description: Sync Toast employee and shift data with payroll systems using the Labor API.\n      - name: Reporting and Analytics\n        description: Pull order and payment data via bulk orders API for custom reporting and business intelligence.\n      - name: Inventory Management\n        description: Integrate restaurant inventory systems with Toast Stock API for real-time stock tracking.\n      - name: Loyalty and Gift Cards\n        description: Build loyalty program and gift card integrations using Toast outbound webhook APIs.\n      - name: Multi-Location Management\n        description: Partner integrations managing hundreds of restaurant locations via Partners API.\n  - type: Integrations\n\
  \    data:\n      - name: DoorDash\n        description: Third-party delivery platform integrated with Toast for order injection.\n      - name: UberEats\n        description: Delivery platform integration for menu sync and order management.\n      - name: QuickBooks\n        description: Accounting integration for restaurant financial data via Toast reporting APIs.\n      - name: ADP\n        description: Payroll platform integration using Toast Labor API data.\n      - name: OpenTable\n        description: Reservation system integration with Toast for guest management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/apis.yml
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/apis.yml
use_cases:
- description: Connect third-party online ordering platforms to Toast POS for order injection and menu sync.
  name: Online Ordering Integration
- description: Sync Toast employee and shift data with payroll systems using the Labor API.
  name: Payroll and Labor Integration
- description: Pull order and payment data via bulk orders API for custom reporting and business intelligence.
  name: Reporting and Analytics
- description: Integrate restaurant inventory systems with Toast Stock API for real-time stock tracking.
  name: Inventory Management
- description: Build loyalty program and gift card integrations using Toast outbound webhook APIs.
  name: Loyalty and Gift Cards
- description: Partner integrations managing hundreds of restaurant locations via Partners API.
  name: Multi-Location Management
---
