---
api_count: 5
apis:
- description: The 2026 GAAP Financial Reporting Taxonomy (GRT) is the official XBRL taxonomy maintained by FASB for SEC financial filings. It incorporates updates for FASB accounting standards published through Dec
  name: US GAAP Financial Reporting Taxonomy 2026
  slug: ''
- description: The SEC EDGAR XBRL APIs provide free, real-time access to structured financial data from public company filings. APIs include company submissions, company facts (all XBRL disclosures), company concept
  name: SEC EDGAR XBRL API
  slug: ''
- description: International Financial Reporting Standards (IFRS) are global accounting standards issued by the International Accounting Standards Board (IASB). IFRS standards govern the financial reporting of compa
  name: IFRS Accounting Standards
  slug: ''
- description: The FASB Accounting Standards Codification (ASC) is the single source of authoritative nongovernmental U.S. GAAP. Organized into Topics, Subtopics, Sections, and Paragraphs, the ASC provides the compl
  name: FASB Accounting Standards Codification
  slug: ''
- description: eXtensible Business Reporting Language (XBRL) is an open international standard for digital business reporting maintained by XBRL International. It enables the exchange of business information in a st
  name: XBRL International Specification
  slug: ''
common:
- title: Financial Accounting Standards Board
  type: Website
  url: https://www.fasb.org/
- title: IFRS Foundation
  type: Website
  url: https://www.ifrs.org/
- title: XBRL US
  type: Website
  url: https://xbrl.us/
- title: XBRL GitHub Organization
  type: GitHubOrganization
  url: https://github.com/xbrl
- title: SEC EDGAR Data Portal
  type: Tools
  url: https://data.sec.gov/
- title: Accounting Standards JSON-LD Context
  type: JSON-LD
  url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/json-ld/accounting-standards-context.jsonld
- title: Accounting Standards Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/vocabulary/accounting-standards-vocabulary.yaml
created: '2025-01-01'
description: Accounting Standards are the formal rules and guidelines that govern how financial transactions and statements are recorded, reported, and disclosed. They ensure consistency, transparency, and comparability across financial reports, and include frameworks like GAAP and IFRS. Digital reporting standards like XBRL enable structured, machine-readable financial filings.
features:
- description: XBRL taxonomies enable machine-readable financial statement reporting that regulators, investors, and analysts can process programmatically.
  name: Structured Financial Reporting
- description: The FASB ASC provides the single authoritative source of US GAAP organized by topic for consistent application across entities.
  name: US GAAP Codification
- description: IFRS provides globally harmonized accounting standards enabling cross-border financial comparability in over 140 jurisdictions.
  name: International Standards Harmonization
- description: SEC EDGAR XBRL APIs provide real-time access to structured financial data from all public company filings as JSON.
  name: Real-Time Financial Data Access
- description: The Data Quality Committee Rules Taxonomy (DQCRT) provides machine-enforceable rules for validating XBRL-tagged financial data.
  name: Data Quality Rules
- description: Annual FASB taxonomy releases incorporate new accounting standards and ensure accurate representation of current GAAP requirements.
  name: Taxonomy Versioning
image: /assets/icons/accounting-standards.png
integrations:
- description: The SEC's public filing database mandating XBRL for financial disclosures, providing free API access to all structured filing data.
  name: SEC EDGAR
- description: Industry consortium supporting XBRL adoption in the US, providing taxonomy resources, training, and data quality rule development.
  name: XBRL US
- description: Human-readable HTML combining with machine-readable XBRL tags, now required by the SEC for financial statement filings.
  name: iXBRL (Inline XBRL)
- description: European Securities and Markets Authority mandating IFRS XBRL reporting under the European Single Electronic Format (ESEF).
  name: ESMA / European Reporting
- description: Deloitte's Accounting Research Tool providing access to FASB ASC and IFRS standards with interpretive guidance and examples.
  name: Deloitte DART
jsonld:
- class_count: 6
  name: Accounting Standards Context
  property_count: 39
  slug: accounting-standards-context
