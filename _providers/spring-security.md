---
api_count: 6
api_specs:
- filename: spring-security-oauth2-openapi.yml
  format: yaml
  label: Spring Security OAuth2 API
  slug: spring-security-oauth2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/openapi/spring-security-oauth2-openapi.yml
- filename: spring-authorization-server-openapi.yml
  format: yaml
  label: Spring Authorization Server API
  slug: spring-authorization-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/openapi/spring-authorization-server-openapi.yml
apis:
- description: OAuth 2.0 and OpenID Connect support for Spring Security. Provides client registration, authorization code flow, token endpoint, token refresh, PKCE support, and resource server JWT validation.
  name: Spring Security OAuth2 API
  slug: spring-security-oauth2
- description: Spring's implementation of an OAuth 2.1 and OpenID Connect 1.0 authorization server. Provides issuing access tokens, refresh tokens, and ID tokens with support for PKCE, token introspection, and autho
  name: Spring Authorization Server API
  slug: spring-authorization-server
- description: Core security features for authentication and authorization. Provides UserDetailsService, password encoding, security context management, method security, and HTTP security configuration.
  name: Spring Security Core
  slug: spring-security-core
- description: SAML 2.0 Service Provider support for Spring Security. Enables SSO integration with SAML identity providers, handling authentication requests, assertions, and SLO (Single Logout).
  name: Spring Security SAML2
  slug: spring-security-saml
- description: LDAP authentication and authorization support for Spring Security. Supports LDAP bind authentication, password comparison, and user details loading from directory services.
  name: Spring Security LDAP
  slug: spring-security-ldap
- description: Reactive security for Spring WebFlux applications. Provides non-blocking authentication, authorization, OAuth2 reactive client support, and CSRF protection for reactive web stacks.
  name: Spring Security WebFlux
  slug: spring-security-webflux
capabilities:
- description: Workflow capability for Spring Security OAuth2 and OpenID Connect operations. Provides unified identity verification, token management, and access control operations. Used by platform admins, security
  name: Spring Security - Identity and Access Management
  slug: identity-and-access
common:
- title: ''
  type: Blog
  url: https://spring.io/blog/category/security
- title: ''
  type: Community
  url: https://stackoverflow.com/questions/tagged/spring-security
- title: ''
  type: Twitter
  url: https://twitter.com/SpringSecurity
- title: ''
  type: Issue Tracker
  url: https://github.com/spring-projects/spring-security/issues
- title: ''
  type: Contributing Guide
  url: https://github.com/spring-projects/spring-security/blob/main/CONTRIBUTING.adoc
- title: ''
  type: License
  url: https://github.com/spring-projects/spring-security/blob/main/LICENSE.txt
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/artifact/org.springframework.security
- title: ''
  type: Changelog
  url: https://github.com/spring-projects/spring-security/releases
created: '2024-01-15'
description: Spring Security is a powerful and highly customizable authentication and access-control framework for Java applications. It is the de-facto standard for securing Spring-based applications, providing comprehensive security services including authentication, authorization, protection against common exploits (CSRF, session fixation, clickjacking), OAuth 2.0, OpenID Connect, SAML 2.0, LDAP, and WebFlux reactive security.
features: []
image: https://spring.io/img/projects/spring-security.svg
integrations: []
jsonld:
- class_count: 5
  name: Spring Security Context
  property_count: 23
  slug: spring-security-context
layout: provider
modified: '2026-05-02'
name: Spring Security
rules:
- name: Spring Security API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 3
  slug: spring-security-rules
