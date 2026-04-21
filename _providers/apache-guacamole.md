---
api_count: 2
apis:
- description: REST API for managing connections, users, groups, and active sessions in Apache Guacamole remote desktop gateway, with token-based authentication and per-data-source resource management.
  name: Apache Guacamole REST API
  slug: apache-guacamole-rest-api
- description: JavaScript client library for embedding the Guacamole remote desktop client in web applications, with APIs for protocol tunneling, display rendering, and user input handling.
  name: Apache Guacamole JavaScript Client API
  slug: apache-guacamole-javascript-api
capabilities:
- description: Unified capability for managing Apache Guacamole remote desktop gateway — managing connections, users, groups, and monitoring active sessions. Designed for IT administrators and security teams managin
  name: Apache Guacamole Remote Access
  slug: guacamole-remote-access
common:
- title: ''
  type: Documentation
  url: https://guacamole.apache.org/doc/gug/
- title: ''
  type: GettingStarted
  url: https://guacamole.apache.org/doc/gug/users-guide.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/guacamole-client
- title: ''
  type: SpectralRules
  url: rules/apache-guacamole-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-guacamole-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/guacamole-remote-access.yaml
created: '2026-03-16'
description: Apache Guacamole is a clientless remote desktop gateway that supports standard protocols like VNC, RDP, and SSH. It requires no plugins or client software and provides access to remote desktops through a web browser with a comprehensive REST API for connection, user, and session management.
features:
- description: Access remote desktops through any HTML5 web browser with no client software or plugins required.
  name: Clientless Remote Desktop
- description: Supports VNC, RDP, SSH, and Telnet protocols through a unified web gateway.
  name: Multi-Protocol Support
- description: Stateless REST API authentication using time-limited tokens from the /api/tokens endpoint.
  name: Token-Based Authentication
- description: REST API for creating, updating, and organizing remote desktop connections and connection groups.
  name: Connection Management
- description: Fine-grained user and group permissions for controlling access to connections and administrative functions.
  name: User and Group Management
- description: Monitor and terminate active remote desktop sessions through the REST API.
  name: Active Session Monitoring
- description: Audit log of all remote desktop sessions with timestamps and user attribution.
  name: Connection History
- description: Java extension API for implementing custom authentication providers, event listeners, and protocol extensions.
  name: Extension API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Runs as a Java web application on Apache Tomcat or any Java Servlet container.
  name: Apache Tomcat
- description: LDAP extension for authenticating users against directory services like Active Directory.
  name: LDAP / Active Directory
- description: Multi-factor authentication extensions supporting TOTP apps and Duo Security.
  name: TOTP / Duo MFA
- description: Database authentication extensions for storing connections and users in relational databases.
  name: MySQL / PostgreSQL
- description: Guacamole can be deployed on Kubernetes with the guacamole-client Docker image.
  name: Kubernetes
jsonld:
- class_count: 9
  name: Apache Guacamole Rest Context
  property_count: 17
  slug: apache-guacamole-rest-context
layout: provider
modified: '2026-04-19'
name: Apache Guacamole
rules:
- name: Apache Guacamole API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: apache-guacamole-spectral-rules
skills: []
slug: apache-guacamole
solutions: []
tags:
- Apache
- Open Source
- RDP
- Remote Access
- Remote Desktop
- SSH
- VNC
- Web Gateway
url: https://raw.githubusercontent.com/api-evangelist/apache-guacamole/refs/heads/main/apis.yml
use_cases:
- description: Provide browser-based access to Linux and Windows desktops for remote workers.
  name: Remote Desktop Access
- description: Access cloud VMs and servers through SSH and RDP via browser without installing VPN or client software.
  name: Cloud Server Management
- description: Use Guacamole as a protocol-proxying bastion host to isolate internal systems from direct network access.
  name: Secure Bastion Host
- description: Provide developers with browser-based access to containerized or virtualized development environments.
  name: Development Environment Access
- description: Enable IT helpdesk teams to access and troubleshoot user desktops through the browser.
  name: IT Support Tooling
---
