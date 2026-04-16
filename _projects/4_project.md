---
layout: page
title: 全向移动机器人平台
description: 基于麦克纳姆轮的灵活移动平台，支持复杂路径规划。
img: assets/img/Omni.png
importance: 3
category: work
---

### 项目概述
本项目设计并制作了一款基于四轮麦克纳姆轮的全向移动机器人，能够实现零半径转向和侧移，适用于狭窄空间的搬运任务。

### 核心技术点
1. **全向移动算法**：实现了基于运动学逆解的四轮速度分解。
2. **嵌入式控制**：采用 STM32 作为主控核心，通过 PID 算法实现对四个电机转速的精确闭环控制。
3. **感知融合**：预留了超声波与激光雷达接口，可扩展自主避障功能。

### 代码结构
```c
// 核心轮速分配代码片段
void Omni_Kinematics(float vx, float vy, float w) {
    target_speed[0] = vx - vy - w * R; // 左前
    target_speed[1] = vx + vy + w * R; // 右前
    // ...
}