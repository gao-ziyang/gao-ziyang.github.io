---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

# Projects

This page lists selected engineering and research-oriented projects. Detailed repositories, figures, and technical reports will be added after public materials are cleaned and organized.

## ZYNQ-7020 GEMM / Attention Accelerator

**Overview.** An FPGA-based accelerator exploration project using Vitis HLS on ZYNQ-7020. It focuses on INT8 GEMM, attention-related computation, instruction-level control, and mapping of CNN and Transformer submodules onto a resource-constrained FPGA platform.

**My Contributions.** I worked on accelerator control flows, shared GEMM scheduling, descriptor-based execution for Conv/QKV/Attention submodules, and functional sanity tests against software reference results.

**Tools / Platform.** ZYNQ-7020, Vitis HLS, Vivado, C/C++, HLS C, Python, AXI-Lite, AXI Master.

**Results or Status.** Ongoing research and engineering exploration. Current baselines include GEMM-only and all-accelerator testing flows; selected large GEMM cases reached around 9-11 MAC/cycle, and one attention sanity case reached `mismatch_count=0` and `max_abs_error=0`.

## FPGA-based LMS Adaptive Filtering and DDS System

**Overview.** A real-time FPGA signal processing system for unknown circuit model exploration, developed as a National Undergraduate Electronic Design Contest project.

**My Contributions.** I worked on FPGA-side signal processing, DDS excitation generation, LMS adaptive filtering, MCU-FPGA cooperation, system integration, and board-level debugging.

**Tools / Platform.** Verilog, Vivado, FPGA, DDS, AD/DA timing control, LMS adaptive filtering, STM32 / MCU-FPGA communication.

**Results or Status.** The project formed a working FPGA-based circuit exploration system and contributed to the 2025 National First Prize in the National Undergraduate Electronic Design Contest.

## AI Titration Automation System

**Overview.** An automated titration system based on computer vision and embedded control. It combines visual endpoint detection with closed-loop injection control.

**My Contributions.** I worked on the endpoint detection workflow, host-controller serial communication, and system-level testing between AI perception and embedded actuation.

**Tools / Platform.** Python, PyTorch, customized YOLOv8-based visual model, embedded microcontroller control, serial communication.

**Results or Status.** Applied AI and automation prototype; public code and cleaned figures are not yet posted.
