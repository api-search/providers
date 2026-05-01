---
api_count: 2
apis:
- description: Retrieve key information about schools across the United States based on proximity to a location or filtered by name, type, and more. Returns school names, addresses, grades offered, type, and website
  name: GreatSchools School Essentials API
  slug: school-essentials
- description: Builds on School Essentials by adding GreatSchools School Rating Bands (below average, average, above average) to assess school quality.
  name: GreatSchools School Quality API
  slug: school-quality
common:
- title: ''
  type: Website
  url: https://www.greatschools.org
- title: ''
  type: Developer Hub
  url: https://www.greatschools.org/api
created: '2026-03-16'
description: GreatSchools provides school information, ratings, and quality data via its Developer Hub APIs, including the School Essentials API for school details and the School Quality API for GreatSchools rating bands.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: GreatSchools
skills: []
slug: greatschools
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: greatschools\nname: GreatSchools\ndescription: >-\n  GreatSchools provides school information, ratings, and quality data via its Developer Hub APIs, including the School Essentials API for school details and the School Quality API for GreatSchools rating bands.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Schools\n  - Education\n  - Ratings\n  - Geolocation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/greatschools/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: greatschools:school-essentials\n    name: GreatSchools School Essentials API\n    description: >-\n      Retrieve key information about schools across the United States based on proximity to a location or filtered by name, type, and more. Returns school names, addresses, grades offered, type, and website links.\n    humanURL: https://www.greatschools.org/api\n    tags:\n\
  \      - Schools\n      - Education\n      - Geolocation\n    properties:\n      - type: Pricing\n        url: https://www.greatschools.org/api\n      - type: Developer Hub\n        url: https://www.greatschools.org/api\n  - aid: greatschools:school-quality\n    name: GreatSchools School Quality API\n    description: >-\n      Builds on School Essentials by adding GreatSchools School Rating Bands (below average, average, above average) to assess school quality.\n    humanURL: https://www.greatschools.org/api\n    tags:\n      - Schools\n      - Education\n      - Ratings\n    properties:\n      - type: Pricing\n        url: https://www.greatschools.org/api\n      - type: Developer Hub\n        url: https://www.greatschools.org/api\ncommon:\n  - type: Website\n    url: https://www.greatschools.org\n  - type: Developer Hub\n    url: https://www.greatschools.org/api\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/greatschools/refs/heads/main/apis.yml
tags:
- Schools
- Education
- Ratings
- Geolocation
url: https://raw.githubusercontent.com/api-evangelist/greatschools/refs/heads/main/apis.yml
use_cases: []
---
