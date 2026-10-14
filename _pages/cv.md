---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/CV.pdf # PDF download button next to the page title (compiled from CV.md, see CLAUDE.md)
cv_format: rendercv # options: rendercv, jsonresume
# description: # optional one-line description shown under the page title (none for now)
toc:
  sidebar: left
# Page-only style. al_folio_core 1.0.15 ships a prebuilt tailwind.css without the `.list-group` rules the CV layout relies on (they were tree-shaken out),
# so every CV entry showed a bullet dot, and the template's generic `table:not(.table) td { border-top }` put a line above each date badge.
_styles: >
  .cv ul.list-group { list-style: none; margin: 0; padding: 0; }
  .cv .list-group-item { list-style: none; }
  .cv table.table-cv td, .cv table.table-cv th { border-top: 0; }
---
