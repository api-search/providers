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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-cxf\nname: Apache CXF\ndescription: >-\n  Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports\n  contract-first (WSDL) and code-first development, full WS-* standards (WS-Security, WS-ReliableMessaging, WS-Addressing, WS-Policy), multiple transports (HTTP, JMS), and integrates with Spring Framework,\n  OSGi/ServiceMix, and major Java EE servers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Apache\n- JAX-RS\n- JAX-WS\n- Java\n- Open Source\n- REST\n- SOAP\n- WS-Security\n- Web Services\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-cxf:apache-cxf\n  name: Apache CXF\n  description:\
  \ >-\n    CXF provides Java APIs for building SOAP (JAX-WS) and REST (JAX-RS) web services with WSDL-first and code-first approaches, WS-* standards support, multiple data bindings (JAXB, Aegis, XMLBeans), pluggable\n    transports (HTTP, JMS, In-VM), and code generation tools (wsdl2java, java2ws).\n  humanURL: https://cxf.apache.org/docs/index.html\n  tags:\n  - CORBA\n  - HTTP\n  - JAX-RS\n  - JAX-WS\n  - Java\n  - JMS\n  - REST\n  - SOAP\n  - WSDL\n  - WS-Security\n  - Web Services\n  properties:\n  - type: Documentation\n    url: https://cxf.apache.org/docs/index.html\n  - type: GettingStarted\n    url: https://cxf.apache.org/docs/a-simple-jax-ws-service.html\n  - type: APIReference\n    url: https://cxf.apache.org/javadoc/latest/\n  - type: GitHubRepository\n    url: https://github.com/apache/cxf\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.cxf/cxf-rt-frontend-jaxws\n    title: cxf-rt-frontend-jaxws (Maven)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.cxf/cxf-rt-frontend-jaxrs\n\
  \    title: cxf-rt-frontend-jaxrs (Maven)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.cxf/cxf-spring-boot-starter-jaxrs\n    title: Spring Boot Starter JAX-RS (Maven)\n  - type: SDK\n    url: https://mvnrepository.com/artifact/org.apache.cxf/cxf-spring-boot-starter-jaxws\n    title: Spring Boot Starter JAX-WS (Maven)\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-jaxrs-endpoint-schema.json\n    title: Jaxrs Endpoint\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-jaxws-endpoint-schema.json\n    title: Jaxws Endpoint\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-schema/apache-cxf-ws-security-config-schema.json\n    title: Ws Security Config\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-jaxrs-endpoint-structure.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-jaxws-endpoint-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-structure/apache-cxf-ws-security-config-structure.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/json-ld/apache-cxf-context.jsonld\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-jaxrs-endpoint-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-jaxws-endpoint-example.json\n  - type: Example\n    url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/examples/apache-cxf-ws-security-config-example.json\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n\
  common:\n- type: Portal\n  url: https://cxf.apache.org/\n- type: Documentation\n  url: https://cxf.apache.org/docs/index.html\n- type: GettingStarted\n  url: https://cxf.apache.org/docs/a-simple-jax-ws-service.html\n- type: ReleaseNotes\n  url: https://cxf.apache.org/download.html\n- type: GitHubRepository\n  url: https://github.com/apache/cxf\n- type: GitHubOrganization\n  url: https://github.com/apache\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/apache-cxf\n- type: Features\n  data:\n  - name: JAX-WS SOAP Services\n    description: Full JAX-WS implementation for building contract-first and code-first SOAP web services with WSDL support.\n  - name: JAX-RS REST Services\n    description: Full JAX-RS implementation for building RESTful services with JSON and XML support and OpenAPI integration.\n  - name: WS-Security\n    description: Comprehensive WS-Security support including XML Signature, XML Encryption, SAML tokens, Kerberos, and Username Tokens.\n  -\
  \ name: Multiple Transports\n    description: Supports HTTP, Servlet, JMS, In-VM, and local transports for flexible service deployment.\n  - name: Code Generation\n    description: wsdl2java generates Java clients and server stubs from WSDL; java2ws generates WSDL and XSD from annotated Java classes.\n  - name: Spring Integration\n    description: Deep Spring Framework integration with Spring Boot starters for rapid JAX-WS and JAX-RS service development.\n  - name: Data Bindings\n    description: Supports JAXB 2.x, Aegis, XMLBeans, SDO, and JiBX data bindings for flexible XML/JSON marshalling.\n  - name: WS-* Standards\n    description: Implements WS-Addressing, WS-ReliableMessaging, WS-Policy, WS-MetadataExchange, and MTOM for enterprise-grade SOAP.\n- type: UseCases\n  data:\n  - name: Enterprise SOA\n    description: Build and expose SOAP-based service-oriented architecture services in enterprise Java applications.\n  - name: REST API Development\n    description: Create RESTful APIs\
  \ with JAX-RS annotations, OpenAPI documentation, and JSON/XML serialization.\n  - name: Legacy SOAP Modernization\n    description: Wrap or migrate legacy SOAP/WSDL services to REST/JSON while maintaining backward compatibility.\n  - name: Spring Boot Microservices\n    description: Use CXF Spring Boot starters to quickly expose JAX-RS or JAX-WS services in microservice architectures.\n  - name: WS-Security Integration\n    description: Secure web services with SAML, Kerberos, PKI, or WS-Username Tokens using CXF WSS4J integration.\n- type: Integrations\n  data:\n  - name: Spring Framework\n    description: CXF provides deep Spring integration including Spring Boot starters for JAX-WS and JAX-RS.\n  - name: Apache Karaf / OSGi\n    description: CXF runs as OSGi bundles in Apache Karaf for modular service deployment.\n  - name: Apache Tomcat / Jetty\n    description: CXF services deploy as WAR files or embedded in Tomcat or Jetty servlet containers.\n  - name: Apache WSS4J\n    description:\
  \ CXF uses WSS4J for WS-Security implementation including XML Signature and SAML.\n  - name: OpenAPI / Swagger\n    description: CXF integrates with Swagger/OpenAPI for automatic API documentation of JAX-RS services.\n  - name: Apache Camel\n    description: CXF provides a Camel component for integrating web services into Camel routing and mediation flows.\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/vocabulary/apache-cxf-vocabulary.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-cxf/refs/heads/main/apis.yml
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
