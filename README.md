---
  status: 
   - work in progress
   - maturity level 1
---

in honour to the [ATC-Project](https://github.com/atc-project|ATC-Project) (Atomic-Threat-Coverage)

# obsidian_atc

## Summary 

Overview of the ATC-project and conversion to [obsidian](obsidian.md) and mapping to other frameworks and standards for data enrichment.

## What to expect
The files in this repo are only for drawing the graph and canvas in an Obsidian vault.

To get the complete documentation of [ATC Framework](https://github.com/atc-project/atomic-threat-coverage), just download the repository and copy the unzipped **Atomic_Threat_Coverage** directory into your Obsidian Vault.

The ATC Framework covers the following subjects:

- **Detection Rules** - Technical description of SIEM rules in a generic format.
- **Data Needed** - Description and example of an event needed for the Detection Rules.
- **Logging Policies** - Policies for the monitored systems.
- **Enrichments** - Helpful enrichment of the events to be logged.
- **Triggers** - Test of the Detection Rules based on the Mitre ATT&CK framework.
- **Response Playbooks** - is an Incident Response Plan, that is a complete list of procedures/tasks.
- **Response Stages** - The 6 phases to detect and manage a cybersecurity incident.
- **Mitigation Policies** - Policies to prevent a technique from being successfully executed.
- **Customers** - Information about the customer, company profile, industry, contact details.
- **Hardening Guides** - Guidelines for hardening systems to protect the C-I-A.
- **Mitigation Systems** - Technical tools to prevent a technique from being successfully executed.
- **Response Actions** - is a description of a specific course of action to be executed during Incident Response.
- **Use Cases** - Description of use cases that are detected by a SIEM.
- **Reporting** - Not yet defined in the ATC-Framework


Frameworks and Standards to enrich data:

- **ATC Framework** - The basic model of the template structure and design
- **Atomic-Red-Team Testing Libary** - is a library of tests for SIEM detection rules, mapped to the MITRE ATT&CK framework.
- **The CIS Benchmarks** - are community-developed secure configuration recommendations for hardening organizations' technologies against cyber attacks.
- **Standards and Certifications** - ISO27k, CIS Critical Controls, NIST, CE, TISAX, NIS
- **MaGMa** - (Management, Growth, Metrics & assessment) is a framework and tool for use case management and administration that helps organizations to operationalize their security monitoring strategy.
- **MITRE ATT&CK®** -  is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations.
- **MITRE D3FEND Matrix** - A knowledge graph of cybersecurity countermeasures
- **SIGMA Rule Repository** - Generic Signature Format for SIEM Systems, it is a generic and open signature format that allows to describe relevant log events in a straightforward manner.
- **DISARM** - is a framework designed for describing and understanding disinformation incidents. 

### Notice ###

Not all areas in the ATC are maintained as extensively as the Response_Action directory. 
The ATC has not yet included use case reporting and assessment.
For this I refer to other frameworks and standards as data sources for your own ideas for documentation.
