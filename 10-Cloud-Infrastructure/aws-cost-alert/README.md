# AWS Cost Anomaly Alert

## Description
Monitors your AWS billing daily using the AWS Cost Explorer API. If the daily spend exceeds your defined budget or shows an anomalous spike compared to the previous day, it immediately alerts the DevOps/Finance channel.

## Features
- **Daily Polling:** Runs every morning to check yesterday's spend.
- **Threshold Logic:** Compares current spend against a hardcoded limit or percentage increase.
- **Multi-Channel Alert:** Sends a formatted breakdown to Slack.
