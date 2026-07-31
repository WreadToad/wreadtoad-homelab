# WreadToad Home Lab

Hands-on cybersecurity home lab using VMware, Kali Linux, Metasploit, Splunk Enterprise, and Wireshark. This repository documents offensive testing, SIEM investigations, and quick-reference notes.

## Structure
- `/homelab` — virtual environment documentation
- `/notes` — quick-reference commands and filters
- `/investigation-template` — SOC-style investigation templates
- `/Connection` — connection setup and environment linking

## Environment
- **Virtualization:** VMware
- **Offensive tools:** Kali Linux, Metasploit
- **SIEM:** Splunk Enterprise
- **Traffic analysis:** Wireshark

## Status
🟢 Actively in progress
## Goals

This homelab is built to demonstrate real SOC analyst skills, including:

- Generating malicious activity in a controlled environment
- Detecting attacks using Splunk Enterprise
- Building alerts with meaningful thresholds
- Investigating events using a structured SOC methodology
- Documenting findings using a professional investigation template
- Practicing escalation workflows (Tier 1 → Tier 2 → IR)
- Strengthening offensive skills using Kali Linux and Metasploit
- Strengthening defensive skills using Splunk, Windows logs, and playbooks
- Adding Linux log ingestion (Ubuntu)
- Creating additional attack simulations
- Expanding playbooks for more alert types
- Building correlation searches in Splunk

## Recommended Viewing Order

1. Read `/homelab` to understand the environment
2. Review `/Connection` to see how the lab was built
3. Explore `/investigations` to see SOC-style analysis
4. Check `/playbooks` to understand alerting workflows
5. Use `/notes` for commands and quick references

