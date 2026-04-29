---
api_count: 1
apis:
- description: Beautiful Soup 4 is a Python library providing a parse tree API for HTML and XML documents. It exposes Tag, NavigableString, BeautifulSoup, and Comment objects with navigation methods (find, find_all,
  name: Beautiful Soup
  slug: beautiful-soup
common:
- title: ''
  type: Website
  url: https://www.crummy.com/software/BeautifulSoup/
- title: ''
  type: Documentation
  url: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
- title: PyPI Package
  type: SDK
  url: https://pypi.org/project/beautifulsoup4/
- title: ''
  type: GitHubOrganization
  url: https://bazaar.launchpad.net/~leonardr/beautifulsoup/bs4
- title: ''
  type: Changelog
  url: https://bazaar.launchpad.net/~leonardr/beautifulsoup/bs4/view/head:/CHANGELOG
created: '2026-03-29'
description: Beautiful Soup is a Python library for pulling data out of HTML and XML files, widely used for web scraping and screen scraping tasks. It provides a parse tree API with simple methods for navigating, searching, and modifying parsed HTML/XML documents. Beautiful Soup automatically handles encoding, supports multiple parsers (html.parser, lxml, html5lib), and integrates with CSS selectors via the Soup Sieve library. Current stable version is 4.14.3.
features:
- description: Supports html.parser (built-in), lxml (fast), and html5lib (browser-like) parsers for flexible HTML/XML parsing.
  name: Multi-Parser Support
- description: Full CSS4 selector support via the Soup Sieve library for familiar CSS-based element selection.
  name: CSS Selector Support
- description: Rich API for navigating the parse tree upward, downward, and sideways including find(), find_all(), parents, children, and siblings.
  name: Tree Navigation API
- description: Automatically detects and handles document encoding using Unicode, Dammit, ensuring correct text extraction.
  name: Automatic Encoding Detection
- description: Full tree modification support including append, insert, extract, decompose, replace_with, wrap, and unwrap operations.
  name: Tree Modification
- description: Multiple output formatters including prettify(), get_text(), and custom formatters for controlled serialization.
  name: Output Formatting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Python HTTP library used in combination with Beautiful Soup to fetch and parse web pages.
  name: Requests
- description: Python web crawling framework that can use Beautiful Soup selectors for content extraction.
  name: Scrapy
- description: Fast XML and HTML parsing library used as an alternate parser backend for Beautiful Soup.
  name: lxml
- description: Pure-Python HTML5 parser used with Beautiful Soup for browser-compatible HTML parsing.
  name: html5lib
- description: DataFrame library commonly used with Beautiful Soup to convert scraped HTML tables into structured data.
  name: Pandas
- description: Browser automation tool used with Beautiful Soup to scrape JavaScript-rendered pages.
  name: Selenium
layout: provider
modified: '2026-04-19'
name: Beautiful Soup
skills: []
slug: beautiful-soup
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: beautiful-soup\nname: Beautiful Soup\ndescription: >-\n  Beautiful Soup is a Python library for pulling data out of HTML and XML files,\n  widely used for web scraping and screen scraping tasks. It provides a parse tree\n  API with simple methods for navigating, searching, and modifying parsed HTML/XML\n  documents. Beautiful Soup automatically handles encoding, supports multiple parsers\n  (html.parser, lxml, html5lib), and integrates with CSS selectors via the Soup Sieve\n  library. Current stable version is 4.14.3.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Extraction\n  - HTML Parsing\n  - Python\n  - Scraping\n  - Web Scraping\n  - XML Parsing\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/beautiful-soup/refs/heads/main/apis.yml\ncreated: '2026-03-29'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: beautiful-soup:beautiful-soup\n    name: Beautiful Soup\n    description:\
  \ >-\n      Beautiful Soup 4 is a Python library providing a parse tree API for HTML and\n      XML documents. It exposes Tag, NavigableString, BeautifulSoup, and Comment\n      objects with navigation methods (find, find_all, CSS selectors), tree traversal\n      (parents, children, siblings), and modification methods (append, extract, replace).\n      Supports html.parser, lxml, and html5lib parsers with automatic encoding detection.\n    humanURL: https://www.crummy.com/software/BeautifulSoup/\n    tags:\n      - Data Extraction\n      - HTML Parsing\n      - Python\n      - Scraping\n      - Web Scraping\n      - XML Parsing\n    properties:\n      - type: Documentation\n        url: https://www.crummy.com/software/BeautifulSoup/bs4/doc/\n      - type: GettingStarted\n        url: https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start\n      - type: SDK\n        url: https://pypi.org/project/beautifulsoup4/\n        title: Python Package (PyPI)\n\ncommon:\n  - type: Website\n\
  \    url: https://www.crummy.com/software/BeautifulSoup/\n  - type: Documentation\n    url: https://www.crummy.com/software/BeautifulSoup/bs4/doc/\n  - type: SDK\n    url: https://pypi.org/project/beautifulsoup4/\n    title: PyPI Package\n  - type: GitHubOrganization\n    url: https://bazaar.launchpad.net/~leonardr/beautifulsoup/bs4\n  - type: Changelog\n    url: https://bazaar.launchpad.net/~leonardr/beautifulsoup/bs4/view/head:/CHANGELOG\n  - type: Features\n    data:\n      - name: Multi-Parser Support\n        description: Supports html.parser (built-in), lxml (fast), and html5lib (browser-like) parsers for flexible HTML/XML parsing.\n      - name: CSS Selector Support\n        description: Full CSS4 selector support via the Soup Sieve library for familiar CSS-based element selection.\n      - name: Tree Navigation API\n        description: Rich API for navigating the parse tree upward, downward, and sideways including find(), find_all(), parents, children, and siblings.\n      - name:\
  \ Automatic Encoding Detection\n        description: Automatically detects and handles document encoding using Unicode, Dammit, ensuring correct text extraction.\n      - name: Tree Modification\n        description: Full tree modification support including append, insert, extract, decompose, replace_with, wrap, and unwrap operations.\n      - name: Output Formatting\n        description: Multiple output formatters including prettify(), get_text(), and custom formatters for controlled serialization.\n  - type: UseCases\n    data:\n      - name: Web Scraping\n        description: Extract data from websites by parsing HTML pages with Beautiful Soup and navigating the DOM tree to find target elements.\n      - name: Data Mining\n        description: Mine structured data from HTML tables, lists, and other markup patterns across large numbers of web pages.\n      - name: Content Extraction\n        description: Extract article text, product information, or other content from web pages for NLP\
  \ pipelines and data analysis.\n      - name: Screen Scraping Legacy Systems\n        description: Automate data extraction from legacy HTML web interfaces that lack modern APIs.\n      - name: HTML Sanitization\n        description: Parse and clean HTML documents by removing unwanted tags, scripts, and formatting.\n      - name: XML Processing\n        description: Parse and query XML documents using Beautiful Soup's tree navigation and search capabilities.\n  - type: Integrations\n    data:\n      - name: Requests\n        description: Python HTTP library used in combination with Beautiful Soup to fetch and parse web pages.\n      - name: Scrapy\n        description: Python web crawling framework that can use Beautiful Soup selectors for content extraction.\n      - name: lxml\n        description: Fast XML and HTML parsing library used as an alternate parser backend for Beautiful Soup.\n      - name: html5lib\n        description: Pure-Python HTML5 parser used with Beautiful Soup for\
  \ browser-compatible HTML parsing.\n      - name: Pandas\n        description: DataFrame library commonly used with Beautiful Soup to convert scraped HTML tables into structured data.\n      - name: Selenium\n        description: Browser automation tool used with Beautiful Soup to scrape JavaScript-rendered pages.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/beautiful-soup/refs/heads/main/apis.yml
tags:
- Data Extraction
- HTML Parsing
- Python
- Scraping
- Web Scraping
- XML Parsing
url: https://raw.githubusercontent.com/api-evangelist/beautiful-soup/refs/heads/main/apis.yml
use_cases:
- description: Extract data from websites by parsing HTML pages with Beautiful Soup and navigating the DOM tree to find target elements.
  name: Web Scraping
- description: Mine structured data from HTML tables, lists, and other markup patterns across large numbers of web pages.
  name: Data Mining
- description: Extract article text, product information, or other content from web pages for NLP pipelines and data analysis.
  name: Content Extraction
- description: Automate data extraction from legacy HTML web interfaces that lack modern APIs.
  name: Screen Scraping Legacy Systems
- description: Parse and clean HTML documents by removing unwanted tags, scripts, and formatting.
  name: HTML Sanitization
- description: Parse and query XML documents using Beautiful Soup's tree navigation and search capabilities.
  name: XML Processing
---
