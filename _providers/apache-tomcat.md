---
api_count: 2
apis:
- description: 'The Tomcat Manager application provides an HTTP text protocol API for deploying, undeploying, starting, stopping, and reloading web applications remotely. Key endpoints include: /manager/text/list (li'
  name: Apache Tomcat Manager API
  slug: apache-tomcat-manager-api
- description: The Tomcat JMX API exposes management and monitoring beans for Connectors, Engines, Hosts, Contexts, Sessions, DataSources, thread pools, and memory via Java Management Extensions. JMX can be accessed
  name: Apache Tomcat JMX API
  slug: apache-tomcat-jmx-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tomcat
- title: ''
  type: Documentation
  url: https://tomcat.apache.org/tomcat-10.1-doc/
- title: ''
  type: Portal
  url: https://tomcat.apache.org/
- title: ''
  type: GettingStarted
  url: https://tomcat.apache.org/tomcat-10.1-doc/setup.html
- title: ''
  type: ReleaseNotes
  url: https://tomcat.apache.org/tomcat-10.1-doc/changelog.html
- title: ''
  type: Support
  url: https://tomcat.apache.org/lists.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2024-01-15'
description: Apache Tomcat is an open-source implementation of the Java Servlet, JavaServer Pages (JSP), Java Expression Language, and Java WebSocket technologies. It provides a pure Java HTTP web server and servlet container for hosting Java web applications. Tomcat exposes management APIs via the Manager application (HTTP text protocol), JMX for monitoring, and a Virtual Host Manager for configuration management. It is maintained by the Apache Software Foundation and is one of the most widely deployed Java application servers.
features:
- description: Jakarta Servlet 6.0 (formerly Java EE) compliant servlet container.
  name: Servlet Container
- description: JavaServer Pages compiler and runtime engine for dynamic HTML generation.
  name: JSP Engine
- description: Jakarta WebSocket 2.1 implementation for full-duplex browser-server communication.
  name: WebSocket Support
- description: HTTP/2 multiplexing and server push via APR/Native connector.
  name: HTTP/2 Support
- description: Built-in SSL/TLS support via JSSE or APR/OpenSSL connectors.
  name: SSL/TLS Termination
- description: DBCP2-based database connection pool management via JNDI DataSource.
  name: Connection Pooling
- description: Session replication across Tomcat cluster nodes via DeltaManager or BackupManager.
  name: Clustering
image: https://tomcat.apache.org/res/images/tomcat.png
integrations:
- description: Embedded Tomcat as the default servlet container in Spring Boot applications.
  name: Spring Boot
- description: mod_jk and mod_proxy_ajp for load balancing between Apache httpd and Tomcat.
  name: Apache HTTP Server
- description: Nginx reverse proxy for Tomcat with SSL termination and load balancing.
  name: Nginx
- description: JMX Exporter for exposing Tomcat metrics in Prometheus format.
  name: Prometheus
- description: Official Docker image for containerized Tomcat deployment.
  name: Docker
