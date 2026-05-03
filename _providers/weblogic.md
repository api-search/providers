---
api_count: 5
api_specs:
- filename: weblogic-restful-management-services-openapi.yml
  format: yaml
  label: WebLogic RESTful Management Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-restful-management-services-openapi.yml
- filename: weblogic-monitoring-diagnostics-openapi.yml
  format: yaml
  label: WebLogic Monitoring and Diagnostics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-monitoring-diagnostics-openapi.yml
- filename: weblogic-deployment-openapi.yml
  format: yaml
  label: WebLogic Deployment API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/openapi/weblogic-deployment-openapi.yml
apis:
- description: RESTful API for monitoring and managing WebLogic Server domains, servers, applications, and resources. Provides access to configuration editing, server lifecycle management, cluster administration, da
  name: WebLogic RESTful Management Services API
  slug: ''
- description: API for accessing runtime monitoring data, metrics, and diagnostics information. Provides server health, JVM metrics, thread pool statistics, JDBC data source metrics, JMS statistics, application depl
  name: WebLogic Monitoring and Diagnostics API
  slug: ''
- description: API for deploying, undeploying, redeploying, and managing applications and shared libraries. Supports the full deployment lifecycle including prepare, activate, start, stop, redeploy, and undeploy ope
  name: WebLogic Deployment API
  slug: ''
- description: Python-based scripting interface for automating WebLogic Server administration tasks. Supports online (connected) and offline modes for configuring, deploying, and managing WebLogic domains programmat
  name: WebLogic WLST (WebLogic Scripting Tool) API
  slug: ''
- description: Java Management Extensions API for programmatic access to WebLogic Server MBeans. Provides the same management capabilities as the REST API via JMX connections, suitable for Java-based management clie
  name: WebLogic JMX API
  slug: ''
capabilities:
- description: Unified capability for managing Oracle WebLogic Server application deployments and shared libraries. Combines the deployment API with monitoring to support the full deploy-verify-manage lifecycle. Use
  name: Oracle WebLogic Application Deployment
  slug: application-deployment
- description: Unified capability for Oracle WebLogic Server domain administration combining domain configuration management, server lifecycle control, and monitoring. Used by WebLogic administrators to manage entir
  name: Oracle WebLogic Domain Administration
  slug: domain-administration
common:
- title: ''
  type: Portal
  url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/
- title: ''
  type: Getting Started
  url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/intro/
- title: ''
  type: Downloads
  url: https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Community
  url: https://community.oracle.com/tech/developers/categories/weblogic-server
- title: ''
  type: Blog
  url: https://blogs.oracle.com/weblogicserver/
- title: ''
  type: Website
  url: https://www.oracle.com/middleware/technologies/weblogic.html
- title: ''
  type: Terms of Service
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: GitHub Organization
  url: https://github.com/oracle
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/weblogic
- title: ''
  type: YouTube
  url: https://www.youtube.com/@OracleDevelopers
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: Vocabulary
  url: vocabulary/weblogic-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/weblogic-rules.yml
created: '2024'
description: Collection of APIs and resources for Oracle WebLogic Server administration and management. WebLogic Server is Oracle's enterprise-grade Java EE application server providing high availability, scalability, and comprehensive management capabilities through RESTful management APIs, monitoring and diagnostics, and deployment services.
features: []
image: https://www.oracle.com/a/ocom/img/weblogic-server.png
integrations: []
jsonld:
- class_count: 0
  name: Weblogic Context
  property_count: 9
  slug: weblogic-context
layout: provider
modified: '2026-05-03'
name: Oracle WebLogic Server APIs
rules:
- name: Oracle WebLogic Server APIs API Rules
  rule_count: 13
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 11
  slug: weblogic-rules
