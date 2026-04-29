---
api_count: 10
apis:
- description: Server-side API for managing QlikView Server operations, documents, and sessions.
  name: QlikView Server API
  slug: ''
- description: SOAP-based API for QlikView management and administration tasks.
  name: QlikView Management API (QMS API)
  slug: ''
- description: Web-based API for QlikView AccessPoint portal functionality.
  name: QlikView AccessPoint API
  slug: ''
- description: API for integrating QlikView objects into web applications and portals.
  name: QlikView Workbench API
  slug: ''
- description: COM-based API for creating custom objects and extensions in QlikView.
  name: QlikView Plugin API
  slug: ''
- description: ActiveX/COM API for automating QlikView Desktop operations.
  name: QlikView OCX API (Automation API)
  slug: ''
- description: The Qlik data eXchange (QVX) SDK enables developers to build custom connectors for integrating external data sources into QlikView, using a high-performance file and stream format for data input.
  name: QlikView QVX SDK API
  slug: ''
- description: JavaScript API library for building websites containing QlikView content and for developing custom extension objects that extend QlikView visualization capabilities.
  name: QlikView JavaScript API
  slug: ''
- description: Authentication API providing Custom Ticket Exchange (CTE) for secure single sign-on access to QlikView Server, allowing third-party systems to request authentication tokens on behalf of users.
  name: QlikView Authentication API (Ticket API)
  slug: ''
- description: API interface for the QlikView Distribution Service, providing programmatic access to document distribution, task management, and scheduled reload operations including External Document Exchange (EDX)
  name: QlikView Distribution Service API (IQDS)
  slug: ''
common:
- title: ''
  type: Portal
  url: https://help.qlik.com/en-US/qlikview-developer/
- title: ''
  type: APIReference
  url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/Home.htm
- title: ''
  type: Support
  url: https://community.qlik.com/
- title: ''
  type: Training
  url: https://www.qlik.com/us/services/training
- title: ''
  type: Pricing
  url: https://www.qlik.com/us/pricing
- title: ''
  type: ReleaseNotes
  url: https://community.qlik.com/t5/Release-Notes/tkb-p/ReleaseNotes
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: DeveloperPortal
  url: https://qlik.dev/
created: '2024-01-01'
description: QlikView is a business intelligence and data visualization platform that enables users to create guided analytics applications and dashboards for data discovery.
features:
- description: Explore data relationships dynamically with QlikView's patented associative engine.
  name: Associative Data Model
- description: Fast analytics with in-memory data compression and calculation.
  name: In-Memory Processing
- description: Build guided analytics applications with interactive dashboards and drill-down capabilities.
  name: Guided Analytics
- description: Rich set of chart types and visualization objects for data exploration and presentation.
  name: Data Visualization
- description: Extend QlikView with custom objects, connectors, and plugins using the Plugin and QVX APIs.
  name: Custom Extensions
- description: Web-based access to QlikView documents through the AJAX Zero Footprint Client.
  name: AJAX Client
- description: Schedule and distribute QlikView documents and reports via the Distribution Service.
  name: Document Distribution
- description: Integrate single sign-on with custom authentication systems using the Ticket API.
  name: Custom Ticket Authentication
image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png
integrations:
- description: Migrate and extend QlikView applications to the modern Qlik Sense platform.
  name: Qlik Sense
- description: Connect to SQL Server, Oracle, MySQL, PostgreSQL and other relational databases.
  name: SQL Databases
- description: Extract and visualize SAP data with native SAP connectors.
  name: SAP
- description: Integrate with Salesforce CRM data for sales analytics and reporting.
  name: Salesforce
- description: Authenticate users and manage access through Active Directory integration.
  name: Active Directory
