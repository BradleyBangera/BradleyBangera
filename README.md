<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════ -->

<!--                         EMBEDDED SYSTEM HEADER                         -->

<!-- ═══════════════════════════════════════════════════════════════════════ -->

<svg width="900" height="180" viewBox="0 0 900 180" xmlns="http://www.w3.org/2000/svg">

<rect width="900" height="180" rx="10" fill="#0D1117"/>

<!-- Grid -->

<defs>
<pattern id="grid" width="45" height="45" patternUnits="userSpaceOnUse">
<path d="M 45 0 L 0 0 0 45" fill="none" stroke="#161B22" stroke-width="1"/>
</pattern>
</defs>

<rect width="900" height="180" rx="10" fill="url(#grid)"/>

<!-- Top status bar -->

<rect x="24" y="18" width="852" height="24" rx="4" fill="#161B22"/>
<circle cx="40" cy="30" r="4" fill="#00D4AA"/>
<text x="54" y="34"
      font-family="monospace"
      font-size="10"
      fill="#8B949E"
      letter-spacing="2">
SYSTEM ONLINE
</text>

<text x="860" y="34"
   text-anchor="end"
   font-family="monospace"
   font-size="9"
   fill="#484F58"
   letter-spacing="1">
STM32::VAULT </text>

<!-- Signal trace -->

<polyline
points="
0,130 35,130
40,105 50,105 55,130
90,130
95,145 105,145 110,130
145,130
150,92 160,92 165,130
200,130
205,112 215,112 220,130
255,130
260,148 270,148 275,130
310,130
315,100 325,100 330,130
365,130
370,115 380,115 385,130
420,130
425,145 435,145 440,130
475,130
480,95 490,95 495,130
530,130
535,110 545,110 550,130
585,130
590,148 600,148 605,130
640,130
645,103 655,103 660,130
695,130
700,115 710,115 715,130
750,130
755,145 765,145 770,130
805,130
810,98 820,98 825,130
860,130
900,130"
fill="none"
stroke="#00D4AA"
stroke-width="2"
opacity="0.65"/>

<!-- Name -->

<text x="450" y="82"
   text-anchor="middle"
   font-family="monospace"
   font-size="29"
   font-weight="bold"
   fill="#E6EDF3"
   letter-spacing="5">
BRADLEY BANGERA </text>

<text x="450" y="103"
   text-anchor="middle"
   font-family="monospace"
   font-size="11"
   fill="#00D4AA"
   letter-spacing="3">
EMBEDDED FIRMWARE · STM32 · RTOS · HARDWARE </text>

</svg>

<br/>

### `FIRMWARE × HARDWARE × TESTING × SYSTEMS`

</div>

---

<div align="center">

**Embedded Firmware Engineer** · Manipal, India

Building production embedded systems with **STM32, C, FreeRTOS, Python and hardware/software integration.**

</div>

<br/>

---

## `01 // SYSTEM PROFILE`

```text
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│  ROLE        Embedded Firmware Engineer                            │
│  DOMAIN      Medical Devices · IoT · Real-Time Systems             │
│  MCU         STM32 Cortex-M · ESP32                                │
│  CORE        Embedded C · FreeRTOS · Drivers · Debugging            │
│  INTERFACES  SPI · I²C · UART · CAN · GSM/GPRS · MQTT              │
│  TESTING     HIL · Hardware Validation · Python Automation          │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

I work on embedded systems where **firmware reliability, hardware behaviour and verification** have to come together.

My professional experience is primarily in **medical-grade IoT devices and temperature-monitoring systems**, including production firmware, low-power operation, sensor processing, communications, automated testing and engineering documentation.

My current focus is becoming a deeper **embedded systems engineer** — moving from individual firmware features toward **drivers, RTOS architecture, testing infrastructure, system design and safety-critical engineering**.

---

## `02 // TECHNICAL MATRIX`

<div align="center">

<svg width="900" height="330" viewBox="0 0 900 330" xmlns="http://www.w3.org/2000/svg">

<rect width="900" height="330" rx="8" fill="#0D1117"/>

<!-- headers -->

