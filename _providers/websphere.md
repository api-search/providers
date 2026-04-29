---
api_count: 8
apis:
- description: REST API for administrative operations on WebSphere Application Server including deployment, configuration, and monitoring. Starting with version 9.0.0.1, Swagger documentation can be discovered and e
  name: WebSphere Application Server Admin API
  slug: websphere-admin-rest-api
- description: RESTful administrative API for WebSphere Liberty servers, providing configuration and runtime management capabilities. The Admin REST Connector enables secure remote access through HTTPS calls or Java
  name: WebSphere Liberty Admin REST API
  slug: websphere-liberty-admin-rest-api
- description: Secure REST-based JMX connector for remote administration of Liberty servers. Provides file transfer and JMX MBean access through HTTPS endpoints, requiring TLS for confidential communication.
  name: WebSphere Liberty REST Connector API
  slug: websphere-liberty-rest-connector-api
- description: REST API for IBM MQ messaging operations including sending and receiving messages, queue management, and monitoring. Supports both administration and messaging endpoints for point-to-point and publish
  name: WebSphere MQ REST API
  slug: websphere-mq-rest-api
- description: Java Management Extensions (JMX) API for programmatic management and monitoring of WebSphere Application Server. Provides MBean access for server configuration, performance monitoring, and resource ma
  name: WebSphere Application Server JMX API
  slug: websphere-jmx-api
- description: API for managing Liberty collective environments, including member management, scaling, and centralized administration. Supports subscription-based notifications for API changes across collective memb
  name: WebSphere Liberty Collective Controller REST API
  slug: websphere-liberty-collective-controller-rest-api
- description: API for WebSphere Automation capabilities including vulnerability management, automated patching, and health monitoring. Accessible through the Swagger UI on OpenShift Container Platform deployments.
  name: WebSphere Automation REST API
  slug: websphere-automation-rest-api
- description: Open Liberty provides application programming interfaces that extend and complement Jakarta EE and MicroProfile APIs. Includes APIs for security, admin connectors, batch processing, messaging, and mor
  name: Open Liberty APIs
  slug: open-liberty-apis
capabilities:
- description: Workflow for managing IBM MQ messaging infrastructure including queue management, message operations, channels, and topics for integration architects and middleware administrators.
  name: WebSphere Messaging and Integration
  slug: messaging-and-integration
- description: Workflow for monitoring WebSphere environments combining health checks, metrics, performance data, logging, and batch job tracking from Open Liberty and traditional WAS APIs for operations teams.
  name: WebSphere Monitoring and Observability
  slug: monitoring-and-observability
- description: Workflow for security vulnerability management, automated patching, compliance reporting, and health monitoring across WebSphere environments for security engineers and compliance teams.
  name: WebSphere Security and Compliance
  slug: security-and-compliance
- description: Unified workflow for administering WebSphere Application Server and Liberty environments, combining traditional admin, Liberty admin, collective controller, and JMX connector APIs for platform adminis
  name: WebSphere Server Administration
  slug: server-administration
common:
- title: ''
  type: Portal
  url: https://developer.ibm.com/wasdev/
- title: ''
  type: Support
  url: https://www.ibm.com/mysupport
- title: ''
  type: Documentation
  url: https://www.ibm.com/docs/en/was
- title: ''
  type: GettingStarted
  url: https://www.ibm.com/support/pages/websphere-liberty-developers
- title: ''
  type: ChangeLog
  url: https://www.ibm.com/support/pages/recommended-updates-websphere-application-server
- title: ''
  type: Pricing
  url: https://www.ibm.com/products/websphere-hybrid-edition/pricing
- title: ''
  type: TermsOfService
  url: https://www.ibm.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.ibm.com/us-en/privacy
- title: ''
  type: StatusPage
  url: https://cloud.ibm.com/status
- title: ''
  type: Blog
  url: https://openliberty.io/blog/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/websphere
- title: ''
  type: SignUp
  url: https://cloud.ibm.com/registration
- title: ''
  type: Console
  url: https://www.ibm.com/products/liberty
- title: ''
  type: GitHubOrganization
  url: https://github.com/WASdev
- title: ''
  type: SDK
  url: https://github.com/WASdev/sample.batch.bonuspayout
