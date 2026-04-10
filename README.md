# MonPG Status Page

[![Status](https://img.shields.io/badge/Status_Page-status.monpg.app-green)](https://status.monpg.app)
[![Website](https://img.shields.io/badge/Website-monpg.app-blue)](https://monpg.app)
[![Powered By](https://img.shields.io/badge/Powered_By-Upptime-white)](https://upptime.js.org)

This repository powers the **[MonPG status page](https://status.monpg.app)**, providing real-time uptime monitoring and incident tracking for the [MonPG](https://monpg.app) PostgreSQL monitoring platform.

## What is MonPG?

**[MonPG](https://monpg.app)** is a production-grade PostgreSQL monitoring and performance optimization platform. It provides real-time dashboards, index advisory, vacuum advisory, and smart alerting for PostgreSQL databases — including self-hosted, AWS RDS, Aurora, and Azure Database for PostgreSQL.

Learn more at **[monpg.app](https://monpg.app)**.

## Monitored Services

| Service | URL | Description |
|---------|-----|-------------|
| MonPG Landing | [monpg.app](https://monpg.app) | Marketing website and documentation |
| MonPG App | [app.monpg.app](https://app.monpg.app) | Main monitoring application |
| MonPG API | [api.monpg.app](https://api.monpg.app/api/v1/health) | Backend API health endpoint |
| MonPG Auth | [auth.monpg.app](https://auth.monpg.app) | Authentication service |

## How It Works

This status page is built with [Upptime](https://upptime.js.org), an open-source uptime monitor and status page powered by GitHub Actions. Every 5 minutes, GitHub Actions checks the health of all MonPG services and updates this repository with the results.

- **Uptime checks** run every 5 minutes via GitHub Actions
- **Incident reports** are created automatically as GitHub Issues
- **Historical data** is stored in this repository as JSON and CSV
- **Status page** is served at [status.monpg.app](https://status.monpg.app)

## MonPG Features

- **[PostgreSQL Monitoring](https://monpg.app/postgresql-monitoring)** — real-time query and server monitoring
- **[AWS RDS Monitoring](https://monpg.app/aws-rds-monitoring)** — first-class RDS and Aurora support
- **Index Advisor** — find missing and unused indexes
- **Vacuum Advisor** — prevent table bloat issues
- **Smart Alerts** — anomaly-based alerting
- **Log Insights** — automated log pattern analysis

## Related Repositories

- **[monpg](https://github.com/Devopzone-Eood/monpg)** — MonPG platform (backend + frontend)
- **[monpg-landing](https://github.com/Devopzone-Eood/monpg-landing)** — MonPG landing page at [monpg.app](https://monpg.app)

## Links

- **Status Page**: [status.monpg.app](https://status.monpg.app)
- **Website**: [monpg.app](https://monpg.app)
- **Application**: [app.monpg.app](https://app.monpg.app)
- **Blog**: [monpg.app/blog](https://monpg.app/blog)
- **Documentation**: [monpg.app/docs](https://monpg.app/docs)

---

Built by [Devopzone](https://github.com/Devopzone-Eood) | [monpg.app](https://monpg.app)
