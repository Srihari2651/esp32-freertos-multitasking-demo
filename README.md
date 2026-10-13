# ESP32 FreeRTOS Multitasking Demo

A fundamental FreeRTOS demonstration on the ESP32 demonstrating concurrent task execution without using standard `delay()` blocking mechanisms.

## 📌 Project Overview
This project demonstrates how to leverage the built-in FreeRTOS kernel on the ESP32 using the Arduino framework to run two concurrent tasks:
- **Task 1**: Sensor Monitoring task scheduled every **1000 ms**.
- **Task 2**: System Monitoring task scheduled every **2000 ms**.

## 🛠️ Hardware & Tools
- **Microcontroller**: ESP32 Development Board
- **IDE**: Arduino IDE
- **Core Framework**: ESP32 Arduino Core (FreeRTOS)

## 📊 Output
![Serial Monitor Output](image_b1e8f9.png)

## 🚀 Key Concepts Covered
- Creating RTOS tasks with `xTaskCreate()`
- Non-blocking delays with `vTaskDelay()` and `pdMS_TO_TICKS()`
- Multi-task execution using the ESP32 dual-core scheduler
<img width="1600" height="894" alt="WhatsApp Image 2026-10-13 at 2 11 41 PM" src="https://github.com/user-attachments/assets/e62267e3-6bda-433b-8c91-3b4084f92d08" />
