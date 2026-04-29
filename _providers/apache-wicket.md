---
api_count: 1
apis:
- description: The Wicket Component API provides the core Java classes for building web UIs. Pages extend WebPage, components extend Panel, Form, Link, Button, and other base classes. The model system uses IModel<T>
  name: Apache Wicket Component API
  slug: apache-wicket-component-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/wicket
- title: ''
  type: Documentation
  url: https://wicket.apache.org/learn/
- title: ''
  type: Portal
  url: https://wicket.apache.org/
- title: ''
  type: GettingStarted
  url: https://wicket.apache.org/start/quickstart.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/wicket/releases
- title: ''
  type: Support
  url: https://wicket.apache.org/help/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache Wicket is a component-based web application framework for Java that provides a clean separation of markup and logic with a stateful component model. It enables developers to build web applications using pure Java and HTML, without XML configuration. Wicket's stateful model stores component state on the server side while providing Ajax integration, type-safe page parameters, and deep testability. It is maintained by the Apache Software Foundation.
features:
- description: Server-side stateful component model with automatic state serialization and clustering support.
  name: Stateful Component Model
- description: No JSP, no annotations on HTML, no XML mappings - just Java classes and plain HTML templates.
  name: Pure Java and HTML
- description: Type-safe page parameters using PageParameters with automatic encoding/decoding.
  name: Type-Safe URLs
- description: Built-in Ajax behaviors and components for partial page updates without JavaScript coding.
  name: Ajax Integration
- description: WicketTester class provides comprehensive unit testing without a running servlet container.
  name: Testability
- description: Built-in CSRF protection, authorization strategies, and secure page parameters.
  name: Security
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: SpringComponentInjector for Spring bean injection into Wicket components.
  name: Spring Framework
- description: CDI/Weld integration for Jakarta EE dependency injection in Wicket.
  name: CDI
- description: Hibernate model integration for domain objects bound to Wicket components.
  name: Hibernate
- description: Wicket Bootstrap library for Bootstrap CSS integration.
  name: Bootstrap
layout: provider
modified: '2026-04-19'
name: Apache Wicket
skills: []
slug: apache-wicket
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-wicket\nname: Apache Wicket\ndescription: >-\n  Apache Wicket is a component-based web application framework for Java that provides a clean\n  separation of markup and logic with a stateful component model. It enables developers to build\n  web applications using pure Java and HTML, without XML configuration. Wicket's stateful model\n  stores component state on the server side while providing Ajax integration, type-safe page\n  parameters, and deep testability. It is maintained by the Apache Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Component-Based\n  - Java\n  - Web Applications\n  - Web Framework\n  - Open Source\n  - Ajax\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-wicket/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-wicket:apache-wicket-component-api\n\
  \    name: Apache Wicket Component API\n    description: >-\n      The Wicket Component API provides the core Java classes for building web UIs. Pages extend\n      WebPage, components extend Panel, Form, Link, Button, and other base classes. The model\n      system uses IModel<T> for type-safe data binding. The AjaxRequestTarget enables partial\n      page updates. Wicket provides built-in components for forms (TextField, DropDownChoice,\n      CheckBox), containers (RepeatingView, ListView, DataView), feedback, and navigation.\n    humanURL: https://wicket.apache.org/learn/\n    tags:\n      - Java\n      - Components\n      - Web Framework\n      - Ajax\n    properties:\n      - type: Documentation\n        url: https://wicket.apache.org/learn/\n      - type: APIReference\n        url: https://ci.apache.org/projects/wicket/apidocs/10.x/\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.wicket\n        title: Maven Java SDK\ncommon:\n  - type: GitHubRepository\n\
  \    url: https://github.com/apache/wicket\n  - type: Documentation\n    url: https://wicket.apache.org/learn/\n  - type: Portal\n    url: https://wicket.apache.org/\n  - type: GettingStarted\n    url: https://wicket.apache.org/start/quickstart.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/wicket/releases\n  - type: Support\n    url: https://wicket.apache.org/help/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Stateful Component Model\n        description: Server-side stateful component model with automatic state serialization and clustering support.\n      - name: Pure Java and HTML\n        description: No JSP, no annotations on HTML, no XML mappings - just Java classes and plain HTML templates.\n      - name: Type-Safe URLs\n        description: Type-safe page parameters using PageParameters with automatic encoding/decoding.\n      - name: Ajax Integration\n        description: Built-in Ajax behaviors\
  \ and components for partial page updates without JavaScript coding.\n      - name: Testability\n        description: WicketTester class provides comprehensive unit testing without a running servlet container.\n      - name: Security\n        description: Built-in CSRF protection, authorization strategies, and secure page parameters.\n  - type: UseCases\n    data:\n      - name: Enterprise Java Web Applications\n        description: Complex business applications with rich server-side state management.\n      - name: Form-Intensive Applications\n        description: Data entry applications with complex validation and type conversion.\n      - name: Content Management Systems\n        description: CMS backends with hierarchical content management and editorial workflows.\n  - type: Integrations\n    data:\n      - name: Spring Framework\n        description: SpringComponentInjector for Spring bean injection into Wicket components.\n      - name: CDI\n        description: CDI/Weld integration\
  \ for Jakarta EE dependency injection in Wicket.\n      - name: Hibernate\n        description: Hibernate model integration for domain objects bound to Wicket components.\n      - name: Bootstrap\n        description: Wicket Bootstrap library for Bootstrap CSS integration.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-wicket/refs/heads/main/apis.yml
tags:
- Component-Based
- Java
- Web Applications
- Web Framework
- Open Source
- Ajax
url: https://raw.githubusercontent.com/api-evangelist/apache-wicket/refs/heads/main/apis.yml
use_cases:
- description: Complex business applications with rich server-side state management.
  name: Enterprise Java Web Applications
- description: Data entry applications with complex validation and type conversion.
  name: Form-Intensive Applications
- description: CMS backends with hierarchical content management and editorial workflows.
  name: Content Management Systems
---
