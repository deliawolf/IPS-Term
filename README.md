# IPS-Term

A Cisco Intrusion Prevention System (IPS) is a system that performs deep analysis of network traffic, searching for signs of suspicious or malicious behavior. If it detects such behavior, the IPS can take protective action. An IPS can perform deep packet analysis and can complement a firewall by blocking attacks that would normally pass through a traditional firewall device. For example, an IPS can detect and block a wide range of malicious files and behavior, including botnet attacks, malware, and application abuse.

There are several methods of traffic inspection that are used in various IPSs:

1. Signature-based inspection: A signature-based IPS examines the packet headers or data payloads in network traffic and compares the data against a database of known attack signatures. The database must be continually updated to remain effective. A signature might be a sequence or a string of bytes in a certain context. Signature-based inspection is sometimes referred to as rule-based or pattern-matching inspection.

2. Anomaly-based inspection: Anomaly-based network IPS devices observe network traffic and act if a network event outside normal network behavior is detected.

There are three types of anomaly-based network IPSs:

1. Statistical anomaly detection (network behavior analysis): Observes network traffic over time and builds a statistical profile of normal traffic behavior based on communication patterns, traffic rate, mixture of protocols, and traffic volume. After a normal profile has been established, statistical anomaly detection systems detect or prevent activity that violates the normal profile.

2. Protocol verification: Observes network traffic and compares network, transport, and application layer protocols that are used inside network traffic to protocol standards. If a deviation from standards-based protocol behavior is detected (such as a malformed IP packet), the system can take appropriate action.

3. Policy-based inspection: A policy-based IPS analyzes network traffic and takes action if it detects a network event outside a configured traffic policy.

Modern IPSs (NGIPSs) combine the benefits of these inspection methods. They utilize technology such as traffic normalization and protocol decodes to counter evasive attacker techniques and to improve efficacy. They also utilize newer and more sophisticated technologies such as reputation, context awareness, event correlation, and cloud-based services to provide more robust and flexible protection.
