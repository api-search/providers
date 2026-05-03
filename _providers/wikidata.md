---
api_count: 5
api_specs:
- filename: wikidata-mediawiki-openapi.yml
  format: yaml
  label: Wikibase REST API
  slug: wikibase-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/openapi/wikidata-mediawiki-openapi.yml
apis:
- description: The Wikibase REST API provides OpenAPI-based read and write operations for Wikidata entities (items and properties), including labels, descriptions, aliases, statements, sitelinks, and patches. Authen
  name: Wikibase REST API
  slug: wikibase-rest-api
- description: The MediaWiki Action API provides batch entity retrieval, editing, and search for Wikidata via wbgetentities, wbsearchentities, wbeditentity, and other actions. Supports up to 50 entities per request.
  name: MediaWiki Action API
  slug: mediawiki-action-api
- description: The Wikidata Query Service provides a SPARQL 1.1 endpoint at query.wikidata.org for running complex graph queries over the full Wikidata knowledge base. Supports federated queries, GeoSPARQL, and time
  name: SPARQL Query Service
  slug: sparql-query-service
- description: The Wikidata Linked Data Interface provides individual entity data via content negotiation at http://www.wikidata.org/entity/{QID}. Supports JSON, JSON-LD, RDF/XML, Turtle, and N-Triples output format
  name: Linked Data Interface
  slug: linked-data-interface
- description: The Wikimedia Event Stream provides real-time Server-Sent Events (SSE) for Wikidata changes, revision creations, and page events. Available at stream.wikimedia.org. Ideal for monitoring Wikidata edits
  name: Recent Changes Event Stream
  slug: event-stream
capabilities:
- description: 'Unified capability for reading and writing to the Wikidata knowledge graph. Combines Wikibase REST API operations for entity retrieval, statement management, and structured data writing. Intended for '
  name: Wikidata Knowledge Graph Access
  slug: knowledge-graph-access
common:
- title: ''
  type: Website
  url: https://www.wikidata.org/
- title: ''
  type: Portal
  url: https://www.wikidata.org/wiki/Wikidata:Data_access
- title: ''
  type: Documentation
  url: https://www.wikidata.org/wiki/Wikidata:Data_access
- title: ''
  type: GitHubOrganization
  url: https://github.com/wikimedia
- title: ''
  type: GitHubRepository
  url: https://github.com/wikimedia/mediawiki
- title: ''
  type: TermsOfService
  url: https://foundation.wikimedia.org/wiki/Terms_of_Use
- title: ''
  type: PrivacyPolicy
  url: https://foundation.wikimedia.org/wiki/Privacy_policy
- title: ''
  type: Support
  url: https://www.wikidata.org/wiki/Wikidata:Contact_the_development_team
- title: ''
  type: Blog
  url: https://blog.wikimedia.org/
- title: ''
  type: StatusPage
  url: https://www.wikimediastatus.net/
- title: ''
  type: RateLimits
  url: https://www.mediawiki.org/wiki/API:Etiquette
- title: ''
  type: Authentication
  url: https://www.mediawiki.org/wiki/OAuth/For_Developers
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/rules/wikidata-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/vocabulary/wikidata-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/capabilities/knowledge-graph-access.yaml
created: '2025-01-01'
description: Wikidata is a free, collaborative, multilingual knowledge graph hosted by the Wikimedia Foundation. It provides structured linked data for Wikipedia and other Wikimedia projects, as well as a public platform for anyone to read and edit. Wikidata exposes several APIs including a Wikibase REST API for entity read/write operations, the MediaWiki Action API for batch entity retrieval and editing, a SPARQL endpoint for complex graph queries, Linked Data URIs for individual entity access in multiple RDF formats, a real-time Server-Sent Events stream for change monitoring, and full database dumps for bulk data processing.
features:
- description: All entities support labels, descriptions, and aliases in hundreds of languages via BCP 47 language codes.
  name: Multilingual Support
- description: Every claim is modeled as a statement with property, value, rank, qualifiers, and references for full provenance.
  name: Structured Statements
- description: All Wikidata content is released under CC0 1.0 Universal (Public Domain) — no attribution required.
  name: Open License
- description: Complex multi-hop queries over 100M+ entities via SPARQL 1.1 at query.wikidata.org with GeoSPARQL and time extensions.
  name: SPARQL Graph Queries
