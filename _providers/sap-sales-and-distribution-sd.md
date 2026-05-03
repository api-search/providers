---
api_count: 17
api_specs:
- filename: sap-sd-sales-order-openapi.yml
  format: yaml
  label: Sales Order API
  slug: sales-order
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-order-openapi.yml
- filename: sap-sd-customer-master-data-openapi.yml
  format: yaml
  label: Customer Master Data API
  slug: customer-master-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-master-data-openapi.yml
- filename: sap-sd-outbound-delivery-openapi.yml
  format: yaml
  label: Outbound Delivery API
  slug: outbound-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-outbound-delivery-openapi.yml
- filename: sap-sd-billing-document-openapi.yml
  format: yaml
  label: Billing Document API
  slug: billing-document
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-billing-document-openapi.yml
- filename: sap-sd-pricing-openapi.yml
  format: yaml
  label: Pricing API
  slug: pricing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-pricing-openapi.yml
- filename: sap-sd-sales-quotation-openapi.yml
  format: yaml
  label: Sales Quotation API
  slug: sales-quotation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-quotation-openapi.yml
- filename: sap-sd-credit-management-openapi.yml
  format: yaml
  label: Credit Management API
  slug: credit-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-credit-management-openapi.yml
- filename: sap-sd-material-master-openapi.yml
  format: yaml
  label: Material Master API
  slug: material-master
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-material-master-openapi.yml
- filename: sap-sd-credit-memo-request-openapi.yml
  format: yaml
  label: Credit Memo Request API
  slug: credit-memo-request
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-credit-memo-request-openapi.yml
- filename: sap-sd-debit-memo-request-openapi.yml
  format: yaml
  label: Debit Memo Request API
  slug: debit-memo-request
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-debit-memo-request-openapi.yml
- filename: sap-sd-sales-contract-openapi.yml
  format: yaml
  label: Sales Contract API
  slug: sales-contract
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-contract-openapi.yml
- filename: sap-sd-sales-inquiry-openapi.yml
  format: yaml
  label: Sales Inquiry API
  slug: sales-inquiry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-inquiry-openapi.yml
- filename: sap-sd-sales-scheduling-agreement-openapi.yml
  format: yaml
  label: Sales Scheduling Agreement API
  slug: sales-scheduling-agreement
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-scheduling-agreement-openapi.yml
- filename: sap-sd-customer-return-openapi.yml
  format: yaml
  label: Customer Return API
  slug: customer-return
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-return-openapi.yml
- filename: sap-sd-customer-returns-delivery-openapi.yml
  format: yaml
  label: Customer Returns Delivery API
  slug: customer-returns-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-returns-delivery-openapi.yml
- filename: sap-sd-customer-material-openapi.yml
  format: yaml
  label: Customer Material API
  slug: customer-material
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-material-openapi.yml
- filename: sap-sd-inbound-delivery-openapi.yml
  format: yaml
  label: Inbound Delivery API
  slug: inbound-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-inbound-delivery-openapi.yml
apis:
- description: Create, read, update, and delete sales orders in SAP S/4HANA. This OData service (API_SALES_ORDER_SRV) supports full CRUD operations on sales order headers, items, partners, pricing elements, and sche
  name: Sales Order API
  slug: sales-order
- description: Manage customer master data including addresses, contact information, and business partner details in SAP S/4HANA. Provides access to business partner records used across SAP S/4HANA modules.
  name: Customer Master Data API
  slug: customer-master-data
- description: Create and manage outbound deliveries, goods issue, and shipping documents. Supports delivery creation with reference to sales orders and subsequent logistics processing including goods issue posting.
  name: Outbound Delivery API
  slug: outbound-delivery
- description: Create and manage billing documents, invoices, credit memos, and debit memos. Enables billing document processing as part of the order-to-cash cycle in SAP S/4HANA including cancellation.
  name: Billing Document API
  slug: billing-document
