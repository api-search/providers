---
api_count: 78
api_specs:
- filename: sap-ariba-procurement-api.yml
  format: yaml
  label: SAP Ariba Procurement API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/openapi/sap-ariba-procurement-api.yml
- filename: openapi.json
  format: json
  label: SAP Ariba Sourcing API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/sourcing/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Supplier Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/supplier/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Contract Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/contracts/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Analytical Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/analytics/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Invoice Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/invoices/openapi.json
apis:
- description: Enables integration with procurement processes including requisitions, purchase orders, invoices, suppliers, and receipts across the SAP Business Network.
  name: SAP Ariba Procurement API
  slug: ''
- description: Provides access to sourcing events, RFx processes, auctions, and bid management.
  name: SAP Ariba Sourcing API
  slug: ''
- description: Manages supplier lifecycle including onboarding, qualification, performance, and risk assessment.
  name: SAP Ariba Supplier Management API
  slug: ''
- description: Enables contract creation, management, compliance tracking, and renewal workflows.
  name: SAP Ariba Contract Management API
  slug: ''
- description: Provides access to spend analytics, reporting data, and business intelligence metrics.
  name: SAP Ariba Analytical Reporting API
  slug: ''
- description: Manages invoice processing, approval workflows, and payment status tracking.
  name: SAP Ariba Invoice Management API
  slug: ''
- description: Allows buyers to create, manage, and track purchase orders across the SAP Ariba Network.
  name: Ariba Network Purchase Orders Buyer API
  slug: ''
- description: Enables suppliers to retrieve purchase order and line item information from buyers on the SAP Business Network.
  name: Ariba Network Purchase Orders Supplier API
  slug: ''
- description: Provides access to supplier profile details on the SAP Ariba Network.
  name: Ariba Network Supplier Profile API
  slug: ''
- description: Extracts invoice header information from the SAP Ariba Network for data analysis and integration.
  name: Ariba Network Invoice Header Data Extraction API
  slug: ''
- description: Ensures contract compliance by validating procurement activities against contract terms and conditions.
  name: SAP Ariba Contract Compliance API
  slug: ''
- description: Provides access to general supplier data including company information and classification details.
  name: SAP Ariba Supplier Data API
  slug: ''
- description: Retrieves supplier data with pagination support for handling large datasets.
  name: SAP Ariba Supplier Data API with Pagination
  slug: ''
- description: Extracts detailed supplier information for integration with external systems and analytics.
  name: SAP Ariba Supplier Data Extraction API
  slug: ''
- description: Provides supplier profile and related detail information for supplier lifecycle management.
  name: SAP Ariba Supplier Information API
  slug: ''
- description: Invites suppliers to participate in procurement transactions and network activities.
  name: SAP Ariba Supplier Invite API
  slug: ''
- description: Analyzes and reports on supplier risk exposure across the supply chain.
  name: SAP Ariba Risk Exposure API
  slug: ''
- description: Manages supplier risk engagement activities and assessment workflows.
  name: SAP Ariba Supplier Risk Engagements API
  slug: ''
- description: Provides risk classification and category details for supplier risk exposure analysis.
  name: SAP Ariba Risk Category Information API
  slug: ''
- description: Handles approval workflows for procurement documents including requisitions and purchase orders.
  name: SAP Ariba Document Approval API
  slug: ''
- description: Enables external approval routing for sourcing events and supplier management processes.
  name: SAP Ariba External Approval API for Sourcing and Supplier Management
  slug: ''
- description: Enables applications to manage catalog content and get faceted catalog data based on specific attributes.
  name: SAP Ariba Catalog Content API
  slug: ''
- description: Controls catalog operations across the SAP Ariba Network including subscriptions and publishing.
  name: SAP Ariba Network Catalog Management API
  slug: ''
- description: Manages internal catalog shopping experiences for procurement users.
  name: SAP Ariba Internal Catalogs Shop API
  slug: ''
- description: Manages public marketplace catalog experiences for procurement users.
  name: SAP Ariba Public Catalogs Shop API
  slug: ''
- description: Retrieves contract workspace information for contract lifecycle management.
  name: SAP Ariba Contract Workspace Retrieval API
  slug: ''
- description: Administers contract collaboration spaces including creation, updates, and lifecycle management.
  name: SAP Ariba Contract Workspace Management API
  slug: ''
