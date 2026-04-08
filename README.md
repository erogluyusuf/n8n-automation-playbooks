# Enterprise n8n Automation & SOAR Playbooks

[![Maintainer](https://img.shields.io/badge/Maintainer-Yusuf_Eroğlu-blue)](https://github.com/erogluyusuf)
[![Project](https://img.shields.io/badge/Project-Globipedi-orange)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A curated collection of enterprise-grade n8n automation workflows and SOAR (Security Orchestration, Automation, and Response) playbooks designed to optimize operations across various business departments.

## Repository Structure

This repository is divided into specialized domains. Each folder contains a detailed `README.md` and a ready-to-import `workflow.json` file.

* **[01-CyberSecurity-SOAR](./01-CyberSecurity-SOAR):** Incident response, phishing analysis, and threat intel enrichment.
* **[02-ECommerce-Operations](./02-ECommerce-Operations):** Abandoned cart recovery, inventory sync, and invoice generation.
* **[03-HumanResources](./03-HumanResources):** Candidate tracking, employee onboarding, and PTO management.
* **[04-DevOps-and-IT](./04-DevOps-and-IT):** Server monitoring, backup alerting, and GitHub issue triage.
* **[05-Marketing-and-Sales](./05-Marketing-and-Sales):** CRM lead capture, campaign tracking, and social media scheduling.
* **[06-Finance-and-Accounting](./06-Finance-and-Accounting):** Payment gateway synchronization and expense approvals.
* **[07-Data-and-Analytics](./07-Data-and-Analytics):** SQL-to-Sheets ETL pipelines and daily metric reporting.
* **[08-Personal-Productivity](./08-Personal-Productivity):** RSS bots, task reminders, and weather alerts.

## How to Use

1. Navigate to the desired category folder.
2. Open the `workflow.json` file and copy its contents.
3. Open your n8n instance.
4. Go to the workflow canvas, press `Ctrl+V` (or `Cmd+V`) to paste the nodes.
5. Configure your specific credentials (API keys, Webhook URLs, database connections).
6. Activate the workflow!

## About the Project
Developed as part of the **Globipedi** project ecosystem. These workflows are designed to serve as foundational templates that can be scaled and customized to fit specific organizational needs.

---
*Maintained with ❤️ by [Yusuf Eroğlu](https://github.com/erogluyusuf).*
