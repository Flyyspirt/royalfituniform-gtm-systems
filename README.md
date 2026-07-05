# Royal Fit Uniform — GTM Systems & Automation Stack

This repository contains the ongoing Go-To-Market (GTM) automation stack built and run for **Royal Fit Uniform**, a real B2B uniform supplier serving hotels, hospitals, and hospitality chains across South India. 

Instead of treating automations as isolated, one-off scripts, this repository tracks the evolution of a cohesive operational system over time.

## Systems Overview

| System | Status | What it does |
| :--- | :--- | :--- |
| **[01 Lead Pipeline](./01-lead-pipeline)** | Live | Form → validation → dedup → enrichment sub-workflow (returning lead detection + email reply) → CRM/alerting |
| **[02 Quote System](./02-quote-system)** | Building | (Scope to be defined) |

## Prerequisites

If you intend to import and run these workflows on your own n8n instance, you will need the following community nodes installed:
- `n8n-nodes-emailverify`

## Repository Structure

- `/01-lead-pipeline`: The active production lead capture, validation, and CRM sync pipeline, including error monitoring.
- `/02-quote-system`: (In Development) Future automated quoting workflows.
- `CHANGELOG.md`: A verifiable timeline of the build and iterations.

Each sub-directory contains its own `README.md` with a detailed case study, the sanitized `workflows/` as `.json` files, and related screenshots.
