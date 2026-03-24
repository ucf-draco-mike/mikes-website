---
title: "RTOS-Based Flight Controller"
excerpt: "Hard real-time flight controller on STM32 with sensor fusion and PID control at 1kHz<br/><img src='/images/500x300.png'>"
collection: portfolio
order: 1
---

<!-- TODO: Replace all placeholder content with your actual project details -->

## Overview

[1-2 sentence summary of the project. What does it do and why does it matter?]

## Technical Architecture

- **MCU**: STM32F4 / STM32H7
- **RTOS**: FreeRTOS with priority-based preemptive scheduling
- **Sensors**: IMU (MPU6050/ICM-20948), barometer (BMP280), GPS (u-blox NEO-M8N)
- **Control Loop**: Cascaded PID running at 1kHz on a dedicated high-priority task
- **Communication**: MAVLink over UART, SPI for sensor buses

## Key Design Decisions

<!-- TODO: Describe the hard technical decisions you made and why -->

- **Sensor Fusion**: [Describe your approach — complementary filter, Kalman filter, etc.]
- **Task Architecture**: [How did you partition tasks? What priority scheme?]
- **Timing Guarantees**: [How did you ensure hard real-time deadlines?]

## Results

- [Quantified result — e.g., "Achieved deterministic 1kHz loop rate with <5μs jitter"]
- [Another result — e.g., "Stable hover within ±2cm altitude hold"]

## What I Learned

[1-2 sentences on the key takeaway — what would you do differently?]

## Links

- [GitHub Repository](#) <!-- TODO: Add your repo link -->
- [Demo Video](#) <!-- TODO: Add if available -->
