---
layout: page
title: "面向光学轮廓测量的白光干涉测头设计与开发"
description: "面向光学轮廓仪，开发紧凑（compact）型的白光干涉测头，负责算法开发、软件集成与实操测试。"
img: assets/img/projects/csi-probe-cover.png
importance: 1
---


<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-cover.png" alt="系统总览图，高亮部分为白光干涉测头（左下为放大图）" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**横向项目** | 2024年11月 – 2025年11月 | 角色：参与（算法开发、软件集成与实操测试）

基于Mirau型紧凑光路结构，采用最小二乘迭代算法解决机台振动问题，开发了适用于光学轮廓仪的白光干涉测头。

- 开发了用于仪器控制与软件集成的动态链接库，涵盖图像采集、扫描控制、形貌重建、数据再处理和表面粗糙度评价。
- 将算法与软件部分同测头硬件集成并开展实操测试，为光学轮廓仪成功交付功能完整的白光干涉测头做出贡献。
- 参与了紧凑型白光干涉测头的元器件选型（宽光谱点光源、压电陶瓷位移器、干涉物镜和工业相机采集），工作基于实验室前期的硬件研发基础。
- 独立设计并开展了微球辅助白光干涉的探索性实验，以提升横向分辨率，并指出了微球操控、实验稳定性和正向模型验证方面的局限。

<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-software-1.png" alt="光学轮廓仪软件截图：测量工作区" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    光学轮廓仪控制软件：表面测量工作区，含运动控制与白光传感器面板。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/csi-probe-software-2.png" alt="光学轮廓仪软件截图：粗糙度评价" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    同一软件中的粗糙度评价：三维图与俯视图、面粗糙度参数（Sa、Sq、Sz）及轮廓曲线。
</div>

<h2>{{ site.data.i18n['zh-CN'].references }}</h2>
<div class="publications">
  {% cite lyu2026coherence %}
  {% bibliography --cited_in_order --template bib_zh %}
</div>
