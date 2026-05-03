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
- description: RESTful API for monitoring and managing WebLogic Server domains, servers, applications, and resources.
  name: WebLogic RESTful Management Services API
  slug: ''
- description: API for accessing runtime monitoring data, metrics, and diagnostics information.
  name: WebLogic Monitoring and Diagnostics API
  slug: ''
- description: API for deploying, undeploying, and managing applications and resources.
  name: WebLogic Deployment API
  slug: ''
- description: Python-based scripting interface for automating WebLogic Server administration tasks.
  name: WebLogic WLST (WebLogic Scripting Tool) API
  slug: ''
- description: Java Management Extensions API for programmatic access to WebLogic Server MBeans.
  name: WebLogic JMX API
  slug: ''
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
created: '2024'
description: Collection of APIs and resources for Oracle WebLogic Server administration and management.
features: []
image: https://www.oracle.com/a/ocom/img/weblogic-server.png
integrations: []
jsonld:
- class_count: 0
  name: Weblogic Context
  property_count: 9
  slug: weblogic-context
layout: provider
modified: '2026-03-04'
name: Oracle WebLogic Server APIs
skills: []
slug: weblogic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Oracle WebLogic Server APIs\ndescription: >-\n  Collection of APIs and resources for Oracle WebLogic Server administration and management.\nimage: https://www.oracle.com/a/ocom/img/weblogic-server.png\nurl: https://www.oracle.com/middleware/technologies/weblogic.html\ncreated: '2024'\nmodified: '2026-03-04'\nspecificationVersion: '0.18'\napis:\n  - name: WebLogic RESTful Management Services API\n    description: >-\n      RESTful API for monitoring and managing WebLogic Server domains, servers, applications,\n      and resources.\n    image: https://www.oracle.com/a/ocom/img/weblogic-server.png\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/\n    baseUrl: https://host:port/management/weblogic/latest\n    tags:\n      - Configuration\n      - Management\n      - Monitoring\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/restm/\n\
  \      - type: OpenAPI\n        url: openapi/weblogic-restful-management-services-openapi.yml\n      - type: JSONSchema\n        url: json-schema/weblogic-server-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-domain-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-cluster-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-datasource-configuration.json\n      - type: JSONSchema\n        url: json-schema/weblogic-server-runtime.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n    contact:\n      - FN: Oracle Support\n        url: https://support.oracle.com\n  - name: WebLogic Monitoring and Diagnostics API\n    description: >-\n      API for accessing runtime monitoring data, metrics, and diagnostics information.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/\n    baseUrl: https://host:port/management/wls/latest\n  \
  \  tags:\n      - Diagnostics\n      - Metrics\n      - Monitoring\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrst/\n      - type: OpenAPI\n        url: openapi/weblogic-monitoring-diagnostics-openapi.yml\n      - type: JSONSchema\n        url: json-schema/weblogic-server-runtime.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n  - name: WebLogic Deployment API\n    description: >-\n      API for deploying, undeploying, and managing applications and resources.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/\n    baseUrl: https://host:port/management/weblogic/latest/edit/appDeployments\n    tags:\n      - Applications\n      - Deployment\n      - Resources\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/\n\
  \      - type: OpenAPI\n        url: openapi/weblogic-deployment-openapi.yml\n      - type: JSONSchema\n        url: json-schema/weblogic-application-deployment.json\n      - type: JSONLD\n        url: json-ld/weblogic-context.jsonld\n  - name: WebLogic WLST (WebLogic Scripting Tool) API\n    description: >-\n      Python-based scripting interface for automating WebLogic Server administration\n      tasks.\n    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/\n    tags:\n      - Automation\n      - CLI\n      - Python\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/\n      - type: Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstg/\n  - name: WebLogic JMX API\n    description: >-\n      Java Management Extensions API for programmatic access to WebLogic Server MBeans.\n\
  \    humanUrl: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/\n    tags:\n      - Java\n      - JMX\n      - Management\n      - MBeans\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/\n      - type: API Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlmbr/\ncommon:\n  - type: Portal\n    url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/\n  - type: Getting Started\n    url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/intro/\n  - type: Downloads\n    url: https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html\n  - type: Support\n    url: https://support.oracle.com\n  - type: Community\n    url: https://community.oracle.com/tech/developers/categories/weblogic-server\n  - type: Blog\n    url: https://blogs.oracle.com/weblogicserver/\n\
  \  - type: Website\n    url: https://www.oracle.com/middleware/technologies/weblogic.html\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: GitHub Organization\n    url: https://github.com/oracle\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/weblogic\n  - type: YouTube\n    url: https://www.youtube.com/@OracleDevelopers\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Application Server\n  - Enterprise\n  - Java EE\n  - Middleware\n  - Oracle\n  - WebLogic\n"
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
