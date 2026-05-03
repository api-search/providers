---
api_count: 7
api_specs:
- filename: sybase-ase-rest-api-openapi.yml
  format: yaml
  label: Sybase ASE REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/openapi/sybase-ase-rest-api-openapi.yml
- filename: openapi.json
  format: json
  label: Sybase IQ REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sybase.example.com/iq/v1/openapi.json
apis:
- description: REST API for Sybase Adaptive Server Enterprise administration and monitoring. Provides programmatic access to server configuration, database management, performance monitoring, user administration, an
  name: Sybase ASE REST API
  slug: ''
- description: REST API for SAP IQ (formerly Sybase IQ) analytics database.
  name: Sybase IQ REST API
  slug: ''
- description: APIs for Sybase mobile application development and management.
  name: SAP Mobile Platform API
  slug: ''
- description: SAP SQL Anywhere includes a built-in HTTP web server that exposes database objects as OData and REST web services. Developers can create SERVICE objects that transform SQL query results into XML, HTML
  name: SAP SQL Anywhere HTTP Web Services
  slug: ''
- description: The SDK for SAP Adaptive Server Enterprise is a set of libraries and utilities for developing client applications. It includes SAP Open Client for C-language applications, Embedded SQL precompilers fo
  name: SDK for SAP ASE
  slug: ''
- description: SAP Replication Server provides real-time data replication between SAP ASE databases and heterogeneous data sources. It uses Replication Command Language (RCL) to manage replication definitions, publi
  name: SAP Replication Server
  slug: ''
- description: SAP ASE Cockpit is a web-based administration and management console for SAP Adaptive Server Enterprise. It provides monitoring, configuration, and management capabilities for ASE servers through a br
  name: SAP ASE Cockpit
  slug: ''
capabilities:
- description: Unified database administration capability for SAP Adaptive Server Enterprise. Enables DBAs and platform teams to monitor server health, manage databases, track performance, administer users, and exec
  name: Sybase ASE Database Administration
  slug: database-administration
common:
- title: ''
  type: Portal
  url: https://support.sap.com/sybase
- title: ''
  type: Support
  url: https://support.sap.com/en/product/database.html
- title: ''
  type: Community
  url: https://pages.community.sap.com/topics/applications-on-ase
- title: ''
  type: Downloads
  url: https://support.sap.com/swdc
- title: ''
  type: Blog
  url: https://blogs.sap.com/tags/products-sybase/
- title: ''
  type: Website
  url: https://www.sap.com/products/data-cloud/sybase-ase.html
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/SAP_ASE
- title: ''
  type: Getting Started
  url: https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html
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
  type: Change Log
  url: https://help.sap.com/docs/SAP_ASE/791c41982ee345a19c4ec4b774222c4f/5db753f3a9c24ddcabc2581a98b99585.html
- title: ''
  type: Login
  url: https://accounts.sap.com
- title: ''
  type: Sign Up
  url: https://www.sap.com/products/technology-platform/sybase-ase/trial.html
- title: ''
  type: GitHub Organization
  url: https://github.com/sqlanywhere
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/sybase
- title: ''
  type: SDKs
  url: https://help.sap.com/docs/SAP_ASE_SDK
- title: ''
  type: Pricing
  url: https://www.sap.com/products/data-cloud/sybase-ase.html
created: '2024'
description: A collection of APIs and resources for Sybase database systems.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg
integrations: []
jsonld:
- class_count: 18
  name: Sybase Context
  property_count: 6
  slug: sybase-context
layout: provider
modified: '2026-05-03'
name: Sybase
rules:
- name: Sybase API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 1
    info: 0
    warn: 6
  slug: sybase-rules
