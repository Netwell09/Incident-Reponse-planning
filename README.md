# Incident Response Plan

[![Group: 14](https://img.shields.io/badge/Group-14-blue)](https://github.com/Group14/INFO6081-IRP)  
[![Course: INFO6081](https://img.shields.io/badge/Course-INFO--6081-green)](INFO6081-IRP-Group14.pdf)  
[![Submitted: 03 June 2023](https://img.shields.io/badge/Submitted-03%20June%202023-yellow)](INFO6081-IRP-Group14.pdf)

This repository hosts the Incident Response Plan (IRP) document for a fictional organization, Justice League Inc., developed as a group project for INFO6081. It includes the full PDF (INFO6081-IRP-Group14.pdf) with structured guidelines for managing cybersecurity incidents, drawing from NIST best practices. The content features definitions, processes, roles, and scenario-based action logs, demonstrated through tables, flow descriptions, and appendices. All elements were created ethically for educational purposes, assuming fictional structures, employees, and vendors to simulate real-world application without any actual deployment.

**Key Themes**: Incident detection/analysis, containment/eradication, recovery/post-activity; severity levels and SLAs; CSIRT roles; threat agents and types. Emphasizes traceability via JIRA, lessons learned for continuous improvement, and compliance with standards like NIST SP 800-61.

## Abstract

In today's threat landscape, effective incident response is crucial for minimizing damage to confidentiality, integrity, and availability. This IRP provides a comprehensive framework for Justice League Inc., covering cyber incidents like unauthorized access, ransomware, and physical breaches. It outlines a six-phase process (Detection to Post-Incident), roles for CSIRT and stakeholders, and SLAs for timely action. Appendices detail resolution logs for three scenarios, promoting proactive containment and evidence retention. The plan aligns with NIST guidelines, fostering a resilient IT environment through annual reviews, impact analysis, and tacit knowledge capture. Overall, it equips teams with tools for swift response, ethical handling, and prevention, preparing for roles in cybersecurity operations or compliance.

## Table of Contents

- [Document Overview](#document-overview)
  - [Cover and Assumptions](#cover-and-assumptions)
  - [Table of Contents and Version Control](#table-of-contents-and-version-control)
  - [Introduction](#introduction)
- [Terminology and Definitions](#terminology-and-definitions)
  - [Cyber Incidents](#cyber-incidents)
  - [Threat Agents](#threat-agents)
  - [Incident Severity and SLAs](#incident-severity-and-slas)
- [Roles and Responsibilities](#roles-and-responsibilities)
  - [CSIRT Team](#csirt-team)
  - [External Stakeholders](#external-stakeholders)
  - [Steering Committee](#steering-committee)
- [Incident Response Process](#incident-response-process)
  - [Detection](#detection)
  - [Analysis](#analysis)
  - [Containment](#containment)
  - [Eradication](#eradication)
  - [Recovery](#recovery)
  - [Post-Incident Activity](#post-incident-activity)
- [Appendices](#appendices)
  - [Appendix A: Unauthorized Access](#appendix-a-unauthorized-access)
  - [Appendix B: System Intrusion](#appendix-b-system-intrusion)
  - [Appendix C: Physical Security Breach](#appendix-c-physical-security-breach)
- [References](#references)
- [Key Concepts and Tools](#key-concepts-and-tools)
- [Best Practices Learned](#best-practices-learned)
- [Ethics and Challenges](#ethics-and-challenges)
- [Conclusion](#conclusion)
- [Authors](#authors)
- [License](#license)
- [How to View/Download](#how-to-viewdownload)

## Document Overview

This section summarizes the foundational elements of the IRP, including setup and high-level structure.

### Cover and Assumptions
**Objective and Explanation**: Establishes the document's context as a group project for INFO6081, dated 03 June 2023. Assumptions include fictional organization (Justice League Inc.), employee/vendor details, and scenario specifics to enable realistic elaboration.  
**Key Details**: 
- Group 14 members and IDs listed in a table.
- Ensures focus on educational simulation.
**Broader Insight**: Grounds the plan in hypothetical yet practical terms, aligning with academic integrity.

### Table of Contents and Version Control
**Objective and Explanation**: Outlines the document structure from Version Control to References. Version log tracks changes, creators, approvals by CSO, and dates (e.g., v1.0 on June 01 2023 by Shanjeevan).  
**Key Details**:
- Sections numbered with page references.
- Changes include additions to processes, appendices, and reviews.
**Broader Insight**: Promotes accountability and iterative improvement.

### Introduction
**Objective and Explanation**: Defines purpose (guided incident management to limit damage), authority (CSIRT custodianship under CSO), and review triggers (annual or post-high-severity). References industry practices.  
**Key Details**: Bullet points for review instances.   
**Broader Insight**: Sets tone for proactive security governance.

## Terminology and Definitions

Core terms for consistent understanding.

### Cyber Incidents 
**Objective and Explanation**: Defines incidents as threats to CIA triad, with 8 types (e.g., Unauthorized Access: external/insider attempts; Ransomware: data encryption for ransom).  
**Key Details**: Numbered table with descriptions.  
**Broader Insight**: Categorizes risks for targeted response.

### Threat Agents (page7.png)
**Objective and Explanation**: Lists agents like Hackers (unauthorized access), Insiders (abuse privileges), Criminals (physical theft), Natural Disasters (infrastructure damage).  
**Key Details**: Table with examples.  
**Broader Insight**: Highlights diverse origins beyond digital.

### Incident Severity and SLAs (page7.png, page8.png)
**Objective and Explanation**: Severity levels (High: severe data loss/image damage; Moderate: replaceable info; Low: minor disruption). SLAs for response (<10 min High) and resolution (<4 hrs High).  
**Key Details**: Tables for levels and times.   
**Broader Insight**: Prioritizes resources based on impact.

## Roles and Responsibilities

Details stakeholders for coordinated response.

### CSIRT Team
**Objective and Explanation**: Central team for end-to-end execution, with roles like IR Manager (Bruce Wayne: oversight), Forensic Analyst (Victor Stone: evidence custody).  
**Key Details**: Table with names, contacts, responsibilities.  
**Broader Insight**: Ensures specialized handling.

### External Stakeholders
**Objective and Explanation**: Contacts for support, e.g., Canadian Centre for Cyber Security (legal aid), Firewall Vendor (extended resources).  
**Key Details**: Table format.  
**Broader Insight**: Leverages external expertise.

### Steering Committee
**Objective and Explanation**: Advisory roles like CIO (IT alignment), CSO (cyber strategy).  
**Key Details**: Table with contacts.  
**Broader Insight**: Aligns with business objectives.

## Incident Response Process

Six-phase NIST-derived workflow.

### Detection
**Objective and Explanation**: Triggers via precursors (e.g., vulnerability scans) or indicators (e.g., malware alerts). Sources: alerts, logs, public info, people. Reporting via JIRA.  
**Key Details**: Lists, examples, table of sources.  
**Broader Insight**: Early warning critical.

### Analysis
**Objective and Explanation**: Verify incidents via docs, logs, research; update JIRA if confirmed.  
**Key Details**: Numbered actions (e.g., review baselines).   
**Broader Insight**: Confirms before escalation.

### Containment
**Objective and Explanation**: Isolate to limit damage; strategies by type (e.g., block phishing domains). Empowered: IR Manager primary.  
**Key Details**: Table of strategies.    
**Broader Insight**: Prevents spread.

### Eradication 
**Objective and Explanation**: Remove threats (e.g., malware scan, patching). Strategies by incident type.  
**Key Details**: Detailed table.  
**Broader Insight**: Addresses root causes.

### Recovery 
**Objective and Explanation**: Restore to BAU (e.g., backups, patches); monitor post-recovery. Phased for long timelines.  
**Key Details**: Numbered actions.    
**Broader Insight**: Ensures stability.

### Post-Incident Activity
**Objective and Explanation**: Lessons learned (meeting agenda), evidence retention (3 years).  
**Key Details**: Discussion points; retention for legal/policy.  
**Broader Insight**: Drives prevention.

## Appendices

Scenario-specific logs.

### Appendix A: Unauthorized Access
**Objective and Explanation**: Phase-wise actions (e.g., Detection: alert comms; Eradication: malware removal).  
**Key Details**: Tables per phase.    
**Broader Insight**: Template for access incidents.

### Appendix B: System Intrusion 
**Objective and Explanation**: Similar structure (e.g., Containment: segregate server).  
**Key Details**: Phase tables.  
**Broader Insight**: Handles data tampering.

### Appendix C: Physical Security Breach 
**Objective and Explanation**: Actions like log analysis, sanitizing software.  
**Key Details**: Tables.   
**Broader Insight**: Covers physical-digital overlap.

## References (page24.png)
**Objective and Explanation**: Cites NIST SP 800-61, Johansen's guides, Microsoft Assurance.  
**Broader Insight**: Credible foundations.

## Key Concepts and Tools

- **Processes**: NIST phases, JIRA tracking.
- **Definitions**: CIA threats, severity/SLAs.
- **Roles**: CSIRT, stakeholders.
- **Strategies**: Isolation, patching, monitoring.
- **Tools**: Antivirus, firewalls, logs (e.g., AD, network).

## Best Practices Learned

- **Documentation**: JIRA for traceability; lessons meetings.
- **Response**: Severity-based SLAs; phased recovery.
- **Prevention**: Annual reviews, evidence retention.
- **General**: Isolate sandboxes; consult publics like CVE.

## Ethics and Challenges

- **Challenges**: Decision timing in containment; evidence security; long recoveries.
- **Ethics**: Fictional scenarios only; focus on defense; retain for legal without misuse.
- **Overcoming**: Empower key roles; monitor post-recovery.

## Conclusion

This IRP bridges theory (NIST) with practice (scenarios), enhancing incident handling skills. Key takeaways: Structured phases minimize impact; collaboration key. Ideal for cybersecurity studies or CISSP prep. Expand to emerging threats like AI-driven attacks.

## Authors

- **Group 14**: Gihan Shamike Liyanage (1142109), Deepik Ravichander (1144695), Saiganesh Jeyapandi (1154547), Shanjeevan Mahesapalan (1126696)
- Semester: Summer 2023
- Contact: Update with emails if sharing.

## License

Academic work under MIT License - see [LICENSE](LICENSE) for details. Free to view/fork for learning; no commercial redistribution.

## How to View/Download

- **PDF**: Use Adobe Reader or online viewers.
- Star/watch for updates. Open issues for feedback.
- **Full File**: [Download PDF](INFO6081-IRP-Group14.pdf). Folder: root/. Last updated: October 2025.
