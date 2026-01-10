# SOCMINT

## Definition

Social Media Intelligence (SOCMINT) is the branch of cyber intelligence dedicated to locating, collecting, processing, and analyzing publicly generated information from social platforms and digital communities (social networks, forums, blogs, public messaging channels, and review sites) with the goal of producing actionable knowledge that supports operational, tactical, or strategic decision-making.

SOCMINT does not involve accessing private information or bypassing platform security mechanisms. It operates on publicly available content and metadata (without authentication or with legitimate access) and adheres to principles of legality, proportionality, and respect for privacy. Unlike general OSINT, SOCMINT focuses specifically on the digital social ecosystem as a primary source of intelligence.

## Scope

- **Published content**: Texts (posts, comments, titles, descriptions), images, videos, public live streams, and stories.

- **Explicit and derived metadata**: Dates and times, geolocation, language, client/application used, embedded links, tags/hashtags, mentions. When legitimately accessible, this also includes image EXIF data and technical clues that assist verification.

- **Interaction graphs and dynamics**: Followers/following relationships, mentions, replies, reposts, groups, and lists; detection of communities, influential nodes, and information flows.

- **Behavioral signals**: Posting cadence and schedules, repetition of templates, account synchrony, possible indicators of automation or coordination.

- **Multi-source context**: Correlation with news, official open data, internet technical data (WHOIS/DNS/certificates), satellite imagery, or open sensors to strengthen verification.

## Use cases

- **Disinformation detection**: Identifying disinformation campaigns and emerging narratives; spotting orchestrated accounts or bots.

- **Incident analysis and fact-checking**: Verifying events through geolocation, timelines of posts, and cross-referencing with other sources.

- **Risk assessment and reputation monitoring**: Monitoring organizations, sectors, or critical infrastructure for potential threats and reputational issues.

- **Community profiling**: Non-intrusive mapping of communities to understand actors, affinities, and influence vectors.

- **Cyber threat investigation support**: Linking aliases, domains, and activity patterns to known campaigns for threat analysis.

## Common fields by entity

In SOCMINT, analysts usually work with different levels of information, or “fields by entity.” This allows them to systematically organize, analyze, and verify the data.

- **Account/profile level**: Common metadata includes the unique identifier, username and display name, biography, language and time zone, creation date, number of followers/following, and links declared in the bio. These fields allow analysts to assess account maturity, detect sudden changes in the audience, and locate potential sockpuppets (alternate accounts).

- **Post level**: Each post retains a post_id, creation timestamp (and, if applicable, edit timestamp), language, publishing source or client, hashtags and mentions, embedded links, as well as interaction counters (likes, shares, replies). These data allow the reconstruction of threads (via conversation/thread_id), detection of coordinated spikes, and comparison of narratives over time (timelines).

- **Multimedia level**: Images and videos provide resolution, duration, and sometimes EXIF metadata (date/time, device, orientation, and, if not stripped by the platform, GPS coordinates). While many platforms remove EXIF upon upload, the content itself provides visual clues (signage, license plates, terrain, shadows, weather) useful for geolocation and temporal verification.

- **Relationship level (social graph)**: Edges such as follow, reply, mention, quote/repost, and like describe the interaction structure. Analyzing the graph (communities, centrality, bridges) helps identify influential nodes, propagation paths, and potential coordinated campaigns.