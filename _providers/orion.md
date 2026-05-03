---
api_count: 4
api_specs:
- filename: orion-fhir-openapi.yml
  format: yaml
  label: Orion Health FHIR API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-fhir-openapi.yml
- filename: orion-population-health-openapi.yml
  format: yaml
  label: Orion Health Population Health API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-population-health-openapi.yml
- filename: orion-hie-openapi.yml
  format: yaml
  label: Orion Health HIE API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-hie-openapi.yml
- filename: orion-rhapsody-openapi.yml
  format: yaml
  label: Orion Health Rhapsody Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/openapi/orion-rhapsody-openapi.yml
apis:
- description: Fast Healthcare Interoperability Resources (FHIR) API for accessing and exchanging healthcare data.
  name: Orion Health FHIR API
  slug: ''
- description: API for population health management, analytics, and care coordination.
  name: Orion Health Population Health API
  slug: ''
- description: Health Information Exchange API for sharing patient information across healthcare organizations.
  name: Orion Health HIE API
  slug: ''
- description: API for healthcare integration engine enabling connectivity between disparate healthcare systems.
  name: Orion Health Rhapsody Integration API
  slug: ''
asyncapis:
- description: 'The Orion Health Rhapsody Integration Engine processes healthcare messages in real-time across connected healthcare systems. This specification describes the event-driven messaging patterns supported '
  name: Orion Health Rhapsody Messaging Events
  slug: orion-rhapsody-messaging-asyncapi
common:
- title: ''
  type: Portal
  url: https://developer.orionhealth.io/
- title: ''
  type: Getting Started
  url: https://www.orionhealth.com/developers/getting-started
- title: ''
  type: Authentication
  url: https://www.orionhealth.com/developers/authentication
- title: ''
  type: Support
  url: https://www.orionhealth.com/support
- title: ''
  type: Terms of Service
  url: https://www.orionhealth.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.orionhealth.com/privacy-policy
- title: ''
  type: Contact
  url: https://www.orionhealth.com/contact
- title: ''
  type: Blog
  url: https://www.orionhealth.com/blog
- title: ''
  type: Status
  url: https://status.orionhealth.com
- title: ''
  type: Website
  url: https://www.orionhealth.com
- title: ''
  type: GitHub Organization
  url: https://github.com/orionhealth
- title: ''
  type: Community
  url: https://community.orionhealth.com
created: '2024'
description: Orion Health is a global healthcare technology company that provides health information technology solutions, including population health management, health information exchange, and clinical workflow tools.
features: []
image: https://www.orionhealth.com/assets/img/orion-health-logo.png
integrations: []
jsonld:
- class_count: 5
  name: Orion Healthcare Context
  property_count: 17
  slug: orion-healthcare-context
