---
api_count: 5
api_specs:
- filename: OpenAPI.yaml
  format: yaml
  label: JBoss EAP Management API
  slug: jboss-eap-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/wildfly/wildfly/main/docs/src/main/asciidoc/_admin-guide/management-api/OpenAPI.yaml
- filename: openapi.json
  format: json
  label: Keycloak Admin REST API
  slug: keycloak-admin-rest-api
  spec_type: OpenAPI
  url: https://www.keycloak.org/docs-api/latest/rest-api/openapi.json
apis:
- description: RESTful management API for JBoss Enterprise Application Platform (EAP) administration and monitoring of server configuration, deployments, and runtime state.
  name: JBoss EAP Management API
  slug: jboss-eap-management-api
- description: RESTful interface for WildFly (the community version of JBoss EAP) server management, deployments, and runtime configuration.
  name: WildFly REST API
  slug: wildfly-rest-api
- description: REST API for distributed in-memory caching with JBoss Data Grid (Red Hat Data Grid), based on the Infinispan project.
  name: JBoss Data Grid REST API
  slug: jboss-data-grid-rest-api
- description: Administration REST API for Keycloak identity and access management, supporting OAuth2, OpenID Connect, and SAML for SSO scenarios.
  name: Keycloak Admin REST API
  slug: keycloak-admin-rest-api
- description: REST DSL for Apache Camel integration in JBoss Fuse, enabling definition of REST endpoints and routes for enterprise integration patterns.
  name: JBoss Fuse REST DSL
  slug: jboss-fuse-rest-dsl
common:
- title: ''
  type: Portal
  url: https://developers.redhat.com/products/eap/overview
- title: ''
  type: Getting Started
  url: https://www.jboss.org/get-started/
- title: ''
  type: Blog
  url: https://www.jboss.org/posts/
- title: ''
  type: GitHub Organization
  url: https://github.com/jbossas
- title: ''
  type: Support
  url: https://access.redhat.com/support/
created: '2024-01-15'
description: JBoss is a division of Red Hat providing open source middleware and application server technologies for enterprise Java workloads. The JBoss product portfolio includes JBoss EAP (Enterprise Application Platform), the WildFly community application server, JBoss Data Grid (Red Hat Data Grid), Keycloak identity and access management, and JBoss Fuse integration platform built on Apache Camel. These projects power Jakarta EE deployments, single sign-on, distributed caching, and microservices integration in enterprise environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: JBoss
skills: []
slug: jboss
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jboss\nname: JBoss\ndescription: >-\n  JBoss is a division of Red Hat providing open source middleware and\n  application server technologies for enterprise Java workloads. The JBoss\n  product portfolio includes JBoss EAP (Enterprise Application Platform), the\n  WildFly community application server, JBoss Data Grid (Red Hat Data Grid),\n  Keycloak identity and access management, and JBoss Fuse integration platform\n  built on Apache Camel. These projects power Jakarta EE deployments, single\n  sign-on, distributed caching, and microservices integration in enterprise\n  environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Server\n  - Cloud Native\n  - Enterprise\n  - Jakarta EE\n  - Java EE\n  - Microservices\n  - Middleware\n  - Open Source\n  - Red Hat\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/jboss/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\n\
  specificationVersion: '0.19'\napis:\n  - aid: jboss:jboss-eap-management-api\n    name: JBoss EAP Management API\n    description: >-\n      RESTful management API for JBoss Enterprise Application Platform (EAP)\n      administration and monitoring of server configuration, deployments,\n      and runtime state.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_jboss_enterprise_application_platform\n    tags:\n      - Application Server\n      - Management\n      - Middleware\n    properties:\n      - type: Documentation\n        url: https://docs.jboss.org/author/display/WFLY/Management+API+reference\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/wildfly/wildfly/main/docs/src/main/asciidoc/_admin-guide/management-api/OpenAPI.yaml\n      - type: Authentication\n        url: https://access.redhat.com/documentation/en-us/red_hat_jboss_enterprise_application_platform/7.4/html/configuration_guide/management_api_reference\n  - aid: jboss:wildfly-rest-api\n\
  \    name: WildFly REST API\n    description: >-\n      RESTful interface for WildFly (the community version of JBoss EAP)\n      server management, deployments, and runtime configuration.\n    humanURL: https://wildfly.org\n    tags:\n      - Application Server\n      - Management\n      - WildFly\n    properties:\n      - type: Documentation\n        url: https://docs.wildfly.org/\n      - type: GitHub\n        url: https://github.com/wildfly/wildfly\n      - type: Reference\n        url: https://docs.wildfly.org/management-api/\n  - aid: jboss:jboss-data-grid-rest-api\n    name: JBoss Data Grid REST API\n    description: >-\n      REST API for distributed in-memory caching with JBoss Data Grid\n      (Red Hat Data Grid), based on the Infinispan project.\n    humanURL: https://access.redhat.com/products/red-hat-data-grid\n    tags:\n      - Cache\n      - Data Grid\n      - Distributed Systems\n      - In-Memory\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_data_grid/8.4/html/data_grid_rest_api\n\
  \      - type: Reference\n        url: https://infinispan.org/docs/stable/titles/rest/rest.html\n  - aid: jboss:keycloak-admin-rest-api\n    name: Keycloak Admin REST API\n    description: >-\n      Administration REST API for Keycloak identity and access management,\n      supporting OAuth2, OpenID Connect, and SAML for SSO scenarios.\n    humanURL: https://www.keycloak.org\n    tags:\n      - Authentication\n      - Authorization\n      - Identity Management\n      - OAuth2\n      - OpenID Connect\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://www.keycloak.org/docs/latest/server_development/#admin-rest-api\n      - type: OpenAPI\n        url: https://www.keycloak.org/docs-api/latest/rest-api/openapi.json\n      - type: GitHub\n        url: https://github.com/keycloak/keycloak\n  - aid: jboss:jboss-fuse-rest-dsl\n    name: JBoss Fuse REST DSL\n    description: >-\n      REST DSL for Apache Camel integration in JBoss Fuse, enabling\n      definition of\
  \ REST endpoints and routes for enterprise integration\n      patterns.\n    humanURL: https://access.redhat.com/products/red-hat-fuse\n    tags:\n      - Camel\n      - ESB\n      - Integration\n      - Microservices\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_fuse/7.11/html/apache_camel_development_guide/basicprinciples-restdsl\n      - type: Reference\n        url: https://camel.apache.org/components/latest/rest-api-component.html\ncommon:\n  - type: Portal\n    url: https://developers.redhat.com/products/eap/overview\n  - type: Getting Started\n    url: https://www.jboss.org/get-started/\n  - type: Blog\n    url: https://www.jboss.org/posts/\n  - type: GitHub Organization\n    url: https://github.com/jbossas\n  - type: Support\n    url: https://access.redhat.com/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jboss/refs/heads/main/apis.yml
tags:
- Application Server
- Cloud Native
- Enterprise
- Jakarta EE
- Java EE
- Microservices
- Middleware
- Open Source
- Red Hat
url: https://raw.githubusercontent.com/api-evangelist/jboss/refs/heads/main/apis.yml
use_cases: []
---
