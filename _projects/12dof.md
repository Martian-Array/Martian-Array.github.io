---
layout: page
title: 12-DOF Quadruped Robot (Latest)
description: The first quadruped robot in CURC to achieve knee-elbow conversion via rigid linkages.
img: assets/img/神奇的双连杆.png
importance: 2
category: work
---

### 项目概述
本项目设计了一款12DOF的四足机器人。采用双连杆传动机构，从本体设计到运控、感知方案做了较大革新。

### 核心创新
1. **轴向错位双连杆传动**：设计了一套新型的传动机构，可完全规避连杆死点，将小腿运动范围提升至普通四足机器人的两倍。
2. **可靠快拆设计**：设计径向拆装结构，综合PPA FDM技术、TC4钛合金SLS技术实现多材料整合。
3. **强化运控**：针对高运动性能需求，部署强化学习的策略进行上游运动控制。

### 功能展示
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/腿姿变换.png" title="机器人可实现的四种腿部姿态" class="img-fluid rounded z-depth-1" %}
    </div>    
</div>

<div class="caption">
    Comparison of Joint Configurations for Quadrupedal Locomotion
</div>

### CAD
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/塞北箭.png" title="机器人三维设计图" class="img-fluid rounded z-depth-1" %}
    </div>    
</div>

### 实物展示
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/实拍润色图.png" title="机器人实拍图" class="img-fluid rounded z-depth-1" %}
    </div>    
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/布线后.png" title="机器人实拍" class="img-fluid rounded z-depth-1" %}
    </div>    
</div>

---

### 🛠️ 技术文档
* [中南大学EK战队四足技术介绍（2026.2）](/assets/pdf/中南大学EK战队四足技术介绍（2026.2）.pdf)