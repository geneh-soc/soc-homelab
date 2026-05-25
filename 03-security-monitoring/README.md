# Security Monitoring

## Overview

This section documents the centralized logging, endpoint telemetry, SIEM engineering, monitoring workflows, and detection capabilities implemented within the RedRack Technologies SOC Lab environment.

The goal is to simulate enterprise SOC visibility, log ingestion, security event monitoring, and detection engineering workflows across Windows and Linux systems.

---

## Monitoring Stack

### SIEM Platforms
- Wazuh
- Splunk

### Endpoint Telemetry
- Sysmon
- PowerShell Logging
- Windows Event Logs
- Linux system logs

### Monitoring & Visibility
- Grafana
- Uptime Kuma
- Custom Python monitoring scripts

---

## Planned Monitoring Components

| Component | Purpose | Status |
|---|---|---|
| Wazuh Server | Centralized SIEM | Planned |
| Sysmon | Windows telemetry | In Progress |
| Splunk Forwarder | Log forwarding | In Progress |
| PowerShell Logging | Script visibility | In Progress |
| Linux Logging | Ubuntu telemetry | Planned |
| Grafana | Monitoring dashboards | Planned |

---

## Planned Detection Scenarios

- Failed logins
- Privilege escalation attempts
- Suspicious PowerShell execution
- Process creation monitoring
- Network connection anomalies
- Authentication failures
- Unauthorized administrative activity
- Persistence mechanisms
- Command execution monitoring

---

## MITRE ATT&CK Mapping

Planned ATT&CK coverage includes:

- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Command and Control

---

## Planned Dashboards

- Endpoint health
- Authentication monitoring
- Sysmon event monitoring
- Failed login tracking
- PowerShell activity
- Linux system activity
- Threat hunting dashboards

---

## Validation Goals

- Verify successful log ingestion
- Validate endpoint telemetry
- Test detection rules
- Simulate suspicious activity
- Monitor SIEM alert generation
- Validate dashboard visibility

---

## Planned Screenshots

- Wazuh dashboards
- Splunk searches
- Sysmon event logs
- PowerShell logging events
- Alert workflows
- Threat hunting queries

---

## Lessons Learned

This section will document:
- SIEM deployment challenges,
- log ingestion troubleshooting,
- telemetry tuning,
- false positive reduction,
- and monitoring workflow improvements encountered during implementation.
