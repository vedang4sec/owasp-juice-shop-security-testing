# Azure Sentinel based Home Lab

## Objective:
To Build a cloud-based SIEM lab using Microsoft Sentinel to simulate 
real SOC analyst workflow i.e log ingestion, detection rule creation, 
incident triage and response.

## Architecture:
- Microsoft Sentinel + Log Analytics Workspace
- Windows VM (intentionally exposed on RDP for log generation)
- Data sources: Windows Security Events and Azure Activity Logs

## Process:
- Connected 2 data sources via Azure Monitor Agent and DCR
- Wrote 2 custom KQL analytics rules (new user creation and suspicious process detection)
- Performed end-to-end incident triage in Sentinel

## KQL Rules
(./kql-queries/)

## Screenshots
(./screenshots/)

## Tools Used:
Microsoft Sentinel, Log Analytics, KQL, Azure Monitor and Windows Vm
