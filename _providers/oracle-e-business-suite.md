---
api_count: 8
apis:
- description: 'RESTful web services for Oracle E-Business Suite modules exposed through the Integrated SOA Gateway (ISG). PL/SQL APIs, Java Bean Services, Application Module Services, and other interface types from '
  name: Oracle EBS Integrated SOA Gateway REST API
  slug: ''
- description: SOAP-based web services for Oracle E-Business Suite exposed through the Integrated SOA Gateway. Supports synchronous and asynchronous interaction patterns for PL/SQL APIs, Concurrent Programs, and Bus
  name: Oracle EBS Integrated SOA Gateway SOAP Web Services
  slug: ''
- description: APIs for financial management including General Ledger, Accounts Payable, Accounts Receivable, Fixed Assets, and Cash Management. These PL/SQL APIs can be deployed as REST or SOAP services through the
  name: Oracle EBS Financial Services API
  slug: ''
- description: 'APIs for inventory management, purchasing, order management, and logistics within Oracle E-Business Suite. Provides programmatic access to supply chain operations through PL/SQL interfaces deployable '
  name: Oracle EBS Supply Chain Management API
  slug: ''
- description: APIs for human resources management, payroll processing, and workforce administration. Oracle HRMS provides PL/SQL packaged procedures and functions that serve as an open interface for managing employ
  name: Oracle EBS Human Resources API
  slug: ''
- description: APIs for discrete and process manufacturing operations including Bills of Material, Work in Process, and Work Orders. Provides programmatic access to manufacturing execution and planning functions wit
  name: Oracle EBS Manufacturing API
  slug: ''
- description: Oracle e-Commerce Gateway provides EDI transaction support enabling Oracle E-Business Suite to exchange traditional Electronic Data Interchange documents with trading partners. Supports ASC X12 and ED
  name: Oracle EBS e-Commerce Gateway API
  slug: ''
- description: The PL/SQL API framework provides the core programmatic interface to Oracle E-Business Suite database objects. These stored procedures and functions enable data manipulation across all EBS modules and
  name: Oracle EBS PL/SQL API Framework
  slug: ''
capabilities:
- description: End-to-end financial operations combining General Ledger, AP/AR, procurement, and cash management. Used by finance teams and controllers for the procure-to-pay and order-to-cash cycles.
  name: Oracle EBS Financial Operations
  slug: financial-operations
- description: Integration capabilities combining ISG REST API for service management and e-Commerce Gateway for EDI document exchange with trading partners. Used by integration architects and B2B teams.
  name: Oracle EBS Integration and EDI
  slug: integration-and-edi
- description: Manufacturing execution combining BOMs, routings, discrete jobs, WIP operations, and inventory management. Used by production managers and shop floor supervisors for manufacturing lifecycle.
  name: Oracle EBS Manufacturing Operations
  slug: manufacturing-operations
- description: Human capital management combining HR, payroll, benefits, and organizational management. Used by HR administrators and payroll managers for employee lifecycle operations.
  name: Oracle EBS Workforce Management
  slug: workforce-management
common:
- title: ''
  type: Authentication
  url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm
- title: ''
  type: Portal
  url: https://developer.oracle.com/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/cd/E26401_01/index.htm
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm
- title: ''
  type: APIReference
  url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Blog
  url: https://blogs.oracle.com/ebstech/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/ebs/
- title: ''
  type: ChangeLog
  url: https://docs.oracle.com/cd/E26401_01/index.htm
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: StatusPage
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: SignUp
  url: https://signup.cloud.oracle.com/
- title: ''
  type: Pricing
  url: https://www.oracle.com/applications/ebusiness/
- title: ''
  type: GitHubOrganization
  url: https://github.com/oracle
- title: ''
  type: SDK
  url: https://github.com/oracle/oci-java-sdk
- title: ''
  type: SDK
  url: https://github.com/oracle/oci-python-sdk
- title: ''
  type: SDK
  url: https://github.com/oracle/oci-go-sdk
- title: ''
  type: SDK
  url: https://github.com/oracle/oci-dotnet-sdk
- title: ''
  type: CLI
  url: https://github.com/oracle/oci-cli
created: '2024-01-01'
description: A collection of APIs for Oracle E-Business Suite (EBS), Oracle's comprehensive suite of integrated, global business applications that supports today's evolving business models across financials, human capital management, supply chain, and manufacturing.
features:
- Financial management (GL, AP, AR, FA, Cash Management)
- Supply chain management (Purchasing, Inventory, Order Management)
- Human capital management (HR, Payroll, Benefits)
- Manufacturing (Discrete, Process, WIP, BOM)
- EDI transaction processing via e-Commerce Gateway
- RESTful API access through Integrated SOA Gateway
- PL/SQL API framework for programmatic data access
- Multi-org and multi-currency support
image: /assets/icons/oracle-e-business-suite.png
integrations:
- Oracle SOA Suite for service orchestration
- Oracle Integration Cloud for hybrid integration
- EDI translators for ASC X12 and EDIFACT standards
- Oracle BI Publisher for reporting
- Oracle Identity Management for SSO
- Third-party middleware via REST and SOAP APIs
jsonld:
- class_count: 0
  name: context Context
  property_count: 12
  slug: context
