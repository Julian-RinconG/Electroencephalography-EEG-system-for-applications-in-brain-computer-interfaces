# Low-Cost EEG Acquisition System for BCI Research

A high-performance, open-source 8-channel EEG acquisition system designed for Brain-Computer Interface (BCI) applications. This project offers a medical-grade precision alternative at a fraction of the cost of commercial devices.

## 🛠 Tech Stack
* [cite_start]**Hardware:** Texas Instruments ADS1299 (24-bit ADC), ESP32-C3 SoC, 4-layer Custom PCB.
* [cite_start]**Firmware:** ESP-IDF (C/C++), SPI communication, Dual-link (UART/BLE).
* [cite_start]**Software:** Python 3, PyQt5, PyQtGraph, NumPy, SciPy.

## ✨ Key Features
* [cite_start]**High Fidelity:** 24-bit resolution with -110 dB CMRR for clean biopotential capture.
* [cite_start]**Real-Time DSP:** Integrated filter designer for visualization with Live configurable FFT/PSD.
* [cite_start]**Data Management:** Export raw and filtered signals to CSV format, compatible with tools like MATLAB and EEGLAB.
* [cite_start]**High Throughput:** Stable 250-1000 SPS sampling rates via multithreaded architecture.
* [cite_start]**Ultra Low-Cost:** Total BOM under $350 USD (approx. 5% of high-end commercial equivalents).
* [cite_start]**Portability:** Compact wearable with low consumption (38 mA Serial / 58 mA BLE).

## 📂 Repository Structure
* [cite_start]`/Hardware`: Altium Designer files (schematics, layout)[cite: 758].
* [cite_start]`/Firmware`: ESP32-C3 source code and SPI drivers[cite: 1011, 1016].
* [cite_start]`/Software`: Python GUI and real-time processing scripts[cite: 1231, 1248].

## ⚖️ License
[cite_start]This project was developed as an Undergraduate Thesis at **Pontificia Universidad Javeriana**.
