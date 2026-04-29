---
api_count: 3
apis:
- description: CFIUS publishes an annual report to Congress summarizing covered transactions reviewed during the prior calendar year, statistics on notices, declarations, withdrawn cases, and presidential decisions.
  name: CFIUS Annual Report to Congress
  slug: annual-reports
- description: 'CFIUS provides guidance for parties submitting declarations (short-form filings) and joint voluntary notices (full-form filings) for covered transactions. The Treasury maintains forms, FAQs, and case '
  name: CFIUS Declarations and Notices Guidance
  slug: declarations-and-notices
- description: The CFIUS regulatory framework is published in 31 CFR Parts 800, 801, and 802, and is anchored in Section 721 of the Defense Production Act as amended by FIRRMA. Regulations and statutes are available
  name: CFIUS Regulations and Statutes
  slug: regulations
common:
- title: ''
  type: Website
  url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius
- title: ''
  type: Documentation
  url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance
- title: ''
  type: Reference
  url: https://www.ecfr.gov/current/title-31/subtitle-B/chapter-VIII
- title: ''
  type: Reports
  url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-reports-and-tables
- title: ''
  type: FAQ
  url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-frequently-asked-questions-faqs
created: '2024-12-03'
description: The Committee on Foreign Investment in the United States (CFIUS) is an inter-agency committee chaired by the U.S. Department of the Treasury that reviews certain foreign investment transactions for national security implications. CFIUS reviews are governed by the Defense Production Act and Section 721, and were significantly strengthened by the Foreign Investment Risk Review Modernization Act of 2018 (FIRRMA). On September 15, 2022, President Biden issued Executive Order 14083 directing CFIUS to focus on emerging national security risks. CFIUS work is largely confidential, and the public-facing surface is limited to regulations, annual reports to Congress, FAQs, declarations and notices guidance, and case studies.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Committee on Foreign Investment in the United States
skills: []
slug: committee-on-foreign-investment-in-the-united-states
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: committee-on-foreign-investment-in-the-united-states\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/committee-on-foreign-investment-in-the-united-states/refs/heads/main/apis.yml\nname: Committee on Foreign Investment in the United States\nx-type: government\ndescription: >-\n  The Committee on Foreign Investment in the United States (CFIUS) is an\n  inter-agency committee chaired by the U.S. Department of the Treasury that\n  reviews certain foreign investment transactions for national security\n  implications. CFIUS reviews are governed by the Defense Production Act and\n  Section 721, and were significantly strengthened by the Foreign Investment\n  Risk Review Modernization Act of 2018 (FIRRMA). On September 15, 2022,\n  President Biden issued Executive Order 14083 directing CFIUS to focus on\n  emerging national security risks. CFIUS work is largely confidential, and\n  the public-facing surface is limited to regulations, annual reports to\n  Congress,\
  \ FAQs, declarations and notices guidance, and case studies.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CFIUS\n  - Federal Government\n  - Foreign Investment\n  - National Security\n  - Regulation\n  - Treasury\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: committee-on-foreign-investment-in-the-united-states:annual-reports\n    name: CFIUS Annual Report to Congress\n    description: >-\n      CFIUS publishes an annual report to Congress summarizing covered\n      transactions reviewed during the prior calendar year, statistics on\n      notices, declarations, withdrawn cases, and presidential decisions.\n      Annual reports are released as PDF documents and contain the most\n      complete public statistics on CFIUS activity.\n    humanURL: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-reports-and-tables\n    baseURL:\
  \ https://home.treasury.gov\n    tags:\n      - Annual Report\n      - PDF\n      - Statistics\n      - Transparency\n    properties:\n      - type: Documentation\n        url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-reports-and-tables\n      - type: Reference\n        url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius\n    x-features:\n      - Annual aggregate statistics on covered transaction notices\n      - Counts of investigations, withdrawals, and presidential actions\n      - Industry and country-of-origin breakdowns of reviewed transactions\n      - Released as PDF; no machine-readable API or feed\n    x-useCases:\n      - Researching trends in CFIUS reviews over time\n      - Benchmarking national security review activity by sector\n      - Informing policy analysis and academic research\n  - aid: committee-on-foreign-investment-in-the-united-states:declarations-and-notices\n\
  \    name: CFIUS Declarations and Notices Guidance\n    description: >-\n      CFIUS provides guidance for parties submitting declarations (short-form\n      filings) and joint voluntary notices (full-form filings) for covered\n      transactions. The Treasury maintains forms, FAQs, and case examples but\n      filings themselves are confidential and are not exposed via any public\n      API.\n    humanURL: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance\n    baseURL: https://home.treasury.gov\n    tags:\n      - Compliance\n      - Declarations\n      - Filings\n      - Guidance\n      - Notices\n    properties:\n      - type: Documentation\n        url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance\n      - type: Reference\n        url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-frequently-asked-questions-faqs\n\
  \    x-features:\n      - Guidance on covered investments under FIRRMA\n      - FAQs covering scope, mandatory filings, and timing\n      - Forms for declarations and joint voluntary notices\n      - Filings are confidential; no public API\n    x-useCases:\n      - Determining whether a transaction is subject to mandatory filing\n      - Preparing declarations or joint voluntary notices\n      - Advising clients on CFIUS compliance and timing\n  - aid: committee-on-foreign-investment-in-the-united-states:regulations\n    name: CFIUS Regulations and Statutes\n    description: >-\n      The CFIUS regulatory framework is published in 31 CFR Parts 800, 801,\n      and 802, and is anchored in Section 721 of the Defense Production Act\n      as amended by FIRRMA. Regulations and statutes are available through\n      the Federal Register, eCFR, and govinfo.gov, all of which expose\n      machine-readable formats such as XML, JSON, and bulk data.\n    humanURL: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance\n\
  \    baseURL: https://www.ecfr.gov\n    tags:\n      - eCFR\n      - FIRRMA\n      - Federal Register\n      - Regulations\n      - Statutes\n    properties:\n      - type: Documentation\n        url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance\n      - type: Reference\n        url: https://www.ecfr.gov/current/title-31/subtitle-B/chapter-VIII\n      - type: Reference\n        url: https://www.federalregister.gov/agencies/foreign-investment-in-the-united-states-office-of-investment-security\n    x-features:\n      - 31 CFR Parts 800, 801, and 802 cover the CFIUS regulatory regime\n      - eCFR provides machine-readable XML and JSON of current regulations\n      - Federal Register publishes proposed and final rules with metadata\n      - govinfo.gov offers bulk data access to the Code of Federal Regulations\n    x-useCases:\n      - Tracking changes to CFIUS regulations over time\n      - Building\
  \ tooling that ingests regulatory text from eCFR or govinfo\n      - Cross-referencing CFIUS regulations with other federal rules\ncommon:\n  - type: Website\n    url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius\n  - type: Documentation\n    url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-laws-and-guidance\n  - type: Reference\n    url: https://www.ecfr.gov/current/title-31/subtitle-B/chapter-VIII\n  - type: Reports\n    url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-reports-and-tables\n  - type: FAQ\n    url: https://home.treasury.gov/policy-issues/international/the-committee-on-foreign-investment-in-the-united-states-cfius/cfius-frequently-asked-questions-faqs\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/committee-on-foreign-investment-in-the-united-states/refs/heads/main/apis.yml
tags:
- CFIUS
- Federal Government
- Foreign Investment
- National Security
- Regulation
- Treasury
url: https://raw.githubusercontent.com/api-evangelist/committee-on-foreign-investment-in-the-united-states/refs/heads/main/apis.yml
use_cases: []
---
