---
layout: page
title: XHand Exoskeleton
description: Based on the open-source project DexUMI, with the core goal of implementing teleoperation (master-slave) conversion via DAgger.
img: assets/img/exohand1.png
importance: 4
category: work
---

### 项目概述
基于DexUMI的开源项目，本项目为XHand灵巧手的外骨骼添加了12个主动自由度。通过直驱与锥齿轮传动的结合，实现了手部外骨骼的主动驱动。在需要专家介入遥操时，外骨骼设备可直接运动至手部同一位置，实现丝滑接管。项目在清华大学智能产业研究院（AIR）完成，由智源学者<a href="https://sites.google.com/view/fromandto/">赵昊</a>指导。

### 核心创新
1. **锥齿轮紧凑传动**：采用锥齿轮传动方案，在极小的空间内完成中指和无名指的传动。
2. **混合驱动设计**：因直驱更容易保留原始纯净的数据，故优先使用直接驱动的方式，而在空间极度受限区域使用齿轮传动。
3. **人因工程**：综合XHand SDK手部数据与一般人手尺寸数据设计，实现外骨骼舒适佩戴。

### 实物展示
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/onhand.png" title="外骨骼佩戴在手上的实物照片" class="img-fluid rounded z-depth-1" style="max-width: 30%;" %}
       <h6 class="mt-2 text-muted font-weight-light">外骨骼佩戴在手上的实物照片</h6>
    </div>    
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/双手实物图片.png" title="外骨骼佩戴在手上的实物照片" class="img-fluid rounded z-depth-1" style="max-width: 30%;" %}
       <h6 class="mt-2 text-muted font-weight-light">双手实物图片</h6>
    </div>    
</div>
### 项目成果
AIR冬令营项目，拟投稿ICRA 2027

---

