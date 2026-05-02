---
api_count: 8
api_specs:
- filename: openapi.json
  format: json
  label: Microsoft Access Database Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://example.com/openapi.json
apis:
- description: API for programmatic access to Microsoft Access databases through various interfaces including ODBC, OLE DB, and DAO.
  name: Microsoft Access Database Engine API
  slug: ''
- description: API for accessing Microsoft Access databases stored in SharePoint or OneDrive through Microsoft Graph.
  name: Microsoft Graph API (for Access Online)
  slug: ''
- description: 'The Access Visual Basic for Applications (VBA) object model provides programmatic access to all Access objects, properties, methods, and events for developing custom solutions and automating database '
  name: Microsoft Access VBA API
  slug: ''
- description: 'Data Access Objects (DAO) provide a programmatic interface to create, query, and modify the structure and data of Access databases, with objects like Database, Recordset, TableDef, QueryDef, and more '
  name: Microsoft Data Access Objects (DAO) API
  slug: ''
- description: ActiveX Data Objects (ADO) enable client applications to access and manipulate data from Access databases through OLE DB providers, supporting features for building client/server and web-based applica
  name: Microsoft ActiveX Data Objects (ADO) API
  slug: ''
- description: The Microsoft Access SQL reference provides documentation for the Access SQL dialect, including data definition language (DDL) for creating and modifying database structures and data manipulation lang
  name: Microsoft Access SQL API
  slug: ''
- description: The Access macro actions interface provides a set of programmable actions for automating database tasks including data operations, form management, navigation, filtering, and system commands without w
  name: Microsoft Access Macro Actions API
  slug: ''
- description: Power Automate for desktop provides built-in actions for automating Microsoft Access databases, including launching Access instances, reading tables, running stored queries, executing macros, and clos
  name: Power Automate Access Actions API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.microsoft.com/en-us/microsoft-365
- title: ''
  type: Support
  url: https://support.microsoft.com/access
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/access/compare-microsoft-access-plans-and-pricing
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/access-blog/bg-p/AccessBlog
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: Developer Documentation
  url: https://learn.microsoft.com/en-us/office/client-developer/access/access-home
- title: ''
  type: Desktop Database Reference
  url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/
- title: ''
  type: Access Database Engine Download
  url: https://www.microsoft.com/en-us/download/details.aspx?id=54920
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: JSON-LD
  url: json-ld/microsoft-access-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-access-database-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-access-table-schema.json
created: '2024'
description: Microsoft Access is a database management system from Microsoft that combines the relational Microsoft Jet Database Engine with a graphical user interface and software development tools.
features: []
image: https://www.microsoft.com/en-us/microsoft-365/access
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Access Context
  property_count: 9
  slug: microsoft-access-context
