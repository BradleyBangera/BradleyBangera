<div align="center">

<!-- OSCILLOSCOPE SIGNAL TRACE HEADER -->
<svg width="100%" height="140" viewBox="0 0 800 140" xmlns="http://www.w3.org/2000/svg">
  <rect width="800" height="140" fill="#0D1117" rx="10" stroke="#30363D" stroke-width="1"/>
  <defs>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#161B22" stroke-width="1"/>
    </pattern>
    <linearGradient id="traceGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00D4AA" stop-opacity="0.2"/>
      <stop offset="50%" stop-color="#00D4AA" stop-opacity="1"/>
      <stop offset="100%" stop-color="#58A6FF" stop-opacity="0.9"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="2" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>
  <rect width="800" height="140" fill="url(#grid)" rx="10"/>
  
  <!-- Glowing Signal Trace -->
  <polyline points="0,70 35,70 40,25 50,25 55,70 95,70 100,105 110,105 115,70 155,70 160,35 170,35 175,70 215,70 220,15 230,15 235,70 285,70 290,90 300,90 305,70 355,70 360,25 370,25 375,70 415,70 420,100 430,100 435,70 475,70 480,35 490,35 495,70 535,70 540,20 550,20 555,70 595,70 600,90 610,90 615,70 655,70 660,35 670,35 675,70 715,70 720,110 730,110 735,70 800,70"
    fill="none" stroke="url(#traceGrad)" stroke-width="2.5" filter="url(#glow)"/>
  
  <!-- Typography -->
  <text x="400" y="62" text-anchor="middle" font-family="'Courier New', monospace" font-size="28" font-weight="900" fill="#F0F6FC" letter-spacing="6">BRADLEY CHRISBEN BANGERA</text>
  <text x="400" y="96" text-anchor="middle" font-family="'Courier New', monospace" font-size="12" font-weight="bold" fill="#00D4AA" letter-spacing="3">EMBEDDED SYSTEMS ENGINEER · FIRMWARE · HIL TEST JIGS · IoT</text>
</svg>

<br/>

<!-- SIGNAL DIVIDER 1: SYSTEM STATUS -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="270" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="280" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">SYSTEM_STATUS</text>
  <circle cx="420" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="430" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