layout: provider
modified: '2026-04-18'
name: QlikView
skills: []
slug: qlikview
solutions: []
source_filename: apis.yml
source_yaml: "aid: qlikview\nname: QlikView\ndescription: QlikView is a business intelligence and data visualization platform that enables users to create guided analytics applications and dashboards for data discovery.\ntype: Index\nimage: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\nurl: https://raw.githubusercontent.com/api-evangelist/qlikview/refs/heads/main/apis.yml\ntags:\n  - Analytics\n  - Business Intelligence\n  - Dashboards\n  - Data Discovery\n  - Data Visualization\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: QlikView Server API\n    description: >-\n      Server-side API for managing QlikView Server operations, documents, and sessions.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview/\n    baseURL: http://qlikview-server:4799/QMS/Service\n    tags:\n      - Administration\n      - Documents\n      - Server Management\n\
  \      - Sessions\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/Server/Content/QV_Server/sv-reference-QMS-API.htm\n      - type: OpenAPI\n        url: https://help.qlik.com/en-US/qlikview-developer/APIs/\n      - type: GettingStartedGuide\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView Management API (QMS API)\n    description: >-\n      SOAP-based API for QlikView management and administration tasks.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview/\n    baseURL: http://qlikview-server:4799/QMS/Service\n    tags:\n      - Administration\n      - Configuration\n      - Management\n      - SOAP\n    properties:\n      - type:\
  \ Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/Server/Content/QV_Server/sv-qms-api-interface.htm\n      - type: WSDL\n        url: http://qlikview-server:4799/QMS/Service?wsdl\n      - type: SDK\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Content/QV_QlikViewSDK/QV_SDK_Introduction.htm\n      - type: APIReference\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/Home.htm\n      - type: InterfaceReference\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/PIX.Services.V12.IQMS.htm\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView AccessPoint API\n    description: >-\n      Web-based API for QlikView AccessPoint portal functionality.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n   \
  \ humanURL: https://help.qlik.com/en-US/qlikview/\n    baseURL: http://qlikview-server/QvAJAXZfc/\n    tags:\n      - AJAX\n      - Frontend\n      - User Access\n      - Web Portal\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/AJAX/Content/QV_AJAX/ajax-api-introduction.htm\n      - type: JavaScript API\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/AJAX/Content/QV_AJAX/qva-getdocumentlist.htm\n      - type: JavaScriptLibrary\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/apis/js%20API/\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView Workbench API\n    description: >-\n      API for integrating QlikView objects into web applications and portals.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview/\n\
  \    baseURL: http://qlikview-server/QvAJAXZfc/\n    tags:\n      - .NET\n      - Embedding\n      - Web Integration\n      - Workbench\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/Workbench/Content/QV_Workbench/workbench-introduction.htm\n      - type: ASP.NET Controls\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/Workbench/Content/QV_Workbench/server-side-controls.htm\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView Plugin API\n    description: >-\n      COM-based API for creating custom objects and extensions in QlikView.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview/\n    baseURL: local\n    tags:\n      - COM\n      - Custom Objects\n      - Extensions\n      - Plugins\n    properties:\n \
  \     - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/PluginAPI/Content/QV_PluginAPI/plugin-api-introduction.htm\n      - type: SDK\n        url: https://community.qlik.com/t5/Developers/ct-p/qlik-developers\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView OCX API (Automation API)\n    description: >-\n      ActiveX/COM API for automating QlikView Desktop operations.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview/\n    baseURL: local\n    tags:\n      - ActiveX\n      - Automation\n      - COM\n      - Desktop\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/OCX/Content/QV_OCX/ocx-introduction.htm\n      - type: Reference Guide\n        url: https://help.qlik.com/en-US/qlikview-developer/November2023/Subsystems/OCX/Content/QV_OCX/ocx-api-reference.htm\n\
  \    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView QVX SDK API\n    description: >-\n      The Qlik data eXchange (QVX) SDK enables developers to build custom connectors\n      for integrating external data sources into QlikView, using a high-performance\n      file and stream format for data input.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n    baseURL: local\n    tags:\n      - Custom Connectors\n      - Data Integration\n      - Data Sources\n      - QVX\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QVXSDKAPI/Content/QV_QVXSDKAPI/Getting-started.htm\n      - type: APIReference\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QVXSDKAPI/Content/QV_QVXSDKAPI/QlikView%20QVX%20File%20Format/command-pipe.htm\n\
  \    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView JavaScript API\n    description: >-\n      JavaScript API library for building websites containing QlikView content and\n      for developing custom extension objects that extend QlikView visualization\n      capabilities.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n    baseURL: http://qlikview-server/QvAJAXZfc/\n    tags:\n      - AJAX\n      - Extensions\n      - JavaScript\n      - Visualization\n      - Web Development\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/apis/js%20API/\n      - type: GettingStartedGuide\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n   \
  \ contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView Authentication API (Ticket API)\n    description: >-\n      Authentication API providing Custom Ticket Exchange (CTE) for secure single\n      sign-on access to QlikView Server, allowing third-party systems to request\n      authentication tokens on behalf of users.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n    baseURL: http://qlikview-server/QvAJAXZfc/\n    tags:\n      - Authentication\n      - Custom Ticket Exchange\n      - Security\n      - Single Sign-On\n      - Tickets\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Content/QV_HelpSites/APIsAndSDKs.htm\n      - type: Support\n        url: https://community.qlik.com/t5/Official-Support-Articles/Customized-Authentication-in-QlikView/ta-p/1710763\n\
  \    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\n  - name: QlikView Distribution Service API (IQDS)\n    description: >-\n      API interface for the QlikView Distribution Service, providing programmatic\n      access to document distribution, task management, and scheduled reload\n      operations including External Document Exchange (EDX) triggers.\n    image: https://www.qlik.com/us/-/media/images/qlik/global/qlik-logo-2x.png\n    humanURL: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/PIX.Services.IQDS.htm\n    baseURL: http://qlikview-server:4799/QMS/Service\n    tags:\n      - Distribution\n      - Document Reload\n      - EDX\n      - Scheduling\n      - Task Management\n    properties:\n      - type: Documentation\n        url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/PIX.Services.IQDS.htm\n      - type: APIReference\n \
  \       url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/Home.htm\n    contact:\n      - FN: Qlik Support\n        email: support@qlik.com\n        url: https://community.qlik.com/\ncommon:\n  - type: Portal\n    url: https://help.qlik.com/en-US/qlikview-developer/\n  - type: APIReference\n    url: https://help.qlik.com/en-US/qlikview-developer/September2025/Subsystems/QMSAPIref/Content/Home.htm\n  - type: Support\n    url: https://community.qlik.com/\n  - type: Training\n    url: https://www.qlik.com/us/services/training\n  - type: Pricing\n    url: https://www.qlik.com/us/pricing\n  - type: ReleaseNotes\n    url: https://community.qlik.com/t5/Release-Notes/tkb-p/ReleaseNotes\n  - type: GitHubOrganization\n    url: https://github.com/qlik-oss\n  - type: DeveloperPortal\n    url: https://qlik.dev/\n  - type: Features\n    data:\n      - name: Associative Data Model\n        description: Explore data relationships dynamically with QlikView's\
  \ patented associative engine.\n      - name: In-Memory Processing\n        description: Fast analytics with in-memory data compression and calculation.\n      - name: Guided Analytics\n        description: Build guided analytics applications with interactive dashboards and drill-down capabilities.\n      - name: Data Visualization\n        description: Rich set of chart types and visualization objects for data exploration and presentation.\n      - name: Custom Extensions\n        description: Extend QlikView with custom objects, connectors, and plugins using the Plugin and QVX APIs.\n      - name: AJAX Client\n        description: Web-based access to QlikView documents through the AJAX Zero Footprint Client.\n      - name: Document Distribution\n        description: Schedule and distribute QlikView documents and reports via the Distribution Service.\n      - name: Custom Ticket Authentication\n        description: Integrate single sign-on with custom authentication systems using the\
  \ Ticket API.\n  - type: UseCases\n    data:\n      - name: Business Intelligence Dashboards\n        description: Build interactive BI dashboards for sales, finance, and operations analytics.\n      - name: Embedded Analytics\n        description: Embed QlikView analytics objects into existing web applications and portals.\n      - name: Automated Reporting\n        description: Schedule and distribute data-driven reports to stakeholders across the organization.\n      - name: Data Discovery\n        description: Enable self-service data discovery and exploration for business users.\n      - name: Custom Data Connectors\n        description: Build custom connectors to integrate QlikView with proprietary data sources.\n  - type: Integrations\n    data:\n      - name: Qlik Sense\n        description: Migrate and extend QlikView applications to the modern Qlik Sense platform.\n      - name: SQL Databases\n        description: Connect to SQL Server, Oracle, MySQL, PostgreSQL and other relational\
  \ databases.\n      - name: SAP\n        description: Extract and visualize SAP data with native SAP connectors.\n      - name: Salesforce\n        description: Integrate with Salesforce CRM data for sales analytics and reporting.\n      - name: Active Directory\n        description: Authenticate users and manage access through Active Directory integration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlikview/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Discovery
- Data Visualization
url: https://raw.githubusercontent.com/api-evangelist/qlikview/refs/heads/main/apis.yml
use_cases:
- description: Build interactive BI dashboards for sales, finance, and operations analytics.
  name: Business Intelligence Dashboards
- description: Embed QlikView analytics objects into existing web applications and portals.
  name: Embedded Analytics
- description: Schedule and distribute data-driven reports to stakeholders across the organization.
  name: Automated Reporting
- description: Enable self-service data discovery and exploration for business users.
  name: Data Discovery
- description: Build custom connectors to integrate QlikView with proprietary data sources.
  name: Custom Data Connectors
---
