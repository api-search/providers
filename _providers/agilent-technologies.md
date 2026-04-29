---
api_count: 4
api_specs:
- filename: agilent-ilab-operations-api.yaml
  format: yaml
  label: Agilent iLab Operations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/openapi/agilent-ilab-operations-api.yaml
apis:
- description: The iLab API enables customers to seamlessly integrate outside applications with iLab's billing and reporting modules. It leverages a RESTful application architecture with HATEOAS (Hypermedia as the E
  name: Agilent iLab Operations API
  slug: ''
- description: The SLIMS (Smart Laboratory Information Management System) REST API provides programmatic access to Agilent SLIMS laboratory data management platform. SLIMS features three APIs — REST, Java, and Pytho
  name: Agilent SLIMS REST API
  slug: ''
- description: The CrossLab Asset Manager API provides programmatic access to Agilent's CrossLab instrument services platform, enabling management of laboratory assets, instrument service records, maintenance schedu
  name: Agilent CrossLab Asset Manager API
  slug: ''
- description: The VWorks API provides a Component Object Model (COM) application programming interface for VWorks laboratory automation software (version 14.0 and later). It enables programmatic control of laborato
  name: Agilent VWorks Automation API
  slug: ''
capabilities:
- description: 'Unified laboratory operations capability combining iLab core facility management for billing, scheduling, service requests, and reporting. Used by core facility managers, research administrators, and '
  name: Agilent Laboratory Operations
  slug: laboratory-operations
common:
- title: ''
  type: Website
  url: https://www.agilent.com/en
- title: ''
  type: Support
  url: https://www.agilent.com/en/support
- title: ''
  type: Community
  url: https://community.agilent.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Agilent
- title: ''
  type: TermsOfService
  url: https://www.agilent.com/en/legal
- title: ''
  type: PrivacyPolicy
  url: https://www.agilent.com/en/privacy-statement
- title: ''
  type: SpectralRules
  url: rules/agilent-technologies-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/laboratory-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/agilent-technologies-vocabulary.yaml
created: ''
description: Agilent Technologies is a global leader in life sciences, diagnostics, and applied chemical markets, providing instruments, software, services, and consumables for laboratory workflows. Agilent offers APIs for laboratory operations management including iLab for core facility billing and scheduling, SLIMS for laboratory information management, CrossLab Asset Manager for instrument management, and VWorks for laboratory automation.
features:
- description: iLab and CrossLab APIs leverage RESTful architecture with HATEOAS for discoverable resource navigation.
  name: RESTful Architecture
- description: Secure access to APIs via OAuth2 with client ID and API token-based authentication.
  name: OAuth2 Authentication
- description: Pre-built integration support for SAP, Oracle/PeopleSoft, Lawson, and Banner financial systems.
  name: Financial System Integration
- description: Integration with laboratory information management systems for sample tracking and results management.
  name: LIMS Integration
- description: Ability to import usage logs and data directly from connected laboratory instruments.
  name: Instrument Data Import
- description: SLIMS supports custom plugin development via Java and Python APIs for workflow extension.
  name: Plugin Architecture
- description: SLIMS REST API documentation is automatically generated from each deployed instance.
  name: Auto-Generated API Documentation
image: ''
integrations:
- description: Financial system integration for billing and cost accounting via iLab API.
  name: SAP
- description: ERP integration for institutional billing and financial reporting.
  name: Oracle PeopleSoft
- description: Financial management system integration for laboratory billing workflows.
  name: Lawson
- description: Higher education ERP integration for core facility cost center management.
  name: Banner
- description: Integration between Agilent instruments and LabWare LIMS for data transfer and workflow coordination.
  name: LabWare LIMS
- description: Integration with institutional identity providers for single sign-on and user provisioning.
  name: Identity Management Systems
jsonld:
- class_count: 23
  name: Agilent Ilab Operations Api Context
  property_count: 37
  slug: agilent-ilab-operations-api-context
layout: provider
modified: '2026-04-19'
name: agilent-technologies
rules:
- name: agilent-technologies API Rules
  rule_count: 35
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 21
  slug: agilent-technologies-spectral-rules
