# Changelog

Each version matches the version number of the published page on claude.ai
(https://claude.ai/artifact/E7D9J1rL6Q1SJNEEonhgrm) and has a matching git tag (`v1`, `v2`, ...).
Versions 1–8 were made before versioning started, so only v9 onward exist as git commits.
Earlier versions can still be viewed in the page's version history on claude.ai.

## v12 — 2026-11-04
- Redesigned the "From source to consumer" architecture section as an animated, interactive diagram:
  random 0s and 1s flow from sources through Bronze, Silver, Gold and Platinum to the presentation layer, changing colour at each layer.
- Added an Orchestration band (Airflow + Fabric Data Factory) and a OneLake marker to the diagram.
- Added stage tabs and a details panel with each stage's tools. Selecting a stage highlights it; selecting it again returns to the overview.
- Sources: SQL databases, Azure SQL, Dataverse, Oracle, REST APIs, Excel files, CSV files, Parquet files.
- Presentation layer (renamed from Consumers): Power BI, Tableau, QlikView, SSRS reports.
- Diagram switches to a vertical layout on narrow screens; motion is turned off for visitors who prefer reduced motion.
- Added a UTF-8 charset tag so symbols display correctly when the file is hosted outside claude.ai.

## v11 — 2026-11-04 (draft, not approved)
- Removed the auto tour; new sources and presentation tools. Used dots for the flowing data. Replaced by v12; never committed.

## v10 — 2026-11-04 (draft, not approved)
- First draft of the animated architecture diagram with an auto-play tour. Replaced by v11; never committed.

## v9 — 2026-11-03
- Moved the "See projects" and "Get in touch" buttons above "Technologies I use".
- Added the title "From source to consumer" to the architecture diagram.

## v8 — 2026-11-03
- Replaced the location / SC / certification row in the intro with "Technologies I use", a strip of 19 technology logos.
- Added MongoDB, Oracle, Tableau and QlikView logos.

## v7 — 2026-11-03
- Turned the Blog section into a sideways slider with arrow buttons, dots and swipe.
- Added three more "Coming soon" post ideas (six in total).

## v6 — 2026-11-03
- Replaced the "Done before" text on the value cards with "Technologies used" logo rows.

## v5 — 2026-11-03
- Renamed the section heading to "Projects I can add significant value to".

## v4 — 2026-11-03
- Added the "Projects I can add significant value" section below the Blog, with six project types.

## v3 — 2026-11-03
- Removed all company names (employers and the 8x8 vendor) and replaced them with neutral descriptions.

## v2 — 2026-11-03
- Replaced the four results tiles (£400k, 2 wk → 1 hr, ~200, 20+) with a Blog section.
- Added Blog to the menu bar.

## v1 — 2026-11-03
- First version of the portfolio, built from the CV: intro, architecture diagram, results tiles, filterable Projects, Skills, Experience, Certifications & Education, Contact.