- description: Administers contract term definitions and clause libraries.
  name: SAP Ariba Contract Terms Management API
  slug: ''
- description: Delivers operational metrics and reporting data for procurement activities.
  name: SAP Ariba Operational Reporting API for Procurement
  slug: ''
- description: Delivers operational metrics and reporting data for strategic sourcing activities.
  name: SAP Ariba Operational Reporting API for Strategic Sourcing
  slug: ''
- description: Delivers analytics across strategic and operational procurement domains including contracts, sourcing, spend analysis, and buying.
  name: SAP Ariba Analytical Reporting API for Strategic and Operational Procurement
  slug: ''
- description: Obtains master data for sourcing operations including commodity codes and regions.
  name: SAP Ariba Master Data Retrieval API for Sourcing
  slug: ''
- description: Retrieves procurement master data including cost centers, accounts, and units of measure.
  name: SAP Ariba Master Data Retrieval API for Procurement
  slug: ''
- description: Oversees sourcing project workflows including event creation and management.
  name: SAP Ariba Sourcing Project Management API
  slug: ''
- description: Manages sourcing events and their lifecycle including RFx and auction events.
  name: SAP Ariba Event Management API
  slug: ''
- description: Enables proxy bidding mechanisms for sourcing events on behalf of suppliers.
  name: SAP Ariba Surrogate Bid API
  slug: ''
- description: Manages order modification requests from the buyer perspective.
  name: SAP Ariba Order Change Requests API for Buyers
  slug: ''
- description: Handles order change request processing from the supplier perspective.
  name: SAP Ariba Order Change Requests API for Suppliers
  slug: ''
- description: Receives and processes shipment notifications for buyers on the Ariba Network.
  name: SAP Ariba Ship Notice API for Buyers
  slug: ''
- description: Sends shipment notifications from suppliers to buyers on the Ariba Network.
  name: SAP Ariba Ship Notice API for Suppliers
  slug: ''
- description: Validates service fulfillment and delivery for buyers in service procurement.
  name: SAP Ariba Proof of Service API for Buyers
  slug: ''
- description: Validates service fulfillment and delivery for suppliers in service procurement.
  name: SAP Ariba Proof of Service API for Suppliers
  slug: ''
- description: Enables buyer-side planning and forecast collaboration with suppliers.
  name: SAP Ariba Planning Collaboration Buyer API
  slug: ''
- description: Enables supplier-side planning and forecast collaboration with buyers.
  name: SAP Ariba Planning Collaboration Supplier API
  slug: ''
- description: Imports item volume data for procurement planning and sourcing optimization.
  name: SAP Ariba Item Volume Import API
  slug: ''
- description: Imports bill of materials structures for sourcing and procurement processes.
  name: SAP Ariba Bill of Materials Import API
  slug: ''
- description: Organizes product classification and category hierarchy structures.
  name: SAP Ariba Product Hierarchy Management API
  slug: ''
- description: Extracts and manages pricing data for product sourcing price information.
  name: SAP Ariba Pricing API for Product Sourcing
  slug: ''
- description: Extracts cost component and cost breakdown information for analysis.
  name: SAP Ariba Cost Breakdown Data Extraction API
  slug: ''
- description: Searches and retrieves content across the SAP Ariba platform.
  name: SAP Ariba Content Lookup API
  slug: ''
- description: Provides audit trail search capabilities across procurement and sourcing activities.
  name: SAP Ariba Audit Search API
  slug: ''
- description: Initiates and creates procurement workspace environments for project collaboration.
  name: SAP Ariba Create Procurement Workspace API
  slug: ''
- description: Extends workflow processing capabilities for custom procurement and sourcing processes.
  name: SAP Ariba Flow Extension API
  slug: ''
- description: Manages long-running asynchronous operations and their status tracking.
  name: SAP Ariba Asynchronous Requests Management API
  slug: ''
- description: Monitors and queries integration events for procurement process tracking.
  name: SAP Ariba Integration Event Monitoring Query API for Procurement
  slug: ''
- description: Tracks integration health and performance for procurement system integrations.
  name: SAP Ariba Integration Monitoring API for Procurement
  slug: ''
- description: Tracks integration health and performance for strategic sourcing system integrations.
  name: SAP Ariba Integration Monitoring API for Strategic Sourcing
  slug: ''
- description: Observes and reports on transaction activities and processing status.
  name: SAP Ariba Transaction Monitoring API
  slug: ''
