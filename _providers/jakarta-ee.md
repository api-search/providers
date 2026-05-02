---
api_count: 6
apis:
- description: Jakarta RESTful Web Services (formerly JAX-RS) is the API specification for developing web services that follow the REST architectural pattern. It defines a set of Java APIs and annotations that enabl
  name: Jakarta RESTful Web Services
  slug: jakarta-restful-web-services
- description: Jakarta JSON Processing (formerly JSON-P) provides an API to parse, generate, transform, and query JSON documents. It includes a streaming API similar to StAX and an object model API similar to DOM fo
  name: Jakarta JSON Processing
  slug: jakarta-json-processing
- description: Jakarta JSON Binding (formerly JSON-B) is a binding framework for converting Java objects to and from JSON documents. It provides a default mapping between classes and JSON, with the ability to custom
  name: Jakarta JSON Binding
  slug: jakarta-json-binding
- description: 'Jakarta WebSocket defines a standard API for creating server and client endpoints that communicate using the WebSocket protocol (RFC 6455). It enables full-duplex, bidirectional communication between '
  name: Jakarta WebSocket
  slug: jakarta-websocket
- description: Jakarta Servlet is a server-side Java API for handling HTTP requests and generating dynamic responses. It provides the foundational programming model for Java-based web applications and underpins many
  name: Jakarta Servlet
  slug: jakarta-servlet
- description: Jakarta Validation (formerly Bean Validation) provides an object-level constraint declaration and validation facility through annotations and a runtime API. It is widely used to validate inputs in RES
  name: Jakarta Validation
  slug: jakarta-validation
common:
- title: ''
  type: Website
  url: https://jakarta.ee/
- title: ''
  type: Specifications
  url: https://jakarta.ee/specifications/
- title: ''
  type: Documentation
  url: https://jakarta.ee/learn/
- title: ''
  type: GitHub Organization
  url: https://github.com/jakartaee
- title: ''
  type: News
  url: https://jakarta.ee/news/
- title: ''
  type: Community
  url: https://jakarta.ee/community/
- title: ''
  type: Eclipse Foundation
  url: https://www.eclipse.org/
created: '2025-01-01'
description: Jakarta EE is the open source successor to Java EE, providing a set of specifications for enterprise Java development. Jakarta EE is developed under the Eclipse Foundation and includes specifications for web services, messaging, persistence, security, and other enterprise computing needs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Jakarta EE
skills: []
slug: jakarta-ee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: jakarta-ee\nname: Jakarta EE\ndescription: >-\n  Jakarta EE is the open source successor to Java EE, providing a set of\n  specifications for enterprise Java development. Jakarta EE is developed\n  under the Eclipse Foundation and includes specifications for web services,\n  messaging, persistence, security, and other enterprise computing needs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise\n  - Jakarta EE\n  - Java\n  - Standards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/jakarta-ee/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: jakarta-ee:jakarta-restful-web-services\n    name: Jakarta RESTful Web Services\n    description: >-\n      Jakarta RESTful Web Services (formerly JAX-RS) is the API specification\n      for developing web services that follow the REST architectural pattern.\n      It defines a set of\
  \ Java APIs and annotations that enable the development\n      and deployment of RESTful web services on the Jakarta EE platform.\n    humanURL: https://jakarta.ee/specifications/restful-ws/\n    tags:\n      - REST\n      - Specification\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://jakarta.ee/specifications/restful-ws/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/rest\n  - aid: jakarta-ee:jakarta-json-processing\n    name: Jakarta JSON Processing\n    description: >-\n      Jakarta JSON Processing (formerly JSON-P) provides an API to parse,\n      generate, transform, and query JSON documents. It includes a streaming\n      API similar to StAX and an object model API similar to DOM for working\n      with JSON data in Jakarta EE applications.\n    humanURL: https://jakarta.ee/specifications/jsonp/\n    tags:\n      - JSON\n      - Parsing\n      - Specification\n    properties:\n      - type: Documentation\n  \
  \      url: https://jakarta.ee/specifications/jsonp/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/jsonp-api\n  - aid: jakarta-ee:jakarta-json-binding\n    name: Jakarta JSON Binding\n    description: >-\n      Jakarta JSON Binding (formerly JSON-B) is a binding framework for\n      converting Java objects to and from JSON documents. It provides a\n      default mapping between classes and JSON, with the ability to customize\n      the mapping process through a comprehensive configuration API.\n    humanURL: https://jakarta.ee/specifications/jsonb/\n    tags:\n      - Binding\n      - JSON\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://jakarta.ee/specifications/jsonb/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/jsonb-api\n  - aid: jakarta-ee:jakarta-websocket\n    name: Jakarta WebSocket\n    description: >-\n      Jakarta WebSocket defines a standard API for creating server and client\n\
  \      endpoints that communicate using the WebSocket protocol (RFC 6455). It\n      enables full-duplex, bidirectional communication between clients and\n      servers over a single TCP connection in Jakarta EE applications.\n    humanURL: https://jakarta.ee/specifications/websocket/\n    tags:\n      - Specification\n      - Streaming\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://jakarta.ee/specifications/websocket/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/websocket\n  - aid: jakarta-ee:jakarta-servlet\n    name: Jakarta Servlet\n    description: >-\n      Jakarta Servlet is a server-side Java API for handling HTTP requests\n      and generating dynamic responses. It provides the foundational\n      programming model for Java-based web applications and underpins many\n      other Jakarta EE web technologies including RESTful Web Services and\n      WebSocket.\n    humanURL: https://jakarta.ee/specifications/servlet/\n\
  \    tags:\n      - HTTP\n      - Specification\n      - Web\n    properties:\n      - type: Documentation\n        url: https://jakarta.ee/specifications/servlet/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/servlet\n  - aid: jakarta-ee:jakarta-validation\n    name: Jakarta Validation\n    description: >-\n      Jakarta Validation (formerly Bean Validation) provides an object-level\n      constraint declaration and validation facility through annotations and\n      a runtime API. It is widely used to validate inputs in REST endpoints,\n      persistence entities, and other Jakarta EE components.\n    humanURL: https://jakarta.ee/specifications/bean-validation/\n    tags:\n      - Specification\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://jakarta.ee/specifications/bean-validation/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/validation\ncommon:\n  - type: Website\n    url: https://jakarta.ee/\n\
  \  - type: Specifications\n    url: https://jakarta.ee/specifications/\n  - type: Documentation\n    url: https://jakarta.ee/learn/\n  - type: GitHub Organization\n    url: https://github.com/jakartaee\n  - type: News\n    url: https://jakarta.ee/news/\n  - type: Community\n    url: https://jakarta.ee/community/\n  - type: Eclipse Foundation\n    url: https://www.eclipse.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jakarta-ee/refs/heads/main/apis.yml
tags:
- Enterprise
- Jakarta EE
- Java
- Standards
url: https://raw.githubusercontent.com/api-evangelist/jakarta-ee/refs/heads/main/apis.yml
use_cases: []
---
