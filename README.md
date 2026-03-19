# jeremystrindade.github.io

> Personal portfolio and professional presence of **Jeremy Trindade** — Data Engineering Professional in Training.
> Live at **[jeremystrindade.com](https://jeremystrindade.com)**

---

## 📋 About This Repository

This repository hosts the source code for my personal portfolio website, deployed via **GitHub Pages** and served through a custom domain with **Cloudflare CDN**.

The site serves as a central hub for my Data Engineering career development — showcasing my learning roadmap, portfolio projects, technical skills, and professional background.

---

## 🌐 Live Website

| | |
|---|---|
| **Primary URL** | [https://jeremystrindade.com](https://jeremystrindade.com) |
| **GitHub Pages URL** | [https://jeremystrindade.github.io](https://jeremystrindade.github.io) |
| **CV Download** | [https://jeremystrindade.com/jetcv.pdf](https://jeremystrindade.com/jetcv.pdf) |

Scan to download CV directly:

> QR code generated via [qrcode-monkey.com](https://www.qrcode-monkey.com) · Colour `#003366` · Points to `https://jeremystrindade.com/jetcv.pdf`

---

## 🎨 Design System

The site uses a consistent dark theme aligned with the professional colour palette used across all portfolio documents (CV, proposal).

### Colour Palette

| Variable | Hex | Usage |
|---|---|---|
| `--bg` | `#0a0e1a` | Page background |
| `--bg2` | `#0f1422` | Section backgrounds |
| `--bg3` | `#151b2e` | Card hover states |
| `--blue` | `#3b82f6` | Primary accent, links, highlights |
| `--teal` | `#2dd4bf` | Secondary accent, phase chips |
| `--white` | `#f0f4ff` | Primary text |
| `--gray` | `#8892aa` | Secondary text, descriptions |
| `--border` | `rgba(255,255,255,0.07)` | Borders and dividers |

### Document Colour Palette (CV & Proposal)

| Name | Hex | Usage |
|---|---|---|
| Navy Dark | `#1F3864` | Primary headings, header background |
| Navy Mid | `#2E75B6` | Section dividers, links, accents |
| Navy Recommended | `#0F3460` | Recommended CV accent colour |
| Light Blue | `#D6E4F0` | Table row highlights, tag backgrounds |
| Light Gray | `#F2F2F2` | Alternate table rows |
| Body Text | `#333333` | Primary document body text |
| Secondary Text | `#595959` | Metadata, captions |

### Typography

| Role | Font | Source |
|---|---|---|
| Display / Headings | `Syne` (800 weight) | Google Fonts |
| Body Text | `DM Sans` | Google Fonts |
| Code / Labels / Tags | `DM Mono` | Google Fonts |

---

## 🗂️ Site Structure

```
jeremystrindade.github.io/
│
├── index.html          # Complete single-page portfolio
├── jetcv.pdf           # CV download (linked via QR code)
└── README.md           # This file
```

---

## 📄 Page Sections

| # | Section | Description |
|---|---|---|
| 01 | **Hero** | Name, title, tech stack tags, CTA buttons |
| 02 | **About** | Professional profile, location, work setup, languages |
| 03 | **Learning Roadmap** | 6-phase data engineering preparation roadmap |
| 04 | **Portfolio Projects** | All 6 projects with status, tech stack, and links |
| 05 | **Technical Skills in Training** | Focused data engineering skill set |
| 06 | **Contact** | Email, LinkedIn, GitHub, website |

---

## 🚀 Portfolio Projects

| # | Project | Status | Technologies |
|---|---|---|---|
| 00 | [Production-Ready Pipeline Template](https://github.com/jeremystrindade/data-engineering-project-template) | ✅ Completed | Git, SDLC |
| 01 | [Portfolio Website & Infrastructure](https://jeremystrindade.com) | ✅ Completed | HTML, CSS, JS, GitHub Pages, Cloudflare, DNS |
| 02 | [Automated Data Ingestion Pipeline](https://github.com/jeremystrindade/data-pipeline-python-sql) | 🔄 In Development | Python, REST APIs, PostgreSQL, Airflow |
| 03 | [Large-Scale Processing with PySpark](https://github.com/jeremystrindade/big-data-processing-pyspark) | 🔄 In Development | Apache Spark, PySpark, Spark SQL |
| 04 | [Cloud Pipeline: Azure & Databricks](https://github.com/jeremystrindade/azure-data-engineering-pipeline) | 🔄 In Development | Azure Data Factory, ADLS, Databricks, Delta Lake |
| 05 | [Data Warehouse & Analytics Model](https://github.com/jeremystrindade/data-warehouse-analytics-model) | 🔄 In Development | SQL, PostgreSQL, Python, Star Schema |

---

## 🗺️ Learning Roadmap

| Phase | Focus | Course | Duration |
|---|---|---|---|
| 01 | Python Foundation | 100 Days of Code: Python Pro Bootcamp | 6–8 weeks |
| 02 | SQL & Databases | SQL for Data Analytics & Business Intelligence | 3–4 weeks |
| 03 | Data Engineering | The Data Engineer Bootcamp | 3–4 weeks |
| 04 | Big Data Processing | Spark and Python for Big Data with PySpark | 2–3 weeks |
| 05 | Pipeline Orchestration | Master Apache Airflow (Hands-On) | 1–2 weeks |
| 06 | Cloud Engineering | Azure Databricks & Spark SQL + Azure MasterClass | 3–4 weeks |

**Total estimated timeline:** 3–6 months

---

## 🛠️ Technical Skills in Training

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Querying | SQL, PostgreSQL |
| Big Data Processing | Apache Spark, PySpark, Spark SQL |
| Pipeline Orchestration | Apache Airflow, DAG design, workflow scheduling |
| Cloud & Platforms | Microsoft Azure, Databricks, Delta Lake |
| Data Engineering | ETL/ELT pipelines, data lakes, data warehouses, lakehouse architecture |
| Version Control | Git, GitHub |
| Academic | BSc Computer Science — University of the People (in progress) · Harvard CS50 |

---

## 🏗️ Infrastructure & Deployment

This site is deployed using the following stack:

```
Domain Registrar: site.pt (jeremystrindade.com)
     ↓
Nameservers: Cloudflare (ashley.ns.cloudflare.com / yichun.ns.cloudflare.com)
     ↓
DNS Records:
  A     @    → 185.199.108.153  (GitHub Pages)
  A     @    → 185.199.109.153  (GitHub Pages)
  A     @    → 185.199.110.153  (GitHub Pages)
  A     @    → 185.199.111.153  (GitHub Pages)
  CNAME www  → jeremystrindade.github.io
     ↓
CDN & SSL: Cloudflare (Free plan — caching, DDoS protection, SSL/TLS)
     ↓
Hosting: GitHub Pages (jeremystrindade.github.io)
     ↓
Live URL: https://jeremystrindade.com
```

### Key Infrastructure Decisions

- **Cloudflare as CDN** — faster page loads globally, DDoS protection, free SSL certificate management
- **DNS only mode on A records** — required for GitHub Pages to correctly serve the site (proxied mode breaks GitHub Pages SSL verification)
- **CNAME www → github.io** — ensures both `www.jeremystrindade.com` and `jeremystrindade.com` resolve correctly
- **Enforce HTTPS** — enabled in GitHub Pages settings for secure connections only

---

## 📁 Related Repositories

| Repository | Description |
|---|---|
| [data-engineering-project-template](https://github.com/jeremystrindade/data-engineering-project-template) | Project 00 — Production-ready pipeline template |
| [data-pipeline-python-sql](https://github.com/jeremystrindade/data-pipeline-python-sql) | Project 02 — Automated data ingestion pipeline |
| [big-data-processing-pyspark](https://github.com/jeremystrindade/big-data-processing-pyspark) | Project 03 — Large-scale PySpark processing |
| [azure-data-engineering-pipeline](https://github.com/jeremystrindade/azure-data-engineering-pipeline) | Project 04 — Cloud pipeline: Azure & Databricks |
| [data-warehouse-analytics-model](https://github.com/jeremystrindade/data-warehouse-analytics-model) | Project 05 — Data warehouse & analytics model |

---

## 🔧 How to Update

To update the site, simply edit `index.html` and commit the changes to the `main` branch. GitHub Pages will automatically redeploy within a few minutes.

To update the CV download, replace `jetcv.pdf` in the repository root with the new version. The QR code URL (`jeremystrindade.com/jetcv.pdf`) will continue to work without any changes.

---

## 👤 Contact

| | |
|---|---|
| **Email** | [jeremystrindade@gmail.com](mailto:jeremystrindade@gmail.com) |
| **LinkedIn** | [linkedin.com/in/jeremystrindade](https://linkedin.com/in/jeremystrindade) |
| **GitHub** | [github.com/jeremystrindade](https://github.com/jeremystrindade) |
| **Website** | [jeremystrindade.com](https://jeremystrindade.com) |
| **Location** | Viseu, Portugal |

---

*Last updated: March 2026*
