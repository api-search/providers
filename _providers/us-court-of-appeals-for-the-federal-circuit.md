---
api_count: 3
apis:
- description: Public Access to Court Electronic Records (PACER) provides online access to U.S. Federal Court case and docket information from Federal Courts including the U.S. Court of Appeals for the Federal Circu
  name: PACER - Public Access to Court Electronic Records
  slug: pacer
- description: 'Public access to U.S. Court of Appeals for the Federal Circuit opinions, orders, and judgments. Includes precedential opinions, Rule 36 judgments, non-ministerial orders, and errata. Available online '
  name: Federal Circuit Opinions and Orders
  slug: opinions-orders
- description: Case information and records for the U.S. Court of Appeals for the Federal Circuit. Cases filed on or after March 1, 2012, are available through PACER or at public terminals in the Clerk's Office. The
  name: Federal Circuit Case Records
  slug: case-records
common:
- title: ''
  type: Website
  url: https://www.cafc.uscourts.gov/
- title: Case Information
  type: Documentation
  url: https://www.cafc.uscourts.gov/home/case-information/
- title: Opinions and Orders
  type: Documentation
  url: https://www.cafc.uscourts.gov/home/case-information/opinions-orders/
- title: PACER Registration
  type: GettingStarted
  url: https://pacer.uscourts.gov/
- title: PACER Developer Resources
  type: APIReference
  url: https://pacer.uscourts.gov/file-case/developer-resources
- title: Rules and Procedures
  type: Documentation
  url: https://www.cafc.uscourts.gov/home/rules-procedures/
- title: Contact the Court
  type: Contact
  url: https://www.cafc.uscourts.gov/home/about-the-court/contact/
- title: US Court of Appeals for the Federal Circuit Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/vocabulary/us-court-of-appeals-for-the-federal-circuit-vocabulary.yml
- title: US Court of Appeals for the Federal Circuit JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld
created: '2024-12-25'
description: The US Court of Appeals for the Federal Circuit is a federal appellate court with nationwide jurisdiction over cases involving patent law, international trade, government contracts, federal employment, veterans' benefits, and other specialized areas of federal law. The court provides public access to opinions and orders online from 2004 to present, with full case records accessible via PACER for cases filed after March 1, 2012. The PACER system offers developer APIs including the Authentication API and the Case Locator (PCL) API for programmatic access to federal case data across all federal courts.
features:
- description: Programmatic access to the nationwide federal court case index via the PACER Case Locator (PCL) API, enabling searches for cases and associated parties across all federal courts including the Federal Circuit.
  name: PACER Case Locator API
- description: API allowing automated authentication to PACER without a user interface, enabling programmatic access to court records using PACER credentials.
  name: PACER Authentication API
- description: Court's electronic filing system (CM/ECF) for filing and managing case documents. Provides XML tags and NextGen CM/ECF integration.
  name: CM/ECF Electronic Filing
- description: Free public access to all Federal Circuit opinions, orders, and judgments published from October 2004 to present in PDF format.
  name: Online Opinions and Orders
- description: Online calendar of scheduled oral argument cases and courtroom assignments at the Federal Circuit.
  name: Scheduled Cases Calendar
- description: Aggregated case statistics and reports available through the court's media and public information pages, plus data request process.
  name: Statistical Reports
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Federal Circuit case records fully integrated with the nationwide PACER federal court records system and CM/ECF filing system.
  name: PACER System
- description: Free Law Project's CourtListener provides API access to Federal Circuit opinions and RECAP-archived PACER documents.
  name: CourtListener
- description: Justia aggregates Federal Circuit case docket information and provides public access to filings.
  name: Justia Dockets
jsonld:
- class_count: 5
  name: Us Court Of Appeals For The Federal Circuit Context
  property_count: 25
  slug: us-court-of-appeals-for-the-federal-circuit-context
