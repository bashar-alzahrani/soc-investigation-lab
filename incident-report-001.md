# Incident Report 001

## Summary

Multiple failed login attempts were detected from a single IP address.

## Indicators

- Source IP: 192.168.1.10
- Repeated authentication failures

## Risk Level

Medium

## Investigation Findings

The source IP generated multiple failed login attempts within a short period of time, indicating possible brute-force activity.

## Recommendations

- Block the source IP
- Enable Multi-Factor Authentication (MFA)
- Monitor future login activity
