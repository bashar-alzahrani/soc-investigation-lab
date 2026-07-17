# 🛡️ SOC Investigation Lab

A collection of Security Operations Center (SOC) investigations, threat hunting activities, incident analysis reports, and cybersecurity case studies.

## 🎯 Objective

This lab demonstrates practical cybersecurity investigation skills including:

- Threat Analysis
- IOC Hunting
- Incident Response
- Log Investigation
- MITRE ATT&CK Mapping
- Security Reporting

## 🔍 Investigation Scenarios

### Case 001 - Multiple Failed Login Attempts

#### Incident Summary

Several failed login attempts were detected from the same IP address within a short period of time.

#### Findings

- Multiple authentication failures
- Repeated source IP activity
- Brute-force behavior indicators

#### Impact

Medium Risk

#### Recommendation

- Block suspicious IP
- Enable MFA
- Monitor authentication events

---

### Case 002 - Suspicious Phishing URL

#### Incident Summary

A suspicious URL was shared through email and analyzed for phishing indicators.

#### Findings

- Suspicious keywords
- No HTTPS
- Domain impersonation indicators

#### Impact

High Risk

#### Recommendation

- Block domain
- Notify users
- Initiate phishing awareness campaign

---

### Case 003 - Malware Alert Investigation

#### Incident Summary

Endpoint security generated an alert for suspicious executable activity.

#### Findings

- Unexpected process execution
- Suspicious file behavior
- Potential malware indicators

#### Impact

High Risk

#### Recommendation

- Isolate endpoint
- Perform malware scan
- Collect forensic evidence

---

## 🧰 Security Skills Demonstrated

- Incident Analysis
- Threat Detection
- Log Analysis
- IOC Investigation
- Cybersecurity Reporting
- Risk Assessment

## ⚔️ MITRE ATT&CK Techniques

- T1110 - Brute Force
- T1566 - Phishing
- T1059 - Command Execution

## 📚 Tools & Platforms

- Python
- SIEM Concepts
- ServiceNow
- Microsoft Security Solutions

## 👨‍💻 Author

Bashar Alzahrani