- description: Server-Sent Events at stream.wikimedia.org deliver real-time change notifications for Wikidata edits.
  name: Real-Time Event Streaming
- description: Entities available as JSON, JSON-LD, RDF/XML, Turtle, and N-Triples via content negotiation on Linked Data URIs.
  name: Multiple Serialization Formats
- description: Wikidata is an instance of Wikibase; federated SPARQL queries can cross Wikibase instances including Wikimedia Commons.
  name: Wikibase Federation
- description: Full JSON and RDF/TTL database dumps refreshed weekly at dumps.wikimedia.org for local bulk processing.
  name: Database Dumps
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Wikidata powers structured data for all Wikipedia language editions via Lua modules and infobox templates.
  name: Wikipedia
- description: Media files on Wikimedia Commons are described using Wikidata items via structured data on Commons.
  name: Wikimedia Commons
- description: OSM features are linked to Wikidata via the wikidata=* tag, enabling geographic entity cross-referencing.
  name: OpenStreetMap
- description: Scholia is a Wikidata-based scholarly profile service that visualizes publications, authors, and institutions.
  name: Scholia
- description: Reasonator renders human-readable pages for Wikidata items, integrating maps, timelines, and media.
  name: Reasonator
- description: Mix'n'match links Wikidata items to external databases (VIAF, ORCID, GND, etc.) for authority control.
  name: Mix'n'match
- description: OpenRefine has a Wikidata reconciliation service and can batch-upload tabular data as Wikidata statements.
  name: OpenRefine
jsonld:
- class_count: 10
  name: Wikidata Context
  property_count: 27
  slug: wikidata-context
layout: provider
modified: '2026-05-03'
name: Wikidata
rules:
- name: Wikidata API Rules
  rule_count: 33
  severity_counts:
    error: 12
    hint: 0
    info: 5
    warn: 16
  slug: wikidata-spectral-rules
