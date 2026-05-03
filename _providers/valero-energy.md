---
api_count: 2
apis:
- description: 'Valero Energy Corporation SEC filings and financial data available through the SEC EDGAR system. Includes 10-K, 10-Q, earnings releases, and other regulatory filings. Accessible via the SEC EDGAR API '
  name: Valero Energy SEC EDGAR Data
  slug: sec-edgar
- description: Valero Energy investor relations portal providing access to financial data, quarterly results, SEC filings, stock information, dividend history, and corporate governance documents.
  name: Valero Investor Relations Portal
  slug: investor-relations
common:
- title: ''
  type: Website
  url: https://www.valero.com/
- title: ''
  type: InvestorRelations
  url: https://investorvalero.com/
- title: ''
  type: SECEdgar
  url: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001035002
- title: ''
  type: PrivacyPolicy
  url: https://www.valero.com/privacy-policy
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/vocabulary/valero-energy-vocabulary.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/json-schema/valero-energy-refinery-schema.json
created: '2026-03-21'
description: Valero Energy Corporation is the world's largest independent petroleum refiner and a leading producer of low-carbon transportation fuels. Headquartered in San Antonio, Texas, Valero operates 14 petroleum refineries with 3 million barrels per day capacity, 12 ethanol plants, and renewable diesel production facilities across the US, Canada, and UK. The company trades on NYSE as VLO and is a Fortune 100 company.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Valero Energy Context
  property_count: 3
  slug: valero-energy-context
layout: provider
modified: '2026-05-03'
name: Valero Energy
skills: []
slug: valero-energy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: valero-energy\nname: Valero Energy\ndescription: >-\n  Valero Energy Corporation is the world's largest independent petroleum refiner and\n  a leading producer of low-carbon transportation fuels. Headquartered in San Antonio,\n  Texas, Valero operates 14 petroleum refineries with 3 million barrels per day capacity,\n  12 ethanol plants, and renewable diesel production facilities across the US, Canada,\n  and UK. The company trades on NYSE as VLO and is a Fortune 100 company.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Energy\n  - Petroleum\n  - Refining\n  - Renewable Fuels\n  - Fortune 100\n  - Ethanol\n  - Renewable Diesel\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: valero-energy:sec-edgar\n    name: Valero Energy SEC EDGAR Data\n    description: >-\n      Valero\
  \ Energy Corporation SEC filings and financial data available through\n      the SEC EDGAR system. Includes 10-K, 10-Q, earnings releases, and other\n      regulatory filings. Accessible via the SEC EDGAR API using CIK 0001035002.\n    humanURL: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001035002\n    tags:\n      - SEC\n      - EDGAR\n      - Financial Data\n      - Regulatory Filings\n      - Investor Relations\n    properties:\n      - type: Documentation\n        url: https://efts.sec.gov/LATEST/search-index?q=%22valero%22&dateRange=custom&startdt=2024-01-01\n      - type: InvestorRelations\n        url: https://investorvalero.com/\n      - type: SECFilings\n        url: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001035002&type=10-K&dateb=&owner=include&count=10\n  - aid: valero-energy:investor-relations\n    name: Valero Investor Relations Portal\n    description: >-\n      Valero Energy investor relations portal providing access to financial\
  \ data,\n      quarterly results, SEC filings, stock information, dividend history, and\n      corporate governance documents.\n    humanURL: https://investorvalero.com/\n    tags:\n      - Investor Relations\n      - Financial Data\n      - Stock Data\n      - Dividends\n    properties:\n      - type: InvestorRelations\n        url: https://investorvalero.com/\n      - type: StockQuote\n        url: https://investorvalero.com/stock-information/stock-quote\n      - type: SECFilings\n        url: https://investorvalero.com/financials/sec-filings\ncommon:\n  - type: Website\n    url: https://www.valero.com/\n  - type: InvestorRelations\n    url: https://investorvalero.com/\n  - type: SECEdgar\n    url: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001035002\n  - type: PrivacyPolicy\n    url: https://www.valero.com/privacy-policy\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/vocabulary/valero-energy-vocabulary.yml\n\
  \  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/json-schema/valero-energy-refinery-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/apis.yml
tags:
- Energy
- Petroleum
- Refining
- Renewable Fuels
- Fortune 100
- Ethanol
- Renewable Diesel
url: https://raw.githubusercontent.com/api-evangelist/valero-energy/refs/heads/main/apis.yml
use_cases: []
---