<!-- TERMINAL DASHBOARD CARD -->
<svg width="100%" height="300" viewBox="0 0 780 300" xmlns="http://www.w3.org/2000/svg">
  <rect width="780" height="300" fill="#0D1117" rx="8" stroke="#30363D" stroke-width="1"/>
  
  <!-- Terminal Header Bar -->
  <path d="M 0 8 C 0 3, 3 0, 8 0 L 772 0 C 777 0, 780 3, 780 8 L 780 32 L 0 32 Z" fill="#161B22"/>
  <circle cx="20" cy="16" r="5" fill="#FF5F56"/>
  <circle cx="36" cy="16" r="5" fill="#FFBD2E"/>
  <circle cx="52" cy="16" r="5" fill="#27C93F"/>
  <text x="390" y="20" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#8B949E">bradley@mcu-node:~ $ ./sys_init.sh --profile</text>
  
  <!-- Terminal Code Output -->
  <text x="24" y="60" font-family="'Courier New', monospace" font-size="12" fill="#58A6FF" font-weight="bold">role</text>
  <text x="140" y="60" font-family="'Courier New', monospace" font-size="12" fill="#00D4AA">:=</text>
  <text x="165" y="60" font-family="'Courier New', monospace" font-size="12" fill="#E6EDF3">"L3 Embedded Systems Engineer @ Blackfrog Technologies"</text>

  <text x="24" y="85" font-family="'Courier New', monospace" font-size="12" fill="#58A6FF" font-weight="bold">architecture</text>
  <text x="140" y="85" font-family="'Courier New', monospace" font-size="12" fill="#00D4AA">:=</text>
  <text x="165" y="85" font-family="'Courier New', monospace" font-size="12" fill="#E6EDF3">"STM32 (ARM Cortex-M4/M0) · FreeRTOS · Bare-Metal C/C++"</text>

  <text x="24" y="110" font-family="'Courier New', monospace" font-size="12" fill="#58A6FF" font-weight="bold">domain</text>
  <text x="140" y="110" font-family="'Courier New', monospace" font-size="12" fill="#00D4AA">:=</text>
  <text x="165" y="110" font-family="'Courier New', monospace" font-size="12" fill="#E6EDF3">"WHO PQS Medical Devices · HIL Validation Rigs · GSM IoT"</text>

  <text x="24" y="135" font-family="'Courier New', monospace" font-size="12" fill="#58A6FF" font-weight="bold">compliance</text>
  <text x="140" y="135" font-family="'Courier New', monospace" font-size="12" fill="#00D4AA">:=</text>
  <text x="165" y="135" font-family="'Courier New', monospace" font-size="12" fill="#E6EDF3">"ISO-Compliant V&amp;V Workflows &amp; Audit Traceability"</text>

  <text x="24" y="160" font-family="'Courier New', monospace" font-size="12" fill="#58A6FF" font-weight="bold">goal</text>
  <text x="140" y="160" font-family="'Courier New', monospace" font-size="12" fill="#00D4AA">:=</text>
  <text x="165" y="160" font-family="'Courier New', monospace" font-size="12" fill="#FFBD2E">"Seeking Research Internship Opportunities in Germany (2025/26)"</text>

  <line x1="20" y1="180" x2="760" y2="180" stroke="#21262D" stroke-width="1"/>

  <!-- Concise Summary Text -->
  <text x="24" y="208" font-family="system-ui, sans-serif" font-size="12.5" fill="#C9D1D9">Embedded Systems Engineer with ~3 years of production experience building mission-critical medical firmware.</text>
  <text x="24" y="230" font-family="system-ui, sans-serif" font-size="12.5" fill="#C9D1D9">Expertise spans low-level STM32 C drivers, FreeRTOS multi-threading, low-power state machines, and HIL test jigs.</text>
  <text x="24" y="252" font-family="system-ui, sans-serif" font-size="12.5" fill="#C9D1D9">Bridging production engineering rigor with applied research in real-time systems, IoT, and embedded control.</text>
</svg>

<br/>

<!-- SIGNAL DIVIDER 2: TECHNICAL MATRIX -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="250" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="260" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">TECHNICAL_MATRIX</text>
  <circle cx="440" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="450" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

