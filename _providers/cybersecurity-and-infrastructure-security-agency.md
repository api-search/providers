---
api_count: 3
api_specs:
- filename: cisa-kev-openapi.yml
  format: yaml
  label: CISA Known Exploited Vulnerabilities (KEV) Catalog
  slug: kev
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/openapi/cisa-kev-openapi.yml
apis:
- description: 'The KEV catalog is CISA''s authoritative list of vulnerabilities actively exploited in the wild. The full catalog is published as JSON and CSV at cisa.gov/sites/default/files/feeds, mirrored on GitHub '
  name: CISA Known Exploited Vulnerabilities (KEV) Catalog
  slug: kev
- description: CISA's Automated Indicator Sharing (AIS) program uses a TAXII 2.1 server to deliver STIX-formatted cyber threat indicators (CTI) and defensive measures (DM) to vetted partners. AIS includes AIS PUBLIC
  name: CISA Automated Indicator Sharing (AIS) TAXII Server
  slug: ais
- description: 'CISA publishes Cybersecurity Advisories (CSAs), Industrial Control Systems Advisories (ICSAs), and Common Security Advisory Framework (CSAF) JSON documents describing tactics, techniques, indicators, '
  name: CISA Cybersecurity Advisories
  slug: advisories
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cisa.gov
- title: ''
  type: KEVCatalog
  url: https://www.cisa.gov/known-exploited-vulnerabilities-catalog
- title: ''
  type: Advisories
  url: https://www.cisa.gov/news-events/cybersecurity-advisories
- title: ''
  type: Topics
  url: https://www.cisa.gov/topics
- title: ''
  type: ResourcesAndTools
  url: https://www.cisa.gov/resources-tools
- title: ''
  type: NewsAndEvents
  url: https://www.cisa.gov/news-events
- title: ''
  type: GitHubOrganization
  url: https://github.com/cisagov
- title: ''
  type: KEVDataMirror
  url: https://github.com/cisagov/kev-data
- title: ''
  type: ContactUs
  url: https://www.cisa.gov/about/contact-us
- title: ''
  type: PrivacyPolicy
  url: https://www.cisa.gov/privacy-policy
- title: ''
  type: JSON-LD
  url: json-ld/cisa-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cisa-kev-vulnerability-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cisa-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/cisa-kev-capabilities.yml
- title: ''
  type: Rules
  url: rules/cisa-kev-rules.yml
created: '2024-12-03'
description: The Cybersecurity and Infrastructure Security Agency (CISA) is the United States federal civilian cybersecurity agency, part of the Department of Homeland Security. CISA reduces cybersecurity and physical security risk for the nation, coordinates federal civilian cyber defense, and partners with state, local, tribal, and territorial governments and the private sector. CISA publishes a number of public, unauthenticated machine-readable feeds, including the Known Exploited Vulnerabilities (KEV) catalog (mandatorily remediated by federal civilian agencies under Binding Operational Directive 22-01), Cybersecurity Advisories, and Common Security Advisory Framework (CSAF) advisories. CISA also operates an Automated Indicator Sharing (AIS) TAXII 2.1 server that delivers STIX cyber threat indicators to vetted partners under a Terms of Use and Interconnection Agreement.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Cisa Context
  property_count: 0
  slug: cisa-context
