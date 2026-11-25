---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
lang: en
translation_url: /zh/projects/
---

## ZYNQ-7020 GEMM Accelerator

**Overview.** An FPGA-based accelerator exploration project using Vitis HLS on ZYNQ-7020. It focuses on INT8 GEMM, instruction-level control, shared scheduling, and mapping of CNN and Transformer submodules onto a resource-constrained FPGA platform.

**My Contributions.** I worked on accelerator control flows, shared GEMM scheduling, descriptor-based execution for Conv/QKV-related submodules, and functional sanity tests against software reference results.

**Tools / Platform.** ZYNQ-7020, Vitis HLS, Vivado, C/C++, HLS C, Python, AXI-Lite, AXI Master.

**Results or Status.** Ongoing research and engineering exploration. Current baselines include GEMM-only and all-accelerator testing flows; selected large GEMM cases reached around 9-11 MAC/cycle.

## FPGA-based LMS Adaptive Filtering System

**Overview.** A real-time FPGA signal processing system for unknown circuit model exploration, developed as a National Undergraduate Electronic Design Contest project.

**My Contributions.** I worked on FPGA-side signal processing, excitation generation, LMS adaptive filtering, MCU-FPGA cooperation, system integration, and board-level debugging.

**Tools / Platform.** Verilog, Vivado, FPGA, AD/DA timing control, LMS adaptive filtering, MCU-FPGA communication.

**Results or Status.** The project formed a working FPGA-based circuit exploration system and contributed to the 2025 National First Prize in the National Undergraduate Electronic Design Contest.

## AI Titration Automation System

**Overview.** An automated titration system based on computer vision, embedded control, and custom hardware design. It combines visual endpoint detection with closed-loop injection control.

**My Contributions.** I designed the overall hardware architecture, participated in mechanical structure design with SolidWorks and 3D-printed components, worked on the endpoint detection workflow, and integrated host-controller serial communication with embedded control logic.

**Tools / Platform.** Python, PyTorch, customized YOLOv8-based visual model, embedded microcontroller control, serial communication, SolidWorks, 3D printing, hardware prototyping.

**Results or Status.** The prototype detects the titration endpoint and controls reagent delivery automatically.

## Robotic Tic-Tac-Toe

**Overview.** The device plays tic-tac-toe against a person on a physical board. A camera reads the board, a microcontroller selects the next move, and a mechanism driven by stepper and servo motors picks up and places pieces. The device can also restore the board after a piece is moved by mistake.

**My Contributions.** As team lead, I designed and integrated the system and independently developed its Python vision module. I estimated the board pose and mapped the nine squares to image coordinates, then used Lab color statistics to identify the contents of each square. I also helped test the microcontroller logic and the mechanism for moving pieces.

**Tools / Platform.** Python, embedded microcontroller, stepper motors, servo motors.

**Results or Status.** The project won a provincial first prize in the 2024 Jiangsu Undergraduate Electronic Design Contest.
