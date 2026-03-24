---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: Fill in your actual education, skills, and details below -->

Education
======
* **B.S. in [Your Major], [Your University]**, Expected [Graduation Year]
  * Relevant Coursework: Embedded Systems Design, Real-Time Operating Systems, Digital Signal Processing, Computer Architecture, Control Systems, VLSI Design
  * GPA: [X.XX/4.00]

<!-- Uncomment if you have or plan to pursue a graduate degree:
* **M.S. in [Your Major], [Your University]**, Expected [Year]
  * Focus: [Your research focus]
-->

Technical Skills
======
* **Languages**: C, C++, Python, Assembly (ARM, RISC-V), Verilog/VHDL, Rust, MATLAB
* **Microcontrollers & Processors**: STM32, ESP32, MSP430, nRF52, Arduino, Raspberry Pi, RISC-V
* **RTOS & Frameworks**: FreeRTOS, Zephyr, Mbed OS, Arduino Framework, ESP-IDF
* **Protocols & Interfaces**: SPI, I2C, UART, CAN, USB, Ethernet, BLE, Wi-Fi
* **Tools & Equipment**:
  * Debug: JTAG/SWD, GDB, OpenOCD, Segger J-Link, Logic Analyzers, Oscilloscopes
  * Build: CMake, Make, GCC ARM Toolchain, PlatformIO
  * Version Control: Git, GitHub
  * PCB/Hardware: KiCad, Altium Designer, LTSpice
  * CI/CD: GitHub Actions, Jenkins
* **Methodologies**: Agile, Test-Driven Development, MISRA C compliance, Code Review

Work Experience
======
<!-- TODO: Replace with your actual experiences -->

* **[Job Title], [Company Name]** — [Start Date] - [End Date]
  * [What you built, designed, or accomplished - focus on embedded/real-time work]
  * [Quantify impact: latency reduced by X%, power consumption cut by Y%]
  * Technologies: [list relevant tech]

* **[Job Title], [Company Name]** — [Start Date] - [End Date]
  * [Description of work]
  * [Measurable achievement]
  * Technologies: [list relevant tech]

Projects
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Competitions & Awards
======
<!-- TODO: Add your actual competitions and awards here, or they will auto-populate from the competitions collection if you create one -->
* [Competition/Award Name] — [Place/Recognition], [Year]
* [Competition/Award Name] — [Place/Recognition], [Year]

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Leadership & Service
======
<!-- TODO: Replace with your actual involvement -->
* [Club/Organization Name] — [Role], [Dates]
* [Club/Organization Name] — [Role], [Dates]
