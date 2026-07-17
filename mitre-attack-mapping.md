# ⚔️ MITRE ATT&CK Mapping

This document maps investigation scenarios to relevant MITRE ATT&CK techniques.

---

## Incident Report 001 - Brute Force Activity

### Technique

- T1110 - Brute Force

### Description

Adversaries may attempt to gain access by repeatedly trying multiple passwords against one or more accounts.

### Detection Opportunities

- Multiple failed login attempts
- Authentication anomalies
- Repeated source IP addresses

---

## Incident Report 002 - Phishing Investigation

### Technique

- T1566 - Phishing

### Description

Adversaries may send fraudulent messages to trick users into revealing sensitive information.

### Detection Opportunities

- Suspicious URLs
- Malicious attachments
- Email impersonation

---

## Incident Report 003 - Malware Investigation

### Techniques

- T1204 - User Execution
- T1059 - Command and Scripting Interpreter

### Description

Adversaries may rely on users to execute malicious files, scripts, or commands.

### Detection Opportunities

- Unexpected process execution
- Suspicious script activity
- Endpoint security alerts

---

## Analyst Notes

MITRE ATT&CK mapping helps security analysts:

- Understand attacker behavior
- Improve threat detection
- Enhance incident response
- Standardize investigations