<!-- HARDWARE & SOFTWARE MATRIX SVG -->
<svg width="100%" height="320" viewBox="0 0 780 320" xmlns="http://www.w3.org/2000/svg">
  <rect width="780" height="320" fill="#0D1117" rx="8" stroke="#30363D" stroke-width="1"/>
  
  <!-- Column Headers -->
  <text x="20" y="28" font-family="'Courier New', monospace" font-size="11" fill="#00D4AA" font-weight="bold" letter-spacing="1">FIRMWARE &amp; RTOS</text>
  <text x="210" y="28" font-family="'Courier New', monospace" font-size="11" fill="#00D4AA" font-weight="bold" letter-spacing="1">PROTOCOLS &amp; BUSSES</text>
  <text x="400" y="28" font-family="'Courier New', monospace" font-size="11" fill="#00D4AA" font-weight="bold" letter-spacing="1">HARDWARE &amp; TOOLS</text>
  <text x="590" y="28" font-family="'Courier New', monospace" font-size="11" fill="#00D4AA" font-weight="bold" letter-spacing="1">LANGUAGES &amp; STACK</text>

  <line x1="20" y1="36" x2="760" y2="36" stroke="#30363D" stroke-width="1"/>

  <!-- Column 1: Firmware -->
  <text x="24" y="58" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="58" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">STM32 Cortex-M4/M0</text>
  <text x="24" y="78" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="78" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">FreeRTOS Kernel</text>
  <text x="24" y="98" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="98" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Bare-Metal Drivers</text>
  <text x="24" y="118" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="118" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Bootloader Dev</text>
  <text x="24" y="138" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="138" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Low-Power Modes</text>
  <text x="24" y="158" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="158" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">DSP Digital Filtering</text>
  <text x="24" y="178" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="178" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Closed-Loop PID</text>
  <text x="24" y="198" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="198" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">HIL Test Platforms</text>
  <text x="24" y="218" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="36" y="218" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">ESP32 / ESP8266</text>

  <line x1="200" y1="36" x2="200" y2="280" stroke="#21262D" stroke-width="1"/>

  <!-- Column 2: Protocols -->
  <text x="214" y="58" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="58" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">SPI / I2C / UART</text>
  <text x="214" y="78" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="78" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">GSM / GPRS Telemetry</text>
  <text x="214" y="98" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="98" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">MQTT Protocol</text>
  <text x="214" y="118" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="118" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">MODBUS RS232/485</text>
  <text x="214" y="138" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="138" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">BLE (Bluetooth LE)</text>
  <text x="214" y="158" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="158" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">CAN / J1939</text>
  <text x="214" y="178" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="178" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">ISO15765 Protocol</text>
  <text x="214" y="198" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="226" y="198" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">PWM / ADC / DAC</text>

  <line x1="390" y1="36" x2="390" y2="280" stroke="#21262D" stroke-width="1"/>

  <!-- Column 3: Hardware & Tools -->
  <text x="404" y="58" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="58" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Altium Designer</text>
  <text x="404" y="78" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="78" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">KiCad PCB Layout</text>
  <text x="404" y="98" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="98" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">LTspice Simulation</text>
  <text x="404" y="118" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="118" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">STM32CubeIDE</text>
  <text x="404" y="138" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="138" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Keil MDK / µVision</text>
  <text x="404" y="158" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="158" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">ST-Link / J-Link / GDB</text>
  <text x="404" y="178" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="178" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">JTAG / SWD Logic</text>
  <text x="404" y="198" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="416" y="198" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Git / CMake Build</text>

  <line x1="580" y1="36" x2="580" y2="280" stroke="#21262D" stroke-width="1"/>

  <!-- Column 4: Languages -->
  <text x="594" y="58" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="606" y="58" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Embedded C</text>
  <text x="594" y="78" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="606" y="78" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Embedded C++</text>
  <text x="594" y="98" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="606" y="98" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">Python (PyQt/JSON)</text>
  <text x="594" y="118" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="606" y="118" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">ARM Assembly</text>
  <text x="594" y="138" fill="#00D4AA" font-family="'Courier New', monospace" font-size="11">▸</text>
  <text x="606" y="138" fill="#E6EDF3" font-family="'Courier New', monospace" font-size="11">MATLAB / Simulink</text>

  <!-- Bottom Rule & Badges -->
  <line x1="20" y1="280" x2="760" y2="280" stroke="#30363D" stroke-width="1"/>
  
  <rect x="20" y="292" width="130" height="20" rx="4" fill="#161B22" stroke="#00D4AA" stroke-width="1"/>
  <text x="85" y="306" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" font-weight="bold" fill="#00D4AA">WHO PQS Compliant</text>
  
  <rect x="160" y="292" width="120" height="20" rx="4" fill="#161B22" stroke="#00D4AA" stroke-width="1"/>
  <text x="220" y="306" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" font-weight="bold" fill="#00D4AA">ISO V&amp;V Audited</text>
  
  <rect x="290" y="292" width="130" height="20" rx="4" fill="#161B22" stroke="#00D4AA" stroke-width="1"/>
  <text x="355" y="306" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" font-weight="bold" fill="#00D4AA">Medical-Grade HIL</text>
  
  <rect x="430" y="292" width="140" height="20" rx="4" fill="#161B22" stroke="#00D4AA" stroke-width="1"/>
  <text x="500" y="306" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" font-weight="bold" fill="#00D4AA">Production Firmware</text>
  
  <rect x="580" y="292" width="130" height="20" rx="4" fill="#161B22" stroke="#00D4AA" stroke-width="1"/>
  <text x="645" y="306" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" font-weight="bold" fill="#00D4AA">Low-Power Systems</text>
</svg>

<br/>

<!-- SIGNAL DIVIDER 3: EXPERIENCE -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="220" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="230" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">WORK_EXPERIENCE</text>
  <circle cx="470" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="480" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

</div>

<br/>