<text x="25" y="28" font-family="monospace" font-size="11" font-weight="bold" fill="#00D4AA">FIRMWARE</text> <text x="240" y="28" font-family="monospace" font-size="11" font-weight="bold" fill="#00D4AA">PROTOCOLS</text> <text x="455" y="28" font-family="monospace" font-size="11" font-weight="bold" fill="#00D4AA">TOOLS</text> <text x="670" y="28" font-family="monospace" font-size="11" font-weight="bold" fill="#00D4AA">LANGUAGES</text>

<line x1="20" y1="40" x2="880" y2="40" stroke="#21262D"/>

<!-- firmware -->

<text x="25" y="65" font-family="monospace" font-size="11" fill="#E6EDF3">STM32 Cortex-M</text> <text x="25" y="87" font-family="monospace" font-size="11" fill="#E6EDF3">Bare-metal C</text> <text x="25" y="109" font-family="monospace" font-size="11" fill="#E6EDF3">FreeRTOS</text> <text x="25" y="131" font-family="monospace" font-size="11" fill="#E6EDF3">DMA / Timers / ADC</text> <text x="25" y="153" font-family="monospace" font-size="11" fill="#E6EDF3">Drivers</text> <text x="25" y="175" font-family="monospace" font-size="11" fill="#E6EDF3">Bootloaders</text> <text x="25" y="197" font-family="monospace" font-size="11" fill="#E6EDF3">Low-power systems</text> <text x="25" y="219" font-family="monospace" font-size="11" fill="#E6EDF3">Signal processing</text>

<!-- protocols -->

<text x="240" y="65" font-family="monospace" font-size="11" fill="#E6EDF3">SPI</text> <text x="240" y="87" font-family="monospace" font-size="11" fill="#E6EDF3">I²C</text> <text x="240" y="109" font-family="monospace" font-size="11" fill="#E6EDF3">UART</text> <text x="240" y="131" font-family="monospace" font-size="11" fill="#E6EDF3">CAN / J1939</text> <text x="240" y="153" font-family="monospace" font-size="11" fill="#E6EDF3">GSM / GPRS</text> <text x="240" y="175" font-family="monospace" font-size="11" fill="#E6EDF3">MQTT</text> <text x="240" y="197" font-family="monospace" font-size="11" fill="#E6EDF3">BLE</text> <text x="240" y="219" font-family="monospace" font-size="11" fill="#E6EDF3">PWM / ADC / DAC</text>

<!-- tools -->

<text x="455" y="65" font-family="monospace" font-size="11" fill="#E6EDF3">STM32CubeIDE</text> <text x="455" y="87" font-family="monospace" font-size="11" fill="#E6EDF3">Git / GitHub</text> <text x="455" y="109" font-family="monospace" font-size="11" fill="#E6EDF3">GDB / ST-Link</text> <text x="455" y="131" font-family="monospace" font-size="11" fill="#E6EDF3">JTAG / SWD</text> <text x="455" y="153" font-family="monospace" font-size="11" fill="#E6EDF3">KiCad / Altium</text> <text x="455" y="175" font-family="monospace" font-size="11" fill="#E6EDF3">LTspice</text> <text x="455" y="197" font-family="monospace" font-size="11" fill="#E6EDF3">MATLAB / Simulink</text> <text x="455" y="219" font-family="monospace" font-size="11" fill="#E6EDF3">Logic Analyser</text>

<!-- languages -->

<text x="670" y="65" font-family="monospace" font-size="11" fill="#E6EDF3">C</text> <text x="670" y="87" font-family="monospace" font-size="11" fill="#E6EDF3">C++</text> <text x="670" y="109" font-family="monospace" font-size="11" fill="#E6EDF3">Python</text> <text x="670" y="131" font-family="monospace" font-size="11" fill="#E6EDF3">ARM Assembly</text>

<!-- vertical dividers -->

<line x1="215" y1="40" x2="215" y2="245" stroke="#21262D"/>
<line x1="430" y1="40" x2="430" y2="245" stroke="#21262D"/>
<line x1="645" y1="40" x2="645" y2="245" stroke="#21262D"/>

<!-- status -->

<line x1="20" y1="250" x2="880" y2="250" stroke="#21262D"/>

