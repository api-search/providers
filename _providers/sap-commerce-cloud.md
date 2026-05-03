---
api_count: 5
api_specs:
- filename: overview
  format: yaml
  label: Commerce Web Services API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/commerce_web_services/overview
- filename: sap-commerce-cloud-assisted-service-openapi.yml
  format: yaml
  label: Assisted Service Module API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-assisted-service-openapi.yml
- filename: sap-commerce-cloud-integration-openapi.yml
  format: yaml
  label: Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-integration-openapi.yml
- filename: sap-commerce-cloud-admin-openapi.yml
  format: yaml
  label: Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-admin-openapi.yml
- filename: sap-commerce-cloud-product-content-management-openapi.yml
  format: yaml
  label: Product Content Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/openapi/sap-commerce-cloud-product-content-management-openapi.yml
apis:
- description: RESTful API for commerce operations including product catalog, cart, checkout, and order management.
  name: Commerce Web Services API
  slug: ''
- description: API for assisted service capabilities enabling customer service representatives to help customers with their shopping experience.
  name: Assisted Service Module API
  slug: ''
- description: OData-based integration API for data integration and synchronization with external systems.
  name: Integration API
  slug: ''
- description: Administrative API for system configuration, maintenance, and monitoring.
  name: Admin API
  slug: ''
- description: API for managing product content including images, descriptions, and attributes.
  name: Product Content Management API
  slug: ''
capabilities:
- description: Workflow capability for managing product catalogs, categories, and content in SAP Commerce Cloud. Combines catalog browsing, product content management, and customer service workflows. Used by catalog
  name: SAP Commerce Cloud Catalog and Content Management
  slug: catalog-and-content-management
- description: 'Workflow capability for the customer shopping journey in SAP Commerce Cloud. Covers product discovery, cart management, checkout, and order tracking for both B2B and B2C scenarios. Used by storefront '
  name: SAP Commerce Cloud Shopping and Checkout
  slug: shopping-and-checkout
common:
- title: ''
  type: Portal
  url: https://api.sap.com/
- title: ''
  type: Getting Started
  url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/0996ba68e5794b8ab51db8d25d4c9f8c/
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html
- title: ''
  type: Support
  url: https://support.sap.com/
- title: ''
  type: Community
  url: https://community.sap.com/topics/commerce-cloud
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Status
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: OpenAPI
  url: openapi/sap-commerce-cloud-commerce-web-services-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-commerce-cloud-assisted-service-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-commerce-cloud-integration-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-commerce-cloud-admin-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-commerce-cloud-product-content-management-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/sap-commerce-cloud-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sap-commerce-cloud-product-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-commerce-cloud-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-commerce-cloud-cart-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sap-commerce-cloud-customer-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-commerce-cloud-product-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-commerce-cloud-order-structure.json
- title: ''
  type: SpectralRules
  url: rules/sap-commerce-cloud-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shopping-and-checkout.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/catalog-and-content-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/sap-commerce-cloud-vocabulary.yml
created: '2024-01-01'
description: SAP Commerce Cloud (formerly Hybris) provides enterprise e-commerce and omnichannel customer experience management capabilities including product content management, order management, personalization, and assisted service for B2B and B2C commerce scenarios.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Sap Commerce Cloud Context
  property_count: 14
  slug: sap-commerce-cloud-context
layout: provider
modified: '2026-05-02'
name: SAP Commerce Cloud
rules:
- name: SAP Commerce Cloud API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 0
    info: 4
    warn: 6
  slug: sap-commerce-cloud-rules
