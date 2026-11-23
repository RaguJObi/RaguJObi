<h1 align="center">Hi, I'm Ragunandhan 👋</h1>
<p align="center">
  <b>Embedded software engineer: firmware, Embedded Linux and test automation for 5G and RF hardware.</b><br/>
  Chennai, India · open to embedded / firmware roles in Bengaluru, Hyderabad and Chennai
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ragunandhan-dhanasekaran1/"><img src="https://img.shields.io/badge/LinkedIn-Ragunandhan%20Dhanasekaran-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ragunandhan48@gmail.com"><img src="https://img.shields.io/badge/Email-ragunandhan48%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### What I work on

- **Firmware:** FreeRTOS on STM32 (Cortex-M) using the HAL, a custom bootloader for A/B (dual-bank) field updates, SPI / I2C / UART drivers, DMA
- **Embedded Linux:** x86 kernel and driver changes for PCIe and USB, and ARM (HPS) firmware on Intel FPGA SoCs
- **5G and RF:** O-RAN 7.2x fronthaul (eCPRI, PTP, numerology, PRBs), RF transceiver and clock bring-up, IQ / EVM / BER validation on SDR hardware
- **Software:** multithreaded C++ backends with Python/Qt front ends, and Python test automation that proves the hardware works

### Featured project

<table>
<tr>
<td width="55%">
<a href="https://github.com/RaguJObi/RF-Link-Lab"><b>📡 RF Link Lab</b></a><br/><br/>
An end-to-end telemetry radio I built on my own hardware: <b>bare-metal STM32 firmware → UART → QPSK modem → bladeRF SDR → receiver → automated diagnosis</b>.<br/><br/>
• 322 CRC-valid frames from the real board<br/>
• Diagnosed a receiver phase-tracking problem from saved I/Q and added a PLL: <b>4/12 → 12/12 frames, 0 bit errors</b><br/>
• 450+ tests and CI on every push
</td>
<td width="45%">
<a href="https://github.com/RaguJObi/RF-Link-Lab"><img src="https://raw.githubusercontent.com/RaguJObi/RF-Link-Lab/main/artifacts/preview/02-workbench.png" alt="RF Link Lab workbench"/></a>
</td>
</tr>
</table>

### Tools I use

![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5A9A2E)
![Embedded Linux](https://img.shields.io/badge/Embedded%20Linux-FCC624?logo=linux&logoColor=black)
![Qt](https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=white)
![Intel FPGA](https://img.shields.io/badge/Intel%20FPGA%20SoC-0071C5?logo=intel&logoColor=white)
![5G O-RAN](https://img.shields.io/badge/5G%20NR%20%2F%20O--RAN-6A1B9A)
![SDR](https://img.shields.io/badge/SDR%20(bladeRF)-333333)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

### Right now

- 🔧 Extending RF Link Lab with fresh hardware captures to test the new receiver
- 📚 Going deeper on Linux device drivers and the 5G NR physical layer

<sub>Older repositories here are from my college years (web and mobile apps), kept for reference.</sub>
