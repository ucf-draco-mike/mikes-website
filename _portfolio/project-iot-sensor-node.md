---
title: "Low-Power IoT Sensor Node"
excerpt: "Battery-powered wireless sensor node with custom PCB — BLE mesh, sleep modes, 2+ year battery life<br/><img src='/images/500x300.png'>"
collection: portfolio
order: 4
---

<!-- TODO: Replace all placeholder content with your actual project details -->

## Overview

[What does this sensor node measure? Where is it deployed? Why low power?]

## Hardware Design

- **MCU**: [nRF52840 / STM32L4 / ESP32-S3]
- **Sensors**: [temp, humidity, accelerometer, etc.]
- **Power**: [Battery type, voltage regulator, solar harvesting?]
- **PCB**: [Designed in KiCad/Altium, X-layer board, dimensions]
- **Wireless**: [BLE 5.0 / LoRa / Zigbee / Wi-Fi]

## Firmware Architecture

- **RTOS/Scheduler**: [Zephyr / FreeRTOS / bare-metal superloop]
- **Power Management**: [Sleep modes, wake sources, duty cycling strategy]
- **Communication Stack**: [BLE GATT services, MQTT, custom protocol]
- **OTA Updates**: [How firmware updates are delivered]

## Power Budget

| State         | Current Draw | Duration   | Duty Cycle |
|---------------|-------------|------------|------------|
| Deep Sleep    | [X μA]      | [X sec]    | [X%]       |
| Sensor Read   | [X mA]      | [X ms]     | [X%]       |
| BLE Transmit  | [X mA]      | [X ms]     | [X%]       |
| **Average**   | **[X μA]**  |            |            |

**Estimated Battery Life**: [X years] on [battery spec]

## Results

- [Battery life achieved vs. target]
- [Range/reliability of wireless link]
- [Any deployment outcomes]

## Links

- [GitHub Repository](#) <!-- TODO -->
- [Schematic / PCB Layout](#) <!-- TODO -->
