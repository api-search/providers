---
api_count: 5
apis:
- description: The Internet Engineering Task Force (IETF) produces Internet Standards (STDs) and Best Current Practices (BCPs) covering core internet protocols including HTTP, TLS, OAuth, OpenID Connect, JSON, and m
  name: IETF Internet Standards
  slug: ietf-standards
- description: The World Wide Web Consortium (W3C) leads the World Wide Web to its full potential by developing open standards for web technologies. W3C standards critical to APIs include CORS (Cross-Origin Resource
  name: W3C Web Standards
  slug: w3c-standards
- description: The Institute of Electrical and Electronics Engineers (IEEE) develops standards for electronics, electrical engineering, and computer science. IEEE standards relevant to APIs and technology include IE
  name: IEEE Standards
  slug: ieee-standards
- description: OASIS Open is a nonprofit standards development organization that advances the creation, convergence, and adoption of open standards for the global information society. OASIS standards relevant to API
  name: OASIS Open Standards
  slug: oasis-standards
- description: OAuth 2.0 (RFC 6749) is the industry-standard protocol for authorization, enabling third-party applications to obtain limited access to web services. OpenID Connect (OIDC) is an identity layer built o
  name: OAuth and OpenID Connect
  slug: oauth-openid
common:
- title: ''
  type: Website
  url: https://www.ietf.org/
- title: ''
  type: Website
  url: https://www.w3.org/
- title: ''
  type: Website
  url: https://standards.ieee.org/
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/vocabulary/technology-standards-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/json-ld/technology-standards-context.jsonld
created: '2025-01-01'
description: Technology Standards covers the landscape of formal technical standards, protocols, and normative specifications developed by international standards bodies including IEEE, IETF, W3C, ISO, OASIS, and the Linux Foundation. These standards define how technology systems interoperate, communicate, and behave. In the API economy, key standards govern data formats (JSON, XML, CSV), communication protocols (HTTP/2, HTTP/3, WebSocket, gRPC), security (OAuth 2.0, OpenID Connect, TLS), identity (SAML, SCIM), and API description (OpenAPI, AsyncAPI). Technology standards ensure interoperability, reduce vendor lock-in, and form the foundation of the modern internet and API ecosystem.
features: []
image: ''
integrations: []
jsonld:
- class_count: 44
  name: Technology Standards Context
  property_count: 0
  slug: technology-standards-context
layout: provider
modified: '2026-05-03'
name: Technology Standards
skills: []
slug: technology-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: technology-standards\nname: Technology Standards\ndescription: >-\n  Technology Standards covers the landscape of formal technical standards, protocols,\n  and normative specifications developed by international standards bodies including\n  IEEE, IETF, W3C, ISO, OASIS, and the Linux Foundation. These standards define how\n  technology systems interoperate, communicate, and behave. In the API economy, key\n  standards govern data formats (JSON, XML, CSV), communication protocols (HTTP/2,\n  HTTP/3, WebSocket, gRPC), security (OAuth 2.0, OpenID Connect, TLS), identity\n  (SAML, SCIM), and API description (OpenAPI, AsyncAPI). Technology standards ensure\n  interoperability, reduce vendor lock-in, and form the foundation of the modern\n  internet and API ecosystem.\nurl: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - IEEE\n  - IETF\n  -\
  \ ISO\n  - Protocols\n  - Standards\n  - Technology Standards\n  - W3C\napis:\n  - aid: technology-standards:ietf-standards\n    name: IETF Internet Standards\n    description: >-\n      The Internet Engineering Task Force (IETF) produces Internet Standards (STDs)\n      and Best Current Practices (BCPs) covering core internet protocols including HTTP,\n      TLS, OAuth, OpenID Connect, JSON, and many more. IETF RFCs form the normative\n      basis for most web API standards. Key API-related RFCs include RFC 9110 (HTTP\n      Semantics), RFC 6749 (OAuth 2.0), RFC 7519 (JWT), RFC 7946 (GeoJSON), and\n      RFC 8259 (JSON).\n    humanURL: https://www.ietf.org/\n    baseURL: https://datatracker.ietf.org/api/v1\n    tags:\n      - HTTP\n      - IETF\n      - Internet Standards\n      - OAuth\n      - Protocols\n      - RFC\n      - TLS\n    properties:\n      - type: Documentation\n        url: https://www.ietf.org/standards/\n      - type: Website\n        url: https://www.ietf.org/\n   \
  \   - type: API\n        url: https://datatracker.ietf.org/api/v1/\n  - aid: technology-standards:w3c-standards\n    name: W3C Web Standards\n    description: >-\n      The World Wide Web Consortium (W3C) leads the World Wide Web to its full potential\n      by developing open standards for web technologies. W3C standards critical to APIs\n      include CORS (Cross-Origin Resource Sharing), Web Authentication (WebAuthn),\n      Linked Data (RDF, JSON-LD), and the Activity Streams vocabulary. The W3C also\n      maintains standards for semantic web technologies including OWL and SPARQL.\n    humanURL: https://www.w3.org/standards/\n    baseURL: https://www.w3.org\n    tags:\n      - CORS\n      - Linked Data\n      - Semantic Web\n      - W3C\n      - Web Standards\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/\n      - type: Website\n        url: https://www.w3.org/\n      - type: GitHub\n        url: https://github.com/w3c\n  - aid: technology-standards:ieee-standards\n\
  \    name: IEEE Standards\n    description: >-\n      The Institute of Electrical and Electronics Engineers (IEEE) develops standards\n      for electronics, electrical engineering, and computer science. IEEE standards\n      relevant to APIs and technology include IEEE 802 (networking), IEEE P2510 (IoT\n      data trust), and standards around software engineering lifecycle processes.\n    humanURL: https://standards.ieee.org/\n    baseURL: https://standards.ieee.org\n    tags:\n      - Computer Science\n      - Electrical Engineering\n      - IEEE\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://standards.ieee.org/\n      - type: Website\n        url: https://standards.ieee.org/\n  - aid: technology-standards:oasis-standards\n    name: OASIS Open Standards\n    description: >-\n      OASIS Open is a nonprofit standards development organization that advances the\n      creation, convergence, and adoption of open standards for the global information\n\
  \      society. OASIS standards relevant to APIs include SAML (Security Assertion Markup\n      Language), OData (Open Data Protocol), WS-Security, MQTT, AMQP, and OpenDocument.\n    humanURL: https://www.oasis-open.org/\n    baseURL: https://www.oasis-open.org\n    tags:\n      - AMQP\n      - MQTT\n      - OData\n      - OASIS\n      - SAML\n    properties:\n      - type: Documentation\n        url: https://www.oasis-open.org/standards/\n      - type: Website\n        url: https://www.oasis-open.org/\n      - type: GitHub\n        url: https://github.com/oasis-tcs\n  - aid: technology-standards:oauth-openid\n    name: OAuth and OpenID Connect\n    description: >-\n      OAuth 2.0 (RFC 6749) is the industry-standard protocol for authorization,\n      enabling third-party applications to obtain limited access to web services.\n      OpenID Connect (OIDC) is an identity layer built on top of OAuth 2.0 that\n      enables clients to verify the identity of end users and obtain profile information.\n\
  \      Together they form the foundation for API security and developer authentication\n      across the modern web.\n    humanURL: https://oauth.net/2/\n    baseURL: https://oauth.net\n    tags:\n      - Authentication\n      - Authorization\n      - Identity\n      - OAuth\n      - OpenID Connect\n      - Security\n    properties:\n      - type: Documentation\n        url: https://oauth.net/2/\n      - type: Website\n        url: https://oauth.net/\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc6749\ncommon:\n  - type: Website\n    url: https://www.ietf.org/\n  - type: Website\n    url: https://www.w3.org/\n  - type: Website\n    url: https://standards.ieee.org/\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/vocabulary/technology-standards-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/json-ld/technology-standards-context.jsonld\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/apis.yml
tags:
- IEEE
- IETF
- ISO
- Protocols
- Standards
- Technology Standards
- W3C
url: https://raw.githubusercontent.com/api-evangelist/technology-standards/refs/heads/main/apis.yml
use_cases: []
---
