# 🎯 Threat Hunting Playbook

## Objective

Identify suspicious activities and indicators of compromise (IOCs) before they become security incidents.

---

## Hunt 1: Failed Login Detection

### What to Look For

- Multiple failed login attempts
- Repeated authentication failures
- Unusual login times

### Indicators

- High volume of failed logins
- Repeated source IP addresses

### Action

- Investigate source IP
- Review authentication logs
- Enable MFA where applicable

---

## Hunt 2: Phishing Activity

### What to Look For

- Suspicious URLs
- Fake login pages
- Unusual email sender domains

### Indicators

- Missing HTTPS
- Domain impersonation
- Unexpected attachments

### Action

- Block malicious domains
- Notify users
- Review email security controls

---

## Hunt 3: Malware Execution

### What to Look For

- Unknown executables
- Suspicious processes
- Unexpected script execution

### Indicators

- Endpoint security alerts
- New unauthorized applications
- Abnormal system behavior

### Action

- Isolate affected devices
- Collect forensic evidence
- Perform malware analysis

---

## Analyst Notes

Threat hunting is a proactive cybersecurity activity focused on identifying hidden threats before they cause business impact.