- description: Exports non-disclosure agreement data for compliance and record keeping.
  name: SAP Ariba NDA Data Export API
  slug: ''
- description: Connects to external catalog systems for punchout and roundtrip catalog integration.
  name: SAP Ariba Catalog Connectivity Service API
  slug: ''
- description: Manages trading partner certifications and compliance documentation.
  name: SAP Ariba Trading Partner Profile Certification API
  slug: ''
- description: Validates user eligibility and qualifications for procurement processes.
  name: SAP Ariba User Qualification API
  slug: ''
- description: Implements System for Cross-domain Identity Management for user provisioning and management.
  name: SAP Ariba SCIM API
  slug: ''
- description: Creates and manages custom form definitions for procurement and sourcing workflows.
  name: SAP Ariba Custom Forms API
  slug: ''
- description: Manages dynamic reference and lookup tables for configurable procurement data.
  name: SAP Ariba Dynamic Lookup Table API
  slug: ''
- description: Manages guided buying documentation and functional purchase request workflows.
  name: SAP Ariba Guided Buying Functional Documents API
  slug: ''
- description: Manages asset lifecycle and inventory tracking for procurement-related assets.
  name: SAP Ariba Asset Management API
  slug: ''
- description: Reviews and manages system configuration parameters for Ariba solutions.
  name: SAP Ariba Configuration Parameter Review API
  slug: ''
- description: Organizes and manages project-related documents within sourcing and procurement projects.
  name: SAP Ariba Project Document Management API
  slug: ''
- description: Exports public procurement announcements and tender notices.
  name: SAP Ariba Public Procurement Notices Export API
  slug: ''
- description: Manages electronic tendering announcements and notice lifecycle.
  name: SAP Ariba ETendering Notice Management API
  slug: ''
- description: Publishes RFx opportunities to external marketplaces for broader supplier discovery.
  name: SAP Ariba Discovery RFx Publication TO External Marketplace API
  slug: ''
- description: Imports RFx opportunities from external marketplaces into SAP Ariba.
  name: SAP Ariba Discovery RFx Publication FROM External Marketplace API
  slug: ''
- description: Manages tagging and classification for materials and bill of materials entries.
  name: SAP Ariba Materials and BOM Tag Management API
  slug: ''
- description: Monitors data replication status across multi-ERP configurations.
  name: SAP Ariba Data Replication Status API
  slug: ''
- description: Tracks master data synchronization job status for operational procurement.
  name: SAP Ariba Master Data Integration Job Status API
  slug: ''
- description: Imports external risk assessment responses for supplier engagement risk evaluation.
  name: SAP Ariba Engagement Risk Assessment External Response Import API
  slug: ''
- description: Integrates risk findings and event collaboration for supplier risk management.
  name: SAP Ariba Finding and Event Collaboration Integration API for Supplier Risk
  slug: ''
capabilities:
- description: Unified procure-to-pay capability combining purchase orders, invoices, requisitions, suppliers, and receipts. Used by procurement teams and AP automation workflows.
  name: SAP Ariba Procure-to-Pay
  slug: procure-to-pay
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.ariba.com
- title: ''
  type: Authentication
  url: https://developer.ariba.com/api/authentication
- title: ''
  type: GettingStarted
  url: https://developer.ariba.com/api/getting-started
- title: ''
  type: StatusPage
  url: https://status.ariba.com
- title: ''
  type: Support
  url: https://help.sap.com/ariba
- title: ''
  type: TermsOfService
  url: https://www.ariba.com/legal/terms-of-use
- title: ''
  type: RateLimits
  url: https://developer.ariba.com/api/rate-limits
- title: ''
  type: SDK
  url: https://developer.ariba.com/tools/sdks
- title: ''
  type: Community
  url: https://community.ariba.com
- title: ''
  type: ReleaseNotes
  url: https://developer.ariba.com/api/release-notes
- title: ''
  type: Hub
  url: https://api.sap.com/package/SAPAribaOpenAPIs/overview
- title: REST APIs
  type: Hub
  url: https://api.sap.com/package/SAPAribaOpenAPIs/rest
- title: Documents
  type: Hub
  url: https://api.sap.com/package/SAPAribaOpenAPIs/documents
