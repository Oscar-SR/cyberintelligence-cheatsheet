# Tools

## Search engines

Search engines provide broad access to indexed web content and are often the first entry point in OSINT investigations. When combined with advanced operators, they enable analysts to efficiently filter noise, uncover hidden resources, and identify relevant documents, metadata, and references across the open web.

| <h2>Google</h2> | |
|-----------------|---|
| **Description** | General-purpose search engine widely used for OSINT investigations through advanced search operators. |
| **Access** | Web: [https://www.google.com](https://www.google.com) |
| **Key Features** | <ul><li>Web pages and documents</li><li>Cached content</li><li>Metadata via advanced operators (site:, filetype:, intitle:)</li></ul> |
| **License** | Free |

| <h2>Bing</h2> | |
|---------------|---|
| **Description** | General search engine useful as an alternative data source and for cross-validation of results. |
| **Access** | Web: [https://www.bing.com](https://www.bing.com) |
| **Key Features** | <ul><li>Web pages</li><li>Indexed documents</li><li>Image and video search results</li></ul> |
| **License** | Free |

| <h2>DuckDuckGo</h2> | |
|---------------------|---|
| **Description** | Privacy-focused search engine with reduced personalization and tracking. |
| **Access** | Web: [https://duckduckgo.com](https://duckduckgo.com) |
| **Key Features** | <ul><li>Web search results</li><li>Instant answers</li><li>Reduced user-based bias</li></ul> |
| **License** | Free |

## Vertical search engines

Vertical search engines focus on a specific type of data or domain, offering deeper and more specialized results than general-purpose search engines. In OSINT, they are essential for reducing information overload and retrieving high-signal data such as exposed services, images, social media content, or historical web snapshots.

| <h2>Google Images</h2> | |
|------------------------|---|
| **Description** | Image search engine with built-in reverse image search |
| **Access** | Web: [https://images.google.com](https://images.google.com) |
| **Key Features** | <ul><li>Reverse image search (upload image or paste URL)</li><li>Detection of visually similar images</li><li>Source webpages and image context</li></ul> |
| **License** | Free |


| <h2>Yandex Images</h2> | |
|------------------------|---|
| **Description** | Image search engine particularly effective for reverse image searches. |
| **Access** | Web: [https://yandex.com/images](https://yandex.com/images) |
| **Key Features** | <ul><li>Visually similar images</li><li>Image sources</li><li>Alternate resolutions</li></ul> |
| **License** | Free |

| <h2>crt.sh</h2> | |
|-----------------|---|
| **Description** | Search engine for public TLS/SSL certificates. |
| **Access** | Web: [https://crt.sh](https://crt.sh) |
| **Key Features** | <ul><li>Issued certificates</li><li>Subdomain discovery</li><li>Certificate metadata</li></ul> |
| **License** | Free |

| <h2>Shodan</h2> | |
|-----------------|---|
| **Description** | Internet-wide scanning service for inventorying exposed services and fingerprinting IoT and networked devices. |
| **Access** | Web: [https://www.shodan.io](https://www.shodan.io) |
| **Key Features** | <ul><li>Search and filter exposed services by banner, port, or vulnerability</li><li>Command-line interface and API for automation and integration</li><li>Historical data and monitoring of infrastructure changes</li></ul> |
| **License** | Freemium |

## Web archives

Web archives preserve historical versions of websites and online content, allowing analysts to examine how information has changed over time. They are particularly valuable for attribution, timeline reconstruction, and recovering deleted or altered content that is no longer available on the live web.

| <h2>Wayback Machine</h2> | |
|--------------------------|---|
| **Description** | Web archiving service providing historical snapshots of websites. |
| **Access** | Web: [https://web.archive.org/](https://web.archive.org/) |
| **Key Features** | <ul><li>Archived versions of websites</li><li>Historical page content</li><li>Deleted or modified pages</li></ul> |
| **License** | Free |

| <h2>CDX API</h2> | |
|------------------|---|
| **Description** | API interface for querying Wayback Machine indexes programmatically. |
| **Access** | Repository: [https://github.com/internetarchive/wayback/tree/master/wayback-cdx-server](https://github.com/internetarchive/wayback/tree/master/wayback-cdx-server) |
| **Key Features** | <ul><li>Snapshot metadata</li><li>Timestamped URLs</li><li>Change history</li></ul> |
| **License** | Free |

| <h2>Waybackpack</h2> | |
|---|---|
| **Category** | Web Archiving, Attribution, Historical Analysis |
| **Access** | Repository: [https://github.com/jsvine/waybackpack](https://github.com/jsvine/waybackpack) |
| **Description** | Tool for downloading all archived versions of a website from the Wayback Machine, useful for attribution and historical analysis. |
| **Key Features** | <ul><li>Bulk download of archived snapshots of websites</li><li>Support for filtering by date and file type</li><li>Useful for tracking content changes over time</li></ul> |
| **License** | Open source (MIT) |

| <h2>Common Crawl</h2> | |
|-----------------------|---|
| **Description** | Open repository of large-scale web crawl data for bulk analysis and research. |
| **Access** | Web: [https://commoncrawl.org](https://commoncrawl.org) |
| **Key Features** | <ul><li>HTML content</li><li>Web metadata</li><li>Large-scale historical datasets</li></ul> |
| **License** | Open source |

## Government records

Government records include publicly accessible databases and official publications released by state institutions. These sources provide authoritative data such as corporate registrations, legal notices, financial disclosures, and open datasets, making them critical for verification, attribution, and contextual analysis.

| <h2>data.gov</h2> | |
|-------------------|---|
| **Description** | US government open data portal providing access to public datasets. |
| **Access** | Web: [https://www.data.gov](https://www.data.gov) |
| **Key Features** | <ul><li>Government datasets</li><li>Statistics and reports</li><li>Geospatial data</li></ul> |
| **License** | Free |

| <h2>data.europa.eu</h2> | |
|-------------------------|---|
| **Description** | European Union open data portal aggregating datasets from EU institutions and member states. |
| **Access** | Web: [https://data.europa.eu](https://data.europa.eu) |
| **Key Features** | <ul><li>EU datasets</li><li>Policy-related data</li><li>Economic and social indicators</li></ul> |
| **License** | Free |

| <h2>datos.gob.es</h2> | |
|-----------------------|---|
| **Description** | Spanish national open data portal for public sector information. |
| **Access** | Web: [https://datos.gob.es](https://datos.gob.es) |
| **Key Features** | <ul><li>Administrative datasets</li><li>Geographical information</li><li>Public sector statistics</li></ul> |
| **License** | Free |

| <h2>UK Companies House</h2> | |
|-----------------------------|---|
| **Description** | Official UK registry for company information. |
| **Access** | Web: [https://www.gov.uk/government/organisations/companies-house](https://www.gov.uk/government/organisations/companies-house) |
| **Key Features** | <ul><li>Company registrations</li><li>Directors and shareholders</li><li>Financial filings</li></ul> |
| **License** | Free |

| <h2>SEC EDGAR</h2> | |
|--------------------|---|
| **Description** | US SEC database of corporate financial filings. |
| **Access** | Web: [https://www.sec.gov/edgar](https://www.sec.gov/edgar) |
| **Key Features** | <ul><li>Annual and quarterly reports</li><li>Ownership disclosures</li><li>Regulatory filings</li></ul> |
| **License** | Free |

## Domain and network

Domain and network intelligence tools provide visibility into internet infrastructure, including domain ownership, IP address allocation, DNS records, and TLS certificates. They are fundamental for mapping digital assets, identifying relationships between entities, and supporting technical attribution in OSINT and cyber intelligence investigations.

| <h2>WHOIS</h2> | |
|----------------|---|
| **Description** | Classic protocol to query information about domains and IPs, including registrant, creation/expiration dates, and DNS servers. |
| **Access** | CLI: `whois example.com` <br> Web: [https://whois.domaintools.com](https://whois.domaintools.com) |
| **Key Features** | <ul><li>Domain owner / registrant</li><li>Creation and expiration dates</li><li>DNS servers and administrative contacts</li></ul> |
| **License** | Open source |

| <h2>RDAP</h2> | |
|---------------|---|
| **Description** | Modern protocol that replaces WHOIS, providing standardized JSON responses; ideal for automation and structured analysis of domains and IPs. |
| **Access** | CLI: `curl https://rdap.org/domain/example.com` <br> Web: [https://rdap.org](https://rdap.org) |
| **Key Features** | <ul><li>Domain owner / registrant</li><li>Creation, update, and expiration dates</li><li>DNS servers, contacts, and legal notes</li></ul> |
| **License** | Open source |

| <h2>Nmap</h2> | |
|---------------|---|
| **Description** | Network scanning and reconnaissance tool used to discover hosts, open ports, services, and operating systems. |
| **Access** | CLI: `nmap target` <br> Web: [https://nmap.org](https://nmap.org) <br> Repository: [https://svn.nmap.org/](https://svn.nmap.org/) |
| **Key Features** | <ul><li>Host discovery and port scanning</li><li>Service and version detection</li><li>OS fingerprinting and scripting engine (NSE)</li></ul> |
| **License** | Open source |

## Media monitoring

Media monitoring tools aggregate and analyze digital news sources at local, national, and global levels. They enable continuous tracking of events, narratives, and trends, and support large-scale analysis of media coverage, making them valuable for situational awareness and strategic intelligence.

| <h2>Google News</h2> | |
|----------------------|---|
| **Description** | News aggregation platform with advanced search and filtering options. |
| **Access** | Web: [https://news.google.com](https://news.google.com) |
| **Key Features** | <ul><li>News articles</li><li>Source attribution</li><li>Timeline-based results</li></ul> |
| **License** | Free |

| <h2>GDELT 2.0</h2> | |
|--------------------|---|
| **Description** | Global database for monitoring worldwide news media and events. |
| **Access** | Web: [https://www.gdeltproject.org](https://www.gdeltproject.org) |
| **Key Features** | <ul><li>Global news coverage</li><li>Event metadata</li><li>Geopolitical indicators</li></ul> |
| **License** | Free |

## Geo-OSINT

Geo-OSINT tools leverage geospatial data such as satellite imagery, sensor feeds, and location-based tracking systems. These sources allow analysts to verify locations, monitor physical movements, and correlate events in the real world with digital information.

| <h2>Sentinel-2</h2> | |
|---------------------|---|
| **Description** | Earth observation satellite providing free multispectral imagery. |
| **Access** | Web: [https://sentinel.esa.int](https://sentinel.esa.int) |
| **Key Features** | <ul><li>Satellite imagery</li><li>Environmental monitoring data</li><li>Temporal change detection</li></ul> |
| **License** | Free |

| <h2>MarineTraffic</h2> | |
|------------------------|---|
| **Description** | AIS-based vessel tracking platform. |
| **Access** | Web: [https://www.marinetraffic.com](https://www.marinetraffic.com) |
| **Key Features** | <ul><li>Ship positions</li><li>Vessel metadata</li><li>Historical movement tracks</li></ul> |
| **License** | Freemium |

## Data leaks

Data leak sources include platforms where raw text, databases, or credentials are publicly shared, intentionally or unintentionally. In OSINT and CTI, they are commonly used to identify exposed information, monitor breach activity, and detect early indicators of compromise or criminal activity.

| <h2>Pastebin</h2> | |
|-------------------|---|
| **Description** | Website used to publish text content, often associated with leaks or dumps. |
| **Access** | Web: [https://pastebin.com](https://pastebin.com) |
| **Key Features** | <ul><li>Leaked credentials</li><li>Configuration files</li><li>Source code snippets</li></ul> |
| **License** | Free / Freemium |

## People search

People search tools focus on identifying and correlating information related to individuals across public sources. They support the discovery of digital footprints, social connections, and publicly available personal data, and are often used in background research and attribution workflows.

| <h2>Recon-ng</h2> | |
|-------------------|---|
| **Description** | Modular Metasploit-style framework for OSINT; ideal for large-scale scripting. |
| **Access** | Repository: [https://github.com/lanmaster53/recon-ng](https://github.com/lanmaster53/recon-ng) |
| **Key Features** | <ul><li>Modular architecture with multiple reconnaissance modules</li><li>Automated data collection from public sources and APIs</li><li>Workspace-based data management and export capabilities</li></ul> |
| **License** | Open source (GPL 3.0) |

| <h2>Maltego</h2> | |
|------------------|---|
| **Description** | Graph-based visualization and pivoting between entities using hundreds of built-in transforms, widely used in SOCMINT and CTI investigations. |
| **Access** | Web: [https://www.maltego.com](https://www.maltego.com) |
| **Key Features** | <ul><li>Interactive graph visualization for complex relationship analysis</li><li>Extensive library of transforms for domains, people, organizations, and infrastructure</li><li>Pivoting across multiple data sources from a single entity</li></ul> |
| **License** | Free for non-commercial use (Community Edition) |

| <h2>SpiderFoot</h2> | |
|---------------------|---|
| **Description** | Automated OSINT collection framework with 200+ modules for domains, IPs, and digital identities; integrates with services such as Shodan and Have I Been Pwned. |
| **Access** | Repository: [https://github.com/smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) |
| **Key Features** | <ul><li>Large modular scanning engine with extensive data source coverage</li><li>Automated correlation of results across multiple sources</li><li>Integration with external threat intelligence platforms and APIs</li></ul> |
| **License** | Open source (MIT) |

| <h2>theHarvester</h2> | |
|-----------------------|---|
| **Description** | Fast enumeration tool for emails, subdomains, hosts, and open ports using search engines and public APIs. |
| **Access** | Repository: [https://github.com/laramies/theHarvester](https://github.com/laramies/theHarvester) |
| **Key Features** | <ul><li>Rapid discovery of email addresses and subdomains</li><li>Support for multiple search engines and data sources</li><li>Lightweight and easy integration into reconnaissance workflows</li></ul> |
| **License** | Open source |

## General purpose

General-purpose OSINT tools provide flexible functionality that can be applied across multiple investigative domains. Rather than targeting a single data type, they act as frameworks or aggregation platforms that help structure, automate, or correlate information from diverse open sources.

| <h2>Lampyre OSINT Studio</h2> | |
|-------------------------------|---|
| **Description** | OSINT analysis platform for mixed datasets (financial, telecommunications, and social networks) using predefined query templates. |
| **Access** | Web: [https://lampyre.io](https://lampyre.io) |
| **Key Features** | <ul><li>Correlation of heterogeneous data sources in a single workspace</li><li>Predefined analytical templates for investigations</li><li>Advanced visualization and link analysis capabilities</li></ul> |
| **License** | Freemium |

| <h2>OSINT Combine</h2> | |
|------------------------|---|
| **Description** | AI-powered SaaS platform for prioritizing alerts and deduplicating findings from multiple OSINT and CTI sources. |
| **Access** | Web: [https://www.osintcombine.com](https://www.osintcombine.com) |
| **Key Features** | <ul><li>Automated correlation and deduplication of OSINT data</li><li>AI-assisted prioritization of alerts and findings</li><li>Centralized dashboard for multi-source intelligence analysis</li></ul> |
| **License** | Commercial (SaaS) |

| <h2>OSINT Framework</h2> | |
|--------------------------|---|
| **Description** | Web-based framework that organizes a large collection of OSINT tools and resources by category, helping analysts find relevant tools for different investigative tasks. It presents links in a structured, interactive layout. |
| **Access** | Web: [https://osintframework.com](https://osintframework.com) <br> Repository: [https://github.com/lockfale/osint-framework](https://github.com/lockfale/osint-framework) |
| **Key Features** | <ul><li>Comprehensive directory of free and paid OSINT tools</li><li>Categorized by data type and investigative use</li><li>Interactive map/tree structure for navigation</li><li>Links to third-party tools for deep dives</li></ul> |
| **License** | Open source (MIT license) |