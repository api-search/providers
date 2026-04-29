---
api_count: 5
apis:
- description: The cfo.gov public website is the official portal for the federal CFO Council, hosting member rosters, council news, working-group outputs, financial-management policy guidance, and links to companion
  name: CFO Council Website
  slug: cfoc-website
- description: The CFO Council operates topical working groups covering areas such as financial systems, internal control, grants management, payment integrity, financial reporting, and data analytics. Working-group
  name: CFO Council Working Groups
  slug: cfoc-working-groups
- description: PaymentAccuracy.gov is the OMB-maintained transparency site for reporting government-wide improper payments and payment-integrity activities. The site publishes downloadable agency-level payment accur
  name: PaymentAccuracy.gov (Payment Integrity)
  slug: cfoc-payment-integrity
- description: USAspending.gov is the Treasury-operated public source of accountable federal spending data, exposing a comprehensive REST API for federal awards, contracts, grants, sub-awards, and agency budget data
  name: USAspending.gov API (Treasury)
  slug: usaspending
- description: Performance.gov is the OMB-administered public site for federal cross-agency priority goals, agency strategic plans, and performance reports. The CFO Council collaborates with OMB on financial-managem
  name: MAX.gov / Performance.gov
  slug: max-gov
common:
- title: ''
  type: Website
  url: https://www.cfo.gov/
- title: ''
  type: About
  url: https://www.cfo.gov/about-the-council/
- title: ''
  type: Resources
  url: https://www.cfo.gov/resources/
- title: ''
  type: WorkingGroups
  url: https://www.cfo.gov/working-groups/
- title: ''
  type: News
  url: https://www.cfo.gov/news/
- title: ''
  type: Events
  url: https://www.cfo.gov/events/
- title: ''
  type: Members
  url: https://www.cfo.gov/members/
- title: ''
  type: Contact
  url: mailto:CFOC.support@gsa.gov
- title: ''
  type: Privacy Policy
  url: https://www.cfo.gov/privacy-policy/
- title: ''
  type: AccessibilityStatement
  url: https://www.cfo.gov/accessibility/
- title: ''
  type: USAspending
  url: https://www.usaspending.gov/
- title: ''
  type: PaymentAccuracy
  url: https://www.paymentaccuracy.gov/
- title: ''
  type: PerformanceGov
  url: https://www.performance.gov/
- title: ''
  type: OMB
  url: https://www.whitehouse.gov/omb/
- title: ''
  type: Treasury
  url: https://home.treasury.gov/
- title: ''
  type: GSA
  url: https://www.gsa.gov/
- title: ''
  type: ProgramAreas
  url: ''
- title: ''
  type: WorkingGroups
  url: ''