layout: provider
modified: '2026-04-19'
name: Accounting Standards
skills: []
slug: accounting-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: accounting-standards\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/apis.yml\nname: Accounting Standards\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounting Standards\n  - Finance\n  - GAAP\n  - IFRS\n  - XBRL\n  - Financial Reporting\n  - SEC\n  - FASB\ndescription: >-\n  Accounting Standards are the formal rules and guidelines that govern how\n  financial transactions and statements are recorded, reported, and disclosed.\n  They ensure consistency, transparency, and comparability across financial\n  reports, and include frameworks like GAAP and IFRS. Digital reporting\n  standards like XBRL enable structured, machine-readable financial filings.\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name: US GAAP Financial Reporting Taxonomy 2026\n    description: >-\n      The 2026 GAAP Financial Reporting Taxonomy (GRT)\
  \ is the official XBRL\n      taxonomy maintained by FASB for SEC financial filings. It incorporates\n      updates for FASB accounting standards published through December 1, 2025.\n      The taxonomy provides structured element definitions for US Generally\n      Accepted Accounting Principles (GAAP) financial statement reporting,\n      available in XSD format with namespace http://fasb.org/us-gaap/2026.\n    humanURL: https://xbrl.us/xbrl-taxonomy/2026-us-gaap/\n    baseURL: https://xbrl.fasb.org/us-gaap/2026/\n    tags:\n      - GAAP\n      - XBRL\n      - FASB\n      - SEC\n      - Financial Reporting\n    properties:\n      - type: Documentation\n        url: https://xbrl.us/xbrl-taxonomy/2026-us-gaap/\n      - type: Specification\n        url: https://fasb.org/standards\n      - type: Documentation\n        url: https://asc.fasb.org/\n        title: FASB Accounting Standards Codification\n  - name: SEC EDGAR XBRL API\n    description: >-\n      The SEC EDGAR XBRL APIs provide free,\
  \ real-time access to structured\n      financial data from public company filings. APIs include company\n      submissions, company facts (all XBRL disclosures), company concepts\n      (individual taxonomy tags per company), and aggregated XBRL frames across\n      all filers. Data is returned in JSON and covers US-GAAP, IFRS, DEI, and\n      SRT taxonomies. Rate limit is 10 requests/second with required User-Agent\n      header.\n    humanURL: https://www.sec.gov/about/developer-resources\n    baseURL: https://data.sec.gov/\n    tags:\n      - SEC\n      - EDGAR\n      - XBRL\n      - Financial Data\n      - Open Data\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.sec.gov/about/developer-resources\n      - type: APIReference\n        url: https://www.sec.gov/search-filings/edgar-application-programming-interfaces\n      - type: RateLimits\n        url: https://www.sec.gov/about/developer-resources\n        title: 10 requests/second, User-Agent\
  \ header required\n  - name: IFRS Accounting Standards\n    description: >-\n      International Financial Reporting Standards (IFRS) are global accounting\n      standards issued by the International Accounting Standards Board (IASB).\n      IFRS standards govern the financial reporting of companies in over 140\n      jurisdictions. The IFRS Foundation publishes the IFRS Taxonomy for\n      structured XBRL tagging of IFRS financial statements, referenced by the\n      SEC for foreign private issuers.\n    humanURL: https://www.ifrs.org/issued-standards/list-of-standards/\n    baseURL: https://www.ifrs.org/\n    tags:\n      - IFRS\n      - IASB\n      - International\n      - Financial Reporting\n      - XBRL\n    properties:\n      - type: Documentation\n        url: https://www.ifrs.org/issued-standards/list-of-standards/\n      - type: Specification\n        url: https://www.sec.gov/data-research/standard-taxonomies/ifrs-taxonomy\n        title: IFRS Taxonomy via SEC\n  - name: FASB\
  \ Accounting Standards Codification\n    description: >-\n      The FASB Accounting Standards Codification (ASC) is the single source of\n      authoritative nongovernmental U.S. GAAP. Organized into Topics, Subtopics,\n      Sections, and Paragraphs, the ASC provides the complete set of accounting\n      guidance for US GAAP. The ASC online provides search, navigation, and\n      research tools for accounting practitioners.\n    humanURL: https://asc.fasb.org/\n    baseURL: https://asc.fasb.org/\n    tags:\n      - GAAP\n      - FASB\n      - Codification\n      - US Accounting\n    properties:\n      - type: Documentation\n        url: https://asc.fasb.org/\n      - type: Documentation\n        url: https://www.fasb.org/standards/accounting-standard-updates\n        title: Accounting Standards Updates\n  - name: XBRL International Specification\n    description: >-\n      eXtensible Business Reporting Language (XBRL) is an open international\n      standard for digital business reporting\
  \ maintained by XBRL International.\n      It enables the exchange of business information in a structured,\n      machine-readable format. XBRL is required by the SEC for financial\n      filings and adopted by regulators worldwide including ESMA, EIOPA, and\n      EBA.\n    humanURL: https://www.xbrl.org/\n    baseURL: https://www.xbrl.org/\n    tags:\n      - XBRL\n      - Digital Reporting\n      - Financial Data\n      - Open Standard\n    properties:\n      - type: Documentation\n        url: https://www.xbrl.org/\n      - type: Specification\n        url: https://www.xbrl.org/specification/gnl/rec-2003-12-31/gnl-2003-12-31.htm\n        title: XBRL 2.1 Specification\ncommon:\n  - type: Website\n    url: https://www.fasb.org/\n    title: Financial Accounting Standards Board\n  - type: Website\n    url: https://www.ifrs.org/\n    title: IFRS Foundation\n  - type: Website\n    url: https://xbrl.us/\n    title: XBRL US\n  - type: GitHubOrganization\n    url: https://github.com/xbrl\n\
  \    title: XBRL GitHub Organization\n  - type: Tools\n    url: https://data.sec.gov/\n    title: SEC EDGAR Data Portal\n  - type: Features\n    data:\n      - name: Structured Financial Reporting\n        description: >-\n          XBRL taxonomies enable machine-readable financial statement reporting\n          that regulators, investors, and analysts can process programmatically.\n      - name: US GAAP Codification\n        description: >-\n          The FASB ASC provides the single authoritative source of US GAAP\n          organized by topic for consistent application across entities.\n      - name: International Standards Harmonization\n        description: >-\n          IFRS provides globally harmonized accounting standards enabling\n          cross-border financial comparability in over 140 jurisdictions.\n      - name: Real-Time Financial Data Access\n        description: >-\n          SEC EDGAR XBRL APIs provide real-time access to structured financial\n          data from all\
  \ public company filings as JSON.\n      - name: Data Quality Rules\n        description: >-\n          The Data Quality Committee Rules Taxonomy (DQCRT) provides\n          machine-enforceable rules for validating XBRL-tagged financial data.\n      - name: Taxonomy Versioning\n        description: >-\n          Annual FASB taxonomy releases incorporate new accounting standards and\n          ensure accurate representation of current GAAP requirements.\n  - type: UseCases\n    data:\n      - name: Public Company Financial Reporting\n        description: >-\n          Companies use XBRL taxonomies when filing 10-K, 10-Q, and 8-K reports\n          with the SEC, ensuring structured, machine-readable disclosure.\n      - name: Financial Data Analysis\n        description: >-\n          Investors and analysts use SEC EDGAR XBRL APIs to retrieve structured\n          financial statements for quantitative analysis and screening.\n      - name: Accounting Research\n        description: >-\n \
  \         CPAs and finance professionals use the FASB ASC to research applicable\n          US GAAP guidance for specific transaction types and disclosures.\n      - name: Regulatory Compliance\n        description: >-\n          Finance teams implement GAAP or IFRS accounting standards to meet\n          regulatory requirements and auditor expectations.\n      - name: FinTech Integration\n        description: >-\n          FinTech platforms integrate with SEC EDGAR APIs to ingest standardized\n          financial data for valuation models, credit analysis, and benchmarking.\n  - type: Integrations\n    data:\n      - name: SEC EDGAR\n        description: >-\n          The SEC's public filing database mandating XBRL for financial\n          disclosures, providing free API access to all structured filing data.\n      - name: XBRL US\n        description: >-\n          Industry consortium supporting XBRL adoption in the US, providing\n          taxonomy resources, training, and data quality\
  \ rule development.\n      - name: iXBRL (Inline XBRL)\n        description: >-\n          Human-readable HTML combining with machine-readable XBRL tags, now\n          required by the SEC for financial statement filings.\n      - name: ESMA / European Reporting\n        description: >-\n          European Securities and Markets Authority mandating IFRS XBRL\n          reporting under the European Single Electronic Format (ESEF).\n      - name: Deloitte DART\n        description: >-\n          Deloitte's Accounting Research Tool providing access to FASB ASC and\n          IFRS standards with interpretive guidance and examples.\n  - type: JSON-LD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/json-ld/accounting-standards-context.jsonld\n    title: Accounting Standards JSON-LD Context\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/vocabulary/accounting-standards-vocabulary.yaml\n\
  \    title: Accounting Standards Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/apis.yml
tags:
- Accounting Standards
- Finance
- GAAP
- IFRS
- XBRL
- Financial Reporting
- SEC
- FASB
url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/apis.yml
use_cases:
- description: Companies use XBRL taxonomies when filing 10-K, 10-Q, and 8-K reports with the SEC, ensuring structured, machine-readable disclosure.
  name: Public Company Financial Reporting
- description: Investors and analysts use SEC EDGAR XBRL APIs to retrieve structured financial statements for quantitative analysis and screening.
  name: Financial Data Analysis
- description: CPAs and finance professionals use the FASB ASC to research applicable US GAAP guidance for specific transaction types and disclosures.
  name: Accounting Research
- description: Finance teams implement GAAP or IFRS accounting standards to meet regulatory requirements and auditor expectations.
  name: Regulatory Compliance
- description: FinTech platforms integrate with SEC EDGAR APIs to ingest standardized financial data for valuation models, credit analysis, and benchmarking.
  name: FinTech Integration
---
