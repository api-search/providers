---
api_count: 1
api_specs:
- filename: apache-shiro-rest-api.yaml
  format: yaml
  label: Apache Shiro
  slug: apache-shiro
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/openapi/apache-shiro-rest-api.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-shiro\nname: Apache Shiro\ndescription: >-\n  Apache Shiro is a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management. It provides a clean API for securing applications\n  from the smallest mobile applications to the largest enterprise systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Authentication\n- Authorization\n- Cryptography\n- Java\n- Security\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-shiro:apache-shiro\n  name: Apache Shiro\n  description: >-\n    Shiro provides a Java API for authentication (login/logout), authorization (access control), cryptography (hashing/encryption), and session management, with\
  \ support for web applications, REST APIs,\n    and standalone applications.\n  humanURL: https://shiro.apache.org/documentation.html\n  tags:\n  - Authentication\n  - Authorization\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://shiro.apache.org/documentation.html\n  - type: OpenAPI\n    url: openapi/apache-shiro-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/shiro\n- type: Documentation\n  url: https://shiro.apache.org/\n- type: SpectralRules\n  url: rules/apache-shiro-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-shiro-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shiro-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-shiro-context.jsonld\n- type: Features\n  data:\n  - name: Authentication\n    description: Pluggable authentication with username/password, remember-me, and token support\n  - name:\
  \ Authorization\n    description: Role-based and permission-based access control with wildcard permissions\n  - name: Session Management\n    description: Native session management independent of HTTP containers\n  - name: Cryptography\n    description: Password hashing with salt, bcrypt, Argon2, and SHA-256\n  - name: Multiple Realms\n    description: JDBC, LDAP, properties file, and custom realm support\n  - name: Web Integration\n    description: Filter-based web application security with URL pattern matching\n  - name: Annotations\n    description: AOP and annotation-based security for method-level authorization\n- type: UseCases\n  data:\n  - name: Web Application Security\n    description: Secure Java web applications with authentication and URL-based access control\n  - name: REST API Security\n    description: Protect REST APIs with token authentication and permission checks\n  - name: Microservice Auth\n    description: Stateless JWT authentication for microservice architectures\n\
  \  - name: Admin Portal Security\n    description: Role-based admin interface with fine-grained permissions\n- type: Integrations\n  data:\n  - name: Spring Framework\n    description: Shiro Spring integration for bean-level security\n  - name: Jakarta EE\n    description: Java EE web filter integration for servlet containers\n  - name: LDAP/Active Directory\n    description: LDAP realm for enterprise user directory authentication\n  - name: JDBC\n    description: Database-backed realm for user and permission storage\n  - name: Hazelcast\n    description: Distributed session management with Hazelcast\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/apis.yml
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
