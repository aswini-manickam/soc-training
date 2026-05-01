[README_ soc training.md](https://github.com/user-attachments/files/27274635/README_.soc.training.md)
#  SOC Analyst Training Curriculum - Practical Guide for Security Operations Professionals

> A structured, hands-on SOC training curriculum built from the ground up - continuously updated with practical labs, real-world scenarios, and mapped learning paths to help SOC professionals and the wider cybersecurity community develop job-ready analyst skills.

[![Domain](https://img.shields.io/badge/Domain-SOC%20%7C%20Threat%20Detection%20%7C%20DFIR-red?style=flat)]()
[![Frameworks](https://img.shields.io/badge/Mapped-MITRE%20ATT%26CK%20%7C%20Essential%20Eight-orange?style=flat)]()
[![Certifications](https://img.shields.io/badge/Aligned-Cisco%20CyberOps%20%7C%20ISC2%20CC-blue?style=flat)]()
[![Status](https://img.shields.io/badge/Status-Continuously%20Updated-brightgreen?style=flat)]()
[![Audience](https://img.shields.io/badge/Audience-Beginner%20to%20Intermediate-grey?style=flat)]()

---

##  About This Curriculum

This repository is a **practical, framework-aligned SOC training curriculum** designed for beginner and intermediate security analysts who want structured, hands-on learning - not just theory.

It was built from scratch based on direct experience designing and delivering SOC training, and is continuously updated to reflect current threats, tools, and industry expectations. Every module includes clear learning outcomes, a hands-on lab component, and mapping to professional certification standards so learners can build credentialled, transferable skills.

**Who this is for:**
- Aspiring SOC analysts looking for a structured self-study path
- Junior analysts wanting to fill gaps in their practical knowledge
- Cybersecurity educators designing lab-based training programmes
- Career changers transitioning into security operations

---

##  Learning Path Overview

```
BEGINNER                    INTERMEDIATE                ADVANCED-READY
─────────────────────────────────────────────────────────────────────▶
  Module 1           Module 3 & 4         Module 5          Module 6 & 7
SOC Fundamentals  →  SIEM Operations  →  Threat Scenarios  →  DFIR & Vuln Mgmt
                      Log Analysis         Simulations          Assessment
                         │
                    Module 2
                 Threat Intelligence
                  MITRE ATT&CK
```

---

## 🗂️ Curriculum Modules

### Module 1 - Security Operations Fundamentals

**Who this is for:** Complete beginners entering SOC for the first time

**What you will learn:**
- SOC structure - tier model, analyst roles, escalation workflows
- Alert triage methodology and decision-making frameworks
- Common log formats across Windows, Linux, and network devices
- How to read and interpret security events without prior experience

**Hands-on lab:**
- Log triage exercises using pre-built SIEM dashboards
- Simulated alert queue - classify, prioritise, and escalate across mixed scenarios

**Certification alignment:** ISC2 CC Domain 4 · Cisco CyberOps - Security Monitoring

---

### Module 2 - Threat Intelligence & MITRE ATT&CK

**Who this is for:** Analysts who can triage alerts but want to understand *why* attacks happen

**What you will learn:**
- How to read and apply the MITRE ATT&CK framework in real investigations
- The difference between tactical, operational, and strategic threat intelligence
- How to enrich SIEM alerts with threat intelligence context
- Mapping observed attacker behaviour to ATT&CK techniques and tactics

**Hands-on lab:**
- ATT&CK Navigator exercises - map simulated attack telemetry to techniques
- Threat intelligence enrichment workflow using OSINT sources
- Build a threat profile for a simulated adversary

**Certification alignment:** Cisco CyberOps - Threat Intelligence · ISC2 CC Domain 1

---

### Module 3 — SIEM Operations & Log Analysis

**Who this is for:** Analysts ready to move beyond alert reading into active detection

**What you will learn:**
- How to query Splunk, Security Onion, and Kibana for threat hunting and detection
- Building correlation rules and dashboards for real-time monitoring
- Applying CIM (Common Information Model) for log normalisation
- Recognising attacker patterns in log data across diverse source types

**Hands-on lab:**
- Splunk SPL query exercises - from basic field extraction to multi-source correlation
- Security Onion alert review and Zeek/Suricata log analysis
- Build an operational Kibana dashboard for network and endpoint telemetry

**Tools:** `Splunk` `Security Onion` `Kibana` `Splunk CIM` `Universal Forwarders`

**Certification alignment:** Cisco CyberOps - Security Monitoring (largest exam domain)

---

### Module 4 - Incident Triage & Escalation

**Who this is for:** Analysts who want to work faster and more confidently under pressure

**What you will learn:**
- Structured triage methodology - how to prioritise security alerts consistently
- Distinguishing true positives, false positives, and benign anomalies
- IRP (Incident Response Plan) protocols - documentation and escalation standards
- How to write a clear, accurate incident ticket

**Hands-on lab:**
- Simulated alert queue with mixed true/false positives - triage under time pressure
- Incident documentation exercise using structured IR templates
- Escalation decision-making scenarios mapped to severity tiers

**Certification alignment:** ISC2 CC Domain 2 · Cisco CyberOps - Incident Response

---

### Module 5 - Threat Scenario Simulations

**Who this is for:** Analysts ready to investigate real attack patterns end-to-end

**What you will learn:**
- Identifying indicators of compromise (IOCs) across phishing, malware, and intrusion scenarios
- Tracing attacker behaviour across the kill chain using SIEM and endpoint telemetry
- Applying countermeasures and documenting response actions

**Three core simulation scenarios:**

| Scenario | Attack Type | What You Detect |
|----------|-------------|----------------|
| **Phishing Campaign** | Credential harvesting via malicious email | Email gateway logs · proxy logs · auth anomalies |
| **Malware Infection** | Endpoint compromise and C2 callback | EDR telemetry · outbound connection anomalies |
| **Network Intrusion** | Lateral movement post-initial access | Network flow analysis · Zeek logs · SIEM correlation |

**Tools:** `Security Onion` `Splunk` `Wireshark` `Sandboxed lab environment`

---

### Module 6 - Digital Forensics & Incident Investigation

**Who this is for:** Analysts moving into Tier 2/3 or DFIR-focused roles

**What you will learn:**
- Structured DFIR methodology - scoping through reporting
- Reconstructing attacker timelines from log and forensic artefact analysis
- Writing professional incident investigation reports for technical and non-technical audiences
- Chain-of-custody documentation standards

**Hands-on lab:**
- File system and memory artefact analysis
- Log correlation to build a complete attack timeline
- Structured findings report - written to professional DFIR standards

**Certification alignment:** ISC2 CC Domain 2 · Cisco CyberOps - Digital Forensics

---

### Module 7 - Vulnerability Assessment & Essential Eight

**Who this is for:** Analysts expanding into vulnerability management and compliance

**What you will learn:**
- How to conduct a structured vulnerability assessment using Nessus and OpenVAS
- CVE triage - severity scoring (CVSS), business impact weighting, and prioritisation
- Mapping remediation actions to the Australian Essential Eight maturity controls
- Communicating findings in structured assessment reports

**Hands-on lab:**
- Nessus credentialed scan → findings triage exercise
- Essential Eight control mapping worksheet
- Windows Server hardening checklist - applying controls in sequence

**Tools:** `Nessus` `OpenVAS` `Windows Server` `Group Policy`

---

### Module 8 - Endpoint Security & Hardening

**Who this is for:** Analysts who want to understand how hardened environments reduce alert volume

**What you will learn:**
- Least-privilege principles applied across Active Directory environments
- Group Policy-based endpoint hardening using CIS benchmark baselines
- Monitoring endpoint security posture and detecting configuration drift
- How hardening decisions directly affect SIEM detection coverage

**Hands-on lab:**
- Active Directory account audit and privilege review exercise
- GPO hardening exercise - applying CIS benchmark controls step by step
- Validate hardening impact through SIEM log comparison (before/after)

---

##  Lab Design Philosophy

Every lab in this curriculum is built on four principles:

**1. Realism over abstraction**
Labs are based on documented real-world attack patterns mapped to MITRE ATT&CK - not synthetic textbook scenarios. The goal is for every lab to feel like something you might encounter on your first week on the job.

**2. Graduated difficulty**
Each module scales from guided walkthrough → independent investigation → challenge mode (time-pressured, minimal guidance). This mirrors the progression you experience moving from Tier 1 to Tier 2 in a real SOC.

**3. Framework-anchored outcomes**
Every lab maps to at least one professional certification domain (Cisco CyberOps or ISC2 CC) and one industry framework (MITRE ATT&CK or Essential Eight). Skills built here are directly transferable and credentialled.

**4. Dual-format delivery**
All materials are structured for both **instructor-led** and **self-paced** learning — so you can work through this alone, in a study group, or as part of a facilitated training programme.

---

##  Recommended Lab Environment

You can run all labs locally using free and open-source tools:

```
┌─────────────────────────────────────────────────┐
│           Recommended Lab Stack                  │
├──────────────────┬──────────────────────────────┤
│  SIEM / NSM      │  Splunk Free · Security Onion │
│                  │  Kibana (ELK Stack)            │
├──────────────────┼──────────────────────────────┤
│  Network         │  Wireshark · Nmap · Zeek       │
│  Analysis        │  Suricata                      │
├──────────────────┼──────────────────────────────┤
│  Endpoint        │  Windows Server (Eval)         │
│                  │  Active Directory · GPO        │
├──────────────────┼──────────────────────────────┤
│  Vuln Scanning   │  Nessus Essentials (Free)      │
│                  │  OpenVAS                        │
├──────────────────┼──────────────────────────────┤
│  Virtualisation  │  VirtualBox · VMware Workstation│
│                  │  Player (Free)                 │
└──────────────────┴──────────────────────────────┘
```

> All tools listed have free tiers suitable for lab use. Links and setup guides will be added to each module folder.

---

##  Certification Alignment Map

| Module | MITRE ATT&CK | Essential Eight | Cisco CyberOps | ISC2 CC |
|--------|-------------|----------------|----------------|---------|
| 1 — SOC Fundamentals | - | - | Security Monitoring | Domain 4 |
| 2 — Threat Intelligence |  Full mapping | - | Threat Intelligence | Domain 1 |
| 3 — SIEM & Log Analysis |  Detection coverage | - | Security Monitoring | Domain 4 |
| 4 — Incident Triage |  Kill chain | - | Incident Response | Domain 2 |
| 5 — Threat Simulations |  Tactic/Technique | - | All domains | Domain 2 |
| 6 — DFIR |  Post-exploitation | - | Digital Forensics | Domain 2 |
| 7 — Vuln Assessment | - |  All 8 controls |  | Domain 5 |
| 8 — Endpoint Hardening |  |  Controls 1-5 | Endpoint Security | Domain 4 |

---

## 📁 Repository Structure

```
soc-training-curriculum/
│
├── README.md                        # This file - curriculum overview
│
├── module-01-soc-fundamentals/
│   ├── learning-outcomes.md
│   ├── lab-guide.md
│   └── resources.md
│
├── module-02-threat-intelligence/
│   ├── learning-outcomes.md
│   ├── lab-guide.md
│   ├── attack-navigator-exercises/
│   └── resources.md
│
├── module-03-siem-log-analysis/
│   ├── learning-outcomes.md
│   ├── splunk-spl-exercises.md
│   ├── security-onion-lab.md
│   └── resources.md
│
├── module-04-incident-triage/
│   ├── learning-outcomes.md
│   ├── lab-guide.md
│   ├── templates/
│   │   └── incident-report-template.md
│   └── resources.md
│
├── module-05-threat-simulations/
│   ├── scenario-01-phishing/
│   ├── scenario-02-malware/
│   ├── scenario-03-network-intrusion/
│   └── resources.md
│
├── module-06-dfir/
│   ├── learning-outcomes.md
│   ├── lab-guide.md
│   ├── templates/
│   │   └── investigation-report-template.md
│   └── resources.md
│
├── module-07-vulnerability-assessment/
│   ├── learning-outcomes.md
│   ├── nessus-lab-guide.md
│   ├── essential-eight-mapping.md
│   └── resources.md
│
└── module-08-endpoint-hardening/
    ├── learning-outcomes.md
    ├── lab-guide.md
    ├── cis-benchmark-checklist.md
    └── resources.md
```

---

## 🤝 Contributing

This curriculum is a living resource. Contributions, corrections, and additions are welcome.

If you spot something outdated, want to suggest a lab scenario, or have a tool recommendation - open an issue or submit a pull request.

---

## 📚 References & Frameworks

- [MITRE ATT&CK Framework](https://attack.mitre.org/)
- [Australian Essential Eight](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/essential-eight)
- [Cisco CyberOps Associate Exam Topics](https://www.cisco.com/c/en/us/training-events/training-certifications/exams/current-list/cyberops-associate-200-201.html)
- [ISC2 CC Exam Outline](https://www.isc2.org/certifications/cc)
- [Splunk Documentation](https://docs.splunk.com/)
- [Security Onion Documentation](https://docs.securityonion.net/)
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

## 👤 Author

**Aswini Manickam**
Cybersecurity Practitioner & Educator
-  [LinkedIn](https://www.linkedin.com/in/aswini-manickam/)
-  [GitHub](https://github.com/aswini-manickam)

---

*Part of the [Cybersecurity Portfolio]
