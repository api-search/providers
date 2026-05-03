---
api_count: 5
api_specs:
- filename: oracle-weblogic-management-openapi.yml
  format: yaml
  label: WebLogic RESTful Management Services API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-management-openapi.yml
- filename: oracle-weblogic-monitoring-openapi.yml
  format: yaml
  label: WebLogic Monitoring and Diagnostics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-monitoring-openapi.yml
- filename: oracle-weblogic-deployment-openapi.yml
  format: yaml
  label: WebLogic Deployment API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/openapi/oracle-weblogic-deployment-openapi.yml
apis:
- description: RESTful API for managing and monitoring WebLogic Server domains, servers, applications, and resources.
  name: WebLogic RESTful Management Services API
  slug: ''
- description: API for accessing runtime monitoring data, diagnostics information, and performance metrics.
  name: WebLogic Monitoring and Diagnostics API
  slug: ''
- description: API for deploying, undeploying, and managing application deployments on WebLogic Server.
  name: WebLogic Deployment API
  slug: ''
- description: Python-based scripting interface for automating WebLogic Server administration tasks.
  name: WebLogic WLST (WebLogic Scripting Tool) API
  slug: ''
- description: Java Management Extensions API for programmatic management and monitoring of WebLogic Server.
  name: WebLogic JMX API
  slug: ''
common:
- title: ''
  type: Support
  url: https://support.oracle.com/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/
- title: ''
  type: Downloads
  url: https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html
- title: ''
  type: Community
  url: https://community.oracle.com/customerconnect/categories/appsuite-weblogic-server
- title: ''
  type: License
  url: https://www.oracle.com/downloads/licenses/standard-license.html
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
  type: Sign Up
  url: https://cloud.oracle.com/
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
created: '2024'
description: APIs for managing and monitoring Oracle WebLogic Server - a leading platform for building and deploying enterprise Java applications.
features: []
image: https://www.oracle.com/a/ocom/img/weblogic-server.png
integrations: []
jsonld:
- class_count: 40
  name: Oracle Weblogic Context
  property_count: 54
  slug: oracle-weblogic-context
layout: provider
modified: '2026-04-28'
name: Oracle WebLogic Server
skills: []
slug: oracle-weblogic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Oracle WebLogic Server\ndescription: >-\n  APIs for managing and monitoring Oracle WebLogic Server - a leading platform for\n  building and deploying enterprise Java applications.\nimage: https://www.oracle.com/a/ocom/img/weblogic-server.png\nurl: https://www.oracle.com/middleware/weblogic/\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Application Server\n  - Enterprise\n  - Java EE\n  - Middleware\n  - Oracle\napis:\n  - name: WebLogic RESTful Management Services API\n    description: >-\n      RESTful API for managing and monitoring WebLogic Server domains, servers, applications,\n      and resources.\n    image: https://www.oracle.com/a/ocom/img/weblogic-server.png\n    humanURL: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/index.html\n    baseURL: http://localhost:7001/management/weblogic/latest\n    tags:\n      - Management\n      - Monitoring\n      - REST\n    properties:\n      -\
  \ type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/index.html\n      - type: OpenAPI\n        url: openapi/oracle-weblogic-management-openapi.yml\n      - type: Authentication\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/authentication.html\n      - type: JSONSchema\n        url: json-schema/oracle-weblogic-server-configuration.json\n      - type: JSONSchema\n        url: json-schema/oracle-weblogic-data-source.json\n      - type: JSONSchema\n        url: json-schema/oracle-weblogic-jms-configuration.json\n      - type: JSON-LD\n        url: json-ld/oracle-weblogic-context.jsonld\n  - name: WebLogic Monitoring and Diagnostics API\n    description: >-\n      API for accessing runtime monitoring data, diagnostics information, and performance\n      metrics.\n    humanURL: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html\n\
  \    baseURL: http://localhost:7001/management/weblogic/latest/domainRuntime\n    tags:\n      - Diagnostics\n      - JMX\n      - Metrics\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html\n      - type: Guide\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlach/monitor.html\n      - type: OpenAPI\n        url: openapi/oracle-weblogic-monitoring-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-weblogic-domain-runtime.json\n  - name: WebLogic Deployment API\n    description: >-\n      API for deploying, undeploying, and managing application deployments on WebLogic\n      Server.\n    humanURL: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/op-management-weblogic-latest-edit-appdeployments-post.html\n    baseURL: http://localhost:7001/management/weblogic/latest/edit/appDeployments\n\
  \    tags:\n      - Applications\n      - Deployment\n      - Lifecycle\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlrest/resources.html\n      - type: Tutorial\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/depgd/index.html\n      - type: OpenAPI\n        url: openapi/oracle-weblogic-deployment-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-weblogic-deployment.json\n  - name: WebLogic WLST (WebLogic Scripting Tool) API\n    description: >-\n      Python-based scripting interface for automating WebLogic Server administration\n      tasks.\n    humanURL: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/index.html\n    baseURL: https://localhost:5556\n    tags:\n      - Administration\n      - Automation\n      - Python\n      - Scripting\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstc/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlstg/index.html\n  - name: WebLogic JMX API\n    description: >-\n      Java Management Extensions API for programmatic management and monitoring of\n      WebLogic Server.\n    humanURL: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html\n    baseURL: service:jmx:rmi:///jndi/rmi://localhost:7001/jmxrmi\n    tags:\n      - Java\n      - JMX\n      - Management\n      - MBeans\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/index.html\n      - type: API Reference\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/wlapi/index.html\n      - type: Examples\n        url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/12.2.1.4/jmxcu/examples.html\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Support\n    url: https://support.oracle.com/\n  - type: Documentation\n    url: https://docs.oracle.com/en/middleware/fusion-middleware/weblogic-server/\n  - type: Downloads\n    url: https://www.oracle.com/middleware/technologies/weblogic-server-downloads.html\n  - type: Community\n    url: https://community.oracle.com/customerconnect/categories/appsuite-weblogic-server\n  - type: License\n    url: https://www.oracle.com/downloads/licenses/standard-license.html\n  - type: Blog\n    url: https://blogs.oracle.com/weblogicserver/\n  - type: Website\n    url: https://www.oracle.com/middleware/technologies/weblogic.html\n  - type: Terms of Service\n    url: https://www.oracle.com/legal/terms.html\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\n  - type: GitHub Organization\n    url: https://github.com/oracle\n  - type: Stack Overflow\n    url:\
  \ https://stackoverflow.com/questions/tagged/weblogic\n  - type: YouTube\n    url: https://www.youtube.com/@OracleDevelopers\n  - type: Sign Up\n    url: https://cloud.oracle.com/\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-weblogic/refs/heads/main/apis.yml
tags:
- Application Server
- Enterprise
- Java EE
- Middleware
- Oracle
url: https://www.oracle.com/middleware/weblogic/
use_cases: []
---
