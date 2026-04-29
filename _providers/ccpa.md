---
api_count: 4
apis:
- description: Global Privacy Control is a browser-level signal that communicates a user's opt-out preference to websites. The California Attorney General has affirmed that GPC must be treated as a valid CCPA "Do No
  name: Global Privacy Control (GPC) Specification
  slug: global-privacy-control
- description: The IAB Tech Lab Global Privacy Platform (GPP) is the successor to the US Privacy (USP) string. It provides a standardized way to communicate user consent and opt-out signals between publishers, conse
  name: IAB Tech Lab Global Privacy Platform (GPP)
  slug: iab-gpp
- description: Official resources from the California Privacy Protection Agency, the body empowered by CPRA to implement, enforce, and publish regulations under the CCPA.
  name: California Privacy Protection Agency (CPPA) Resources
  slug: cppa-enforcement-resources
- description: Official California Attorney General registry of data brokers required to register under Civil Code section 1798.99.80, providing a public list that consumers can use to submit opt-out requests.
  name: California Data Broker Registry
  slug: ca-data-broker-registry
common:
- title: ''
  type: Website
  url: https://oag.ca.gov/privacy/ccpa
- title: ''
  type: Documentation
  url: https://oag.ca.gov/privacy/ccpa
- title: ''
  type: Regulator
  url: https://cppa.ca.gov/
- title: ''
  type: StatuteText
  url: https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CIV&division=3.&title=1.81.5.&part=4.&chapter=&article=
- title: ''
  type: Regulations
  url: https://cppa.ca.gov/regulations/
- title: ''
  type: FAQ
  url: https://oag.ca.gov/privacy/ccpa
- title: ''
  type: Enforcement
  url: https://cppa.ca.gov/enforcement/
- title: ''
  type: DataBrokerRegistry
  url: https://oag.ca.gov/data-brokers
- title: ''
  type: GPC
  url: https://globalprivacycontrol.org/
- title: ''
  type: GPP
  url: https://iabtechlab.com/gpp/
- title: ''
  type: Rights
  url: ''
- title: ''
  type: Applicability
  url: ''
