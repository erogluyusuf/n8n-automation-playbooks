# Wazuh Alert Routing & Escalation

## Description
Receives webhooks directly from the Wazuh SIEM/XDR manager. It parses the incoming alert, evaluates the rule severity level, and dynamically routes the alert:
- **Severity 12+ (Critical):** Creates a Jira Incident ticket and pages the on-call team.
- **Severity 7-11 (High):** Sends a notification to the SOC Slack channel.
- **Below 7:** Logs the event for reporting purposes without generating noise.

## Features
- **Intelligent Routing:** Switch node logic based on `rule.level`.
- **Jira Integration:** Automated ticket creation with full alert context.
- **Noise Reduction:** Prevents alert fatigue by silencing low-severity events.

## Prerequisites
- Wazuh Manager configured to send webhooks to n8n
- Jira API credentials (Email + API Token)