created: '2024-12-03'
description: The Chief Financial Officers Council (CFOC) was established by the Chief Financial Officers (CFO) Act of 1990 (Public Law 101-576) and is composed of the CFOs and Deputy CFOs of the 24 largest federal departments and agencies, along with senior officials from the Office of Management and Budget (OMB) and the Department of the Treasury. The Council works collaboratively to improve federal financial management through shared guidance, working groups, and inter-agency standards. While the CFO Council itself does not operate a developer API program, its remit is closely tied to the larger ecosystem of federal financial management data and APIs administered by Treasury (USAspending.gov, Fiscal Service), OMB (PaymentAccuracy.gov, MAX.gov), and GSA (Performance.gov, SAM.gov).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Chief Financial Officers Council
skills: []
slug: chief-financial-officers-council
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chief-financial-officers-council\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chief-financial-officers-council/refs/heads/main/apis.yml\nname: Chief Financial Officers Council\ntags:\n  - Federal Financial Management\n  - Federal Government\n  - Finance\n  - Government\n  - OMB\n  - Treasury\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  The Chief Financial Officers Council (CFOC) was established by the Chief\n  Financial Officers (CFO) Act of 1990 (Public Law 101-576) and is composed\n  of the CFOs and Deputy CFOs of the 24 largest federal departments and\n  agencies, along with senior officials from the Office of Management and\n  Budget (OMB) and the Department of the Treasury. The Council works\n  collaboratively to improve federal financial management through shared\n\
  \  guidance, working groups, and inter-agency standards. While the CFO\n  Council itself does not operate a developer API program, its remit is\n  closely tied to the larger ecosystem of federal financial management\n  data and APIs administered by Treasury (USAspending.gov, Fiscal Service),\n  OMB (PaymentAccuracy.gov, MAX.gov), and GSA (Performance.gov, SAM.gov).\napis:\n  - aid: chief-financial-officers-council:cfoc-website\n    name: CFO Council Website\n    tags:\n      - Council\n      - Federal Financial Management\n      - Resources\n    humanURL: https://www.cfo.gov/\n    properties:\n      - url: https://www.cfo.gov/\n        type: Website\n      - url: https://www.cfo.gov/about-the-council/\n        type: About\n      - url: https://www.cfo.gov/resources/\n        type: Resources\n    description: >-\n      The cfo.gov public website is the official portal for the federal CFO\n      Council, hosting member rosters, council news, working-group outputs,\n      financial-management\
  \ policy guidance, and links to companion federal\n      financial-management resources.\n  - aid: chief-financial-officers-council:cfoc-working-groups\n    name: CFO Council Working Groups\n    tags:\n      - Inter-Agency\n      - Standards\n      - Working Groups\n    humanURL: https://www.cfo.gov/working-groups/\n    properties:\n      - url: https://www.cfo.gov/working-groups/\n        type: Website\n    description: >-\n      The CFO Council operates topical working groups covering areas such as\n      financial systems, internal control, grants management, payment\n      integrity, financial reporting, and data analytics. Working-group\n      products including white papers, playbooks, and recommended practices\n      are published on cfo.gov.\n  - aid: chief-financial-officers-council:cfoc-payment-integrity\n    name: PaymentAccuracy.gov (Payment Integrity)\n    tags:\n      - Improper Payments\n      - Open Data\n      - Payment Integrity\n    humanURL: https://www.paymentaccuracy.gov/\n\
  \    properties:\n      - url: https://www.paymentaccuracy.gov/\n        type: Website\n      - url: https://www.paymentaccuracy.gov/payment-accuracy-the-numbers/\n        type: Data\n    description: >-\n      PaymentAccuracy.gov is the OMB-maintained transparency site for\n      reporting government-wide improper payments and payment-integrity\n      activities. The site publishes downloadable agency-level payment\n      accuracy datasets that are referenced and used by CFO Council members\n      for benchmarking.\n  - aid: chief-financial-officers-council:usaspending\n    name: USAspending.gov API (Treasury)\n    tags:\n      - Federal Spending\n      - Open Data\n      - Treasury\n    humanURL: https://api.usaspending.gov/\n    properties:\n      - url: https://api.usaspending.gov/\n        type: Website\n      - url: https://api.usaspending.gov/docs/endpoints\n        type: Documentation\n      - url: https://api.usaspending.gov/api/v2/\n        type: BaseURL\n    description: >-\n\
  \      USAspending.gov is the Treasury-operated public source of accountable\n      federal spending data, exposing a comprehensive REST API for federal\n      awards, contracts, grants, sub-awards, and agency budget data. CFO\n      Council members rely on USAspending data quality and standards\n      (DAIMS) for transparency reporting.\n  - aid: chief-financial-officers-council:max-gov\n    name: MAX.gov / Performance.gov\n    tags:\n      - Performance Management\n      - Treasury Performance\n    humanURL: https://www.performance.gov/\n    properties:\n      - url: https://www.performance.gov/\n        type: Website\n      - url: https://www.performance.gov/about/\n        type: About\n    description: >-\n      Performance.gov is the OMB-administered public site for federal\n      cross-agency priority goals, agency strategic plans, and performance\n      reports. The CFO Council collaborates with OMB on financial-management\n      Cross-Agency Priority (CAP) goals reported through\
  \ Performance.gov.\ncommon:\n  - type: Website\n    url: https://www.cfo.gov/\n  - type: About\n    url: https://www.cfo.gov/about-the-council/\n  - type: Resources\n    url: https://www.cfo.gov/resources/\n  - type: WorkingGroups\n    url: https://www.cfo.gov/working-groups/\n  - type: News\n    url: https://www.cfo.gov/news/\n  - type: Events\n    url: https://www.cfo.gov/events/\n  - type: Members\n    url: https://www.cfo.gov/members/\n  - type: Contact\n    url: mailto:CFOC.support@gsa.gov\n  - type: Privacy Policy\n    url: https://www.cfo.gov/privacy-policy/\n  - type: AccessibilityStatement\n    url: https://www.cfo.gov/accessibility/\n  - type: USAspending\n    url: https://www.usaspending.gov/\n  - type: PaymentAccuracy\n    url: https://www.paymentaccuracy.gov/\n  - type: PerformanceGov\n    url: https://www.performance.gov/\n  - type: OMB\n    url: https://www.whitehouse.gov/omb/\n  - type: Treasury\n    url: https://home.treasury.gov/\n  - type: GSA\n    url: https://www.gsa.gov/\n\
  \  - name: ProgramAreas\n    type: ProgramAreas\n    data:\n      - name: Federal Financial Management\n      - name: Financial Reporting\n      - name: Internal Controls\n      - name: Payment Integrity\n      - name: Improper Payments\n      - name: Grants Management\n      - name: Financial Systems\n      - name: Workforce Development\n      - name: Data Standards (DAIMS)\n      - name: Cross-Agency Priority Goals\n  - name: WorkingGroups\n    type: WorkingGroups\n    data:\n      - name: Financial Management Workforce\n      - name: Financial Systems\n      - name: Grants Policy\n      - name: Internal Control\n      - name: Payment Integrity\n      - name: Performance and Accountability\n      - name: Financial Reporting\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chief-financial-officers-council/refs/heads/main/apis.yml
tags:
- Federal Financial Management
- Federal Government
- Finance
- Government
- OMB
- Treasury
url: https://raw.githubusercontent.com/api-evangelist/chief-financial-officers-council/refs/heads/main/apis.yml
use_cases: []
---