created: '2025-01-01'
description: 'The California Consumer Privacy Act (CCPA), amended by the California Privacy Rights Act (CPRA), is a state statute that grants California residents rights over their personal information: the right to know, delete, correct, opt-out of sale/sharing, limit use of sensitive personal information, and non-discrimination for exercising privacy rights. It is enforced by the California Privacy Protection Agency (CPPA) and the California Attorney General. Technical interoperability mechanisms include the Global Privacy Control (GPC) browser signal and the IAB Tech Lab US Privacy (USP) / Global Privacy Platform (GPP) signals for advertising technology. This index tracks the official regulatory resources, technical privacy signals, and commercial APIs that help businesses comply with CCPA/CPRA obligations.'
features:
- name: Notice at Collection
- name: Privacy Policy Disclosure
- name: Do Not Sell or Share Link
- name: Limit Use of Sensitive PI Link
- name: Verifiable Consumer Requests
- name: Authorized Agent Requests
- name: Opt-Out Preference Signal (GPC)
- name: Service Provider / Contractor Contracts
- name: Data Processing Addendum
- name: Data Retention Disclosure
- name: Risk Assessments (CPRA)
- name: Cybersecurity Audits (CPRA)
- name: Automated Decision-Making Disclosures (CPRA)
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CCPA (California Consumer Privacy Act)
skills: []
slug: ccpa
solutions: []
source_yaml: "aid: ccpa\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ccpa/refs/heads/main/apis.yml\nname: CCPA (California Consumer Privacy Act)\ntags:\n  - CPRA\n  - California\n  - Compliance\n  - Data Protection\n  - Data Subject Rights\n  - Legal\n  - Privacy\n  - Regulation\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  The California Consumer Privacy Act (CCPA), amended by the California\n  Privacy Rights Act (CPRA), is a state statute that grants California\n  residents rights over their personal information: the right to know,\n  delete, correct, opt-out of sale/sharing, limit use of sensitive personal\n  information, and non-discrimination for exercising privacy rights. It is\n  enforced by the California Privacy Protection Agency (CPPA) and the\n  California Attorney General. Technical interoperability mechanisms\n\
  \  include the Global Privacy Control (GPC) browser signal and the IAB Tech\n  Lab US Privacy (USP) / Global Privacy Platform (GPP) signals for\n  advertising technology. This index tracks the official regulatory\n  resources, technical privacy signals, and commercial APIs that help\n  businesses comply with CCPA/CPRA obligations.\napis:\n  - aid: ccpa:global-privacy-control\n    name: Global Privacy Control (GPC) Specification\n    tags:\n      - Browser Signal\n      - Opt-Out\n      - Standard\n    humanURL: https://globalprivacycontrol.org/\n    properties:\n      - url: https://globalprivacycontrol.org/\n        type: Website\n      - url: https://privacycg.github.io/gpc-spec/\n        type: Specification\n      - url: https://github.com/privacycg/gpc-spec\n        type: SourceCode\n    description: >-\n      Global Privacy Control is a browser-level signal that communicates a\n      user's opt-out preference to websites. The California Attorney\n      General has affirmed that GPC\
  \ must be treated as a valid CCPA\n      \"Do Not Sell or Share\" opt-out request.\n  - aid: ccpa:iab-gpp\n    name: IAB Tech Lab Global Privacy Platform (GPP)\n    tags:\n      - AdTech\n      - Consent\n      - IAB\n      - Signals\n    humanURL: https://iabtechlab.com/gpp/\n    properties:\n      - url: https://iabtechlab.com/gpp/\n        type: Documentation\n      - url: https://github.com/InteractiveAdvertisingBureau/Global-Privacy-Platform\n        type: SourceCode\n      - url: https://github.com/InteractiveAdvertisingBureau/USPrivacy\n        type: LegacySpec\n    description: >-\n      The IAB Tech Lab Global Privacy Platform (GPP) is the successor to\n      the US Privacy (USP) string. It provides a standardized way to\n      communicate user consent and opt-out signals between publishers,\n      consent management platforms, and adtech vendors for CCPA, CPRA, and\n      other jurisdictions.\n  - aid: ccpa:cppa-enforcement-resources\n    name: California Privacy Protection Agency\
  \ (CPPA) Resources\n    tags:\n      - Enforcement\n      - Regulation\n      - Rulemaking\n    humanURL: https://cppa.ca.gov/\n    properties:\n      - url: https://cppa.ca.gov/\n        type: Website\n      - url: https://cppa.ca.gov/regulations/\n        type: Regulations\n      - url: https://cppa.ca.gov/enforcement/\n        type: Enforcement\n    description: >-\n      Official resources from the California Privacy Protection Agency, the\n      body empowered by CPRA to implement, enforce, and publish regulations\n      under the CCPA.\n  - aid: ccpa:ca-data-broker-registry\n    name: California Data Broker Registry\n    tags:\n      - Data Brokers\n      - Registry\n    humanURL: https://oag.ca.gov/data-brokers\n    properties:\n      - url: https://oag.ca.gov/data-brokers\n        type: Registry\n      - url: https://oag.ca.gov/data-brokers/submit\n        type: Registration\n    description: >-\n      Official California Attorney General registry of data brokers\n      required\
  \ to register under Civil Code section 1798.99.80, providing\n      a public list that consumers can use to submit opt-out requests.\ncommon:\n  - type: Website\n    url: https://oag.ca.gov/privacy/ccpa\n  - type: Documentation\n    url: https://oag.ca.gov/privacy/ccpa\n  - type: Regulator\n    url: https://cppa.ca.gov/\n  - type: StatuteText\n    url: https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CIV&division=3.&title=1.81.5.&part=4.&chapter=&article=\n  - type: Regulations\n    url: https://cppa.ca.gov/regulations/\n  - type: FAQ\n    url: https://oag.ca.gov/privacy/ccpa\n  - type: Enforcement\n    url: https://cppa.ca.gov/enforcement/\n  - type: DataBrokerRegistry\n    url: https://oag.ca.gov/data-brokers\n  - type: GPC\n    url: https://globalprivacycontrol.org/\n  - type: GPP\n    url: https://iabtechlab.com/gpp/\n  - name: Rights\n    type: Rights\n    data:\n      - name: Right to Know\n      - name: Right to Delete\n      - name: Right to Correct\n  \
  \    - name: Right to Opt-Out of Sale\n      - name: Right to Opt-Out of Sharing (Cross-Context Behavioral Advertising)\n      - name: Right to Limit Use of Sensitive Personal Information\n      - name: Right to Data Portability\n      - name: Right to Non-Discrimination\n  - name: Applicability\n    type: Applicability\n    data:\n      - name: Gross Annual Revenue > $25M\n      - name: Personal Information of 100k+ California Residents\n      - name: 50%+ Revenue From Sale of Personal Information\n  - name: Features\n    type: Features\n    data:\n      - name: Notice at Collection\n      - name: Privacy Policy Disclosure\n      - name: Do Not Sell or Share Link\n      - name: Limit Use of Sensitive PI Link\n      - name: Verifiable Consumer Requests\n      - name: Authorized Agent Requests\n      - name: Opt-Out Preference Signal (GPC)\n      - name: Service Provider / Contractor Contracts\n      - name: Data Processing Addendum\n      - name: Data Retention Disclosure\n      - name:\
  \ Risk Assessments (CPRA)\n      - name: Cybersecurity Audits (CPRA)\n      - name: Automated Decision-Making Disclosures (CPRA)\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: DSAR (Data Subject Access Request) Automation\n      - name: Consent Management Platform (CMP)\n      - name: Cookie Banner and Preference Center\n      - name: Data Inventory and Mapping\n      - name: Vendor Risk Management\n      - name: Privacy Impact Assessments\n      - name: Audit and Reporting\n      - name: Global Privacy Control Handling\n      - name: Data Broker Registration\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ccpa/refs/heads/main/apis.yml
tags:
- CPRA
- California
- Compliance
- Data Protection
- Data Subject Rights
- Legal
- Privacy
- Regulation
url: https://raw.githubusercontent.com/api-evangelist/ccpa/refs/heads/main/apis.yml
use_cases:
- name: DSAR (Data Subject Access Request) Automation
- name: Consent Management Platform (CMP)
- name: Cookie Banner and Preference Center
- name: Data Inventory and Mapping
- name: Vendor Risk Management
- name: Privacy Impact Assessments
- name: Audit and Reporting
- name: Global Privacy Control Handling
- name: Data Broker Registration
---
