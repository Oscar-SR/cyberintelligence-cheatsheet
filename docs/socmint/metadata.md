# Metadata

Metadata is the information that is included in addition to the content of a digital file, such as identifiers, dates and times, language, the client/app used, relationships with other accounts, location, counters, etc.

## Common fields by entity

In SOCMINT, analysts usually work with different levels of information, or “fields by entity.” This allows them to systematically organize, analyze, and verify the data.

- **Account/profile level**: Common metadata includes the unique identifier, username and display name, biography, language and time zone, creation date, number of followers/following, and links declared in the bio. These fields allow analysts to assess account maturity, detect sudden changes in the audience, and locate potential sockpuppets (alternate accounts).

- **Post level**: Each post retains a `post_id`, creation timestamp (and, if applicable, edit timestamp), language, publishing source or client, hashtags and mentions, embedded links, as well as interaction counters (likes, shares, replies). These data allow the reconstruction of threads (via `conversation_id`/`thread_id`), detection of coordinated spikes, and comparison of narratives over time (timelines).

- **Multimedia level**: Images and videos provide resolution, duration, and sometimes EXIF metadata (date/time, device, orientation, and, if not stripped by the platform, GPS coordinates). While many platforms remove EXIF upon upload, the content itself provides visual clues (signage, license plates, terrain, shadows, weather) useful for geolocation and temporal verification.

- **Relationship level (social graph)**: Edges such as follow, reply, mention, quote/repost, and like describe the interaction structure. Analyzing the graph (communities, centrality, bridges) helps identify influential nodes, propagation paths, and potential coordinated campaigns.

## Taxonomy

| Category | Examples |
|------------------|------------------------|
| **Technical Metadata** | |
| | Unique identifiers: UUIDs for posts, comments, and users |
| | Timestamps: Creation, modification, deletion, interaction |
| | Device information: Type, operating system, application version |
| | Connection data: IP addresses (even behind VPNs on some platforms), ASNs, providers |
| | Advanced fingerprinting: Digital signatures of browsing behavior |
| | Session telemetry: Usage patterns, uptime, action sequences |
| **Geospatial Metadata** | |
| | Explicit geolocation: GPS coordinates voluntarily shared |
| | Implicit geolocation: Location inferred from network connection |
| | Mobility patterns: Temporal sequences of locations |
| | Proximity data: Bluetooth and NFC information from nearby devices |
| | Geographic references: Mentions of places in textual content |
| | EXIF metadata: Geographical information embedded in images and videos |
| **Relational Metadata** | |
| | Interaction graphs: Communication patterns between users |
| | Engagement metrics: Frequency, intensity, and nature of interactions |
| | Affiliation data: Membership in groups, communities, and lists |
| | Influence patterns: Information cascades and content diffusion |
| | Relational timeline: Temporal evolution of connections |
| | Messaging metadata: Information about private communications (when available) |
| **Behavioral Metadata** | |
| | Activity patterns: Posting schedules, frequency, and rhythms |
| | Attention data: Time spent on specific content |
| | Linguistic footprints: Stylometry and writing patterns |
| | Emotional metadata: Emoji usage patterns, reactions, and sentiment |
| | Navigation sequences: User paths through the platform |
| | Consumption metadata: Content preferences and viewing time |

## Use cases

- **Temporal and Geographical Verification**: Cross-checking timestamps with visible weather conditions and solar lighting, or with known public events; using location tags or visual inferences.

??? warning "Inaccurate geotags"

    Few users enable GPS; many locations are imprecise manual tags.

- **Narrative Reconstruction**: `conversation_id` and reply/mention relationships make it possible to trace the origin and amplification of a message.
- **Automation Detection**: Exact posting cadences, improbable time windows, repeated publishing clients, and template-like texts suggest automated behavior.
- **Lightweight Attribution**: Correlating aliases, recurring domains, and activity schedules with other profiles or open forums.
- **Impact Measurement**: Reading time-stamped counters (which vary over time) to assess reach and momentum.

??? warning "Noise and bias"

    Counters may be artificially influenced; some cameras/editors modify EXIF data, or device clocks may be incorrect.

## Recommendations

- Convert all dates to **UTC ISO 8601** and retain the platform’s original timestamp value.

- Preserve evidence by saving captures (HTML/PDF/images) and media hashes.

- Version edited posts and clarify whether counters reflect the time of collection.

- Tag language and detect character encodings to avoid search errors.

- Model data as a graph (nodes: accounts/posts/locations; edges: interactions) to facilitate community analysis.