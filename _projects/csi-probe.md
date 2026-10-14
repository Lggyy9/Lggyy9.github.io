---
layout: page
title: "Development of a Coherence Scanning Interferometry Probe for Optical Profilometry"
description: "Contributed to the development of a compact coherence scanning interferometry probe for an optical profilometer, responsible for algorithm development, software integration, and hands-on testing."
img: assets/img/projects/csi-probe-cover.png
importance: 1
related_publications: true
---

{% comment %} Source: the owner's project summary (info.md); wording approved by the owner on 2026-10-14. This is a Liquid comment: it is dropped at build time (an HTML comment would show up in the published page source). {% endcomment %}

<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-cover.png" alt="System overview drawing with the CSI probe highlighted (magnified view at lower left)" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**Industry-Sponsored Project** | Nov. 2024 – Nov. 2025 | Role: Contributor (algorithm development, software integration, and hands-on testing)

Based on a Mirau-type compact optical structure, a least-squares iterative algorithm was used to address machine-induced vibration, yielding a coherence scanning interferometry probe suitable for optical profilometers.

- Developed dynamic-link libraries for instrument control and software integration, including image acquisition, scanning control, topography reconstruction, data reprocessing, and surface-roughness evaluation.
- Integrated the algorithmic and software components with the probe hardware and carried out hands-on testing, contributing to the successful delivery of a functional CSI probe for an optical profilometer.
- Participated in the component selection of a compact CSI probe integrating broadband illumination, piezoelectric vertical scanning, an interferometric objective, and industrial-camera acquisition, building on the laboratory's earlier hardware development.
- Independently designed and conducted exploratory microsphere-assisted CSI experiments for enhanced lateral-resolution measurement and identified limitations in microsphere manipulation, experimental stability, and forward-model validation.

{% comment %} The two screenshots are stacked (one per row) on purpose: side by side they would be ~435 px wide and the interface text unreadable. {% endcomment %}
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-software-1.png" alt="Screenshot of the profiler software: measurement workspace" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Control software of the optical profilometer: the surface-measurement workspace with motion-control and white-light sensor panels (software interface in Chinese).
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-software-2.png" alt="Screenshot of the profiler software: roughness evaluation" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Roughness evaluation in the same software: 3D and top-view maps, areal parameters (Sa, Sq, Sz) and a profile (software interface in Chinese).
</div>

**Related publication:** {% cite lyu2026coherence %}
