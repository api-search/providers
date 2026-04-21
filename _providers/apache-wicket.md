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
