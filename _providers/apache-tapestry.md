---
api_count: 1
apis:
- description: The Tapestry Component API provides Java annotations and interfaces for building reusable web components. Components are defined by a Java class and an HTML template file. The API includes @Component,
  name: Apache Tapestry Component API
  slug: apache-tapestry-component-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tapestry-5
- title: ''
  type: Documentation
  url: https://tapestry.apache.org/documentation.html
- title: ''
  type: Portal
  url: https://tapestry.apache.org/
- title: ''
  type: GettingStarted
  url: https://tapestry.apache.org/getting-started.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tapestry-5/releases
- title: ''
  type: Support
  url: https://tapestry.apache.org/community.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Tapestry is a component-oriented framework for creating highly scalable web applications in Java. It provides a component-based development model with live class reloading, built-in Ajax support, type-safe URL generation, strong convention-over-configuration principles, and deep IDE integration. Tapestry applications are highly testable and work well with dependency injection via Tapestry IoC. It is maintained by the Apache Software Foundation.
features:
- description: Hot class reloading during development without server restart for faster iteration.
  name: Live Class Reloading
- description: Pure component-based development with isolated component state and event handling.
  name: Component Model
- description: Built-in inversion of control container with service binding and decoration.
  name: Tapestry IoC
- description: Built-in Zone components for partial page updates and Ajax event handling.
  name: Ajax Support
- description: Type-safe URL generation with automatic parameter encoding and SEO-friendly URLs.
  name: Type-Safe URLs
- description: Automatic asset minification, versioning, and CDN support for JavaScript and CSS.
  name: Asset Pipeline
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spring IoC integration for service injection into Tapestry pages and components.
  name: Spring Framework
- description: Hibernate ORM integration for database access from Tapestry pages.
  name: Hibernate
- description: JPA integration module for entity management in Tapestry applications.
  name: JPA
layout: provider
modified: '2026-04-19'
name: Apache Tapestry
skills: []
slug: apache-tapestry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-tapestry\nname: Apache Tapestry\ndescription: >-\n  Apache Tapestry is a component-oriented framework for creating highly scalable web applications\n  in Java. It provides a component-based development model with live class reloading, built-in\n  Ajax support, type-safe URL generation, strong convention-over-configuration principles, and\n  deep IDE integration. Tapestry applications are highly testable and work well with dependency\n  injection via Tapestry IoC. It is maintained by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Component-Based\n  - Java\n  - Web Applications\n  - Web Framework\n  - Open Source\n  - Ajax\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tapestry/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-tapestry:apache-tapestry-component-api\n\
  \    name: Apache Tapestry Component API\n    description: >-\n      The Tapestry Component API provides Java annotations and interfaces for building reusable\n      web components. Components are defined by a Java class and an HTML template file. The API\n      includes @Component, @Property, @Parameter, @InjectPage, @OnEvent annotations for component\n      wiring, event handling, and page navigation. Tapestry also provides built-in components for\n      forms, loops, conditionals, and Ajax event handling.\n    humanURL: https://tapestry.apache.org/component-classes.html\n    tags:\n      - Java\n      - Components\n      - Web Framework\n      - Ajax\n    properties:\n      - type: Documentation\n        url: https://tapestry.apache.org/component-classes.html\n      - type: APIReference\n        url: https://tapestry.apache.org/apidocs/\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.tapestry\n        title: Maven Java SDK\ncommon:\n  - type: GitHubRepository\n\
  \    url: https://github.com/apache/tapestry-5\n  - type: Documentation\n    url: https://tapestry.apache.org/documentation.html\n  - type: Portal\n    url: https://tapestry.apache.org/\n  - type: GettingStarted\n    url: https://tapestry.apache.org/getting-started.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/tapestry-5/releases\n  - type: Support\n    url: https://tapestry.apache.org/community.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Live Class Reloading\n        description: Hot class reloading during development without server restart for faster iteration.\n      - name: Component Model\n        description: Pure component-based development with isolated component state and event handling.\n      - name: Tapestry IoC\n        description: Built-in inversion of control container with service binding and decoration.\n      - name: Ajax Support\n        description: Built-in Zone components\
  \ for partial page updates and Ajax event handling.\n      - name: Type-Safe URLs\n        description: Type-safe URL generation with automatic parameter encoding and SEO-friendly URLs.\n      - name: Asset Pipeline\n        description: Automatic asset minification, versioning, and CDN support for JavaScript and CSS.\n  - type: UseCases\n    data:\n      - name: Enterprise Java Web Applications\n        description: Large-scale enterprise applications with reusable component libraries.\n      - name: Form-Heavy Applications\n        description: Complex data entry applications with server-side validation and type coercion.\n      - name: Single-Page Application Backends\n        description: Ajax-driven UIs with partial page updates via Tapestry Zone components.\n  - type: Integrations\n    data:\n      - name: Spring Framework\n        description: Spring IoC integration for service injection into Tapestry pages and components.\n      - name: Hibernate\n        description: Hibernate\
  \ ORM integration for database access from Tapestry pages.\n      - name: JPA\n        description: JPA integration module for entity management in Tapestry applications.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tapestry/refs/heads/main/apis.yml
tags:
- Component-Based
- Java
- Web Applications
- Web Framework
- Open Source
- Ajax
url: https://raw.githubusercontent.com/api-evangelist/apache-tapestry/refs/heads/main/apis.yml
use_cases:
- description: Large-scale enterprise applications with reusable component libraries.
  name: Enterprise Java Web Applications
- description: Complex data entry applications with server-side validation and type coercion.
  name: Form-Heavy Applications
- description: Ajax-driven UIs with partial page updates via Tapestry Zone components.
  name: Single-Page Application Backends
---