layout: provider
modified: '2026-04-28'
name: Microsoft Access
skills: []
slug: microsoft-access
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Access\ndescription: Microsoft Access is a database management system from Microsoft that combines the relational Microsoft Jet Database Engine with a graphical user interface and software development tools.\nimage: https://www.microsoft.com/en-us/microsoft-365/access\ntags:\n  - Access Database\n  - Database\n  - Desktop Database\n  - Microsoft\n  - Relational Database\ncreated: '2024'\nmodified: '2026-04-28'\nurl: https://www.microsoft.com/en-us/microsoft-365/access\nspecificationVersion: '0.18'\napis:\n  - name: Microsoft Access Database Engine API\n    description: >-\n      API for programmatic access to Microsoft Access databases through various interfaces\n      including ODBC, OLE DB, and DAO.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/client-developer/access/access-home\n    baseUrl: https://api.example.com/access\n    tags:\n      - DAO\n      - Database\n      - ODBC\n \
  \     - OLE DB\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/\n      - type: OpenAPI\n        url: https://example.com/openapi.json\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/office/vba/access/concepts/miscellaneous/concepts-access-vba-reference\n  - name: Microsoft Graph API (for Access Online)\n    description: >-\n      API for accessing Microsoft Access databases stored in SharePoint or OneDrive\n      through Microsoft Graph.\n    image: https://learn.microsoft.com/graph/images/microsoft-graph.png\n    humanUrl: https://learn.microsoft.com/en-us/graph/overview\n    baseUrl: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud Database\n      - Microsoft Graph\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/list\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n\
  \      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Microsoft Access VBA API\n    description: The Access Visual Basic for Applications (VBA) object model provides programmatic access to all Access objects, properties, methods, and events for developing custom solutions and automating database operations.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/vba/api/overview/access\n    tags:\n      - Automation\n      - Macros\n      - Object Model\n      - VBA\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/vba/api/overview/access\n      - type: Object Model Reference\n        url: https://learn.microsoft.com/en-us/office/vba/api/overview/access/object-model\n      - type: Application Object Reference\n        url: https://learn.microsoft.com/en-us/office/vba/api/access.application\n      - type: DoCmd Object Reference\n\
  \        url: https://learn.microsoft.com/en-us/office/vba/api/access.docmd\n  - name: Microsoft Data Access Objects (DAO) API\n    description: Data Access Objects (DAO) provide a programmatic interface to create, query, and modify the structure and data of Access databases, with objects like Database, Recordset, TableDef, QueryDef, and more mapping directly to database constructs.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-data-access-objects-reference\n    tags:\n      - DAO\n      - Data Access\n      - QueryDef\n      - Recordset\n      - TableDef\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-data-access-objects-reference\n      - type: Database Object Reference\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/database-object-dao\n\
  \  - name: Microsoft ActiveX Data Objects (ADO) API\n    description: ActiveX Data Objects (ADO) enable client applications to access and manipulate data from Access databases through OLE DB providers, supporting features for building client/server and web-based applications with extensions for multidimensional data (ADO MD) and schema management (ADOX).\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-activex-data-objects-reference\n    tags:\n      - ActiveX\n      - ADO\n      - Data Access\n      - OLE DB\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-activex-data-objects-reference\n      - type: OLE DB Providers Reference\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/ole-db-providers\n\
  \  - name: Microsoft Access SQL API\n    description: The Microsoft Access SQL reference provides documentation for the Access SQL dialect, including data definition language (DDL) for creating and modifying database structures and data manipulation language (DML) for querying and updating data.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-access-sql-reference\n    tags:\n      - DDL\n      - DML\n      - Query\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/microsoft-access-sql-reference\n      - type: SQL Reference Overview\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/overview-of-the-access-sql-reference\n  - name: Microsoft Access Macro Actions API\n    description: The Access\
  \ macro actions interface provides a set of programmable actions for automating database tasks including data operations, form management, navigation, filtering, and system commands without writing VBA code.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/access-macro-actions-access-developer-reference\n    tags:\n      - Actions\n      - Automation\n      - Macros\n      - No-Code\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/access-macro-actions-access-developer-reference\n      - type: Macro Commands Reference\n        url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/macro-commands\n  - name: Power Automate Access Actions API\n    description: Power Automate for desktop provides built-in actions for automating\
  \ Microsoft Access databases, including launching Access instances, reading tables, running stored queries, executing macros, and closing databases programmatically within desktop flows.\n    image: https://www.microsoft.com/en-us/microsoft-365/access\n    humanUrl: https://learn.microsoft.com/en-us/power-automate/desktop-flows/actions-reference/access\n    tags:\n      - Automation\n      - Desktop Flows\n      - Power Automate\n      - RPA\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-automate/desktop-flows/actions-reference/access\ncommon:\n  - type: Portal\n    url: https://www.microsoft.com/en-us/microsoft-365\n  - type: Support\n    url: https://support.microsoft.com/access\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/access/compare-microsoft-access-plans-and-pricing\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/access-blog/bg-p/AccessBlog\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/servicesagreement\n\
  \  - type: Developer Documentation\n    url: https://learn.microsoft.com/en-us/office/client-developer/access/access-home\n  - type: Desktop Database Reference\n    url: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/\n  - type: Access Database Engine Download\n    url: https://www.microsoft.com/en-us/download/details.aspx?id=54920\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: JSON-LD\n    url: json-ld/microsoft-access-context.jsonld\n  - type: JSONSchema\n    url: json-schema/microsoft-access-database-schema.json\n  - type: JSONSchema\n    url: json-schema/microsoft-access-table-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-access/refs/heads/main/apis.yml
tags:
- Access Database
- Database
- Desktop Database
- Microsoft
- Relational Database
url: https://www.microsoft.com/en-us/microsoft-365/access
use_cases: []
---
