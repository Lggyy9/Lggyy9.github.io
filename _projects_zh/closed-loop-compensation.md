---
layout: page
title: "光学性能引导的共体多反系统闭环补偿制造"
description: "面向共体多反系统（MMOSs）的光学性能引导闭环补偿制造框架：将原位波前测量、基于光线追迹的优化与单点金刚石车削刀具路径闭环联动，使系统波前像差RMS降低90%，达到衍射极限的光学性能。"
img: assets/img/projects/closed-loop-cover.jpg
importance: 1
---

{% comment %}
  Chinese version of _projects/closed-loop-compensation.md (same figures). Text approved by the owner on 2026-11-09 (review sheet 03_closed_loop_paper).
  Captions are translations of the paper's own captions; MMOSs is rendered as 共体多反系统（MMOSs）, as the owner decided.
{% endcomment %}

<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-cover.jpg" alt="共体双反射镜系统的实验装置：金刚石车床上的加工夹具、夹具的CAD视图和在机激光干涉仪" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    实验装置 (a) 离轴双反射镜系统（DMS）光路；(b) 实验所用机床布局；(c) 共体加工过程；(d) 在机测量夹具结构；(e) 整体硬件布局。
</div>

**实验室内部项目** | 2025年12月 – 2026年8月 | 角色：主要完成人（共同第一作者）

**关键词：** 单点金刚石车削 · 原位波前测量 · 闭环补偿制造 · 共体加工

- 主导了由单点金刚石车削加工的共体双反射镜光学系统闭环补偿流程的实验实施与测量。
- 开发并运行了基于Zemax ZOS-API的工作流，仿真实测面形误差的传播，并从系统级光学性能角度评估候选补偿策略。
- 处理并分析了加工、面形测量和光学性能数据，以评估补偿方法的有效性。补偿迭代后将系统波前误差RMS降低90%，通过实验验证了光学性能引导补偿框架的有效性。
- 整合仿真与实验结果，并主导了由此形成的共同第一作者论文的撰写。

<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-paradigm.jpg" alt="多反系统制造范式的四个阶段：分体加工、部分共体加工和共体加工，最终实现免装调的高性能制造" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    共体多反系统（MMOSs）制造范式的发展。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-framework.jpg" alt="多反系统的补偿式制造优化流程，与传统的“先制造后装调”流程对比" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    MMOSs 的补偿式制造优化流程。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-simulation.jpg" alt="MATLAB与Zemax迭代仿真流程图" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    完整的迭代仿真流程。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-iterations.jpg" alt="第一、二、三轮补偿加工后的波前像差分布图，含PV与RMS值" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    三轮补偿加工后的波前像差（WFA）分布 (a) 第一次补偿加工后的WFA分布；(b) 第二次补偿加工后的WFA分布；(c) 第三次补偿加工后的WFA分布。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/closed-loop-results.jpg" alt="重复性实验A和B中各补偿迭代的波前像差分布图，含PV与RMS值" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    重复性实验中的WFA分布 (a) 实验A的结果；(b) 实验B的结果。
</div>

<h2>{{ site.data.i18n['zh-CN'].references }}</h2>
<div class="publications">
  {% cite liu2026closed %}
  {% bibliography --cited_in_order --template bib_zh %}
</div>
