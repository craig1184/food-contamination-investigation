# Food Contamination Investigation — Greater Charlotte Indian Restaurants

## Overview
This repository contains investigation data on food safety violations at Indian restaurants in the Greater Charlotte, NC area. The investigation was triggered by a cockroach sighting at Hyderabad House Charlotte (Concord, NC) on July 3, 2026.

## Database Structure
- **restaurants.json** — Tracked restaurants with addresses, risk levels, and status
- **inspections.json** — Health inspection records with scores, grades, and violation details
- **incidents.json** — Incident reports (pest sightings, closures, explosions, health violations)
- **investigations.json** — Active investigation case files with findings and recommendations

## Key Findings

### Critical Risk
| Restaurant | Location | Issue | Score | Date |
|---|---|---|---|---|
| Curry N Cake (Soma Bistro) | Charlotte, NC | Shut down — roaches on pans, microwave, walls | 71 (C) | Feb 2025 |
| Masti/Pudina | Charlotte, NC | 6+ years of cockroach violations | 74.5 (C) / 86 (B) | 2018 & 2024 |
| Hyderabad House Charlotte | Concord, NC | Cockroach on table + prior explosion | Pending | Jul 2026 |

### High Risk
| Restaurant | Location | Issue | Score | Date |
|---|---|---|---|---|
| Hyderabad House Gwinnett GA | Gwinnett, GA | Scored 47% on health inspection | 47 | Recent |

### Medium Risk
| Restaurant | Location | Issue | Score | Date |
|---|---|---|---|---|
| Ruchi | Charlotte, NC | B grade inspection | 87.5 (B) | Nov 2024 |
| Nawabi Hyderabad House Ballantyne | Charlotte, NC | Same chain as Concord location | — | — |

### Low Risk
| Restaurant | Location | Issue | Score | Date |
|---|---|---|---|---|
| Choice Indian Restaurant | Charlotte, NC | Minor violations only | 98.5 (A) | May 2022 |
| Jaipur Indian Cuisine | Charlotte, NC | Clean inspection | 95 (A) | Nov 2018 |

## Data Sources
- NC Public Health Inspection Database (public.cdpehs.com)
- Mecklenburg County Health Department
- Cabarrus County Health Department
- Charlotte Observer
- Patch.com
- Charlotte Alerts News
- WSOC TV
- WBTW News
- WCNC
- Concord Fire Department
- Yelp

## Monitoring
An automated weekly workflow scans all tracked restaurants every Monday at 9am ET for new violations and alerts the user if critical issues are found.

## License
Investigation data — use freely for public health awareness.
