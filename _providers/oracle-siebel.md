---
api_count: 7
api_specs:
- filename: swagger.json
  format: json
  label: Oracle Siebel REST API
  slug: ''
  spec_type: OpenAPI
  url: https://{siebel-server}/siebel/v1.0/swagger.json
apis:
- description: RESTful API for accessing Siebel business objects, business services, and repository objects. The Siebel REST API supports standard CRUD operations using HTTP verbs (GET, POST, PUT, DELETE) and is com
  name: Oracle Siebel REST API
  slug: ''
- description: SOAP-based web services for enterprise integration with Siebel CRM, supporting complex business operations and workflows. Siebel provides both inbound web services for external clients to access Siebe
  name: Oracle Siebel SOAP Web Services
  slug: ''
- description: APIs for creating and consuming custom business services within the Siebel platform for specialized business logic. Business services encapsulate reusable business logic that can be invoked through sc
  name: Oracle Siebel Business Service API
  slug: ''
- description: 'Integration services for connecting Siebel with external systems using various protocols and data formats. Siebel EAI provides bidirectional, real-time, and batch integration solutions with pre-built '
  name: Oracle Siebel EAI (Enterprise Application Integration)
  slug: ''
- description: Programmatic interfaces for accessing Siebel business objects, business components, and application objects using Siebel eScript, Siebel Visual Basic, or the Siebel Java Data Bean. The Object Interfac
  name: Oracle Siebel Object Interfaces API
  slug: ''
- description: 'Client-side JavaScript API for customizing the Siebel Open UI user interface. The API provides well-defined customization points for styling, layout, and user interface design, allowing developers to '
  name: Oracle Siebel Open UI JavaScript API
  slug: ''
- description: Event-driven integration framework enabling real-time communication between Siebel CRM and external systems using Apache Kafka. The Event Pub/Sub API supports publishing events from Siebel to Kafka to
  name: Oracle Siebel Event Pub/Sub API
  slug: ''
asyncapis:
- description: Event-driven integration framework enabling real-time communication between Oracle Siebel CRM and external systems using Apache Kafka. The Event Pub/Sub system supports publishing events from Siebel t
  name: Oracle Siebel CRM Event Pub/Sub
  slug: oracle-siebel-event-pubsub-asyncapi
common:
- title: ''
  type: Portal
  url: https://docs.oracle.com/cd/G15000_01/SiebelInfoPortal/
- title: ''
  type: Website
  url: https://www.oracle.com/applications/siebel/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/applications/siebel/
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/cd/F26413_61/books/FundOUI/index.html
- title: ''
  type: Authentication
  url: https://docs.oracle.com/cd/F26413_26/books/Secur/single-sign-on-authentication.html
- title: ''
  type: Security
  url: https://docs.oracle.com/cd/F26413_26/books/Secur/index.html
- title: ''
  type: Support
  url: https://www.oracle.com/support/premier/software/siebel/
- title: ''
  type: Community
  url: https://community.oracle.com/customerconnect/categories/onprem-siebel-crm
- title: ''
  type: Blog
  url: https://blogs.oracle.com/siebelcrm/
- title: ''
  type: Change Log
  url: https://docs.oracle.com/cd/F26413_61/homepage.htm
- title: ''
  type: Training
  url: https://learn.oracle.com/ols/home/38497
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Login
  url: https://support.oracle.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/OracleSiebel
- title: ''
  type: GitHubRepository
  url: https://github.com/OracleSiebel/ConfiguringSiebel
