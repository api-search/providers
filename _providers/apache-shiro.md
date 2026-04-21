---
api_count: 1
apis:
- description: Shiro provides a Java API for authentication (login/logout), authorization (access control), cryptography (hashing/encryption), and session management, with support for web applications, REST APIs, an
  name: Apache Shiro
  slug: apache-shiro
capabilities:
- description: ''
  name: Shiro Workflow
  slug: shiro-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/shiro
- title: ''
  type: Documentation
  url: https://shiro.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-shiro-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-shiro-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shiro-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-shiro-context.jsonld
created: '2026-03-16'
description: Apache Shiro is a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management. It provides a clean API for securing applications from the smallest mobile applications to the largest enterprise systems.
features:
- description: Pluggable authentication with username/password, remember-me, and token support
  name: Authentication
- description: Role-based and permission-based access control with wildcard permissions
  name: Authorization
- description: Native session management independent of HTTP containers
  name: Session Management
- description: Password hashing with salt, bcrypt, Argon2, and SHA-256
  name: Cryptography
- description: JDBC, LDAP, properties file, and custom realm support
  name: Multiple Realms
- description: Filter-based web application security with URL pattern matching
  name: Web Integration
- description: AOP and annotation-based security for method-level authorization
  name: Annotations
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Shiro Spring integration for bean-level security
  name: Spring Framework
- description: Java EE web filter integration for servlet containers
  name: Jakarta EE
- description: LDAP realm for enterprise user directory authentication
  name: LDAP/Active Directory
- description: Database-backed realm for user and permission storage
  name: JDBC
- description: Distributed session management with Hazelcast
  name: Hazelcast
jsonld:
- class_count: 12
  name: Apache Shiro Context
  property_count: 26
  slug: apache-shiro-context
layout: provider
modified: '2026-04-19'
name: Apache Shiro
rules:
- name: Apache Shiro API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-shiro-spectral-rules
skills: []
slug: apache-shiro
solutions: []
tags:
- Authentication
- Authorization
- Cryptography
- Java
- Security
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/apis.yml
use_cases:
- description: Secure Java web applications with authentication and URL-based access control
  name: Web Application Security
- description: Protect REST APIs with token authentication and permission checks
  name: REST API Security
- description: Stateless JWT authentication for microservice architectures
  name: Microservice Auth
- description: Role-based admin interface with fine-grained permissions
  name: Admin Portal Security
---