layout: provider
modified: '2026-05-03'
name: US Court of Appeals for the Federal Circuit
skills: []
slug: us-court-of-appeals-for-the-federal-circuit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-court-of-appeals-for-the-federal-circuit\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/apis.yml\napis:\n  - aid: us-court-of-appeals-for-the-federal-circuit:pacer\n    name: PACER - Public Access to Court Electronic Records\n    tags:\n      - Federal Courts\n      - PACER\n      - Case Records\n      - Legal\n    humanURL: https://pacer.uscourts.gov/file-case/court-cmecf-lookup/court/CAFC\n    properties:\n      - url: https://pacer.uscourts.gov/file-case/court-cmecf-lookup/court/CAFC\n        type: Documentation\n      - url: https://pacer.uscourts.gov/file-case/developer-resources\n        type: APIReference\n        title: PACER Developer Resources\n      - url: https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide\n        type: Documentation\n        title: PACER Authentication API User Guide\n      - url: https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide\n\
  \        type: Documentation\n        title: PACER Case Locator (PCL) API User Guide\n    description: >-\n      Public Access to Court Electronic Records (PACER) provides online access\n      to U.S. Federal Court case and docket information from Federal Courts\n      including the U.S. Court of Appeals for the Federal Circuit (CAFC).\n      PACER provides the Authentication API and the Case Locator (PCL) API\n      for programmatic access to federal court records and case data.\n  - aid: us-court-of-appeals-for-the-federal-circuit:opinions-orders\n    name: Federal Circuit Opinions and Orders\n    tags:\n      - Federal Courts\n      - Opinions\n      - Legal Decisions\n      - Legal\n    humanURL: https://www.cafc.uscourts.gov/home/case-information/opinions-orders/\n    properties:\n      - url: https://www.cafc.uscourts.gov/home/case-information/opinions-orders/\n        type: Documentation\n        title: Opinions and Orders Search\n    description: >-\n      Public access to U.S.\
  \ Court of Appeals for the Federal Circuit opinions,\n      orders, and judgments. Includes precedential opinions, Rule 36 judgments,\n      non-ministerial orders, and errata. Available online from October 1, 2004,\n      to present. PDF documents accessible directly from cafc.uscourts.gov.\n  - aid: us-court-of-appeals-for-the-federal-circuit:case-records\n    name: Federal Circuit Case Records\n    tags:\n      - Federal Courts\n      - Case Records\n      - Legal\n    humanURL: https://www.cafc.uscourts.gov/home/case-information/case-records/\n    properties:\n      - url: https://www.cafc.uscourts.gov/home/case-information/case-records/\n        type: Documentation\n      - url: https://www.cafc.uscourts.gov/home/case-information/\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-schema/cafc-case-schema.json\n        type: JSONSchema\n        title: Federal Circuit\
  \ Case Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-schema/cafc-opinion-schema.json\n        type: JSONSchema\n        title: Federal Circuit Opinion Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-schema/cafc-docket-entry-schema.json\n        type: JSONSchema\n        title: PACER Docket Entry Schema\n    description: >-\n      Case information and records for the U.S. Court of Appeals for the\n      Federal Circuit. Cases filed on or after March 1, 2012, are available\n      through PACER or at public terminals in the Clerk's Office. The court\n      provides aggregated case statistics via a data request process.\nname: US Court of Appeals for the Federal Circuit\ntags:\n  - Federal Government\n  - Legal\n  - Patent Law\n  - Federal Courts\n  - Appellate Courts\ntype: Index\nimage:\
  \ https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-25'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  The US Court of Appeals for the Federal Circuit is a federal appellate court\n  with nationwide jurisdiction over cases involving patent law, international\n  trade, government contracts, federal employment, veterans' benefits, and other\n  specialized areas of federal law. The court provides public access to opinions\n  and orders online from 2004 to present, with full case records accessible via\n  PACER for cases filed after March 1, 2012. The PACER system offers developer\n  APIs including the Authentication API and the Case Locator (PCL) API for\n  programmatic access to federal case data across all federal courts.\ncommon:\n  - type: Website\n    url: https://www.cafc.uscourts.gov/\n  - type: Documentation\n    url: https://www.cafc.uscourts.gov/home/case-information/\n    title: Case Information\n  -\
  \ type: Documentation\n    url: https://www.cafc.uscourts.gov/home/case-information/opinions-orders/\n    title: Opinions and Orders\n  - type: GettingStarted\n    url: https://pacer.uscourts.gov/\n    title: PACER Registration\n  - type: APIReference\n    url: https://pacer.uscourts.gov/file-case/developer-resources\n    title: PACER Developer Resources\n  - type: Documentation\n    url: https://www.cafc.uscourts.gov/home/rules-procedures/\n    title: Rules and Procedures\n  - type: Contact\n    url: https://www.cafc.uscourts.gov/home/about-the-court/contact/\n    title: Contact the Court\n  - type: Features\n    data:\n      - name: PACER Case Locator API\n        description: >-\n          Programmatic access to the nationwide federal court case index via\n          the PACER Case Locator (PCL) API, enabling searches for cases and\n          associated parties across all federal courts including the Federal Circuit.\n      - name: PACER Authentication API\n        description: >-\n\
  \          API allowing automated authentication to PACER without a user interface,\n          enabling programmatic access to court records using PACER credentials.\n      - name: CM/ECF Electronic Filing\n        description: >-\n          Court's electronic filing system (CM/ECF) for filing and managing\n          case documents. Provides XML tags and NextGen CM/ECF integration.\n      - name: Online Opinions and Orders\n        description: >-\n          Free public access to all Federal Circuit opinions, orders, and\n          judgments published from October 2004 to present in PDF format.\n      - name: Scheduled Cases Calendar\n        description: >-\n          Online calendar of scheduled oral argument cases and courtroom\n          assignments at the Federal Circuit.\n      - name: Statistical Reports\n        description: >-\n          Aggregated case statistics and reports available through the court's\n          media and public information pages, plus data request process.\n\
  \  - type: UseCases\n    data:\n      - name: Patent Case Legal Research\n        description: >-\n          Researching Federal Circuit patent law precedent using published\n          opinions, orders, and PACER case dockets.\n      - name: Federal Employment and Veterans Claims Research\n        description: >-\n          Finding Federal Circuit decisions on government contracts, federal\n          employment, veterans benefits, and specialized federal jurisdiction.\n      - name: Court Records Access via PACER\n        description: >-\n          Programmatic access to Federal Circuit case dockets, filings, and\n          documents using the PACER Authentication API and Case Locator API.\n      - name: Appellate Monitoring\n        description: >-\n          Monitoring active Federal Circuit cases, oral arguments, and new\n          opinions relevant to specific technology, trade, or legal areas.\n      - name: Legal Data Analytics\n        description: >-\n          Using PACER data\
  \ to analyze trends in Federal Circuit patent,\n          trade, and government contract decisions for legal research.\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/vocabulary/us-court-of-appeals-for-the-federal-circuit-vocabulary.yml\n    title: US Court of Appeals for the Federal Circuit Vocabulary\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld\n    title: US Court of Appeals for the Federal Circuit JSON-LD Context\n  - type: Integrations\n    data:\n      - name: PACER System\n        description: >-\n          Federal Circuit case records fully integrated with the nationwide\n          PACER federal court records system and CM/ECF filing system.\n      - name: CourtListener\n        description: >-\n          Free\
  \ Law Project's CourtListener provides API access to Federal\n          Circuit opinions and RECAP-archived PACER documents.\n      - name: Justia Dockets\n        description: >-\n          Justia aggregates Federal Circuit case docket information and\n          provides public access to filings.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/apis.yml
tags:
- Federal Government
- Legal
- Patent Law
- Federal Courts
- Appellate Courts
url: https://raw.githubusercontent.com/api-evangelist/us-court-of-appeals-for-the-federal-circuit/refs/heads/main/apis.yml
use_cases:
- description: Researching Federal Circuit patent law precedent using published opinions, orders, and PACER case dockets.
  name: Patent Case Legal Research
- description: Finding Federal Circuit decisions on government contracts, federal employment, veterans benefits, and specialized federal jurisdiction.
  name: Federal Employment and Veterans Claims Research
- description: Programmatic access to Federal Circuit case dockets, filings, and documents using the PACER Authentication API and Case Locator API.
  name: Court Records Access via PACER
- description: Monitoring active Federal Circuit cases, oral arguments, and new opinions relevant to specific technology, trade, or legal areas.
  name: Appellate Monitoring
- description: Using PACER data to analyze trends in Federal Circuit patent, trade, and government contract decisions for legal research.
  name: Legal Data Analytics
---
