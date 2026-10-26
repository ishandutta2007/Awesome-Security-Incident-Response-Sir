# Awesome-Security-Incident-Response-Sir

# Top Security Incident Response (SIR) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Incident Triage, Case Management & Automated Response Orchestration*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Security Incident Response (SIR)**. These tools enable security teams to detect, investigate, contain, and remediate security incidents through structured case management, automated playbooks, and orchestration across SIEM, EDR, threat intelligence, and ticketing systems.

**Examples** include ServiceNow Security Incident Response, Splunk Phantom (SOAR), Palo Alto Networks Cortex XSOAR, IBM Security QRadar SOAR, Rapid7 InsightConnect, Swimlane, Microsoft Sentinel, D3 Security SOAR, Siemplify (Google Chronicle SOAR), and Tines (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted incident response platforms, case management, and SOAR automation—ideal for SOC teams, CSIRTs, and organizations building sovereign incident response infrastructure without per-case or per-analyst licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Security Incident Response](https://www.servicenow.com/)**  
  Enterprise SIR on the Now Platform with SIEM integration (CrowdStrike Next-Gen SIEM, Splunk ES, Azure Sentinel), relationship graph for visualizing incident context, bulk closure with predefined codes, Process Mining for bottleneck analysis, on-call scheduling, and observables sharing with TISC including TLP and confidence metadata .

- **[Splunk Phantom (SOAR)](https://www.splunk.com/)**  
  SOAR platform tightly integrated with Splunk SIEM; supports visual and Python-based playbook automation, case management, and 1,000+ app integrations for orchestrating response across security tools .

- **[Palo Alto Networks Cortex XSOAR](https://www.paloaltonetworks.com/)**  
  Market-leading SOAR with 1,000+ third-party integrations, visual playbook canvas with automatic component installation, and use-case-first automation approach; core to Cortex XSIAM, XDR, and Cloud running on the new Cortex platform .

- **[IBM Security QRadar SOAR](https://www.ibm.com/)**  
  SOAR platform for incident response orchestration, case management, and automation playbooks, integrated with QRadar SIEM and the broader IBM Security portfolio.

- **[Rapid7 InsightConnect](https://www.rapid7.com/)**  
  Security automation and orchestration platform with pre-built workflows and integrations for accelerating incident response across InsightIDR and third-party tools.

- **[Swimlane](https://swimlane.com/)**  
  Low-code security automation platform with drag-and-drop playbook builder, case management, and Turbine AI for automated triage and response.

- **[Microsoft Sentinel](https://learn.microsoft.com/azure/sentinel/)**  
  Cloud-native SIEM and SOAR with automation rules, playbooks via Logic Apps, and unified incident management; transitioning fully to the Microsoft Defender portal by March 2027.

- **[D3 Security SOAR](https://d3security.com/)**  
  SOAR platform with visual playbook builder, case management, and threat intelligence enrichment for SOC teams.

- **[Siemplify (Google Chronicle SOAR)](https://cloud.google.com/chronicle)**  
  SOAR platform (acquired by Google Cloud) with visual playbooks, case management, and integration with Chronicle SIEM and Google Cloud security tools.

- **[Tines](https://www.tines.com/)**  
  No-code automation platform for security and IT workflows; built by former SOC practitioners with a focus on simplicity and fast time-to-value for repetitive tasks and incident response.

## Open-Source GitHub Projects

- **[TheHive](https://github.com/TheHive-Project/TheHive)**  
  Leading open-source security incident response platform (AGPL-3.0) designed for SOCs, CSIRTs, and CERTs; provides case management, observable analysis, task tracking, and integration with MISP for threat intelligence enrichment and Cortex for automated analyzers .

- **[MozDef](https://github.com/mozilla/MozDef)**  
  Open-source platform (Mozilla) that automates the security incident handling process and facilitates real-time activities of incident handlers; designed for SOC operations with event correlation and response workflows .

- **[IRIS](https://github.com/dfir-iris/iris-web)**  
  Web collaborative platform for incident response analysts (DFIR-IRIS); enables sharing investigations at a technical level with case management, IOC tracking, and timeline analysis .

- **[Shuffle](https://github.com/Shuffle/Shuffle)**  
  Open-source SOAR platform (AGPL-3.0) for automating security workflows; provides a visual workflow editor, 1,000+ app integrations, and orchestration across SIEM, EDR, and ticketing tools.

- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Open-source SIEM/XDR platform (GPL-2.0) with active response capabilities; can trigger automated actions on endpoints in response to detected threats, serving as both detection and response layer.

- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  
  Open-source endpoint visibility and digital forensics platform (Apache 2.0) for hunting threats and investigating incidents at scale; uses VQL for collecting endpoint telemetry and detecting malicious activity .

- **[GRR Rapid Response](https://github.com/google/grr)**  
  Incident response framework from Google focused on remote live forensics; includes a Python agent on target systems and a server infrastructure for managing investigations at fleet scale .

- **[Fleetdm](https://github.com/fleetdm/fleet)**  
  Host monitoring platform built on osquery (MIT) tailored for security teams; provides visibility across devices with minimal overhead and supports incident response workflows .

- **[Matano](https://github.com/matanolabs/matano)**  
  Open-source serverless security lake platform on AWS (Apache 2.0) for ingesting, storing, and analyzing security data in an Apache Iceberg data lake; supports real-time Python detections as code .

- **[XCLOAK Security Suite](https://github.com/The-Abhishek1/XCLOAK-SECURITY-SUITE)**  
  Open-source enterprise SOC platform (AGPL-3.0) combining SIEM, SOAR, EDR, and more; SOAR features include playbooks with human-approval gates, AI recommender (Ollama/Claude) for MITRE-context suggestions, FIM auto-quarantine with approval queue, and stale task expiry for destructive actions .

### Additional Strong Open-Source Options

- **Cortex** — Open-source observable analysis and active response engine from TheHive Project; runs analyzers (VirusTotal, AbuseIPDB, etc.) and responders for automated enrichment.
- **MISP** — Open-source threat intelligence sharing platform (AGPL-3.0) for IOC storage and correlation; integrates with TheHive and SIEM tools for intelligence-driven incident response.
- **Sigma** — Open standard for SIEM-agnostic detection rules; portable detection logic across Splunk, Elastic, QRadar, and other backends.
- **SOC Multi-tool** — Browser extension that streamlines investigations for security professionals with quick lookups across multiple intelligence sources .

**Frameworks for building custom systems**: Combine **TheHive** for case management and investigation workflow, **Shuffle** for SOAR automation, **MISP** for threat intelligence enrichment, **Wazuh** for detection with active response, and **Velociraptor** for endpoint forensics in a fully self-hosted security incident response stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SIR platforms handling incident data must comply with applicable regulations and organizational security policies; incident records may contain sensitive information requiring access controls and retention policies.
- Self-hosted open-source solutions require significant operational investment in playbook development, integration maintenance, and 24/7 SOC coverage.
- Verify license terms for commercial use; TheHive uses AGPL-3.0, Shuffle uses AGPL-3.0, Wazuh uses GPL-2.0, and Velociraptor uses Apache-2.0.

---

**Made for SOC analysts, incident responders, CSIRT teams, and security operations managers.**  
Let's make security incident response more open, automated, and effective.
