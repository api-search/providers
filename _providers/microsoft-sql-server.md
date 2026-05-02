---
api_count: 14
api_specs:
- filename: openapi.yaml
  format: yaml
  label: SQL Server Database Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.microsoft.com/sql/connect/
- filename: sql
  format: yaml
  label: Azure SQL Database REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql
- filename: '2.0'
  format: yaml
  label: SQL Server Reporting Services (SSRS) API
  slug: ''
  spec_type: OpenAPI
  url: https://app.swaggerhub.com/apis/microsoft-rs/SSRS/2.0
apis:
- description: Core database engine APIs for querying, managing, and administering SQL Server databases.
  name: SQL Server Database Engine API
  slug: ''
- description: .NET API for managing and administering SQL Server programmatically.
  name: SQL Server Management Objects (SMO) API
  slug: ''
- description: REST API for managing Azure SQL Database resources and configurations.
  name: Azure SQL Database REST API
  slug: ''
- description: REST API for managing reports, subscriptions, and data sources in SQL Server Reporting Services.
  name: SQL Server Reporting Services (SSRS) API
  slug: ''
- description: API for managing SSIS packages, projects, and execution in the SSIS Catalog.
  name: SQL Server Integration Services (SSIS) Catalog API
  slug: ''
- description: REST API for creating, configuring, and managing Azure SQL Managed Instances including databases, operations, and scheduling.
  name: Azure SQL Managed Instance REST API
  slug: ''
- description: Open source configuration-based engine that creates REST and GraphQL APIs for SQL Server, Azure SQL, Azure Cosmos DB, PostgreSQL, and MySQL databases.
  name: Data API Builder
  slug: ''
- description: REST API for managing Azure Analysis Services resources and performing asynchronous data refreshes of tabular models.
  name: Azure Analysis Services REST API
  slug: ''
- description: ADO.NET data provider for .NET Framework and .NET Core used for connecting to SQL Server, executing commands, and retrieving results.
  name: Microsoft SqlClient Data Provider (ADO.NET)
  slug: ''
- description: Type 4 JDBC driver providing database connectivity to SQL Server through standard JDBC application program interfaces on the Java platform.
  name: Microsoft JDBC Driver for SQL Server
  slug: ''
- description: ODBC driver providing native-code API connectivity to SQL Server and Azure SQL Database for applications on Windows, Linux, and macOS.
  name: Microsoft ODBC Driver for SQL Server
  slug: ''
- description: Stand-alone OLE DB data access API for low-level COM components requiring high-performance access to SQL Server.
  name: Microsoft OLE DB Driver for SQL Server
  slug: ''
- description: Python driver using Direct Database Connectivity for direct connections to SQL Server without requiring an external driver manager, compliant with Python DB-API 2.0.
  name: Microsoft Python Driver for SQL Server (mssql-python)
  slug: ''
- description: Open-source JavaScript implementation of the TDS protocol for connecting to SQL Server from Node.js on Windows, Linux, or macOS.
  name: Node.js Driver for SQL Server (tedious)
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://docs.microsoft.com/sql/sql-server/sql-server-get-started
- title: ''
  type: Downloads
  url: https://www.microsoft.com/sql-server/sql-server-downloads
- title: ''
  type: Pricing
  url: https://www.microsoft.com/sql-server/sql-server-2022-pricing
- title: ''
  type: Support
  url: https://support.microsoft.com/sql
- title: ''
  type: Blog
  url: https://cloudblogs.microsoft.com/sqlserver/
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/t5/sql-server/ct-p/SQLServer
- title: ''
  type: Training
  url: https://docs.microsoft.com/learn/sql-server/
- title: ''
  type: Release Notes
  url: https://docs.microsoft.com/sql/sql-server/sql-server-version-information
- title: ''
  type: Driver History
  url: https://learn.microsoft.com/en-us/sql/connect/connect-history
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoft/sql-server-samples
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/sql/sql-server/what-s-new-in-sql-server-2025
- title: ''
  type: Forum
  url: https://learn.microsoft.com/en-us/answers/tags/191/sql-server
- title: ''
  type: Feedback
  url: https://feedback.azure.com/d365community/forum/04fe6ee0-3b25-ec11-b6e6-000d3a4f0da0
- title: ''
  type: Videos
  url: https://learn.microsoft.com/en-us/shows/data-exposed/