layout: provider
modified: '2026-04-19'
name: Apache Tomcat
skills: []
slug: apache-tomcat
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-tomcat\nname: Apache Tomcat\ndescription: >-\n  Apache Tomcat is an open-source implementation of the Java Servlet, JavaServer Pages (JSP),\n  Java Expression Language, and Java WebSocket technologies. It provides a pure Java HTTP web\n  server and servlet container for hosting Java web applications. Tomcat exposes management APIs\n  via the Manager application (HTTP text protocol), JMX for monitoring, and a Virtual Host Manager\n  for configuration management. It is maintained by the Apache Software Foundation and is one of\n  the most widely deployed Java application servers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://tomcat.apache.org/res/images/tomcat.png\ntags:\n  - Application Server\n  - Java\n  - JSP\n  - Open Source\n  - Servlet\n  - Web Server\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tomcat/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: apache-tomcat:apache-tomcat-manager-api\n    name: Apache Tomcat Manager API\n    description: >-\n      The Tomcat Manager application provides an HTTP text protocol API for deploying, undeploying,\n      starting, stopping, and reloading web applications remotely. Key endpoints include:\n      /manager/text/list (list deployed apps), /manager/text/deploy (deploy a WAR file),\n      /manager/text/undeploy, /manager/text/start, /manager/text/stop, /manager/text/reload,\n      /manager/text/sessions (session statistics), and /manager/text/serverinfo. Requires\n      manager-script role authentication.\n    humanURL: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html\n    tags:\n      - Administration\n      - Deployment\n      - Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://tomcat.apache.org/tomcat-10.1-doc/manager-howto.html\n  - aid: apache-tomcat:apache-tomcat-jmx-api\n    name: Apache Tomcat JMX API\n    description:\
  \ >-\n      The Tomcat JMX API exposes management and monitoring beans for Connectors, Engines, Hosts,\n      Contexts, Sessions, DataSources, thread pools, and memory via Java Management Extensions.\n      JMX can be accessed via JConsole, Java VisualVM, or remote JMX clients. Prometheus JMX\n      Exporter can expose Tomcat metrics in Prometheus format via HTTP endpoint.\n    humanURL: https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html\n    tags:\n      - JMX\n      - Monitoring\n      - Management\n      - Java\n    properties:\n      - type: Documentation\n        url: https://tomcat.apache.org/tomcat-10.1-doc/monitoring.html\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/tomcat\n  - type: Documentation\n    url: https://tomcat.apache.org/tomcat-10.1-doc/\n  - type: Portal\n    url: https://tomcat.apache.org/\n  - type: GettingStarted\n    url: https://tomcat.apache.org/tomcat-10.1-doc/setup.html\n  - type: ReleaseNotes\n    url: https://tomcat.apache.org/tomcat-10.1-doc/changelog.html\n\
  \  - type: Support\n    url: https://tomcat.apache.org/lists.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Servlet Container\n        description: Jakarta Servlet 6.0 (formerly Java EE) compliant servlet container.\n      - name: JSP Engine\n        description: JavaServer Pages compiler and runtime engine for dynamic HTML generation.\n      - name: WebSocket Support\n        description: Jakarta WebSocket 2.1 implementation for full-duplex browser-server communication.\n      - name: HTTP/2 Support\n        description: HTTP/2 multiplexing and server push via APR/Native connector.\n      - name: SSL/TLS Termination\n        description: Built-in SSL/TLS support via JSSE or APR/OpenSSL connectors.\n      - name: Connection Pooling\n        description: DBCP2-based database connection pool management via JNDI DataSource.\n      - name: Clustering\n        description: Session replication across Tomcat cluster nodes\
  \ via DeltaManager or BackupManager.\n  - type: UseCases\n    data:\n      - name: Java Web Application Hosting\n        description: Deploy and host Java Servlet/JSP web applications.\n      - name: API Gateway Backend\n        description: Host REST API backends built with Spring MVC, JAX-RS, or plain servlets.\n      - name: Microservices Container\n        description: Embedded Tomcat in Spring Boot for microservices deployment.\n      - name: Legacy Application Migration\n        description: Host Java EE applications during cloud migration.\n  - type: Integrations\n    data:\n      - name: Spring Boot\n        description: Embedded Tomcat as the default servlet container in Spring Boot applications.\n      - name: Apache HTTP Server\n        description: mod_jk and mod_proxy_ajp for load balancing between Apache httpd and Tomcat.\n      - name: Nginx\n        description: Nginx reverse proxy for Tomcat with SSL termination and load balancing.\n      - name: Prometheus\n        description:\
  \ JMX Exporter for exposing Tomcat metrics in Prometheus format.\n      - name: Docker\n        description: Official Docker image for containerized Tomcat deployment.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tomcat/refs/heads/main/apis.yml
tags:
- Application Server
- Java
- JSP
- Open Source
- Servlet
- Web Server
url: https://raw.githubusercontent.com/api-evangelist/apache-tomcat/refs/heads/main/apis.yml
use_cases:
- description: Deploy and host Java Servlet/JSP web applications.
  name: Java Web Application Hosting
- description: Host REST API backends built with Spring MVC, JAX-RS, or plain servlets.
  name: API Gateway Backend
- description: Embedded Tomcat in Spring Boot for microservices deployment.
  name: Microservices Container
- description: Host Java EE applications during cloud migration.
  name: Legacy Application Migration
---