layout: provider
modified: '2026-04-28'
name: Cybersecurity and Infrastructure Security Agency
rules:
- name: Cybersecurity and Infrastructure Security Agency API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: cisa-kev-rules
skills: []
slug: cybersecurity-and-infrastructure-security-agency
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cybersecurity-and-infrastructure-security-agency\nname: Cybersecurity and Infrastructure Security Agency\nx-type: government\ndescription: >-\n  The Cybersecurity and Infrastructure Security Agency (CISA) is the\n  United States federal civilian cybersecurity agency, part of the\n  Department of Homeland Security. CISA reduces cybersecurity and\n  physical security risk for the nation, coordinates federal civilian\n  cyber defense, and partners with state, local, tribal, and\n  territorial governments and the private sector. CISA publishes a\n  number of public, unauthenticated machine-readable feeds, including\n  the Known Exploited Vulnerabilities (KEV) catalog (mandatorily\n  remediated by federal civilian agencies under Binding Operational\n  Directive 22-01), Cybersecurity Advisories, and Common Security\n  Advisory Framework (CSAF) advisories. CISA also operates an\n  Automated Indicator Sharing (AIS) TAXII 2.1 server that delivers\n  STIX cyber threat indicators\
  \ to vetted partners under a Terms of\n  Use and Interconnection Agreement.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Advisories\n  - AIS\n  - Binding Operational Directive\n  - CSAF\n  - CVE\n  - CWE\n  - Cybersecurity\n  - Federal Government\n  - Government\n  - ICS-CERT\n  - Information Sharing\n  - KEV\n  - Known Exploited Vulnerabilities\n  - Risk Management\n  - Security\n  - STIX\n  - TAXII\n  - Threat Intelligence\n  - Vulnerability Management\napis:\n  - aid: cybersecurity-and-infrastructure-security-agency:kev\n    name: CISA Known Exploited Vulnerabilities (KEV) Catalog\n    description: >-\n      The KEV catalog is CISA's authoritative list of vulnerabilities\n\
  \      actively exploited in the wild. The full catalog is published as\n      JSON and CSV at cisa.gov/sites/default/files/feeds, mirrored on\n      GitHub at cisagov/kev-data, and accompanied by a versioned JSON\n      Schema. Federal civilian agencies must remediate KEV entries by\n      the per-entry dueDate under BOD 22-01.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cisa.gov/known-exploited-vulnerabilities-catalog\n    baseURL: https://www.cisa.gov\n    tags:\n      - BOD 22-01\n      - CVE\n      - CWE\n      - Federal Government\n      - JSON Feed\n      - KEV\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/known-exploited-vulnerabilities-catalog\n      - type: JSONFeed\n        url: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json\n      - type: CSVFeed\n        url: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.csv\n\
  \      - type: JSONSchema\n        url: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities_schema.json\n      - type: GitHubMirror\n        url: https://github.com/cisagov/kev-data\n      - type: OpenAPI\n        url: openapi/cisa-kev-openapi.yml\n      - type: Capabilities\n        url: capabilities/cisa-kev-capabilities.yml\n      - type: Rules\n        url: rules/cisa-kev-rules.yml\n  - aid: cybersecurity-and-infrastructure-security-agency:ais\n    name: CISA Automated Indicator Sharing (AIS) TAXII Server\n    description: >-\n      CISA's Automated Indicator Sharing (AIS) program uses a TAXII 2.1\n      server to deliver STIX-formatted cyber threat indicators (CTI)\n      and defensive measures (DM) to vetted partners. AIS includes\n      AIS PUBLIC, FEDGOV, and CISCP feed communities. Connection\n      requires a static IP, a Terms of Use, and an Interconnection\n      Agreement; commercial data aggregators also redistribute AIS\n      content to subscribers.\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais\n    tags:\n      - AIS\n      - Information Sharing\n      - STIX\n      - TAXII\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/topics/cyber-threats-and-advisories/information-sharing/automated-indicator-sharing-ais\n      - type: ConnectionGuide\n        url: https://www.cisa.gov/resources-tools/resources/automated-indicator-sharing-ais-taxii-server-connection-guide\n      - type: TAXIIDocumentation\n        url: https://www.cisa.gov/automated-indicator-sharing-ais-20-documents-more-information\n  - aid: cybersecurity-and-infrastructure-security-agency:advisories\n    name: CISA Cybersecurity Advisories\n    description: >-\n      CISA publishes Cybersecurity Advisories (CSAs), Industrial\n      Control Systems Advisories\
  \ (ICSAs), and Common Security Advisory\n      Framework (CSAF) JSON documents describing tactics, techniques,\n      indicators, and required mitigations for active threats. Advisories\n      are browsable on cisa.gov and many are exported as machine-readable\n      CSAF JSON.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cisa.gov/news-events/cybersecurity-advisories\n    tags:\n      - Advisories\n      - CSAF\n      - ICS-CERT\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/news-events/cybersecurity-advisories\n      - type: ICSAdvisories\n        url: https://www.cisa.gov/news-events/ics-advisories\n      - type: CSAF\n        url: https://www.cisa.gov/news-events/cybersecurity-advisories/csaf\ncommon:\n  - type: Website\n    url: https://www.cisa.gov\n  - type: KEVCatalog\n    url: https://www.cisa.gov/known-exploited-vulnerabilities-catalog\n  - type:\
  \ Advisories\n    url: https://www.cisa.gov/news-events/cybersecurity-advisories\n  - type: Topics\n    url: https://www.cisa.gov/topics\n  - type: ResourcesAndTools\n    url: https://www.cisa.gov/resources-tools\n  - type: NewsAndEvents\n    url: https://www.cisa.gov/news-events\n  - type: GitHubOrganization\n    url: https://github.com/cisagov\n  - type: KEVDataMirror\n    url: https://github.com/cisagov/kev-data\n  - type: ContactUs\n    url: https://www.cisa.gov/about/contact-us\n  - type: PrivacyPolicy\n    url: https://www.cisa.gov/privacy-policy\n  - type: JSON-LD\n    url: json-ld/cisa-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cisa-kev-vulnerability-schema.json\n  - type: Vocabulary\n    url: vocabulary/cisa-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/cisa-kev-capabilities.yml\n  - type: Rules\n    url: rules/cisa-kev-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml
tags:
- Advisories
- AIS
- Binding Operational Directive
- CSAF
- CVE
- CWE
- Cybersecurity
- Federal Government
- Government
- ICS-CERT
- Information Sharing
- KEV
- Known Exploited Vulnerabilities
- Risk Management
- Security
- STIX
- TAXII
- Threat Intelligence
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/cybersecurity-and-infrastructure-security-agency/refs/heads/main/apis.yml
use_cases: []
---
