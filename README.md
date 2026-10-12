# Hi, I'm Harishraj 👋

<p align="center">
  <img width="320" src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTMyZzk0aHdlZWdqMjhtbm5pdmV2YWk2bmhkaTJkanNiaXM1MTNndiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Cpaq8odLDnHkDlHK1V/giphy.gif" alt="Oscilloscope waveform">
</p>

<p align="center">
  <b>Electrical &amp; Electronic Engineering Undergraduate</b><br>
  University of Peradeniya, Sri Lanka<br><br>
  📡 Telecommunications · Wireless Systems · Embedded Hardware
</p>

I like working where signals meet hardware: RF and acoustic links on ESP32, firmware written directly in AVR assembly, real-time image processing in Verilog on an FPGA, and machine learning for bandwidth-limited disaster communication.

- 🛰️ Currently working on **semantic communications for post-disaster assessment**: fusing detection and segmentation outputs into compact payloads for bandwidth-limited emergency links
- 📡 Recently built an **autonomous antenna alignment system** driven by live RSSI feedback
- 🌐 **CCNA** training at the IT Center, University of Peradeniya
- 🎯 Seeking opportunities in **telecommunications** and **embedded systems**

---

## 🔧 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📡 [Autonomous Antenna Aligner](https://github.com/harishrajT/autonomous-antenna-aligner)
![Course](https://img.shields.io/badge/EE356-Product%20Design-blue?style=flat-square)

Self-aligning 2.4 GHz directional antenna. It uses a coarse-to-fine RSSI peak search, avoids locking onto side lobes, and re-aligns automatically after a disturbance. It was validated against a measured radiation pattern and in a campus line-of-sight trial.

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Wi-Fi](https://img.shields.io/badge/2.4%20GHz-Wi--Fi-0A66C2?style=flat-square)
![Stepper](https://img.shields.io/badge/NEMA--17-A4988-555?style=flat-square)

</td>
<td width="50%" valign="top">

### 🔊 [RF-Synced Acoustic Ranging](https://github.com/harishrajT/rf-sync-acoustic-ranging)
![Course](https://img.shields.io/badge/EE254-2025-blue?style=flat-square)

Distance by sound time-of-flight with an RF sync reference. nRF24L01+ latency was characterized at ~679 µs (σ ≈ 8.8 µs), and the 16 kHz ASK pulses are detected with an LM567.

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![nRF24L01+](https://img.shields.io/badge/nRF24L01+-RF-0A66C2?style=flat-square)
![MATLAB](https://img.shields.io/badge/MATLAB-Analysis-E16737?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ [Post-Disaster Assessment: Segmentation](https://github.com/harishrajT/fyp-landslide-detection-segmentation)
![FYP](https://img.shields.io/badge/Final%20Year-Research-6f42c1?style=flat-square)
![Phase 2](https://img.shields.io/badge/Phase%202-ongoing-orange?style=flat-square)

**Phase 1:** YOLO11s-seg on a self-collected ground-level landslide dataset, reaching **87.0% mAP@50** and outperforming U-Net, DeepLabV3+ and Mask R-CNN.
**Phase 2:** fusing segmentation with object detection into a semantic payload for low-bandwidth transmission.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO11-Ultralytics-111F68?style=flat-square)

</td>
<td width="50%" valign="top">

### 🖥️ [FPGA Sobel Edge Detection](https://github.com/harishrajT/fpga-sobel-edge-detection)
![Course](https://img.shields.io/badge/2026-Hardware%20Verified-2ea44f?style=flat-square)

Pipelined 3×3 Sobel core with line buffers and a BRAM frame buffer, displayed over 640×480@60 Hz VGA. The RTL matches a Python reference model bit for bit.

![Verilog](https://img.shields.io/badge/Verilog-RTL-555?style=flat-square)
![FPGA](https://img.shields.io/badge/Basys3-Artix--7-C41E3A?style=flat-square)
![Python](https://img.shields.io/badge/NumPy-Verification-013243?style=flat-square&logo=numpy&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 [AVR Assembly Smart Lock](https://github.com/harishrajT/avr-assembly-smart-lock)
![Course](https://img.shields.io/badge/Bare--Metal-Assembly-blue?style=flat-square)

Firmware written entirely in assembly. It includes EEPROM user management, a PWM servo, and LCD (4-bit) and keypad drivers built from scratch.

![AVR](https://img.shields.io/badge/ATmega328P-AVR-00979D?style=flat-square)
![Proteus](https://img.shields.io/badge/Proteus-Simulation-1F6FEB?style=flat-square)

</td>
<td width="50%" valign="top">

### 〰️ [Piezoelectric Vibration Sensor](https://github.com/harishrajT/piezo-vibration-sensor)
![Course](https://img.shields.io/badge/EE251-Analog-blue?style=flat-square)

An analog-only sensor for 100–500 Hz vibration. It uses op-amp signal conditioning and was calibrated across an amplitude range of 0.1–2.5 mm.

![LM741](https://img.shields.io/badge/LM741-Op--Amp-555?style=flat-square)
![Analog](https://img.shields.io/badge/Signal-Conditioning-0A66C2?style=flat-square)

</td>
</tr>
</table>

---

## 🧰 Skills

<table>
<tr>
<td width="25%"><b>📡 Telecom &amp; Networking</b></td>
<td>
<img src="https://img.shields.io/badge/CCNA-Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white"/>
<img src="https://img.shields.io/badge/RF%20Links-2.4%20GHz-0A66C2?style=flat-square"/>
<img src="https://img.shields.io/badge/RSSI-Link%20Analysis-0A66C2?style=flat-square"/>
<img src="https://img.shields.io/badge/ASK-Modulation-0A66C2?style=flat-square"/>
<img src="https://img.shields.io/badge/Time--of--Flight-Ranging-0A66C2?style=flat-square"/>
<img src="https://img.shields.io/badge/Semantic-Communication-6f42c1?style=flat-square"/>
</td>
</tr>
<tr>
<td><b>🔌 Embedded Systems</b></td>
<td>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/>
<img src="https://img.shields.io/badge/ATmega328P-AVR-00979D?style=flat-square"/>
<img src="https://img.shields.io/badge/nRF24L01+-RF%20Module-555?style=flat-square"/>
<img src="https://img.shields.io/badge/Timers%20%7C%20PWM-Interrupts-555?style=flat-square"/>
<img src="https://img.shields.io/badge/I%C2%B2C-EEPROM-555?style=flat-square"/>
<img src="https://img.shields.io/badge/Stepper-A4988-555?style=flat-square"/>
</td>
</tr>
<tr>
<td><b>🖥️ Digital Design</b></td>
<td>
<img src="https://img.shields.io/badge/Verilog-RTL-C41E3A?style=flat-square"/>
<img src="https://img.shields.io/badge/FPGA-Basys3%20%2F%20Artix--7-C41E3A?style=flat-square"/>
<img src="https://img.shields.io/badge/VGA-640%C3%97480-C41E3A?style=flat-square"/>
<img src="https://img.shields.io/badge/Bit--Exact-Verification-C41E3A?style=flat-square"/>
</td>
</tr>
<tr>
<td><b>〰️ Analog &amp; Sensors</b></td>
<td>
<img src="https://img.shields.io/badge/Op--Amp-Signal%20Conditioning-2ea44f?style=flat-square"/>
<img src="https://img.shields.io/badge/Piezoelectric-Sensing-2ea44f?style=flat-square"/>
<img src="https://img.shields.io/badge/LM567-Tone%20Detection-2ea44f?style=flat-square"/>
<img src="https://img.shields.io/badge/LM386-Audio%20Amp-2ea44f?style=flat-square"/>
</td>
</tr>
<tr>
<td><b>💻 Programming</b></td>
<td>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/AVR-Assembly-00979D?style=flat-square"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MATLAB-E16737?style=flat-square"/>
</td>
</tr>
<tr>
<td><b>🧠 ML &amp; Vision</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLO11-Ultralytics-111F68?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
</td>
</tr>
<tr>
<td><b>🛠️ Tools</b></td>
<td>
<img src="https://img.shields.io/badge/Proteus-1F6FEB?style=flat-square"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white"/>
<img src="https://img.shields.io/badge/Label%20Studio-FF7557?style=flat-square"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square"/>
</td>
</tr>
</table>

<sub>🌐 Also comfortable with web basics (HTML, CSS, JavaScript, Node.js, MySQL), which I picked up as a side interest.</sub>

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harish-raj-/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harsharajkajanu@gmail.com)
