# Tools

## Web archives

Web archives preserve historical versions of websites and online content, allowing analysts to examine how information has changed over time. They are particularly valuable for attribution, timeline reconstruction, and recovering deleted or altered content that is no longer available on the live web.

| <h2>archive.ph</h2> | |
|--------------------|---|
| **Description** | Web archiving service that captures snapshots of social media web pages, preserving content even if the original is removed. |
| **Access** | Web: [https://archive.ph](https://archive.ph) |
| **Key Features** | <ul><li>On-demand page snapshots</li><li>Permanent links to archived pages</li><li>Content preservation for deleted/modified social media</li></ul> |
| **License** | Free |

## Media monitoring

Media monitoring tools aggregate and analyze digital news sources at local, national, and global levels. They enable continuous tracking of events, narratives, and trends, and support large-scale analysis of media coverage, making them valuable for situational awareness and strategic intelligence.

| <h2>BRAND24</h2> | |
|------------------|---|
| **Description** | Social listening and online brand reputation management tool that tracks mentions across platforms. |
| **Access** | Web: [https://brand24.com](https://brand24.com) |
| **Key Features** | <ul><li>Real-time social mentions tracking</li><li>Sentiment analysis</li><li>Influencer identification</li></ul> |
| **License** | Commercial (SaaS) |

## Sentiment analysis

| <h2>BERT / RoBERTa</h2> | |
|-------------------------|---|
| **Description** | Advanced transformer-based NLP models used for high-accuracy sentiment analysis and contextual understanding of social media content. |
| **Access** | Web: [https://pypi.org/project/fast-bert/](https://pypi.org/project/fast-bert/) |
| **Key Features** | <ul><li>Deep contextual understanding</li><li>High sentiment classification accuracy</li><li>Handles sarcasm, negation, and complex language</li><li>Can be fine-tuned for SOCMINT-specific domains</li></ul> |
| **License** | Open Source |


| <h2>Flair</h2> | |
|----------------|---|
| **Description** | NLP framework that provides efficient sentiment analysis using contextual string embeddings, suitable for real-time social media monitoring. |
| **Access** | Repository: [https://github.com/flairNLP/flair](https://github.com/flairNLP/flair) |
| **Key Features** | <ul><li>Good balance between accuracy and performance</li><li>Fast inference compared to transformers</li><li>Easy integration into SOCMINT pipelines</li><li>Supports multiple languages</li></ul> |
| **License** | Open Source (MIT License) |


| <h2>VADER</h2> | |
|----------------|---|
| **Description** | Lexicon and rule-based sentiment analysis tool optimized for social media language and short informal texts. |
| **Access** | Repository: [https://github.com/cjhutto/vaderSentiment](https://github.com/cjhutto/vaderSentiment) |
| **Key Features** | <ul><li>Optimized for social media text</li><li>Handles emojis, slang, and punctuation</li><li>Very fast processing speed</li><li>No training required</li></ul> |
| **License** | Open Source (MIT License) |


| <h2>TextBlob</h2> | |
|-------------------|---|
| **Description** | Simple NLP library providing basic sentiment analysis, mainly used for rapid prototyping and exploratory analysis. |
| **Access** | Web: [https://textblob.readthedocs.io/en/dev/](https://textblob.readthedocs.io/en/dev/) <br> Repository: [https://github.com/sloria/TextBlob](https://github.com/sloria/TextBlob) |
| **Key Features** | <ul><li>Very easy to use</li><li>Lightweight and fast</li><li>Good for educational or prototype SOCMINT projects</li></ul> |
| **License** | Open Source (MIT License) |

## Metadata analysis

| <h2>ExifTool</h2> | |
|------------------|---|
| **Description** | De facto standard for reading, writing, and normalizing EXIF, XMP, and IPTC metadata across a wide range of file formats. |
| **Access** | Website: [https://exiftool.org/](https://exiftool.org/) <br> Repository: [https://github.com/exiftool/exiftool](https://github.com/exiftool/exiftool) |
| **Key Features** | <ul><li>Supports hundreds of file formats</li><li>Read, write, and delete metadata</li><li>Highly scriptable and automation-friendly</li><li>Widely used in digital forensics and OSINT</li></ul> |
| **License** | Open Source (GPL 3.0) |

| <h2>MediaInfo</h2> | |
|------------------|---|
| **Description** | Technical analysis tool for audio and video files, providing detailed information about codecs, bitrates, containers, and timestamps. |
| **Access** | Website: [https://mediaarea.net/en/MediaInfo](https://mediaarea.net/en/MediaInfo) <br> Repository: [https://github.com/MediaArea/MediaInfo](https://github.com/MediaArea/MediaInfo) |
| **Key Features** | <ul><li>Detailed codec and container inspection</li><li>Supports audio, video, and subtitle streams</li><li>CLI and GUI versions available</li><li>Commonly used in media forensics</li></ul> |
| **License** | Open Source (BSD 2-Clause License) |

| <h2>FFmpeg / FFprobe</h2> | |
|------------------|---|
| **Description** | Comprehensive multimedia framework for inspecting, processing, and extracting metadata, keyframes, and media streams. |
| **Access** | Website: [https://ffmpeg.org/](https://ffmpeg.org/) <br> Repository: [https://git.ffmpeg.org/ffmpeg.git](https://git.ffmpeg.org/ffmpeg.git) |
| **Key Features** | <ul><li>Extract and inspect detailed media metadata</li><li>Keyframe and stream analysis with FFprobe</li><li>Supports virtually all audio/video formats</li><li>Powerful CLI for forensic workflows</li></ul> |
| **License** | Open Source (LGPL and GPL) |

| <h2>MAT2</h2> | |
|---------------------------------------------|---|
| **Description** | Tool designed to detect and remove metadata from files before sharing, helping to prevent unintentional information disclosure. |
| **Access** | Repository: [https://github.com/tpet/mat2](https://github.com/tpet/mat2) |
| **Key Features** | <ul><li>Removes metadata from images, documents, audio, and video</li><li>Focus on privacy and operational security</li><li>CLI and GUI versions available</li><li>Used by journalists and activists</li></ul> |
| **License** | Open Source (LGPL 3.0) |

| <h2>XnView MP</h2> | |
|------------------|---|
| **Description** | Cross-platform media viewer with basic EXIF/IPTC metadata viewing and editing capabilities. |
| **Access** | Website: [https://www.xnview.com/en/xnviewmp/](https://www.xnview.com/en/xnviewmp/) |
| **Key Features** | <ul><li>View and edit basic EXIF/IPTC metadata</li><li>Supports a large number of image formats</li><li>Batch processing capabilities</li><li>User-friendly graphical interface</li></ul> |
| **License** | Freemium |