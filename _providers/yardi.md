---
api_count: 8
api_specs:
- filename: swagger
  format: yaml
  label: Yardi Voyager API
  slug: ''
  spec_type: OpenAPI
  url: https://api.yardi.com/swagger
apis:
- description: Core property management platform API providing access to accounting, operations, and reporting functionality for real estate portfolios. Yardi Voyager uses SOAP-based web services defined via WSDL, w
  name: Yardi Voyager API
  slug: ''
- description: Web service interface that provides the ability to export commercial data from Yardi Voyager databases, including property, unit, lease, and rent roll information. Built on the OSCRE standard with Yar
  name: Yardi Voyager Commercial Data API
  slug: ''
- description: API for online rental applications, payments, and resident portal functionality for multifamily properties. RENTCafe APIv2 provides transaction-based pricing with an annual price cap, enabling vendors
  name: Yardi RENTCafe API
  slug: ''
- description: Maintenance and work order management API enabling integration with maintenance operations, service requests, and vendor management. Part of the Voyager Standard Interface Partnership Program, this AP
  name: Yardi Maintenance IQ API
  slug: ''
- description: API for investment and asset management functions including deal tracking, investor reporting, and portfolio analytics. Provides programmatic access to investment management data within the Yardi Voya
  name: Yardi Investment Manager API
  slug: ''
- description: SOAP-based API for Yardi's self-storage management platform, formerly known as CenterShift. The SWS2 API provides tokenized authentication and access to store management methods for creating custom ap
  name: Yardi Store Web Services API
  slug: ''
- description: 'API and webhook integration for Yardi Kube, the coworking and flexible workspace management platform. Enables connecting third-party applications with Yardi Kube for member management, billing, space '
  name: Yardi Kube API
  slug: ''
- description: Interface API for Yardi's Electronic Health Records platform designed for senior living communities. Supports secure data exchange with pharmacy networks, laboratory systems, and other healthcare part
  name: Yardi Senior Living EHR API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.yardi.com/platform/
- title: ''
  type: Developer Resources
  url: https://www.yardi.com/platform/api/
- title: ''
  type: Support
  url: https://www.yardi.com/support/
- title: ''
  type: Contact
  url: https://www.yardi.com/contact-us/
- title: ''
  type: Privacy Policy
  url: https://resources.yardi.com/legal/privacy-statement/
- title: ''
  type: Terms of Service
  url: https://www.yardi.com/about-us/legal/terms-of-use/
- title: ''
  type: Status
  url: https://status.yardi.com
- title: ''
  type: Website
  url: https://www.yardi.com
- title: ''
  type: Blog
  url: https://www.yardi.com/blog/
- title: ''
  type: Getting Started
  url: https://www.yardi.com/company/become-an-interface-partner/
- title: ''
  type: Sign Up
  url: https://www.yardi.com/company/become-an-interface-partner/
- title: ''
  type: Documentation
  url: https://www.yardi.com/services/interfaces/standard-interface-options/
- title: ''
  type: GitHub Organization
  url: https://github.com/YardiSystems
- title: ''
  type: Training
  url: https://www.yardi.com/company/training/
- title: ''
  type: Login
  url: https://www.yardi.com/company/technical-support/