skills: []
slug: sybase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Sybase\ndescription: >-\n  A collection of APIs and resources for Sybase database systems.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\ntags:\n  - Database\n  - Enterprise\n  - SAP\n  - SQL\ncreated: '2024'\nmodified: '2026-05-03'\nurl: https://www.sap.com/products/data-cloud/sybase-ase.html\napis:\n  - name: Sybase ASE REST API\n    description: >-\n      REST API for Sybase Adaptive Server Enterprise administration and monitoring.\n      Provides programmatic access to server configuration, database management,\n      performance monitoring, user administration, and backup operations.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_ASE\n    baseURL: https://{server}:{port}/ase/v1\n    tags:\n      - Administration\n      - Backup\n      - Database Management\n      - Monitoring\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ASE\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/openapi/sybase-ase-rest-api-openapi.yml\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_ASE/authentication\n      - type: Change Log\n        url: https://help.sap.com/docs/SAP_ASE/791c41982ee345a19c4ec4b774222c4f/5db753f3a9c24ddcabc2581a98b99585.html\n  - name: Sybase IQ REST API\n    description: >-\n      REST API for SAP IQ (formerly Sybase IQ) analytics database.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_IQ\n    baseURL: https://api.sybase.example.com/iq/v1\n    tags:\n      - Analytics\n      - Big Data\n      - Data Warehouse\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_IQ/REST_API\n      - type: OpenAPI\n        url: https://api.sybase.example.com/iq/v1/openapi.json\n  - name: SAP Mobile Platform API\n    description:\
  \ >-\n      APIs for Sybase mobile application development and management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_MOBILE_PLATFORM\n    baseURL: https://api.sybase.example.com/mobile/v1\n    tags:\n      - Application Development\n      - Mobile\n      - Synchronization\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_MOBILE_PLATFORM/API\n      - type: SDK\n        url: https://help.sap.com/docs/SAP_MOBILE_PLATFORM/SDK\n  - name: SAP SQL Anywhere HTTP Web Services\n    description: >-\n      SAP SQL Anywhere includes a built-in HTTP web server that exposes database\n      objects as OData and REST web services. Developers can create SERVICE objects\n      that transform SQL query results into XML, HTML, and JSON formats, and\n      database tables and views can be automatically exposed via an OData producer.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_SQL_Anywhere\n    baseURL: https://{server}:{port}\n    tags:\n      - Database\n      - Embedded Database\n      - OData\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_SQL_Anywhere\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_SQL_Anywhere/98ad9ec940e2465695685d98e308dff5/8e8c9049a1fe448a820c5f5bc72119e7.html\n      - type: Getting Started\n        url: https://dcx.sap.com/\n  - name: SDK for SAP ASE\n    description: >-\n      The SDK for SAP Adaptive Server Enterprise is a set of libraries and\n      utilities for developing client applications. It includes SAP Open Client\n      for C-language applications, Embedded SQL precompilers for C and COBOL,\n      the ASE ODBC driver, ASE ADO.NET Data Provider, and jConnect for JDBC.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_ASE_SDK\n\
  \    baseURL: https://{server}:{port}\n    tags:\n      - Client Libraries\n      - Database Connectivity\n      - JDBC\n      - ODBC\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ASE_SDK\n      - type: Reference\n        url: https://help.sap.com/docs/SAP_ASE_SDK/882ef48c7e9c4d6e845d98f34378db40/b21b7c31bbf91014ae38f7f5cc782b0b.html\n      - type: Getting Started\n        url: https://help.sap.com/docs/SAP_ASE_SDK/e12c539de04b44a0bb17a545a148361c/0d968d9bcca6462f9414cf6010088af9.html\n  - name: SAP Replication Server\n    description: >-\n      SAP Replication Server provides real-time data replication between SAP ASE\n      databases and heterogeneous data sources. It uses Replication Command\n      Language (RCL) to manage replication definitions, publications, and\n      subscriptions for table and stored procedure replication.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL: https://help.sap.com/docs/SAP_REPLICATION_SERVER\n\
  \    baseURL: https://{server}:{port}\n    tags:\n      - Data Synchronization\n      - High Availability\n      - Replication\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_REPLICATION_SERVER\n      - type: Reference\n        url: https://help.sap.com/doc/efc57020a2914d40af14c48e08bfd01f/16.0.4.3/en-US/Replication_Server_Reference_Manual_en.pdf\n      - type: Getting Started\n        url: https://help.sap.com/doc/1699d891ffc746babeaf700da051f89e/16.0.4.1/en-US/SAP_RS_Quick_Start_ASE_en.pdf\n  - name: SAP ASE Cockpit\n    description: >-\n      SAP ASE Cockpit is a web-based administration and management console for\n      SAP Adaptive Server Enterprise. It provides monitoring, configuration, and\n      management capabilities for ASE servers through a browser-based interface,\n      replacing the earlier Adobe Flash-based console starting with ASE 16.0 SP04.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo.svg\n    humanURL:\
  \ https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html\n    baseURL: https://{server}:{port}\n    tags:\n      - Administration\n      - Management Console\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html\n      - type: Getting Started\n        url: https://blogs.sap.com/2018/02/18/first-steps-with-sap-ase-cockpit/\ncommon:\n  - type: Portal\n    url: https://support.sap.com/sybase\n  - type: Support\n    url: https://support.sap.com/en/product/database.html\n  - type: Community\n    url: https://pages.community.sap.com/topics/applications-on-ase\n  - type: Downloads\n    url: https://support.sap.com/swdc\n  - type: Blog\n    url: https://blogs.sap.com/tags/products-sybase/\n  - type: Website\n    url: https://www.sap.com/products/data-cloud/sybase-ase.html\n  - type: Documentation\n    url: https://help.sap.com/docs/SAP_ASE\n\
  \  - type: Getting Started\n    url: https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html\n  - type: Terms of Service\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Status\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: Change Log\n    url: https://help.sap.com/docs/SAP_ASE/791c41982ee345a19c4ec4b774222c4f/5db753f3a9c24ddcabc2581a98b99585.html\n  - type: Login\n    url: https://accounts.sap.com\n  - type: Sign Up\n    url: https://www.sap.com/products/technology-platform/sybase-ase/trial.html\n  - type: GitHub Organization\n    url: https://github.com/sqlanywhere\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/sybase\n  - type: SDKs\n    url: https://help.sap.com/docs/SAP_ASE_SDK\n  - type: Pricing\n    url: https://www.sap.com/products/data-cloud/sybase-ase.html\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/apis.yml
tags:
- Database
- Enterprise
- SAP
- SQL
url: https://www.sap.com/products/data-cloud/sybase-ase.html
use_cases: []
---
