---
layout: page
title: "Compensation Single-Point Diamond Turning of Large Aperture Biconic Optical Surfaces"
description: "For the fabrication of high-precision, large-aperture biconic mirrors, the machined surface is measured with a LUPHOScan, the machining error is calculated from the measurement results, and algorithms were developed to generate a new, compensated tool path that improves surface accuracy."
img: assets/img/projects/biconic-turning-cover.png
importance: 2
---

{% comment %} Source: the owner's project summary (info.md); wording approved by the owner on 2026-10-14. The project has no paper, so there is no related_publications / cite. This is a Liquid comment: it is dropped at build time (an HTML comment would show up in the published page source). {% endcomment %}

<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-cover.png" alt="Ultra-precision diamond-turning lathe (left) and LUPHOScan optical profilometer (right)" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**Industry-Facing Engineering Project** | Apr. 2026 – Jul. 2026 | Role: Key Contributor

**Keywords:** slow-tool-servo single-point diamond turning · LUPHOScan optical profilometer · curvature error below 1% in both directions · RMSi below 30 nm

- Led the diagnosis of systematic surface-form errors in the production machining of biconic optical components and established corresponding compensation strategies.
- Developed feature-specific surface-error fitting algorithms for different error morphologies, enabling accurate representation of measured form errors with low fitting residuals.
- Generated compensated tool paths for biconic surfaces with varying design parameters and supported their implementation in ultra-precision diamond-turning production.
- Developed the core dynamic-link libraries for error-source identification, surface-error fitting, and compensated tool-path generation, which were integrated into a production-oriented software system delivered for routine use by laboratory engineers.

{% comment %}
  The before/after pair sits side by side on purpose (it is meant to be compared); click an image to zoom. The two software screenshots are stacked
  (one per row) like in the CSI project, because side by side the interface text would be unreadable.
{% endcomment %}
<div class="row">
    <div class="col-12 col-md-6 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-before.jpg" alt="LuphoScan measurement of a machined biconic surface before compensation: deviation map, 3D view, profiles and form-error statistics" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-12 col-md-6 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-after.jpg" alt="LuphoScan measurement of the same biconic surface after compensation" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    LuphoScan form measurements of an example biconic surface before (left) and after (right) compensated machining: deviation maps, X/Y profiles and form-error statistics.
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-software-pathplan.png" alt="Screenshot of the CAM software: tool-path planning window" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Tool-path planning in the CAM software: biconic workpiece and process parameters, the surface model with its spiral tool path, and the planned X/Z-axis motion and tool-edge contact angles (software interface in Chinese).
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-software-compensation.png" alt="Screenshot of the CAM software: path-compensation window" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Path compensation in the same software: load the measured data, calculate the form error, fit it with a sinusoidal-harmonic superposition and export the compensated tool path; the panels show the error map, the fitted point cloud and the fit residual (software interface in Chinese).
</div>