- title: ''
  type: Portal
  url: https://api.sap.com/products/SAPAriba/apis/packages
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/ariba-apis
- title: ''
  type: Quickstart
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers
- title: Steps to Start Using APIs
  type: GettingStarted
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/steps-to-start-using-sap-ariba-apis
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-authentication
- title: SAP Community
  type: Resources
  url: https://community.sap.com
- title: ''
  type: Marketplace
  url: https://www.sap.com/products/spend-management/ariba-network.html
- title: ''
  type: CodeExamples
  url: https://github.com/SAP-samples/ariba-extensibility-samples
- title: ''
  type: Blog
  url: https://community.sap.com/t5/spend-management-blog-posts-by-sap/sap-ariba-api-faq-and-best-practice-on-developer-portal-and-gateway/ba-p/13512565
created: '2024'
description: SAP Ariba is a cloud-based procurement and supply chain collaboration platform that connects buyers and suppliers. It offers APIs for procurement, sourcing, contract management, supplier management, and spend analysis.
features:
- description: End-to-end automation from requisition through purchase order, receipt, and invoice processing.
  name: Procure-to-Pay Automation
- description: Access to millions of suppliers on the SAP Business Network for discovery and collaboration.
  name: Supplier Network
- description: Automated matching of purchase orders, receipts, and invoices for payment approval.
  name: Three-Way Matching
- description: Full contract creation, compliance tracking, and renewal workflow management.
  name: Contract Lifecycle Management
- description: Comprehensive reporting and analytics across procurement, sourcing, and supplier management.
  name: Spend Analytics
image: https://www.ariba.com/ariba-logo.png
integrations:
- description: Native integration with SAP ERP for purchase order, invoice, and master data synchronization.
  name: SAP S/4HANA
- description: Connect buyers and suppliers for electronic document exchange across the network.
  name: SAP Business Network
- description: Integration with non-SAP ERP systems through standardized APIs and data replication.
  name: External ERP Systems
jsonld:
- class_count: 0
  name: Sap Ariba Context
  property_count: 14
  slug: sap-ariba-context
- class_count: 0
  name: Sap Ariba Procurement Context
  property_count: 0
  slug: sap-ariba-procurement-context
