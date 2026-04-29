---
api_count: 1
apis:
- description: The Struts REST Plugin provides a convention-based REST API framework for building RESTful services. It maps HTTP methods to action methods (GET→index/show, POST→create, PUT→update, DELETE→destroy) an
  name: Apache Struts REST Plugin
  slug: apache-struts-rest-plugin
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/struts
- title: ''
  type: Documentation
  url: https://struts.apache.org/documentation.html
- title: ''
  type: Portal
  url: https://struts.apache.org/
- title: ''
  type: GettingStarted
  url: https://struts.apache.org/getting-started/index.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/struts/releases
- title: ''
  type: Support
  url: https://struts.apache.org/support.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: FAQ
  url: https://struts.apache.org/faq.html
created: '2026-03-16'
description: Apache Struts is a free, open-source, MVC framework for creating elegant, modern Java web applications. It provides a clean separation between the model, view, and controller layers with a powerful convention-over-configuration approach, interceptor-based AOP support, type-safe configuration, and built-in REST plugin. Apache Struts is maintained by the Apache Software Foundation and is widely used in enterprise Java web development.
features:
- description: Zero-XML configuration with naming conventions for action and result mapping.
  name: Convention-Over-Configuration
- description: AOP-style interceptors for cross-cutting concerns like validation, logging, and security.
  name: Interceptor Framework
- description: Automatic type conversion between HTTP request parameters and Java types.
  name: Type Conversion
- description: Object-Graph Navigation Language for dynamic data binding and expression evaluation.
  name: OGNL Expression Language
- description: Template composition via Apache Tiles for reusable page layouts.
  name: Tiles Integration
- description: Convention-based REST API support with content type negotiation.
  name: REST Plugin
- description: Native Spring Framework integration for dependency injection.
  name: Spring Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Spring IoC container integration for dependency injection.
  name: Spring Framework
- description: Hibernate ORM integration for database persistence in action classes.
  name: Hibernate
- description: Template composition framework for reusable page layouts and components.
  name: Apache Tiles
- description: FreeMarker template engine support as an alternative to JSP views.
  name: FreeMarker
- description: Apache Velocity template engine for HTML view rendering.
  name: Velocity
layout: provider
modified: '2026-04-19'
name: Apache Struts
skills: []
slug: apache-struts
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-struts\nname: Apache Struts\ndescription: >-\n  Apache Struts is a free, open-source, MVC framework for creating elegant, modern Java web\n  applications. It provides a clean separation between the model, view, and controller layers\n  with a powerful convention-over-configuration approach, interceptor-based AOP support,\n  type-safe configuration, and built-in REST plugin. Apache Struts is maintained by the Apache\n  Software Foundation and is widely used in enterprise Java web development.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Java\n  - MVC\n  - Web Applications\n  - Web Framework\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-struts/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-struts:apache-struts-rest-plugin\n    name: Apache Struts REST\
  \ Plugin\n    description: >-\n      The Struts REST Plugin provides a convention-based REST API framework for building\n      RESTful services. It maps HTTP methods to action methods (GET→index/show, POST→create,\n      PUT→update, DELETE→destroy) and supports multiple content type negotiation for JSON,\n      XML, and HTML responses via content type headers and URL extensions.\n    humanURL: https://struts.apache.org/plugins/rest/\n    tags:\n      - REST\n      - Java\n      - MVC\n      - JSON\n      - XML\n    properties:\n      - type: Documentation\n        url: https://struts.apache.org/plugins/rest/\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.struts2\n        title: Maven Java SDK\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/struts\n  - type: Documentation\n    url: https://struts.apache.org/documentation.html\n  - type: Portal\n    url: https://struts.apache.org/\n  - type: GettingStarted\n    url: https://struts.apache.org/getting-started/index.html\n\
  \  - type: ReleaseNotes\n    url: https://github.com/apache/struts/releases\n  - type: Support\n    url: https://struts.apache.org/support.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: FAQ\n    url: https://struts.apache.org/faq.html\n  - type: Features\n    data:\n      - name: Convention-Over-Configuration\n        description: Zero-XML configuration with naming conventions for action and result mapping.\n      - name: Interceptor Framework\n        description: AOP-style interceptors for cross-cutting concerns like validation, logging, and security.\n      - name: Type Conversion\n        description: Automatic type conversion between HTTP request parameters and Java types.\n      - name: OGNL Expression Language\n        description: Object-Graph Navigation Language for dynamic data binding and expression evaluation.\n      - name: Tiles Integration\n        description: Template composition via Apache Tiles for reusable page layouts.\n      -\
  \ name: REST Plugin\n        description: Convention-based REST API support with content type negotiation.\n      - name: Spring Integration\n        description: Native Spring Framework integration for dependency injection.\n  - type: UseCases\n    data:\n      - name: Enterprise Java Web Applications\n        description: Build large-scale Java web applications with clean MVC separation.\n      - name: RESTful Web Services\n        description: Create REST APIs using the Struts REST plugin with JSON/XML content negotiation.\n      - name: Form-Based Applications\n        description: Complex form processing with server-side validation and type conversion.\n  - type: Integrations\n    data:\n      - name: Spring Framework\n        description: Native Spring IoC container integration for dependency injection.\n      - name: Hibernate\n        description: Hibernate ORM integration for database persistence in action classes.\n      - name: Apache Tiles\n        description: Template composition\
  \ framework for reusable page layouts and components.\n      - name: FreeMarker\n        description: FreeMarker template engine support as an alternative to JSP views.\n      - name: Velocity\n        description: Apache Velocity template engine for HTML view rendering.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-struts/refs/heads/main/apis.yml
tags:
- Java
- MVC
- Web Applications
- Web Framework
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-struts/refs/heads/main/apis.yml
use_cases:
- description: Build large-scale Java web applications with clean MVC separation.
  name: Enterprise Java Web Applications
- description: Create REST APIs using the Struts REST plugin with JSON/XML content negotiation.
  name: RESTful Web Services
- description: Complex form processing with server-side validation and type conversion.
  name: Form-Based Applications
---
