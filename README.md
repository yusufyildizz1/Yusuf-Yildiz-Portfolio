<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

```text
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║   YUSUF YILDIZ                                              Rev. 2.1     ║
║   Electrical & Electronics Engineering — Senior Student                  ║
║                                                                          ║
║   FOCUS    Analog Circuit Design · Discrete Electronics ·                ║
║            Signal Integrity                                              ║
║   ORIGIN   Abdullah Gül University (AGU) · Kayseri, Turkey               ║
║            100% English Curriculum                                       ║
║   CONTACT  yusufyldz.eee@gmail.com                                       ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝

      ∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿           ┌──┐    ┌──┐    ┌──┐
      analog domain                ────┘  └────┘  └────┘  └────  digital domain
```

<div align="center">

<a href="mailto:yusufyldz.eee@gmail.com"><img src="https://img.shields.io/badge/Gmail-yusufyldz.eee%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Analog_Circuit_Design-F5D33C?style=for-the-badge" alt="Analog Circuit Design"/>
<img src="https://img.shields.io/badge/Discrete_Electronics-29C5F6?style=for-the-badge" alt="Discrete Electronics"/>
<img src="https://img.shields.io/badge/Signal_Integrity-E040FB?style=for-the-badge" alt="Signal Integrity"/>

[**1** General Description](#1-general-description) · [**2** Features](#2-features) · [**3** Applications](#3-applications) · [**4** Design Methodology](#4-design-methodology) · [**5** Projects](#5-project-portfolio) · [**6** Supplementary Docs](#6-supplementary-documentation) · [**7** Capabilities](#7-technical-capabilities) · [**8** Contact](#8-contact)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

## 1. GENERAL DESCRIPTION

I am an **Electrical-Electronics Engineering** student at **Abdullah Gül University (AGU)** with a specialized interest in **Analog Circuit Design**, **Discrete Electronics**, and **Signal Integrity**. My engineering philosophy is built on the principle of bridging the gap between complex mathematical models and robust, industrial-grade hardware.

> [!IMPORTANT]
> **Design philosophy** — Rather than relying solely on high-level integrated solutions, I am passionate about exploring the **"physics of the circuit"**: designing from the ground up using discrete components.

My work involves extensive **transistor-level modeling in LTSpice**, where I analyze parasitic behaviors, timing constraints, and frequency responses. From designing high-precision **Sallen-Key active filters** to optimizing **Wien Bridge oscillators**, I focus on developing electronic systems that are not only functional but also optimized for **reliability and cost-effectiveness** in R&D environments.

## 2. FEATURES

- Ground-up **discrete design** — exploring the *"physics of the circuit"* at BJT/MOSFET level
- Extensive **transistor-level modeling** in LTSpice: parasitic behaviors, timing constraints, frequency response
- High-precision **Sallen-Key active filter** design
- **Wien Bridge oscillator** design and optimization
- Bridging **complex mathematical models** with **robust, industrial-grade hardware**
- Systems optimized for **reliability and cost-effectiveness** in R&D environments

## 3. APPLICATIONS

- Biomedical signal acquisition and real-time analysis
- Microcontroller-free capacitive sensing interfaces
- Semiconductor lithography process simulation (EUV / ArF)
- CMOS digital building blocks — oscillators, counters, multiplexers

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

## 4. DESIGN METHODOLOGY

```mermaid
flowchart LR
    A["<b>MATHEMATICAL MODEL</b><br/>hand calculation"] --> B["<b>LTSPICE SIMULATION</b><br/>transistor-level · parasitics"]
    B --> C["<b>DISCRETE PROTOTYPE</b><br/>breadboard / PCB"]
    C --> D["<b>MEASURE &amp; VALIDATE</b><br/>frequency · timing"]
    D -. "iterate · refine" .-> A
    style A fill:#F5D33C,stroke:#7a6410,color:#111111
    style B fill:#29C5F6,stroke:#0b5c78,color:#111111
    style C fill:#E040FB,stroke:#701f7e,color:#111111
    style D fill:#66BB6A,stroke:#2b5e2e,color:#111111
```

Every design starts from first principles: hand analysis, then transistor-level SPICE verification of parasitics and timing, then a discrete hardware prototype — iterated until the bench measurements agree with the model.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

## 5. PROJECT PORTFOLIO

*Projects are color-coded like oscilloscope channels —*
<img src="https://img.shields.io/badge/CH1-F5D33C?style=flat-square" alt="CH1"/> <img src="https://img.shields.io/badge/CH2-29C5F6?style=flat-square" alt="CH2"/> <img src="https://img.shields.io/badge/CH3-E040FB?style=flat-square" alt="CH3"/> <img src="https://img.shields.io/badge/CH4-66BB6A?style=flat-square" alt="CH4"/>

### 5.1 — SAPA · Electronic Stethoscope

<img src="https://img.shields.io/badge/CH1-F5D33C?style=flat-square" alt="CH1"/> <img src="https://img.shields.io/badge/MATLAB-App_Designer-blue?style=flat-square" alt="MATLAB App Designer"/> <img src="https://img.shields.io/badge/Hardware-Arduino-teal?style=flat-square&logo=arduino&logoColor=white" alt="Arduino"/> <img src="https://img.shields.io/badge/Analog-Filter_Design-orange?style=flat-square" alt="Analog Filter Design"/>

Designed a **low-noise electronic stethoscope** using Sallen-Key active filters. Integrated **Arduino ADC** with a **MATLAB GUI** for real-time heart sound analysis.

```text
acoustic input ─▶ [ Sallen-Key active filters ] ─▶ [ Arduino ADC ] ─▶ [ MATLAB GUI · real-time analysis ]
```

**Documentation** — [![View Full Report](https://img.shields.io/badge/%F0%9F%93%84_View_Full_Report-PDF-8B0000?style=flat-square)](./SAPA_Electronic_Stethoscope_Report.pdf)

### 5.2 — Capacitive Touch Sensor Lock

<img src="https://img.shields.io/badge/CH2-29C5F6?style=flat-square" alt="CH2"/> <img src="https://img.shields.io/badge/Hardware-Discrete_Design-yellow?style=flat-square" alt="Discrete Design"/> <img src="https://img.shields.io/badge/PCB-Prototyping-green?style=flat-square" alt="PCB Prototyping"/> <img src="https://img.shields.io/badge/Sim-LTSpice-red?style=flat-square" alt="LTSpice"/>

Developed a **microcontroller-free** touch interface using a **Wien Bridge Oscillator (50 kHz)** and discrete **BJT amplifiers** for cost-sensitive applications.

```text
touch plate (ΔC) ─▶ [ Wien Bridge oscillator · 50 kHz ] ─▶ [ discrete BJT amplifiers ] ─▶ [ lock output ]
```

**Documentation** — [![View Full Report](https://img.shields.io/badge/%F0%9F%93%84_View_Full_Report-PDF-8B0000?style=flat-square)](./Analog_Capacitive_Touch_Sensor_Report.pdf)

### 5.3 — LithoSuite · Lithography Simulator

<img src="https://img.shields.io/badge/CH3-E040FB?style=flat-square" alt="CH3"/> <img src="https://img.shields.io/badge/Code-MATLAB-blue?style=flat-square" alt="MATLAB"/> <img src="https://img.shields.io/badge/Theory-Semiconductor-purple?style=flat-square" alt="Semiconductor Theory"/> <img src="https://img.shields.io/badge/Algorithm-Modeling-lightgrey?style=flat-square" alt="Algorithm Modeling"/>

Built a **physics-based simulation engine in MATLAB** to model **EUV/ArF Lithography** processes, analyzing manufacturing failure cases like **CD & DOF**.

```text
process parameters (EUV/ArF) ─▶ [ physics-based simulation engine · MATLAB ] ─▶ [ CD & DOF failure analysis ]
```

**Documentation** — [![View Full Report](https://img.shields.io/badge/%F0%9F%93%84_View_Full_Report-PDF-8B0000?style=flat-square)](./LithoSuite_Lithography_Simulation_Report.pdf)

### 5.4 — Digital System Design

<img src="https://img.shields.io/badge/CH4-66BB6A?style=flat-square" alt="CH4"/> <img src="https://img.shields.io/badge/VLSI-CMOS_Logic-black?style=flat-square" alt="CMOS Logic"/> <img src="https://img.shields.io/badge/Tools-LTSpice-red?style=flat-square" alt="LTSpice"/>

Designed **CMOS Ring Oscillators** and **Switchable Counters**. Verified **timing constraints** and logic levels using **SPICE simulations**.

```text
CMOS schematic (ring osc. · counters) ─▶ [ SPICE simulation ] ─▶ [ timing & logic-level verification ]
```

**Documentation** — [![View Full Report](https://img.shields.io/badge/%F0%9F%93%84_View_Full_Report-PDF-8B0000?style=flat-square)](./Digital_System_Design_Final_Report.pdf)

<!-- ═════════════════════ YENİ PROJELER BURAYA ═════════════════════
Yeni 2 projeyi 5.5 ve 5.6 olarak bu yorumun ÜSTÜNE ekleyin.
Şablon (kopyala, doldur — kanal rengi olarak CH5/CH6 için yeni bir
hex seçebilir ya da paleti tekrarlayabilirsiniz):

### 5.5 — Proje Adı

<img src="https://img.shields.io/badge/CH5-FF8A65?style=flat-square" alt="CH5"/> <img src="https://img.shields.io/badge/Etiket-Deger-blue?style=flat-square" alt=""/>

Kısa proje açıklaması (1–2 cümle, İngilizce).

```text
giriş ─▶ [ blok 1 ] ─▶ [ blok 2 ] ─▶ çıkış
```

**Documentation** — [![View Full Report](https://img.shields.io/badge/%F0%9F%93%84_View_Full_Report-PDF-8B0000?style=flat-square)](./Rapor_Dosyasi.pdf)

═════════════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

## 6. SUPPLEMENTARY DOCUMENTATION

Detailed breakdowns of specific digital design tasks:

| Document | Link |
|:---|:---:|
| **CMOS Ring Oscillator Design Report** | [![PDF](https://img.shields.io/badge/View-PDF-8B0000?style=flat-square)](./CMOS_Ring_Oscillator_Design_Report.pdf) |
| **CMOS Multiplexer Design Report** | [![PDF](https://img.shields.io/badge/View-PDF-8B0000?style=flat-square)](./CMOS_Multiplexer_Design_Report.pdf) |

## 7. TECHNICAL CAPABILITIES

| Category | Capabilities |
|:---|:---|
| **Hardware Design** | <img src="https://img.shields.io/badge/PCB_Design-2E7D32?style=flat-square" alt="PCB Design"/> <img src="https://img.shields.io/badge/Analog_Filters_(Active%2FPassive)-F57C00?style=flat-square" alt="Analog Filters"/> <img src="https://img.shields.io/badge/Oscillators-8E24AA?style=flat-square" alt="Oscillators"/> <img src="https://img.shields.io/badge/Discrete_Electronics_(BJT%2FMOSFET)-546E7A?style=flat-square" alt="Discrete Electronics"/> |
| **Embedded Systems** | <img src="https://img.shields.io/badge/Arduino_(AVR)-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino"/> <img src="https://img.shields.io/badge/STM32-Basics-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32"/> <img src="https://img.shields.io/badge/Sensor_Integration_(ADC%2FDAC%2FI2C)-00695C?style=flat-square" alt="Sensor Integration"/> |
| **Simulation & Tools** | <img src="https://img.shields.io/badge/MATLAB-Advanced-E86E05?style=flat-square" alt="MATLAB Advanced"/> <img src="https://img.shields.io/badge/LTSpice-900000?style=flat-square" alt="LTSpice"/> <img src="https://img.shields.io/badge/Altium_Designer-Learning-A5915F?style=flat-square" alt="Altium Designer"/> <img src="https://img.shields.io/badge/Proteus-1565C0?style=flat-square" alt="Proteus"/> |
| **Programming** | <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C/C++"/> <img src="https://img.shields.io/badge/MATLAB-Scripting-E86E05?style=flat-square" alt="MATLAB Scripting"/> <img src="https://img.shields.io/badge/Python-Basic-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/> |

## 8. CONTACT

| Parameter | Value |
|:---|:---|
| Designation | Yusuf Yıldız |
| Function | Electrical & Electronics Engineering — Senior Student |
| Institution | Abdullah Gül University (AGU) · 100% English Curriculum |
| Location | Kayseri, Turkey |
| Interface | [yusufyldz.eee@gmail.com](mailto:yusufyldz.eee@gmail.com) |

Feel free to explore the reports linked above.

<div align="center">

<a href="mailto:yusufyldz.eee@gmail.com"><img src="https://img.shields.io/badge/Gmail-yusufyldz.eee%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=4" width="100%" alt=""/>

<div align="center">

**REVISION HISTORY**

| Rev. | Date | Description |
|:---:|:---:|:---|
| 1.0 | — | Initial release — first four project reports published |
| 2.0 | 2026-07 | Portfolio restructured in datasheet format |
| 2.1 | 2026-07 | Color revision — oscilloscope channel palette, Mermaid methodology diagram |

<sub>Designed at the transistor level · documented like a datasheet · color-coded like a scope.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F5D33C,33:29C5F6,66:E040FB,100:66BB6A&height=90&section=footer" width="100%" alt=""/>

</div>
