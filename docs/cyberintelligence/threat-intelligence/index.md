# Threat intelligence

A **cyberthreat** is understood as the possibility of carrying out malicious actions that affect the confidentiality, integrity, and/or availability of the resources of a computer system. Therefore, **threat intelligence** refers to the knowledge, skills, and experience-based information about cyberthreats, aimed at helping to mitigate potential attacks and harmful events that occur in cyberspace.

In the field of cybersecurity, threat intelligence plays a crucial role in anticipating potential attacks. Threat intelligence provides context, such as who is attacking us, what their motivation and capabilities are, and which indicators of compromise allow us to detect the attacks. This context helps organizations make faster, more informed security decisions and shift their approach from reactive to proactive in combating attacks.

## Types of threat intelligence

Regarding the types of threat intelligence that exist, various sources only distinguish between operational intelligence and strategic intelligence. Others also include tactical intelligence and even technical intelligence.

### Strategic intelligence

Strategic threat intelligence provides a broad view of an organization's threat landscape. It is designed to inform high-level decisions made by executives and other decision-makers within an organization, which means its content is usually less technical and is presented through reports or briefings.

The most common information sources for strategic threat intelligence include:

- Policy documents from nation-states or non-governmental organizations (NGOs).

- News from local and national media, industry- and topic-specific publications, or other subject-matter experts.

- Books, research reports, and other content produced by security organizations.

### Tactical intelligence

Tactical threat intelligence describes the tactics, techniques, and procedures (TTPs) of threat actors. It is intended to help defenders understand, in specific terms, how their organization could be attacked and the best ways to defend against or mitigate those attacks. It usually includes technical context and is used by personnel directly involved in defending an organization, such as system architects, administrators, and security staff.

Its sources include information about attack vectors, the tools and infrastructure that attackers are using, including details on which vulnerabilities are being targeted and which exploits attackers are leveraging, as well as the strategies and tools they may be using to evade or delay detection.

### Technical intelligence

Technical intelligence refers to detailed, actionable information about cyber threats, including specific indicators of compromise (IOCs), attack vectors, tools, tactics, techniques, and procedures (TTPs) used by threat actors. It is primarily used by security teams to detect, prevent, and respond to cyberattacks in real time. Technical intelligence often comes from threat data feeds, malware analysis, logs, and other technical sources that provide granular, operational-level insights.

### Operative intelligence

Operational intelligence is knowledge about cyberattacks, events, or campaigns. It provides specialized information that helps incident response teams understand the nature, intent, and timing of specific attacks.

Since it usually includes technical information —such as which attack vector is being used, which vulnerabilities are being exploited, or which command-and-control domains are being employed— this type of intelligence is also referred to as technical threat intelligence. A common source of technical information is threat data feeds, which typically focus on a single type of indicator, such as malware hashes or suspicious domains.

## Indicators

It is important to understand the difference between the two most important types of threat intelligence indicators; indicators of compromise and indicators of attack, when a company adopts and develops an intelligence program.

### Indicators of compromise

An indicator of compromise (IoC) is usually described in the forensic world as evidence that indicates a network’s security has been breached. Researchers typically collect this data after being notified of a suspected incident. Ideally, this information is gathered to create “smarter” tools that can detect and mitigate attacks.

The most common IoCs are, for example:

- Suspicious or known hostile domain or IP.

- Checksum of a suspicious or known hostile file (e.g., MD5, SHA256).

- Rules or signatures to detect suspicious or known data, such as antivirus and IDS signatures.

- Data related to the potential exploitation of a vulnerability.

- Tactics, Techniques, and Procedures (TTPs) associated with hostile events, such as an unauthorized instance of Mimikatz on an endpoint.

Indicators of compromise can be classified into three categories:

- **Atomic**: Those that cannot be divided into smaller parts and retain their meaning in the context of an intrusion (e.g., IP address, URL, email address, registry key, file path, vulnerability identifiers).

- **Computed**: Those derived from data related to an incident (e.g., regular expressions, file hash values).

- **Behavioral**: Those that result from grouping atomic and computed indicators, subject to qualification by quantity and logical combinatorial possibilities (e.g., the intruder initially uses a backdoor that employs [port], generating network traffic matching [regular expression] and [connection frequency] to [IP address/URL], with this backdoor being replaced, once the connection with the C2 server is established, by another executable with hash value [MD5 hash]).

The three most commonly shared indicators (hashes, IP addresses, and domain names) are also the easiest to evade, which limits their usefulness. For an attacker, it is trivial to modify a hash—from compilation to execution—change an IP address used as a C2 or exfiltration server, or alter domain names with minimal effort. Thus, a threat actor with basic capabilities can evade detection based on these types of indicators. However, when it comes to behavioral indicators with TTPs, modifying them is more difficult for an actor. Therefore, if we can detect these modus operandi, our success in identifying compromises increases.

So, if atomic and computed indicators are not the most useful, why are they the most commonly used and shared? The answer is simple: they can be automatically ingested into security tools, providing immediate results. Identifying TTPs, in many cases, requires establishing relationships between security events; these relationships are often temporal but can also be tied to dependencies between activities, for example.

In summary, we share the intelligence that is easiest to use, but not the best. To detect advanced threat activities, we need to share the most valuable intelligence, and to achieve this, that intelligence must be automatically processable across all relevant environments, ideally following a standard.

### Indicators of attack

Indicators of attack (IoA) focus on detecting the intent of what an attacker is trying to achieve, regardless of the malware or exploit used in an attack. Like AV signatures, an IOC-based detection approach cannot detect the growing threats of malware-less intrusions and zero-day exploits. As a result, next-generation security solutions are moving toward an IoA-based approach.

Indicators of attack focus more on the *why* and the intent of an actor. In many ways, they represent a more strategic view of an actor’s or group’s techniques, tactics, and procedures. When properly placed within a more mature intelligence program, IoAs can genuinely identify proactive strategies for detecting and defending against new, unknown threats.