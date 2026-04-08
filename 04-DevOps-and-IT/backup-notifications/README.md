# Backup Notifications & Alerting

## Description
Monitors automated backup jobs (e.g., AWS Backup, Proxmox, Veeam or custom cron scripts). It receives webhooks upon job completion and immediately alerts the IT team if a backup fails or is incomplete.

## Features
- **Status Evaluation:** Routes logic based on `success` or `failed` payload.
- **Critical Alerting:** Pings the DevOps Slack channel with failure logs.
- **Reporting:** Logs successful backups quietly into a Google Sheet for compliance audits.