skills: []
slug: weblogic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Oracle WebLogic Server APIs\ndescription: >-\n  Collection of APIs and resources for Oracle WebLogic Server administration and management.\n  WebLogic Server is Oracle's enterprise-grade Java EE application server providing high\n  availability, scalability, and comprehensive management capabilities through RESTful\n  management APIs, monitoring and diagnostics, and deployment services.\nimage: https://www.oracle.com/a/ocom/img/weblogic-server.png\nurl: https://www.oracle.com/middleware/technologies/weblogic.html\ncreated: '2024'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - name: WebLogic RESTful Management Services API\n    description: >-\n      RESTful API for monitoring and managing WebLogic Server domains, servers, applications,\n      and resources. Provides access to configuration editing, server lifecycle management,\n      cluster administration, data source management, and JMS resource configuration.\n    image: https://www.oracle.com/a/ocom/img/weblogic-server.png\n\
  \    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/\n    baseUrl: https://host:port/management/weblogic/latest\n    tags:\n      - Administration\n      - Clusters\n      - Configuration\n      - Data Sources\n      - JMS\n      - Management\n      - Monitoring\n      - REST\n      - Server Lifecycle\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/\n      - type: OpenAPI\n        url: openapi/weblogic-restful-management-services-openapi.yml\n      - type: JSONSchema\n        url: json-schema/weblogic-server-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-domain-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-cluster-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-datasource-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-server-runtime.json\n\
  \      - type: JSONStructure\n        url: json-structure/weblogic-server-configuration-structure.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n    contact:\n      - FN: Oracle Support\n        url: https://support.oracle.com\n  - name: WebLogic Monitoring and Diagnostics API\n    description: >-\n      API for accessing runtime monitoring data, metrics, and diagnostics information.\n      Provides server health, JVM metrics, thread pool statistics, JDBC data source\n      metrics, JMS statistics, application deployment metrics, and WLDF diagnostics.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/\n    baseUrl: https://host:port/management/wls/latest\n    tags:\n      - Diagnostics\n      - Health\n      - JMX\n      - Metrics\n      - Monitoring\n      - Performance\n      - WLDF\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/\n\
  \      - type: OpenAPI\n        url: openapi/weblogic-monitoring-diagnostics-openapi.yml\n      - type: JSONSchema\n        url: json-schema/weblogic-server-runtime.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n  - name: WebLogic Deployment API\n    description: >-\n      API for deploying, undeploying, redeploying, and managing applications and shared\n      libraries. Supports the full deployment lifecycle including prepare, activate, start,\n      stop, redeploy, and undeploy operations.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/\n    baseUrl: https://host:port/management/weblogic/latest/edit/appDeployments\n    tags:\n      - Applications\n      - Deployment\n      - DevOps\n      - Libraries\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/\n      - type: OpenAPI\n        url: openapi/weblogic-deployment-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/weblogic-application-deployment.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n  - name: WebLogic WLST (WebLogic Scripting Tool) API\n    description: >-\n      Python-based scripting interface for automating WebLogic Server administration\n      tasks. Supports online (connected) and offline modes for configuring, deploying,\n      and managing WebLogic domains programmatically.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/\n    tags:\n      - Automation\n      - CLI\n      - Python\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/\n      - type: Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstg/\n  - name: WebLogic JMX API\n    description: >-\n      Java Management Extensions\
  \ API for programmatic access to WebLogic Server MBeans.\n      Provides the same management capabilities as the REST API via JMX connections,\n      suitable for Java-based management clients and monitoring tools.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/\n    tags:\n      - Java\n      - JMX\n      - Management\n      - MBeans\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/\n      - type: API Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlmbr/\n\ncommon:\n  - type: Portal\n    url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/\n  - type: Getting Started\n    url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/intro/\n  - type: Downloads\n    url: https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html\n\
  \  - type: Support\n    url: https://support.oracle.com\n  - type: Community\n    url: https://community.oracle.com/tech/developers/categories/weblogic-server\n  - type: Blog\n    url: https://blogs.oracle.com/weblogicserver/\n  - type: Website\n    url: https://www.oracle.com/middleware/technologies/weblogic.html\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: GitHub Organization\n    url: https://github.com/oracle\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/weblogic\n  - type: YouTube\n    url: https://www.youtube.com/@OracleDevelopers\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: Vocabulary\n    url: vocabulary/weblogic-vocabulary.yml\n  - type: SpectralRules\n    url: rules/weblogic-rules.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n\ntags:\n \
  \ - Application Server\n  - Enterprise\n  - Java EE\n  - Middleware\n  - Oracle\n  - WebLogic\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weblogic/refs/heads/main/apis.yml
tags:
- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle
- WebLogic
url: https://www.oracle.com/middleware/technologies/weblogic.html
use_cases: []
---