skills: []
slug: agilent-technologies
solutions: []
source_filename: apis.yml
source_yaml: "aid: agilent-technologies\nurl: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/apis.yml\nmodified: '2026-04-19'\ndescription: >-\n  Agilent Technologies is a global leader in life sciences, diagnostics, and\n  applied chemical markets, providing instruments, software, services, and\n  consumables for laboratory workflows. Agilent offers APIs for laboratory\n  operations management including iLab for core facility billing and scheduling,\n  SLIMS for laboratory information management, CrossLab Asset Manager for\n  instrument management, and VWorks for laboratory automation.\ntags:\n  - Life Sciences\n  - Diagnostics\n  - Laboratory\n  - Scientific Instruments\n  - LIMS\n  - Laboratory Automation\napis:\n  - name: Agilent iLab Operations API\n    description: >-\n      The iLab API enables customers to seamlessly integrate outside applications\n      with iLab's billing and reporting modules. It leverages a RESTful\n      application architecture\
  \ with HATEOAS (Hypermedia as the Engine of\n      Application State) and OAuth2 for secure access. The API supports\n      integrations with institutional financial systems such as SAP,\n      Oracle/PeopleSoft, Lawson, and Banner, as well as identity management\n      systems and LIMS.\n    humanURL: https://help.ilab.agilent.com/ilab-api\n    baseURL: https://api.ilabsolutions.com/v1\n    tags:\n      - Laboratory Operations\n      - Billing\n      - Core Facilities\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://help.ilab.agilent.com/ilab-api\n      - type: Authentication\n        url: https://help.ilab.agilent.com/ilab-api\n      - type: OpenAPI\n        url: openapi/agilent-ilab-operations-api.yaml\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-core-schema.json\n        title: Core Schema\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-service-schema.json\n        title: Service Schema\n    \
  \  - type: JSONSchema\n        url: json-schema/ilab-operations-api-service-request-schema.json\n        title: Service Request Schema\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-reservation-schema.json\n        title: Reservation Schema\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-invoice-schema.json\n        title: Invoice Schema\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-member-schema.json\n        title: Member Schema\n      - type: JSONSchema\n        url: json-schema/ilab-operations-api-project-schema.json\n        title: Project Schema\n      - type: JSONStructure\n        url: json-structure/ilab-operations-api-core-structure.json\n        title: Core Structure\n      - type: JSONStructure\n        url: json-structure/ilab-operations-api-service-request-structure.json\n        title: Service Request Structure\n      - type: JSON-LD\n        url: json-ld/agilent-ilab-operations-api-context.jsonld\n\
  \  - name: Agilent SLIMS REST API\n    description: >-\n      The SLIMS (Smart Laboratory Information Management System) REST API\n      provides programmatic access to Agilent SLIMS laboratory data management\n      platform. SLIMS features three APIs — REST, Java, and Python — enabling\n      integration with analytical instruments, NGS workflows, biobanks, and R&D\n      labs. The REST API is auto-documented within each SLIMS instance.\n    humanURL: https://slims-python-api.readthedocs.io/\n    baseURL: https://your-slims-instance/rest\n    tags:\n      - LIMS\n      - Laboratory Information Management\n      - NGS\n      - Biobank\n    properties:\n      - type: Documentation\n        url: https://community.agilent.com/cfs-file/__key/docpreview-s/00-00-02-00-89/slims_5F00_development_5F00_manual_2D00_6.9.29.pdf\n        title: SLIMS Development Manual v6.9\n      - type: SDK\n        url: https://github.com/genohm/slims-python-api\n        title: Python SDK\n      - type: SDK\n  \
  \      url: https://github.com/genohm/slims-api\n        title: Plugin API\n  - name: Agilent CrossLab Asset Manager API\n    description: >-\n      The CrossLab Asset Manager API provides programmatic access to Agilent's\n      CrossLab instrument services platform, enabling management of laboratory\n      assets, instrument service records, maintenance scheduling, and compliance\n      tracking across laboratory environments.\n    humanURL: https://crosslab-api.agilent.com/\n    baseURL: https://crosslab-api.agilent.com\n    tags:\n      - Asset Management\n      - Instrument Services\n      - CrossLab\n      - Maintenance\n    properties:\n      - type: Documentation\n        url: https://crosslab-api.agilent.com/\n  - name: Agilent VWorks Automation API\n    description: >-\n      The VWorks API provides a Component Object Model (COM) application\n      programming interface for VWorks laboratory automation software (version\n      14.0 and later). It enables programmatic control of\
  \ laboratory workstations,\n      automated liquid handling robots, and integrated automation systems.\n    humanURL: https://www.agilent.com/cs/library/usermanuals/public/D0008025_VWorks_API_Reference_Agilent.pdf\n    baseURL: https://www.agilent.com\n    tags:\n      - Laboratory Automation\n      - Robotics\n      - Liquid Handling\n      - Workstation\n    properties:\n      - type: Documentation\n        url: https://www.agilent.com/cs/library/usermanuals/public/D0008025_VWorks_API_Reference_Agilent.pdf\n        title: VWorks API Reference Guide v14.0\ncommon:\n  - type: Website\n    url: https://www.agilent.com/en\n  - type: Support\n    url: https://www.agilent.com/en/support\n  - type: Community\n    url: https://community.agilent.com\n  - type: GitHubOrganization\n    url: https://github.com/Agilent\n  - type: TermsOfService\n    url: https://www.agilent.com/en/legal\n  - type: PrivacyPolicy\n    url: https://www.agilent.com/en/privacy-statement\n  - type: SpectralRules\n    url:\
  \ rules/agilent-technologies-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/laboratory-operations.yaml\n  - type: Vocabulary\n    url: vocabulary/agilent-technologies-vocabulary.yaml\n  - type: Features\n    data:\n      - name: RESTful Architecture\n        description: iLab and CrossLab APIs leverage RESTful architecture with HATEOAS for discoverable resource navigation.\n      - name: OAuth2 Authentication\n        description: Secure access to APIs via OAuth2 with client ID and API token-based authentication.\n      - name: Financial System Integration\n        description: Pre-built integration support for SAP, Oracle/PeopleSoft, Lawson, and Banner financial systems.\n      - name: LIMS Integration\n        description: Integration with laboratory information management systems for sample tracking and results management.\n      - name: Instrument Data Import\n        description: Ability to import usage logs and data directly from connected laboratory instruments.\n\
  \      - name: Plugin Architecture\n        description: SLIMS supports custom plugin development via Java and Python APIs for workflow extension.\n      - name: Auto-Generated API Documentation\n        description: SLIMS REST API documentation is automatically generated from each deployed instance.\n  - type: UseCases\n    data:\n      - name: Core Facility Billing Automation\n        description: Automate billing workflows between iLab core facilities and institutional financial systems such as SAP or Oracle.\n      - name: Laboratory Scheduling Integration\n        description: Integrate external scheduling applications with iLab's equipment reservation and usage tracking.\n      - name: Sample Lifecycle Management\n        description: Use the SLIMS API to track samples from receipt through analysis and reporting across NGS, biobank, and R&D workflows.\n      - name: Instrument Asset Tracking\n        description: Manage laboratory instrument service records, calibration schedules,\
  \ and compliance documentation via CrossLab Asset Manager API.\n      - name: Automation Workflow Control\n        description: Programmatically control VWorks-driven liquid handling robots and integrated workstations for high-throughput workflows.\n      - name: LIMS Data Reporting\n        description: Extract and aggregate laboratory data from SLIMS for custom reporting and business intelligence integrations.\n  - type: Integrations\n    data:\n      - name: SAP\n        description: Financial system integration for billing and cost accounting via iLab API.\n      - name: Oracle PeopleSoft\n        description: ERP integration for institutional billing and financial reporting.\n      - name: Lawson\n        description: Financial management system integration for laboratory billing workflows.\n      - name: Banner\n        description: Higher education ERP integration for core facility cost center management.\n      - name: LabWare LIMS\n        description: Integration between Agilent\
  \ instruments and LabWare LIMS for data transfer and workflow coordination.\n      - name: Identity Management Systems\n        description: Integration with institutional identity providers for single sign-on and user provisioning.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/apis.yml
tags:
- Life Sciences
- Diagnostics
- Laboratory
- Scientific Instruments
- LIMS
- Laboratory Automation
url: https://raw.githubusercontent.com/api-evangelist/agilent-technologies/refs/heads/main/apis.yml
use_cases:
- description: Automate billing workflows between iLab core facilities and institutional financial systems such as SAP or Oracle.
  name: Core Facility Billing Automation
- description: Integrate external scheduling applications with iLab's equipment reservation and usage tracking.
  name: Laboratory Scheduling Integration
- description: Use the SLIMS API to track samples from receipt through analysis and reporting across NGS, biobank, and R&D workflows.
  name: Sample Lifecycle Management
- description: Manage laboratory instrument service records, calibration schedules, and compliance documentation via CrossLab Asset Manager API.
  name: Instrument Asset Tracking
- description: Programmatically control VWorks-driven liquid handling robots and integrated workstations for high-throughput workflows.
  name: Automation Workflow Control
- description: Extract and aggregate laboratory data from SLIMS for custom reporting and business intelligence integrations.
  name: LIMS Data Reporting
---