created: '2024-01-15'
description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
features:
- Enterprise Java Application Hosting
- Cloud-Native Deployment with Liberty
- Centralized Server Management
- Auto-Scaling and Clustering
- JMX Remote Administration
- IBM MQ Integration
- Automated Vulnerability Patching
- Jakarta EE and MicroProfile Support
image: https://www.ibm.com/brand/experience-guides/developer/b1db1ae501d522a1a4b49613fe07c9f4/01_8-bar-positive.svg
integrations:
- IBM MQ
- IBM Cloud
- OpenShift Container Platform
- Jenkins CI/CD
- IBM Db2
- Oracle Database
- LDAP / Active Directory
- Prometheus and Grafana
jsonld:
- class_count: 3
  name: context Context
  property_count: 11
  slug: context
- class_count: 0
  name: Open Libertys Context
  property_count: 0
  slug: open-libertys-context
- class_count: 0
  name: Websphere Admin Rest Context
  property_count: 0
  slug: websphere-admin-rest-context
- class_count: 0
  name: Websphere Automation Rest Context
  property_count: 0
  slug: websphere-automation-rest-context
- class_count: 0
  name: Websphere Liberty Admin Rest Context
  property_count: 0
  slug: websphere-liberty-admin-rest-context
- class_count: 0
  name: Websphere Liberty Collective Controller Rest Context
  property_count: 0
  slug: websphere-liberty-collective-controller-rest-context
- class_count: 0
  name: Websphere Liberty Rest Connector Context
  property_count: 0
  slug: websphere-liberty-rest-connector-context
- class_count: 0
  name: Websphere Mq Rest Context
  property_count: 0
  slug: websphere-mq-rest-context
