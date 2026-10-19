---
layout: page
permalink: /zh/publications/
title: 论文
nav: true
nav_order: 2
---

<script src="{{ '/assets/js/bibsearch.js' | relative_url | bust_file_cache }}" type="module"></script>
<input type="text" id="bibsearch" spellcheck="false" autocomplete="off" class="search bibsearch-form-input" placeholder="{{ site.data.i18n['zh-CN'].filter_placeholder }}">

<div class="publications">

{% bibliography --template bib_zh %}

</div>