- class_count: 0
  name: Ecommerce Gateway Context
  property_count: 0
  slug: ecommerce-gateway-context
- class_count: 0
  name: Financial Services Context
  property_count: 0
  slug: financial-services-context
- class_count: 0
  name: Human Resources Context
  property_count: 0
  slug: human-resources-context
- class_count: 0
  name: Isg Rest Context
  property_count: 0
  slug: isg-rest-context
- class_count: 0
  name: Manufacturing Context
  property_count: 0
  slug: manufacturing-context
- class_count: 0
  name: Supply Chain Context
  property_count: 0
  slug: supply-chain-context
layout: provider
modified: '2026-04-18'
name: Oracle E-Business Suite
rules:
- name: Oracle E-Business Suite API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: oracle-e-business-suite-spectral-rules
skills: []
slug: oracle-e-business-suite
solutions: []
source_yaml: "aid: oracle-e-business-suite\nname: Oracle E-Business Suite\ndescription: >-\n  A collection of APIs for Oracle E-Business Suite (EBS), Oracle's comprehensive\n  suite of integrated, global business applications that supports today's evolving\n  business models across financials, human capital management, supply chain, and\n  manufacturing.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Business Applications\n  - E-Business Suite\n  - Enterprise\n  - ERP\n  - Oracle\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml\napis:\n  - name: Oracle EBS Integrated SOA Gateway REST API\n    description: RESTful web services for Oracle E-Business Suite modules exposed through the Integrated SOA Gateway (ISG). PL/SQL APIs, Java Bean Services, Application\
  \ Module Services, and other interface types from the Integration Repository can be deployed as lightweight REST services.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/rest/\n    humanURL: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/T511473T516479.htm\n    tags:\n      - Enterprise\n      - Integration\n      - Rest Services\n      - Soa Gateway\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n      - type: GettingStarted\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e69284/T660136T660140.htm\n      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm\n      - type: OpenAPI\n        url: openapi/isg-rest-api.yml\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n\
  \  - name: Oracle EBS Integrated SOA Gateway SOAP Web Services\n    description: SOAP-based web services for Oracle E-Business Suite exposed through the Integrated SOA Gateway. Supports synchronous and asynchronous interaction patterns for PL/SQL APIs, Concurrent Programs, and Business Service Objects deployed to Oracle SOA Suite.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/SOAProvider/\n    humanURL: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n    tags:\n      - Integration\n      - Soa Gateway\n      - Soap Services\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20923/T291171T291173.htm\n      - type: GettingStarted\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm\n      - type:\
  \ JSONSchema\n        url: json-schema/customer.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS Financial Services API\n    description: APIs for financial management including General Ledger, Accounts Payable, Accounts Receivable, Fixed Assets, and Cash Management. These PL/SQL APIs can be deployed as REST or SOAP services through the Integrated SOA Gateway.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/rest/\n    humanURL: https://docs.oracle.com/cd/E26401_01/index.htm\n    tags:\n      - Accounting\n      - Accounts Payable\n      - Financials\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n\
  \      - type: OpenAPI\n        url: openapi/financial-services-api.yml\n      - type: JSONSchema\n        url: json-schema/invoice.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS Supply Chain Management API\n    description: APIs for inventory management, purchasing, order management, and logistics within Oracle E-Business Suite. Provides programmatic access to supply chain operations through PL/SQL interfaces deployable as REST services.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/rest/\n    humanURL: https://docs.oracle.com/cd/E26401_01/index.htm\n    tags:\n      - Inventory\n      - Order Management\n      - Purchasing\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n\
  \      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n      - type: OpenAPI\n        url: openapi/supply-chain-api.yml\n      - type: JSONSchema\n        url: json-schema/purchase-order.json\n      - type: JSONSchema\n        url: json-schema/supplier.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS Human Resources API\n    description: APIs for human resources management, payroll processing, and workforce administration. Oracle HRMS provides PL/SQL packaged procedures and functions that serve as an open interface for managing employee data, compensation, and benefits.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/rest/\n    humanURL: https://docs.oracle.com/cd/E26401_01/nav/hcm.htm\n    tags:\n      - Human Capital\n\
  \      - Human Resources\n      - Payroll\n      - Workforce Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/nav/hcm.htm\n      - type: OpenAPI\n        url: openapi/human-resources-api.yml\n      - type: JSONSchema\n        url: json-schema/employee.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS Manufacturing API\n    description: APIs for discrete and process manufacturing operations including Bills of Material, Work in Process, and Work Orders. Provides programmatic access to manufacturing execution and planning functions within Oracle E-Business Suite.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    baseURL: https://{instance}.oracle.com/webservices/rest/\n\
  \    humanURL: https://docs.oracle.com/cd/E26401_01/index.htm\n    tags:\n      - Bills of Material\n      - Manufacturing\n      - Production\n      - Work Orders\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n      - type: APIReference\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n      - type: OpenAPI\n        url: openapi/manufacturing-api.yml\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS e-Commerce Gateway API\n    description: Oracle e-Commerce Gateway provides EDI transaction support enabling Oracle E-Business Suite to exchange traditional Electronic Data Interchange documents with trading partners. Supports ASC X12 and EDIFACT standards through flat ASCII file integration with third-party EDI translators.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n\
  \    baseURL: https://{instance}.oracle.com/\n    humanURL: https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm\n    tags:\n      - Data Interchange\n      - E-Commerce\n      - Edi\n      - Trading Partners\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e20931/T168264T168267.htm\n      - type: OpenAPI\n        url: openapi/ecommerce-gateway-api.yml\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle EBS PL/SQL API Framework\n    description: The PL/SQL API framework provides the core programmatic interface to Oracle E-Business Suite database objects. These stored procedures and functions enable data manipulation across all EBS modules and can be published as REST services through the Integration Repository.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n\
  \    baseURL: https://{instance}.oracle.com/\n    humanURL: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n    tags:\n      - Database Api\n      - Development Framework\n      - Pl/Sql\n      - Stored Procedures\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n      - type: GettingStarted\n        url: https://docs.oracle.com/cd/E26401_01/doc.122/e69284/T660136T660140.htm\n      - type: JSONSchema\n        url: json-schema/purchase-order.json\n      - type: JSONSchema\n        url: json-schema/invoice.json\n      - type: JSONSchema\n        url: json-schema/employee.json\n      - type: JSONSchema\n        url: json-schema/customer.json\n      - type: JSONSchema\n        url: json-schema/supplier.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\ncommon:\n  - type: Authentication\n\
  \    url: https://docs.oracle.com/cd/E26401_01/doc.122/e20927/toc.htm\n  - type: Portal\n    url: https://developer.oracle.com/\n  - type: Documentation\n    url: https://docs.oracle.com/cd/E26401_01/index.htm\n  - type: GettingStarted\n    url: https://docs.oracle.com/cd/E26401_01/doc.122/e20925/T511175T513043.htm\n  - type: APIReference\n    url: https://docs.oracle.com/cd/E26401_01/doc.122/e22961/toc.htm\n  - type: Support\n    url: https://support.oracle.com\n  - type: Blog\n    url: https://blogs.oracle.com/ebstech/\n  - type: Blog\n    url: https://blogs.oracle.com/ebs/\n  - type: ChangeLog\n    url: https://docs.oracle.com/cd/E26401_01/index.htm\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms/\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: StatusPage\n    url: https://ocistatus.oraclecloud.com/\n  - type: SignUp\n    url: https://signup.cloud.oracle.com/\n  - type: Pricing\n    url: https://www.oracle.com/applications/ebusiness/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/oracle\n  - type: SDK\n    url: https://github.com/oracle/oci-java-sdk\n    name: Oracle OCI Java SDK\n  - type: SDK\n    url: https://github.com/oracle/oci-python-sdk\n    name: Oracle OCI Python SDK\n  - type: SDK\n    url: https://github.com/oracle/oci-go-sdk\n    name: Oracle OCI Go SDK\n  - type: SDK\n    url: https://github.com/oracle/oci-dotnet-sdk\n    name: Oracle OCI .NET SDK\n  - type: CLI\n    url: https://github.com/oracle/oci-cli\n    name: Oracle OCI CLI\n  - type: Features\n    data:\n      - Financial management (GL, AP, AR, FA, Cash Management)\n      - Supply chain management (Purchasing, Inventory, Order Management)\n      - Human capital management (HR, Payroll, Benefits)\n      - Manufacturing (Discrete, Process, WIP, BOM)\n      - EDI transaction processing via e-Commerce Gateway\n      - RESTful API access through Integrated SOA Gateway\n      - PL/SQL API framework for programmatic data access\n      -\
  \ Multi-org and multi-currency support\n  - type: UseCases\n    data:\n      - Automate financial close and journal posting\n      - Integrate procurement and purchase order workflows\n      - Manage employee lifecycle and payroll processing\n      - Track manufacturing work orders and material usage\n      - Exchange EDI documents with trading partners\n      - Build custom integrations via REST and SOAP services\n      - Synchronize EBS data with external systems\n  - type: Integrations\n    data:\n      - Oracle SOA Suite for service orchestration\n      - Oracle Integration Cloud for hybrid integration\n      - EDI translators for ASC X12 and EDIFACT standards\n      - Oracle BI Publisher for reporting\n      - Oracle Identity Management for SSO\n      - Third-party middleware via REST and SOAP APIs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml
tags:
- Business Applications
- E-Business Suite
- Enterprise
- ERP
- Oracle
url: https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/apis.yml
use_cases:
- Automate financial close and journal posting
- Integrate procurement and purchase order workflows
- Manage employee lifecycle and payroll processing
- Track manufacturing work orders and material usage
- Exchange EDI documents with trading partners
- Build custom integrations via REST and SOAP services
- Synchronize EBS data with external systems
---
