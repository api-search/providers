---
api_count: 18
api_specs:
- filename: overview
  format: yaml
  label: SAP S/4HANA Business Partner API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_BUSINESS_PARTNER/overview
- filename: sap-s4hana-sales-order-openapi.yml
  format: yaml
  label: SAP S/4HANA Sales Order API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-s4hana/refs/heads/main/openapi/sap-s4hana-sales-order-openapi.yml
- filename: overview
  format: yaml
  label: SAP S/4HANA Purchase Order API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Material Document API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Product Master API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_PRODUCT_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Journal Entry API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_JOURNALENTRY_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Billing Document API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Supplier Invoice API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Customer Return API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Purchase Requisition API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Outbound Delivery API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Inbound Delivery API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Cost Center API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_COSTCENTER_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA GL Account API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Bank Master API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_BANKDETAIL_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Production Order API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Maintenance Order API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_MAINTENANCEORDER/overview
- filename: overview
  format: yaml
  label: SAP S/4HANA Workforce Timesheet API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/overview
apis:
- description: API for creating, reading, updating, and deleting business partner master data.
  name: SAP S/4HANA Business Partner API
  slug: ''
- description: API for managing sales orders including creation, updates, and status changes.
  name: SAP S/4HANA Sales Order API
  slug: ''
- description: API for creating and managing purchase orders in procurement processes.
  name: SAP S/4HANA Purchase Order API
  slug: ''
- description: API for posting goods movements and managing inventory transactions.
  name: SAP S/4HANA Material Document API
  slug: ''
- description: API for managing product and material master data.
  name: SAP S/4HANA Product Master API
  slug: ''
- description: API for creating and managing financial journal entries.
  name: SAP S/4HANA Journal Entry API
  slug: ''
- description: API for reading, canceling, and retrieving PDFs of billing documents in sales and distribution.
  name: SAP S/4HANA Billing Document API
  slug: ''
- description: API for creating and processing supplier invoices referenced to purchase orders.
  name: SAP S/4HANA Supplier Invoice API
  slug: ''
- description: API for integrating external applications with customer return processing including advanced returns management.
  name: SAP S/4HANA Customer Return API
  slug: ''
- description: API for creating, updating, and managing purchase requisitions in procurement workflows.
  name: SAP S/4HANA Purchase Requisition API
  slug: ''
- description: API for creating, reading, updating, and deleting outbound deliveries including goods issue and picking operations.
  name: SAP S/4HANA Outbound Delivery API
  slug: ''
- description: API for creating, reading, updating, and deleting inbound deliveries for procurement and logistics.
  name: SAP S/4HANA Inbound Delivery API
  slug: ''
- description: API for reading cost center master data used in controlling and cost management.
  name: SAP S/4HANA Cost Center API
  slug: ''
- description: API for reading general ledger account master data in chart of accounts.
  name: SAP S/4HANA GL Account API
  slug: ''
- description: API for reading bank master data including bank keys, SWIFT codes, and bank details.
  name: SAP S/4HANA Bank Master API
  slug: ''
- description: API for reading production order data including components, operations, and status information.
  name: SAP S/4HANA Production Order API
  slug: ''
- description: API for reading maintenance order data used in plant maintenance and enterprise asset management.
  name: SAP S/4HANA Maintenance Order API
  slug: ''
- description: API for creating, reading, updating, and deleting workforce timesheet entries with automatic posting to controlling.
  name: SAP S/4HANA Workforce Timesheet API
  slug: ''
capabilities:
- description: Unified order-to-cash capability combining sales order management with items, partners, pricing, schedule lines, and text records. Used by sales operations and order management teams.
  name: SAP S/4HANA Order-to-Cash
  slug: order-to-cash
common:
- title: ''
  type: Portal
  url: https://api.sap.com
- title: ''
  type: GettingStarted
  url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/1e45cfd73e814aa6b1a1118e2c1d3cec.html
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html
- title: ''
  type: ChangeLog
  url: https://api.sap.com/releasenotes
- title: ''
  type: Support
  url: https://support.sap.com
- title: ''
  type: TermsOfService
  url: https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: API Catalog
  url: https://api.sap.com/products/SAPS4HANACloud/apis/all
