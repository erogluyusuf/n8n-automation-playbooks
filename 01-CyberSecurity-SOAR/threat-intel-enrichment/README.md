# Threat Intel Enrichment API

## Description
Provides an internal API endpoint (Webhook) to quickly enrich IP addresses or File Hashes. It queries multiple Threat Intel sources (like AbuseIPDB or AlienVault) and returns a consolidated JSON response. Ideal for integrating with SIEMs or custom scripts.

## Features
- **Webhook Trigger:** Accepts `GET` or `POST` requests with an `ip` parameter.
- **AbuseIPDB Integration:** Checks the IP confidence score and recent reports.
- **Standardized Output:** Returns a clean JSON payload for the requesting service.

## Prerequisites
- AbuseIPDB API Key
