# Food Contamination Investigation

## Overview
Systematic investigation of food safety violations at Indian restaurants in the Greater Charlotte, NC area. Triggered by a cockroach sighting at Hyderabad House Charlotte (Concord, NC) on July 3, 2026.

## Database
- `data/restaurants.json` - 7 tracked Indian restaurants
- `data/inspections.json` - 6 health inspection records
- `data/incidents.json` - 5 incident reports
- `data/investigations.json` - 1 active investigation case file

## Key Findings

| Restaurant | Risk | Key Issue | Score |
|---|---|---|---|
| Hyderabad House Charlotte | HIGH | Cockroach on table + explosion history | Pending |
| Curry N Cake | CRITICAL | Shut down - roaches everywhere (Feb 2025) | 71 (C) |
| Masti/Pudina | CRITICAL | 6+ years of cockroach violations | 74.5 (C) / 86 (B) |
| Ruchi | MEDIUM | B grade inspection | 87.5 (B) |
| Choice | LOW | Minor violations only | 98.5 (A) |
| Jaipur | LOW | Clean inspection | 95 (A) |

## Issues
GitHub issues track each violation with severity labels:
- [CRITICAL] Curry N Cake shutdown
- [CRITICAL] Masti/Pudina repeat cockroach violations
- [HIGH] Hyderabad House cockroach + explosion
- [MEDIUM] Ruchi B grade
- [INFO] Choice & Jaipur clean baseline

## Sources
- NC Public Health Inspection Database (public.cdpehs.com)
- Charlotte Observer, Patch.com, Charlotte Alerts News
- WSOC TV, WBTW News, WCNC
- Concord Fire Department, Yelp

## Monitoring
Automated workflow runs every Monday at 9am ET scanning for new violations.

## Investigation Started
July 4, 2026
