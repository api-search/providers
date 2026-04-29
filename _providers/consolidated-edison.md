---
api_count: 2
apis:
- description: Green Button Connect My Data is the OAuth2-based ESPI service that lets Con Edison customers authorize a registered third party to receive their interval energy usage and account data on a recurring b
  name: Green Button Connect My Data
  slug: green-button-connect
- description: 'Customer-driven file export that lets Con Edison residential and small commercial accounts download up to one year of smart-meter interval data as CSV or ESPI XML directly from the My Account portal. '
  name: Green Button Download My Data
  slug: green-button-download
common:
- title: ''
  type: Website
  url: https://www.coned.com
- title: ''
  type: Customer Portal
  url: https://www.coned.com/en/accounts-billing
- title: ''
  type: Become a Third Party
  url: https://www.coned.com/en/accounts-billing/share-energy-usage-data/become-a-third-party
- title: ''
  type: Share My Data Overview
  url: https://www.coned.com/en/accounts-billing/share-energy-usage-data/share-my-data
- title: ''
  type: Investor Relations
  url: https://investor.conedison.com
- title: ''
  type: Careers
  url: https://www.conedjobs.com
- title: ''
  type: Privacy Policy
  url: https://www.coned.com/en/about-us/privacy-statement
- title: ''
  type: Terms of Service
  url: https://www.coned.com/en/about-us/terms-of-use
- title: ''
  type: Support
  url: https://www.coned.com/en/contact-us
created: '2026-03-21'
description: Consolidated Edison, Inc. (Con Edison) is a Fortune 500 holding company that, through its subsidiaries, provides electric, natural gas, and steam service to customers in New York City and Westchester County. Con Edison does not publish a general-purpose developer portal; programmatic data access is delivered through the Green Button Connect My Data (GBC) program, which lets authorized third parties retrieve customer energy usage data via the NAESB Energy Services Provider Interface (ESPI) standard once the customer grants consent through Con Edison's authorization portal.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Consolidated Edison
skills: []
slug: consolidated-edison
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consolidated-edison\nname: Consolidated Edison\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/consolidated-edison/refs/heads/main/apis.yml\ntags:\n  - Energy\n  - Fortune 500\n  - Green Button\n  - Natural Gas\n  - New York\n  - Steam\n  - Utility\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: company\ndescription: >-\n  Consolidated Edison, Inc. (Con Edison) is a Fortune 500 holding company that,\n  through its subsidiaries, provides electric, natural gas, and steam service\n  to customers in New York City and Westchester County. Con Edison does not\n  publish a general-purpose developer portal; programmatic data access is\n  delivered through the Green Button Connect My Data (GBC) program, which lets\n  authorized third parties retrieve customer energy usage data via the NAESB\n  Energy\
  \ Services Provider Interface (ESPI) standard once the customer grants\n  consent through Con Edison's authorization portal.\napis:\n  - aid: consolidated-edison:green-button-connect\n    name: Green Button Connect My Data\n    tags:\n      - Energy\n      - Green Button\n      - OAuth2\n      - Smart Meter\n      - Usage Data\n    humanURL: >-\n      https://www.coned.com/en/accounts-billing/share-energy-usage-data/become-a-third-party\n    properties:\n      - url: >-\n          https://www.coned.com/en/accounts-billing/share-energy-usage-data/become-a-third-party\n        type: Documentation\n      - url: >-\n          https://www.coned.com/en/business-partners/access-customer-data\n        type: Authentication\n    description: >-\n      Green Button Connect My Data is the OAuth2-based ESPI service that lets\n      Con Edison customers authorize a registered third party to receive their\n      interval energy usage and account data on a recurring basis. Third\n      parties register\
  \ through Con Edison's onboarding process to obtain\n      client credentials, then exchange them for access tokens that retrieve\n      ESPI Atom/XML resources for usage points, meter readings, and electric\n      power usage summaries.\n  - aid: consolidated-edison:green-button-download\n    name: Green Button Download My Data\n    tags:\n      - CSV\n      - Energy\n      - Green Button\n      - Self-Service\n      - Usage Data\n      - XML\n    humanURL: >-\n      https://www.coned.com/en/save-money/make-better-energychoices-with-green-button\n    properties:\n      - url: >-\n          https://www.coned.com/en/save-money/make-better-energychoices-with-green-button\n        type: Documentation\n    description: >-\n      Customer-driven file export that lets Con Edison residential and small\n      commercial accounts download up to one year of smart-meter interval data\n      as CSV or ESPI XML directly from the My Account portal. Useful for\n      one-shot analytics, audits, and migrating\
  \ data into third-party tools\n      without requiring an OAuth integration.\ncommon:\n  - type: Website\n    url: https://www.coned.com\n  - type: Customer Portal\n    url: https://www.coned.com/en/accounts-billing\n  - type: Become a Third Party\n    url: >-\n      https://www.coned.com/en/accounts-billing/share-energy-usage-data/become-a-third-party\n  - type: Share My Data Overview\n    url: >-\n      https://www.coned.com/en/accounts-billing/share-energy-usage-data/share-my-data\n  - type: Investor Relations\n    url: https://investor.conedison.com\n  - type: Careers\n    url: https://www.conedjobs.com\n  - type: Privacy Policy\n    url: https://www.coned.com/en/about-us/privacy-statement\n  - type: Terms of Service\n    url: https://www.coned.com/en/about-us/terms-of-use\n  - type: Support\n    url: https://www.coned.com/en/contact-us\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consolidated-edison/refs/heads/main/apis.yml
tags:
- Energy
- Fortune 500
- Green Button
- Natural Gas
- New York
- Steam
- Utility
url: https://raw.githubusercontent.com/api-evangelist/consolidated-edison/refs/heads/main/apis.yml
use_cases: []
---