layout: provider
modified: '2026-03-04'
name: Orion Health
skills: []
slug: orion
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Orion Health\ndescription: Orion Health is a global healthcare technology company that provides health information technology solutions, including population health management, health information exchange, and clinical workflow tools.\nimage: https://www.orionhealth.com/assets/img/orion-health-logo.png\nurl: https://www.orionhealth.com\ncreated: '2024'\nmodified: '2026-03-04'\nspecificationVersion: '0.18'\napis:\n  - name: Orion Health FHIR API\n    description: >-\n      Fast Healthcare Interoperability Resources (FHIR) API for accessing and exchanging\n      healthcare data.\n    image: https://www.orionhealth.com/assets/img/orion-health-logo.png\n    humanURL: https://www.orionhealth.com/products/rhapsody-integration-engine/\n    baseURL: https://api.orionhealth.com/fhir\n    tags:\n      - EHR\n      - FHIR\n      - Healthcare\n      - Interoperability\n      - Patient Data\n    properties:\n      - type: Documentation\n        url: https://www.orionhealth.com/developers/fhir-api\n\
  \      - type: OpenAPI\n        url: openapi/orion-fhir-openapi.yml\n      - type: Authentication\n        url: https://www.orionhealth.com/developers/authentication\n      - type: JSONSchema\n        url: json-schema/orion-patient-schema.json\n      - type: JSONSchema\n        url: json-schema/orion-observation-schema.json\n      - type: JSONLD\n        url: json-ld/orion-healthcare-context.jsonld\n    contact:\n      - FN: Orion Health API Support\n        email: apisupport@orionhealth.com\n        url: https://www.orionhealth.com/support\n  - name: Orion Health Population Health API\n    description: >-\n      API for population health management, analytics, and care coordination.\n    image: https://www.orionhealth.com/assets/img/orion-health-logo.png\n    humanURL: https://www.orionhealth.com/products/population-health/\n    baseURL: https://api.orionhealth.com/population-health\n    tags:\n      - Analytics\n      - Care Coordination\n      - Healthcare\n      - Population Health\n\
  \      - Risk Stratification\n    properties:\n      - type: Documentation\n        url: https://www.orionhealth.com/developers/population-health-api\n      - type: OpenAPI\n        url: openapi/orion-population-health-openapi.yml\n      - type: Sandbox\n        url: https://sandbox.orionhealth.com/population-health\n      - type: JSONSchema\n        url: json-schema/orion-care-plan-schema.json\n      - type: JSONLD\n        url: json-ld/orion-healthcare-context.jsonld\n    contact:\n      - FN: Orion Health API Support\n        email: apisupport@orionhealth.com\n        url: https://www.orionhealth.com/support\n  - name: Orion Health HIE API\n    description: >-\n      Health Information Exchange API for sharing patient information across healthcare\n      organizations.\n    image: https://www.orionhealth.com/assets/img/orion-health-logo.png\n    humanURL: https://www.orionhealth.com/products/health-information-exchange/\n    baseURL: https://api.orionhealth.com/hie\n    tags:\n    \
  \  - Data Sharing\n      - Health Information Exchange\n      - HIE\n      - Interoperability\n      - Patient Records\n    properties:\n      - type: Documentation\n        url: https://www.orionhealth.com/developers/hie-api\n      - type: OpenAPI\n        url: openapi/orion-hie-openapi.yml\n      - type: Terms of Service\n        url: https://www.orionhealth.com/terms-of-service\n      - type: JSONLD\n        url: json-ld/orion-healthcare-context.jsonld\n    contact:\n      - FN: Orion Health API Support\n        email: apisupport@orionhealth.com\n        url: https://www.orionhealth.com/support\n  - name: Orion Health Rhapsody Integration API\n    description: >-\n      API for healthcare integration engine enabling connectivity between disparate\n      healthcare systems.\n    image: https://www.orionhealth.com/assets/img/orion-health-logo.png\n    humanURL: https://www.orionhealth.com/products/rhapsody-integration-engine/\n    baseURL: https://api.orionhealth.com/rhapsody\n    tags:\n\
  \      - FHIR\n      - Healthcare\n      - HL7\n      - Integration\n      - Interoperability\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://www.orionhealth.com/developers/rhapsody-api\n      - type: OpenAPI\n        url: openapi/orion-rhapsody-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/orion-rhapsody-messaging-asyncapi.yml\n      - type: Getting Started\n        url: https://www.orionhealth.com/developers/getting-started\n      - type: JSONLD\n        url: json-ld/orion-healthcare-context.jsonld\n    contact:\n      - FN: Orion Health API Support\n        email: apisupport@orionhealth.com\n        url: https://www.orionhealth.com/support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - EHR\n  - FHIR\n  - Health IT\n  - Healthcare\n  - HIE\n  - HL7\n  - Integration\n  - Interoperability\n  - Population Health\ninclude: []\ncommon:\n  - type: Portal\n    url: https://developer.orionhealth.io/\n\
  \  - type: Getting Started\n    url: https://www.orionhealth.com/developers/getting-started\n  - type: Authentication\n    url: https://www.orionhealth.com/developers/authentication\n  - type: Support\n    url: https://www.orionhealth.com/support\n  - type: Terms of Service\n    url: https://www.orionhealth.com/terms-of-service\n  - type: Privacy Policy\n    url: https://www.orionhealth.com/privacy-policy\n  - type: Contact\n    url: https://www.orionhealth.com/contact\n  - type: Blog\n    url: https://www.orionhealth.com/blog\n  - type: Status\n    url: https://status.orionhealth.com\n  - type: Website\n    url: https://www.orionhealth.com\n  - type: GitHub Organization\n    url: https://github.com/orionhealth\n  - type: Community\n    url: https://community.orionhealth.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/orion/refs/heads/main/apis.yml
tags:
- EHR
- FHIR
- Health IT
- Healthcare
- HIE
- HL7
- Integration
- Interoperability
- Population Health
url: https://www.orionhealth.com
use_cases: []
---