### 🏢 Blackfrog Technologies Private Limited — Manipal, Karnataka, India

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ [Dec 2024 – Present]  L3 EMBEDDED SYSTEMS ENGINEER                                     │
│ Focus: WHO PQS Medical Devices · Low-Power Systems · GSM Telemetry · ISO Compliance   │
└────────────────────────────────────────────────────────────────────────────────────────┘
```
* **Low-Power Firmware Strategy:** Architected STM32 sleep and stop mode routines, peripheral power gating, and wake-up interrupt handling for field-deployed medical devices.
* **GSM/GPRS IoT Telemetry:** Implemented two-way telemetry transmission routines connecting embedded hardware to cloud dashboards via MQTT/TCP protocols.
* **On-Device Diagnostic Computing:** Engineered real-time KPI computation logic and digital signal processing (DSP) filters for daily performance summaries and anomaly detection.
* **Python Tooling & Validation:** Developed desktop automation suites using PyQt for configuration generation, JSON schema validation, and SD-card log integrity verification.
* **Regulatory Compliance & ISO Ownership:** Primary owner of technical documentation, traceability matrices, and audit readiness workflows for production devices under WHO PQS and ISO standards.

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ [Aug 2024 – Nov 2024] TRAINEE EMBEDDED ENGINEER                                        │
└────────────────────────────────────────────────────────────────────────────────────────┘
```
* **FreeRTOS UI Firmware:** Designed multi-threaded graphical user interface firmware using STM32 microcontrollers and FreeRTOS tasks.
* **Low-Level Storage Drivers:** Implemented SPI/I2C Flash memory drivers for persistent event logging, crash dumps, and system parameters.

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ [Jan 2024 – Jun 2024] EMBEDDED FIRMWARE & PROTOTYPING INTERN                          │
└────────────────────────────────────────────────────────────────────────────────────────┘
```
* **HIL Test Platforms & Electronic Loads:** Designed automated multi-channel fan test setups and programmable electronic loads utilizing closed-loop PID current regulation.
* **Sensor Calibration & Custom PCBs:** Implemented regression-based sensor calibration and fabricated PCB breakout test boards in Altium Designer / KiCad.

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│ [Jul 2023 – Nov 2023] EMBEDDED ENGINEER INTERN                                         │
└────────────────────────────────────────────────────────────────────────────────────────┘
```
* **Production QA Systems:** Built STM32-based quality assurance test rigs and authored custom C libraries for segmented LCD modules.

<br/>

<div align="center">

<!-- SIGNAL DIVIDER 4: RESEARCH & PROJECTS -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="220" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="230" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">RESEARCH_&amp;_PROJECTS</text>
  <circle cx="470" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="480" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

</div>

<br/>

#### 🔬 B.Tech Thesis: Hardware-in-the-Loop (HIL) Test System for Medical Refrigeration Devices
> **Manipal Institute of Technology (2024)**  
> *Designed and deployed an automated STM32-based HIL test bench to validate daughter boards used in Emvólio cold-chain vaccine refrigeration devices. Performed parametric verification of communication buses (SPI/I2C/UART), power rails, and sensor I/O with automated test reporting.*

```
   ┌───────────────────┐       SPI / I2C / UART       ┌───────────────────────┐
   │    STM32 HIL      │ ───────────────────────────► │  Daughter Board (DUT) │
   │    Controller     │ ◄─────────────────────────── │  (Voltage / Charging) │
   └───────────────────┘       Stimulus & Response    └───────────────────────┘
             │                                                    │
             ▼                                                    ▼
   [PMDB Power Rail Check]                                [Structured Report Generator]
   • ACS712 Current Sensing                               • Pass/Fail Analytics
   • Closed-Loop PID Load                                 • Automated QC Pipeline
```

#### ⚡ Automated 18650 Li-Ion Battery Cell Testing Platform
* Designed an automated microcontroller-driven discharge platform using constant-current loads to measure discharge curves, calculate real-time mAh capacity, and evaluate cell State-of-Health (SoH).

#### 📡 Smart IoT Battery Monitoring System (BMS)
* Developed an ESP32-enabled BMS setup streaming battery voltage, charge current, and thermal parameters to a cloud dashboard via MQTT with over-voltage/over-temperature trigger alerts.

