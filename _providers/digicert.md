---
api_count: 5
apis:
- description: The DigiCert Services API automates certificate processes to save time and streamline certificate management across the CertCentral platform. Use this API to manage all aspects of your CertCentral acc
  name: DigiCert Services API
  slug: digicert-services-api
- description: 'The DigiCert Report Library API allows users to create and manage custom reports for CertCentral certificate orders, domains, organizations, and account activity. Programmatically schedule, retrieve, '
  name: DigiCert Report Library API
  slug: digicert-report-library-api
- description: The DigiCert Discovery API enables scanning of internal and public-facing networks using sensors to find SSL/TLS certificates regardless of the issuing Certificate Authority. Use the API to manage sca
  name: DigiCert Discovery API
  slug: digicert-discovery-api
- description: The DigiCert Automation API allows configuration of automation profiles and management of automation activities for certificate lifecycle operations. Access all automation features available in CertCe
  name: DigiCert Automation API
  slug: digicert-automation-api
- description: The DigiCert Custom Reports API allows generation of customizable and comprehensive data sets by leveraging the powerful GraphQL query language. Build tailored reporting against CertCentral data sourc
  name: DigiCert Custom Reports API
  slug: digicert-custom-reports-api
common:
- title: ''
  type: Developer
  url: https://dev.digicert.com/
- title: ''
  type: Documentation
  url: https://docs.digicert.com/
- title: ''
  type: Support
  url: https://knowledge.digicert.com/
- title: ''
  type: Website
  url: https://www.digicert.com/
- title: ''
  type: Blog
  url: https://www.digicert.com/blog/
- title: ''
  type: Pricing
  url: https://www.digicert.com/tls-ssl/compare-certificates
- title: ''
  type: Security
  url: https://www.digicert.com/trust/
- title: ''
  type: Status
  url: https://status.digicert.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.digicert.com/legal-repository/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.digicert.com/legal-repository/master-services-agreement
- title: ''
  type: GitHub
  url: https://github.com/digicert
- title: ''
  type: ChangeLog
  url: https://dev.digicert.com/en/changelog.html
