# Yusuf Yıldız — Engineering Portfolio

**Senior Electrical & Electronics Engineering student, Abdullah Gül University (AGU)** · Kayseri, Türkiye · English-medium program
Contact: [yusufyldz.eee@gmail.com](mailto:yusufyldz.eee@gmail.com)

---

## About

I focus on analog front-end design and signal processing. I like taking a circuit from hand calculation to LTspice simulation to bench measurement, and understanding where the three disagree. My projects range from discrete analog stages (active filters, oscillators, BJT amplifiers) to an end-to-end speech link over a real software-defined radio. Most were team projects; each entry lists the team.

---

## Featured Projects

### 1. CAPSUL — LPC Vocoder over Software-Defined Radio
*EE3001 Telecommunication System Design using DSP · Team of 2 (with Mümin Mutluer) · 2026*

End-to-end digital voice link built in MATLAB and tested over a real RF loopback on a USRP-2900 (B200).

- **Speech coding:** 48 kHz → 8 kHz decimation (FIR Hamming low-pass), 14th-order LPC converted to LSF, 128 bits per frame (LSF vector, log-gain, pitch, voicing flag)
- **Transmission:** BPSK with root-raised-cosine pulse shaping (roll-off 0.35) in the 915 MHz ISM band; matched filtering, cross-correlation synchronization, hard-decision demodulation
- **Result:** 10.4 : 1 compression relative to 16-bit PCM; 51 of 52 frames reconstructed error-free (1 bit error in 6,656 transmitted bits); intelligible reconstructed speech

`MATLAB` `Communications Toolbox` `USRP` `DSP` · [Report (PDF)](./EE3001_Final_Report.pdf)

### 2. Capacitive Touch Lock — Microcontroller-Free Analog Interface
*Analogue Electronics project · Team of 2 (with Yusuf Taha Gümüş)*

Two-key touch lock that converts a homemade capacitive sensor's picofarad-level change into a logic signal using only analog stages — no microcontroller.

- **Signal chain:** TL082 Wien-bridge oscillator (50 kHz carrier) → capacitive sensor → two-stage 2N2222 BJT amplifier with emitter degeneration → 1N5819 Schottky voltage doubler → 74HC74 D flip-flop state hold
- **Simulation:** LTspice parametric sweep of sensor capacitance (10–90 pF); 6–8 ms output settling that acts as a built-in debounce
- **Bench results (breadboard, 5 V supply):** 50.0 kHz carrier measured on the oscilloscope; key output rises to 4.8 V on touch

`LTspice` `Discrete BJT Design` `Oscillators` `Breadboard Prototyping` · [Report (PDF)](./Analog_Capacitive_Touch_Sensor_Report.pdf)

### 3. SAPA — Electronic Stethoscope
*Capsule project · Team of 3 (with Sude Nur Görez, Yusuf Taha Gümüş)*

Analog front-end and MATLAB application for recording and analysing heart sounds.

- **Analog front-end:** electret microphone, 2nd-order Butterworth Sallen-Key high-pass (30 Hz) and low-pass (720 Hz) filters on LM358, and an inverting gain stage (total gain ≈ 18), giving a 30–720 Hz pass band for heart and lung sounds
- **Acquisition:** Arduino Uno ADC streaming samples to MATLAB over serial
- **Software:** MATLAB App Designer GUI with adjustable cut-off frequencies, time and FFT views, and BPM estimation
- Filter responses verified in LTspice (Bode plots) before the hardware build

`LTspice` `Analog Filters` `Arduino` `MATLAB App Designer` · [Report (PDF)](./SAPA_Electronic_Stethoscope_Report.pdf)

### 4. Two-Axis Laser Scanner — Optical Design and Servo Control
*EE421 Geometrical Optics · Team of 3 (with Sude Nur Görez, Yusuf Taha Gümüş) · 2026 · electronics and control design phase*

Laser projector that writes letters on a screen by steering a beam with two servo-driven mirrors.

