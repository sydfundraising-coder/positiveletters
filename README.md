# Akshardham Positive Support Letter Drive — Seva Centre Meeting Tracker

Dashboard + tracker for the Seva Centre meetings held **Mon 7 Sep – Wed 16 Sep 2026**
(10-day window, each meeting scheduled outside the centre's own weekly assembly day).

## Contents
| File | Purpose |
|---|---|
| `index.html` | Live dashboard + tracker (served by GitHub Pages) |
| `Seva_Centre_Meeting_Tracker.xlsx` | Multi-user working tracker for SharePoint/Teams co-authoring |

## Live site
Once GitHub Pages is enabled: `https://sydfundraising-coder.github.io/<repo-name>/`

## How to use
- **Dashboard tab** — meetings per state/territory, per day (with centre names), per follow-up person; KPIs update as entries are filled in.
- **Tracker tab** — record attendance, support letters received, follow-up person and status. Data saves in each viewer's browser; use Export/Import JSON to consolidate, or use the Excel on SharePoint for real-time multi-user editing.
- **Add follow-up people** — type names (comma-separated) in the "Manage team" box.
- **Allocate a centre** — set the "Follow-up Person" dropdown on that centre's row in the Tracker tab.

## Updating in future
Replace `index.html` (and/or the `.xlsx`) with the newer version and commit — GitHub Pages redeploys automatically within a minute or two.

## Privacy note
This tracker includes coordinators' and sanchalaks' mobile numbers. GitHub Pages sites are public.
For a public URL, use a redacted build (contacts hidden); keep the full-contact version in the private Excel.
