---
api_count: 13
apis:
- description: Call MATLAB from Python, allowing Python programs to start MATLAB, execute MATLAB functions, and exchange data between Python and MATLAB.
  name: MATLAB Engine API for Python
  slug: ''
- description: Execute MATLAB functions from Java programs and exchange data between Java and MATLAB.
  name: MATLAB Engine API for Java
  slug: ''
- description: Call MATLAB from C++ programs with object-oriented programming support.
  name: MATLAB Engine API for C++
  slug: ''
- description: Call MATLAB from C and Fortran programs using the MATLAB engine library, enabling MATLAB as a computation engine for native applications.
  name: MATLAB Engine API for C and Fortran
  slug: ''
- description: Call MATLAB from .NET programming languages, enabling .NET programs to launch MATLAB, evaluate MATLAB functions with arguments, and exchange data synchronously or asynchronously.
  name: MATLAB Engine API for .NET
  slug: ''
- description: Create and deploy RESTful web services from MATLAB functions using MATLAB Production Server.
  name: MATLAB RESTful Web Services
  slug: ''
- description: RESTful API for executing MATLAB functions on MATLAB Production Server, including function execution, discovery and diagnostics, and secure management of deployable archives.
  name: MATLAB Production Server RESTful API
  slug: ''
- description: Host MATLAB apps and Simulink simulations as interactive web apps, with support for authentication, role-based access, and server management via command-line interface.
  name: MATLAB Web App Server
  slug: ''
- description: Work with MATLAB data types in C++ applications.
  name: MATLAB Data API for C++
  slug: ''
- description: RESTful web services support for making HTTP requests from MATLAB.
  name: MATLAB HTTP Interface
  slug: ''
- description: Build MEX functions that enable calling C, C++, and Fortran code from MATLAB, with support for both the C++ MEX API and the C Matrix API.
  name: MATLAB MEX API
  slug: ''
- description: Build C/C++ shared libraries, .NET assemblies, Java classes, and Python packages from MATLAB programs for integration with custom applications.
  name: MATLAB Compiler SDK API
  slug: ''
- description: IoT analytics platform REST API for reading and writing data to channels, creating and managing channels, and analyzing IoT data with MATLAB in the cloud.
  name: ThingSpeak REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.mathworks.com
- title: ''
  type: Documentation
  url: https://www.mathworks.com/help/index.html
- title: ''
  type: Pricing
  url: https://www.mathworks.com/pricing-licensing.html
- title: ''
  type: Blog
  url: https://blogs.mathworks.com/
- title: ''
  type: Community
  url: https://www.mathworks.com/matlabcentral/
- title: ''
  type: Community
  url: https://www.mathworks.com/matlabcentral/answers/index
- title: ''
  type: GitHubOrganization
  url: https://github.com/mathworks
- title: ''
  type: StatusPage
  url: https://status.mathworks.com/
- title: ''
  type: Support
  url: https://www.mathworks.com/support.html
- title: ''
  type: Login
  url: https://www.mathworks.com/login
