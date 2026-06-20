# Matador Ventures Capital — Deal Pipeline

GitHub Pages site tracking pre-seed and seed AI-native deals for **Matador Ventures Capital** (Mohammed Al-Abdullah, Founder & GP).

Built by Ahsan Habib using the autonomous deal-sourcing pipeline.

## Stack

- GitHub Pages (static site, auto-deployed via GitHub Actions)
- Dark-theme deal pipeline with Grid/Kanban/Table views
- Sync via Contents API from `ai-deal-sourcer` pipeline

## Repo maintenance

Deals are synced automatically from the `ai-deal-sourcer` pipeline project via `sync_matador_to_github.py`. Do not edit `data/deals.json` directly unless making manual overrides.
