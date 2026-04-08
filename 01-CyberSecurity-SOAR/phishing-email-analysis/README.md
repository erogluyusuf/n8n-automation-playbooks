# Phishing Email Analysis Workflow

## Description
This SOAR playbook automatically ingests reported suspicious emails, extracts Indicators of Compromise (IOCs) such as URLs and domains, and analyzes them using threat intelligence platforms (VirusTotal). It significantly reduces manual triage time for SOC analysts.

## Features
- **Automated Ingestion:** Monitors a dedicated mailbox via IMAP.
- **IOC Parsing:** Extracts URLs and sender domains using RegEx.
- **Threat Enrichment:** Integrates with VirusTotal API.
- **Alert Generation:** Sends formatted alerts directly to Slack/Teams.

## Prerequisites
- VirusTotal API Key
- IMAP Access for the abuse/phishing mailbox
- Slack Webhook or API credentials
