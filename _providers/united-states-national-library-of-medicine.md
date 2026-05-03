---
api_count: 4
api_specs:
- filename: ncbi-e-utilities-openapi.yml
  format: yaml
  label: NCBI E-Utilities API
  slug: ncbi-e-utilities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-e-utilities-openapi.yml
- filename: openapi3.docs.yaml
  format: yaml
  label: NCBI Datasets REST API
  slug: ncbi-datasets-api
  spec_type: OpenAPI
  url: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/openapi3/openapi3.docs.yaml
- filename: ncbi-blast-openapi.yml
  format: yaml
  label: NCBI BLAST URL API
  slug: ncbi-blast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-blast-openapi.yml
- filename: nlm-clinicaltrials-openapi.yml
  format: yaml
  label: ClinicalTrials.gov API
  slug: nlm-clinical-trials-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/nlm-clinicaltrials-openapi.yml
apis:
- description: The NCBI E-Utilities (Entrez Programming Utilities) are the public API to the NCBI Entrez system providing access to all Entrez databases including PubMed (biomedical literature), PMC (full-text artic
  name: NCBI E-Utilities API
  slug: ncbi-e-utilities-api
- description: The NCBI Datasets REST API v2 provides programmatic access to biological data including genome assemblies, gene records, and protein sequences across organisms. Returns data packages containing sequen
  name: NCBI Datasets REST API
  slug: ncbi-datasets-api
- description: The NCBI BLAST URL API allows developers to submit BLAST (Basic Local Alignment Search Tool) sequence searches for processing at NCBI using HTTPS. Supports nucleotide and protein sequence searches aga
  name: NCBI BLAST URL API
  slug: ncbi-blast-api
- description: 'The ClinicalTrials.gov API provides programmatic access to clinical trial data registered with ClinicalTrials.gov, operated by the National Library of Medicine. Returns study information, eligibility '
  name: ClinicalTrials.gov API
  slug: nlm-clinical-trials-api
capabilities:
- description: Unified capability for biomedical literature research and clinical trial discovery workflows combining NCBI E-Utilities (PubMed, Entrez databases) with ClinicalTrials.gov. Used by researchers, clinici
  name: NLM Biomedical Literature and Clinical Research
  slug: biomedical-literature-research
common:
- title: ''
  type: Portal
  url: https://www.ncbi.nlm.nih.gov/home/develop/api/
created: 2024/01/01
description: The United States National Library of Medicine (NLM) is the world's largest biomedical library. It serves as a vital resource for researchers, healthcare professionals, and the general public by providing access to a vast collection of biomedical literature and resources. The NLM offers a wide range of services and resources including online databases, digital archives, and research tools that support medical research, education, and patient care. Key APIs include the NCBI E-Utilities (PubMed, Entrez), NCBI Datasets (genomes, genes), BLAST sequence alignment, and the ClinicalTrials.gov API.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: United States National Library Of Medicine Context
  property_count: 19
  slug: united-states-national-library-of-medicine-context
layout: provider
modified: '2026-05-03'
name: United States National Library of Medicine
rules:
- name: United States National Library of Medicine API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: ncbi-e-utilities-rules
skills: []
slug: united-states-national-library-of-medicine
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-national-library-of-medicine\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml\napis:\n  - aid: >-\n      united-states-national-library-of-medicine:ncbi-e-utilities-api\n    name: NCBI E-Utilities API\n    tags:\n      - Biomedical\n      - PubMed\n      - Literature\n      - Genomics\n      - Federal Government\n    humanURL: https://www.ncbi.nlm.nih.gov/books/NBK25497/\n    baseURL: https://eutils.ncbi.nlm.nih.gov/entrez/eutils\n    properties:\n      - url: https://www.ncbi.nlm.nih.gov/books/NBK25497/\n        type: Documentation\n      - url: https://www.ncbi.nlm.nih.gov/home/develop/api/\n        type: Portal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-e-utilities-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/rules/ncbi-e-utilities-rules.yml\n\
  \        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/capabilities/biomedical-literature-research.yaml\n        type: NaftikoCapability\n    description: >-\n      The NCBI E-Utilities (Entrez Programming Utilities) are the public API\n      to the NCBI Entrez system providing access to all Entrez databases including\n      PubMed (biomedical literature), PMC (full-text articles), Gene, Nuccore\n      (nucleotide sequences), Protein, and 39 other databases. Supports search,\n      retrieval, linking, and posting operations. API keys from\n      ncbi.nlm.nih.gov/account/ increase the rate limit from 3 to 10 requests/second.\n\n  - aid: >-\n      united-states-national-library-of-medicine:ncbi-datasets-api\n    name: NCBI Datasets REST API\n    tags:\n      - Genomics\n      - Biological Sequences\n      - Gene Data\n      - Federal Government\n    humanURL: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/\n\
  \    baseURL: https://api.ncbi.nlm.nih.gov/datasets/v2\n    properties:\n      - url: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/\n        type: Documentation\n      - url: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/api/rest-api/\n        type: SwaggerUI\n      - url: https://www.ncbi.nlm.nih.gov/datasets/docs/v2/openapi3/openapi3.docs.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-datasets-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/capabilities/biomedical-literature-research.yaml\n        type: NaftikoCapability\n      - url: https://github.com/ncbi/datasets\n        type: Repository\n    description: >-\n      The NCBI Datasets REST API v2 provides programmatic access to biological\n      data including genome assemblies,\
  \ gene records, and protein sequences across\n      organisms. Returns data packages containing sequences, annotations, metadata,\n      and related data. An OpenAPI 3.0 specification is available on GitHub at\n      github.com/ncbi/datasets. API keys are optional but increase rate limits.\n\n  - aid: >-\n      united-states-national-library-of-medicine:ncbi-blast-api\n    name: NCBI BLAST URL API\n    tags:\n      - Genomics\n      - Sequence Alignment\n      - Bioinformatics\n      - Federal Government\n    humanURL: https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html\n    baseURL: https://blast.ncbi.nlm.nih.gov/blast/Blast.cgi\n    properties:\n      - url: https://blast.ncbi.nlm.nih.gov/doc/blast-help/developerinfo.html\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/ncbi-blast-openapi.yml\n        type: OpenAPI\n    description: >-\n      The NCBI\
  \ BLAST URL API allows developers to submit BLAST (Basic Local\n      Alignment Search Tool) sequence searches for processing at NCBI using HTTPS.\n      Supports nucleotide and protein sequence searches against NCBI databases.\n      The API can check the status of submitted searches and retrieve results in\n      multiple formats including XML, JSON, text, and ASN.1.\n\n  - aid: >-\n      united-states-national-library-of-medicine:nlm-clinical-trials-api\n    name: ClinicalTrials.gov API\n    tags:\n      - Clinical Trials\n      - Healthcare\n      - Research\n      - Federal Government\n    humanURL: https://clinicaltrials.gov/data-api/api\n    baseURL: https://clinicaltrials.gov/api/v2\n    properties:\n      - url: https://clinicaltrials.gov/data-api/api\n        type: Documentation\n      - url: https://clinicaltrials.gov/data-api/api#introduction\n        type: Portal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/openapi/nlm-clinicaltrials-openapi.yml\n\
  \        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/capabilities/biomedical-literature-research.yaml\n        type: NaftikoCapability\n    description: >-\n      The ClinicalTrials.gov API provides programmatic access to clinical trial\n      data registered with ClinicalTrials.gov, operated by the National Library of\n      Medicine. Returns study information, eligibility criteria, outcomes, locations,\n      sponsor/collaborator data, and results for hundreds of thousands of trials.\n      No API key required.\n\nname: United States National Library of Medicine\ntags:\n  - Federal Government\n  - Biomedical Research\n  - Healthcare\n  - Genomics\n  - Literature\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncommon:\n  - url: https://www.ncbi.nlm.nih.gov/home/develop/api/\n    type: Portal\ncreated: 2024/01/01\nmodified: '2026-05-03'\n\
  position: Consuming\naccess: 3rd-Party\ndescription: >-\n  The United States National Library of Medicine (NLM) is the world's largest\n  biomedical library. It serves as a vital resource for researchers, healthcare\n  professionals, and the general public by providing access to a vast collection\n  of biomedical literature and resources. The NLM offers a wide range of\n  services and resources including online databases, digital archives, and\n  research tools that support medical research, education, and patient care.\n  Key APIs include the NCBI E-Utilities (PubMed, Entrez), NCBI Datasets (genomes,\n  genes), BLAST sequence alignment, and the ClinicalTrials.gov API.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml
tags:
- Federal Government
- Biomedical Research
- Healthcare
- Genomics
- Literature
url: https://raw.githubusercontent.com/api-evangelist/united-states-national-library-of-medicine/refs/heads/main/apis.yml
use_cases: []
---