created: '2025-01-01'
description: Yardi develops and supports industry-leading investment and property management software for all types and sizes of real estate companies. The platform includes solutions for residential, commercial, public housing, affordable housing, and military housing management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Yardi
skills: []
slug: yardi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: yardi\nname: Yardi\ndescription: Yardi develops and supports industry-leading investment and property management software for all types and sizes of real estate companies. The platform includes solutions for residential, commercial, public housing, affordable housing, and military housing management.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\napis:\n  - name: Yardi Voyager API\n    description: >-\n      Core property management platform API providing access to accounting,\n      operations, and reporting functionality for real estate portfolios. Yardi\n      Voyager uses SOAP-based web services defined via WSDL, with interfaces for\n      billing and payments, common data, service requests, vendor invoicing, job\n      cost, and commercial data export.\n    image:\
  \ https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardi.com/products/voyager/\n    baseURL: https://api.yardi.com\n    tags:\n      - Accounting\n      - Commercial\n      - Property Management\n      - Real Estate\n      - Residential\n    properties:\n      - type: Documentation\n        url: https://www.yardi.com/platform/api/\n      - type: OpenAPI\n        url: https://api.yardi.com/swagger\n      - type: Authentication\n        url: https://www.yardi.com/platform/api/authentication/\n      - type: Getting Started\n        url: https://www.yardi.com/company/become-an-interface-partner/\n      - type: Reference\n        url: https://www.yardi.com/services/interfaces/standard-interface-options/\n  - name: Yardi Voyager Commercial Data API\n    description: >-\n      Web service interface that provides the ability to export commercial data\n      from Yardi Voyager databases, including property, unit, lease, and rent roll\n      information.\
  \ Built on the OSCRE standard with Yardi-specific extensions, this\n      API expands existing services geared towards financial transactions and\n      facilities management.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardi.com/news/press-releases/yardi-adds-commercial-data-interface-to-voyager-standard-interface-partnership-program/\n    baseURL: https://api.yardi.com\n    tags:\n      - Commercial\n      - Data Export\n      - Leasing\n      - OSCRE\n    properties:\n      - type: Documentation\n        url: https://www.yardi.com/services/interfaces/standard-interface-options/\n      - type: Getting Started\n        url: https://www.yardi.com/company/become-an-interface-partner/\n  - name: Yardi RENTCafe API\n    description: >-\n      API for online rental applications, payments, and resident portal\n      functionality for multifamily properties. RENTCafe APIv2 provides\n      transaction-based pricing with an annual price\
  \ cap, enabling vendors to\n      integrate leasing, marketing, and resident services into their applications.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.rentcafe.com/\n    baseURL: https://api.rentcafe.com\n    tags:\n      - Applications\n      - Multifamily\n      - Payments\n      - Portal\n      - Residents\n    properties:\n      - type: Documentation\n        url: https://www.rentcafe.com/api/\n      - type: Terms of Service\n        url: https://resources.yardi.com/legal/rc-api-tou/\n      - type: Getting Started\n        url: https://www.yardi.com/company/become-an-interface-partner/\n  - name: Yardi Maintenance IQ API\n    description: >-\n      Maintenance and work order management API enabling integration with\n      maintenance operations, service requests, and vendor management. Part of the\n      Voyager Standard Interface Partnership Program, this API supports creating\n      and updating work orders between Yardi\
  \ and third-party systems.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardi.com/products/maintenance-iq/\n    baseURL: https://api.yardi.com/maintenance\n    tags:\n      - Facilities\n      - Maintenance\n      - Vendors\n      - Work Orders\n    properties:\n      - type: Documentation\n        url: https://www.yardi.com/platform/api/maintenance/\n      - type: Getting Started\n        url: https://www.yardi.com/company/become-an-interface-partner/\n  - name: Yardi Investment Manager API\n    description: >-\n      API for investment and asset management functions including deal tracking,\n      investor reporting, and portfolio analytics. Provides programmatic access to\n      investment management data within the Yardi Voyager platform.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardi.com/products/investment-manager/\n    baseURL: https://api.yardi.com/investment\n\
  \    tags:\n      - Analytics\n      - Asset Management\n      - Investment\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://www.yardi.com/platform/api/investment/\n      - type: Getting Started\n        url: https://www.yardi.com/company/become-an-interface-partner/\n  - name: Yardi Store Web Services API\n    description: >-\n      SOAP-based API for Yardi's self-storage management platform, formerly known\n      as CenterShift. The SWS2 API provides tokenized authentication and access to\n      store management methods for creating custom applications and websites that\n      interact with Yardi Store Enterprise and Store Advantage systems.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://centershiftdevx.com/\n    baseURL: https://api.yardi.com\n    tags:\n      - Reservations\n      - Self Storage\n      - SOAP\n      - Store Management\n    properties:\n      - type: Documentation\n        url:\
  \ https://centershiftdevx.com/2015/01/22/sws2-api-documentation/\n      - type: Reference\n        url: https://centershiftdevx.com/2017/01/23/end-points/\n      - type: Getting Started\n        url: https://centershiftdevx.com/2017/04/16/overview-using-yardi-store-web-services-sws/\n      - type: Support\n        url: https://centershiftdevx.com/2011/06/20/contacting-centershift/\n  - name: Yardi Kube API\n    description: >-\n      API and webhook integration for Yardi Kube, the coworking and flexible\n      workspace management platform. Enables connecting third-party applications\n      with Yardi Kube for member management, billing, space booking, access\n      control, and CRM integrations.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardikube.com/integrations-api/\n    baseURL: https://api.yardikube.com\n    tags:\n      - Booking\n      - Coworking\n      - Flexible Workspace\n      - Webhooks\n    properties:\n      -\
  \ type: Documentation\n        url: https://www.yardikube.com/integrations-api/\n  - name: Yardi Senior Living EHR API\n    description: >-\n      Interface API for Yardi's Electronic Health Records platform designed for\n      senior living communities. Supports secure data exchange with pharmacy\n      networks, laboratory systems, and other healthcare partners through\n      standardized interfaces including NCPDP 10.6 SCRIPT compliance.\n    image: https://www.yardi.com/wp-content/uploads/2023/01/yardi-logo.svg\n    humanURL: https://www.yardi.com/product/ehr/\n    baseURL: https://api.yardi.com\n    tags:\n      - EHR\n      - Healthcare\n      - Pharmacy\n      - Senior Living\n    properties:\n      - type: Documentation\n        url: https://www.yardi.com/product/ehr/\ncommon:\n  - type: Portal\n    url: https://www.yardi.com/platform/\n  - type: Developer Resources\n    url: https://www.yardi.com/platform/api/\n  - type: Support\n    url: https://www.yardi.com/support/\n  - type:\
  \ Contact\n    url: https://www.yardi.com/contact-us/\n  - type: Privacy Policy\n    url: https://resources.yardi.com/legal/privacy-statement/\n  - type: Terms of Service\n    url: https://www.yardi.com/about-us/legal/terms-of-use/\n  - type: Status\n    url: https://status.yardi.com\n  - type: Website\n    url: https://www.yardi.com\n  - type: Blog\n    url: https://www.yardi.com/blog/\n  - type: Getting Started\n    url: https://www.yardi.com/company/become-an-interface-partner/\n  - type: Sign Up\n    url: https://www.yardi.com/company/become-an-interface-partner/\n  - type: Documentation\n    url: https://www.yardi.com/services/interfaces/standard-interface-options/\n  - type: GitHub Organization\n    url: https://github.com/YardiSystems\n  - type: Training\n    url: https://www.yardi.com/company/training/\n  - type: Login\n    url: https://www.yardi.com/company/technical-support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Accounting\n  - Commercial\
  \ Real Estate\n  - Coworking\n  - Investment Management\n  - Multifamily\n  - Property Management\n  - Real Estate\n  - Residential\n  - Self Storage\n  - Senior Living\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/apis.yml
tags:
- Accounting
- Commercial Real Estate
- Coworking
- Investment Management
- Multifamily
- Property Management
- Real Estate
- Residential
- Self Storage
- Senior Living
url: https://raw.githubusercontent.com/api-evangelist/yardi/refs/heads/main/apis.yml
use_cases: []
---
