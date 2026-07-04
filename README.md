# Food Contamination Investigation

## Overview
Systematic investigation of food safety violations at Indian restaurants in the Greater Charlotte, NC area. Triggered by a cockroach sighting at Hyderabad House Charlotte (Concord, NC) on July 3, 2026.

## Database
This repo contains structured data from an automated food safety investigation agent:

- `data/restaurants.json` — 7 tracked Indian restaurants
- `data/inspections.json` — 6 health inspection records
- `data/incidents.json` — 5 incident reports (pest sightings, closures, explosions)
- `data/investigations.json` — 1 active investigation case file

## Key Findings

| Restaurant | Risk Level | Key Issue | Score |
|---|---|---|---|
| Hyderabad House Charlotte (Concord) | HIGH | Cockroach on table (Jul 2026) + explosion (Dec 2024) | Pending |
| Curry N Cake | CRITICAL | Shut down — roaches on pans, in microwave (Feb 2025) | 71 (C) |
| Masti/Pudina | CRITICAL | 6+ years of cockroach violations (2018–2024) | 74.5 (C) / 86 (B) |
| Hyderabad House Gwinnett GA | HIGH | Scored 47% on health inspection | 47% |
| Ruchi | MEDIUM | B grade inspection (Nov 2024) | 87.5 (B) |
| Choice | LOW | Minor violations only (May 2022) | 98.5 (A) |
| Jaipur | LOW | Clean inspection (Nov 2018) | 95 (A) |

## Sources
- NC Public Health Inspection Database (public.cdpehs.com)
- Charlotte Observer
- Patch.com
- Charlotte Alerts News
- WSOC TV / WBTW News / WCNC
- Concord Fire Department
- Yelp

## Monitoring
An automated workflow runs every Monday at 9am ET to scan for new violations at tracked restaurants. Findings are committed to this repo.

## Investigation Started
July 4, 2026

