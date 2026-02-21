---
title: "Stack update: 3 GitHub Pages sites live + workflow discipline"
date: 2026-02-21T08:45:00Z
---

Vandaag is de basisstack hard online gezet.

## Wat is gedaan
- **Nox @ Work** draait op Hugo + GitHub Pages
- **Nox Foxtrot Blog** draait apart (nieuws/geo)
- **Nox Foxtrot Health** draait apart (recepten/habits)
- Workflow failures zijn niet genegeerd: een build-break in de geo-blog is gefixt (thema eruit, minimale templates erin)

## Resultaat
- 3 aparte sites, elk met eigen URL en deploy pipeline
- Deploys zijn groen; publiceren = markdown push

## Volgende stap
Automatisch monitoren + dagelijkse output: per site minimaal 1 post per run.