- title: ''
  type: API Packages
  url: https://api.sap.com/products/SAPS4HANACloud/apis/packages
- title: ''
  type: OData V4 APIs
  url: https://api.sap.com/products/SAPS4HANACloud/apis/ODATAV4
- title: ''
  type: REST APIs
  url: https://api.sap.com/products/SAPS4HANACloud/apis/REST
- title: ''
  type: On-Premise API Catalog
  url: https://api.sap.com/products/SAPS4HANA/apis/all
- title: ''
  type: On-Premise API Packages
  url: https://api.sap.com/products/SAPS4HANA/apis/packages
- title: ''
  type: Private Edition APIs
  url: https://api.sap.com/products/SAPS4HANACloudPrivateEdition/apis/packages
- title: ''
  type: Community
  url: https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-s-4hana-apis-and-where-to-find-them/ba-p/13723939
- title: ''
  type: StatusPage
  url: https://www.sap.com/about/cloud-trust-center/cloud-service-status.html
created: '2024-01-15'
description: Collection of SAP S/4HANA Cloud and On-Premise APIs for enterprise resource planning.
features:
- description: RESTful APIs following OData protocol for standardized CRUD operations and query capabilities.
  name: OData V2 and V4 APIs
- description: Create complex documents with header and dependent entities in a single API request.
  name: Deep Insert
- description: ETag-based concurrency control to prevent conflicting updates to business documents.
  name: Optimistic Concurrency
- description: Synchronous API access to live ERP data for real-time business process integration.
  name: Real-Time Integration
- description: APIs spanning finance, sales, procurement, logistics, manufacturing, and HR modules.
  name: Multi-Module Coverage
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations:
- description: Native integration with SAP BTP for extensions, analytics, and AI/ML capabilities.
  name: SAP Business Technology Platform
- description: Pre-built integration flows for connecting S/4HANA with third-party applications.
  name: SAP Integration Suite
- description: Integration with Excel and Outlook for business data analysis and communication workflows.
  name: Microsoft Office
jsonld:
- class_count: 10
  name: Sap S4Hana Context
  property_count: 14
  slug: sap-s4hana-context
- class_count: 0
  name: Sap S4Hana Sales Order Context
  property_count: 0
  slug: sap-s4hana-sales-order-context
