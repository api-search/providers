---
api_count: 21
api_specs:
- filename: sql.json
  format: json
  label: SQL Server REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/sql/resource-manager/Microsoft.Sql/stable/2021-11-01/sql.json
- filename: databases.json
  format: json
  label: Azure SQL Database REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/sql/resource-manager/Microsoft.Sql/stable/2021-11-01/databases.json
apis:
- description: Native database engine APIs for connecting and executing queries against SQL Server.
  name: SQL Server Database Engine API
  slug: ''
- description: REST API for managing SQL Server resources in Azure.
  name: SQL Server REST API
  slug: ''
- description: .NET API for programmatically managing SQL Server instances and databases.
  name: SQL Server Management Objects (SMO)
  slug: ''
- description: REST API for managing and accessing SQL Server Reporting Services.
  name: SQL Server Reporting Services (SSRS) API
  slug: ''
- description: ODBC driver API for connecting applications to SQL Server.
  name: ODBC Driver for SQL Server
  slug: ''
- description: JDBC driver for connecting Java applications to SQL Server.
  name: JDBC Driver for SQL Server
  slug: ''
- description: APIs for managing and querying SQL Server Analysis Services.
  name: SQL Server Analysis Services (SSAS) API
  slug: ''
- description: REST API for managing Azure SQL Database resources.
  name: Azure SQL Database REST API
  slug: ''
- description: REST API for creating, configuring, and managing Azure SQL Managed Instances.
  name: Azure SQL Managed Instance REST API
  slug: ''
- description: Native T-SQL stored procedure sp_invoke_external_rest_endpoint for calling external HTTPS REST endpoints directly from SQL Server 2025 and Azure SQL.
  name: SQL Server External REST Endpoint Invocation
  slug: ''
- description: Open-source tool that generates REST and GraphQL endpoints for SQL Server and Azure SQL databases from configuration, without writing custom API code.
  name: Data API Builder for SQL Server
  slug: ''
- description: The official .NET data provider for Microsoft SQL Server and Azure SQL databases, providing ADO.NET access to SQL Server.
  name: ADO.NET Provider for SQL Server (Microsoft.Data.SqlClient)
  slug: ''
- description: Stand-alone OLE DB data access API for connecting applications to SQL Server.
  name: OLE DB Driver for SQL Server
  slug: ''
- description: Programmable object model for building, managing, and executing ETL data integration packages in SQL Server.
  name: SQL Server Integration Services (SSIS) API
  slug: ''
- description: Node.js driver (tedious/mssql) for connecting JavaScript and TypeScript applications to SQL Server and Azure SQL Database.
  name: Node.js Driver for SQL Server
  slug: ''
- description: Python drivers for connecting to SQL Server including the first-party mssql-python driver, pyodbc, and pymssql.
  name: Python Drivers for SQL Server
  slug: ''
- description: Microsoft Go driver (go-mssqldb) for connecting Go applications to SQL Server and Azure SQL Database using the TDS protocol.
  name: Go Driver for SQL Server
  slug: ''
- description: Microsoft Drivers for PHP for SQL Server providing SQLSRV and PDO_SQLSRV extensions for connecting PHP applications to SQL Server.
  name: PHP Drivers for SQL Server
  slug: ''
- description: Ruby driver (TinyTDS) for connecting Ruby applications to SQL Server using FreeTDS DB-Library bindings.
  name: Ruby Driver for SQL Server
  slug: ''
- description: Entity Framework Core database provider enabling .NET object-relational mapping with SQL Server and Azure SQL databases.
  name: Entity Framework Core SQL Server Provider
  slug: ''
- description: PowerShell cmdlets for managing SQL Server instances, databases, and resources from the command line.
  name: SQL Server PowerShell Module
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://docs.microsoft.com/en-us/sql/sql-server/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/sql-server/sql-server-2022-pricing
- title: ''
  type: Support
  url: https://support.microsoft.com/sql
- title: ''
  type: Download
  url: https://www.microsoft.com/en-us/sql-server/sql-server-downloads
- title: ''
  type: Blog
  url: https://cloudblogs.microsoft.com/sqlserver/
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/t5/sql-server/ct-p/SQLServer
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Status
  url: https://azure.microsoft.com/en-us/status/
