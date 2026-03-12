# Database Design

## Overview

MadridStats is best supported by a relational database because football analytics depends on structured entities and well-defined relationships. The project uses PostgreSQL hosted on Neon. Matches connect to teams, players belong to teams, competitions contain standings, and statistical records must remain traceable to a clear context. A relational model supports these patterns cleanly while remaining flexible for analytics-oriented querying.

## Core Entities

### Players

The players entity represents individual footballers and provides a stable identity for statistics, team association, and historical tracking across matches and competitions.

### Matches

Matches represent the central event around which most analytics are organized. They connect participating teams, competition context, scheduling data, and match-specific statistics or events.

### Competitions

Competitions define the tournament or league context for each match and standings record. This allows the platform to distinguish between league play, cup fixtures, and future competition expansion.

### Teams

Teams provide the organizational structure for player membership, match participation, standings position, and recent form summaries. Team records also support comparison workflows in the frontend.

### Standings

Standings capture table-level state such as rank, points, wins, draws, losses, and goal-related measures. They provide context that users expect when viewing team performance over time.

### Player Statistics

Player statistics store performance-oriented data connected to a specific player and match or reporting window. This entity supports dashboards that compare output, consistency, and trend development.

### Match Events

Match events represent time-based records such as goals, cards, substitutions, or other event-level moments. This entity adds depth beyond final scores and enables richer storytelling in analytics views.

### Recent Form

Recent form summarizes a team’s or player’s near-term performance and is useful for quick analysis, trend spotting, and dashboard summaries.

## Why Relational Design Fits This Project

Relational design is a good fit for MadridStats for several reasons:

- Football data is inherently relational and context dependent.
- Data integrity matters when the same entities appear across many records.
- Queries often depend on joins between teams, players, matches, and competitions.
- The structure supports both operational workflows and analytics-friendly reporting.

## Design Principles

The database design emphasizes:

- clear entity ownership
- normalized references between records
- controlled duplication only where it improves reporting speed or simplicity
- room for future extension into additional leagues, seasons, and derived metrics

This approach keeps the model academically defensible while also matching how a real analytics platform would need to evolve.
