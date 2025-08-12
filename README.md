# DHT22 Temperature & Humidity Plotter (MATLAB App Designer)

🌐 This README is also available in Spanish 🇪🇸: [README.es.md](README.es.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/DHT22-Temperature-and-Humidity-Plotter-MATLAB-App)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/DHT22-Temperature-and-Humidity-Plotter-MATLAB-App)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/DHT22-Temperature-and-Humidity-Plotter-MATLAB-App/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FDHT22-Temperature-and-Humidity-Plotter-MATLAB-App%2Fmain%2Freport%2Fbadge%2Ftested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Top language](https://img.shields.io/github/languages/top/adriancrc/DHT22-Temperature-and-Humidity-Plotter-MATLAB-App?label=Top%20Language&color=blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)

---

## About

MATLAB App Designer project that **reads a DHT22 sensor via Arduino** and **plots temperature (°C) and relative humidity (%) in real time**.  
This repository shares the **complete source code** as a **collaborative project**, inviting community contributions for improvements, optimizations, and new features.

---

## Summary (140 characters)

Real‑time DHT22 temperature & humidity plotting with MATLAB App Designer and Arduino, open and collaborative for community improvements.

---

## Description

**Features**
- Live plots for temperature and relative humidity
- Numeric indicators (°C and %RH)
- Toggles to start/stop each channel
- Serial port selector (COM1–COM7) with status lamps
- Responsive layout (auto‑reflow)

**Requirements**
- MATLAB R2021a or later
- MATLAB Support Package for Arduino Hardware
- Adafruit DHT22 library (via MATLAB Add‑On / Arduino Library Manager)
- Arduino Mega 2560 (default, configurable)
- DHT22 connected to **D3** (adjust in code if needed)

**Quick Start**
1. Install required Add‑Ons in MATLAB.
2. Connect Arduino + DHT22 (DATA → D3, 10 kΩ pull‑up to VCC recommended).
3. Open `Temperatura.mlapp`.
4. Select the proper COM port and toggle **System → On**.
5. Toggle **Temperature** / **Humidity** to start plotting.

**Notes**
- Buffer window set to 50 samples (editable).
- Extend COM list if your system uses other ports.

---

## Tags

**English:**  
`matlab`, `app-designer`, `arduino`, `dht22`, `temperature`, `humidity`, `sensor`, `data-logging`, `real-time`, `ui`

**Español:**  
`matlab`, `app-designer`, `arduino`, `dht22`, `temperatura`, `humedad`, `sensor`, `registro-de-datos`, `tiempo-real`, `interfaz`

---

## License

Released under the MIT License – see [LICENSE](LICENSE).
