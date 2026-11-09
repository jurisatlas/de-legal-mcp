---
name: de-legal-mcp-skill
description: Official Germany (DE) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Germany Legal Research & Multi-Tier Case Law Skill (`de-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Germany (DE)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `ECLI:DE:BGH:2024:100124UVIII_ZR_12.23.0 or BGB § 433`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Amtsgerichte (AG), Landgerichte (LG), Verwaltungsgerichte (VG), Arbeitsgerichte (ArbG), Sozialgerichte (SG) & Finanzgerichte (FG)
   - **Second Instance (Cantonal / Regional / Appellate):** 24 Oberlandesgerichte (OLG / KG Berlin), Oberverwaltungsgerichte (OVG / VGH), Landesarbeitsgerichte (LAG) & Landessozialgerichte (LSG) across 16 Bundesländer
   - **Supreme & Constitutional Instance:** Bundesverfassungsgericht (BVerfG), Bundesgerichtshof (BGH), Bundesverwaltungsgericht (BVerwG), Bundesfinanzhof (BFH), Bundesarbeitsgericht (BAG) & Bundessozialgericht (BSG)
   - **Primary Tiered Database:** OpenLegalData.io (AG/LG/OLG/Federal) & Rechtsprechung im Internet + 16 Landesrechtsprechungsdatenbanken (`https://de.openlegaldata.io/api/cases/`)