- title: ''
  type: Drivers
  url: https://learn.microsoft.com/en-us/sql/connect/sql-connection-libraries
- title: ''
  type: Learning
  url: https://learn.microsoft.com/en-us/sql/sql-server/educational-sql-resources
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/modules/introduction-to-sql-server-2022/
- title: ''
  type: Certification
  url: https://learn.microsoft.com/en-us/credentials/certifications/azure-database-administrator-associate/
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/sql/sql-server/what-s-new-in-sql-server-2022
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2024'
description: A collection of APIs and interfaces for interacting with Microsoft SQL Server.
features:
- description: Full-featured relational database engine with comprehensive T-SQL support for queries, stored procedures, and functions.
  name: T-SQL Query Engine
- description: High availability and disaster recovery with automatic failover for mission-critical databases.
  name: Always On Availability Groups
- description: Memory-optimized tables and natively compiled stored procedures for high-throughput transaction processing.
  name: In-Memory OLTP
- description: Query external data sources including Hadoop, Azure Blob Storage, and Oracle using T-SQL.
  name: PolyBase
- description: Enterprise reporting platform for creating, managing, and delivering paginated reports.
  name: SQL Server Reporting Services
- description: ETL platform for building data integration and transformation packages.
  name: SQL Server Integration Services
- description: Generate REST and GraphQL endpoints from database tables and views without custom code.
  name: Data API Builder
- description: Call external HTTPS REST APIs directly from T-SQL using sp_invoke_external_rest_endpoint.
  name: External REST Endpoint Invocation
image: /assets/icons/sql-server.png
integrations:
- description: Cloud-hosted managed SQL database service with automatic backups and scaling.
  name: Azure SQL Database
- description: Connect Power BI to SQL Server for interactive dashboards and reports.
  name: Power BI
- description: Orchestrate data movement and transformation pipelines with SQL Server as source or destination.
  name: Azure Data Factory
- description: Object-relational mapping for .NET applications with the SQL Server provider.
  name: Entity Framework Core
- description: Develop and manage SQL Server databases with integrated tools in Visual Studio.
  name: Visual Studio
- description: Extend SQL Server data into cloud-scale analytics with Azure Synapse.
  name: Azure Synapse Analytics
