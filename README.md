# 🛰 Flight-Grade PSFB DC-DC Converter (100 V → 400 V, 300 W)

This repository contains the complete LTspice simulation and technical documentation for a high-efficiency Phase-Shifted Full-Bridge (PSFB) converter designed for aerospace applications. This project serves as the second stage in a three-stage electric propulsion power supply system.

---

##  System Overview

- **Input Voltage:** 100 V  
- **Output Voltage:** 400 V  
- **Output Power:** 300 W  
- **Peak Efficiency:** 98.44%  
- **Startup Time:** <6 ms  
- **Output Ripple:** <0.02%  
- **Switching Frequency:** 80 kHz  
- **Topology:** Phase-Shifted Full-Bridge with Synchronous Rectification

---

##  Contents

- `Technical_Writeup.pdf` — Full design report and simulation analysis  
- `LTspice_Models/` — All LTspice schematics, models, and supporting files  
- `Waveforms/` — Key waveform captures with ripple, ZVS, control behavior  
- `Control_Logic/` — Custom gate expressions and timing logic  
- `Images/` — Block diagrams and cover design  
- `Documentation/` — Source `.docx` for reference

---

##  Preview

![Block Diagram](Images/Block_Diagram.png)

---

##  Highlights

- ZVS on both half-bridge legs
- Synchronous rectification with MOSFETs replacing secondary diodes
- Real-world modeled MOSFETs, capacitors, inductors with parasitics
- Type III compensation feedback loop
- Custom-built Vcontrol-based gate drive logic

---

##  Licensing

This project is shared for educational and portfolio purposes. Commercial use is not permitted without permission.

---

##  Contact

If you're a recruiter, professor, or engineer interested in collaboration, reach out via GitHub or [insert LinkedIn link].