skills: []
slug: spring-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-security\nname: Spring Security\ndescription: >-\n  Spring Security is a powerful and highly customizable authentication and\n  access-control framework for Java applications. It is the de-facto standard\n  for securing Spring-based applications, providing comprehensive security\n  services including authentication, authorization, protection against common\n  exploits (CSRF, session fixation, clickjacking), OAuth 2.0, OpenID Connect,\n  SAML 2.0, LDAP, and WebFlux reactive security.\ntype: Index\nimage: https://spring.io/img/projects/spring-security.svg\nurl: https://spring.io/projects/spring-security\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Authentication\n  - Authorization\n  - Java\n  - JWT\n  - OAuth2\n  - OpenID Connect\n  - SAML\n  - Security\n  - Spring Framework\napis:\n  - aid: spring-security:spring-security-oauth2\n    name: Spring Security OAuth2 API\n    description: >-\n      OAuth 2.0 and OpenID Connect\
  \ support for Spring Security. Provides\n      client registration, authorization code flow, token endpoint, token\n      refresh, PKCE support, and resource server JWT validation.\n    humanURL: https://spring.io/projects/spring-security\n    baseURL: http://localhost:8080\n    tags:\n      - Authorization Server\n      - JWT\n      - OAuth2\n      - OpenID Connect\n      - Token\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html\n      - type: OAuth2 Client Documentation\n        url: https://docs.spring.io/spring-security/reference/servlet/oauth2/client/index.html\n      - type: OAuth2 Resource Server\n        url: https://docs.spring.io/spring-security/reference/servlet/oauth2/resource-server/index.html\n      - type: Authorization Server\n        url: https://spring.io/projects/spring-authorization-server\n      - type: OpenAPI\n        url: openapi/spring-security-oauth2-openapi.yml\n  - aid: spring-security:spring-authorization-server\n\
  \    name: Spring Authorization Server API\n    description: >-\n      Spring's implementation of an OAuth 2.1 and OpenID Connect 1.0 authorization\n      server. Provides issuing access tokens, refresh tokens, and ID tokens with\n      support for PKCE, token introspection, and authorization server metadata.\n    humanURL: https://spring.io/projects/spring-authorization-server\n    baseURL: http://localhost:9000\n    tags:\n      - Authorization Server\n      - OAuth2\n      - OpenID Connect\n      - Token Issuance\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-authorization-server/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-authorization-server\n      - type: Getting Started\n        url: https://docs.spring.io/spring-authorization-server/docs/current/reference/html/getting-started.html\n      - type: OpenAPI\n        url: openapi/spring-authorization-server-openapi.yml\n\
  \  - aid: spring-security:spring-security-core\n    name: Spring Security Core\n    description: >-\n      Core security features for authentication and authorization. Provides\n      UserDetailsService, password encoding, security context management,\n      method security, and HTTP security configuration.\n    humanURL: https://spring.io/projects/spring-security\n    baseURL: https://docs.spring.io/spring-security/site/docs/current/api/\n    tags:\n      - Authentication\n      - Authorization\n      - Core\n      - Method Security\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/\n      - type: API Reference\n        url: https://docs.spring.io/spring-security/site/docs/current/api/\n      - type: Getting Started\n        url: https://spring.io/guides/gs/securing-web/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-security\n      - type: Release Notes\n        url: https://github.com/spring-projects/spring-security/releases\n\
  \      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.security\n  - aid: spring-security:spring-security-saml\n    name: Spring Security SAML2\n    description: >-\n      SAML 2.0 Service Provider support for Spring Security. Enables SSO\n      integration with SAML identity providers, handling authentication\n      requests, assertions, and SLO (Single Logout).\n    humanURL: https://docs.spring.io/spring-security/reference/servlet/saml2/index.html\n    tags:\n      - Enterprise SSO\n      - Federation\n      - SAML\n      - Single Logout\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/servlet/saml2/index.html\n      - type: SAML2 Login\n        url: https://docs.spring.io/spring-security/reference/servlet/saml2/login/index.html\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-security\n  - aid: spring-security:spring-security-ldap\n    name:\
  \ Spring Security LDAP\n    description: >-\n      LDAP authentication and authorization support for Spring Security.\n      Supports LDAP bind authentication, password comparison, and user\n      details loading from directory services.\n    humanURL: https://spring.io/projects/spring-security\n    tags:\n      - Authentication\n      - Directory Services\n      - Enterprise\n      - LDAP\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/servlet/authentication/passwords/ldap.html\n      - type: Guide\n        url: https://spring.io/guides/gs/authenticating-ldap/\n  - aid: spring-security:spring-security-webflux\n    name: Spring Security WebFlux\n    description: >-\n      Reactive security for Spring WebFlux applications. Provides non-blocking\n      authentication, authorization, OAuth2 reactive client support, and\n      CSRF protection for reactive web stacks.\n    humanURL: https://spring.io/projects/spring-security\n   \
  \ tags:\n      - Non-Blocking\n      - Reactive\n      - Security\n      - WebFlux\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-security/reference/reactive/index.html\n      - type: Getting Started\n        url: https://docs.spring.io/spring-security/reference/reactive/getting-started.html\n      - type: OAuth2 WebFlux\n        url: https://docs.spring.io/spring-security/reference/reactive/oauth2/index.html\nmaintainers:\n  - FN: Spring Security Team\n    email: spring-security@vmware.com\n    url: https://spring.io/team\ninclude:\n  - name: Spring Framework\n    url: https://spring.io/projects/spring-framework\n  - name: Spring Boot\n    url: https://spring.io/projects/spring-boot\n  - name: Spring Authorization Server\n    url: https://spring.io/projects/spring-authorization-server\ncommon:\n  - type: Blog\n    url: https://spring.io/blog/category/security\n  - type: Community\n    url: https://stackoverflow.com/questions/tagged/spring-security\n\
  \  - type: Twitter\n    url: https://twitter.com/SpringSecurity\n  - type: Issue Tracker\n    url: https://github.com/spring-projects/spring-security/issues\n  - type: Contributing Guide\n    url: https://github.com/spring-projects/spring-security/blob/main/CONTRIBUTING.adoc\n  - type: License\n    url: https://github.com/spring-projects/spring-security/blob/main/LICENSE.txt\n  - type: Maven Repository\n    url: https://mvnrepository.com/artifact/org.springframework.security\n  - type: Changelog\n    url: https://github.com/spring-projects/spring-security/releases\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-security/refs/heads/main/apis.yml
tags:
- Authentication
- Authorization
- Java
- JWT
- OAuth2
- OpenID Connect
- SAML
- Security
- Spring Framework
url: https://spring.io/projects/spring-security
use_cases: []
---
