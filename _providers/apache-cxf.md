---
api_count: 1
apis:
- description: CXF provides Java APIs for building SOAP (JAX-WS) and REST (JAX-RS) web services with WSDL-first and code-first approaches, WS-* standards support, multiple data bindings (JAXB, Aegis, XMLBeans), plug
  name: Apache CXF
  slug: apache-cxf
common:
- title: ''
  type: Portal
  url: https://cxf.apache.org/
- title: ''
  type: Documentation
  url: https://cxf.apache.org/docs/index.html
- title: ''
  type: GettingStarted
  url: https://cxf.apache.org/docs/a-simple-jax-ws-service.html
- title: ''
  type: ReleaseNotes
  url: https://cxf.apache.org/download.html
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/cxf
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/apache-cxf
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/vocabulary/apache-cxf-vocabulary.yaml
created: '2026-03-16'
description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first development, full WS-* standards (WS-Security, WS-ReliableMessaging, WS-Addressing, WS-Policy), multiple transports (HTTP, JMS), and integrates with Spring Framework, OSGi/ServiceMix, and major Java EE servers.
features:
- description: Full JAX-WS implementation for building contract-first and code-first SOAP web services with WSDL support.
  name: JAX-WS SOAP Services
- description: Full JAX-RS implementation for building RESTful services with JSON and XML support and OpenAPI integration.
  name: JAX-RS REST Services
- description: Comprehensive WS-Security support including XML Signature, XML Encryption, SAML tokens, Kerberos, and Username Tokens.
  name: WS-Security
- description: Supports HTTP, Servlet, JMS, In-VM, and local transports for flexible service deployment.
  name: Multiple Transports
- description: wsdl2java generates Java clients and server stubs from WSDL; java2ws generates WSDL and XSD from annotated Java classes.
  name: Code Generation
- description: Deep Spring Framework integration with Spring Boot starters for rapid JAX-WS and JAX-RS service development.
  name: Spring Integration
- description: Supports JAXB 2.x, Aegis, XMLBeans, SDO, and JiBX data bindings for flexible XML/JSON marshalling.
  name: Data Bindings
- description: Implements WS-Addressing, WS-ReliableMessaging, WS-Policy, WS-MetadataExchange, and MTOM for enterprise-grade SOAP.
  name: WS-* Standards
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: CXF provides deep Spring integration including Spring Boot starters for JAX-WS and JAX-RS.
  name: Spring Framework
- description: CXF runs as OSGi bundles in Apache Karaf for modular service deployment.
  name: Apache Karaf / OSGi
- description: CXF services deploy as WAR files or embedded in Tomcat or Jetty servlet containers.
  name: Apache Tomcat / Jetty
- description: CXF uses WSS4J for WS-Security implementation including XML Signature and SAML.
  name: Apache WSS4J
- description: CXF integrates with Swagger/OpenAPI for automatic API documentation of JAX-RS services.
  name: OpenAPI / Swagger
- description: CXF provides a Camel component for integrating web services into Camel routing and mediation flows.
  name: Apache Camel
jsonld:
- class_count: 3
  name: Apache Cxf Context
  property_count: 19
  slug: apache-cxf-context
layout: provider
modified: '2026-04-19'
name: Apache CXF
skills: []
slug: apache-cxf
solutions: []
tags:
- Apache
- JAX-RS
- JAX-WS
- Java
- Open Source
- REST
- SOAP
- WS-Security
- Web Services
url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/apis.yml
use_cases:
- description: Build and expose SOAP-based service-oriented architecture services in enterprise Java applications.
  name: Enterprise SOA
- description: Create RESTful APIs with JAX-RS annotations, OpenAPI documentation, and JSON/XML serialization.
  name: REST API Development
- description: Wrap or migrate legacy SOAP/WSDL services to REST/JSON while maintaining backward compatibility.
  name: Legacy SOAP Modernization
- description: Use CXF Spring Boot starters to quickly expose JAX-RS or JAX-WS services in microservice architectures.
  name: Spring Boot Microservices
- description: Secure web services with SAML, Kerberos, PKI, or WS-Username Tokens using CXF WSS4J integration.
  name: WS-Security Integration
---
