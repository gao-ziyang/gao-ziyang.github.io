---
layout: single
title: "项目"
permalink: /zh/projects/
author_profile: true
lang: zh
translation_url: /projects/
---

这里列出若干代表性工程与研究探索项目。公开代码、图示和技术报告会在材料整理与脱敏后逐步补充。

## ZYNQ-7020 GEMM Accelerator

**项目概述。** 基于 ZYNQ-7020 与 Vitis HLS 的 FPGA 加速器探索项目，关注 INT8 GEMM、指令级控制、共享调度，以及 CNN 和 Transformer 相关子模块在资源受限 FPGA 平台上的映射。

**个人贡献。** 我参与了加速器控制流设计、共享 GEMM 调度、Conv/QKV 相关子模块的描述符式执行，以及与软件参考结果对比的功能正确性测试。

**工具 / 平台。** ZYNQ-7020、Vitis HLS、Vivado、C/C++、HLS C、Python、AXI-Lite、AXI Master。

**结果 / 状态。** 这是一个仍在推进的研究与工程探索项目。目前已有 GEMM-only 和 all-accelerator 测试流程；部分大规模 GEMM case 达到约 9-11 MAC/cycle。

## FPGA-based LMS Adaptive Filtering System

**项目概述。** 面向未知电路模型探索的实时 FPGA 信号处理系统，来源于全国大学生电子设计竞赛项目。

**个人贡献。** 我参与 FPGA 侧信号处理、激励生成、LMS 自适应滤波、MCU-FPGA 协同、系统集成和板级调试。

**工具 / 平台。** Verilog、Vivado、FPGA、AD/DA 时序控制、LMS 自适应滤波、STM32 / MCU-FPGA 通信。

**结果 / 状态。** 项目形成了可工作的 FPGA 电路探索与实时信号处理系统，并支撑了全国大学生电子设计竞赛 2025 年全国一等奖成果。

## AI Titration Automation System

**项目概述。** 基于计算机视觉、嵌入式控制和自定义硬件架构的自动滴定系统，将视觉终点检测与闭环注射控制结合。

**个人贡献。** 我负责整体硬件架构设计，参与 SolidWorks 机械结构设计与 3D 打印部件制作，完成视觉终点检测流程与主机-控制器串口通信、嵌入式控制逻辑之间的系统集成。

**工具 / 平台。** Python、PyTorch、定制 YOLOv8 视觉模型、嵌入式微控制器、串口通信、SolidWorks、3D 打印、硬件原型搭建。

**结果 / 状态。** 这是一个面向实验自动化的 AI + 硬件系统原型；公开代码、整理后的图片和详细技术材料暂未发布。