#### 📳 Vibration Analyzer with LabVIEW Integration
* Constructed an industrial vibration monitoring node with an accelerometer and microcontroller, interfaced with LabVIEW for real-time amplitude visualization and threshold-driven safety cutoff relays.

<br/>

<div align="center">

<!-- SIGNAL DIVIDER 5: ACADEMICS -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="230" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="240" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">ACADEMICS_&amp;_CERTS</text>
  <circle cx="460" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="470" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

</div>

<br/>

| Qualification | Institution | Year | Grade / Distinction |
| :--- | :--- | :---: | :---: |
| **B.Tech in Electrical & Electronics Engineering** *(Minor in Embedded Systems)* | Manipal Institute of Technology (MIT) | 2021 – 2024 | **7.63 CGPA** |
| **Diploma in Electrical & Electronics Engineering** | Dr. TMA Pai Polytechnic | 2018 – 2021 | **93.48%** *(First Class Distinction)* |

* **Core Coursework:** Microcontrollers, Embedded System Design, Real-Time Systems, FPGA-Based System Design, Internet of Things, Digital Signal Processing, Linear Control Theory, Analog System Design, Industrial Automation.
* **Certifications:** Arm Cortex-M Processors Overview (Arm) · Intro to Battery Management Systems (CU Boulder) · Altium Education Schematic & PCB Units 1 & 2 · Crash Course on Python (Google) · MATLAB Onramp (MathWorks).

<br/>

<div align="center">

<!-- SIGNAL DIVIDER 6: RESEARCH INTERNSHIP GERMANY -->
<svg width="100%" height="24" viewBox="0 0 700 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="210" y2="12" stroke="#30363D" stroke-width="1"/>
  <circle cx="220" cy="12" r="3.5" fill="#00D4AA"/>
  <text x="350" y="16" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" font-weight="bold" fill="#8B949E" letter-spacing="3">RESEARCH_INTERNSHIP_GERMANY</text>
  <circle cx="480" cy="12" r="3.5" fill="#00D4AA"/>
  <line x1="490" y1="12" x2="700" y2="12" stroke="#30363D" stroke-width="1"/>
</svg>

</div>

<br/>

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│  TARGET: Seeking Research Internship Opportunities in Germany (2025 / 2026)             │
├────────────────────────────────────────────────────────────────────────────────────────┤
│  • Embedded Systems Research    • Real-Time Systems        • IoT & Wireless Mesh       │
│  • Low-Power Computing          • Firmware Verification    • Hardware-Software Co-Design│
└────────────────────────────────────────────────────────────────────────────────────────┘
```

* **Why Germany:** Aiming to bring production-grade medical device compliance engineering (WHO PQS, ISO V&V) and hands-on HIL test jig design to applied research groups (TU Munich, KIT, RWTH Aachen, TU Chemnitz, Fraunhofer Institutes).
* **Languages:** **English** (*C1 Proficient*) · **German** (*A1 Basic - Active Learner*) · **Kannada** (*Native*) · **Hindi / Tulu** (*B2*).

<br/>

<div align="center">

<!-- FOOTER SIGNAL TRACE -->
<svg width="100%" height="55" viewBox="0 0 700 55" xmlns="http://www.w3.org/2000/svg">
  <polyline points="0,25 40,25 45,10 55,10 60,25 100,25 105,38 115,38 120,25 160,25 165,12 175,12 180,25 220,25 225,40 235,40 240,25 280,25 285,15 295,15 300,25 340,25 345,35 355,35 360,25 400,25 405,10 415,10 420,25 460,25 465,38 475,38 480,25 520,25 525,15 535,15 540,25 580,25 585,40 595,40 600,25 640,25 645,12 655,12 660,25 700,25"
    fill="none" stroke="#00D4AA" stroke-width="1.5" opacity="0.5"/>
  <text x="350" y="48" text-anchor="middle" font-family="'Courier New', monospace" font-size="9" fill="#8B949E" letter-spacing="2">BRADLEY CHRISBEN BANGERA · EMBEDDED SYSTEMS ENGINEER · MANIPAL, INDIA</text>
</svg>

<br/>

[![Email](https://img.shields.io/badge/Email-bradleycbangera%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bradleycbangera@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bradley-bangera-270b611b2)

</div>
