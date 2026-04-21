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
