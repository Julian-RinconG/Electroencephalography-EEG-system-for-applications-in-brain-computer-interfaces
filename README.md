# Electroencephalography-EEG-system-for-applications-in-brain-computer-interfaces
This repository contains the complete hardware and software ecosystem for an 8-channel (expandable to 16) Electroencephalography (EEG) acquisition system. It was designed as a high-performance, accessible tool for research in Brain-Computer Interfaces (BCI).

## 🛠 Tech Stack
* **Hardware:** Texas Instruments ADS1299 (24-bit ADC), ESP32-C3 SoC, 4-layer Custom PCB.
* **Firmware:** ESP-IDF (C/C++), SPI communication, Dual-link (UART/BLE).
* **Software:** Python 3, PyQt5, PyQtGraph, NumPy, SciPy.

## ✨ Key Features
* **High Fidelity:** 24-bit resolution with -110 dB CMRR for clean biopotential capture.
* **Real-Time DSP:** Integrated filter designer for visualization with Live configurable FFT/PSD.
* **High Throughput:** Stable 250-1000 SPS sampling rates via multithreaded architecture.
* **Ultra Low-Cost:** Total BOM under $350 USD.
* **Portability:** Compact wearable form factor with limited consume (38 mA Serial - 58 mA BLE).

## 📂 Repository Structure
* `/Hardware`: Altium Designer files (schematics, layout).
* `/Firmware`: ESP32-C3 source code and SPI drivers.
* `/Software`: Python GUI and real-time processing scripts.