created: '2025-01-08'
description: Digicert is a leading provider of digital security solutions, specializing in SSL/TLS certificates, PKI solutions, and website security. They help organizations of all sizes protect their websites, data, and communications from cyber threats by providing secure encryption and authentication services. Digicert's CertCentral platform exposes a suite of REST and GraphQL APIs for certificate lifecycle management, discovery, automation, and reporting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Digicert
skills: []
slug: digicert
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: digicert\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/digicert/refs/heads/main/apis.yml\napis:\n  - aid: digicert:digicert-services-api\n    name: DigiCert Services API\n    tags:\n      - Certificates\n      - Encryption\n      - PKI\n      - SSL\n      - TLS\n    humanURL: https://dev.digicert.com/en/certcentral-apis/services-api.html\n    baseURL: https://www.digicert.com/services/v2\n    properties:\n      - url: https://dev.digicert.com/en/certcentral-apis/services-api.html\n        type: Documentation\n    description: >-\n      The DigiCert Services API automates certificate processes to save time and\n      streamline certificate management across the CertCentral platform. Use this\n      API to manage all aspects of your CertCentral account including order, issue,\n      reissue, renew, and revoke for SSL/TLS, code signing, client, and document\n      signing certificates, as well as user, organization, domain, and product\n      management.\n\
  \  - aid: digicert:digicert-report-library-api\n    name: DigiCert Report Library API\n    tags:\n      - Certificates\n      - Encryption\n      - Reporting\n    humanURL: https://dev.digicert.com/en/certcentral-apis/report-library-api.html\n    properties:\n      - url: https://dev.digicert.com/en/certcentral-apis/report-library-api.html\n        type: Documentation\n    description: >-\n      The DigiCert Report Library API allows users to create and manage custom\n      reports for CertCentral certificate orders, domains, organizations, and\n      account activity. Programmatically schedule, retrieve, and export reports\n      to streamline visibility and auditing of certificate inventories.\n  - aid: digicert:digicert-discovery-api\n    name: DigiCert Discovery API\n    tags:\n      - Certificates\n      - Discovery\n      - Encryption\n      - Scanning\n    humanURL: https://dev.digicert.com/en/certcentral-apis/discovery-api.html\n    properties:\n      - url: https://dev.digicert.com/en/certcentral-apis/discovery-api.html\n\
  \        type: Documentation\n    description: >-\n      The DigiCert Discovery API enables scanning of internal and public-facing\n      networks using sensors to find SSL/TLS certificates regardless of the\n      issuing Certificate Authority. Use the API to manage scan configurations,\n      sensors, divisions, and the certificates that have been discovered to\n      reduce risk from unknown or expired certificates.\n  - aid: digicert:digicert-automation-api\n    name: DigiCert Automation API\n    tags:\n      - Automation\n      - Certificates\n      - Encryption\n    humanURL: https://dev.digicert.com/en/certcentral-apis/automation-api.html\n    properties:\n      - url: https://dev.digicert.com/en/certcentral-apis/automation-api.html\n        type: Documentation\n    description: >-\n      The DigiCert Automation API allows configuration of automation profiles\n      and management of automation activities for certificate lifecycle\n      operations. Access all automation features\
  \ available in CertCentral\n      programmatically without needing to log in to the platform.\n  - aid: digicert:digicert-custom-reports-api\n    name: DigiCert Custom Reports API\n    tags:\n      - Certificates\n      - Encryption\n      - GraphQL\n      - Reporting\n    humanURL: https://dev.digicert.com/en/certcentral-apis/custom-reports-api.html\n    properties:\n      - url: https://dev.digicert.com/en/certcentral-apis/custom-reports-api.html\n        type: Documentation\n    description: >-\n      The DigiCert Custom Reports API allows generation of customizable and\n      comprehensive data sets by leveraging the powerful GraphQL query language.\n      Build tailored reporting against CertCentral data sources with flexible\n      filtering, sorting, and field selection.\nname: Digicert\ntags:\n  - Certificates\n  - Encryption\n  - PKI\n  - SSL\n  - TLS\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  -\
  \ name: DigiCert Developer Portal\n    url: https://dev.digicert.com/\n    type: Developer\n  - name: DigiCert Documentation\n    url: https://docs.digicert.com/\n    type: Documentation\n  - name: DigiCert Knowledge Base\n    url: https://knowledge.digicert.com/\n    type: Support\n  - name: DigiCert\n    url: https://www.digicert.com/\n    type: Website\n  - name: DigiCert Blog\n    url: https://www.digicert.com/blog/\n    type: Blog\n  - name: DigiCert Pricing\n    url: https://www.digicert.com/tls-ssl/compare-certificates\n    type: Pricing\n  - name: DigiCert Trust Center\n    url: https://www.digicert.com/trust/\n    type: Security\n  - name: DigiCert Status\n    url: https://status.digicert.com/\n    type: Status\n  - name: DigiCert Privacy Policy\n    url: https://www.digicert.com/legal-repository/privacy-policy\n    type: PrivacyPolicy\n  - name: DigiCert Master Services Agreement\n    url: https://www.digicert.com/legal-repository/master-services-agreement\n    type: TermsOfService\n\
  \  - name: DigiCert GitHub\n    url: https://github.com/digicert\n    type: GitHub\n  - name: DigiCert Changelog\n    url: https://dev.digicert.com/en/changelog.html\n    type: ChangeLog\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Digicert is a leading provider of digital security solutions, specializing in\n  SSL/TLS certificates, PKI solutions, and website security. They help\n  organizations of all sizes protect their websites, data, and communications\n  from cyber threats by providing secure encryption and authentication services.\n  Digicert's CertCentral platform exposes a suite of REST and GraphQL APIs for\n  certificate lifecycle management, discovery, automation, and reporting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/digicert/refs/heads/main/apis.yml
tags:
- Certificates
- Encryption
- PKI
- SSL
- TLS
url: https://raw.githubusercontent.com/api-evangelist/digicert/refs/heads/main/apis.yml
use_cases: []
---
