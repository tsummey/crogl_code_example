# GitHub Security Advisories Pipeline

This project provides a complete end-to-end workflow for scraping GitHub advisories, retrieving detailed data via the GraphQL API, organizing advisories by severity, enriching them with Known Exploited Vulnerabilities (KEV) data from CISA, and exporting everything into structured CSVs and ZIP archives.

---

## 📦 Project Overview

The pipeline includes:

1. **Web Scraping** GitHub advisories
2. **GraphQL API calls** to get full advisory metadata
3. **Severity-based JSON organization**
4. **Merging JSON into a single dataset**
5. **KEV correlation against CISA catalog**
6. **ZIP archiving by severity**

---