layout: provider
modified: '2026-04-18'
name: Microsoft SQL Server APIs
skills: []
slug: sql-server
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft SQL Server APIs\ndescription: >-\n  A collection of APIs and interfaces for interacting with Microsoft SQL Server.\nurl: https://www.microsoft.com/sql-server\ntype: Index\ntags:\n  - Azure SQL\n  - Cloud Database\n  - Data Management\n  - Database\n  - Microsoft\n  - Relational Database\n  - SQL\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\naccess: 3rd-Party\napis:\n  - name: SQL Server Database Engine API\n    description: >-\n      Native database engine APIs for connecting and executing queries against SQL\n      Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/sql/sql-server/\n    baseURL: ''\n    tags:\n      - Database Engine\n      - Query Execution\n      - T-SQL\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/sql/connect/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/sql/sql-server/educational-sql-resources\n\
  \      - type: OpenAPI\n        url: ''\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: SQL Server REST API\n    description: >-\n      REST API for managing SQL Server resources in Azure.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/rest/api/sql/\n    baseURL: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/sql/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/sql/resource-manager/Microsoft.Sql/stable/2021-11-01/sql.json\n      - type: Swagger\n        url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql\n    contact:\n      - FN: Azure Support\n        email: azuresupport@microsoft.com\n  - name: SQL Server Management\
  \ Objects (SMO)\n    description: >-\n      .NET API for programmatically managing SQL Server instances and databases.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/sql/relational-databases/server-management-objects-smo/\n    baseURL: ''\n    tags:\n      - .NET\n      - Automation\n      - Management\n      - SMO\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/sql/relational-databases/server-management-objects-smo/\n      - type: NuGet Package\n        url: https://www.nuget.org/packages/Microsoft.SqlServer.SqlManagementObjects/\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: SQL Server Reporting Services (SSRS) API\n    description: >-\n      REST API for managing and accessing SQL Server Reporting Services.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/sql/reporting-services/\n\
  \    baseURL: http://localhost/reports/api/v2.0\n    tags:\n      - Business Intelligence\n      - Reporting\n      - REST\n      - SSRS\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/sql/reporting-services/developer/rest-api\n      - type: OpenAPI\n        url: ''\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: ODBC Driver for SQL Server\n    description: >-\n      ODBC driver API for connecting applications to SQL Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/sql/connect/odbc/\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Cross-Platform\n      - Driver\n      - ODBC\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/sql/connect/odbc/microsoft-odbc-driver-for-sql-server\n      - type: Download\n        url: https://docs.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server\n\
  \    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: JDBC Driver for SQL Server\n    description: >-\n      JDBC driver for connecting Java applications to SQL Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/sql/connect/jdbc/\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - Java\n      - JDBC\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server\n      - type: Download\n        url: https://docs.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server\n      - type: GitHub\n        url: https://github.com/microsoft/mssql-jdbc\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: SQL Server Analysis Services (SSAS) API\n    description: >-\n      APIs for managing and querying SQL Server\
  \ Analysis Services.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/analysis-services/\n    baseURL: ''\n    tags:\n      - Analysis\n      - Business Intelligence\n      - OLAP\n      - SSAS\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/analysis-services/instances/analysis-services-instance-management\n      - type: PowerShellModule\n        url: https://docs.microsoft.com/en-us/analysis-services/instances/install-windows/install-analysis-services\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Azure SQL Database REST API\n    description: >-\n      REST API for managing Azure SQL Database resources.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://docs.microsoft.com/en-us/azure/azure-sql/database/\n    baseURL: https://management.azure.com\n    tags:\n      - Azure\n\
  \      - Cloud\n      - PaaS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/sql/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/sql/resource-manager/Microsoft.Sql/stable/2021-11-01/databases.json\n    contact:\n      - FN: Azure Support\n        email: azuresupport@microsoft.com\n  - name: Azure SQL Managed Instance REST API\n    description: >-\n      REST API for creating, configuring, and managing Azure SQL Managed Instances.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/\n    baseURL: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Managed Instance\n      - PaaS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/sql/managed-instances\n    \
  \  - type: APIReference\n        url: https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/api-references-create-manage-instance\n    contact:\n      - FN: Azure Support\n        email: azuresupport@microsoft.com\n  - name: SQL Server External REST Endpoint Invocation\n    description: >-\n      Native T-SQL stored procedure sp_invoke_external_rest_endpoint for calling external\n      HTTPS REST endpoints directly from SQL Server 2025 and Azure SQL.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql\n    baseURL: ''\n    tags:\n      - External Endpoints\n      - Integration\n      - REST\n      - SQL Server 2025\n      - T-SQL\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-invoke-external-rest-endpoint-transact-sql\n\
  \    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Data API Builder for SQL Server\n    description: >-\n      Open-source tool that generates REST and GraphQL endpoints for SQL Server and\n      Azure SQL databases from configuration, without writing custom API code.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/azure/data-api-builder/\n    baseURL: ''\n    tags:\n      - Azure\n      - Data API\n      - GraphQL\n      - Open Source\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/data-api-builder/overview\n      - type: GitHub\n        url: https://github.com/Azure/data-api-builder\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: ADO.NET Provider for SQL Server (Microsoft.Data.SqlClient)\n    description: >-\n      The official .NET data provider for Microsoft\
  \ SQL Server and Azure SQL databases,\n      providing ADO.NET access to SQL Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/ado-net/microsoft-ado-net-sql-server\n    baseURL: ''\n    tags:\n      - .NET\n      - ADO.NET\n      - Connectivity\n      - Driver\n      - SqlClient\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/ado-net/introduction-microsoft-data-sqlclient-namespace\n      - type: NuGetPackage\n        url: https://www.nuget.org/packages/Microsoft.Data.SqlClient\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/ado-net/download-microsoft-sqlclient-data-provider\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: OLE DB Driver for SQL Server\n    description: >-\n      Stand-alone OLE DB data access API for connecting applications to SQL Server.\n\
  \    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - OLE DB\n      - Windows\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/oledb/oledb-driver-for-sql-server\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/oledb/download-oledb-driver-for-sql-server\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: SQL Server Integration Services (SSIS) API\n    description: >-\n      Programmable object model for building, managing, and executing ETL data integration\n      packages in SQL Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/integration-services/sql-server-integration-services\n\
  \    baseURL: ''\n    tags:\n      - Automation\n      - Data Integration\n      - ETL\n      - SSIS\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/integration-services/sql-server-integration-services\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Node.js Driver for SQL Server\n    description: >-\n      Node.js driver (tedious/mssql) for connecting JavaScript and TypeScript applications\n      to SQL Server and Azure SQL Database.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - JavaScript\n      - Node.js\n      - Npm\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/node-js/node-js-driver-for-sql-server\n      - type: GitHub\n       \
  \ url: https://github.com/tediousjs/node-mssql\n      - type: npmPackage\n        url: https://www.npmjs.com/package/mssql\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Python Drivers for SQL Server\n    description: >-\n      Python drivers for connecting to SQL Server including the first-party mssql-python\n      driver, pyodbc, and pymssql.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/python/python-driver-for-sql-server\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - Pymssql\n      - Pyodbc\n      - Python\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/python/python-driver-for-sql-server\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/python/pyodbc/python-sql-driver-pyodbc\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/python/mssql-python/python-sql-driver-mssql-python\n\
  \    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Go Driver for SQL Server\n    description: >-\n      Microsoft Go driver (go-mssqldb) for connecting Go applications to SQL Server\n      and Azure SQL Database using the TDS protocol.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/golang/microsoft-go-mssqldb-driver\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - Go\n      - Golang\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/golang/microsoft-go-mssqldb-driver\n      - type: GitHub\n        url: https://github.com/microsoft/go-mssqldb\n      - type: GoPackage\n        url: https://pkg.go.dev/github.com/microsoft/go-mssqldb\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: PHP Drivers for SQL Server\n    description: >-\n    \
  \  Microsoft Drivers for PHP for SQL Server providing SQLSRV and PDO_SQLSRV extensions\n      for connecting PHP applications to SQL Server.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/php/microsoft-php-driver-for-sql-server\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - PDO\n      - PHP\n      - SQLSRV\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/php/microsoft-php-driver-for-sql-server\n      - type: GitHub\n        url: https://github.com/microsoft/msphpsql\n      - type: Download\n        url: https://learn.microsoft.com/en-us/sql/connect/php/download-drivers-php-sql-server\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Ruby Driver for SQL Server\n    description: >-\n      Ruby driver (TinyTDS) for connecting Ruby applications to SQL Server using FreeTDS\n\
  \      DB-Library bindings.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/sql/connect/ruby/step-3-proof-of-concept-connecting-to-sql-using-ruby\n    baseURL: ''\n    tags:\n      - Connectivity\n      - Driver\n      - Ruby\n      - TinyTDS\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sql/connect/ruby/step-3-proof-of-concept-connecting-to-sql-using-ruby\n      - type: GitHub\n        url: https://github.com/rails-sqlserver/tiny_tds\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Entity Framework Core SQL Server Provider\n    description: >-\n      Entity Framework Core database provider enabling .NET object-relational mapping\n      with SQL Server and Azure SQL databases.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/ef/core/providers/sql-server/\n\
  \    baseURL: ''\n    tags:\n      - .NET\n      - Driver\n      - Entity Framework\n      - ORM\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/ef/core/providers/sql-server/\n      - type: NuGetPackage\n        url: https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer\n      - type: GitHub\n        url: https://github.com/dotnet/efcore\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: SQL Server PowerShell Module\n    description: >-\n      PowerShell cmdlets for managing SQL Server instances, databases, and resources\n      from the command line.\n    image: https://www.microsoft.com/sql-server/images/sql-server-logo.png\n    humanURL: https://learn.microsoft.com/en-us/powershell/module/sqlserver/\n    baseURL: ''\n    tags:\n      - Automation\n      - CLI\n      - Management\n      - PowerShell\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/powershell/module/sqlserver/\n\
  \      - type: Download\n        url: https://learn.microsoft.com/en-us/powershell/sql-server/download-sql-server-ps-module\n      - type: GitHub\n        url: https://github.com/microsoft/SQLServerPSModule\n      - type: PowerShellGallery\n        url: https://www.powershellgallery.com/packages/SqlServer\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Getting Started\n    url: https://docs.microsoft.com/en-us/sql/sql-server/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/sql-server/sql-server-2022-pricing\n  - type: Support\n    url: https://support.microsoft.com/sql\n  - type: Download\n    url: https://www.microsoft.com/en-us/sql-server/sql-server-downloads\n  - type: Blog\n    url: https://cloudblogs.microsoft.com/sqlserver/\n  - type: Community\n    url: https://techcommunity.microsoft.com/t5/sql-server/ct-p/SQLServer\n\
  \  - type: Portal\n    url: https://portal.azure.com\n  - type: Status\n    url: https://azure.microsoft.com/en-us/status/\n  - type: Drivers\n    url: https://learn.microsoft.com/en-us/sql/connect/sql-connection-libraries\n  - type: Learning\n    url: https://learn.microsoft.com/en-us/sql/sql-server/educational-sql-resources\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/modules/introduction-to-sql-server-2022/\n  - type: Certification\n    url: https://learn.microsoft.com/en-us/credentials/certifications/azure-database-administrator-associate/\n  - type: GitHubRepository\n    url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/sql\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/sql/sql-server/what-s-new-in-sql-server-2022\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Features\n   \
  \ data:\n      - name: T-SQL Query Engine\n        description: Full-featured relational database engine with comprehensive T-SQL support for queries, stored procedures, and functions.\n      - name: Always On Availability Groups\n        description: High availability and disaster recovery with automatic failover for mission-critical databases.\n      - name: In-Memory OLTP\n        description: Memory-optimized tables and natively compiled stored procedures for high-throughput transaction processing.\n      - name: PolyBase\n        description: Query external data sources including Hadoop, Azure Blob Storage, and Oracle using T-SQL.\n      - name: SQL Server Reporting Services\n        description: Enterprise reporting platform for creating, managing, and delivering paginated reports.\n      - name: SQL Server Integration Services\n        description: ETL platform for building data integration and transformation packages.\n      - name: Data API Builder\n        description: Generate\
  \ REST and GraphQL endpoints from database tables and views without custom code.\n      - name: External REST Endpoint Invocation\n        description: Call external HTTPS REST APIs directly from T-SQL using sp_invoke_external_rest_endpoint.\n  - type: UseCases\n    data:\n      - name: Enterprise Data Management\n        description: Store and manage enterprise data with ACID compliance, security, and high availability.\n      - name: Business Intelligence\n        description: Build BI solutions with reporting services, analysis services, and data integration.\n      - name: Cloud Database Migration\n        description: Migrate on-premises SQL Server databases to Azure SQL Database or Managed Instance.\n      - name: Application Backend\n        description: Use SQL Server as the data tier for web, mobile, and enterprise applications.\n      - name: Data Warehousing\n        description: Build data warehouses with columnstore indexes, partitioning, and ETL pipelines.\n  - type: Integrations\n\
  \    data:\n      - name: Azure SQL Database\n        description: Cloud-hosted managed SQL database service with automatic backups and scaling.\n      - name: Power BI\n        description: Connect Power BI to SQL Server for interactive dashboards and reports.\n      - name: Azure Data Factory\n        description: Orchestrate data movement and transformation pipelines with SQL Server as source or destination.\n      - name: Entity Framework Core\n        description: Object-relational mapping for .NET applications with the SQL Server provider.\n      - name: Visual Studio\n        description: Develop and manage SQL Server databases with integrated tools in Visual Studio.\n      - name: Azure Synapse Analytics\n        description: Extend SQL Server data into cloud-scale analytics with Azure Synapse.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sql-server/refs/heads/main/apis.yml
tags:
- Azure SQL
- Cloud Database
- Data Management
- Database
- Microsoft
- Relational Database
- SQL
url: https://www.microsoft.com/sql-server
use_cases:
- description: Store and manage enterprise data with ACID compliance, security, and high availability.
  name: Enterprise Data Management
- description: Build BI solutions with reporting services, analysis services, and data integration.
  name: Business Intelligence
- description: Migrate on-premises SQL Server databases to Azure SQL Database or Managed Instance.
  name: Cloud Database Migration
- description: Use SQL Server as the data tier for web, mobile, and enterprise applications.
  name: Application Backend
- description: Build data warehouses with columnstore indexes, partitioning, and ETL pipelines.
  name: Data Warehousing
---
