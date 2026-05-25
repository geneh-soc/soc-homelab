# redrack-util01

## Purpose

Ubuntu 24.04 utility and automation server used for Linux administration, Python development, Bash scripting, Git operations, SSH management, and future security automation workflows within the RedRack Technologies SOC Lab environment.

This system functions as the primary Linux administration and automation platform for the lab.

---

## Operating System

- Ubuntu Server 24.04

---

## Current Status

Active

---

## Installed Components

- Python 3
- pip
- python3-venv
- Git
- curl
- wget
- unzip
- OpenSSH Server
- net-tools
- htop
- vim
- nano

---

## Planned Services and Tooling

- Python automation scripts
- Bash scripting
- Git version control
- SSH remote management
- Wazuh Agent
- API integrations
- Ansible
- Docker
- Monitoring scripts

---

## Planned Validation

### Linux Administration
- Package installation validation
- Service management
- User and permission management
- SSH access validation

### Python Environment
- Virtual environments
- Dependency installation
- Automation scripting
- JSON parsing

### Git & SSH
- GitHub connectivity
- SSH authentication
- Repository cloning
- Commit workflows

### Automation
- Alert ingestion scripts
- IOC enrichment
- Risk scoring
- Notification workflows

---

## Validation Commands

```bash
hostnamectl
ip a
systemctl status ssh
python3 --version
git --version
ssh -V
df -h
free -m
```

---

## Planned Screenshots

- Ubuntu system information
- SSH service status
- Python environment validation
- Git configuration
- Automation script execution
- Linux package installations

---

## Planned Automation Projects

- Python alert ingestion pipeline
- IOC enrichment automation
- GeoIP lookups
- CVE enrichment
- Slack/email notifications
- Log parsing workflows
- API integrations

---

## Lessons Learned

This section will document:
- Linux administration troubleshooting,
- SSH connectivity issues,
- Python environment setup,
- package installation problems,
- and automation workflow challenges encountered during deployment.