<rect x="25" y="270" width="150" height="25" rx="4" fill="#161B22" stroke="#00D4AA"/>
<text x="100" y="287" text-anchor="middle" font-family="monospace" font-size="9" fill="#00D4AA">PRODUCTION FIRMWARE</text>

<rect x="190" y="270" width="135" height="25" rx="4" fill="#161B22" stroke="#00D4AA"/>
<text x="257" y="287" text-anchor="middle" font-family="monospace" font-size="9" fill="#00D4AA">HIL TESTING</text>

<rect x="340" y="270" width="135" height="25" rx="4" fill="#161B22" stroke="#00D4AA"/>
<text x="407" y="287" text-anchor="middle" font-family="monospace" font-size="9" fill="#00D4AA">WHO PQS</text>

<rect x="490" y="270" width="145" height="25" rx="4" fill="#161B22" stroke="#00D4AA"/>
<text x="562" y="287" text-anchor="middle" font-family="monospace" font-size="9" fill="#00D4AA">REAL-TIME SYSTEMS</text>

<rect x="650" y="270" width="145" height="25" rx="4" fill="#161B22" stroke="#00D4AA"/>
<text x="722" y="287" text-anchor="middle" font-family="monospace" font-size="9" fill="#00D4AA">MEDICAL DEVICES</text>

</svg>

</div>

---

## `03 // STM32 VAULT`

### `A public embedded-systems knowledge base`

The **STM32 Vault** is my long-term collection of embedded experiments, reusable drivers, peripheral implementations, RTOS concepts and testing infrastructure.

```text
                         STM32 VAULT
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
       PERIPHERALS         DRIVERS              RTOS
          │                   │                   │
     GPIO / ADC           OLED / RTC          Tasks
     DMA / TIMERS         Flash / SD          Queues
     UART / SPI           Sensors             Mutexes
     I²C / CAN            Displays            Notifications
          │                   │                   │
          └───────────────────┼───────────────────┘
                              │
                           TESTING
                              │
                    Unit / HIL / Hardware
```

**Goal:** document not just *how* something works, but **why it was designed that way, how it was tested, and what happens when it fails.**

---

## `04 // FLAGSHIP PROJECT`

### SPECTRA — 10-Channel Temperature Data Logger

`STM32F411` · `Embedded C` · `ADC + DMA` · `I²C` · `OLED` · `SD Card` · `RTC`

A multi-channel temperature acquisition system designed around an STM32F411.

**System**

```text
10× NTC Sensors
       │
       ▼
 ADC + DMA
       │
       ▼
 Signal Processing
       │
       ▼
 Calibration
       │
       ├───────────────┐
       ▼               ▼
     OLED            SD Card
       │               │
       └───────┬───────┘
               ▼
             RTC
```

**Engineering focus**

* DMA-based ADC acquisition
* Multi-channel sensor handling
* Temperature conversion and calibration
* Filtering / averaging
* OLED user interface
* Persistent data logging
* RTC-based timestamps
* UART diagnostics
* Modular firmware architecture