- description: Calculate prices, discounts, and surcharges based on pricing conditions. Manages sales pricing condition records used to determine prices in sales documents within SAP S/4HANA.
  name: Pricing API
  slug: pricing
- description: Create and manage sales quotations and customer inquiries. Supports the complete quotation lifecycle from creation through approval and conversion to sales orders.
  name: Sales Quotation API
  slug: sales-quotation
- description: Manage customer credit limits, credit exposure, and credit checks in SAP S/4HANA. Enables automated credit risk assessment during sales order processing.
  name: Credit Management API
  slug: credit-management
- description: Access material master data including product information, availability, and pricing. Provides read and write access to product records used across procurement, manufacturing, and sales processes.
  name: Material Master API
  slug: material-master
- description: Create, read, update, and delete credit memo requests. Enables approval or denial of credit memo requests that require authorization before processing.
  name: Credit Memo Request API
  slug: credit-memo-request
- description: Create, read, update, and delete debit memo requests. Supports the full lifecycle of debit memo requests used to charge customers for additional amounts.
  name: Debit Memo Request API
  slug: debit-memo-request
- description: Create and manage sales contracts including quantity contracts and value contracts. Supports contract lifecycle management from creation through fulfillment tracking.
  name: Sales Contract API
  slug: sales-contract
- description: Read sales inquiries from SAP S/4HANA. Provides access to sales inquiry documents used in the pre-sales process to capture customer interest in products or services.
  name: Sales Inquiry API
  slug: sales-inquiry
- description: Manage sales scheduling agreements in SAP S/4HANA. Scheduling agreements define delivery schedules for recurring deliveries of materials to customers over a specified period.
  name: Sales Scheduling Agreement API
  slug: sales-scheduling-agreement
- description: Create, read, update, and delete customer returns in SAP S/4HANA. Supports integration with customer return processing including SAP Advanced Returns Management using deep insert requests.
  name: Customer Return API
  slug: customer-return
- description: Manage customer returns deliveries in SAP S/4HANA. Enables processing of inbound deliveries related to customer returns, including goods receipt and inspection.
  name: Customer Returns Delivery API
  slug: customer-returns-delivery
- description: Manage customer-material information records that link customer-specific material numbers to internal material numbers. Supports the sales process by mapping customer part numbers to SAP materials.
  name: Customer Material API
  slug: customer-material
- description: Create and manage inbound deliveries in SAP S/4HANA. Supports creation of inbound deliveries with reference to sales documents and manages batch-split items for existing deliveries.
  name: Inbound Delivery API
  slug: inbound-delivery
capabilities:
- description: Unified capability for customer and credit management operations in SAP S/4HANA Sales and Distribution. Combines Customer Master Data, Credit Management, and Customer Material APIs for sales administr
  name: SAP SD Customer Management
  slug: customer-management
- description: Unified capability for end-to-end order-to-cash operations in SAP S/4HANA Sales and Distribution. Combines Sales Order, Outbound Delivery, Billing Document, and Pricing APIs into a single workflow for
  name: SAP SD Order-to-Cash
  slug: order-to-cash
common:
- title: ''
  type: Portal
  url: https://api.sap.com
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/SAP_S4HANA_CLOUD
- title: ''
  type: Website
  url: https://www.sap.com
- title: ''
  type: Getting Started
  url: https://developers.sap.com/tutorials.html
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/
- title: ''
  type: Blog
  url: https://community.sap.com/t5/c-khhcw49343/SD+%28Sales+and+Distribution%29/pd-p/209057551571413566377230676804921
- title: ''
  type: Status
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: Support
  url: https://support.sap.com
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/agreements/product-use-and-support-terms.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: GitHub Organization
  url: https://github.com/SAP
- title: ''
  type: Community
  url: https://community.sap.com
- title: ''
  type: Login
  url: https://accounts.sap.com
- title: ''
  type: Sign Up
  url: https://developers.sap.com