- **Optics:** two-mirror layout modeled in Zemax; ~142 × 140 mm scan area at 500 mm throw distance, calibrated at 0.0492 °/mm (X) and 0.1139 °/mm (Y)
- **Hardware:** Arduino Uno driving two MG90S servos, selected over a stepper, a DC motor with encoder and a galvanometer in a trade-off study; 2N2222 transistor switch for a red laser module (< 5 mW); USB power bank with a ~275 mA typical / ~1.4 A peak current budget
- **Control:** point-to-point vector drawing; screen coordinates mapped directly to servo pulse widths (Servo 1 = 1450 − 0.519·X µs, Servo 2 = 1450 − 1.203·Y µs); each stroke interpolated in 25 steps with the laser blanked during repositioning moves
- **Output:** seven letters (H, E, L, N, O, T, A) encoded as scan trajectories, about 1 s per letter

`Zemax` `Arduino` `Servo Control` `Optics` · [Phase II report (PDF)](./Laser_Scanner_EE421_Phase2_Report.pdf)

### 5. LithoSuite — Optical Lithography Process Simulator
*Team of 3 (with Sude Nur Görez, Yusuf Taha Gümüş) · intermediate report*

Educational MATLAB tool that models pattern transfer in optical lithography and flags process settings that will fail.

- **Models:** Rayleigh resolution (critical dimension), depth of focus, flare-induced contrast loss, sigmoid resist-exposure model
- **Scenarios:** ArF dry (193 nm), KrF (248 nm), EUV (13.5 nm with 5 % flare), immersion high-NA (pass case), KrF with 600 nm defocus (failure case)
- **Outputs:** aerial image, resist profile, intensity map and printed-wafer view, with automatic pass/fail diagnostics based on MTF

`MATLAB` `Semiconductor Processing` `Physical Modeling` · [Report (PDF)](./LithoSuite_Lithography_Simulation_Report.pdf)

### 6. Gate-Level Digital System — Ring Oscillator, CMOS MUX and Switchable Counter
*Digital System Design capsule project · Team of 2 (with Yusuf Taha Gümüş)*

Three-stage design built from discrete transistors and logic, simulated end to end in LTspice.

- **Clock generation:** 7-stage ring oscillators from discrete 2N7000/BS250 MOSFETs (1 Hz and 2 Hz outputs; 1.84 Hz hand calculation vs 2 Hz in simulation)
- **Clock selection:** 2×2 multiplexer in CMOS configuration
- **Counting:** switchable BCD counter (step of 1 or 2) driving a 7-segment display, plus a duty-cycle-variable pulse generator (0–50 %)

`LTspice` `Discrete CMOS` `Sequential Logic` · [Final report (PDF)](./Digital_System_Design_Final_Report.pdf) · [Task 1: Ring oscillator](./CMOS_Ring_Oscillator_Design_Report.pdf) · [Task 2: Multiplexer](./CMOS_Multiplexer_Design_Report.pdf) · [Simulation video](https://youtu.be/IeM8DrGkxiU)

---

## Experience

**Engineering Intern — GİS Elektrik** · Jul–Aug 2026
Electrical panel production and drawing; worked both on the assembly floor and in the design office (AutoCAD, EPLAN Electric P8).

---

## Technical Skills

| Area | Skills |
| :--- | :--- |
| **Analog & hardware** | Active filters (Sallen-Key), oscillators (Wien bridge, ring), discrete BJT/MOSFET stages, breadboard prototyping, bench measurement (oscilloscope, DC supply, multimeter) |
| **DSP & communications** | Speech coding (LPC/LSF), digital modulation (BPSK, ASK/FSK/PSK), pulse shaping, SDR (USRP-2900), analog modulation (AM/FM/PM) |
| **Embedded** | Arduino (ADC sampling, serial data streaming, servo PWM control) |
| **Software & tools** | MATLAB (App Designer, Communications Toolbox), LTspice, Proteus, AutoCAD, EPLAN Electric P8 |
| **Programming** | MATLAB, C/C++ (Arduino), Python (basic) |
| **Currently learning** | Altium Designer (PCB design), STM32 |
