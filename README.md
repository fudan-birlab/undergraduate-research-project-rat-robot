# 本科生科研项目：小鼠仿生机器人
## 项目概述

本课题面向具身智能与仿生机器人研究，以小鼠仿生机器人为实践对象，围绕硬件搭建、仿真建模和运动控制三个环节，逐步实现从机器人平台构建到智能控制验证的完整流程。

目标是完成可运行、可调试的小鼠仿生机器人平台，为后续仿真建模、智能控制与真机验证提供基础。

## 主要方向

1. 小鼠机器人搭建
2. CAD 机器人结构设计与搭建
3. 强化学习运动控制

## 需要学习的基础知识

- 机械：结构、装配、传动、材料与加工
- 电子电路：供电、驱动、电路连接和硬件调试
- 嵌入式：控制器、通信、烧录、底层接口
- 运控算法：强化学习、闭环调节
- 传感器/电机：采集、标定、滤波、电机测试

## 方向一：小鼠机器人搭建

- 完成小鼠机器人硬件搭建，包括接线、供电、控制器和传感器连接。
- 调试机器人，帮助部署运动控制算法。
- 根据部署效果对机器人进行调试与修改。

## 方向二：机器人结构设计与 CAD 建模

- 学习 SolidWorks、Onshape 等 3D 建模工具，选择其中一种即可。
- 对小鼠仿生机器人进行建模。
- 探索 AI 生成 CAD 文件的方法。
- 探索模拟器中关节参数、域随机化参数等参数的 AI 辅助确定方法。

## 方向三：强化学习运动控制

- 研究基于深度强化学习（DRL）的运动控制算法。
- 训练小鼠机器人的运动策略。
- 后续部署到真机，完成 Sim2Real 调试，并根据真机表现修正算法。

## 学习资料

### 小鼠仿生机器人模型论文

所有同学需要熟悉：

> Bing, Zhenshan, et al. "Lateral flexion of a compliant spine improves motor performance in a bioinspired mouse robot." Science Robotics 8.85 (2023): eadg7165.

### 建模软件学习

- SolidWorks 或类似建模软件教学：<https://www.bilibili.com/video/BV16nQoBdESy/>
- 也可以选择其他 B 站教学视频或 Onshape 相关教程。

### 强化学习运动控制算法学习

- <https://github.com/google-deepmind/mujoco_playground>
- <https://github.com/Hellod035/LeggedLab>

### 嵌入式与电子电路

相关 PPT 和资料见本仓库的 `materials/` 目录。

## 仓库文件

- `project-learning-content-and-direction.pptx`：第一次线下会议/项目学习内容与方向 PPT
- `materials/USB拓展坞焊接.pptx`
- `materials/天气时钟焊接.pptx`
- `materials/直插时钟焊接.pdf`
- `materials/锡焊技能.pptx`
- `materials/Archive/`：由原始 `Archive.zip` 解压得到的嵌入式与电子电路补充资料

说明：原始压缩包 `Archive.zip` 本身不上传；其解压后的资料文件上传到 `materials/Archive/`。

## 学习情况记录表
【腾讯文档】小鼠机器人项目学习进度表
- https://docs.qq.com/sheet/DSkZ1TVdJYVdobG54
