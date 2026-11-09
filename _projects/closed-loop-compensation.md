---
layout: page
title: "A closed-loop compensatory manufacturing process for monolithic multi-mirror systems guided by optical performance"
description: "An optical-performance-guided closed-loop compensation framework for monolithic multi-mirror optical systems (MMOSs): in-situ wavefront measurement, ray-tracing-based optimization and single-point diamond-turning tool paths are linked in a closed loop, reducing the system wavefront-aberration RMS by 90% and reaching diffraction-limited performance."
img: assets/img/projects/closed-loop-cover.jpg
importance: 1
related_publications: true
---

{% comment %}
  Full page (replaces the earlier stub with the same slug). Figures 10, 1, 2, 7, 15 and 16 of the published paper; captions are the paper's own captions
  (cover = Fig. 10, body = Figs. 1, 2, 7, 15, 16 in paper order). In the Fig. 1 and Fig. 10 captions the abbreviations MMOSs / DMS / WFA are expanded at first use (the owner allowed this).
  Bullets, role and keywords are the owner's approved text; "manuscript" was changed to "paper" at his request (2026-11-09).
  PENDING-APPROVAL: "(co-first author)" appended to the Role line (drafted from his request to highlight co-first authorship); the expansion "multi-mirror optical systems (MMOSs)" in the Fig. 1 caption.
{% endcomment %}

<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-cover.jpg" alt="Experimental setup of the monolithic dual-mirror system: machining fixtures on the diamond-turning machine, a CAD view of the fixture and the on-machine laser interferometer" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Experimental Setup (a) Optical path of the off-axis dual-mirror system (DMS); (b) Layout of the machine tool used in the experiment; (c) Monolithic machining process; (d) Structure of the on-machine measurement fixture; (e) Overall hardware layout.
</div>

**Lab-Initiated Research Project** | Dec. 2025 – Aug. 2026 | Role: Key Contributor (co-first author)

**Keywords:** single-point diamond turning · in-situ wavefront measurement · closed-loop compensation manufacturing · monolithic machining

- Led the experimental implementation and metrology of a closed-loop compensation process for a monolithic dual-reflector optical system manufactured by single-point diamond turning.
- Developed and executed a Zemax ZOS-API workflow to simulate the propagation of measured surface errors and evaluate candidate compensation strategies in terms of system-level optical performance.
- Processed and analyzed machining, surface-metrology, and optical-performance data to evaluate the effectiveness of the compensation method. Reduced the system wavefront error RMS by 90% after compensation iteration, experimentally validating the effectiveness of the optical-performance-guided compensation framework.
- Consolidated the simulation and experimental results and led the preparation of the resulting co-first-author paper.

{% comment %} Wide figures are stacked (one per row): side by side the figure text would be unreadable. {% endcomment %}
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-paradigm.jpg" alt="Four phases of the multi-mirror optical system manufacturing paradigm: separate machining, partly monolithic machining and monolithic machining, leading to alignment-free, high-performance manufacturing" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The development of the multi-mirror optical systems (MMOSs) manufacturing paradigm.
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-framework.jpg" alt="Compensatory manufacturing optimization process of multi-mirror systems, compared with the traditional manufacturing-then-alignment process" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Compensatory manufacturing optimization process of MMOSs.
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-simulation.jpg" alt="Flowchart of the iterative MATLAB and Zemax simulation workflow" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Complete iterative simulation workflow
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-iterations.jpg" alt="Wavefront aberration maps with PV and RMS values after the first, second and third compensation machining cycles" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The wavefront aberration (WFA) distribution after three compensation machining cycles (a) The WFA distribution after the first compensation machining; (b) The WFA distribution after the second compensation machining; (c) The WFA distribution after the third compensation machining.
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-results.jpg" alt="Wavefront aberration maps with PV and RMS values over successive compensation iterations in repeatability experiments A and B" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The WFA distribution in repeatability experiments (a) Results of Experiment A; (b) Results of Experiment B.
</div>

**Related publication:** {% cite liu2026closed %}