skills: []
slug: sap-commerce-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP Commerce Cloud\ndescription: >-\n  SAP Commerce Cloud (formerly Hybris) provides enterprise e-commerce and\n  omnichannel customer experience management capabilities including product\n  content management, order management, personalization, and assisted service\n  for B2B and B2C commerce scenarios.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\nurl: https://www.sap.com/products/crm/commerce-cloud.html\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - B2B\n  - B2C\n  - Commerce\n  - Customer Experience\n  - Ecommerce\n  - Omnichannel\n  - Retail\napis:\n  - name: Commerce Web Services API\n    description: >-\n      RESTful API for commerce operations including product catalog, cart, checkout,\n      and order management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/9d346683b0084da2938be8a285c0c27a/\n\
  \    baseURL: https://{tenant}.{region}.commercecloud.sap/occ/v2\n    tags:\n      - Cart\n      - Checkout\n      - Orders\n      - Products\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/8c19398686691014a8c0fd6c3e5d44a0.html\n      - type: OpenAPI\n        url: https://api.sap.com/api/commerce_web_services/overview\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html\n      - type: OpenAPI\n        url: openapi/sap-commerce-cloud-commerce-web-services-openapi.yml\n  - name: Assisted Service Module API\n    description: >-\n      API for assisted service capabilities enabling customer service representatives\n      to help customers with their shopping experience.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html\n\
  \    baseURL: https://{tenant}.{region}.commercecloud.sap/assistedservicewebservices\n    tags:\n      - Assisted Service\n      - Customer Service\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE/9d346683b0084da2938be8a285c0c27a/8b571515866910148fc18b9e59d3e084.html\n      - type: OpenAPI\n        url: openapi/sap-commerce-cloud-assisted-service-openapi.yml\n  - name: Integration API\n    description: >-\n      OData-based integration API for data integration and synchronization with external\n      systems.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/50c996852b32456c96d3161a95544cdb/\n    baseURL: https://{tenant}.{region}.commercecloud.sap/odata2webservices\n    tags:\n      - Data Sync\n      - Integration\n      - OData\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/50c996852b32456c96d3161a95544cdb/8696c1e06fce461a862d7f0eb60cca7b.html\n\
  \      - type: API Reference\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/b490bb4e85bc42a7aa09d513d0bcb18e/\n      - type: OpenAPI\n        url: openapi/sap-commerce-cloud-integration-openapi.yml\n  - name: Admin API\n    description: >-\n      Administrative API for system configuration, maintenance, and monitoring.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/\n    baseURL: https://{tenant}.{region}.commercecloud.sap/\n    tags:\n      - Admin\n      - Configuration\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/\n      - type: OpenAPI\n        url: openapi/sap-commerce-cloud-admin-openapi.yml\n  - name: Product Content Management API\n    description: >-\n      API for managing product content including images, descriptions, and attributes.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/\n    baseURL: https://{tenant}.{region}.commercecloud.sap/occ/v2\n    tags:\n      - Catalog\n      - Content\n      - Products\n      - REST\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/\n      - type: OpenAPI\n        url: openapi/sap-commerce-cloud-product-content-management-openapi.yml\ncommon:\n  - type: Portal\n    url: https://api.sap.com/\n  - type: Getting Started\n    url: https://help.sap.com/docs/SAP_COMMERCE_CLOUD_PUBLIC_CLOUD/0996ba68e5794b8ab51db8d25d4c9f8c/\n  - type: Authentication\n    url: https://help.sap.com/docs/SAP_COMMERCE/d0224eca81e249cb821f2cdf45a82ace/627c92dbdb7648449c840c07dd9cac7b.html\n  - type: Support\n    url: https://support.sap.com/\n  - type: Community\n    url: https://community.sap.com/topics/commerce-cloud\n  - type: Terms of Service\n    url: https://www.sap.com/about/legal/terms-of-use.html\n\
  \  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: OpenAPI\n    url: openapi/sap-commerce-cloud-commerce-web-services-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-commerce-cloud-assisted-service-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-commerce-cloud-integration-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-commerce-cloud-admin-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-commerce-cloud-product-content-management-openapi.yml\n  - type: JSON-LD\n    url: json-ld/sap-commerce-cloud-context.jsonld\n  - type: JSONSchema\n    url: json-schema/sap-commerce-cloud-product-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-commerce-cloud-order-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-commerce-cloud-cart-schema.json\n  - type: JSONSchema\n    url: json-schema/sap-commerce-cloud-customer-schema.json\n \
  \ - type: JSONStructure\n    url: json-structure/sap-commerce-cloud-product-structure.json\n  - type: JSONStructure\n    url: json-structure/sap-commerce-cloud-order-structure.json\n  - type: SpectralRules\n    url: rules/sap-commerce-cloud-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shopping-and-checkout.yaml\n  - type: NaftikoCapability\n    url: capabilities/catalog-and-content-management.yaml\n  - type: Vocabulary\n    url: vocabulary/sap-commerce-cloud-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-commerce-cloud/refs/heads/main/apis.yml
tags:
- B2B
- B2C
- Commerce
- Customer Experience
- Ecommerce
- Omnichannel
- Retail
url: https://www.sap.com/products/crm/commerce-cloud.html
use_cases: []
---