created: '2025'
description: APIs and integration points for MATLAB, a programming platform designed for engineers and scientists.
features: []
image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg
integrations: []
layout: provider
modified: '2026-04-19'
name: MATLAB
skills: []
slug: matlab
solutions: []
source_yaml: "name: MATLAB\ndescription: >-\n  APIs and integration points for MATLAB, a programming platform designed for engineers\n  and scientists.\nimage: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\nurl: https://www.mathworks.com\ncreated: '2025'\nmodified: '2026-04-19'\napis:\n  - name: MATLAB Engine API for Python\n    description: >-\n      Call MATLAB from Python, allowing Python programs to start MATLAB, execute MATLAB\n      functions, and exchange data between Python and MATLAB.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/matlab-engine-for-python.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - Engine\n      - Integration\n      - Python\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab-engine-for-python.html\n      - type: GettingStarted\n     \
  \   url: https://www.mathworks.com/help/matlab/matlab_external/install-the-matlab-engine-for-python.html\n      - type: GettingStarted\n        url: https://www.mathworks.com/help/matlab/matlab_external/get-started-with-matlab-engine-for-python.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/matlab.engine.matlabengine-class.html\n      - type: SDK\n        url: https://pypi.org/project/matlabengine/\n      - type: GitHubRepository\n        url: https://github.com/mathworks/matlab-engine-for-python\n  - name: MATLAB Engine API for Java\n    description: >-\n      Execute MATLAB functions from Java programs and exchange data between Java and\n      MATLAB.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/matlab-engine-api-for-java.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - Engine\n      - Integration\n    \
  \  - Java\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab-engine-api-for-java.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/matlabengine-package.html\n  - name: MATLAB Engine API for C++\n    description: >-\n      Call MATLAB from C++ programs with object-oriented programming support.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/matlab-engine-api-for-cpp.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - C++\n      - Engine\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab-engine-api-for-cpp.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/matlab-engine-api-for-c++.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab_external/requirements-to-build-cpp-engine-programs.html\n\
  \  - name: MATLAB Engine API for C and Fortran\n    description: >-\n      Call MATLAB from C and Fortran programs using the MATLAB engine library, enabling\n      MATLAB as a computation engine for native applications.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/matlab_external/introducing-matlab-engine.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - C\n      - Engine\n      - Fortran\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab_external/introducing-matlab-engine.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/calling-matlab-engine-from-c-programs-1.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/calling-matlab-engine-from-fortran-programs.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/engine.html\n\
  \      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab_external/matlab-fortran-api-libraries.html\n  - name: MATLAB Engine API for .NET\n    description: >-\n      Call MATLAB from .NET programming languages, enabling .NET programs to launch\n      MATLAB, evaluate MATLAB functions with arguments, and exchange data synchronously\n      or asynchronously.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/call-matlab-from-net.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - .NET\n      - Engine\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/call-matlab-from-net.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/mathworks.matlab.engine.matlabengine.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab_external/requirements-to-build-net-engine-programs.html\n\
  \  - name: MATLAB RESTful Web Services\n    description: >-\n      Create and deploy RESTful web services from MATLAB functions using MATLAB Production\n      Server.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/mps/restfuljson/creating-http-post-interface-to-restful-web-service.html\n    baseURL: https://www.mathworks.com/products/matlab-production-server.html\n    tags:\n      - Production\n      - REST\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/mps/restfuljson/\n      - type: Documentation\n        url: https://www.mathworks.com/products/matlab-production-server.html\n  - name: MATLAB Production Server RESTful API\n    description: >-\n      RESTful API for executing MATLAB functions on MATLAB Production Server, including\n      function execution, discovery and diagnostics, and secure management of deployable\n      archives.\n\
  \    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/mps/restful-api-and-json.html\n    baseURL: https://www.mathworks.com/help/mps\n    tags:\n      - Deployment\n      - Enterprise\n      - Production Server\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/mps/restful-api-and-json.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/mps/restfuljson/restful-api.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/mps/restfuljson/restful-api-for-discovery-and-diagnostics.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/mps/restfuljson/restful-api-for-deployable-archive-upload.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/mps/client-programming.html\n      - type: SDK\n        url: https://www.mathworks.com/products/matlab-production-server/client-libraries.html\n\
  \      - type: OpenAPI\n        url: https://github.com/mathworks-ref-arch/openapi-productionserver\n      - type: Documentation\n        url: https://www.mathworks.com/help/mps/\n  - name: MATLAB Web App Server\n    description: >-\n      Host MATLAB apps and Simulink simulations as interactive web apps, with support\n      for authentication, role-based access, and server management via command-line\n      interface.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/webappserver/index.html\n    baseURL: https://www.mathworks.com/help/webappserver\n    tags:\n      - Deployment\n      - Server\n      - Web Apps\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/webappserver/index.html\n      - type: Documentation\n        url: https://www.mathworks.com/products/matlab-web-app-server.html\n      - type: GettingStarted\n        url: https://www.mathworks.com/help/webappserver/ug/set-up-matlab-web-app-server.html\n\
  \      - type: Documentation\n        url: https://www.mathworks.com/help/webappserver/server-management.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/webappserver/ref/webappsconfig.html\n  - name: MATLAB Data API for C++\n    description: >-\n      Work with MATLAB data types in C++ applications.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/matlab-data-api-for-c-plus-plus.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n    tags:\n      - C++\n      - Data\n      - Types\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/matlab-data-api-for-c-plus-plus.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/apiref/matlab-data-api-for-c++.html\n  - name: MATLAB HTTP Interface\n    description: >-\n      RESTful web services support for making HTTP requests from MATLAB.\n\
  \    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/http-interface.html\n    baseURL: https://www.mathworks.com/help/matlab\n    tags:\n      - Client\n      - HTTP\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/http-interface.html\n      - type: CodeExamples\n        url: https://www.mathworks.com/help/matlab/ref/webread.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/web-services.html\n  - name: MATLAB MEX API\n    description: >-\n      Build MEX functions that enable calling C, C++, and Fortran code from MATLAB,\n      with support for both the C++ MEX API and the C Matrix API.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/matlab/call-mex-files-1.html\n    baseURL: https://www.mathworks.com/help/matlab/apiref\n\
  \    tags:\n      - C\n      - C++\n      - Extensions\n      - Fortran\n      - MEX\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/matlab/call-mex-files-1.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/matlab_external/cpp-mex-api.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/matlab_external/c-mex-functions.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/cc-mx-matrix-library.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/matlab/ref/mex.html\n  - name: MATLAB Compiler SDK API\n    description: >-\n      Build C/C++ shared libraries, .NET assemblies, Java classes, and Python packages\n      from MATLAB programs for integration with custom applications.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/compiler_sdk/\n\
  \    baseURL: https://www.mathworks.com/help/compiler_sdk\n    tags:\n      - Compiler\n      - Deployment\n      - Integration\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/compiler_sdk/\n      - type: Documentation\n        url: https://www.mathworks.com/products/matlab-compiler-sdk.html\n      - type: GettingStarted\n        url: https://www.mathworks.com/help/compiler_sdk/getting_started_with_compiler_sdk.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/compiler_sdk/cxx/summary-of-sdk-cpp-apis.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/compiler_sdk/dotnet/summary-of-matlab-compiler-sdk-dotnet-apis.html\n      - type: Documentation\n        url: https://www.mathworks.com/help/compiler_sdk/mps.html\n  - name: ThingSpeak REST API\n    description: >-\n      IoT analytics platform REST API for reading and writing data to channels, creating\n      and managing channels,\
  \ and analyzing IoT data with MATLAB in the cloud.\n    image: https://www.mathworks.com/etc/designs/mathworks/img/pic-header-mathworks-logo2.svg\n    humanURL: https://www.mathworks.com/help/thingspeak/rest-api.html\n    baseURL: https://api.thingspeak.com\n    tags:\n      - Analytics\n      - Channels\n      - IoT\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.mathworks.com/help/thingspeak/index.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/thingspeak/rest-api.html\n      - type: APIReference\n        url: https://www.mathworks.com/help/thingspeak/channels-and-charts-api.html\n      - type: Documentation\n        url: https://www.mathworks.com/products/thingspeak.html\n      - type: GitHubRepository\n        url: https://github.com/mathworks/thingspeak-arduino\ncommon:\n  - type: Portal\n    url: https://www.mathworks.com\n  - type: Documentation\n    url: https://www.mathworks.com/help/index.html\n  - type: Pricing\n\
  \    url: https://www.mathworks.com/pricing-licensing.html\n  - type: Blog\n    url: https://blogs.mathworks.com/\n  - type: Community\n    url: https://www.mathworks.com/matlabcentral/\n  - type: Community\n    url: https://www.mathworks.com/matlabcentral/answers/index\n  - type: GitHubOrganization\n    url: https://github.com/mathworks\n  - type: StatusPage\n    url: https://status.mathworks.com/\n  - type: Support\n    url: https://www.mathworks.com/support.html\n  - type: Login\n    url: https://www.mathworks.com/login\n  - type: Features\n    url: https://www.mathworks.com/products/matlab.html\n  - type: UseCases\n    url: https://www.mathworks.com/solutions.html\n  - type: Integrations\n    url: https://www.mathworks.com/products/connections.html\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Data Analysis\n  - Engineering\n  - Machine Learning\n  - Numerical Analysis\n  - Scientific Computing\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/matlab/refs/heads/main/apis.yml
tags:
- Data Analysis
- Engineering
- Machine Learning
- Numerical Analysis
- Scientific Computing
url: https://www.mathworks.com
use_cases: []
---