layout: provider
modified: '2026-04-18'
name: IBM WebSphere
rules:
- name: IBM WebSphere API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: websphere-spectral-rules
skills: []
slug: websphere
solutions: []
source_yaml: "aid: websphere\nname: IBM WebSphere\ndescription: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.\nimage: https://www.ibm.com/brand/experience-guides/developer/b1db1ae501d522a1a4b49613fe07c9f4/01_8-bar-positive.svg\nurl: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/apis.yml\ntags:\n  - Application Server\n  - Cloud Native\n  - Enterprise Java\n  - J2EE\n  - Microservices\n  - Middleware\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Index\napis:\n  - aid: websphere:websphere-admin-rest-api\n    name: WebSphere Application Server Admin API\n    description: REST API for administrative operations on WebSphere Application Server including deployment, configuration, and monitoring. Starting with version 9.0.0.1, Swagger documentation can be discovered and exposed for deployed RESTful\
  \ endpoints.\n    image: https://www.ibm.com/brand/experience-guides/developer/b1db1ae501d522a1a4b49613fe07c9f4/01_8-bar-positive.svg\n    baseURL: https://localhost:9443/ibm/api\n    humanURL: https://www.ibm.com/docs/en/was\n    tags:\n      - Administration\n      - Configuration\n      - Deployment\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=overview-administrative-rest-api\n      - type: OpenAPI\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=api-openapi-specification\n      - type: OpenAPI\n        url: openapi/websphere-admin-rest-api.yml\n      - type: Authentication\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=api-authentication-authorization\n      - type: GettingStarted\n        url: https://www.ibm.com/docs/en/was-nd/9.0.5?topic=specifications-discovering-rest-api-documentation\n      - type: APIReference\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=javadoc-apis-application-programming-interfaces\n\
  \      - type: JSONSchema\n        url: json-schema/application.json\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONSchema\n        url: json-schema/cluster.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:websphere-liberty-admin-rest-api\n    name: WebSphere Liberty Admin REST API\n    description: RESTful administrative API for WebSphere Liberty servers, providing configuration and runtime management capabilities. The Admin REST Connector enables secure remote access through HTTPS calls or Java clients.\n    baseURL: https://localhost:9443/ibm/api\n    humanURL: https://www.ibm.com/docs/en/was-liberty\n    tags:\n      - Administration\n      - Configuration\n      - Liberty\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=liberty-admin-rest-api\n      - type: OpenAPI\n        url: openapi/websphere-liberty-admin-rest-api.yml\n      -\
  \ type: GettingStarted\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=api-getting-started\n      - type: APIReference\n        url: https://openliberty.io/docs/latest/reference/feature/restConnector-2.0.html\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=center-setting-up-admin\n      - type: JSONSchema\n        url: json-schema/application.json\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:websphere-liberty-rest-connector-api\n    name: WebSphere Liberty REST Connector API\n    description: Secure REST-based JMX connector for remote administration of Liberty servers. Provides file transfer and JMX MBean access through HTTPS endpoints, requiring TLS for confidential communication.\n    baseURL: https://localhost:9443/IBMJMXConnectorREST/api\n    humanURL: https://openliberty.io/docs/latest/reference/feature/restConnector-2.0.html\n\
  \    tags:\n      - JMX\n      - Liberty\n      - Remote Administration\n      - REST Connector\n    properties:\n      - type: Documentation\n        url: https://openliberty.io/docs/latest/reference/feature/restConnector-2.0.html\n      - type: OpenAPI\n        url: openapi/websphere-liberty-rest-connector-api.yml\n      - type: APIReference\n        url: https://openliberty.io/docs/latest/reference/api/open-liberty-apis.html\n      - type: Documentation\n        url: https://openliberty.io/docs/latest/configuring-jmx-connection.html\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was-liberty/core?topic=features-admin-rest-connector-20\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:websphere-mq-rest-api\n    name: WebSphere MQ REST API\n    description: REST API for IBM MQ messaging operations including sending and receiving messages, queue management, and monitoring. Supports both administration and messaging endpoints for point-to-point\
  \ and publish-subscribe patterns.\n    baseURL: https://localhost:9443/ibmmq/rest/v2\n    humanURL: https://www.ibm.com/docs/en/ibm-mq\n    tags:\n      - Integration\n      - Messaging\n      - Publish Subscribe\n      - Queue Management\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/ibm-mq/9.3?topic=api-rest-introduction\n      - type: OpenAPI\n        url: openapi/websphere-mq-rest-api.yml\n      - type: APIReference\n        url: https://www.ibm.com/docs/en/ibm-mq/9.3?topic=api-rest-reference\n      - type: Authentication\n        url: https://www.ibm.com/docs/en/ibm-mq/9.3?topic=api-rest-authentication\n      - type: GettingStarted\n        url: https://developer.ibm.com/tutorials/mq-develop-mq-rest-api/\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/ibm-mq/9.3?topic=mq-messaging-using-rest-api\n      - type: JSONSchema\n        url: json-schema/message-queue.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n\
  \  - aid: websphere:websphere-jmx-api\n    name: WebSphere Application Server JMX API\n    description: Java Management Extensions (JMX) API for programmatic management and monitoring of WebSphere Application Server. Provides MBean access for server configuration, performance monitoring, and resource management.\n    baseURL: service:jmx:rmi:///jndi/rmi://localhost:2809/jmxrmi\n    humanURL: https://www.ibm.com/docs/en/was\n    tags:\n      - JMX\n      - Management\n      - MBeans\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=api-using-jmx\n      - type: APIReference\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=reference-javadoc\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was/9.0.5?topic=api-jmx-examples\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:websphere-liberty-collective-controller-rest-api\n\
  \    name: WebSphere Liberty Collective Controller REST API\n    description: API for managing Liberty collective environments, including member management, scaling, and centralized administration. Supports subscription-based notifications for API changes across collective members.\n    baseURL: https://localhost:9443/ibm/api/collective\n    humanURL: https://www.ibm.com/docs/en/was-liberty\n    tags:\n      - Clustering\n      - Collective\n      - Liberty\n      - Management\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=liberty-collective-rest-api\n      - type: OpenAPI\n        url: openapi/websphere-liberty-collective-controller-rest-api.yml\n      - type: APIReference\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=api-collective-reference\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/was-liberty/base?topic=deploying-applications-in-liberty\n      - type: JSONSchema\n       \
  \ url: json-schema/cluster.json\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:websphere-automation-rest-api\n    name: WebSphere Automation REST API\n    description: API for WebSphere Automation capabilities including vulnerability management, automated patching, and health monitoring. Accessible through the Swagger UI on OpenShift Container Platform deployments.\n    baseURL: https://automation-api.example.com/v1\n    humanURL: https://www.ibm.com/docs/en/ws-automation\n    tags:\n      - Automation\n      - Health Monitoring\n      - Patching\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://www.ibm.com/docs/en/ws-automation?topic=apis\n      - type: OpenAPI\n        url: openapi/websphere-automation-rest-api.yml\n      - type: APIReference\n        url: https://www.ibm.com/docs/en/ws-automation?topic=reference-rest-api\n      - type: Documentation\n\
  \        url: https://www.ibm.com/docs/en/ws-automation?topic=viewing-rest-api\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n  - aid: websphere:open-liberty-apis\n    name: Open Liberty APIs\n    description: Open Liberty provides application programming interfaces that extend and complement Jakarta EE and MicroProfile APIs. Includes APIs for security, admin connectors, batch processing, messaging, and more.\n    baseURL: https://localhost:9443/ibm/api\n    humanURL: https://openliberty.io/docs/latest/reference/api/open-liberty-apis.html\n    tags:\n      - Cloud Native\n      - Jakarta EE\n      - MicroProfile\n      - Open Liberty\n    properties:\n      - type: Documentation\n        url: https://openliberty.io/docs/latest/reference/api/open-liberty-apis.html\n      - type: OpenAPI\n        url: openapi/open-liberty-apis.yml\n      - type: APIReference\n        url: https://openliberty.io/docs/latest/documentation-openapi.html\n\
  \      - type: GettingStarted\n        url: https://openliberty.io/guides/rest-intro.html\n      - type: Documentation\n        url: https://openliberty.io/docs/latest/microprofile.html\n      - type: Blog\n        url: https://openliberty.io/blog/\n      - type: JSONSchema\n        url: json-schema/application.json\n      - type: JSONSchema\n        url: json-schema/server.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.ibm.com/wasdev/\n  - type: Support\n    url: https://www.ibm.com/mysupport\n  - type: Documentation\n    url: https://www.ibm.com/docs/en/was\n  - type: GettingStarted\n    url: https://www.ibm.com/support/pages/websphere-liberty-developers\n  - type: ChangeLog\n    url: https://www.ibm.com/support/pages/recommended-updates-websphere-application-server\n  - type: Pricing\n    url: https://www.ibm.com/products/websphere-hybrid-edition/pricing\n\
  \  - type: TermsOfService\n    url: https://www.ibm.com/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.ibm.com/us-en/privacy\n  - type: StatusPage\n    url: https://cloud.ibm.com/status\n  - type: Blog\n    url: https://openliberty.io/blog/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/websphere\n  - type: SignUp\n    url: https://cloud.ibm.com/registration\n  - type: Console\n    url: https://www.ibm.com/products/liberty\n  - type: GitHubOrganization\n    url: https://github.com/WASdev\n  - type: SDK\n    url: https://github.com/WASdev/sample.batch.bonuspayout\n  - type: Features\n    url: https://www.ibm.com/products/websphere-application-server\n    data:\n      - Enterprise Java Application Hosting\n      - Cloud-Native Deployment with Liberty\n      - Centralized Server Management\n      - Auto-Scaling and Clustering\n      - JMX Remote Administration\n      - IBM MQ Integration\n      - Automated Vulnerability Patching\n      - Jakarta\
  \ EE and MicroProfile Support\n  - type: UseCases\n    url: https://www.ibm.com/products/websphere-application-server\n    data:\n      - Enterprise Application Hosting and Deployment\n      - Microservices Architecture with Liberty\n      - Message-Driven Integration with IBM MQ\n      - Automated Compliance and Security Patching\n      - Batch Processing and Job Management\n      - Centralized Multi-Server Administration\n  - type: Integrations\n    url: https://www.ibm.com/docs/en/was\n    data:\n      - IBM MQ\n      - IBM Cloud\n      - OpenShift Container Platform\n      - Jenkins CI/CD\n      - IBM Db2\n      - Oracle Database\n      - LDAP / Active Directory\n      - Prometheus and Grafana\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/apis.yml
tags:
- Application Server
- Cloud Native
- Enterprise Java
- J2EE
- Microservices
- Middleware
url: https://raw.githubusercontent.com/api-evangelist/websphere/refs/heads/main/apis.yml
use_cases:
- Enterprise Application Hosting and Deployment
- Microservices Architecture with Liberty
- Message-Driven Integration with IBM MQ
- Automated Compliance and Security Patching
- Batch Processing and Job Management
- Centralized Multi-Server Administration
---
