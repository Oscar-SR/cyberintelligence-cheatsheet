# SOCMINT

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

## Platforms

Currently, social media intelligence relies on a mosaic of environments, each with different dynamics and limitations. **X (formerly Twitter)** remains the fastest channel for capturing early signals and live conversations, although its APIs and access limits are more restrictive; it requires well-defined lists and search terms, along with immediate archiving.  

**TikTok** dominates short-form video consumption: investigations focus on hashtags, sounds, challenges, and pinned comments. Explicit geolocation is limited, and visual inference plays a central role.  

**Instagram/Facebook (Meta ecosystem)** combine Reels, posts, and public groups (topic-centric) and Marketplaces, which are useful for detecting fraud, account sales, and scams; interface changes are frequent.  

**LinkedIn** provides corporate SOCMINT (career paths, talent movements, job postings, and partnerships) with a strong emphasis on ToS compliance and minimizing personal data.  

**Reddit** hosts topic-based communities with active moderation; research relies on threads, wikis, and discussion timelines.  

**YouTube and livestreams** offer live content and automatic transcriptions valuable for search and summarization; live chats provide additional context.  

**Telegram** (public channels and supergroups) and **Discord** (servers with open channels) have become semi-public diffusion hubs; external indexing is partial, and strict OPSEC is required (observation without interaction).  

Meanwhile, federated networks like **Mastodon** or **Bluesky** expand the spectrum with distributed search and lower centralization and, in some geographic contexts, regional platforms (e.g., **VK, Weibo**) can be critical for coverage.

![Social media collection](../../assets/social-media-collection.png "Social media collection")