- title: ''
  type: SDK
  url: https://sap.github.io/cloud-sdk/
- title: ''
  type: SDK
  url: https://github.com/SAP/cloud-sdk-js
- title: ''
  type: SpectralRules
  url: rules/sap-sd-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/order-to-cash.yaml
- title: ''
  type: Capabilities
  url: capabilities/customer-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/sap-sd-vocabulary.yml
created: '2024-01-01'
description: APIs for SAP Sales and Distribution module covering sales orders, pricing, delivery, billing, and customer management processes within SAP S/4HANA. These OData-based APIs enable integration with external applications for end-to-end order-to-cash operations including sales document management, logistics execution, billing, and credit management.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Sap Sd Context
  property_count: 65
  slug: sap-sd-context
layout: provider
modified: '2026-05-02'
name: SAP Sales and Distribution (SD)
rules:
- name: SAP Sales and Distribution (SD) API Rules
  rule_count: 17
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 9
  slug: sap-sd-rules
skills: []
slug: sap-sales-and-distribution-sd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sap-sales-and-distribution-sd\nname: SAP Sales and Distribution (SD)\ndescription: >-\n  APIs for SAP Sales and Distribution module covering sales orders, pricing,\n  delivery, billing, and customer management processes within SAP S/4HANA.\n  These OData-based APIs enable integration with external applications for\n  end-to-end order-to-cash operations including sales document management,\n  logistics execution, billing, and credit management.\ntype: Index\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Distribution\n  - ERP\n  - OData\n  - S/4HANA\n  - Sales\n  - SAP\napis:\n  - aid: sap-sales-and-distribution-sd:sales-order\n    name: Sales Order API\n    description: >-\n      Create, read, update, and delete sales orders in SAP S/4HANA. This\
  \ OData\n      service (API_SALES_ORDER_SRV) supports full CRUD operations on sales order\n      headers, items, partners, pricing elements, and schedule lines. Sales\n      orders are created using deep insert requests.\n    humanURL: https://api.sap.com/api/API_SALES_ORDER_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_ORDER_SRV\n    tags:\n      - OData\n      - Order Management\n      - S/4HANA\n      - Sales Orders\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SALES_ORDER_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-sales-order-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-sales-order-schema.json\n      - type: JSONSchema\n        url: json-schema/sap-sd-sales-order-item-schema.json\n      - type: JSONStructure\n        url: json-structure/sap-sd-sales-order-structure.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n      - type:\
  \ Examples\n        url: examples/sap-sd-list-sales-orders-example.json\n      - type: Examples\n        url: examples/sap-sd-create-sales-order-example.json\n\n  - aid: sap-sales-and-distribution-sd:customer-master-data\n    name: Customer Master Data API\n    description: >-\n      Manage customer master data including addresses, contact information, and\n      business partner details in SAP S/4HANA. Provides access to business\n      partner records used across SAP S/4HANA modules.\n    humanURL: https://api.sap.com/api/API_BUSINESS_PARTNER/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BUSINESS_PARTNER\n    tags:\n      - Business Partner\n      - Customer Data\n      - Master Data\n      - OData\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-customer-master-data-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-business-partner-schema.json\n\
  \      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:outbound-delivery\n    name: Outbound Delivery API\n    description: >-\n      Create and manage outbound deliveries, goods issue, and shipping documents.\n      Supports delivery creation with reference to sales orders and subsequent\n      logistics processing including goods issue posting.\n    humanURL: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_OUTBOUND_DELIVERY_SRV\n    tags:\n      - Delivery\n      - Logistics\n      - OData\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-outbound-delivery-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-outbound-delivery-schema.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\
  \n  - aid: sap-sales-and-distribution-sd:billing-document\n    name: Billing Document API\n    description: >-\n      Create and manage billing documents, invoices, credit memos, and debit\n      memos. Enables billing document processing as part of the order-to-cash\n      cycle in SAP S/4HANA including cancellation.\n    humanURL: https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BILLING_DOCUMENT_SRV\n    tags:\n      - Billing\n      - Credit Memo\n      - Invoice\n      - OData\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-billing-document-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-billing-document-schema.json\n      - type: JSONStructure\n        url: json-structure/sap-sd-billing-document-structure.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\
  \n  - aid: sap-sales-and-distribution-sd:pricing\n    name: Pricing API\n    description: >-\n      Calculate prices, discounts, and surcharges based on pricing conditions.\n      Manages sales pricing condition records used to determine prices in\n      sales documents within SAP S/4HANA.\n    humanURL: https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SLSPRCGCONDITIONRECORD_SRV\n    tags:\n      - Conditions\n      - Discount\n      - OData\n      - Pricing\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-pricing-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-pricing-condition-schema.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:sales-quotation\n    name: Sales Quotation API\n    description:\
  \ >-\n      Create and manage sales quotations and customer inquiries. Supports the\n      complete quotation lifecycle from creation through approval and conversion\n      to sales orders.\n    humanURL: https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_QUOTATION_SRV\n    tags:\n      - OData\n      - Pre-Sales\n      - Quotation\n      - Sales Document\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-sales-quotation-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:credit-management\n    name: Credit Management API\n    description: >-\n      Manage customer credit limits, credit exposure, and credit checks in\n      SAP S/4HANA. Enables automated credit risk assessment during sales\n      order processing.\n\
  \    humanURL: https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CREDIT_MANAGEMENT\n    tags:\n      - Credit\n      - Finance\n      - OData\n      - Risk Management\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-credit-management-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:material-master\n    name: Material Master API\n    description: >-\n      Access material master data including product information, availability,\n      and pricing. Provides read and write access to product records used across\n      procurement, manufacturing, and sales processes.\n    humanURL: https://api.sap.com/api/API_PRODUCT_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PRODUCT_SRV\n    tags:\n\
  \      - Master Data\n      - Material\n      - OData\n      - Product\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_PRODUCT_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-material-master-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-product-schema.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:credit-memo-request\n    name: Credit Memo Request API\n    description: >-\n      Create, read, update, and delete credit memo requests. Enables approval\n      or denial of credit memo requests that require authorization before\n      processing.\n    humanURL: https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CREDIT_MEMO_REQUEST_SRV\n    tags:\n      - Billing\n      - Credit Memo\n      - OData\n      - Sales Document\n    properties:\n      - type: Documentation\n\
  \        url: https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-credit-memo-request-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:debit-memo-request\n    name: Debit Memo Request API\n    description: >-\n      Create, read, update, and delete debit memo requests. Supports the full\n      lifecycle of debit memo requests used to charge customers for additional\n      amounts.\n    humanURL: https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_DEBIT_MEMO_REQUEST_SRV\n    tags:\n      - Billing\n      - Debit Memo\n      - OData\n      - Sales Document\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-debit-memo-request-openapi.yml\n      - type: JSONLD\n\
  \        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:sales-contract\n    name: Sales Contract API\n    description: >-\n      Create and manage sales contracts including quantity contracts and value\n      contracts. Supports contract lifecycle management from creation through\n      fulfillment tracking.\n    humanURL: https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_CONTRACT_SRV\n    tags:\n      - Agreement\n      - OData\n      - S/4HANA\n      - Sales Contract\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-sales-contract-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:sales-inquiry\n    name: Sales Inquiry API\n    description: >-\n      Read sales inquiries from SAP S/4HANA.\
  \ Provides access to sales inquiry\n      documents used in the pre-sales process to capture customer interest in\n      products or services.\n    humanURL: https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_INQUIRY_SRV\n    tags:\n      - OData\n      - Pre-Sales\n      - S/4HANA\n      - Sales Inquiry\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-sales-inquiry-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:sales-scheduling-agreement\n    name: Sales Scheduling Agreement API\n    description: >-\n      Manage sales scheduling agreements in SAP S/4HANA. Scheduling agreements\n      define delivery schedules for recurring deliveries of materials to\n      customers over a specified period.\n    humanURL: https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview\n\
  \    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_SCHEDULING_AGREEMENT\n    tags:\n      - Logistics\n      - OData\n      - Sales Contract\n      - Scheduling Agreement\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-sales-scheduling-agreement-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:customer-return\n    name: Customer Return API\n    description: >-\n      Create, read, update, and delete customer returns in SAP S/4HANA.\n      Supports integration with customer return processing including SAP\n      Advanced Returns Management using deep insert requests.\n    humanURL: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_RETURN_SRV\n    tags:\n      - Customer\
  \ Returns\n      - OData\n      - Reverse Logistics\n      - S/4HANA\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-customer-return-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-sd-customer-return-schema.json\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:customer-returns-delivery\n    name: Customer Returns Delivery API\n    description: >-\n      Manage customer returns deliveries in SAP S/4HANA. Enables processing\n      of inbound deliveries related to customer returns, including goods receipt\n      and inspection.\n    humanURL: https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_RETURN_DELIVERY_SRV_0002\n    tags:\n      - OData\n      - Returns Delivery\n      - Reverse Logistics\n\
  \      - Shipping\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-customer-returns-delivery-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:customer-material\n    name: Customer Material API\n    description: >-\n      Manage customer-material information records that link customer-specific\n      material numbers to internal material numbers. Supports the sales process\n      by mapping customer part numbers to SAP materials.\n    humanURL: https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_MATERIAL_SRV\n    tags:\n      - Customer Material\n      - Master Data\n      - OData\n      - Sales\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview\n\
  \      - type: OpenAPI\n        url: openapi/sap-sd-customer-material-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\n  - aid: sap-sales-and-distribution-sd:inbound-delivery\n    name: Inbound Delivery API\n    description: >-\n      Create and manage inbound deliveries in SAP S/4HANA. Supports creation\n      of inbound deliveries with reference to sales documents and manages\n      batch-split items for existing deliveries.\n    humanURL: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview\n    baseURL: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_INBOUND_DELIVERY_SRV_0002\n    tags:\n      - Inbound Delivery\n      - Logistics\n      - OData\n      - Warehouse\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview\n      - type: OpenAPI\n        url: openapi/sap-sd-inbound-delivery-openapi.yml\n      - type: JSONLD\n        url: json-ld/sap-sd-context.jsonld\n\
  \ncommon:\n  - type: Portal\n    url: https://api.sap.com\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_S4HANA_CLOUD\n  - type: Website\n    url: https://www.sap.com\n  - type: Getting Started\n    url: https://developers.sap.com/tutorials.html\n  - type: Authentication\n    url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/\n  - type: Blog\n    url: https://community.sap.com/t5/c-khhcw49343/SD+%28Sales+and+Distribution%29/pd-p/209057551571413566377230676804921\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: Support\n    url: https://support.sap.com\n  - type: Terms of Service\n    url: https://www.sap.com/about/agreements/product-use-and-support-terms.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: GitHub Organization\n    url: https://github.com/SAP\n  - type: Community\n    url: https://community.sap.com\n  - type: Login\n    url:\
  \ https://accounts.sap.com\n  - type: Sign Up\n    url: https://developers.sap.com\n  - type: SDK\n    url: https://sap.github.io/cloud-sdk/\n  - type: SDK\n    url: https://github.com/SAP/cloud-sdk-js\n  - type: SpectralRules\n    url: rules/sap-sd-rules.yml\n  - type: Capabilities\n    url: capabilities/order-to-cash.yaml\n  - type: Capabilities\n    url: capabilities/customer-management.yaml\n  - type: Vocabulary\n    url: vocabulary/sap-sd-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml
tags:
- Distribution
- ERP
- OData
- S/4HANA
- Sales
- SAP
url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml
use_cases: []
---