→ **[View SPECTRA →](#)**

---

## `05 // PROFESSIONAL EXPERIENCE`

### Blackfrog Technologies — Embedded Firmware

**2024 — Present · Manipal, India**

Working on embedded firmware for **medical-grade IoT and temperature-monitoring systems**.

**Production Firmware**

* STM32 firmware for battery-operated field devices
* Low-power / sleep-mode implementation
* Peripheral and wake-source management
* Sensor acquisition and signal processing
* Real-time diagnostic and KPI computation

**Connectivity**

* GSM/GPRS communication modules
* Device-to-dashboard data transmission
* Embedded communication diagnostics

**Verification & Automation**

* HIL testing architectures
* Hardware and parametric verification
* Python automation for configuration and validation
* SD-card and communication-interface testing

**Engineering Process**

* WHO PQS compliance work
* ISO-oriented documentation and traceability
* Regression testing following hardware/component changes
* Manufacturing and quality-control support

**Technical Leadership**

* Mentoring junior engineers and interns
* Supporting technical interviews
* Owning engineering workstreams

---

### Earlier Roles

**Trainee Embedded Engineer — 2024**

FreeRTOS-based temperature-monitoring firmware, sensor processing, diagnostic logic and persistent flash storage.

**Embedded Firmware & Prototyping Intern — 2024**

Automated fan-testing systems, programmable electronic loads, PID-based current control, sensor calibration and PCB development.

**Embedded Engineer Intern — 2023**

STM32-based production QA systems and custom C drivers for segmented LCD hardware.

---

## `06 // ENGINEERING PROJECTS`

### `HIL TEST SYSTEM`

**STM32 · SPI · I²C · UART · Hardware Validation**

Automated hardware-in-the-loop system for validating medical-device daughter boards against defined electrical and communication acceptance criteria.

```text
┌─────────────┐       ┌────────────────┐       ┌─────────────┐
│ STM32 HIL   │ ────► │ DEVICE / DUT   │ ────► │ PASS / FAIL │
│ CONTROLLER  │ ◄──── │               │       │   REPORT    │
└─────────────┘       └────────────────┘       └─────────────┘
        │
        ├── Power monitoring
        ├── Sensor verification
        └── Communication validation
```

---

### `BATTERY CELL TEST RIG`

**Arduino · Li-Ion · Test Automation**

Automated 18650 cell characterisation system for measuring performance parameters and estimating cell capacity.

---

### `SMART BATTERY MONITOR`

**ESP32 · IoT · Real-Time Monitoring**

ESP32-based monitoring system for battery current and voltage with live dashboard visualisation.

---

### `VIBRATION ANALYZER`

**Microcontroller · Accelerometer · LabVIEW**

Real-time vibration monitoring with configurable thresholds and LabVIEW visualisation.

---

## `07 // EDUCATION`

**B.Tech — Electrical & Electronics Engineering**
Manipal Institute of Technology · 2021–2024
**CGPA: 7.63 / 10**
Minor: Embedded Systems

**Diploma — Electrical & Electronics Engineering**
Dr. T.M.A. Pai Polytechnic · 2018–2021
**93.48% · First Class with Distinction**

**Selected coursework**

`Microcontrollers` · `Embedded Systems` · `RT Systems` · `FPGA` · `IoT` · `DSP` · `Control Systems` · `Industrial Automation`

---

## `08 // CURRENTLY LEARNING`

```text
EMBEDDED C
████████████████████░░  Deepening

RTOS / FREERTOS
███████████████░░░░░░  Deepening

DRIVER DEVELOPMENT
██████████████░░░░░░░  Building

EMBEDDED TESTING
████████████░░░░░░░░░  Building

LINUX / EMBEDDED LINUX
████████░░░░░░░░░░░░░  Learning

FUNCTIONAL SAFETY
███████░░░░░░░░░░░░░░  Exploring
```

---

## `09 // ENGINEERING INTERESTS`

**Embedded Systems**
**Automotive & Motorsport**
**Medical Devices**
**Robotics**
**Industrial Automation**
**Safety-Critical Systems**
**Edge AI / Embedded AI**
**Hardware–Software Co-Design**

---

<div align="center">

## `BUILD → MEASURE → DEBUG → VERIFY`

<br/>

<a href="https://github.com/YOUR_USERNAME">
<img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=00D4AA"/>
</a>

<a href="https://www.linkedin.com/">
<img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=00D4AA"/>
</a>

<a href="mailto:bradleycbangera@gmail.com">
<img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00D4AA"/>
</a>

<br/><br/>

<svg width="700" height="55" viewBox="0 0 700 55" xmlns="http://www.w3.org/2000/svg">

<polyline
points="0,25 50,25 55,12 65,12 70,25 125,25 130,38 140,38 145,25 200,25 205,10 215,10 220,25 275,25 280,35 290,35 295,25 350,25 355,12 365,12 370,25 425,25 430,40 440,40 445,25 500,25 505,15 515,15 520,25 575,25 580,37 590,37 595,25 650,25 655,11 665,11 670,25 700,25"
fill="none"
stroke="#00D4AA"
stroke-width="1.5"
opacity="0.5"/>

<text x="350" y="48"
text-anchor="middle"
font-family="monospace"
font-size="9"
fill="#8B949E"
letter-spacing="2">
BRADLEY BANGERA · EMBEDDED SYSTEMS · MANIPAL, INDIA </text>

</svg>

</div>
