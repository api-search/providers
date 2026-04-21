---
api_count: 2
apis:
- description: Status and monitoring API for Apache HTTP Server (httpd) provided by mod_status, exposing server metrics, worker state, and load balancer information via HTTP endpoints.
  name: Apache HTTP Server Status API
  slug: apache-httpd-status-api
- description: Configuration directive reference for Apache HTTP Server covering VirtualHost, mod_ssl, mod_rewrite, mod_proxy, and all core directives for web server, proxy, and SSL configuration.
  name: Apache HTTP Server Configuration Reference
  slug: apache-httpd-config-api
capabilities:
- description: ''
  name: Httpd Server Monitoring
  slug: httpd-server-monitoring
common:
- title: ''
  type: Documentation
  url: https://httpd.apache.org/docs/current/
- title: ''
  type: GettingStarted
  url: https://httpd.apache.org/docs/current/getting-started.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/httpd
- title: ''
  type: SpectralRules
  url: rules/apache-httpd-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-httpd-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/httpd-server-monitoring.yaml
created: '2026-03-16'
description: Apache HTTP Server (httpd) is the world's most widely used web server software. It serves static and dynamic content, acts as a reverse proxy and load balancer, and exposes a mod_status monitoring API and balancer-manager management interface for operational visibility.
features:
- description: Real-time server status endpoint providing request rates, worker states, and CPU usage.
  name: mod_status Monitoring
- description: Full-featured reverse proxy with HTTP, HTTPS, WebSocket, and AJP protocol support.
  name: mod_proxy Reverse Proxy
- description: Load balancing across backend servers with byrequests, bytraffic, and bybusyness algorithms.
  name: mod_proxy_balancer Load Balancing
- description: TLS/SSL termination with client certificate authentication and OCSP stapling support.
  name: mod_ssl TLS Termination
- description: Powerful rule-based URL rewriting engine for redirects, proxying, and access control.
  name: mod_rewrite URL Rewriting
- description: Name-based and IP-based virtual hosting for serving multiple domains from a single server.
  name: Virtual Hosting
- description: CGI and FastCGI support for dynamic content generation with external applications.
  name: CGI and FastCGI
- description: Per-directory configuration files for decentralized access control and configuration.
  name: .htaccess Per-Directory Config
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Embeds PHP interpreter directly in the Apache process for PHP application hosting.
  name: mod_php
- description: AJP protocol integration with Apache Tomcat for Java web application proxying.
  name: Tomcat AJP Connector
- description: Automated TLS certificate provisioning with Certbot and the mod_md module.
  name: Let's Encrypt / Certbot
- description: Often deployed alongside Nginx, with Nginx handling static files and Apache handling dynamic content.
  name: Nginx
- description: ModSecurity web application firewall module for OWASP rule-based request filtering.
  name: ModSecurity WAF
jsonld:
- class_count: 26
  name: Apache Httpd Status Context
  property_count: 0
  slug: apache-httpd-status-context
layout: provider
modified: '2026-04-19'
name: Apache HTTP Server
rules:
- name: Apache HTTP Server API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 4
  slug: apache-httpd-spectral-rules
skills: []
slug: apache-httpd
solutions: []
tags:
- Apache
- Load Balancer
- Open Source
- Proxy
- Reverse Proxy
- Web Server
url: https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml
use_cases:
- description: Serve HTML, CSS, JavaScript, and media files with high performance and caching headers.
  name: Static Web Hosting
- description: Proxy requests to application servers (Node.js, Python, Java) with SSL termination.
  name: Reverse Proxy for Applications
- description: Distribute traffic across multiple backend application instances with health checking.
  name: Load Balancing
- description: Route and transform API requests using mod_rewrite and mod_proxy rules.
  name: API Gateway
- description: Run legacy CGI or PHP applications via mod_cgi, mod_fcgid, or mod_php.
  name: Legacy CGI Application Hosting
---