skills: []
slug: wikidata
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wikidata\nname: Wikidata\ndescription: >-\n  Wikidata is a free, collaborative, multilingual knowledge graph hosted by the Wikimedia\n  Foundation. It provides structured linked data for Wikipedia and other Wikimedia projects,\n  as well as a public platform for anyone to read and edit. Wikidata exposes several APIs\n  including a Wikibase REST API for entity read/write operations, the MediaWiki Action API\n  for batch entity retrieval and editing, a SPARQL endpoint for complex graph queries,\n  Linked Data URIs for individual entity access in multiple RDF formats, a real-time\n  Server-Sent Events stream for change monitoring, and full database dumps for bulk\n  data processing.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Knowledge Graph\n  - Linked Data\n  - Open Data\n  - Semantic Web\n  - SPARQL\n  - Wikipedia\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nurl: >-\n\
  \  https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: wikidata:wikibase-rest-api\n    name: Wikibase REST API\n    description: >-\n      The Wikibase REST API provides OpenAPI-based read and write operations for Wikidata\n      entities (items and properties), including labels, descriptions, aliases, statements,\n      sitelinks, and patches. Authentication via OAuth2 or MediaWiki session is required\n      for write operations.\n    humanURL: https://www.wikidata.org/wiki/Wikidata:REST_API\n    baseURL: https://www.wikidata.org/w/rest.php/wikibase/v0\n    tags:\n      - Knowledge Graph\n      - Entities\n      - Items\n      - Properties\n      - Statements\n      - Linked Data\n    properties:\n      - type: Documentation\n        url: https://www.wikidata.org/wiki/Wikidata:REST_API\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/openapi/wikidata-mediawiki-openapi.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/json-schema/wikidata-entity-schema.json\n      - type: JSON-LD\n        url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/json-ld/wikidata-context.jsonld\n\n  - aid: wikidata:mediawiki-action-api\n    name: MediaWiki Action API\n    description: >-\n      The MediaWiki Action API provides batch entity retrieval, editing, and search for\n      Wikidata via wbgetentities, wbsearchentities, wbeditentity, and other actions.\n      Supports up to 50 entities per request. Accessible at wikidata.org/w/api.php.\n    humanURL: https://www.mediawiki.org/wiki/Wikibase/API\n    baseURL: https://www.wikidata.org/w/api.php\n    tags:\n      - MediaWiki\n      - Batch Operations\n      - Entity Retrieval\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.mediawiki.org/wiki/Wikibase/API\n      - type: SDK\n        url: https://pypi.org/project/pywikibot/\n\
  \        title: Pywikibot (Python)\n      - type: SDK\n        url: https://www.npmjs.com/package/wikibase-sdk\n        title: wikibase-sdk (JavaScript)\n      - type: SDK\n        url: https://www.wikidata.org/wiki/Wikidata:Tools/Wikidata_Toolkit\n        title: Wikidata Toolkit (Java)\n\n  - aid: wikidata:sparql-query-service\n    name: SPARQL Query Service\n    description: >-\n      The Wikidata Query Service provides a SPARQL 1.1 endpoint at query.wikidata.org\n      for running complex graph queries over the full Wikidata knowledge base. Supports\n      federated queries, GeoSPARQL, and time-aware queries. Data is CC0 licensed.\n    humanURL: https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service\n    baseURL: https://query.wikidata.org/sparql\n    tags:\n      - SPARQL\n      - Graph Query\n      - Linked Data\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.mediawiki.org/wiki/Wikidata_Query_Service/User_Manual\n      - type: APIReference\n\
  \        url: https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples\n\n  - aid: wikidata:linked-data-interface\n    name: Linked Data Interface\n    description: >-\n      The Wikidata Linked Data Interface provides individual entity data via content\n      negotiation at http://www.wikidata.org/entity/{QID}. Supports JSON, JSON-LD,\n      RDF/XML, Turtle, and N-Triples output formats. No authentication required.\n    humanURL: https://www.wikidata.org/wiki/Wikidata:Data_access#Linked_Data_Interface\n    baseURL: https://www.wikidata.org/entity\n    tags:\n      - Linked Data\n      - RDF\n      - JSON-LD\n      - Content Negotiation\n    properties:\n      - type: Documentation\n        url: https://www.wikidata.org/wiki/Wikidata:Data_access#Linked_Data_Interface\n\n  - aid: wikidata:event-stream\n    name: Recent Changes Event Stream\n    description: >-\n      The Wikimedia Event Stream provides real-time Server-Sent Events (SSE) for\n      Wikidata changes, revision\
  \ creations, and page events. Available at\n      stream.wikimedia.org. Ideal for monitoring Wikidata edits in near-real-time.\n    humanURL: https://wikitech.wikimedia.org/wiki/Event_Platform/EventStreams\n    baseURL: https://stream.wikimedia.org/v2/stream\n    tags:\n      - Event Streaming\n      - Real-time\n      - Server-Sent Events\n      - Change Detection\n    properties:\n      - type: Documentation\n        url: https://wikitech.wikimedia.org/wiki/Event_Platform/EventStreams\n\ncommon:\n  - type: Website\n    url: https://www.wikidata.org/\n  - type: Portal\n    url: https://www.wikidata.org/wiki/Wikidata:Data_access\n  - type: Documentation\n    url: https://www.wikidata.org/wiki/Wikidata:Data_access\n  - type: GitHubOrganization\n    url: https://github.com/wikimedia\n  - type: GitHubRepository\n    url: https://github.com/wikimedia/mediawiki\n  - type: TermsOfService\n    url: https://foundation.wikimedia.org/wiki/Terms_of_Use\n  - type: PrivacyPolicy\n    url: https://foundation.wikimedia.org/wiki/Privacy_policy\n\
  \  - type: Support\n    url: https://www.wikidata.org/wiki/Wikidata:Contact_the_development_team\n  - type: Blog\n    url: https://blog.wikimedia.org/\n  - type: StatusPage\n    url: https://www.wikimediastatus.net/\n  - type: RateLimits\n    url: https://www.mediawiki.org/wiki/API:Etiquette\n  - type: Authentication\n    url: https://www.mediawiki.org/wiki/OAuth/For_Developers\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/rules/wikidata-spectral-rules.yml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/vocabulary/wikidata-vocabulary.yaml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/capabilities/knowledge-graph-access.yaml\n  - type: Features\n    data:\n      - name: Multilingual Support\n        description: All entities support labels, descriptions, and aliases in hundreds of languages via BCP 47\
  \ language codes.\n      - name: Structured Statements\n        description: Every claim is modeled as a statement with property, value, rank, qualifiers, and references for full provenance.\n      - name: Open License\n        description: All Wikidata content is released under CC0 1.0 Universal (Public Domain) — no attribution required.\n      - name: SPARQL Graph Queries\n        description: Complex multi-hop queries over 100M+ entities via SPARQL 1.1 at query.wikidata.org with GeoSPARQL and time extensions.\n      - name: Real-Time Event Streaming\n        description: Server-Sent Events at stream.wikimedia.org deliver real-time change notifications for Wikidata edits.\n      - name: Multiple Serialization Formats\n        description: Entities available as JSON, JSON-LD, RDF/XML, Turtle, and N-Triples via content negotiation on Linked Data URIs.\n      - name: Wikibase Federation\n        description: Wikidata is an instance of Wikibase; federated SPARQL queries can cross Wikibase\
  \ instances including Wikimedia Commons.\n      - name: Database Dumps\n        description: Full JSON and RDF/TTL database dumps refreshed weekly at dumps.wikimedia.org for local bulk processing.\n  - type: UseCases\n    data:\n      - name: Knowledge Graph Augmentation\n        description: Enrich private datasets with structured Wikidata facts — entities, dates, relationships — via item and SPARQL queries.\n      - name: Fact-Checking and Verification\n        description: Retrieve canonical statements with references to verify biographical, geographic, or scientific claims in text.\n      - name: Wikipedia Infobox Data\n        description: Power Wikipedia infoboxes and sister-project templates with live Wikidata entity data via the MediaWiki Action API.\n      - name: NLP Entity Linking\n        description: Resolve named entities from natural language to Wikidata Q-IDs using wbsearchentities and SPARQL label lookups.\n      - name: Semantic Search\n        description: Build ontology-aware\
  \ search systems using Wikidata's P31 (instance of) and P279 (subclass of) property hierarchies.\n      - name: Change Monitoring\n        description: Track real-time edits to Wikidata entities relevant to a domain using the SSE event stream.\n      - name: Linked Open Data Publishing\n        description: Publish organizational data as Linked Open Data by aligning custom schemas to Wikidata properties and Q-IDs.\n  - type: Integrations\n    data:\n      - name: Wikipedia\n        description: Wikidata powers structured data for all Wikipedia language editions via Lua modules and infobox templates.\n      - name: Wikimedia Commons\n        description: Media files on Wikimedia Commons are described using Wikidata items via structured data on Commons.\n      - name: OpenStreetMap\n        description: OSM features are linked to Wikidata via the wikidata=* tag, enabling geographic entity cross-referencing.\n      - name: Scholia\n        description: Scholia is a Wikidata-based scholarly\
  \ profile service that visualizes publications, authors, and institutions.\n      - name: Reasonator\n        description: Reasonator renders human-readable pages for Wikidata items, integrating maps, timelines, and media.\n      - name: Mix'n'match\n        description: Mix'n'match links Wikidata items to external databases (VIAF, ORCID, GND, etc.) for authority control.\n      - name: OpenRefine\n        description: OpenRefine has a Wikidata reconciliation service and can batch-upload tabular data as Wikidata statements.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/apis.yml
tags:
- Knowledge Graph
- Linked Data
- Open Data
- Semantic Web
- SPARQL
- Wikipedia
url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/apis.yml
use_cases:
- description: Enrich private datasets with structured Wikidata facts — entities, dates, relationships — via item and SPARQL queries.
  name: Knowledge Graph Augmentation
- description: Retrieve canonical statements with references to verify biographical, geographic, or scientific claims in text.
  name: Fact-Checking and Verification
- description: Power Wikipedia infoboxes and sister-project templates with live Wikidata entity data via the MediaWiki Action API.
  name: Wikipedia Infobox Data
- description: Resolve named entities from natural language to Wikidata Q-IDs using wbsearchentities and SPARQL label lookups.
  name: NLP Entity Linking
- description: Build ontology-aware search systems using Wikidata's P31 (instance of) and P279 (subclass of) property hierarchies.
  name: Semantic Search
- description: Track real-time edits to Wikidata entities relevant to a domain using the SSE event stream.
  name: Change Monitoring
- description: Publish organizational data as Linked Open Data by aligning custom schemas to Wikidata properties and Q-IDs.
  name: Linked Open Data Publishing
---
