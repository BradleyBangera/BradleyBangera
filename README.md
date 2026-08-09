<div align="center">

  <!-- DYNAMIC BANNER HEADER -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2942,50:1a365d,100:2b6cb0&height=280&section=header&text=BRADLEY%20BANGERA&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=Embedded%20Systems%20%7C%20STM32%20Bare-Metal%20%26%20FreeRTOS%20%7C%20HIL%20Test%20Jigs&descAlignY=60&descAlign=50" width="100%" />

  <!-- DYNAMIC TYPING SUBTITLE -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=3182CE&center=true&vCenter=true&width=750&lines=Architecting+STM32F4+Cortex-M4+Bare-Metal+%26+FreeRTOS+Firmware;Designing+Hardware-in-the-Loop+(HIL)+Test+Jigs+%26+Electronic+Loads;Implementing+Closed-Loop+PID+Control+%26+Digital+Signal+Filtering;Engineering+Low-Power+GSM%2FGPRS+IoT+Telemetry+%26+Custom+PCB+Layouts" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- SOCIAL BADGES -->
  <a href="https://linkedin.com/in/bradley-bangera-270b611b2">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:bradleycbangera@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/bradleybangera">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Karnataka%2C%20India-0052B4?style=for-the-badge&logo=googlemaps&logoColor=white" />

</div>

<br/>

---

## ⚡ Developer Overview

```c
#include <stdio.h>
#include <stdbool.h>

typedef struct {
    const char* engineer_name;
    const char* primary_mcu;
    const char* kernel;
    const char* specialization;
    bool        hardware_design_capable;
} EmbeddedProfile_t;

void sys_init(void) {
    EmbeddedProfile_t bradley = {
        .engineer_name = "Bradley Chrisben Bangera",
        .primary_mcu = "STM32F401 (ARM Cortex-M4) / ESP32",
        .kernel = "FreeRTOS & Bare-Metal C/C++",
        .specialization = "Firmware, HIL Test Systems, Power Validation & IoT",
        .hardware_design_capable = true
    };

    printf("System Booted: Engineering high-reliability bare-metal & RTOS firmware.\n");
}
