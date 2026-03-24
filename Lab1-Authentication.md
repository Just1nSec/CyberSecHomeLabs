# Lab 1 — Windows Authentication Monitoring

## Objective
Validate that Windows authentication events are successfully collected and monitored by Wazuh.

## Tools Used
- Windows Event Logs
- Wazuh Agent
- Wazuh Dashboard

## Procedure
1. Locked the Windows system
2. Entered incorrect password multiple times
3. Successfully logged in
4. Viewed authentication logs

## Events Observed
- Event ID 4625 — Failed login
- Event ID 4624 — Successful login

## MITRE ATT&CK Mapping
Technique: T1078 — Valid Accounts  
Tactic: Persistence / Initial Access

## Screenshots
- Failed login alert
- Successful login alert
- Authentication dashboard
