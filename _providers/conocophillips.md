---
api_count: 3
apis:
- description: The ConocoPhillips vendor relations digital channel where suppliers check invoice status, manage purchase orders via the GEP portal, and collaborate via the Taulia Supplier Portal. ConocoPhillips does
  name: ConocoPhillips Vendor Relations Portal
  slug: vendor-relations-portal
- description: 'ConocoPhillips licenses its Optimized Cascade liquefaction process and related LNG technologies to third-party LNG project developers. The licensing program operates as a contracted technical service '
  name: ConocoPhillips LNG Technology and Licensing
  slug: lng-technology-licensing
- description: 'A web-based tool that lets analysts and stakeholders assemble custom sustainability reports from ConocoPhillips''s published ESG data (emissions, safety, governance, etc.). Output is a curated PDF/web '
  name: ConocoPhillips Custom Sustainability Report Builder
  slug: sustainability-report-builder
common:
- title: ''
  type: Website
  url: https://www.conocophillips.com
- title: ''
  type: Investor Relations
  url: https://www.conocophillips.com/investors/
- title: ''
  type: Vendor Portal
  url: https://vendors.conocophillips.com/
- title: ''
  type: Sustainability
  url: https://www.conocophillips.com/sustainability/
- title: ''
  type: News
  url: https://www.conocophillips.com/news-media/
- title: ''
  type: Careers
  url: https://www.conocophillips.com/careers/
- title: ''
  type: Operations
  url: https://www.conocophillips.com/operations/
- title: ''
  type: Contact
  url: https://www.conocophillips.com/about-us/contact-us/
created: '2026-03-21'
description: ConocoPhillips is a leading global exploration and production company, headquartered in Houston, Texas, that is uniquely equipped to deliver reliable, responsibly produced oil and natural gas. The company operates in more than a dozen countries with conventional and unconventional crude oil, natural gas, LNG, and natural gas liquids assets. ConocoPhillips does not publish public developer APIs; its external digital surface is organized around an investor relations portal, a vendor relations portal (powered by third-party platforms such as GEP and Taulia), an LNG technology and licensing program, and a custom sustainability report builder.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: ConocoPhillips
skills: []
slug: conocophillips
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: conocophillips\nname: ConocoPhillips\ndescription: >-\n  ConocoPhillips is a leading global exploration and production company,\n  headquartered in Houston, Texas, that is uniquely equipped to deliver\n  reliable, responsibly produced oil and natural gas. The company operates\n  in more than a dozen countries with conventional and unconventional crude\n  oil, natural gas, LNG, and natural gas liquids assets. ConocoPhillips\n  does not publish public developer APIs; its external digital surface is\n  organized around an investor relations portal, a vendor relations portal\n  (powered by third-party platforms such as GEP and Taulia), an LNG\n  technology and licensing program, and a custom sustainability report\n  builder.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/conocophillips/refs/heads/main/apis.yml\ncreated: '2026-03-21'\n\
  modified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n  - Crude Oil\n  - Energy\n  - Exploration and Production\n  - LNG\n  - Natural Gas\n  - Oil and Gas\n  - Sustainability\n  - Upstream\n  - Vendor Portal\napis:\n  - aid: conocophillips:vendor-relations-portal\n    name: ConocoPhillips Vendor Relations Portal\n    description: >-\n      The ConocoPhillips vendor relations digital channel where suppliers\n      check invoice status, manage purchase orders via the GEP portal, and\n      collaborate via the Taulia Supplier Portal. ConocoPhillips does not\n      currently publish a public REST API for vendor data; integration is\n      mediated through the underlying GEP and Taulia platforms.\n    humanURL: https://vendors.conocophillips.com/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Procurement\n      - Supplier Portal\n      - Vendor\n    properties:\n      - type: Documentation\n        url: https://vendors.conocophillips.com/\n\
  \      - type: GEP Portal\n        url: https://www.gep.com/\n      - type: Taulia\n        url: https://www.taulia.com/\n    x-features:\n      - Invoice Status\n      - Purchase Order Acknowledgement\n      - ACH/EFT Payment Setup\n      - Supplier Communication\n    x-use-cases:\n      - Look up invoice status as a ConocoPhillips supplier\n      - Acknowledge purchase orders via GEP\n      - Manage early-payment options through Taulia\n  - aid: conocophillips:lng-technology-licensing\n    name: ConocoPhillips LNG Technology and Licensing\n    description: >-\n      ConocoPhillips licenses its Optimized Cascade liquefaction process\n      and related LNG technologies to third-party LNG project developers.\n      The licensing program operates as a contracted technical service\n      rather than a public API, with technical documentation and\n      engineering support delivered to licensed partners.\n    humanURL: https://www.conocophillips.com/operations/lng-technology-licensing/\n \
  \   image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Licensing\n      - LNG\n      - Technology\n    properties:\n      - type: Documentation\n        url: https://www.conocophillips.com/operations/lng-technology-licensing/\n    x-features:\n      - Optimized Cascade Process\n      - LNG Plant Design Support\n      - Licensing Agreements\n    x-use-cases:\n      - License LNG liquefaction technology for new projects\n      - Access engineering support for cascade-process plants\n  - aid: conocophillips:sustainability-report-builder\n    name: ConocoPhillips Custom Sustainability Report Builder\n    description: >-\n      A web-based tool that lets analysts and stakeholders assemble custom\n      sustainability reports from ConocoPhillips's published ESG data\n      (emissions, safety, governance, etc.). Output is a curated PDF/web\n      report rather than a developer API.\n    humanURL: https://www.conocophillips.com/sustainability/\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - ESG\n      - Reporting\n      - Sustainability\n    properties:\n      - type: Documentation\n        url: https://www.conocophillips.com/sustainability/\n    x-features:\n      - Custom Report Builder\n      - ESG Data Library\n      - Downloadable Reports\n    x-use-cases:\n      - Build custom ESG reports for investor analysis\n      - Compare ConocoPhillips sustainability metrics over time\ncommon:\n  - type: Website\n    url: https://www.conocophillips.com\n  - type: Investor Relations\n    url: https://www.conocophillips.com/investors/\n  - type: Vendor Portal\n    url: https://vendors.conocophillips.com/\n  - type: Sustainability\n    url: https://www.conocophillips.com/sustainability/\n  - type: News\n    url: https://www.conocophillips.com/news-media/\n  - type: Careers\n    url: https://www.conocophillips.com/careers/\n  - type: Operations\n    url: https://www.conocophillips.com/operations/\n\
  \  - type: Contact\n    url: https://www.conocophillips.com/about-us/contact-us/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/conocophillips/refs/heads/main/apis.yml
tags:
- Crude Oil
- Energy
- Exploration and Production
- LNG
- Natural Gas
- Oil and Gas
- Sustainability
- Upstream
- Vendor Portal
url: https://raw.githubusercontent.com/api-evangelist/conocophillips/refs/heads/main/apis.yml
use_cases: []
---
