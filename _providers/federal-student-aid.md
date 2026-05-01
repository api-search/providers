---
api_count: 2
apis:
- description: StudentAid.gov is the official consumer platform for U.S. federal student aid. Borrowers and students use the site to complete the FAFSA, manage federal loans, review repayment plans, and access aid r
  name: StudentAid.gov
  slug: studentaid-gov
- description: 'The College Scorecard API, operated by the U.S. Department of Education via api.data.gov, exposes institution-level data including federal aid participation, costs, completion rates, and post-college '
  name: College Scorecard API
  slug: college-scorecard
common:
- title: ''
  type: Website
  url: https://studentaid.gov
- title: ''
  type: About
  url: https://studentaid.gov/about
- title: ''
  type: FAFSA
  url: https://studentaid.gov/h/apply-for-aid/fafsa
- title: ''
  type: Open Data
  url: https://www.ed.gov/about/news/data
created: '2024-12-03'
description: The Federal Student Aid (FSA) office of the U.S. Department of Education provides grants, loans, and work-study funds to eligible students enrolled in college or career school. FSA operates StudentAid.gov as the consumer portal for managing federal student loans, completing the FAFSA, and exploring repayment options. FSA does not currently publish a public, open developer API program; aggregate higher education and aid data is redistributed through the Department of Education's open data programs such as the College Scorecard API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Federal Student Aid
skills: []
slug: federal-student-aid
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: federal-student-aid\nname: Federal Student Aid\ndescription: >-\n  The Federal Student Aid (FSA) office of the U.S. Department of Education\n  provides grants, loans, and work-study funds to eligible students enrolled\n  in college or career school. FSA operates StudentAid.gov as the consumer\n  portal for managing federal student loans, completing the FAFSA, and\n  exploring repayment options. FSA does not currently publish a public,\n  open developer API program; aggregate higher education and aid data is\n  redistributed through the Department of Education's open data programs\n  such as the College Scorecard API.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Education\n  - Federal Government\n  - Financial Aid\n  - Grants\n  - Loans\n  - Student Aid\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/federal-student-aid/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: federal-student-aid:studentaid-gov\n    name: StudentAid.gov\n    description: >-\n      StudentAid.gov is the official consumer platform for U.S. federal\n      student aid. Borrowers and students use the site to complete the FAFSA,\n      manage federal loans, review repayment plans, and access aid resources.\n      The platform itself is not exposed as a public REST API today.\n    humanURL: https://studentaid.gov\n    tags:\n      - Financial Aid\n      - Loans\n      - Student Aid\n    properties:\n      - type: Website\n        url: https://studentaid.gov\n      - type: FAFSA\n        url: https://studentaid.gov/h/apply-for-aid/fafsa\n      - type: Loan Repayment\n        url: https://studentaid.gov/manage-loans/repayment\n  - aid: federal-student-aid:college-scorecard\n    name: College Scorecard API\n    description: >-\n      The College Scorecard API, operated by the U.S. Department of Education\n      via api.data.gov, exposes institution-level\
  \ data including federal aid\n      participation, costs, completion rates, and post-college outcomes that\n      complement Federal Student Aid program information.\n    humanURL: https://collegescorecard.ed.gov/data/documentation/\n    baseURL: https://api.data.gov/ed/collegescorecard/v1\n    tags:\n      - Education\n      - Open Data\n      - Higher Education\n    properties:\n      - type: Documentation\n        url: https://collegescorecard.ed.gov/data/documentation/\n      - type: Sign Up\n        url: https://api.data.gov/signup/\ncommon:\n  - type: Website\n    url: https://studentaid.gov\n  - type: About\n    url: https://studentaid.gov/about\n  - type: FAFSA\n    url: https://studentaid.gov/h/apply-for-aid/fafsa\n  - type: Open Data\n    url: https://www.ed.gov/about/news/data\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/federal-student-aid/refs/heads/main/apis.yml
tags:
- Education
- Federal Government
- Financial Aid
- Grants
- Loans
- Student Aid
url: https://raw.githubusercontent.com/api-evangelist/federal-student-aid/refs/heads/main/apis.yml
use_cases: []
---
