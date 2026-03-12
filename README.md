# MadridStats Football Analytics Platform

MadridStats is a custom soccer analytics and data pipeline project centered on automated collection, processing, storage, and presentation of football data. The platform is designed to gather match statistics, player performance data, standings, recent form, and related analytics, then expose that information through a modern full stack web application.

The project reflects my long-term goals in software engineering, sports data systems, analytics platforms, and product development. It is especially focused on building a reusable and commercially relevant soccer data pipeline that can support websites, media products, and other customer-facing digital experiences.

The production codebase is private due to intellectual property, client-facing development, and collaboration constraints. The live implementation includes proprietary work connected to an upcoming collaboration with a major sports media outlet with a multi-million social audience, so this repository is intentionally limited to documentation, diagrams, screenshots, reflection, and proof of participation.

## Repository Purpose

This repository exists as the public academic documentation layer for the MadridStats project. It is designed to show:

- a technological extracurricular activity aligned with my career goals
- system design and software engineering thinking behind the platform
- how a custom soccer analytics pipeline can be structured for real customer use cases
- assignment deliverables, diagrams, and supporting evidence
- critical reflection on technical decisions, quality, and professional growth

## Features

- Automated soccer data collection and analytics workflows
- Player performance tracking and trend analysis
- Standings and recent form views for contextual team analysis
- Data scraping and scheduled update workflows
- Structured processing and normalization before persistence
- PostgreSQL relational database design hosted with Neon
- Full stack web application built with React and TypeScript
- Python and FastAPI services supporting scraping and data delivery workflows
- Azure-based hosting for deployed platform infrastructure
- Architecture that can be adapted for media, publishing, and customer website integrations

## Repository Structure

```text
EA-1-Madrid-Stats-Data-Platform/
├── README.md
├── docs/
│   ├── system-architecture.md
│   ├── data-pipeline.md
│   ├── database-design.md
│   ├── scraping-system.md
│   └── scalability-plan.md
├── diagrams/
│   ├── architecture-diagram.md
│   ├── data-flow-diagram.md
│   └── database-schema.md
├── screenshots/
│   └── README.md
├── reflection/
│   └── reflection-report.md
└── proof/
    └── participation-evidence.md
```

## Architecture Overview

At a high level, MadridStats follows a modular pipeline:

1. Data collection services gather match, player, competition, and standings data.
2. Python and FastAPI processing services validate and reshape the raw inputs.
3. A Neon-hosted PostgreSQL database stores structured football entities and analytics records.
4. A React and TypeScript web application queries this data to present dashboards and football insights to users.

The platform is hosted on Azure, and this separation keeps the system easier to maintain, test, extend, and adapt to future leagues, data sources, customer requirements, and partner-facing delivery needs.

Further documentation:

- [System Architecture](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/system-architecture.md)
- [Data Pipeline](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/data-pipeline.md)
- [Database Design](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/database-design.md)
- [Scraping System](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/scraping-system.md)
- [Scalability Plan](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/scalability-plan.md)

## Proof of Participation

Evidence of my work on the project is documented in [participation-evidence.md](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/proof/participation-evidence.md). Public proof also includes the live project reference at [madridstats.com](https://madridstats.com), which demonstrates the existence of the product itself without exposing the private production repository. The screenshots folder is reserved for interface captures and other visual proof that support the assignment deliverable without exposing private implementation details.

## Reflection Report

The written reflection for the extracurricular activity is available in [reflection-report.md](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/reflection/reflection-report.md). It summarizes the project’s technical direction, my contributions, quality assessment, and lessons for future iteration.
