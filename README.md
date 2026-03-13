# MadridStats Football Analytics Platform

MadridStats is a custom soccer analytics and data pipeline project focused on collecting, organizing, and presenting football data in a professional product setting. The platform is designed to handle match statistics, player performance data, standings, recent form, and related analytics through a modern web application experience.

This project reflects my long-term goals in software engineering, sports data systems, analytics platforms, and real-world product development. It is especially focused on building a reusable and commercially relevant soccer data pipeline that can support websites, media products, and other customer-facing digital experiences.

The production codebase is private due to intellectual property, client-facing development, and collaboration constraints. The live implementation includes proprietary work connected to an upcoming collaboration with a major sports media outlet with a multi-million social audience, so this repository is intentionally limited to documentation, diagrams, screenshots, reflection, and proof of participation.

## Repository Purpose

This repository exists as the public academic documentation layer for the MadridStats project. It is designed to show:

- a technological extracurricular activity aligned with my career goals
- system design and software engineering thinking behind the platform
- how a custom soccer analytics pipeline can be structured for real customer use cases
- assignment deliverables, diagrams, and supporting evidence
- critical reflection on technical decisions, quality, and professional growth

It is not a public mirror of the private production system.

## Features

- Automated soccer data collection and analytics workflows
- Player performance tracking and trend analysis
- Standings and recent form views for contextual team analysis
- Data scraping and scheduled update workflows
- Structured processing and normalization before persistence
- Relational database design for structured analytics queries
- Full stack web application for modern football data presentation
- Service-oriented backend support for scraping and data delivery workflows
- Cloud-hosted deployment infrastructure
- Architecture that can be adapted for media, publishing, and customer website integrations

## Academic Context

I am using MadridStats as the extracurricular technological activity for this assignment. It demonstrates practical work in software engineering, analytics, and sports technology while also showing how I approach independent technical development, product thinking, and engineering documentation.

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
│   ├── README.md
│   ├── azure-hosting-proof.png
│   ├── github-private-repo-proof.png
│   └── madridstats-live-proof.png
├── reflection/
│   └── reflection-report.md
└── proof/
    └── participation-evidence.md
```

## Architecture Overview

At a high level, MadridStats follows a modular pipeline:

1. Data collection services gather match, player, competition, and standings data.
2. Processing services validate and reshape the raw inputs.
3. A relational database stores structured football entities and analytics records.
4. A web application queries this data to present dashboards and football insights to users.

This separation keeps the system easier to maintain, test, extend, and adapt to future leagues, data sources, customer requirements, and partner-facing delivery needs.

Supporting documents:

- [System Architecture](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/system-architecture.md)
- [Data Pipeline](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/data-pipeline.md)
- [Database Design](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/database-design.md)
- [Scraping System](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/scraping-system.md)
- [Scalability Plan](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/docs/scalability-plan.md)

## Proof of Participation

Evidence of my work on the project is documented in [participation-evidence.md](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/proof/participation-evidence.md). Public proof also includes the live project reference at [madridstats.com](https://madridstats.com) and screenshot evidence stored in [screenshots/](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/screenshots/README.md), including repository ownership, hosting context, and product interface captures.

## Reflection Report

The written reflection for the extracurricular activity is available in [reflection-report.md](/Users/zurielhernandez/EA-1-Madrid-Stats-Data-Platform/reflection/reflection-report.md). It summarizes the project’s technical direction, my contributions, quality assessment, and lessons for future iteration.
