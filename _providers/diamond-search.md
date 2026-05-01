---
api_count: 3
api_specs:
- filename: idex-onsite-full-feed-api-openapi.yml
  format: yaml
  label: IDEX Onsite Full Feed API
  slug: idex-onsite-full-feed-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/openapi/idex-onsite-full-feed-api-openapi.yml
- filename: idex-lab-grown-file-api-openapi.yml
  format: yaml
  label: IDEX Lab Grown File API
  slug: idex-lab-grown-file-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/openapi/idex-lab-grown-file-api-openapi.yml
- filename: idex-data-report-api-openapi.yml
  format: yaml
  label: IDEX Data Report API
  slug: idex-data-report-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/openapi/idex-data-report-api-openapi.yml
apis:
- description: In this natural diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of matching pre-filtered diamonds back in the requested format.
  name: IDEX Onsite Full Feed API
  slug: idex-onsite-full-feed-api
- description: In this lab grown diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of all filtered available diamonds back in a zipped CSV file.
  name: IDEX Lab Grown File API
  slug: idex-lab-grown-file-api
- description: In this API you will send an HTTP request with a date for which you want the report. You will get back a zipped CSV file. The file creation process may take a few minutes.
  name: IDEX Data Report API
  slug: idex-data-report-api
common:
- title: ''
  type: Newsroom
  url: http://www.idexonline.com/rssfeeds
- title: ''
  type: Login
  url: https://www.idexonline.com/ns24/auth/login.aspx
- title: ''
  type: Sign-Up
  url: https://www.idexonline.com/register.aspx
- title: ''
  type: PrivacyPolicy
  url: http://www.idexonline.com/Privacy
- title: ''
  type: TermsOfService
  url: http://www.idexonline.com/Conditions
created: '2024-11-13'
description: IDEX Online is the leading polished diamonds trading platform for professionals, providing unbiased, market-driven diamond pricing tools, news and research. The IDEX Onsite and Data Report APIs deliver natural diamond, lab grown diamond, and market data feeds to subscribers of the IDEX trading platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Diamond Search
skills: []
slug: diamond-search
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: diamond-search\nurl: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml\nname: Diamond Search\ndescription: >-\n  IDEX Online is the leading polished diamonds trading platform for professionals,\n  providing unbiased, market-driven diamond pricing tools, news and research. The\n  IDEX Onsite and Data Report APIs deliver natural diamond, lab grown diamond, and\n  market data feeds to subscribers of the IDEX trading platform.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\ntags:\n  - Diamonds\n  - Lab Grown\n  - Pricing\n  - Trading\ncreated: '2024-11-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: diamond-search:idex-onsite-full-feed-api\n    name: IDEX Onsite Full Feed API\n    humanURL: https://api.idexonline.com/Onsite/FullFeed\n    baseURL: https://api.idexonline.com/onsite/api\n    tags:\n      - Diamonds\n    \
  \  - Feed\n    properties:\n      - type: Documentation\n        url: https://api.idexonline.com/Onsite/FullFeed\n      - type: OpenAPI\n        url: openapi/idex-onsite-full-feed-api-openapi.yml\n    description: >-\n      In this natural diamond feed API you will send an HTTP request with the\n      requested identifiers in JSON, and you will get the full details of\n      matching pre-filtered diamonds back in the requested format. This service\n      is available as an add-on to all subscribers of the IDEX trading platform,\n      however, results may vary based on your subscription type and permissions.\n      Filters and markups can be set on IDEX.\n    contact:\n      - FN: IDEX Online Support\n        email: support@idexonline.com\n  - aid: diamond-search:idex-lab-grown-file-api\n    name: IDEX Lab Grown File API\n    humanURL: https://api.idexonline.com/Onsite/LabGrownFullFile\n    baseURL: https://api.idexonline.com/Onsite\n    tags:\n      - Diamonds\n      - Lab Grown\n   \
  \ properties:\n      - type: Documentation\n        url: https://api.idexonline.com/Onsite/LabGrownFullFile\n      - type: OpenAPI\n        url: openapi/idex-lab-grown-file-api-openapi.yml\n    description: >-\n      In this lab grown diamond feed API you will send an HTTP request with the\n      requested identifiers in JSON, and you will get the full details of all\n      filtered available diamonds back in a zipped CSV file. This service is\n      available as an add-on to all subscribers of the IDEX trading platform,\n      however, results may vary based on your subscription type and permissions.\n      This feed will return all lab grown diamond listings available for onsite\n      feeds from IDEX.\n    contact:\n      - FN: IDEX Online Support\n        email: support@idexonline.com\n  - aid: diamond-search:idex-data-report-api\n    name: IDEX Data Report API\n    humanURL: https://api.idexonline.com/IdexDataApi/Report3\n    baseURL: https://api.idexonline.com/IdexDataApi\n    tags:\n\
  \      - Diamonds\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://api.idexonline.com/IdexDataApi/Report3\n      - type: OpenAPI\n        url: openapi/idex-data-report-api-openapi.yml\n    description: >-\n      In this API you will send an HTTP request with a date for which you want\n      the report. You will get back a zipped CSV file. The file creation process\n      may take a few minutes.\n    contact:\n      - FN: IDEX Online Support\n        email: support@idexonline.com\ncommon:\n  - type: Newsroom\n    name: IDEX Online RSS Feeds\n    url: http://www.idexonline.com/rssfeeds\n    description: >-\n      Really Simple Syndication (RSS) is a format for content distribution. IDEX\n      Online offers a number of RSS feeds. Using an RSS reader, online service,\n      or your browser, you can subscribe for free to any of IDEX Online's\n      channels or track a specific subject.\n  - type: Login\n    name: IDEX Online Login\n    url: https://www.idexonline.com/ns24/auth/login.aspx\n\
  \  - type: Sign-Up\n    name: IDEX Online Sign-Up\n    url: https://www.idexonline.com/register.aspx\n  - type: PrivacyPolicy\n    name: IDEX Online Privacy Guarantees\n    url: http://www.idexonline.com/Privacy\n  - type: TermsOfService\n    name: IDEX Online Terms and Conditions\n    url: http://www.idexonline.com/Conditions\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml
tags:
- Diamonds
- Lab Grown
- Pricing
- Trading
url: https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml
use_cases: []
---