created: '2024'
description: A relational database management system developed by Microsoft for enterprise-scale data management and business intelligence solutions.
features: []
image: https://www.microsoft.com/sql-server/logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft SQL Server
skills: []
slug: microsoft-sql-server
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-sql-server\nname: Microsoft SQL Server\ndescription: >-\n  A relational database management system developed by Microsoft for enterprise-scale\n  data management and business intelligence solutions.\nimage: https://www.microsoft.com/sql-server/logo.png\nurl: https://www.microsoft.com/sql-server\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Cloud\n  - Data Management\n  - Database\n  - Enterprise\n  - Relational Database\n  - SQL\napis:\n  - name: SQL Server Database Engine API\n    description: >-\n      Core database engine APIs for querying, managing, and administering SQL Server\n      databases.\n    image: https://www.microsoft.com/sql-server/database-engine-logo.png\n    humanURL: https://docs.microsoft.com/sql/sql-server/\n    baseURL: https://your-server.database.windows.net\n    tags:\n      - Database\n      - Query\n      - Transact-SQL\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/sql/sql-server/sql-server-technical-documentation\n\
  \      - type: OpenAPI\n        url: https://docs.microsoft.com/sql/connect/\n      - type: Authentication\n        url: https://docs.microsoft.com/sql/relational-databases/security/authentication-access/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com/sql\n  - name: SQL Server Management Objects (SMO) API\n    description: >-\n      .NET API for managing and administering SQL Server programmatically.\n    humanURL: https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/\n    baseURL: https://api.example.com/smo\n    tags:\n      - .NET\n      - Administration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/overview-smo\n\
  \      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.SqlServer.SqlManagementObjects\n      - type: Code Samples\n        url: https://docs.microsoft.com/sql/relational-databases/server-management-objects-smo/create-program/\n  - name: Azure SQL Database REST API\n    description: >-\n      REST API for managing Azure SQL Database resources and configurations.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/sql/\n    baseURL: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Database Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/sql/\n      - type: OpenAPI\n        url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql\n      - type: Authentication\n        url: https://docs.microsoft.com/azure/active-directory/develop/\n      - type: Pricing\n        url: https://azure.microsoft.com/pricing/details/sql-database/\n    \
  \  - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/rest/api/sql/rest-api-sql-create-or-update-database\n    contact:\n      - FN: Azure Support\n        email: azuresupport@microsoft.com\n        url: https://azure.microsoft.com/support/\n  - name: SQL Server Reporting Services (SSRS) API\n    description: >-\n      REST API for managing reports, subscriptions, and data sources in SQL Server\n      Reporting Services.\n    humanURL: https://docs.microsoft.com/sql/reporting-services/\n    baseURL: https://your-server/reports/api/v2.0\n    tags:\n      - Business Intelligence\n      - Reporting\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/reporting-services/developer/rest-api\n      - type: OpenAPI\n        url: https://app.swaggerhub.com/apis/microsoft-rs/SSRS/2.0\n      - type: Tutorial\n        url: https://docs.microsoft.com/sql/reporting-services/tutorial-access-rest-api\n      - type: APIReference\n\
  \        url: https://learn.microsoft.com/en-us/rest/api/sql-server-reporting/\n  - name: SQL Server Integration Services (SSIS) Catalog API\n    description: >-\n      API for managing SSIS packages, projects, and execution in the SSIS Catalog.\n    humanURL: https://docs.microsoft.com/sql/integration-services/\n    baseURL: https://your-server/SSISDB\n    tags:\n      - Data Pipeline\n      - ETL\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/sql/integration-services/service/package-management-ssis-service\n      - type: Stored Procedures\n        url: https://docs.microsoft.com/sql/integration-services/system-stored-procedures/\n  - name: Azure SQL Managed Instance REST API\n    description: >-\n      REST API for creating, configuring, and managing Azure SQL Managed Instances\n      including databases, operations, and scheduling.\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Database Management\n      - Managed Instance\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/sql/managed-instances\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/instance-create-quickstart\n      - type: Pricing\n        url: https://azure.microsoft.com/pricing/details/azure-sql-managed-instance/\n  - name: Data API Builder\n    description: >-\n      Open source configuration-based engine that creates REST and GraphQL APIs for\n      SQL Server, Azure SQL, Azure Cosmos DB, PostgreSQL, and MySQL databases.\n    humanURL: https://learn.microsoft.com/en-us/azure/data-api-builder/overview\n    baseURL: https://localhost:5000/api\n\
  \    tags:\n      - CRUD\n      - Data Access\n      - GraphQL\n      - Open Source\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/data-api-builder/\n      - type: SourceCode\n        url: https://github.com/Azure/data-api-builder\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/data-api-builder/overview\n  - name: Azure Analysis Services REST API\n    description: >-\n      REST API for managing Azure Analysis Services resources and performing asynchronous\n      data refreshes of tabular models.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/analysisservices/\n    baseURL: https://management.azure.com\n    tags:\n      - Analysis Services\n      - Azure\n      - Business Intelligence\n      - REST API\n      - Tabular Models\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/analysisservices/\n      - type: ClientLibraries\n\
  \        url: https://learn.microsoft.com/en-us/analysis-services/client-libraries\n      - type: TMSLReference\n        url: https://learn.microsoft.com/en-us/analysis-services/tmsl/tabular-model-scripting-language-tmsl-reference\n  - name: Microsoft SqlClient Data Provider (ADO.NET)\n    description: >-\n      ADO.NET data provider for .NET Framework and .NET Core used for connecting to\n      SQL Server, executing commands, and retrieving results.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/ado-net/overview-sqlclient-driver\n    tags:\n      - .NET\n      - ADO.NET\n      - Data Provider\n      - SqlClient\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/ado-net/overview-sqlclient-driver\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dotnet/api/microsoft.data.sqlclient\n      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.Data.SqlClient\n      - type: Download\n\
  \        url: https://learn.microsoft.com/en-us/sql/connect/ado-net/download-microsoft-sqlclient-data-provider\n  - name: Microsoft JDBC Driver for SQL Server\n    description: >-\n      Type 4 JDBC driver providing database connectivity to SQL Server through standard\n      JDBC application program interfaces on the Java platform.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server\n    tags:\n      - Cross-Platform\n      - Driver\n      - Java\n      - JDBC\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/sql/connect/jdbc/reference/jdbc-driver-api-reference\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server\n      - type: SourceCode\n        url: https://github.com/microsoft/mssql-jdbc\n\
  \  - name: Microsoft ODBC Driver for SQL Server\n    description: >-\n      ODBC driver providing native-code API connectivity to SQL Server and Azure SQL\n      Database for applications on Windows, Linux, and macOS.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server\n    tags:\n      - Cross-Platform\n      - Driver\n      - Native Code\n      - ODBC\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server\n  - name: Microsoft OLE DB Driver for SQL Server\n    description: >-\n      Stand-alone OLE DB data access API for low-level COM components requiring high-performance\n      access to SQL Server.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server\n    tags:\n      - COM\n \
  \     - Driver\n      - OLE DB\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server\n      - type: ProgrammingGuide\n        url: https://learn.microsoft.com/en-us/sql/connect/oledb/ole-db/oledb-driver-for-sql-server-programming\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/oledb/download-oledb-driver-for-sql-server\n  - name: Microsoft Python Driver for SQL Server (mssql-python)\n    description: >-\n      Python driver using Direct Database Connectivity for direct connections to SQL\n      Server without requiring an external driver manager, compliant with Python DB-API\n      2.0.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python\n    tags:\n      - Cross-Platform\n      - DB-API\n      - Driver\n      - Python\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python\n\
  \      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python-quickstart\n      - type: SourceCode\n        url: https://github.com/microsoft/mssql-python\n      - type: SDK\n        url: https://pypi.org/project/mssql-python/\n  - name: Node.js Driver for SQL Server (tedious)\n    description: >-\n      Open-source JavaScript implementation of the TDS protocol for connecting to\n      SQL Server from Node.js on Windows, Linux, or macOS.\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server\n    tags:\n      - Cross-Platform\n      - Driver\n      - JavaScript\n      - Node.js\n      - TDS\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server\n      - type: SourceCode\n        url: https://github.com/tediousjs/tedious\n      - type: SDK\n        url: https://www.npmjs.com/package/mssql\n\
  common:\n  - type: Getting Started\n    url: https://docs.microsoft.com/sql/sql-server/sql-server-get-started\n  - type: Downloads\n    url: https://www.microsoft.com/sql-server/sql-server-downloads\n  - type: Pricing\n    url: https://www.microsoft.com/sql-server/sql-server-2022-pricing\n  - type: Support\n    url: https://support.microsoft.com/sql\n  - type: Blog\n    url: https://cloudblogs.microsoft.com/sqlserver/\n  - type: Community\n    url: https://techcommunity.microsoft.com/t5/sql-server/ct-p/SQLServer\n  - type: Training\n    url: https://docs.microsoft.com/learn/sql-server/\n  - type: Release Notes\n    url: https://docs.microsoft.com/sql/sql-server/sql-server-version-information\n  - type: Driver History\n    url: https://learn.microsoft.com/en-us/sql/connect/connect-history\n  - type: GitHub Organization\n    url: https://github.com/microsoft/sql-server-samples\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/sql/sql-server/what-s-new-in-sql-server-2025\n\
  \  - type: Forum\n    url: https://learn.microsoft.com/en-us/answers/tags/191/sql-server\n  - type: Feedback\n    url: https://feedback.azure.com/d365community/forum/04fe6ee0-3b25-ec11-b6e6-000d3a4f0da0\n  - type: Videos\n    url: https://learn.microsoft.com/en-us/shows/data-exposed/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-sql-server/refs/heads/main/apis.yml
tags:
- Cloud
- Data Management
- Database
- Enterprise
- Relational Database
- SQL
url: https://www.microsoft.com/sql-server
use_cases: []
---