created: '2024-01-01'
description: Oracle Siebel CRM APIs provide programmatic access to customer relationship management functionality including sales, marketing, and service automation capabilities. Siebel CRM offers REST, SOAP, scripting, and event-driven integration interfaces for building integrations with enterprise systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Oracle Siebel
skills: []
slug: oracle-siebel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-siebel\nname: Oracle Siebel\ndescription: >-\n  Oracle Siebel CRM APIs provide programmatic access to customer relationship\n  management functionality including sales, marketing, and service automation\n  capabilities. Siebel CRM offers REST, SOAP, scripting, and event-driven\n  integration interfaces for building integrations with enterprise systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-siebel/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Oracle Siebel REST API\n    description: >-\n      RESTful API for accessing Siebel business objects, business services, and\n      repository objects. The Siebel REST API supports standard CRUD operations\n      using HTTP verbs (GET, POST, PUT, DELETE) and is compatible with OpenAPI\n    \
  \  3.0 specifications for integration with modern applications and mobile\n      devices.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/E95904_01/books/RestAPI/overview-of-using-the-siebel-rest-api.html\n    baseURL: https://{siebel-server}/siebel/v1.0\n    tags:\n      - CRM\n      - Customer Management\n      - Integration\n      - REST\n      - Sales\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/E95904_01/books/RestAPI/overview-of-using-the-siebel-rest-api.html\n      - type: OpenAPI\n        url: https://{siebel-server}/siebel/v1.0/swagger.json\n      - type: Authentication\n        url: https://docs.oracle.com/cd/F26413_26/books/Secur/single-sign-on-authentication.html\n      - type: Getting Started\n        url: https://docs.oracle.com/cd/E95904_01/books/RestAPI/getting-started-with-the-siebel-rest-api.html\n  - name: Oracle Siebel SOAP Web Services\n    description: >-\n      SOAP-based\
  \ web services for enterprise integration with Siebel CRM,\n      supporting complex business operations and workflows. Siebel provides\n      both inbound web services for external clients to access Siebel\n      functionality and outbound web services for Siebel to call external\n      applications.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_08/books/CRMWeb/siebel-crm-web-services-overview.html\n    baseURL: https://{siebel-server}/siebel/app/soap/services\n    tags:\n      - CRM\n      - Enterprise Integration\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_08/books/CRMWeb/siebel-crm-web-services-overview.html\n      - type: WSDL\n        url: https://{siebel-server}/siebel/app/soap/services?WSDL\n      - type: Reference\n        url: https://docs.oracle.com/cd/F26413_16/books/CRMWeb/crm-web-services-reference.pdf\n  - name: Oracle Siebel\
  \ Business Service API\n    description: >-\n      APIs for creating and consuming custom business services within the Siebel\n      platform for specialized business logic. Business services encapsulate\n      reusable business logic that can be invoked through scripting, workflows,\n      REST, or SOAP interfaces.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_13/books/OIRef/siebel-object-interfaces-reference.html\n    tags:\n      - Business Services\n      - Custom Logic\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_13/books/OIRef/siebel-object-interfaces-reference.html\n  - name: Oracle Siebel EAI (Enterprise Application Integration)\n    description: >-\n      Integration services for connecting Siebel with external systems using\n      various protocols and data formats. Siebel EAI provides bidirectional,\n      real-time, and batch integration solutions\
  \ with pre-built adapters,\n      enterprise connectors, and support for XML, HTTP, IBM MQSeries, and\n      MSMQ transports.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_25/books/EAI1/overview-of-siebel-eai.html\n    tags:\n      - Data Exchange\n      - EAI\n      - Integration\n      - Middleware\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_25/books/EAI1/overview-of-siebel-eai.html\n      - type: Reference\n        url: https://docs.oracle.com/cd/F26413_32/books/EAI2/toc.htm\n  - name: Oracle Siebel Object Interfaces API\n    description: >-\n      Programmatic interfaces for accessing Siebel business objects, business\n      components, and application objects using Siebel eScript, Siebel Visual\n      Basic, or the Siebel Java Data Bean. The Object Interfaces API provides\n      methods for querying, inserting, updating, and deleting records, as well\n      as invoking\
  \ business services and managing application state.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_13/books/OIRef/siebel-object-interfaces-reference.html\n    tags:\n      - Business Components\n      - Java Data Bean\n      - Object Interfaces\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_13/books/OIRef/siebel-object-interfaces-reference.html\n      - type: Reference\n        url: https://docs.oracle.com/cd/F26413_25/books/EAI3/integrating-siebel-crm-with-java-applications.html\n  - name: Oracle Siebel Open UI JavaScript API\n    description: >-\n      Client-side JavaScript API for customizing the Siebel Open UI user\n      interface. The API provides well-defined customization points for styling,\n      layout, and user interface design, allowing developers to integrate Siebel\n      Open UI objects such as views and applets into third-party user interfaces\n\
  \      and include external content in the Siebel Open UI client.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_26/books/ConfigOpenUI/configuring-siebel-open-ui-guide.pdf\n    tags:\n      - Customization\n      - JavaScript\n      - Open UI\n      - User Interface\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_26/books/ConfigOpenUI/configuring-siebel-open-ui-guide.pdf\n      - type: Reference\n        url: https://docs.oracle.com/cd/F26413_17/books/DeployOpenUI/features-of-siebel-open-ui.html\n  - name: Oracle Siebel Event Pub/Sub API\n    description: >-\n      Event-driven integration framework enabling real-time communication between\n      Siebel CRM and external systems using Apache Kafka. The Event Pub/Sub API\n      supports publishing events from Siebel to Kafka topics and consuming events\n      from Kafka into Siebel, with support for Avro serialization, OAuth 2.0\n\
  \      security, and Kafka partitioning for scalability.\n    image: https://www.oracle.com/a/ocom/img/siebel-logo.png\n    humanURL: https://docs.oracle.com/cd/F26413_50/books/SystAdm/c-Overview-of-Siebel-CRM-Event-Publication-and-Subscription.html\n    tags:\n      - Event-Driven\n      - Kafka\n      - Pub/Sub\n      - Real-Time Integration\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/cd/F26413_50/books/SystAdm/c-Overview-of-Siebel-CRM-Event-Publication-and-Subscription.html\ncommon:\n  - type: Portal\n    url: https://docs.oracle.com/cd/G15000_01/SiebelInfoPortal/\n  - type: Website\n    url: https://www.oracle.com/applications/siebel/\n  - type: Documentation\n    url: https://docs.oracle.com/en/applications/siebel/\n  - type: Getting Started\n    url: https://docs.oracle.com/cd/F26413_61/books/FundOUI/index.html\n  - type: Authentication\n    url: https://docs.oracle.com/cd/F26413_26/books/Secur/single-sign-on-authentication.html\n  - type:\
  \ Security\n    url: https://docs.oracle.com/cd/F26413_26/books/Secur/index.html\n  - type: Support\n    url: https://www.oracle.com/support/premier/software/siebel/\n  - type: Community\n    url: https://community.oracle.com/customerconnect/categories/onprem-siebel-crm\n  - type: Blog\n    url: https://blogs.oracle.com/siebelcrm/\n  - type: Change Log\n    url: https://docs.oracle.com/cd/F26413_61/homepage.htm\n  - type: Training\n    url: https://learn.oracle.com/ols/home/38497\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Login\n    url: https://support.oracle.com/\n  - type: GitHub Organization\n    url: https://github.com/OracleSiebel\n  - type: GitHubRepository\n    url: https://github.com/OracleSiebel/ConfiguringSiebel\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - CRM\n\
  \  - Customer Management\n  - Enterprise Software\n  - Marketing Automation\n  - Oracle\n  - Sales Automation\n  - Service Automation\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-siebel/refs/heads/main/apis.yml
tags:
- CRM
- Customer Management
- Enterprise Software
- Marketing Automation
- Oracle
- Sales Automation
- Service Automation
url: https://raw.githubusercontent.com/api-evangelist/oracle-siebel/refs/heads/main/apis.yml
use_cases: []
---