layout: provider
modified: '2026-04-18'
name: SAP Ariba
rules:
- name: SAP Ariba API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: sap-ariba-spectral-rules
skills: []
slug: sap-ariba
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP Ariba\ndescription: SAP Ariba is a cloud-based procurement and supply chain collaboration platform that connects buyers and suppliers. It offers APIs for procurement, sourcing, contract management, supplier management, and spend analysis.\nimage: https://www.ariba.com/ariba-logo.png\nurl: https://www.ariba.com\ncreated: '2024'\nmodified: '2026-04-18'\ntags:\n  - B2B\n  - Contract Management\n  - Procurement\n  - Sourcing\n  - Spend Analysis\n  - Supplier Management\n  - Supply Chain\napis:\n  - name: SAP Ariba Procurement API\n    description: >-\n      Enables integration with procurement processes including requisitions, purchase\n      orders, invoices, suppliers, and receipts across the SAP Business Network.\n    image: https://api.ariba.com/procurement-icon.png\n    humanURL: https://developer.ariba.com/api/procurement\n    baseURL: https://openapi.ariba.com/api/procurement\n    tags:\n      - Invoices\n      - Procurement\n      - Purchase Orders\n      - Requisitions\n\
  \      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/procurement/overview\n      - type: OpenAPI\n        url: openapi/sap-ariba-procurement-api.yml\n      - type: JSONSchema\n        url: json-schema/sap-ariba-purchase-order-schema.json\n      - type: JSONLD\n        url: json-ld/sap-ariba-context.jsonld\n      - type: Authentication\n        url: https://developer.ariba.com/api/authentication\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n  - name: SAP Ariba Sourcing API\n    description: >-\n      Provides access to sourcing events, RFx processes, auctions, and bid management.\n    image: https://api.ariba.com/sourcing-icon.png\n    humanURL: https://developer.ariba.com/api/sourcing\n    baseURL: https://openapi.ariba.com/api/sourcing\n    tags:\n      - Auctions\n      - Bidding\n      - RFx\n      - Sourcing\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/sourcing/overview\n      - type: OpenAPI\n        url: https://developer.ariba.com/api/sourcing/openapi.json\n      - type: Sandbox\n        url: https://sandbox.ariba.com/api/sourcing\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Management API\n    description: >-\n      Manages supplier lifecycle including onboarding, qualification, performance,\n      and risk assessment.\n    image: https://api.ariba.com/supplier-icon.png\n    humanURL: https://developer.ariba.com/api/supplier\n    baseURL: https://openapi.ariba.com/api/supplier\n    tags:\n      - Onboarding\n      - Performance\n      - Risk Management\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/supplier/overview\n      - type: OpenAPI\n        url: https://developer.ariba.com/api/supplier/openapi.json\n\
  \      - type: PostmanCollection\n        url: https://developer.ariba.com/api/supplier/postman\n      - type: Hub\n        url: https://api.sap.com/api/supplier_management/overview\n  - name: SAP Ariba Contract Management API\n    description: >-\n      Enables contract creation, management, compliance tracking, and renewal workflows.\n    image: https://api.ariba.com/contract-icon.png\n    humanURL: https://developer.ariba.com/api/contracts\n    baseURL: https://openapi.ariba.com/api/contracts\n    tags:\n      - CLM\n      - Compliance\n      - Contracts\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/contracts/overview\n      - type: OpenAPI\n        url: https://developer.ariba.com/api/contracts/openapi.json\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Analytical Reporting API\n    description: >-\n      Provides access to spend analytics, reporting data, and business intelligence\n\
  \      metrics.\n    image: https://api.ariba.com/analytics-icon.png\n    humanURL: https://developer.ariba.com/api/analytics\n    baseURL: https://openapi.ariba.com/api/analytics\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Reporting\n      - Spend Analysis\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/analytics/overview\n      - type: OpenAPI\n        url: https://developer.ariba.com/api/analytics/openapi.json\n      - type: Documentation\n        url: https://developer.ariba.com/api/analytics/query-guide\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Invoice Management API\n    description: >-\n      Manages invoice processing, approval workflows, and payment status tracking.\n    image: https://api.ariba.com/invoice-icon.png\n    humanURL: https://developer.ariba.com/api/invoices\n    baseURL: https://openapi.ariba.com/api/invoices\n    tags:\n      -\
  \ AP Automation\n      - Invoices\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developer.ariba.com/api/apis/invoices/overview\n      - type: OpenAPI\n        url: https://developer.ariba.com/api/invoices/openapi.json\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: Ariba Network Purchase Orders Buyer API\n    description: >-\n      Allows buyers to create, manage, and track purchase orders across the SAP Ariba\n      Network.\n    image: https://api.ariba.com/po-buyer-icon.png\n    humanURL: https://api.sap.com/api/purchase_orders/overview\n    baseURL: https://openapi.ariba.com/api/purchase-orders-buyer\n    tags:\n      - Ariba Network\n      - Buyers\n      - Purchase Orders\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/purchase_orders/overview\n      - type: Hub\n        url: https://api.sap.com/api/purchase_orders/overview\n  - name: Ariba Network Purchase Orders\
  \ Supplier API\n    description: >-\n      Enables suppliers to retrieve purchase order and line item information from\n      buyers on the SAP Business Network.\n    image: https://api.ariba.com/po-supplier-icon.png\n    humanURL: https://api.sap.com/api/purchase_orders_supplier/overview\n    baseURL: https://openapi.ariba.com/api/purchase-orders-supplier\n    tags:\n      - Ariba Network\n      - Purchase Orders\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/purchase_orders_supplier/overview\n      - type: Documentation\n        url: https://help.sap.com/doc/3b0b2f4faaa242dda9004b9f337592bf/cloud/en-US/purchase_order_supplier_api.pdf\n      - type: Hub\n        url: https://api.sap.com/api/purchase_orders_supplier/overview\n  - name: Ariba Network Supplier Profile API\n    description: >-\n      Provides access to supplier profile details on the SAP Ariba Network.\n    image: https://api.ariba.com/supplier-profile-icon.png\n   \
  \ humanURL: https://api.sap.com/api/supplier_management/overview\n    baseURL: https://openapi.ariba.com/api/supplier-profile\n    tags:\n      - Ariba Network\n      - Profiles\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://api.sap.com/api/supplier_management/overview\n      - type: Hub\n        url: https://api.sap.com/api/supplier_management/overview\n  - name: Ariba Network Invoice Header Data Extraction API\n    description: >-\n      Extracts invoice header information from the SAP Ariba Network for data analysis\n      and integration.\n    image: https://api.ariba.com/invoice-extraction-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/invoice-extraction\n    tags:\n      - Ariba Network\n      - Data Extraction\n      - Invoices\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n\
  \  - name: SAP Ariba Contract Compliance API\n    description: >-\n      Ensures contract compliance by validating procurement activities against contract\n      terms and conditions.\n    image: https://api.ariba.com/compliance-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/contract-compliance\n    tags:\n      - Compliance\n      - Contracts\n      - Procurement\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Data API\n    description: >-\n      Provides access to general supplier data including company information and classification\n      details.\n    image: https://api.ariba.com/supplier-data-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-data\n    tags:\n      - Data\n      - Master Data\n      -\
  \ Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Data API with Pagination\n    description: >-\n      Retrieves supplier data with pagination support for handling large datasets.\n    image: https://api.ariba.com/supplier-data-paginated-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-data-paginated\n    tags:\n      - Data\n      - Pagination\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Data Extraction API\n    description: >-\n      Extracts detailed supplier information for integration with external systems\n      and analytics.\n    image: https://api.ariba.com/supplier-extraction-icon.png\n\
  \    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-data-extraction\n    tags:\n      - Data Extraction\n      - Integration\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Information API\n    description: >-\n      Provides supplier profile and related detail information for supplier lifecycle\n      management.\n    image: https://api.ariba.com/supplier-info-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-information\n    tags:\n      - Lifecycle\n      - Profiles\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier\
  \ Invite API\n    description: >-\n      Invites suppliers to participate in procurement transactions and network activities.\n    image: https://api.ariba.com/supplier-invite-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-invite\n    tags:\n      - Invitations\n      - Onboarding\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Risk Exposure API\n    description: >-\n      Analyzes and reports on supplier risk exposure across the supply chain.\n    image: https://api.ariba.com/risk-exposure-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/risk-exposure\n    tags:\n      - Risk Management\n      - Suppliers\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n\
  \      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Supplier Risk Engagements API\n    description: >-\n      Manages supplier risk engagement activities and assessment workflows.\n    image: https://api.ariba.com/risk-engagements-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/supplier-risk-engagements\n    tags:\n      - Assessments\n      - Risk Management\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Risk Category Information API\n    description: >-\n      Provides risk classification and category details for supplier risk exposure\n      analysis.\n    image: https://api.ariba.com/risk-category-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/risk-category\n\
  \    tags:\n      - Categories\n      - Classification\n      - Risk Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Document Approval API\n    description: >-\n      Handles approval workflows for procurement documents including requisitions\n      and purchase orders.\n    image: https://api.ariba.com/approval-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/document-approval\n    tags:\n      - Approvals\n      - Documents\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba External Approval API for Sourcing and Supplier Management\n    description: >-\n      Enables external approval routing for sourcing\
  \ events and supplier management\n      processes.\n    image: https://api.ariba.com/external-approval-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/external-approval\n    tags:\n      - Approvals\n      - Sourcing\n      - Supplier Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Catalog Content API\n    description: >-\n      Enables applications to manage catalog content and get faceted catalog data\n      based on specific attributes.\n    image: https://api.ariba.com/catalog-content-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/catalog-content\n    tags:\n      - Catalogs\n      - Content Management\n      - Products\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n\
  \      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Network Catalog Management API\n    description: >-\n      Controls catalog operations across the SAP Ariba Network including subscriptions\n      and publishing.\n    image: https://api.ariba.com/catalog-mgmt-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/network-catalog\n    tags:\n      - Catalogs\n      - Network\n      - Publishing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Internal Catalogs Shop API\n    description: >-\n      Manages internal catalog shopping experiences for procurement users.\n    image: https://api.ariba.com/internal-catalog-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/internal-catalogs\n\
  \    tags:\n      - Catalogs\n      - Internal\n      - Shopping\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Public Catalogs Shop API\n    description: >-\n      Manages public marketplace catalog experiences for procurement users.\n    image: https://api.ariba.com/public-catalog-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/public-catalogs\n    tags:\n      - Catalogs\n      - Marketplace\n      - Shopping\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Contract Workspace Retrieval API\n    description: >-\n      Retrieves contract workspace information for contract lifecycle management.\n    image: https://api.ariba.com/workspace-retrieval-icon.png\n\
  \    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/contract-workspace-retrieval\n    tags:\n      - CLM\n      - Contracts\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Contract Workspace Management API\n    description: >-\n      Administers contract collaboration spaces including creation, updates, and lifecycle\n      management.\n    image: https://api.ariba.com/workspace-mgmt-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/contract-workspace-management\n    tags:\n      - Contracts\n      - Management\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name:\
  \ SAP Ariba Contract Terms Management API\n    description: >-\n      Administers contract term definitions and clause libraries.\n    image: https://api.ariba.com/contract-terms-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/contract-terms\n    tags:\n      - Clauses\n      - Contracts\n      - Terms\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Operational Reporting API for Procurement\n    description: >-\n      Delivers operational metrics and reporting data for procurement activities.\n    image: https://api.ariba.com/ops-reporting-procurement-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis/operational-reporting-api-for-procurement/operational-reporting-api-for-procurement\n    baseURL: https://openapi.ariba.com/api/operational-reporting-procurement\n    tags:\n\
  \      - Operations\n      - Procurement\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis/operational-reporting-api-for-procurement/operational-reporting-api-for-procurement\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Operational Reporting API for Strategic Sourcing\n    description: >-\n      Delivers operational metrics and reporting data for strategic sourcing activities.\n    image: https://api.ariba.com/ops-reporting-sourcing-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/operational-reporting-sourcing\n    tags:\n      - Operations\n      - Reporting\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Analytical Reporting API for Strategic\
  \ and Operational Procurement\n    description: >-\n      Delivers analytics across strategic and operational procurement domains including\n      contracts, sourcing, spend analysis, and buying.\n    image: https://api.ariba.com/analytical-reporting-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/analytical-reporting\n    tags:\n      - Analytics\n      - Operational Procurement\n      - Reporting\n      - Strategic Procurement\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Master Data Retrieval API for Sourcing\n    description: >-\n      Obtains master data for sourcing operations including commodity codes and regions.\n    image: https://api.ariba.com/master-data-sourcing-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/master-data-sourcing\n\
  \    tags:\n      - Master Data\n      - Reference Data\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Master Data Retrieval API for Procurement\n    description: >-\n      Retrieves procurement master data including cost centers, accounts, and units\n      of measure.\n    image: https://api.ariba.com/master-data-procurement-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/master-data-procurement\n    tags:\n      - Master Data\n      - Procurement\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Sourcing Project Management API\n    description: >-\n      Oversees sourcing project workflows\
  \ including event creation and management.\n    image: https://api.ariba.com/sourcing-project-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/sourcing-project\n    tags:\n      - Events\n      - Projects\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Event Management API\n    description: >-\n      Manages sourcing events and their lifecycle including RFx and auction events.\n    image: https://api.ariba.com/event-mgmt-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/event-management\n    tags:\n      - Auctions\n      - Events\n      - RFx\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n\
  \  - name: SAP Ariba Surrogate Bid API\n    description: >-\n      Enables proxy bidding mechanisms for sourcing events on behalf of suppliers.\n    image: https://api.ariba.com/surrogate-bid-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/surrogate-bid\n    tags:\n      - Bidding\n      - Proxy\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Order Change Requests API for Buyers\n    description: >-\n      Manages order modification requests from the buyer perspective.\n    image: https://api.ariba.com/order-change-buyer-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/order-change-buyer\n    tags:\n      - Buyers\n      - Change Requests\n      - Purchase Orders\n    properties:\n      - type: Documentation\n\
  \        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Order Change Requests API for Suppliers\n    description: >-\n      Handles order change request processing from the supplier perspective.\n    image: https://api.ariba.com/order-change-supplier-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/order-change-supplier\n    tags:\n      - Change Requests\n      - Purchase Orders\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Ship Notice API for Buyers\n    description: >-\n      Receives and processes shipment notifications for buyers on the Ariba Network.\n    image: https://api.ariba.com/ship-notice-buyer-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n\
  \    baseURL: https://openapi.ariba.com/api/ship-notice-buyer\n    tags:\n      - Buyers\n      - Notifications\n      - Shipping\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Ship Notice API for Suppliers\n    description: >-\n      Sends shipment notifications from suppliers to buyers on the Ariba Network.\n    image: https://api.ariba.com/ship-notice-supplier-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/ship-notice-supplier\n    tags:\n      - Notifications\n      - Shipping\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Proof of Service API for Buyers\n    description: >-\n      Validates service fulfillment\
  \ and delivery for buyers in service procurement.\n    image: https://api.ariba.com/pos-buyer-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/proof-of-service-buyer\n    tags:\n      - Buyers\n      - Proof of Service\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Proof of Service API for Suppliers\n    description: >-\n      Validates service fulfillment and delivery for suppliers in service procurement.\n    image: https://api.ariba.com/pos-supplier-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/proof-of-service-supplier\n    tags:\n      - Proof of Service\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n\
  \  - name: SAP Ariba Planning Collaboration Buyer API\n    description: >-\n      Enables buyer-side planning and forecast collaboration with suppliers.\n    image: https://api.ariba.com/planning-buyer-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/planning-collaboration-buyer\n    tags:\n      - Buyers\n      - Collaboration\n      - Forecasting\n      - Planning\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Planning Collaboration Supplier API\n    description: >-\n      Enables supplier-side planning and forecast collaboration with buyers.\n    image: https://api.ariba.com/planning-supplier-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/planning-collaboration-supplier\n    tags:\n      - Collaboration\n      - Forecasting\n\
  \      - Planning\n      - Suppliers\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Item Volume Import API\n    description: >-\n      Imports item volume data for procurement planning and sourcing optimization.\n    image: https://api.ariba.com/item-volume-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/item-volume-import\n    tags:\n      - Import\n      - Planning\n      - Volume\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Bill of Materials Import API\n    description: >-\n      Imports bill of materials structures for sourcing and procurement processes.\n    image: https://api.ariba.com/bom-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n\
  \    baseURL: https://openapi.ariba.com/api/bom-import\n    tags:\n      - BOM\n      - Import\n      - Materials\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Product Hierarchy Management API\n    description: >-\n      Organizes product classification and category hierarchy structures.\n    image: https://api.ariba.com/product-hierarchy-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/product-hierarchy\n    tags:\n      - Classification\n      - Hierarchy\n      - Products\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Pricing API for Product Sourcing\n    description: >-\n      Extracts and manages pricing data for product sourcing\
  \ price information.\n    image: https://api.ariba.com/pricing-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/pricing\n    tags:\n      - Pricing\n      - Products\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Cost Breakdown Data Extraction API\n    description: >-\n      Extracts cost component and cost breakdown information for analysis.\n    image: https://api.ariba.com/cost-breakdown-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/cost-breakdown\n    tags:\n      - Cost Analysis\n      - Data Extraction\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n\
  \  - name: SAP Ariba Content Lookup API\n    description: >-\n      Searches and retrieves content across the SAP Ariba platform.\n    image: https://api.ariba.com/content-lookup-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/content-lookup\n    tags:\n      - Content\n      - Lookup\n      - Search\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Audit Search API\n    description: >-\n      Provides audit trail search capabilities across procurement and sourcing activities.\n    image: https://api.ariba.com/audit-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/audit-search\n    tags:\n      - Audit\n      - Compliance\n      - Search\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n\
  \      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Create Procurement Workspace API\n    description: >-\n      Initiates and creates procurement workspace environments for project collaboration.\n    image: https://api.ariba.com/procurement-workspace-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/procurement-workspace\n    tags:\n      - Collaboration\n      - Procurement\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Flow Extension API\n    description: >-\n      Extends workflow processing capabilities for custom procurement and sourcing\n      processes.\n    image: https://api.ariba.com/flow-extension-icon.png\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/flow-extension\n\
  \    tags:\n      - Customization\n      - Extensions\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/ariba-apis\n      - type: Hub\n        url: https://api.sap.com/package/SAPAribaOpenAPIs/rest\n  - name: SAP Ariba Asynchronous Requests Management API\n    descriptio\n\n# --- truncated at 32 KB (49 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/apis.yml
tags:
- B2B
- Contract Management
- Procurement
- Sourcing
- Spend Analysis
- Supplier Management
- Supply Chain
url: https://www.ariba.com
use_cases:
- description: Run RFx events, auctions, and supplier evaluations to optimize procurement decisions.
  name: Strategic Sourcing
- description: Automate invoice submission, approval workflows, and payment reconciliation.
  name: Invoice Automation
- description: Monitor supplier risk exposure and manage risk assessment engagements.
  name: Supplier Risk Management
- description: Manage internal and external catalogs for guided buying experiences.
  name: Catalog Management
---
