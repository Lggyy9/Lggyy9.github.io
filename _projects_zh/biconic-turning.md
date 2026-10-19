---
layout: page
title: "大口径双锥面镜的补偿式单点金刚石车削"
description: "面向高精度大口径双锥面镜制造，采用LUPHOScan对加工后表面进行测量，根据测量结果计算加工误差，开发算法生成新的补偿后的刀具路径，提高表面加工精度。"
img: assets/img/projects/biconic-turning-cover.png
importance: 2
---


<div class="row">
    <div class="col-12">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-cover.png" alt="超精密金刚石车床（左）与LUPHOScan光学轮廓仪（右）" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**面向产业的工程项目** | 2026年4月 – 2026年7月 | 角色：主要完成人

**关键词：** 慢刀伺服单点金刚石车削 · LUPHOScan光学轮廓仪 · 双方向曲率误差小于1% · RMSi小于30 nm

- 主导了双锥面光学元件生产加工中系统性面形误差的诊断，并制定了相应的补偿策略。
- 针对不同误差形态，开发了特征化的面形误差拟合算法，以较低的拟合残差准确表达实测面形误差。
- 为不同设计参数的双锥面生成补偿后的刀具路径，并支持其在超精密金刚石车削生产中的实施。
- 开发了误差源识别、面形误差拟合和补偿刀具路径生成的核心动态链接库，并集成到面向生产的软件系统中，交付实验室工程师日常使用。

<div class="row">
    <div class="col-12 col-md-6 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-before.jpg" alt="补偿前：加工后双锥面的LuphoScan测量结果（偏差图、三维视图、轮廓与面形误差统计）" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-12 col-md-6 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-after.jpg" alt="补偿后：同一双锥面的LuphoScan测量结果" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    某双锥面补偿加工前（左）、后（右）的LuphoScan面形测量结果：偏差图、X/Y方向轮廓和面形误差统计。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-software-pathplan.png" alt="CAM软件截图：刀具路径规划窗口" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    CAM软件中的刀具路径规划：双锥面工件与工艺参数、带螺旋刀具路径的曲面模型，以及规划的X/Z轴运动和刀刃接触角。
</div>
<div class="row">
    <div class="col-12 mt-3">
        {% include figure.liquid loading="eager" path="assets/img/projects/biconic-turning-software-compensation.png" alt="CAM软件截图：路径补偿窗口" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    同一软件中的路径补偿：导入测量数据、计算面形误差、用正弦谐波叠加拟合并导出补偿后的刀具路径；各面板依次为误差图、拟合点云和拟合残差。
</div>