layout: provider
modified: '2026-04-18'
name: SAP S/4HANA
rules:
- name: SAP S/4HANA API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: sap-s4hana-spectral-rules
skills: []
slug: sap-s4hana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP S/4HANA\ndescription: >-\n  Collection of SAP S/4HANA Cloud and On-Premise APIs for enterprise resource planning.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\nurl: https://api.sap.com/apis.json\napis:\n  - name: SAP S/4HANA Business Partner API\n    description: >-\n      API for creating, reading, updating, and deleting business partner master data.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_BUSINESS_PARTNER/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BUSINESS_PARTNER\n    tags:\n      - Business Partner\n      - Customer\n      - ERP\n      - Master Data\n      - Supplier\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/873c58e32fa642eea4ffb53d80819fa3.html\n\
  \      - type: Console\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/tryout\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html\n      - type: APIReference\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_BUSINESS_PARTNER/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Sales Order API\n    description: >-\n      API for managing sales orders including creation, updates, and status changes.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_SALES_ORDER_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_ORDER_SRV\n    tags:\n      - ERP\n      - Order Management\n      - Sales\n      - Sales Order\n    properties:\n     \
  \ - type: OpenAPI\n        url: openapi/sap-s4hana-sales-order-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sap-s4hana-sales-order-schema.json\n      - type: JSONLD\n        url: json-ld/sap-s4hana-context.jsonld\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_SALES_ORDER_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/cd99a61e5e3f45789c954055c1e31de0/46e2b3e1e0d44419b86e4f0f6e90a0c9.html\n      - type: Console\n        url: https://api.sap.com/api/API_SALES_ORDER_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_SALES_ORDER_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_SALES_ORDER_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Purchase Order API\n    description: >-\n      API for creating and managing purchase orders in procurement processes.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n\
  \    humanUrl: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PURCHASEORDER_PROCESS_SRV\n    tags:\n      - ERP\n      - Procurement\n      - Purchase Order\n      - Purchasing\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/68bf513d4c6742ddb5c0268d46b48b7c/7e0da70d14b44e0cac79c2a29c21b695.html\n      - type: Console\n        url: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Material Document API\n    description: >-\n      API for\
  \ posting goods movements and managing inventory transactions.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_MATERIAL_DOCUMENT_SRV\n    tags:\n      - ERP\n      - Goods Movement\n      - Inventory\n      - Material Document\n      - Warehouse\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0dd0e7f348b04fc7b4e6e63bc9e1db9f/e5ced76872764cbbb8d78e81e21e7f35.html\n      - type: Console\n        url: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/schema\n    contact:\n\
  \      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Product Master API\n    description: >-\n      API for managing product and material master data.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_PRODUCT_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PRODUCT_SRV\n    tags:\n      - ERP\n      - Master Data\n      - Material\n      - Product\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_PRODUCT_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/48a7b615c24444a9b3a6f2810f88db71.html\n      - type: Console\n        url: https://api.sap.com/api/API_PRODUCT_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_PRODUCT_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_PRODUCT_SRV/schema\n\
  \    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Journal Entry API\n    description: >-\n      API for creating and managing financial journal entries.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_JOURNALENTRY_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_JOURNALENTRY_SRV\n    tags:\n      - Accounting\n      - ERP\n      - Finance\n      - General Ledger\n      - Journal Entry\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_JOURNALENTRY_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/b8c083f8f1614da6bf6f7a6e06c4f9be/e0f6c2e84e214c8c8d77a24b40a11ae8.html\n      - type: Console\n        url: https://api.sap.com/api/API_JOURNALENTRY_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_JOURNALENTRY_SRV/resource\n   \
  \   - type: JSONSchema\n        url: https://api.sap.com/api/API_JOURNALENTRY_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Billing Document API\n    description: >-\n      API for reading, canceling, and retrieving PDFs of billing documents in sales\n      and distribution.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BILLING_DOCUMENT_SRV\n    tags:\n      - Billing\n      - ERP\n      - Finance\n      - Invoice\n      - Sales\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/03c04db2a7434731b7fe21dca77440da/65680dabb62546029175655482f85edc.html\n      - type: Console\n        url: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/tryout\n\
  \      - type: APIReference\n        url: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Supplier Invoice API\n    description: >-\n      API for creating and processing supplier invoices referenced to purchase orders.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SUPPLIERINVOICE_PROCESS_SRV\n    tags:\n      - Accounts Payable\n      - ERP\n      - Finance\n      - Procurement\n      - Supplier Invoice\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0864cb07010642b3bde45a20de4975bc/8ddf1d448ce74a799390a1706d90ca3d.html\n\
  \      - type: Console\n        url: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Customer Return API\n    description: >-\n      API for integrating external applications with customer return processing including\n      advanced returns management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_RETURN_SRV\n    tags:\n      - Customer Return\n      - ERP\n      - Logistics\n      - Returns Management\n      - Sales\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview\n\
  \      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/03c04db2a7434731b7fe21dca77440da/69bd2e81cb394eb0b3d8eae85d6b4517.html\n      - type: Console\n        url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Purchase Requisition API\n    description: >-\n      API for creating, updating, and managing purchase requisitions in procurement\n      workflows.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PURCHASEREQ_PROCESS_SRV\n    tags:\n      - ERP\n      - Procurement\n      - Purchase\
  \ Requisition\n      - Purchasing\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/overview\n      - type: Console\n        url: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Outbound Delivery API\n    description: >-\n      API for creating, reading, updating, and deleting outbound deliveries including\n      goods issue and picking operations.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_OUTBOUND_DELIVERY_SRV_0002\n    tags:\n      - ERP\n\
  \      - Logistics\n      - Outbound Delivery\n      - Shipping\n      - Warehouse\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/588780cab2774a7ab9fffca3a7f919fe/113abb06f3fe4e94987d35d5f86ba1ac.html\n      - type: Console\n        url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Inbound Delivery API\n    description: >-\n      API for creating, reading, updating, and deleting inbound deliveries for procurement\n      and logistics.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl:\
  \ https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_INBOUND_DELIVERY_SRV_0002\n    tags:\n      - ERP\n      - Inbound Delivery\n      - Logistics\n      - Receiving\n      - Warehouse\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/588780cab2774a7ab9fffca3a7f919fe/f3ff58c5e7ec43c7b55a503be6633567.html\n      - type: Console\n        url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Cost Center API\n    description: >-\n      API for\
  \ reading cost center master data used in controlling and cost management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_COSTCENTER_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_COSTCENTER_SRV\n    tags:\n      - Controlling\n      - Cost Center\n      - ERP\n      - Finance\n      - Master Data\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_COSTCENTER_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/6b39bd1d0e5e4099a5b65d835c29c696/5792333ddf3c47eaad4314b071dfd684.html\n      - type: Console\n        url: https://api.sap.com/api/API_COSTCENTER_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_COSTCENTER_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_COSTCENTER_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n\
  \  - name: SAP S/4HANA GL Account API\n    description: >-\n      API for reading general ledger account master data in chart of accounts.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_GLACCOUNTINCHARTOFACCOUNTS_SRV\n    tags:\n      - Accounting\n      - ERP\n      - Finance\n      - General Ledger\n      - GL Account\n      - Master Data\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/overview\n      - type: Console\n        url: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/schema\n    contact:\n      - type: Support\n\
  \        url: https://support.sap.com\n  - name: SAP S/4HANA Bank Master API\n    description: >-\n      API for reading bank master data including bank keys, SWIFT codes, and bank\n      details.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_BANKDETAIL_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BANKDETAIL_SRV\n    tags:\n      - Bank\n      - ERP\n      - Finance\n      - Master Data\n      - Payment\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_BANKDETAIL_SRV/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/e296651f454c4284ade361292c633d69/1de6770532554d43a1d026f57e7dd46e.html\n      - type: Console\n        url: https://api.sap.com/api/API_BANKDETAIL_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_BANKDETAIL_SRV/resource\n      - type: JSONSchema\n \
  \       url: https://api.sap.com/api/API_BANKDETAIL_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Production Order API\n    description: >-\n      API for reading production order data including components, operations, and\n      status information.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PRODUCTION_ORDER_2_SRV\n    tags:\n      - ERP\n      - Manufacturing\n      - Production Order\n      - Production Planning\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/overview\n      - type: Console\n        url: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/resource\n      - type: JSONSchema\n\
  \        url: https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Maintenance Order API\n    description: >-\n      API for reading maintenance order data used in plant maintenance and enterprise\n      asset management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_MAINTENANCEORDER/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_MAINTENANCEORDER\n    tags:\n      - Asset Management\n      - ERP\n      - Maintenance Order\n      - Plant Maintenance\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_MAINTENANCEORDER/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/2dfa044a255f49e89a3050daf3c61c11/ff951ebb44664d87b2a8db9290a41dc2.html\n      - type: Console\n        url: https://api.sap.com/api/API_MAINTENANCEORDER/tryout\n\
  \      - type: APIReference\n        url: https://api.sap.com/api/API_MAINTENANCEORDER/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_MAINTENANCEORDER/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\n  - name: SAP S/4HANA Workforce Timesheet API\n    description: >-\n      API for creating, reading, updating, and deleting workforce timesheet entries\n      with automatic posting to controlling.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanUrl: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/overview\n    baseUrl: https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_MANAGE_WORKFORCE_TIMESHEET\n    tags:\n      - ERP\n      - Human Resources\n      - Time Management\n      - Timesheet\n      - Workforce\n    properties:\n      - type: OpenAPI\n        url: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/overview\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/b08cb360201544ec803330fefa59b0f7/fa198e62c6d24788bd1f82082feb3096.html\n\
  \      - type: Console\n        url: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/tryout\n      - type: APIReference\n        url: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/resource\n      - type: JSONSchema\n        url: https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/schema\n    contact:\n      - type: Support\n        url: https://support.sap.com\ncommon:\n  - type: Portal\n    url: https://api.sap.com\n  - type: GettingStarted\n    url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/1e45cfd73e814aa6b1a1118e2c1d3cec.html\n  - type: Authentication\n    url: https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html\n  - type: ChangeLog\n    url: https://api.sap.com/releasenotes\n  - type: Support\n    url: https://support.sap.com\n  - type: TermsOfService\n    url: https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html\n  - type: PrivacyPolicy\n    url:\
  \ https://www.sap.com/about/legal/privacy.html\n  - type: API Catalog\n    url: https://api.sap.com/products/SAPS4HANACloud/apis/all\n  - type: API Packages\n    url: https://api.sap.com/products/SAPS4HANACloud/apis/packages\n  - type: OData V4 APIs\n    url: https://api.sap.com/products/SAPS4HANACloud/apis/ODATAV4\n  - type: REST APIs\n    url: https://api.sap.com/products/SAPS4HANACloud/apis/REST\n  - type: On-Premise API Catalog\n    url: https://api.sap.com/products/SAPS4HANA/apis/all\n  - type: On-Premise API Packages\n    url: https://api.sap.com/products/SAPS4HANA/apis/packages\n  - type: Private Edition APIs\n    url: https://api.sap.com/products/SAPS4HANACloudPrivateEdition/apis/packages\n  - type: Community\n    url: https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-s-4hana-apis-and-where-to-find-them/ba-p/13723939\n  - type: StatusPage\n    url: https://www.sap.com/about/cloud-trust-center/cloud-service-status.html\n  - type: Features\n    data:\n\
  \      - name: OData V2 and V4 APIs\n        description: RESTful APIs following OData protocol for standardized CRUD operations and query capabilities.\n      - name: Deep Insert\n        description: Create complex documents with header and dependent entities in a single API request.\n      - name: Optimistic Concurrency\n        description: ETag-based concurrency control to prevent conflicting updates to business documents.\n      - name: Real-Time Integration\n        description: Synchronous API access to live ERP data for real-time business process integration.\n      - name: Multi-Module Coverage\n        description: APIs spanning finance, sales, procurement, logistics, manufacturing, and HR modules.\n  - type: UseCases\n    data:\n      - name: Order-to-Cash\n        description: Automate the sales process from sales order creation through delivery and billing.\n      - name: Procure-to-Pay\n        description: Streamline procurement from purchase requisition through purchase\
  \ order, receipt, and invoice.\n      - name: Financial Close\n        description: Automate journal entries, cost center reporting, and GL account management for period close.\n      - name: Supply Chain Visibility\n        description: Track inbound and outbound deliveries, inventory movements, and material documents in real time.\n  - type: Integrations\n    data:\n      - name: SAP Business Technology Platform\n        description: Native integration with SAP BTP for extensions, analytics, and AI/ML capabilities.\n      - name: SAP Integration Suite\n        description: Pre-built integration flows for connecting S/4HANA with third-party applications.\n      - name: Microsoft Office\n        description: Integration with Excel and Outlook for business data analysis and communication workflows.\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Business Applications\n  - Cloud\n  - Enterprise Resource Planning\n  - ERP\n\
  \  - Finance\n  - Human Resources\n  - Inventory\n  - Logistics\n  - Manufacturing\n  - Plant Maintenance\n  - Procurement\n  - S/4HANA\n  - Sales\n  - SAP\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-s4hana/refs/heads/main/apis.yml
tags:
- Business Applications
- Cloud
- Enterprise Resource Planning
- ERP
- Finance
- Human Resources
- Inventory
- Logistics
- Manufacturing
- Plant Maintenance
- Procurement
- S/4HANA
- Sales
- SAP
url: https://api.sap.com/apis.json
use_cases:
- description: Automate the sales process from sales order creation through delivery and billing.
  name: Order-to-Cash
- description: Streamline procurement from purchase requisition through purchase order, receipt, and invoice.
  name: Procure-to-Pay
- description: Automate journal entries, cost center reporting, and GL account management for period close.
  name: Financial Close
- description: Track inbound and outbound deliveries, inventory movements, and material documents in real time.
  name: Supply Chain Visibility
---
