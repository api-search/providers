---
api_count: 2
api_specs:
- filename: tomcat-manager-openapi.yml
  format: yaml
  label: Apache Tomcat Manager API
  slug: tomcat-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/openapi/tomcat-manager-openapi.yml
apis:
- description: The Apache Tomcat Manager application provides an HTTP text interface for deploying, undeploying, starting, stopping, and reloading web applications. Also includes session management, server status, t
  name: Apache Tomcat Manager API
  slug: tomcat-manager-api
- description: The Apache Tomcat JMX Proxy Servlet provides HTTP-based access to JMX MBeans for querying, getting, setting, and invoking operations on server management beans. Useful for server diagnostics, performa
  name: Apache Tomcat JMX Proxy API
  slug: tomcat-jmx-proxy-api
capabilities:
- description: Unified capability for deploying, managing, and monitoring Java web applications on Apache Tomcat. Covers application deployment, lifecycle management (start/stop/reload), session management, server d
  name: Apache Tomcat Application Management
  slug: application-management
common:
- title: ''
  type: Website
  url: https://tomcat.apache.org/
- title: ''
  type: Documentation
  url: https://tomcat.apache.org/tomcat-10.1-doc/
- title: ''
  type: Manager API Documentation
  url: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html
- title: ''
  type: Downloads
  url: https://tomcat.apache.org/download-10.cgi
- title: ''
  type: GitHub Repository
  url: https://github.com/apache/tomcat
- title: ''
  type: Apache Software Foundation
  url: https://www.apache.org/
- title: ''
  type: Mailing Lists
  url: https://tomcat.apache.org/lists.html
- title: ''
  type: Security
  url: https://tomcat.apache.org/security.html
- title: ''
  type: Changelog
  url: https://tomcat.apache.org/tomcat-10.1-doc/changelog.html
created: '2025-01-01'
description: Apache Tomcat is an open-source implementation of the Jakarta Servlet, Jakarta Server Pages, and other Jakarta EE technologies, providing a pure Java HTTP web server environment for running Java code. The Tomcat Manager application exposes an HTTP API for deploying, managing, and monitoring web applications. The JMX Proxy Servlet provides programmatic access to JMX MBeans for server diagnostics and configuration. Governed by the Apache Software Foundation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Tomcat Context
  property_count: 1
  slug: tomcat-context
layout: provider
modified: '2026-05-03'
name: Apache Tomcat
rules:
- name: Apache Tomcat API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 3
  slug: tomcat-rules
skills: []
slug: tomcat
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tomcat\nname: Apache Tomcat\ndescription: >-\n  Apache Tomcat is an open-source implementation of the Jakarta Servlet, Jakarta Server\n  Pages, and other Jakarta EE technologies, providing a pure Java HTTP web server\n  environment for running Java code. The Tomcat Manager application exposes an HTTP API\n  for deploying, managing, and monitoring web applications. The JMX Proxy Servlet provides\n  programmatic access to JMX MBeans for server diagnostics and configuration. Governed\n  by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Server\n  - Java\n  - Servlet Container\n  - Web Server\n  - Open Source\n  - Apache\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tomcat:tomcat-manager-api\n \
  \   name: Apache Tomcat Manager API\n    description: >-\n      The Apache Tomcat Manager application provides an HTTP text interface for\n      deploying, undeploying, starting, stopping, and reloading web applications.\n      Also includes session management, server status, thread dumps, VM information,\n      SSL/TLS configuration reload, memory leak detection, and configuration saving.\n      Authentication requires roles defined in tomcat-users.xml.\n    humanURL: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html\n    baseURL: http://localhost:8080/manager\n    tags:\n      - Java\n      - Web Server\n      - Application Deployment\n      - Server Management\n    properties:\n      - type: Documentation\n        url: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/openapi/tomcat-manager-openapi.yml\n      - type: NaftikoCapabilities\n \
  \       url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/capabilities/application-management.yaml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/rules/tomcat-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/vocabulary/tomcat-vocabulary.yml\n  - aid: tomcat:tomcat-jmx-proxy-api\n    name: Apache Tomcat JMX Proxy API\n    description: >-\n      The Apache Tomcat JMX Proxy Servlet provides HTTP-based access to JMX MBeans\n      for querying, getting, setting, and invoking operations on server management\n      beans. Useful for server diagnostics, performance monitoring, and dynamic\n      configuration changes without restarting Tomcat.\n    humanURL: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet\n    baseURL: http://localhost:8080/manager/jmxproxy\n\
  \    tags:\n      - JMX\n      - Monitoring\n      - Java\n      - Diagnostics\n    properties:\n      - type: Documentation\n        url: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html#Using_the_JMX_Proxy_Servlet\nfeatures:\n  - Web application deployment via WAR files\n  - Application lifecycle management (start/stop/reload/undeploy)\n  - Session management and expiration\n  - Server status and diagnostics\n  - JMX MBean access via HTTP proxy\n  - SSL/TLS configuration reload\n  - Memory leak detection\n  - Thread dumps\n  - VM information\n  - Configuration persistence\nuseCases:\n  - Automated application deployment\n  - CI/CD pipeline integration\n  - Production server monitoring\n  - Application health checking\n  - Dynamic SSL certificate updates\nsolutions:\n  - DevOps automation\n  - Java application hosting\n  - Enterprise middleware management\ncommon:\n  - type: Website\n    url: https://tomcat.apache.org/\n  - type: Documentation\n    url: https://tomcat.apache.org/tomcat-10.1-doc/\n\
  \  - type: Manager API Documentation\n    url: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html\n  - type: Downloads\n    url: https://tomcat.apache.org/download-10.cgi\n  - type: GitHub Repository\n    url: https://github.com/apache/tomcat\n  - type: Apache Software Foundation\n    url: https://www.apache.org/\n  - type: Mailing Lists\n    url: https://tomcat.apache.org/lists.html\n  - type: Security\n    url: https://tomcat.apache.org/security.html\n  - type: Changelog\n    url: https://tomcat.apache.org/tomcat-10.1-doc/changelog.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml
tags:
- Application Server
- Java
- Servlet Container
- Web Server
- Open Source
- Apache
url: https://raw.githubusercontent.com/api-evangelist/tomcat/refs/heads/main/apis.yml
use_cases: []
---
