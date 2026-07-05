# Changelog

All notable changes to the Royal Fit Uniform GTM automation stack will be documented in this file.

## [Unreleased]

### Added
- `02-quote-system`: Initial scoping and directory structure for the automated quote system.

## [2026-07-05]

### Added
- `01-lead-pipeline`: Initial commit of the production lead pipeline.
- `01-lead-pipeline`: Included webhook auth, data validation, and 5-minute rolling window dedup logic.
- `01-lead-pipeline`: Added companion error-handler workflow for system-wide failure alerting.
- `01-lead-pipeline`: Included Airtable and Google Sheets parallel writing for data integrity auditing.
