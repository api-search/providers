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
source_yaml: "aid: apache-httpd\nname: Apache HTTP Server\ndescription: >-\n  Apache HTTP Server (httpd) is the world's most widely used web server software. It serves static and dynamic content, acts as a reverse proxy and load balancer, and exposes a mod_status monitoring API and balancer-manager management interface for operational visibility.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache\n  - Load Balancer\n  - Open Source\n  - Proxy\n  - Reverse Proxy\n  - Web Server\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-httpd:apache-httpd-status-api\n    name: Apache HTTP Server Status API\n    description: >-\n      Status and monitoring API for Apache HTTP Server (httpd) provided by mod_status, exposing server metrics, worker state,\
  \ and load balancer information via HTTP endpoints.\n    humanURL: https://httpd.apache.org/docs/current/mod/mod_status.html\n    baseURL: http://localhost:80\n    tags:\n      - Balancer\n      - Metrics\n      - Monitoring\n      - REST\n      - Status\n    properties:\n      - type: Documentation\n        url: https://httpd.apache.org/docs/current/mod/mod_status.html\n      - type: OpenAPI\n        url: openapi/apache-httpd-status-openapi.yml\n      - type: JSONSchema\n        url: json-schema/httpd-serverstatus-schema.json\n      - type: JSON-LD\n        url: json-ld/apache-httpd-status-context.jsonld\n\n  - aid: apache-httpd:apache-httpd-config-api\n    name: Apache HTTP Server Configuration Reference\n    description: >-\n      Configuration directive reference for Apache HTTP Server covering VirtualHost, mod_ssl, mod_rewrite, mod_proxy, and all core directives for web server, proxy, and SSL configuration.\n    humanURL: https://httpd.apache.org/docs/current/mod/directives.html\n\
  \    tags:\n      - Configuration\n      - Reference\n    properties:\n      - type: Documentation\n        url: https://httpd.apache.org/docs/current/mod/directives.html\n\ncommon:\n  - type: Documentation\n    url: https://httpd.apache.org/docs/current/\n  - type: GettingStarted\n    url: https://httpd.apache.org/docs/current/getting-started.html\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/httpd\n  - type: SpectralRules\n    url: rules/apache-httpd-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-httpd-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/httpd-server-monitoring.yaml\n  - type: Features\n    data:\n      - name: mod_status Monitoring\n        description: Real-time server status endpoint providing request rates, worker states, and CPU usage.\n      - name: mod_proxy Reverse Proxy\n        description: Full-featured reverse proxy with HTTP, HTTPS, WebSocket,\
  \ and AJP protocol support.\n      - name: mod_proxy_balancer Load Balancing\n        description: Load balancing across backend servers with byrequests, bytraffic, and bybusyness algorithms.\n      - name: mod_ssl TLS Termination\n        description: TLS/SSL termination with client certificate authentication and OCSP stapling support.\n      - name: mod_rewrite URL Rewriting\n        description: Powerful rule-based URL rewriting engine for redirects, proxying, and access control.\n      - name: Virtual Hosting\n        description: Name-based and IP-based virtual hosting for serving multiple domains from a single server.\n      - name: CGI and FastCGI\n        description: CGI and FastCGI support for dynamic content generation with external applications.\n      - name: .htaccess Per-Directory Config\n        description: Per-directory configuration files for decentralized access control and configuration.\n  - type: UseCases\n    data:\n      - name: Static Web Hosting\n        description:\
  \ Serve HTML, CSS, JavaScript, and media files with high performance and caching headers.\n      - name: Reverse Proxy for Applications\n        description: Proxy requests to application servers (Node.js, Python, Java) with SSL termination.\n      - name: Load Balancing\n        description: Distribute traffic across multiple backend application instances with health checking.\n      - name: API Gateway\n        description: Route and transform API requests using mod_rewrite and mod_proxy rules.\n      - name: Legacy CGI Application Hosting\n        description: Run legacy CGI or PHP applications via mod_cgi, mod_fcgid, or mod_php.\n  - type: Integrations\n    data:\n      - name: mod_php\n        description: Embeds PHP interpreter directly in the Apache process for PHP application hosting.\n      - name: Tomcat AJP Connector\n        description: AJP protocol integration with Apache Tomcat for Java web application proxying.\n      - name: Let's Encrypt / Certbot\n        description:\
  \ Automated TLS certificate provisioning with Certbot and the mod_md module.\n      - name: Nginx\n        description: Often deployed alongside Nginx, with Nginx handling static files and Apache handling dynamic content.\n      - name: ModSecurity WAF\n        description: ModSecurity web application firewall module for OWASP rule-based request filtering.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-httpd/refs/heads/main/apis.yml
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
