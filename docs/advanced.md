# 🚀 H) Advanced Topics

> **Cutting-edge embedded technologies: AI/ML, edge computing, security, formal methods, and research topics**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Topics | Quick Jump |
|---------|--------|------------|
| [34. AI/ML on MCUs](#34-aiml-on-microcontrollers) | TinyML, TensorFlow Lite, Edge Impulse | Machine learning |
| [35. Secure Boot & Crypto](#35-secure-boot--cryptography) | Trust zones, secure elements, PKI | Security |
| [36. Formal Verification](#36-formal-verification--model-checking) | SPARK, TLA+, model checking | Correctness proofs |
| [37. Advanced Architectures](#37-advanced-architectures) | RISC-V, multicore, heterogeneous | Modern MCU/SoC |
| [38. Research & Emerging](#38-research--emerging-technologies) | Neuromorphic, quantum, energy harvesting | Future tech |
| [39. Automotive & Telematics](#39-automotive-diagnostic-tools--telematics-free--open-source--free-tier) | CAN, OBD-II, V2X, Telematics | Automotive |
| [40. Hardware Security](#40-open-hardware-security--fault-injection-benches) | SCA, Fault Injection, Glitching | HW Security |
| [41. Silicon Validation](#41-post-silicon-validation--chip-debug-tools) | JTAG, BSDL, Bring-up | Chip Debug |
| [42. Robotics & AGVs](#42-open-source-robotics--agv--warehouse-automation-stacks) | ROS, SLAM, Motion Planning | Robotics |
| [43. Satellite & Space](#43-satellite--space-grade-hardware-tools) | Flight Software, Orbit, SatCom | Aerospace |
| [44. FPGA & ASIC](#44-fpga--asic-open-toolchains) | Verilog, OpenROAD, Soft-Cores | Chip Design |
| [45. Failure Analysis](#45-semiconductor-failure-analysis--reliability-tools) | Reliability, Thermal, ESD | Reliability |
| [46. RF & Antenna](#46-space-grade-rf--antenna-design-tools) | Antenna Design, Link Budget | RF/Wireless |
| [47. DSP & SDR](#47-open-source-dsp--sdr-asic-cores) | Signal Processing, Modems | DSP/Comms |
| [48. Power Electronics](#48-high-voltage--power-electronics-simulation-tools) | SMPS, Motor Control, Magnetics | Power |
| [49. Safety-Critical OS](#49-open-embedded-operating-systems-for-space--defense--safety-critical) | Space OS, Safety Certs | Critical OS |
| [50. Packaging & Assembly](#50-advanced-semiconductor-packaging--assembly-tools) | BGA, Thermal, Assembly | Packaging |
| [51. Acoustics & Piezo](#51-acoustic--ultrasonic--piezo-simulation-tools) | Ultrasonic, Piezo, Audio | Acoustics |
| [52. LiDAR & Radar](#52-lidar--radar-development-stacks-freeopen) | Point Clouds, SLAM | Perception |
| [53. Industrial Vision](#53-industrial-imaging--computer-vision-toolkits-freeopen) | Machine Vision, OCR | Vision |
| [54. Drones & UAVs](#54-autonomous-drones--uav-firmware--ground-systems) | Autopilots, GCS, Swarm | Drones |
| [55. Vibration Analysis](#55-audio--vibration-analysis--condition-monitoring-stacks-freeopen) | PdM, FFT, Machinery | Vibration |

---

## 34. AI/ML on Microcontrollers

### 🤖 TinyML Frameworks

#### **TensorFlow Lite for Microcontrollers** `[Platform: ARM, ESP32, RISC-V]` `[Status: 🟢Production]`
https://www.tensorflow.org/lite/microcontrollers

**Google's ML inference on MCUs**

- ✅ Runs models trained in TensorFlow/Keras
- ✅ Works on Cortex-M0+ and up
- ✅ RAM: 20KB+ typical
- ✅ Example: Speech recognition, gesture detection

**Supported Hardware:**
- ESP32, Arduino Nano 33 BLE, STM32, nRF52, RP2040

---

#### **Edge Impulse** `[Platform: Cloud + embedded]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.edgeimpulse.com

**End-to-end TinyML platform**

- ✅ Data collection, training, deployment
- ✅ Auto-generates C++ library
- ✅ Supports ESP32, STM32, nRF, Arduino, Raspberry Pi
- ✅ Free tier for developers

**Perfect for**: Rapid TinyML prototyping without deep ML knowledge

---

#### **CMSIS-NN** `[Platform: ARM Cortex-M]` `[Status: 🟢Production]`
https://github.com/ARM-software/CMSIS-NN

**ARM's optimized neural network kernels**

- ✅ Hand-tuned for Cortex-M cores
- ✅ Up to 5x faster than naive C
- ✅ Used by TensorFlow Lite Micro

---

### 📦 More TinyML Tools

<details>
<summary><b>ML Frameworks & Tools</b></summary>

**Frameworks:**
- **uTensor** — https://github.com/uTensor/uTensor  
  C++ ML inference for ARM Cortex-M

- **NNoM** — https://github.com/majianjia/nnom  
  Lightweight NN for MCUs

- **Eloquent TinyML** — https://eloquentarduino.com  
  Arduino ML library (simplified interface)

**Hardware Accelerators:**
- **Coral Edge TPU** — https://coral.ai  
  Google's ML accelerator (for Linux devices)

- **Kendryte K210** — RISC-V MCU with KPU (Neural Network Processor)

- **STM32 X-CUBE-AI** — https://www.st.com/en/embedded-software/x-cube-ai.html  
  Neural network deployment for STM32

</details>

<details>
<summary><b>Learning Resources</b></summary>

**Books:**
- **"TinyML" by Pete Warden & Daniel Situnayake**  
  O'Reilly, the definitive TinyML book

**Courses:**
- **Harvard CS249r: TinyML** — https://sites.google.com/g.harvard.edu/tinyml/home  
  Free online course

- **Coursera: Introduction to Embedded Machine Learning** — https://www.coursera.org

**Examples:**
- **TensorFlow Lite Micro Examples** — https://github.com/tensorflow/tflite-micro/tree/main/tensorflow/lite/micro/examples

</details>

---

## 35. Secure Boot & Cryptography

### 🔐 Trusted Execution Environments

#### **ARM TrustZone** `[Platform: Cortex-M23/M33/M55]` `[Status: 🟢Production]`
https://developer.arm.com/ip-products/security-ip/trustzone

**Hardware-enforced security boundary**

- ✅ Separates secure/non-secure worlds
- ✅ Secure boot, secure storage
- ✅ Used in STM32L5, NXP LPC55S69, Nordic nRF9160

**Frameworks:**
- **Trusted Firmware-M (TF-M)** — https://www.trustedfirmware.org/projects/tf-m  
  PSA-certified secure framework

---

#### **Secure Elements (SE) & TPMs**

<details>
<summary><b>Hardware Security Modules</b></summary>

**Secure Elements:**
- **ATECC608** (Microchip) — https://www.microchip.com/wwwproducts/en/ATECC608A  
  Hardware crypto, secure key storage, $0.50

- **SE050** (NXP) — https://www.nxp.com/products/security-and-authentication/authentication/edgelock-se050-iot-secure-element  
  Advanced SE with applets

- **STSAFE-A110** (ST) — https://www.st.com/en/secure-mcus/stsafe-a110.html

**Trusted Platform Modules (TPM):**
- **Infineon Optiga TPM** — https://www.infineon.com/cms/en/product/security-smart-card-solutions/optiga-embedded-security-solutions/optiga-tpm

</details>

---

### 🛠️ Cryptography Libraries

<details>
<summary><b>Crypto for Embedded</b></summary>

**TLS/Crypto:**
- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls
- **wolfSSL** — https://www.wolfssl.com
- **BearSSL** — https://bearssl.org (Small footprint)
- **tinycrypt** — https://github.com/intel/tinycrypt

**Post-Quantum Cryptography:**
- **liboqs** — https://openquantumsafe.org  
  Open Quantum Safe project

**Hardware Acceleration:**
- Most modern MCUs have AES, SHA, PKA accelerators
- Check vendor HAL/SDK for hardware crypto APIs

</details>

---

## 36. Formal Verification & Model Checking

### 🔬 Formal Methods

#### **SPARK Ada** `[Platform: Ada language]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.adacore.com/about-spark

**Provably correct software**

- ✅ Subset of Ada with formal contracts
- ✅ Mathematically prove absence of runtime errors
- ✅ Used in aerospace, defense, rail
- ✅ Free/open-source toolchain (GNATprove)

**Examples:**
- Tokeneer (secure entry system, fully proved)
- IRONSIDES DNS server (provably secure)

---

#### **Frama-C** `[Platform: C language]` `[Level: Pro]` `[Status: 🟢Production]`
https://frama-c.com

**Static analysis + formal verification for C**

- ✅ Prove properties of C code
- ✅ Find bugs via abstract interpretation
- ✅ ACSL (ANSI/ISO C Specification Language)

---

<details>
<summary><b>More Formal Tools</b></summary>

**Model Checkers:**
- **TLA+** — https://lamport.azurewebsites.net/tla/tla.html  
  Specify and verify concurrent systems (Leslie Lamport)

- **SPIN** — http://spinroot.com  
  Model checker for concurrent systems

- **Uppaal** — https://uppaal.org  
  Timed automata verification

**SAT/SMT Solvers:**
- **Z3** — https://github.com/Z3Prover/z3 (Microsoft)
- **CVC5** — https://cvc5.github.io

**Theorem Provers:**
- **Coq** — https://coq.inria.fr
- **Isabelle** — https://isabelle.in.tum.de
- **Lean** — https://leanprover.github.io

</details>

---

## 37. Advanced Architectures

### 🏗️ RISC-V Ecosystem

#### **RISC-V** `[Platform: Open ISA]` `[Status: 🟢Production]`
https://riscv.org

**Open-source instruction set architecture**

- ✅ No licensing fees
- ✅ Modular (RV32I, RV64G, custom extensions)
- ✅ Growing ecosystem (SiFive, Espressif, GigaDevice)

**RISC-V MCUs:**
- **ESP32-C3/C6** — https://www.espressif.com (Wi-Fi + BLE)
- **GD32VF103** — https://www.gigadevice.com (STM32-compatible pinout)
- **SiFive FE310** — https://www.sifive.com
- **Kendryte K210** — Dual-core RISC-V + KPU

**Tools:**
- **RISC-V GNU Toolchain** — https://github.com/riscv-collab/riscv-gnu-toolchain
- **PlatformIO** — Full RISC-V support
- **Zephyr RTOS** — RISC-V support

---

### 🧠 Multicore & Heterogeneous Systems

<details>
<summary><b>Multicore MCUs</b></summary>

**Dual-Core Cortex-M:**
- **STM32H745/H755** — Cortex-M7 + M4
- **RP2040** — Dual Cortex-M0+
- **ESP32** — Dual Xtensa LX6 (not ARM)
- **nRF5340** — Cortex-M33 (app) + M33 (network)

**Frameworks:**
- **OpenAMP** — https://github.com/OpenAMP/open-amp  
  Asymmetric multiprocessing framework

- **RPMsg** — Inter-processor communication

</details>

<details>
<summary><b>Heterogeneous Computing</b></summary>

**MPU + MCU:**
- **i.MX RT (NXP)** — Cortex-M7 @ 600 MHz (crossover MCU)
- **STM32MP1** — Cortex-A7 (Linux) + M4 (RTOS)

**GPU/DSP Offload:**
- **ESP32-S3** — AI acceleration instructions
- **STM32H7** — Chrom-ART (2D graphics accelerator)

</details>

---

## 38. Research & Emerging Technologies

### 🔮 Future of Embedded

<details>
<summary><b>Neuromorphic Computing</b></summary>

**Spiking Neural Networks (SNNs):**
- **Intel Loihi** — https://www.intel.com/content/www/us/en/research/neuromorphic-computing.html  
  Research neuromorphic chip

- **SpiNNaker** — https://apt.cs.manchester.ac.uk/projects/SpiNNaker  
  Brain-scale spiking neural network simulator

- **BrainChip Akida** — https://brainchip.com  
  Neuromorphic processor for edge AI

**Research:**
- More power-efficient than traditional NNs for certain tasks
- Event-driven processing

</details>

<details>
<summary><b>Energy Harvesting</b></summary>

**Power Sources:**
- **Solar** — Indoor/outdoor photovoltaics
- **Thermoelectric** — TEGs (temperature gradients)
- **Piezoelectric** — Vibration energy
- **RF Harvesting** — Ambient radio waves

**Tools:**
- **Texas Instruments BQ25570** — Ultra-low-power boost charger
- **Analog Devices ADP5090** — Energy harvesting PMIC

**Research Areas:**
- Batteryless IoT sensors
- Intermittent computing (checkpointing)

</details>

<details>
<summary><b>Quantum-Resistant Embedded</b></summary>

**Post-Quantum Cryptography (PQC):**
- **NIST PQC Standards** — https://csrc.nist.gov/projects/post-quantum-cryptography  
  CRYSTALS-Kyber (key encapsulation), CRYSTALS-Dilithium (signatures)

- **PQClean** — https://github.com/PQClean/PQClean  
  Clean implementations of PQC

**Challenge**: Larger key sizes, more computation → need optimization for MCUs

</details>

<details>
<summary><b>Ultra-Low-Power Computing</b></summary>

**Techniques:**
- **Sub-threshold operation** — Run at < 0.5V
- **Approximate computing** — Trade accuracy for power
- **Event-driven architectures**

**Research Projects:**
- **ARM Cortex-M0+** — 9 µA/MHz
- **MSP430** — Texas Instruments (sub-µA in standby)
- **Ambiq Apollo4** — SPOT™ (Subthreshold Power Optimized Technology)

</details>

<details>
<summary><b>Time-Sensitive Networking (TSN)</b></summary>

**IEEE 802.1 TSN:**
- Deterministic Ethernet for industrial automation
- Replace CAN/EtherCAT with standard Ethernet
- **OPC UA over TSN** — Industry 4.0 standard

**Chips:**
- **NXP LS1028A** — TSN-enabled processor
- **TI Sitara AM64x** — Industrial TSN

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Compliance & Standards](compliance.md)
- [← Documentation & Learning](documentation-learning.md)

---

## 📚 Research Papers & Academic Resources

<details>
<summary><b>Top Conferences</b></summary>

- **EMSOFT** — ACM Conference on Embedded Software
- **RTAS** — Real-Time and Embedded Technology and Applications Symposium
- **DATE** — Design, Automation & Test in Europe
- **DAC** — Design Automation Conference
- **CASES** — Compilers, Architecture, Synthesis for Embedded Systems

</details>

<details>
<summary><b>Academic Journals</b></summary>

- **IEEE Embedded Systems Letters**
- **ACM Transactions on Embedded Computing Systems**
- **Real-Time Systems Journal**
- **Journal of Systems Architecture**

</details>

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
### 39. Automotive Diagnostic Tools & Telematics (Free / Open-Source / Free-Tier)

#### I. Automotive Diagnostic Stacks (Free/Open)

- **SavvyCAN (Free/Open-Source)** — https://github.com/collin80/SavvyCAN  
  Powerful CAN bus analyzer supporting DBC files, sniffing, replay, reverse engineering vehicle ECUs.

- **socketCAN / can-utils (Free/Open)** — https://github.com/linux-can/can-utils  
  Native Linux CAN stack. Tools for logging, injecting frames, UDS diagnostics, replaying ECUs.

- **python-can (Free/Open)** — https://github.com/hardbyte/python-can  
  Python interface for CAN hardware (USB, PCAN, Kvaser, CANtact, Peak). Perfect for writing custom diagnostics.

- **cangaroo (Free/Open)** — https://github.com/GENIVI/cangaroo  
  CAN bus analyzer with GUI and DBC file support. Good for reverse engineering automotive frames.

- **UDS (ISO 14229) Open Implementations** — https://github.com/openxc/uds  
  Open-source diagnostic protocol implementation for unlocking DTCs, live parameters, ECU resets.

- **OBD-II PID Libraries (Free/Open)** — https://github.com/brendan-w/obd  
  Read vehicle parameters using ELM327 or USB-CAN devices; works on Linux/Android.

#### II. CAN, LIN, FlexRay Tools (Free/Open)

- **cantools (Free/Open)** — https://github.com/eerimoq/cantools  
  Parse, decode, encode DBC, KCD, ARXML automotive network files.

- **openxc (Free/Open)** — https://github.com/openxc/openxc-platform  
  Open telematics stack with signal decoding layers for modern vehicles.

- **CANdevStudio (Free/Open)** — https://github.com/julianstorer/CANdevStudio  
  GUI app to send/receive CAN frames, analyze traffic and simulate ECUs.

- **BusMaster (Free/Open)** — https://rbei-etas.github.io/busmaster  
  Automotive-grade CAN/LIN bus analyzer for Windows.

- **CANtact Firmware + Tools (Free/Open)** — https://github.com/CANtact  
  Open-source hardware and firmware for low-cost CAN interfaces.

#### III. GPS / GNSS / Telemetry Tools (Free/Open)

- **gpsd (Free/Open)** — https://gpsd.gitlab.io/gpsd  
  Collect GNSS data and feed it to telematics systems. Supports USB GPS modules, NMEA, RTK modules.

- **Traccar (Free/Open)** — https://www.traccar.org  
  Self-hosted telematics server with dashboards, geofencing, alerts, multiple protocol/device support.

- **OwnTracks (Free/Open)** — https://owntracks.org  
  MQTT-based location tracking and telematics reporting platform.

- **OpenStreetMap (Free/Open)** — https://www.openstreetmap.org  
  Open mapping data for routing, geofencing, fleet visualizations.

#### IV Fleet / Telematics Platforms (Free-Tier / Open)

- **ThingsBoard Community (Free/Open)** — https://thingsboard.io  
  Asset tracking, telemetry dashboards, rules engine, MQTT integrations for vehicle data.

- **Grafana OSS with GPS Plugins (Free/Open)** — https://grafana.com  
  Geospatial dashboards for telematics.

- **Traccar + InfluxDB + Grafana (Open Stack)** — popular free self-host setup for vehicle fleets.

#### V. Vehicle Reverse Engineering (Free/Open)

- **Kayak (Free/Open)** — https://github.com/dschanoeh/Kayak  
  GUI CAN tool for sniffing, injecting, decoding and DBC editing.

- **CANalyze (Free/Open)** — https://github.com/jonathankang/canalyze  
  Python-based CAN signal reverse-engineering toolkit.

- **CANard (Free/Open)** — https://github.com/ericevenchick/canard  
  Script CAN frames, fuzz ECUs, explore diagnostics.

- **PyOBD / OBD Auto Doctor (Free Editions)** — basic OBD-II analysis.

#### VI. Vehicle-to-Everything (V2X) / DSRC / C-V2X (Free Resources)

- **OpenC2X (Free/Open)** — https://github.com/OpenC2X/openc2x  
  Open-source V2X stack for DSRC and ETSI ITS-G5 research.

- **Vanetza (Free/Open)** — https://github.com/riebl/vanetza  
  ETSI ITS-G5 communication stack used in autonomous car research.

- **Open Source C-V2X Repos (Free)** — reference implementations from academia for V2X PHY/MAC.

#### VII. Telematics Hardware / Firmware (Free/Open)

- **OpenXC Vehicle Interface (Free/Open)** — https://github.com/openxc  
  Open hardware for capturing CAN data over USB/Bluetooth and exporting normalized metrics.

- **Arduino OBD-II Libraries (Free/Open)** — ELM327 + UART stacks for DIY telematics.

- **Raspberry Pi CAN HAT Tools (Free/Open)** — SocketCAN enabled, ready-to-use telematics edge node.

- **TTGO/ESP32 CAN Modules (Open Firmware Projects)** — multiple community projects for BLE+CAN telemetry.

#### VIII. Cloud Integrations for Telematics (Free-Tier)

- **AWS IoT Core Free Tier** — MQTT ingestion, rules, dynamodb/logging.
- **GCP Pub/Sub & BI Free Tier** — pipeline for telematics data.
- **Azure IoT Hub Free Tier** — registry, commands, digital twins.
- **Balena (Free Tier)** — remote OTA for in-vehicle SBC gateway.

#### IX. Bonus — Automotive Dashboards (Free/Open)

- **Grafana Map Panels (Free/Open)** — live GPS, fleet, route, idling analysis.
- **InfluxDB + Chronograf (Free)** — telematics metrics, speed, fuel usage.
- **OpenStreetMap Tile Servers (Free/Open)** — self-hostable maps for fleets.

### 40. Open Hardware Security & Fault Injection Benches  
_Free and open-source tools, projects, and research frameworks for hardware security testing, side-channel analysis, and physical attack experimentation on embedded systems._

#### I. Hardware Security Research Frameworks (Free / Open-Source)

- **OpenTitan (Free/Open)** — https://opentitan.org  
  Open silicon Root-of-Trust (RoT) project by Google & LowRISC. Includes reference design for secure boot, key management, crypto accelerators.

- **ChipWhisperer (Free/Open)** — https://chipwhisperer.io  
  The most popular open-source platform for side-channel and fault injection research. Includes hardware kits, Python APIs, and tutorials.

- **NewAE ChipSHOUTER Resources (Free Docs)** — https://wiki.newae.com  
  Electromagnetic fault injection (EMFI) hardware and methodology — open documentation for EM pulse testing.

- **LowRISC SoC (Free/Open)** — https://lowrisc.org  
  Open RISC-V SoC with secure enclave and debug interface locking — used for hardware trust research.

- **Project Vault (Free/Open)** — https://github.com/google/project-vault  
  Google’s open hardware security token implementing secure storage and communication primitives.

#### II. Side-Channel Analysis (SCA) Tools (Free/Open)

- **ChipWhisperer Analyzer (Free/Open)** — https://github.com/newaetech/chipwhisperer  
  Python toolkit for power trace capture, correlation power analysis (CPA), and differential power analysis (DPA).

- **SCALib (Free/Open)** — https://github.com/simple-crypto/SCALib  
  A library for statistical and leakage analysis for side-channel research.

- **Riscure Inspector Lite (Free Academic)** — https://www.riscure.com  
  Free academic version for learning side-channel leakage testing and fault analysis.

- **Binsec/Rel (Free/Open)** — https://binsec.github.io  
  Binary analysis and formal verification tool for reverse engineering and firmware security.

- **DPA Contest Datasets (Free/Open)** — https://www.dpacontest.org  
  Public datasets for power traces on AES/SHA implementations, used for benchmarking SCA tools.

#### III. Fault Injection & Glitching (Free/Open)

- **ChipWhisperer Glitch Module (Free/Open)** — included in ChipWhisperer hardware.  
  Used to perform voltage, clock, and EM glitching attacks on MCUs, SoCs, and smartcards.

- **ChipFail (Free/Open)** — https://github.com/ChipFail/ChipFail  
  Repository of open-source EMFI, laser fault injection, and glitching experiments with reproducible setups.

- **GlitchKit (Free/Open)** — community scripts and firmware for low-cost fault injection using MCUs and GPIO-based timing control.

- **uGlitcher (Free/Open)** — https://github.com/uglich/uGlitcher  
  Python-based framework for glitching using Raspberry Pi or STM32 hardware.

- **GlitchThis (Free/Open)** — https://github.com/AlessandroAU/GlitchThis  
  Minimal open-source power glitching and trigger control system.

#### IV. Reverse Engineering & Debug Tools (Free/Open)

- **Ghidra (Free/Open)** — https://ghidra-sre.org  
  Reverse-engineering tool from the NSA. Disassembles binaries for ARM, MIPS, RISC-V and more.

- **Radare2 / Cutter (Free/Open)** — https://rada.re / https://cutter.re  
  Open-source reverse-engineering and analysis suite with GUI and scripting.

- **Binwalk (Free/Open)** — https://github.com/ReFirmLabs/binwalk  
  Extracts, analyzes, and identifies components within firmware images.

- **Flashrom (Free/Open)** — https://flashrom.org  
  Utility for reading/writing SPI flash chips — used in firmware extraction and patching.

- **JTAGenum (Free/Open)** — https://github.com/cyphunk/JTAGenum  
  Scans and detects active JTAG pins on unknown hardware targets.

- **OpenOCD (Free/Open)** — https://openocd.org  
  Debugger and flash programming tool for ARM, RISC-V, and other MCUs.

#### V. Secure Element & TPM Research Tools (Free/Open)

- **tpm2-tools (Free/Open)** — https://github.com/tpm2-software/tpm2-tools  
  Utilities for interacting with TPM 2.0 chips. Used for attestation, keys, and PCR management.

- **YubiHSM2 SDK (Free/Open)** — https://developers.yubico.com/YubiHSM2/  
  SDK and examples for secure key storage and cryptographic operations in hardware.

- **SEcube (Free/Open)** — https://secube.eu  
  Open hardware security module with crypto processor, USB interface, and reference firmware.

- **CryptoAuthLib (Free/Open)** — https://github.com/MicrochipTech/cryptoauthlib  
  Microchip ATECC608/508 secure element library and examples.

- **OpenSCA (Free/Open)** — https://github.com/OpenSCA  
  Open-source framework for developing secure hardware analysis tools.

#### VI. Hardware Forensics & Board Analysis Tools (Free/Open)

- **sigrok / PulseView (Free/Open)** — https://sigrok.org  
  Logic analyzer suite with protocol decoders for UART, SPI, I²C, CAN — essential for hardware reverse-engineering.

- **KiCad + Netlist Viewers (Free/Open)** — https://kicad.org  
  Inspect hardware schematics, trace security-sensitive nets, verify crypto paths.

- **OpenBoardView (Free/Open)** — https://openboardview.org  
  View PCB layouts and pin connections for reverse engineering and repair.

- **Fritzing (Free/Open)** — https://fritzing.org  
  Educational tool for visualizing and understanding circuit-level designs.

- **FreeCAD (Free/Open)** — https://www.freecad.org  
  Analyze mechanical design aspects of tamper-proof enclosures and physical security.

#### VII. Hardware Security Education & Labs (Free/Open)

- **HardwareSecurity.training (Free)** — https://hardwaresecurity.training  
  Collection of open labs and resources for hardware hacking, side-channel, and tamper analysis.

- **Hackaday.io Hardware Security Projects (Free)** — https://hackaday.io/projects  
  DIY open projects for EMFI, glitching, secure element programming, board decapping.

- **NYU OSIRIS Lab Hardware Labs (Free)** — https://osiris.cyber.nyu.edu  
  Academic lab materials for fault injection, chip analysis, and side-channel attacks.

- **Cyber-Security Evaluation Lab (Free/Open)** — https://www.ciselab.com (academic repositories)  
  Reference frameworks for hardware trust and countermeasure validation.

#### VIII. Bonus — Post-Quantum & Hardware Crypto Research (Free/Open)

- **libOQS (Free/Open)** — https://openquantumsafe.org  
  Open quantum-safe crypto library for benchmarking hardware implementations.

- **PQShield Whitepapers (Free)** — https://pqshield.com/resources  
  Open educational resources on post-quantum cryptography and hardware secure elements.

- **OpenCryptoHW (Free/Open)** — https://github.com/OpenCryptoProject  
  Collection of open-source hardware cryptography IP cores for FPGA/ASIC evaluation.

### 41. Post-Silicon Validation & Chip Debug Tools  
_Free / open-source utilities for validating SoCs, MCUs, and processors after fabrication — covering JTAG/SWD, firmware loading, trace, boundary-scan, fault isolation and silicon bring-up._

#### I. Low-Level Debug & Bring-Up Tools (Free/Open)

- **OpenOCD (Free/Open-Source)** — https://openocd.org  
  Universal JTAG/SWD debugging for ARM, RISC-V, ESP32 and custom SoCs. Supports GDB, boundary-scan, flash programming and secure debug workflows.

- **PyOCD (Free/Open)** — https://github.com/pyocd/pyOCD  
  JTAG/SWD debug for Cortex-M. Includes flash loader, memory viewer, RTOS thread view and scripting in Python.

- **OpenTitan ‘Silicon Creator’ Tools (Free/Open)** — https://opentitan.org  
  Secure boot ROM bring-up, post-silicon self-test, debug unlock flows, life-cycle states.

- **ESP-IDF Open Debug Stack (Free/Open)** — https://github.com/espressif/esp-idf  
  Post-silicon validation with OpenOCD + GDB for ESP32 family; JTAG, boundary-scan and trace features.

- **J-Link OpenOCD Interface (Free/Open)** — community drivers enabling J-LINK hardware with open debug stacks.

#### II. JTAG, Scan Chain & Boundary-Scan (Free/Open)

- **UrJTAG (Free/Open-Source)** — http://urjtag.org  
  Boundary-scan testing, flash programming, BSDL parsing — used for board-level post-silicon validation.

- **Jtagulator (Open Hardware + Free Tooling)** — https://github.com/grandideastudio/jtagulator  
  Automatic JTAG/SWD/UART pin-out detection for unknown SoCs. Essential for silicon bring-up and reverse engineering.

- **JTAGenum (Free/Open)** — https://github.com/cyphunk/JTAGenum  
  Detect JTAG signals on unknown PCBs to enable debug access.

- **BSV / Open Boundary-SCAN Viewers (Free)** — several GitHub projects letting you check BSDL nets for post-silicon faults.

#### III. Logic Analyzers & Trace (Free/Open)

- **sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Open logic analyzer suite with 100+ protocol decoders. Used for validating SPI/I2C/UART timing, busses and bring-up.

- **Saleae Logic Open SDK (Free APIs)** — APIs for automated validation traces and signal inspection in manufacturing.

- **LAP-C / FX2LA open firmware (Free/Open)** — cheap FX2-based logic analyzers with open firmware + sigrok support.

- **OpenTrace (Free/Open)** — open trace-capture tools for proprietary debug interfaces (community maintained).

#### IV. Silicon-Level Fault Isolation (Free/Open)

- **ChipWhisperer Analyzer (Free/Open)** — https://chipwhisperer.io  
  Useful during post-silicon security validation to detect timing glitches, power faults, or side-channel leakage.

- **GlitchKit / ChipFail (Free/Open)** — open hardware fault-injection methods to test glitch resistance of SoCs & secure boot.

- **Renode (Free/Open)** — https://renode.io  
  Co-simulate SoC peripherals + firmware to reproduce silicon bugs and compare against real hardware logs.

- **QEMU + Plugins (Free/Open)** — emulate ARM/MIPS/RISC-V for differential testing vs real silicon behavior.

#### V. RISC-V / Open Silicon Validation (Free/Open)

- **RISC-V DV (Free/Open)** — https://github.com/google/riscv-dv  
  Random instruction generator + compliance suite for post-silicon CPU verification.

- **OpenHW Group CORE-V Verification (Free/Open)** — https://github.com/openhwgroup  
  Full UVM-based verification environment for open RISC-V cores.

- **OpenTitan DV (Free/Open)** — https://github.com/lowRISC/opentitan  
  Industrial-grade verification framework: UVM, testbenches, assertions, coverage dashboards.

- **riscv-compliance (Free/Open)** — official compliance suite for validating RISC-V ISA behavior on new silicon.

#### VI. FPGA SoC Bring-Up (Free/Open)

- **LiteX (Free/Open)** — https://github.com/enjoy-digital/litex  
  Build FPGA SoCs + debug buses, logic analyzers, UART prints — excellent for early silicon prototyping.

- **Migen + LiteScope (Free/Open)** — embedded logic analyzer for on-chip waveform capture.

- **OpenFPGA Tools (Free/Open)** — SymbiFlow, Verilator, GHDL for validating soft-cores before tape-out.

#### VII. Board-Level Post-Silicon Test (Free/Open)

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Production test automation for boards: power-on tests, UART/JTAG scriptable bring-up, functional validation.

- **pytest + PyVISA + SCPI (Free/Open)** — automation for oscilloscopes, PSUs, SMUs — log waveforms, power tests, startup timing.

- **Open Manufacturing Bench Repos (Free)** — community Python fixtures to automate flashing, current measurement, thermal tests.

#### VIII. Manufacturing & Yield Debug (Free/Open)

- **InfluxDB OSS + Grafana OSS (Free)** — capture yield metrics, flash failures, boot failures, calibration logs during silicon bring-up.

- **Elasticsearch + Kibana (Free/Open)** — log thousands of board results, find systematic silicon or solder-joint issues.

- **Open Serial Loggers (Free)** — automatic logging of boot traces, crashes, panic dumps for lot screening.

#### IX. Datasheet & Model Verification (Free)

- **SVUnit (Free/Open)** — https://github.com/svunit/svunit  
  SystemVerilog unit testing for HDL — validate RTL fixes discovered during post-silicon bring-up.

- **Verilator (Free/Open)** — https://www.veripool.org/verilator  
  Fast SystemVerilog simulator to reproduce silicon bugs offline.

- **GHDL (Free/Open)** — https://github.com/ghdl/ghdl  
  VHDL simulator for verifying behavioral and gate-level issues.

### 42. Open-Source Robotics / AGV / Warehouse Automation Stacks  
_Free and open-source software frameworks for autonomous robots, industrial AGVs/AMRs, warehouse automation, motion planning, perception and control._

#### I. Full Robotics Frameworks (Free / Open-Source)

- **ROS (Robot Operating System) (Free/Open)** — https://www.ros.org  
  Global standard robotics middleware: navigation, SLAM, mapping, drivers, hardware abstraction. Huge ecosystem.

- **ROS 2 (Free/Open)** — https://docs.ros.org/en/rolling  
  Industrial-grade real-time ROS using DDS. Used for AGVs, collaborative robots, factory automation.

- **ROS-Industrial (Free/Open)** — https://rosindustrial.org  
  Industrial extensions: real robot drivers, motion planners, vision, conveyor integration, safety.

- **YARP (Free/Open)** — https://www.yarp.it  
  Modular robotics framework for humanoids, manipulators, service robots.

- **Player/Stage/Gazebo Stack (Free/Open)** — legacy but still used in education and research.

#### II. Motion Planning Libraries (Free/Open)

- **MoveIt (Free/Open)** — https://moveit.ros.org  
  Widely used motion-planning framework: kinematics, collision avoidance, trajectory generation, robot arms & manipulators.

- **OMPL – Open Motion Planning Library (Free/Open)** — https://ompl.kavrakilab.org  
  Sampling-based motion planning library used in MoveIt and custom AGV navigation.

- **CHOMP / STOMP / TrajOpt (Free/Open)** — advanced motion planners for industrial robots.

- **Tesseract (Free/Open)** — https://github.com/tesseract-robotics/tesseract  
  Industrial motion planning and environment modeling used in automation.

#### III. SLAM, Perception & Localization (Free/Open)

- **Cartographer (Google) (Free/Open)** — https://google-cartographer.readthedocs.io  
  Real-time indoor SLAM for AGVs and warehouse robots.

- **Hector SLAM (Free/Open)** — https://wiki.ros.org/hector_slam  
  High-performance 2D SLAM for LIDAR-based AMRs.

- **GMapping (Free/Open)** — https://github.com/OpenSLAM-org/gmapping  
  Classic 2D SLAM for laser AMRs and vacuum robots.

- **RTAB-Map (Free/Open)** — http://introlab.github.io/rtabmap  
  Visual SLAM for RGB-D sensors, depth cameras, stereo rigs.

- **OpenVSLAM (Free/Open)** — https://openvslam.readthedocs.io  
  Stereo/Mono/ROS support — mapping warehouses and shops.

- **Kalibr (Free/Open)** — https://github.com/ethz-asl/kalibr  
  Multi-sensor calibration for IMU + camera + LIDAR.

#### IV. Navigation & AGV Stacks (Free/Open)

- **ROS Navigation Stack (Free/Open)** — https://wiki.ros.org/navigation  
  Global planning, local planning, obstacle avoidance, costmaps for warehouse AGVs.

- **ROS2 Navigation2 (Free/Open)** — https://navigation.ros.org  
  Next-gen real-time navigation — AMRs, multi-robot dispatching.

- **Open-RMF (Open Robotics Fleet Management) (Free/Open)** — https://openrmf.org  
  Fleet orchestration for multiple AMRs/AGVs, traffic control, elevators, doors, charging, scheduling.

- **MRPT (Free/Open)** — https://www.mrpt.org  
  Perception, SLAM, localization, math blocks — C++ robotics toolkit.

- **Mobile Robot Programming Toolkit (MRPT) Datasets (Free)** — SLAM and localization benchmark data.

#### V. Low-Level Control, Kinematics, Dynamics

- **Orocos (RTT) (Free/Open)** — https://www.orocos.org  
  Real-time control framework for industrial manipulators and automation.

- **Drake (MIT) (Free/Open)** — https://drake.mit.edu  
  Dynamics, control, trajectory optimization for robotic systems.

- **Pinocchio (Free/Open)** — https://github.com/stack-of-tasks/pinocchio  
  Fast kinematics and dynamics library used in humanoids and industrial arms.

- **Rigid Body Dynamics Library (RBDL) (Free/Open)** — https://rbdl.readthedocs.io  
  Efficient rigid-body dynamics for simulation and control.

#### VI. Vision & Object Detection (Free/Open)

- **OpenCV (Free/Open)** — https://opencv.org  
  Full computer vision toolkit, used for barcode readers, object pick-and-place, conveyors, safety zones.

- **Darknet / YOLO (Free/Open)** — https://github.com/AlexeyAB/darknet  
  Real-time object detection for robots, pickers, palletizers.

- **OpenPTrack (Free/Open)** — https://openptrack.org  
  Multi-camera people tracking, used in warehouse and HMI robotics.

#### VII. Simulators for Robot Labs (Free/Open)

- **Gazebo / Ignition Robotics (Free/Open)** — https://gazebosim.org  
  3D physics simulator with sensors, conveyors, forklifts, pallet movers, machine vision.

- **Webots (Free/Open)** — https://cyberbotics.com  
  Virtual factory floors, manipulators, conveyor belts, AGVs.

- **AirSim (Free/Open)** — https://github.com/microsoft/AirSim  
  Drones & ground vehicles with depth cameras, IMU, GPS.

- **CoppeliaSim (Free Student/Open)** — https://www.coppeliarobotics.com  
  Pick-and-place cells, robotic arms, conveyors, PLC links.

#### VIII. Multi-Robot Coordination / Warehouse Automation

- **Open-RMF Dispatcher (Free/Open)** — https://openrmf.org  
  Orchestration for dozens of AMRs/AGVs, traffic control, shared resources, elevators and pathways.

- **Fleet Management Plugins for ROS2 (Free/Open)** — GitHub packages enabling missions, dispatching, charging logic.

- **Rapyuta.io Free Tier (Cloud Robotics)** — https://rapyuta.io  
  Cloud-based fleet, teleop, logging, route planning (free developer tier).

#### IX. AGV Hardware / Firmware (Free/Open)

- **ROS-Control (Free/Open)** — motion control and actuator drivers for mobile robots.

- **ROS Serial / Micro-ROS (Free/Open)** — https://micro.ros.org  
  Use STM32/ESP32/PIC for low-level control communicating with ROS2 over DDS.

- **Open Motor Controller Repos** — BLDC/FOC/H-bridge drivers for AMRs (VESC, ODrive are open software stacks).

- **Open-Source LIDAR Stacks** — RPLIDAR, Slamtec, YDLIDAR ROS drivers.

#### X. Mapping / Geofencing / Dispatch Dashboards

- **RViz & RViz2 (Free/Open)** — ROS visualization of map, trajectories, LiDAR, obstacles.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Robotics data visualization: logs, LIDAR, IMU, CAN, maps — browser dashboards.

- **Grafana OSS + InfluxDB (Free/Open)** — live monitoring of fleet health, battery, uptime, missions.

#### XI. Robotics Learning & Academic Repos (Free/Open)

- **Modern Robotics (Free Online Course)** — kinematics, motion planning, dynamics.
- **MIT OCW Robotics (Free)** — perception, control, SLAM.
- **ETH Zurich Autonomous Systems Labs (Free Papers)** — advanced AMR/AGV work.
- **OpenSLAM Paper Library (Free)** — collection of SLAM algorithms & datasets.

### 43. Satellite & Space-Grade Hardware Tools  
_Free/open tools for space avionics, satellite communications, RF link planning, space-grade electronics design, radiation testing, orbital mechanics and mission simulation._

#### I. Satellite Mission Design & Orbital Mechanics (Free/Open)

- **GMAT – General Mission Analysis Tool (Free/Open)** — https://gmat.gsfc.nasa.gov  
  NASA’s open-source mission design suite. Orbit propagation, spacecraft dynamics, maneuver planning, formation flying.

- **Orekit (Free/Open)** — https://www.orekit.org  
  High-precision orbital mechanics in Java. Used in flight dynamics, GNSS, attitude control, Earth observation.

- **POLARIS / Open Source Astrodynamics (Free)** — community orbital analysis and visualization tools.

- **STK Free Version (Limited Free)** — https://www.agi.com/products/stk  
  Popular aerospace modeling suite; free version supports basic orbit modeling, ground stations, coverage.

- **JSatTrak (Free/Open)** — https://jsattrak.sourceforge.net  
  Real-time orbit visualization, tracking, TLE import and mission planning.

- **OpenSpace (Free/Open)** — https://openspaceproject.com  
  NASA-backed visualization of spacecraft, planetary bodies, ground tracks.

#### II. Ground Stations & SDR for SatCom (Free/Open)

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Build satellite modems, telemetry decoders, FSK/QPSK/FSK demodulators, ground station DSP pipelines.

- **SatNogs (Free/Open)** — https://satnogs.org  
  Global open-source satellite ground station network. Antenna rotator designs, demodulators, dashboards.

- **Gpredict (Free/Open)** — https://gpredict.oz9aec.net  
  Live satellite tracking, Doppler correction, rotor control, radio control for receiving telemetry.

- **CSP – CubeSat Space Protocol (Free/Open)** — https://github.com/libcsp/libcsp  
  Lightweight space networking stack for nanosatellites and CubeSats.

- **libtelemetry (Open)** — community modems and decoders for amateur satellites and CubeSats.

- **OpenLST (Free/Open)** — https://github.com/openlst/openlst  
  Long-range telemetry radio system used in NASA Ames’ small-sat missions (open hardware + firmware).

#### III. Space-Grade Electronics, Radiation & Reliability (Free/Public)

- **NASA EEE Parts Lists & Radiation Guides (Free)** — https://nepp.nasa.gov  
  Space-qualified parts databases, radiation effects, derating and reliability handbooks.

- **NASA Radiation Effects Data (Free)** — SEE, SEL, TID test data for COTS components.

- **ECSS Standards (Free PDFs)** — https://ecss.nl  
  European Cooperation for Space Standardization — thermal, mechanical, software, electronics design requirements.

- **ESA Space Engineering Docs (Free)** — https://escies.org  
  Materials, components, failure analysis, derating rules, FPGA guidelines.

- **NASA Lessons Learned Database (Free)** — https://llis.nasa.gov  
  Failures, anomalies, design pitfalls from real missions.

- **Texas Instruments Space-Grade Guides (Free)** — radiation-tolerant power, data converters, logic, isolation.

#### IV. Satellite SDR Demodulators (Free/Open)

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio blocks for decoding dozens of CubeSat and amateur satellite telemetry formats.

- **DireWolf (Free/Open)** — https://github.com/wb2osz/direwolf  
  AX.25, APRS, telemetry decoding — used by amateur satellites.

- **OpenLST Modem (Free/Open)** — open-source robust satcom modem (FSK/GFSK) with flight heritage.

- **CSP + FreeRTOS Satellite Stacks (Open)** — real flight-ready nanosat firmware examples.

#### V. Flight Software, GNC & Satellite OS (Free/Open)

- **NASA cFS – Core Flight System (Free/Open)** — https://cfs.gsfc.nasa.gov  
  Flight-proven satellite flight software framework: commands, telemetry, apps, embedded OS abstraction.

- **F Prime (NASA JPL) (Free/Open)** — https://fprime.jpl.nasa.gov  
  Modular flight software framework used on Mars Helicopter, CubeSats, and deep space missions.

- **NOS3 (Free/Open)** — https://github.com/nasa/nos3  
  CubeSat simulation & avionics test framework: ground station links, environment models, virtual hardware.

- **OpenSatKit (Free/Open)** — https://github.com/OpenSatKit  
  Flight software + ground system + training + drivers for nanosats (built on NASA cFS).

- **OpenMCT (Free/Open)** — https://github.com/nasa/openmct  
  NASA’s open mission control dashboard: telemetry, command, timeline, events.

- **OREKIT + cFS combo examples (Open)** — flight dynamics + flight software integration.

#### VI. Satellite Simulation & Digital Twins (Free/Open)

- **NOS Engine (Free/Open)** — open network-layer simulator for flight software testing.

- **GMAT Mission Simulation (Free/Open)** — full dynamics modeling for thrusters, staging, attitude control.

- **POLYSAT Sims (Free)** — open academic tools for small satellite bus simulation.

- **CSP-in-the-loop Simulators (Free/Open)** — simulate CubeSat comms networks and ground station telemetry.

#### VII. Thermal, Power & Reliability Tools (Free/Public)

- **Thermal Desktop Free Samples (Docs)** — spacecraft thermal control whitepapers.

- **NASA Thermal Control Handbook (Free PDFs)** — radiator, heater, coating models.

- **CubeSat Power Budget Tools (Free Sheets)** — community spreadsheets for solar, battery, eclipse time.

- **ESA Propulsion & Power Handbooks (Free)** — thruster sizing, reaction wheels, momentum dumping.

#### VIII. Amateur Radio & Education (Free/Open)

- **AMSAT Resources (Free/Open)** — https://www.amsat.org  
  Educational satellites, telemetry formats, SDR tutorials.

- **CubeSat Design Spec (Free PDF)** — Cal Poly CubeSat specification for educational missions.

- **SatNOGS Ground Station Hardware (Open Hardware)** — 3D printed rotors, LNA designs, SDR builds.

### 44. FPGA / ASIC Open Toolchains  
_Free and open-source EDA flows, HDL tools, soft-core CPUs, simulation, synthesis, place-and-route, verification and post-silicon debug for FPGA & ASIC design._

#### I. Full FPGA Open Toolchains (RTL → Bitstream)

- **Project Icestorm (Free/Open)** — https://github.com/YosysHQ/icestorm  
  Fully open-source toolchain for Lattice iCE40 FPGAs: synthesis, P&R, bitstream generation.

- **Project Trellis (Free/Open)** — https://github.com/YosysHQ/prjtrellis  
  Reverse-engineered open toolchain for Lattice ECP5 family. Works with nextpnr + Yosys.

- **Project X-Ray (Free/Open)** — https://github.com/f4pga/prjxray  
  Parts of the open XC7 flow (Xilinx 7-series) used in F4PGA. Enables open bitstream generation.

- **F4PGA (Free/Open)** — https://f4pga.org  
  Unified open FPGA development stack for iCE40, ECP5, and Xilinx parts. Synthesis + P&R + bitstream.

- **nextpnr (Free/Open)** — https://github.com/YosysHQ/nextpnr  
  Portable P&R tool with multiple backends (iCE40, ECP5, Nexus). Works with Yosys + Icestorm/Trellis.

- **openFPGALoader (Free/Open)** — https://github.com/trabucayre/openFPGALoader  
  Flash/program a huge range of FPGAs with open drivers (Lattice, Xilinx, Intel, Microchip).

#### II. HDL Synthesis & Simulation (Free/Open)

- **Yosys (Free/Open)** — https://github.com/YosysHQ/yosys  
  Gold-standard open-source Verilog synthesis for FPGA/ASIC, supports SystemVerilog subsets.

- **Verilator (Free/Open)** — https://www.veripool.org/verilator  
  Fast SystemVerilog simulator that compiles designs into C++. Used heavily in silicon verification.

- **GHDL (Free/Open)** — https://github.com/ghdl/ghdl  
  VHDL simulator for testbenches, waveform dumping, coverage.

- **Cocotb (Free/Open)** — https://github.com/cocotb/cocotb  
  Python-based co-simulation testbench framework — drive HDL from Python.

- **Icarus Verilog (Free/Open)** — http://iverilog.icarus.com  
  Lightweight Verilog simulator for education and simple testbenches.

- **GTKWave (Free/Open)** — http://gtkwave.sourceforge.net  
  Waveform viewer for VCD/FST/LXT traces.

#### III. Open Soft-Core CPUs for FPGA & ASIC

- **RISC-V Rocket Chip (Free/Open)** — https://github.com/chipsalliance/rocket-chip  
  Berkeley’s open RISC-V SoC generator — Linux-capable, used for ASIC tape-outs.

- **PicoRV32 (Free/Open)** — https://github.com/cliffordwolf/picorv32  
  Ultra-small RISC-V core used in iCE40/ECP5 FPGAs.

- **VexRiscv (Free/Open)** — https://github.com/SpinalHDL/VexRiscv  
  Configurable RISC-V core written in SpinalHDL. Very popular in open FPGA SoCs.

- **OpenTitan Ibex Core (Free/Open)** — https://github.com/lowRISC/ibex  
  Safety/security-focused RISC-V core with verification suites.

- **SERV (Free/Open)** — https://github.com/olofk/serv  
  “Smallest RISC-V CPU” — fits in tiny LUT counts for ultra-low-cost FPGAs.

#### IV. Open ASIC Flows (RTL → GDS)

- **OpenROAD (Free/Open)** — https://theopenroadproject.org  
  Fully open RTL-to-GDSII flow using industry algorithms. One-click ASIC implementation.

- **OpenLane (Free/Open)** — https://github.com/The-OpenROAD-Project/OpenLane  
  SkyWater/SiliconCompiler-based ASIC flow: synthesis, floorplan, P&R, DRC, LVS, signoff.

- **SkyWater 130nm PDK (Free/Open)** — https://github.com/google/skywater-pdk  
  First open-source foundry PDK. Used for real taped-out chips (Google shuttle).

- **SiliconCompiler (Free/Open)** — https://siliconcompiler.com  
  Python-based compiler that orchestrates full ASIC toolchains: Yosys, OpenROAD, Magic, KLayout.

- **Caravel Harness (Free/Open)** — https://github.com/efabless/caravel  
  Pre-built SoC wrapper for integrating open ASIC hard macros into SkyWater shuttle projects.

- **Efabless MPW Shuttles (Free for Open Designs)** — https://efabless.com  
  Free ASIC fabrication runs funded by Google for open-source chips.

#### V. Physical Verification / Layout Tools (Free/Open)

- **Magic VLSI (Free/Open)** — http://opencircuitdesign.com/magic  
  Classic open silicon layout + DRC/LVS — used in real tape-outs.

- **KLayout (Free/Open)** — https://klayout.de  
  GDS viewer/editor with DRC, LVS, scripting.

- **Netgen (Free/Open)** — http://opencircuitdesign.com/netgen  
  LVS comparison between schematic and layout.

- **OpenSTA (Free/Open)** — https://github.com/The-OpenROAD-Project/OpenSTA  
  Static timing analysis for ASIC signoff.

#### VI. FPGA SoC Frameworks

- **LiteX (Free/Open)** — https://github.com/enjoy-digital/litex  
  Build FPGA SoCs: CPUs, DDR, Ethernet, PCIe, HDMI, soft peripherals, Wishbone/AXI.

- **Migen (Free/Open)** — Python HDL for building FPGA logic, compatible with LiteX cores.

- **LiteScope (Free/Open)** — embedded logic analyzer for FPGA internal waveforms.

- **Amaranth HDL (Free/Open)** — https://github.com/amaranth-lang/amaranth  
  Python HDL successor to Migen, supports Yosys flows.

#### VII. FPGA Debug / Post-Silicon (Free/Open)

- **Sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Works with many USB logic analyzers for FPGA pinwave debugging.

- **OpenFPGAloader (Free/Open)** — flash/program a wide range of FPGAs via USB/JTAG.

- **Open JTAG / FTDI Tools (Free/Open)** — open drivers for programming/debugging over FT2232H.

- **OpenTAP (Free/Open)** — https://github.com/opentap/opentap  
  Automated testing for FPGA/ASIC bring-up and production.

#### VIII. Educational / Learning Repos

- **FPGA4Student (Free/Open)** — Verilog/VHDL mini-projects, ALU, UART, VGA controllers.

- **nand2tetris (Free/Open)** — build a computer from logic gates to running programs.

- **MIT 6.111 Labs (Free)** — FPGA digital design and signal processing labs.

- **Berkeley EECS RISC-V Classes (Free)** — open lecture notes + labs.

### 45. Semiconductor Failure Analysis & Reliability Tools  
_Free / open-source references for failure diagnosis, reliability modeling, thermal analysis, ESD/LU protection, PCB/component aging and silicon defect investigation._

#### I. Failure Analysis Frameworks & Databases (Free/Public)

- **NASA Lessons Learned Database (Free)** — https://llis.nasa.gov  
  Real-world spacecraft and electronics failures, root-cause break-downs, corrective actions.

- **NASA NEPP – Electronics Parts & Packaging Program (Free)** — https://nepp.nasa.gov  
  Failure reports, derating guides, reliability data for COTS parts exposed to radiation, thermal stress and vibration.

- **MIL-HDBK-338 / MIL-HDBK-217 (Free PDFs)**  
  Free military handbooks for reliability predictions, stress models, MTBF calculations.

- **ESA Space Components Docs (Free)** — https://escies.org  
  Failure reports, radiation data, PCB material aging, tin whisker mitigation.

- **JEDEC JESD Guides (Free Public Summaries)** — moisture sensitivity, reflow reliability, ESD/latch-up immunity basics.

#### II. Reliability Calculation Tools (Free/Open)

- **Reliability Block Diagram Tools (Free/Open)** — online RBD editors for modeling redundant systems & single-point failures.

- **Weibull Tool / Weibull++ Community Sheets (Free)** — spreadsheets for lifetime distribution and wear-out analysis.

- **MTBF/MTTF Calculators (Free)** — online tools using MIL-217 or Telcordia factors for ICs, passives, PCB assemblies.

- **PARTSIM / LTspice (Free)** — thermal/electrical stress simulation of MOSFETs, gate drivers, SMPS to predict field failures.

#### III. Thermal, Stress & Aging Analysis (Free/Open)

- **OpenFOAM (Free/Open)** — https://openfoam.org  
  CFD simulation for PCB cooling, heatsinks, airflow inside enclosures, hotspot detection.

- **Thermal Desktop & SINDA/FLUINT (Docs/Samples Free)** — aerospace-grade thermal modeling references (limited free).

- **FEMM (Free/Open)** — https://www.femm.info  
  Magnetic/electrical field modeling for motors, inductors, transformers → thermal stress correlation.

- **FreeCAD + KiCad StepUp (Free/Open)** — PCB + mechanical thermal fit, enclosure interference, hotspot airflow modeling.

- **SimScale Community Edition (Free Tier)** — limited free CFD/thermal simulation for enclosures & PCBs.

#### IV. Board-Level Testing & Fault Isolation (Free/Open)

- **sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Capture intermittent faults, bus glitches, marginal signal timing and decoupling failures.

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automated production testing to detect marginal PCBs, cold solder, intermittent connectors.

- **PyVISA + SCPI (Free/Open)** — automate stress/soak testing using power supplies, SMUs, scopes & chambers.

- **Boundary Scan Tools (UrJTAG) (Free/Open)** — http://urjtag.org  
  Detect open BGA balls, shorts, incomplete assembly, trace faults without powered boot.

#### V. PCB Reliability & Material Guides (Free/Public)

- **IPC-2221 / 9592 Public Summaries (Free)** — creepage, clearance, thermal relief, copper weight reliability.

- **NASA Tin Whisker Mitigation Guidelines (Free PDF)** — prevent whisker-related shorts in long-life electronics.

- **UL PCB Flammability & CTI Guides (Free PDFs)** — insulation aging, tracking & high-voltage failures.

- **Thermal Cycling & Vibration Testing Guides (Free)** — from ESA & NASA for PCB fatigue and solder joint cracking.

#### VI.ESD, Latch-Up & Transient Protection (Free/Public)

- **ESD Association Public Articles (Free)** — best practices for ESD-safe design & manufacturing.

- **TI/Analog Devices ESD App Notes (Free)** — TVS sizing, IEC 61000-4-2 testing, surge/transient mitigation.

- **Latch-Up Testing Basics (Free PDFs)** — JEDEC summaries for CMOS latch-up screening & design rules.

- **Open EMFI & glitch repos (Free/Open)** — used to detect silicon weak spots / reliability under transient stress.

#### VII. Semiconductor Reliability Data (Free/Public)

- **NASA Radiation Test Reports (Free)** — SEE, SEL, SEU results for COTS ICs.

- **ESA Radiation Handbook (Free PDF)** — TID models, shielding, component derating for space electronics.

- **NSIT/OEIS Public Reliability Data (Free)** — failure rate statistics for passives, ICs, connectors.

#### VIII. Failure Debug & Reverse Engineering (Free/Open)

- **Binwalk (Free/Open)** — extract firmware dumps to study corrupted NVM or flash retention issues.

- **OpenScanLab (Free/Open)** — community tools for board inspection, X-ray dataset references.

- **OpenBoardView (Free/Open)** — view PCB pad connectivity; helps locate broken traces & via failures.

- **Ghidra (Free/Open)** — analyze crashes from firmware aging / memory corruption in long-life systems.

#### IX. Checklists & Templates (Free)

- FMEA / DFMEA / PFMEA spreadsheets  
- Stress test plan templates (thermal soak, vibration, HALT/HASS)  
- Derating charts for capacitors, MOSFETs, power supplies  
- Burn-in & soak testing logs  
- Failure reporting & corrective action (FRACAS) sheets  

### 46. Space-Grade RF & Antenna Design Tools  
_Free / open-source modeling tools, antenna optimizers, RF link calculators, propagation simulators and space-rated RF references for satellite and deep-space missions._

#### I. RF & Antenna Simulation (Free/Open)

- **OpenEMS (Free/Open-Source)** — https://www.openems.de  
  FDTD electromagnetic solver ideal for patch antennas, helical antennas, waveguides and space-probe RF design.

- **FDTD-Z (Free/Open)** — community open-source 3D FDTD solver for complex RF structures and dielectric analysis.

- **NEC2 / 4NEC2 (Free/Open)** — https://www.qsl.net/4nec2  
  Classic antenna modeling tool for dipoles, Yagis, patch antennas, satellite dish feeds, reflectors.

- **Feko Lite (Free Student Version)** — limited free version for PCB antennas, radomes, satellite feeds, scattering.

- **LiteSim / Meep (Free/Open)** — https://meep.readthedocs.io  
  Electromagnetic FEM solver used for photonic and microwave R&D.

- **FEMM (Free/Open)** — https://www.femm.info  
  2D electromagnetic solver for coils, magnetics and RF shielding structures.

#### II. RF Link Budget & Propagation Tools (Free)

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Build satellite modems, telemetry decoders, digital downconverters, demodulators.

- **Gpredict (Free/Open)** — https://gpredict.oz9aec.net  
  Satellite tracking with Doppler correction and radio control for uplink/downlink planning.

- **SatNOGS (Free/Open)** — https://satnogs.org  
  Open ground station network with waterfall plots, demodulators and dashboards.

- **SatSim / GPTools (Free/Open)** — open-source link calculators for LEO/MEO/GEO orbits.

- **ITU Propagation Models (Free Docs)** — official models for atmospheric loss, rain fade, ground reflection.

- **FCC / NTIA Free Databases** — satellite and RF spectrum allocations, permissible EIRP levels.

#### III. PCB Antenna Design & Tuning (Free/Open)

- **KiCad RF Tools (Free/Open)** — https://kicad.org  
  Impedance calculators, microstrip/CPW tuning, stack-up design for S-band/L-band PCBs.

- **OpenEMS + KiCad Step Export (Free/Open)** — simulate real PCB geometries for antenna pattern.

- **RFSim99 (Free)** — lightweight Smith-chart matching and filter design (runs in Wine).

- **TX-Line (Free)** — microstrip and CPW calculators for RF traces and controlled impedance.

- **Qucs-S (Free/Open)** — https://ra3xdh.github.io  
  RF circuit simulation with S-parameters, filters, LNAs.

#### IV. Space-Grade RF / High-Rel Design (Free/Public)

- **NASA RF Design Guidelines (Free PDFs)** — waveguides, S-band, X-band, Q/V-band links, low-noise amplifiers, radomes, filters.

- **ESA ECSS RF Standards (Free)** — PCB materials, coax selection, PCB stack-up, microstrip radiation constraints.

- **NASA Parts & Materials Radiation Guides (Free)** — multi-layer board aging, contamination, dielectric breakdown.

- **NASA Antenna Handbook (Free PDF)** — link equations, directivity, radome effects, spacecraft mounting.

- **Navy Antenna Handbook (Free)** — military-grade antenna design principles (reflectors, helical, log periodic).

#### V. SDR Tools for Satellite & Deep Space (Free/Open)

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio modules for decoding CubeSat and amateur satellite telemetry.

- **CSP – CubeSat Space Protocol (Free/Open)** — https://github.com/libcsp/libcsp  
  Lightweight IP-like protocol for nanosatellite radios.

- **Direwolf (Free/Open)** — https://github.com/wb2osz/direwolf  
  AX.25 and APRS packet decoding used in amateur sat missions.

- **OpenLST (Free/Open)** — https://github.com/openlst/openlst  
  Robust telemetry radio used on NASA small-sat missions.

#### VI. Antenna Optimization & AI-Based Design (Free/Open)

- **PyGMO (Free/Open)** — https://esa.github.io/pygmo2  
  ESA’s evolutionary optimization library — used by researchers for RF antenna shape optimization.

- **OpenAntenna Optimizers (Free/Open)** — GitHub projects coupling NEC2/OpenEMS with genetic algorithms.

- **Meep + Python (Free/Open)** — run sweeps to minimize VSWR, maximize gain, and optimize dielectric patterns.

#### VII. Manufacturing & Measurement (Free/Public)

- **NanoVNA + NanoVNA-Saver (Free/Open)** — https://github.com/NanoVNA-Saver/nanovna-saver  
  Open-source VNA software to measure return loss, S11, tuning space-grade patches, feeds and filters.

- **RTL-SDR (Free/Open Firmware)** — low-cost SDR for receiving satellite beacons and telemetry.

- **Orbitron (Free)** — satellite pass prediction and Doppler planning for antenna tracking.

- **Hamlib (Free/Open)** — rig control for rotors and radios, often used with SatNOGS/Gpredict setups.

### 47. Open-Source DSP / SDR ASIC Cores  
_Free and open-source digital signal processing blocks, modem cores, FPGA/ASIC IP, and complete software-defined radio pipelines for communications, radar, and wireless PHY development._

#### I. Full SDR PHY Stacks (Free/Open)

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Gold-standard SDR DSP framework: modulation/demod, filters, OFDM, channel coding, telemetry, radar. Hardware agnostic.

- **Pothos SDR (Free/Open)** — https://github.com/pothosware  
  Visual DSP flow editor. Build end-to-end digital communication chains for SDR, FPGAs and custom DSP algorithms.

- **Liquid-DSP (Free/Open)** — https://github.com/jgaeddert/liquid-dsp  
  Highly optimized DSP library: filters, modems, FEC (Reed-Solomon, LDPC), OFDM, equalizers for embedded SDR.

- **Redhawk SDR (Free/Open)** — https://github.com/RedhawkSDR  
  US DoD-originated SDR framework for large distributed radio networks.

- **srsRAN (Free/Open)** — https://github.com/srsran/srsRAN  
  Complete 4G/5G software radio stack with PHY/MAC/RLC/PDCP. Can run on embedded Linux + SDR.

#### II. Modem & Communication IP Cores (Open-Source)

- **OpenCores DSP & Modem Cores (Free/Open)** — https://opencores.org  
  OFDM, QPSK, QAM, CORDIC, FIR, FFT/IFFT, Viterbi decoders for FPGA/ASIC.

- **Free-Cores Viterbi / Turbo / LDPC IP (Free/Open)** — community IP for forward-error correction PHYs.

- **CSP – CubeSat Space Protocol (Free/Open)** — https://github.com/libcsp/libcsp  
  Space-grade lightweight networking stack.

- **OpenOFDM (Free/Open)** — GitHub projects implementing OFDM PHY in Verilog/VHDL.

- **OpenLTE (Free/Open)** — https://github.com/EURECOM-SW/OpenAirInterface  
  LTE PHY + UE/eNodeB reference designs for FPGAs.

#### III. DSP Engines & Math Accelerators (Open IP)

- **PicoRV32 + DSP Extensions (Free/Open)** — extremely small RISC-V core with multiply–accumulate units.

- **VexRiscv + FPU/DSP Plugins (Free/Open)** — configurable soft-core with SIMD/DSP options.

- **CORDIC Core (Free/Open)** — https://github.com/korayws/Verilog_CORDIC  
  Trigonometric/IP cordic blocks for FPGA signal processing.

- **FIR/IIR Filter IP (Free/Open)** — OpenCores & GitHub repos for parametric digital filters.

- **FFT/IFFT cores (Free/Open)** — multiple Verilog/VHDL implementations for radar, OFDM, audio DSP.

#### IV. SDR Front-Ends & RF Gateware (Open)

- **LimeSDR Gateware (Free/Open)** — https://github.com/myriadrf  
  Complete FPGA signal chain for LimeSDR boards; AGC, mixers, DDC/DUC, filters.

- **BladeRF Gateware (Free/Open)** — https://github.com/Nuand/bladeRF  
  FPGA source for RF frontend and streaming.

- **USRP UHD (Free/Open)** — https://github.com/EttusResearch/uhd  
  Open host drivers + FPGA reference designs for Ettus USRP radios.

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio blocks for decoding dozens of satellite waveforms.

#### V. Radar & Sensing DSP (Free/Open)

- **pyUHD + GNU Radio Radar blocks (Free/Open)** — implement FMCW, pulse radar, doppler processing.

- **PySAR / openSAR (Free/Open)** — community SAR image processors for satellite & UAV radar.

- **OpenPulse (Free/Open)** — pulse compression, matched filters, range-Doppler FFT pipelines.

- **KFR DSP (Free/Open)** — https://github.com/kfrlib/kfr  
  High-performance DSP library for filtering, FFT, convolution (C++) suitable for embedded Linux SDR.

#### VI. Audio / Voice DSP (Free/Open)

- **SpeexDSP (Free/Open)** — high-efficiency audio processing: filters, AGC, echo cancel, noise suppression.

- **Opus Codec (Free/Open)** — https://opus-codec.org  
  Voice + audio codec used in SDR voice links and low-latency comms.

- **SoX DSP (Free/Open)** — https://sox.sourceforge.net  
  Filters, resampling, equalizers for embedded PCM pipelines.

#### VII. Coding & FEC Engines (Free/Open)

- **OpenFEC (Free/Open)** — https://openfec.org  
  Reed-Solomon and RaptorQ FEC for lossy RF links.

- **Kodo C++/Python Community Editions (Free)** — network coding for satellite/mesh networks (limited free).

- **LDPC / Turbo Implementations (OpenCores/GitHub)** — modular HDL blocks for high-rate links.

#### VIII. DSP Simulation, Testing & Tooling (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  MATLAB-compatible numerical computing for filters, modulation, signal analysis.

- **SciPy / NumPy / Matplotlib (Free/Open)** — Python numeric and signal processing stack.

- **Sigrok + PulseView (Free/Open)** — logic analyzer suite ideal for verifying digital baseband and high-speed GPIO/serial DSP streams.

- **Qucs-S (Free/Open)** — RF circuit simulation with S-parameters, mixers, filters.

- **Scilab (Free/Open)** — https://www.scilab.org  
  Numerical DSP analysis/visualization environment.

#### IX. Learning Repos & Academic Datasets (Free/Open)

- **GNU Radio Tutorials & Courseware (Free/Open)** — official examples and university labs.

- **MIT OpenCourseWare DSP (Free)** — full lecture notes, labs and assignments.

- **Stanford EE104 / EE264 (Free Notes)** — advanced DSP, filter design, sampling theory.

- **DSP-Related Kaggle/AIR datasets (Free)** — RF signal classification, radar echoes.

### 48. High-Voltage & Power Electronics Simulation Tools  
_Free / open-source tools for SMPS design, HV converters, motor drives, insulation coordination, switch transients, magnetics and thermal-electrical co-simulation._

#### I. Power Electronics Circuit Simulation (Free/Open)

- **LTspice (Free)** — https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html  
  Industry-standard SMPS simulator. MOSFET drivers, DC-DC, PFC stages, thermal stress, transformer leakage, startup behavior.

- **PSIM Student Version (Free Limited)** — https://powersimtech.com  
  Power stage + control loop simulation (PWM, PFC, motor drive, resonant converters).

- **PLECS Student Edition (Free Limited)** — https://www.plexim.com  
  Fast switching circuit + thermal models, SiC/GaN evaluation, efficiency and loss breakdown.

- **Qucs-S (Free/Open)** — https://ra3xdh.github.io  
  SPICE simulation with S-parameters, filters, resonant tanks, gate driver and EMI analysis.

- **Ngspice (Free/Open)** — http://ngspice.sourceforge.net  
  Generic SPICE engine with transient simulation and custom models for IGBTs, MOSFETs, GaN.

#### II. Magnetics, Transformers & Inductors (Free/Open)

- **FEMM (Free/Open)** — https://www.femm.info  
  2D FEM simulation for magnetics: transformer cores, inductors, flux leakage, saturation and eddy losses.

- **MagNet (Free Student Version)** — limited electromagnetic design for high-power transformers & chokes.

- **IncaMag / OpenMagnetics (Free/Open)** — open magnetic device design with winding losses, AC effects, core selection.

- **Texas Instruments Inductor & Transformer Tools (Free)** — application notes for flyback/forward, coupled inductors, current ripple.

- **PowerEsim (Free-Tier)** — https://www.poweresim.com  
  Online SMPS magnetics calculator, thermal checks, loss estimation, BOM suggestions.

#### III. High-Voltage Isolation, Creepage & Clearance (Free Resources)

- **Creepage/Clearance Calculators (Free Web Tools)** — map altitude, CTI, insulation classes to PCB spacing.

- **UL / IEC Public Guides (Free Summaries)** — mains isolation rules for SMPS, EV chargers, battery packs.

- **Bourns / Littelfuse App Notes (Free)** — fuse sizing, MOV/TVS selection, surge and lightning protection.

- **Pulse/High-Voltage Transformer App Notes (Free PDFs)** — design rules for reinforced insulation windings.

#### IV. Motor Drive & Inverter Simulation (Free/Open)

- **Motor Control Workbench (ST) (Free)** — generate FOC/BLDC code + motor models for STM32 MCUs.

- **TI MotorWare / InstaSPIN Labs (Free)** — motor modeling, FOC, SMO observers, Hall/encoder setups.

- **SVPWM/FOC Reference Repos (Free/Open)** — GitHub C/STM32/ESP32/PIC implementations.

- **SimulIDE + MCU + Gate Drivers (Free/Open)** — small tool to simulate PWM control and inverter switching.

#### V. GaN/SiC & Fast Switching (Free/Public)

- **GaN Systems / Transphorm App Notes (Free)** — gate driver layout, EMI mitigation, ZVS/ZCS design.

- **Wolfspeed SiC Design Tools (Free)** — thermal models, switching waveforms, loss calculators.

- **TI GaN Power Stages (Free)** — SPICE models and layout rules for high-frequency converters.

#### VI. Power Integrity / EMI Pre-Compliance (Free/Open)

- **OpenEMS (Free/Open)** — https://www.openems.de  
  FDTD electromagnetic simulation for radiated emissions, shielding, cable currents.

- **Sigrok + PulseView (Free/Open)** — logic + power switch timing, shoot-through, ringing detection.

- **LTspice + parasitic modeling (Free)** — simulate switch-node ringing, diode recovery, gate loops.

#### VII. Thermal & Reliability (Free/Public)

- **OpenFOAM (Free/Open)** — PCB airflow and heatsink analysis for HV power supplies/chargers.

- **SimScale Community (Free Tier)** — CFD/thermal for enclosures, forced cooling, hotspots.

- **PowerEsim Thermal (Free Tier)** — junction temperature, heatsink sizing, SOA stress.

#### VIII. Test Automation & HIL (Free/Open)

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automate power-on tests, surge tests, calibration, efficiency logs for SMPS prototypes.

- **PyVISA + SCPI (Free/Open)** — control electronic loads, scopes, SMUs for soak testing.

- **Renode/QEMU (Free/Open)** — co-simulate power control firmware with virtual peripherals.

#### IX. High Voltage Safety & Compliance (Free/Public)

- **IPC-2221 / UL Summaries (Free)** — PCB spacing & creepage design.

- **IEC 60601-1 / 62368 Summaries (Free)** — reinforced isolation rules for offline SMPS, medical supplies.

- **NASA Power System Design Guides (Free PDFs)** — grounding, fault protection, radiation derating.

### 49. Open Embedded Operating Systems for Space / Defense / Safety-Critical  
_Free / open-source operating systems and RTOS frameworks used in aerospace, defense, satcom, nuclear, industrial safety, and mission-critical embedded systems._

#### I. Space-Grade Flight Software Frameworks (Free/Open)

- **NASA cFS – Core Flight System (Free/Open)** — https://cfs.gsfc.nasa.gov  
  Flight-proven satellite OS framework with modular apps, telemetry, command, data handling, fault management.

- **F´ (F Prime) by NASA JPL (Free/Open)** — https://fprime.jpl.nasa.gov  
  Component-based flight SW platform used on Mars Helicopter & CubeSats. Includes ground station + codegen.

- **NOS3 (Free/Open)** — https://github.com/nasa/nos3  
  Virtual hardware simulation + CubeSat flight software + ground systems. Full training environment.

- **OpenSatKit (Free/Open)** — https://github.com/OpenSatKit  
  Hands-on flight software, ground station, telemetry viewer, training lab (built around cFS).

#### II. Real-Time Operating Systems for Aerospace & Safety (Free/Open)

- **RTEMS (Free/Open)** — https://www.rtems.org  
  Real-time OS used in ESA/NASA missions. Deterministic, POSIX support, multi-core SMP, flight heritage.

- **FreeRTOS (Free/Open)** — https://freertos.org  
  Widely used embedded RTOS with safety variants (SafeRTOS). Memory protection, deterministic scheduling.

- **Zephyr RTOS (Free/Open)** — https://zephyrproject.org  
  Production-grade, security-patched RTOS for IoT and aerospace. PSA-certified, board support packages, OTA.

- **NuttX (Free/Open)** — https://nuttx.apache.org  
  POSIX-like RTOS used in drones, satellites, high-rel systems. Runs on STM32, ESP32, RISC-V, ARM, Xtensa.

- **Tock OS (Free/Open)** — https://www.tockos.org  
  Memory-safe embedded OS using Rust for isolation — attractive for critical embedded nodes.

- **seL4 Microkernel (Free/Open)** — https://sel4.systems  
  Formally verified microkernel used in defense & avionics for high assurance and secure partitioning.

- **ARINC 653 Open Repos (Open Educational Implementations)** — partitioned avionics OS reference projects.

#### III. Secure / Defense-Oriented OS & Middleware (Free/Open)

- **OpenTitan Firmware Stack (Free/Open)** — https://opentitan.org  
  Secure boot chain, attestation, crypto services for defense/Aero MCUs.

- **Trusted Firmware-M (Free/Open)** — https://www.trustedfirmware.org  
  PSA-Certified secure partitions for Cortex-M: crypto, secure storage, attestation.

- **PSA Crypto + mbedTLS (Free/Open)** — https://github.com/ARMmbed/mbedtls  
  Security stack for RTOS and microcontrollers, used in secure telemetry and command uplinks.

- **AeroKernel (Free/Open)** — academic OS kernels for high-assurance systems.

#### IV. High-Assurance Linux / Embedded Linux (Free/Open)

- **Buildroot (Free/Open)** — https://buildroot.org  
  Minimal secure Linux for aerospace SBCs. Reproducible builds, signed kernels, custom packages.

- **Yocto Project (Free/Open)** — https://www.yoctoproject.org  
  Hardened Linux for satellites/ground stations, supports secure boot & SELinux.

- **OpenWrt (Free/Open)** — https://openwrt.org  
  Trusted networking Linux used in secure gateways and telemetry concentrators.

- **SELinux / AppArmor (Free/Open)** — MAC frameworks for critical Linux deployments.

#### V. Safety-Certified & Standards Alignment (Free/Public Docs)

- **MISRA-C Guidelines (Free Summaries)** — safe C coding rules used in avionics/defense.

- **DO-178C Summaries (Free)** — avionics software certification checklists, traceability goals.

- **ISO 26262 & IEC 61508 Summaries (Free)** — functional safety rules for embedded RTOS and devices.

- **ARINC 653 Public Guides (Free)** — time/space partitioning, inter-partition messaging.

#### VI. Testing, Simulation & Fault Injection (Free/Open)

- **Renode (Free/Open)** — https://renode.io  
  Simulate satellite or defense nodes with RTOS + radios + sensors for pre-flight testing.

- **Gazebo / Webots / AirSim (Free/Open)** — simulate drones, rovers, robots & sensors in mission environments.

- **QEMU (Free/Open)** — emulate ARM/RISC-V flight software and validate memory safety, watchdog behavior.

- **OpenHTF (Free/Open)** — automate hardware-in-loop tests for avionics boards and radios.

- **Syft / Grype (Free/Open)** — generate SBOMs and scan firmware for security vulnerabilities.
  
#### VII. Helpful Open Tools for Flight DevOps

- **OpenMCT (Free/Open)** — https://github.com/nasa/openmct  
  NASA’s modern mission control dashboard for telemetry and command.

- **InfluxDB + Grafana OSS (Free/Open)** — ground station telemetry storage + charts.

- **SatNOGS (Free/Open)** — global telemetry reception network.

- **cFS + COSMOS Ground Station Bundles (Free/Open)** — command/telemetry UI with scripting.

#### VIII. Academic & Learning Resources

- **NASA FSW Training (Free)** — public lecture slides for space-grade software.

- **MIT Space Systems Classes (Free)** — avionics, redundancy, control, fault tolerance.

- **CubeSat Design Specification (Free)** — system-level avionics, radios, FSW expectations.

### 50. Advanced Semiconductor Packaging & Assembly Tools  
_Free / open-source tools and reference resources for IC packaging, wirebonding, flip-chip, 2.5D/3D packaging, PCB assembly, thermal-mechanical modeling, and high-reliability electronic assembly._

#### I. Packaging Design / Layout / Footprint Tools (Free/Open)

- **KiCad (Free/Open)** — https://kicad.org  
  Full PCB + footprint + 3D package modeling. Supports BGA, QFN, CSP, wafer-level, stacked leadframes, HDI microvias.

- **LibrePCB (Free/Open)** — https://librepcb.org  
  PCB and packaging editor with 3D CAD generation, assembly BOM exports.

- **OpenBOM (Free/Open)** — https://www.openbom.com  
  Free tier for BOM creation, variants, assembly documentation.

- **OpenBoardView (Free/Open)** — https://openboardview.org  
  Package pinout and pad-level reverse engineering of assembly faults (BGA shorts, open vias, pad voids).

#### II. Thermal-Mechanical & Warpage Simulation (Free/Open/Public)

- **OpenFOAM (Free/Open)** — https://openfoam.org  
  Thermal simulations for underfill, die attach, heatsink, spreader modeling and airflow on high-power ICs.

- **FEMM (Free/Open)** — https://www.femm.info  
  FEM for magnetics and thermal conduction—useful for package inductors, SiC/GaN power modules.

- **SimScale (Free Community Tier)** — https://simscale.com  
  Web-based FEA/CFD for heat dissipation, warpage, CTE mismatch in multi-layer packages.

- **ANSYS & COMSOL Academic Repos (Free Demos)** — public tutorials on solder fatigue, BGA reliability, thermal cycling.

#### III. Wirebond, Flip-Chip, BGA & HDI Reference (Free/Public)

- **IPC-7351B Public Summaries (Free)** — package footprint standards (QFN/BGA/CSP).

- **JEDEC JESD Guides (Free Public Summaries)** — moisture sensitivity (MSL), reflow, warpage, board reliability.

- **NASA/ESA Assembly & Soldering Standards (Free)** — https://nepp.nasa.gov / https://escies.org  
  Space-grade rules for flux, vias, underfill, whisker mitigation, conformal coat, tin/lead reliability.

- **IPC-7093 (Free Summaries)** — Design/reliability for bottom termination components (QFN/DFN/LGA).

- **“Tin Whisker Mitigation” NASA Guides (Free PDF)** — whisker suppression for long-life boards.

#### IV. 2.5D / 3D Packaging, Interposers, TSV (Free/Open/Public)

- **Open3DFlow (Free/Open)** — research-level open 3D IC design flow (interposers, TSV routing).

- **ASU PTM Models (Free/Open)** — https://ptm.asu.edu  
  Advanced FinFET/TSV reliability, thermal and parasitics models.

- **Chiplet Interconnect Open Specs (Free/Public)** — Bunch of Wires, ODSA, AIB open chiplet PHY references.

- **DARPA CHIPS Program Docs (Free PDFs)** — assembly, chiplets, interposers, thermal management.

#### V. Semiconductor Reliability & Aging (Free/Public)

- **MIL-HDBK-338 / 217 (Free PDFs)** — failure rate prediction for ICs, packaging, interconnects.

- **ARRL/IPC Solder Joint Fatigue Guides (Free)** — lead-free reliability, BGA cracking, voiding, underfill strategies.

- **JEDEC J-STD-020 / 033 (Free Summaries)** — moisture/reflow sensitivity and bake-out rules.

- **NASA Workmanship Standards (Free)** — cable harnessing, conformal coat, staking, crimping, high-rel aerospace assembly.

- **Coffin-Manson & Miner Fatigue Calculators (Free Sheets)** — predict solder/joint fatigue over thermal cycling.

#### VI. X-Ray, AOI & Manufacturing Debug (Free/Open)

- **OpenScanLab (Free/Open)** — datasets and algorithms for PCB/X-ray defect classification.

- **sigrok + PulseView (Free/Open)** — detect intermittent assembly failures, broken power nets, marginal BGA solder.

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automate functional tests in assembly lines: boot-tests, JTAG-tests, UART logs.

- **PyVISA + SCPI (Free/Open)** — automate AOI, ICT and boundary-scan driven tests.

#### VII. PCB/Package Co-Design & Co-Simulation (Free/Open)

- **OpenEMS (Free/Open)** — https://www.openems.de  
  Electromagnetic co-simulation for package + PCB transitions, controlled impedance, HF loss.

- **TX-Line (Free)** — microstrip/CPW calculators for BGA breakout, SerDes, DDR escape.

- **Qucs-S (Free/Open)** — S-parameter simulation for package to board transitions.

#### VIII. SMT, Reflow, Soldering, Assembly Guides (Free/Public)

- **J-STD-001 Summaries (Free)** — soldering workmanship for high-rel electronics.

- **NASA Workmanship Standards (Free)** — staking, conformal coat, potting, cable harness.

- **IPC-A-610 (Free Summaries)** — Acceptability of electronic assemblies.

- **IPC-2221 (Free Summaries)** — insulation, creepage, clearance for high-voltage assemblies.

- **Fritzing (Free/Open)** — visualization of assembly, through-hole/SMD mixed boards.

#### IX. Bonding / Die Attach / Underfill (Free/Public)

- **Henkel/Loctite Application Notes (Free)** — underfill, epoxy, die attach reliability.

- **Dow Corning Thermal Gel Guides (Free)** — TIM/gel selection for SoC and SiC/GaN modules.

- **Nordson/Dage App Notes (Free PDFs)** — X-ray analysis, voiding, delamination.

#### X. Useful Checklists & Templates (Free)

- BGA escape routing checklist  
- MSL storage + drying logs  
- X-ray inspection checklist  
- Reflow profiling templates  
- Reliability qualification matrix (HTOL, HAST, TC, drop, vibration)

### 51. Acoustic / Ultrasonic / Piezo Simulation Tools  
_Free / open-source tools and reference material for designing ultrasonic sensors, piezo drivers, acoustic waveguides, MEMS microphones, sonar, NDT transducers, and acoustic lenses._

#### I. Acoustic Wave & Ultrasonic Simulation (Free/Open)

- **k-Wave (Free/Open)** — https://www.k-wave.org  
  Full acoustic wave simulation toolbox for MATLAB/Octave. Models ultrasound propagation, attenuation, transducer arrays, beamforming.

- **OpenFOAM (Free/Open)** — https://openfoam.org  
  CFD + acoustic propagation simulations for enclosure acoustics, mufflers, underwater robotics, drones, and transducers.

- **Elmer FEM (Free/Open)** — https://www.csc.fi/web/elmer  
  Multiphysics solver with piezoelectric and acoustic FEM. Useful for transducer resonances and pressure fields.

- **MEEP (Free/Open)** — https://meep.readthedocs.io  
  Electromagnetic FDTD solver that also models acousto-optic interactions and wave confinement structures.

- **FreeCAD + FEM Workbench (Free/Open)** — https://freecad.org  
  Design transducer housings, horns, and acoustic waveguides; link to FEM tools for modal analysis.

#### II. Piezoelectric Modeling (Free/Open)

- **Elmer PZ Module (Free/Open)** — models piezo-actuated devices (ultrasonic cleaners, NDT probes, buzzers).

- **FEMM (Free/Open)** — https://www.femm.info  
  Magnetic models for piezo drivers and ultrasonic transducers using transformer-coupled piezo power stages.

- **OpenPZ / Piezoelectric GitHub Projects (Free/Open)** — open scripts and FEM models for PZT resonant tuning, beam/shell effects.

#### III. Acoustics for Speakers, MEMS Mics, Audio Devices (Free/Open)

- **REW – Room EQ Wizard (Free)** — https://www.roomeqwizard.com  
  Acoustic response measurement, FFT, impulse response, echo/reflection analysis.

- **HornResp (Free)** — classic tool for horn-loaded speaker and acoustic waveguide analysis.

- **PulseAudio + ALSA Tools (Free/Open)** — capture and analyze microphone streams, latency, filtering.

- **Audacity (Free/Open)** — https://www.audacityteam.org  
  FFT, spectrograms, filtering, harmonic distortion checks for sonic/ultrasonic signals.

#### IV. Filter, Beamforming & DSP (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  Acoustic signal processing: FFT, FIR/IIR, beamforming, matched filters, STFT.

- **SciPy/NumPy (Free/Open)** — Python scientific stack for acoustic DSP, windowing, simulation and correlation.

- **Liquid-DSP (Free/Open)** — https://github.com/jgaeddert/liquid-dsp  
  Optimized DSP blocks: filters, decimators, modulation for ultrasonic comms & sonar.

- **MATLAB Online + Free Toolboxes (Limited)** — university-hosted acoustic and beamforming examples.

#### V. MEMS Microphones, Hydrophones & Transducers (Free/Public)

- **Analog Devices MEMS Mic App Notes (Free)** — beamforming arrays, noise filtering, ultrasonic drivers.

- **TDK/InvenSense App Notes (Free)** — MEMS mic frequency response, acoustic ports, SNR modeling.

- **Piezo Driver App Notes (Free)** — TI, ADI, ST: resonant drive, class-D, high voltage, impedance tuning.

- **Underwater Acoustics Free Texts (Public)** — sonar basics, hydrophone placement, propagation losses.

#### VI. NDT / Industrial Ultrasonic (Free/Open)

- **OpenUT (Free/Open)** — community libraries for ultrasonic thickness and flaw detection systems.

- **OpenPulse / Ultrasonic Pulse Compression (Free/Open)** — matched filtering and chirp compression for NDT.

- **gprMax (Free/Open)** — https://www.gprmax.com  
  FDTD simulation tool for Ground Penetrating Radar—also applicable to ultrasonic inspection mediums.

#### VII. Measurement, Visualization & Logging (Free/Open)

- **Sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Capture transducer drive waveforms, PWM drivers, and resonant ringing.

- **SoX (Free/Open)** — advanced audio analysis, filtering, spectrograms.

- **OpenMCT + Grafana OSS (Free)** — visualize long-term acoustic telemetry from sensor arrays.

#### VIII. Learning Resources (Free)

- **MIT Acoustics Courseware (Free)** — fundamentals of sound waves, cavity modes, filters, microphones.

- **Coursera / edX Acoustics Modules (Free Audit)** — DSP, transducers, psychoacoustics.

- **Ultrasonic NDT PDFs (Free/Public)** — flaw detection, phased-array transducers.

### 52. LiDAR / Radar Development Stacks (Free/Open)  
_Free and open-source tools for LiDAR / mmWave radar signal processing, point cloud handling, mapping, tracking, perception, SLAM and embedded radar DSP._

#### I. LiDAR Processing & Point Cloud Libraries (Free/Open)

- **Point Cloud Library – PCL (Free/Open)** — https://pointclouds.org  
  Industry-standard library for filtering, segmentation, registration, clustering, object detection and 3D mapping.

- **Open3D (Free/Open)** — https://www.open3d.org  
  Modern 3D data processing: SLAM, ICP registration, surface reconstruction, mesh + point cloud visualization.

- **PDAL (Free/Open)** — https://pdal.io  
  LiDAR pipeline framework (import/export, filters, geospatial transforms). Used in robotics and mapping.

- **MeshLab (Free/Open)** — https://www.meshlab.net  
  3D model processing, decimation, point cloud → mesh workflows.

- **Potree (Free/Open)** — https://github.com/potree/potree  
  Web-based visualization of huge LiDAR datasets (warehouse, outdoor, drone scans).

- **CloudCompare (Free/Open)** — https://www.cloudcompare.org  
  LiDAR point-cloud comparison, surface alignment, deviation analysis, industrial metrology.

#### II. LiDAR SLAM, Mapping & Perception (Free/Open)

- **Cartographer (Free/Open)** — https://google-cartographer.readthedocs.io  
  2D/3D SLAM for mobile robots and warehouse AMRs.

- **LOAM / A-LOAM / LIO-SAM (Free/Open)** — LiDAR odometry and mapping libraries for autonomous cars & robots.

- **Hector SLAM (Free/Open)** — http://wiki.ros.org/hector_slam  
  Fast 2D SLAM for LIDAR on AMRs and service robots.

- **LeGO-LOAM (Free/Open)** — robust outdoor LiDAR mapping for drones and UGVs.

- **ETH ASL Mapping Repos (Free/Open)** — top research implementations for LiDAR odometry & loop closure.

- **ROS Navigation + Costmaps (Free/Open)** — https://wiki.ros.org/navigation  
  Use LiDAR for obstacle detection, path planning and collision avoidance.

#### III. LiDAR Visualization & Playback (Free/Open)

- **RViz / RViz2 (Free/Open)** — part of ROS; visualize point clouds, maps, trajectories, IMU, LiDAR scans.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Modern web-based LiDAR viewer with time sync, TF trees, bag file playback, robot telemetry.

- **ROSBAG (Free/Open)** — record & replay sensor data (LIDAR+IMU+Odom) for offline analysis.

#### IV. Radar / mmWave DSP Frameworks (Free/Open)

- **tiRadar / mmWave-TI Open SDK (Free)** — TI public SDK for IWR/ AWR mmWave sensors: FFT, range-Doppler, CFAR, tracking.

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Build SDR-based radar pipelines: FMCW, pulse radar, Doppler, matched filters.

- **gr-radar (Free/Open)** — GNU Radio radar blocks for FMCW, pulse compression, range-Doppler maps.

- **OpenPulse (Free/Open)** — pulse compression, match filtering, range FFT, CFAR.

- **pyUHD + USRP (Free/Open)** — build custom SDR radars for automotive, drone altimeters, proximity sensors.

#### V. Radar Tracking, Kalman Filtering, Sensor Fusion

- **Robot Localization (Free/Open)** — https://github.com/cra-ros-pkg/robot_localization  
  EKF/UKF sensor fusion for LiDAR + radar + wheel odom + IMU.

- **FilterPy (Free/Open)** — https://github.com/rlabbe/filterpy  
  Python Kalman filters for tracking, SLAM, target detection.

- **Stone Soup (Free/Open)** — https://github.com/dstl/Stone-Soup  
  Advanced tracking framework: data association, multi-target tracking, radar/LiDAR fusion.

- **OpenCV + Open3D Fusion (Free/Open)** — Combine camera + LiDAR for object detection and mapping.

#### VI. Automotive & Robotics LiDAR Stacks (Free/Open)

- **Autoware.AI / Autoware.Auto (Free/Open)** — https://www.autoware.org  
  AV perception stack: LiDAR detection, tracking, HD mapping, route planning.

- **Apollo (Free/Open)** — https://github.com/ApolloAuto/apollo  
  Apollo autonomous driving stack: LiDAR detection, fusion, SLAM, prediction.

- **OpenPilot (Free/Open)** — radar-camera fusion, ACC/adaptive cruise, lane keeping (community automotive).

- **ROS2 Navigation2 (Free/Open)** — https://navigation.ros.org  
  Real-time LiDAR-based navigation and multi-robot fleet control.

#### VII. Industrial Sensing / NDT / Robotics (Free/Open)

- **gprMax (Free/Open)** — https://www.gprmax.com  
  FDTD GPR simulator for subsurface radar; also used for ultrasonic & dielectric imaging.

- **Open3D + ICP Pipelines** — robotic arm inspection, warehouse pallet picking, environment modeling.

- **CloudCompare Deviation Maps** — compare scanned vs CAD to check mechanical tolerances.
  
#### VIII. LiDAR / Radar Hardware Drivers (Free/Open)

- **RPLIDAR / YDLIDAR ROS Drivers (Free/Open)** — ROS support for low-cost 360° LiDARs.

- **Velodyne / Ouster ROS Drivers (Free/Open)** — high-resolution point clouds for robotics & self-driving.

- **Livox ROS Drivers (Free/Open)** — fast point cloud streaming for SLAM and drones.

- **Open IWR mmWave Drivers (Free/Open)** — TI mmWave demo visualizer + Python tools.

#### IX. Tools for Data Logging, Analysis & Replay (Free/Open)

- **ROS Bag / rosbag2 (Free/Open)** — record LiDAR + IMU + radar for regression testing.

- **MCAP (Foxglove) (Free/Open)** — high-performance logging format for large LiDAR datasets.

- **InfluxDB + Grafana OSS (Free)** — telemetry storage and dashboards for fleet sensing.

- **OpenMCT (Free/Open)** — mission control dashboard for sensor telemetry.
  
#### X. Datasets for Testing & AI Models (Free/Open)

- **KITTI Vision Benchmark (Free)** — autonomous driving LiDAR, stereo, radar sets.

- **Waymo Open Dataset (Free)** — full-scale AV LiDAR perception dataset.

- **Nuscenes (Free)** — AV dataset with radar + LiDAR + camera.

- **Ford Autonomous Dataset (Free)** — LiDAR + radar + GPS/IMU mapping data.

### 53. Industrial Imaging / Computer Vision Toolkits (Free/Open)  
_Free / open-source frameworks for machine vision, industrial inspection, barcode/QR, object tracking, defect detection, and production-line automation._

#### I. Core Computer Vision Libraries (Free/Open)

- **OpenCV (Free/Open)** — https://opencv.org  
  The most popular vision library: object detection, image filters, calibration, barcode/QR, OCR, ML, and hardware acceleration.

- **OpenVINO Toolkit (Free)** — https://docs.openvino.ai  
  Intel toolkit for optimized inference on edge CPUs/VPUs; free models for defect detection & industrial inspection.

- **TensorFlow Lite (Free/Open)** — https://www.tensorflow.org/lite  
  ML inference on embedded devices and SBCs for vision classification and anomaly detection.

- **PyTorch + TorchVision (Free/Open)** — https://pytorch.org  
  State-of-the-art CV models, training pipelines and pre-trained factory-detection models.

- **Darknet / YOLO (Free/Open)** — https://github.com/AlexeyAB/darknet  
  Real-time object detection for conveyor lines, pallet detection, zone intrusion.

#### II. Industrial Inspection & SMT/PCB Vision (Free/Open)

- **OpenPnP (Free/Open)** — https://openpnp.org  
  Open-source pick-and-place vision system: fiducial recognition, nozzle alignment, part inspection.

- **OpenCV + Halcon-like pipelines (Free/Open)** — camera calibration, perspective correction, barcode, presence/absence checks.

- **KiKit (Free/Open)** — https://github.com/yaqwsx/KiKit  
  PCB panelization + fiducial placement for machine vision alignment.

- **Gerber2Gcode Open Tools (Free)** — fiducials and inspection image generation from gerbers.

- **BGA/QFN X-ray Dataset Repos (Free/Open)** — community datasets for solder joint defect training.

#### III. Barcode / OCR / Industrial Scanners (Free/Open)

- **ZBar (Free/Open)** — https://github.com/mchehab/zbar  
  Reads QR, EAN, UPC, DataMatrix; used in warehouse scanners and traceability.

- **ZXing (Free/Open)** — https://github.com/zxing/zxing  
  Barcode/QR reading — works on embedded Linux cameras and scanners.

- **Tesseract OCR (Free/Open)** — https://github.com/tesseract-ocr/tesseract  
  OCR for labels, part numbers, packaging, expiry dates.

#### IV. Factory Robotics / Vision Pipelines (Free/Open)

- **ROS + image_pipeline (Free/Open)** — https://wiki.ros.org/image_pipeline  
  Camera drivers, calibration, rectification, stereo depth for robotics.

- **ROS MoveIt + perception plugins (Free/Open)** — object picking, pose estimation.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Visualize real-time camera feeds, 3D point clouds, image topics, factory telemetry.

- **NVIDIA Jetson Multi-Camera (Free/Open Samples)** — object detection for conveyor belts, palletizers.

#### V. Edge Inference / ONNX Tooling (Free/Open)

- **ONNX Runtime (Free/Open)** — https://onnxruntime.ai  
  Deploy models on embedded CPUs/NPUs/GPUs, production-ready, supports OpenCV integration.

- **TensorRT OSS Samples (Free/Open)** — CUDA-accelerated inference for Nvidia Jetson.

- **Edge Impulse Free Tier** — https://edgeimpulse.com  
  Train + deploy anomaly detection & CV models to MCUs/SBCs (free developer tier).

#### VI. 3D Vision / Stereo / Depth Cameras (Free/Open)

- **Intel RealSense SDK (Free/Open)** — https://github.com/IntelRealSense/librealsense  
  Depth cameras for robotic picking, warehouse automation.

- **Open3D (Free/Open)** — 3D scene segmentation, CAD comparison, warehouse mapping.

- **ElasticFusion (Free/Open)** — real-time 3D reconstruction from RGB-D cameras.

#### VII. Defect Detection / Quality Control (Free/Open)

- **Anomalib (Free/Open)** — https://github.com/openvinotoolkit/anomalib  
  Industrial anomaly detection (scratches, dents, missing components) with SOTA deep learning models.

- **OpenCV + scikit-image (Free/Open)** — thresholding, blob detection, color threshold inspection.

- **Segmentation Models Pytorch (Free/Open)** — pretrained semantic segmentation for factory defects.

- **Ultralytics YOLOv8 (Open)** — fast segmentation/defect detection models with free usage on local compute.

#### VIII. Annotation, Labeling & Dataset Tools (Free/Open)

- **CVAT (Free/Open)** — https://cvat.org  
  Annotation tool from Intel. Label objects, polygons, defects, OCR zones, barcodes for training CV models.

- **LabelMe / LabelImg (Free/Open)** — lightweight dataset labeling tools.

- **Roboflow Free Tier** — dataset management and augmentation for small industrial projects.

#### IX. Visualization & Data Logging

- **OpenMCT (Free/Open)** — telemetry dashboards for cameras, robots, production sensors.

- **MCAP / ROS Bag (Free/Open)** — record camera streams for regression testing.

- **Grafana OSS (Free/Open)** — runtime vision system monitoring (fps, latency, anomalies).

#### X. Learning Material

- **OpenCV Python Courses (Free)** — official samples + notebooks.

- **MIT CV Lectures (Free)** — fundamentals of computer vision and robotics perception.

- **Kaggle Industrial Vision Datasets (Free)** — PCB defects, metal surface scratches, product inspection.

### 54. Autonomous Drones / UAV Firmware & Ground Systems  
_Free / open-source autopilot stacks, flight controllers, simulators, ground stations, telemetry radios, swarm frameworks, and computer vision pipelines for UAVs._

#### I. Autopilot Firmware (Free/Open)

- **ArduPilot (Free/Open)** — https://ardupilot.org  
  Industry-leading open-source autopilot: multirotor, fixed-wing, VTOL, rover, boat, sub, antenna tracking. Supports GPS, RTK, ADS-B, obstacle avoidance.

- **PX4 (Free/Open)** — https://px4.io  
  Professional autopilot for drones and VTOL aircraft. Modular flight stack, MAVLink, offboard control, companion computers.

- **Paparazzi UAV (Free/Open)** — https://wiki.paparazziuav.org  
  Research-oriented autopilot with advanced guidance and swarm behaviors.

- **LibrePilot (Free/Open)** — older but popular with hobby drones, F4 flight controllers.

- **Cleanflight / Betaflight / iNav (Free/Open)** — FPV/racing flight stacks with PID tuning, telemetry, OSD, advanced filters.
  
#### II. Ground Control Stations (Free/Open)

- **QGroundControl (Free/Open)** — http://qgroundcontrol.com  
  Mission planning, telemetry, parameter tuning, video streaming, companion computer integration.

- **Mission Planner (Free/Open)** — https://ardupilot.org/planner  
  Data logging, mission planning, sensor calibration, flight replay for ArduPilot.

- **MAVProxy (Free/Open)** — Python-based GCS and command-line control for MAVLink.

- **OpenMCT (Free/Open)** — https://github.com/nasa/openmct  
  NASA mission control UI usable for drone telemetry, map overlays, and flight logs.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Visualize telemetry, IMU, LiDAR, video, CAN/serial logs for autonomous drones.

#### III. Simulation & Digital Twins (Free/Open)

- **Gazebo / Gazebo Garden (Free/Open)** — https://gazebosim.org  
  Physically accurate simulation with drone models, sensors, wind, payloads, PX4 plugins.

- **AirSim (Free/Open)** — https://github.com/microsoft/AirSim  
  Unreal/Unity drone sim with camera, LiDAR, GPS, IMU, computer vision pipelines.

- **RotorS (Free/Open)** — ROS-based multirotor simulator for research and SLAM.

- **jsbsim (Free/Open)** — flight dynamics engine used in FlightGear; PX4/ArduPilot integration.

#### IV. Companion Computer / CV / Perception (Free/Open)

- **ROS + MAVROS (Free/Open)** — ROS → MAVLink bridge to control drones with onboard compute.

- **RTAB-Map, OpenVSLAM, ORB-SLAM2 (Free/Open)** — onboard visual SLAM for GPS-denied navigation.

- **OpenCV, TensorFlow Lite, YOLO (Free/Open)** — onboard object detection and tracking.

- **Autoware Lite / Apollo (Free/Open)** — for ground robots; can be adapted for drone perception & autonomy.

#### V. Swarming, Fleet Control & UTM (Free/Open)

- **Open-RMF (Free/Open)** — multi-robot fleet coordination; can adapt to UAV scheduling & routing.

- **Swarm UAV Open Frameworks (GitHub)** — decentralized mission coordination, formation flight.

- **MAVSDK (Free/Open)** — https://mavsdk.mavlink.io  
  Control multiple UAVs using APIs (Python/C++).

- **DroneCAN (Free/Open)** — CAN-bus ecosystem for UAV payloads, ESCs, GPS, airspeed sensors.

#### VI. Telemetry, Radios, Links (Free/Open)

- **MAVLink (Free/Open)** — https://mavlink.io  
  Lightweight messaging protocol used in PX4/ArduPilot.

- **QoS telemetry via ROS2 DDS (Free/Open)** — robust multi-robot telemetry backbone.

- **RTL-SDR + GNU Radio (Free/Open)** — receive ADS-B, telemetry, custom downlinks.

#### VII. Flight Logs, Analysis & Replay (Free/Open)

- **Flight Review / Mavlink Flight Analyzer (Free/Open)** — online and local tools to analyze UAV logs (battery, PID, GPS, vibration).

- **Mission Planner Log Viewer (Free)** — graphs, FFT analysis for motor/prop vibration.

- **PX4 uLog + plot_juggler (Free/Open)** — real-time and replay dashboards for flight data.

#### VIII. Hardware Repos (Free/Open)

- **OpenDroneID Project (Free/Open)** — standard for broadcast remote ID.

- **Open-Source ESC / BLDC Firmware (Free/Open)** — BLHeli, SimonK, VESC — motor control for drones.

- **Open-Hardware Flight Controllers (Free/Open)** — PX4/ArduPilot compatible boards on GitHub.

#### IX. Learning Resources (Free)

- **PX4 Developer Guide (Free)** — architecture, autopilot internals, HITL, SITL.

- **ArduPilot Docs (Free)** — tuning guides, GPS + RTK, vision-based landing.

- **MIT / ETH UAV Lectures (Free)** — dynamics, control, SLAM, autonomy, multi-robot systems.

### 55. Audio / Vibration Analysis & Condition Monitoring Stacks (Free/Open)  
_Free or open-source tools for machine health monitoring, FFT/Spectrogram analysis, rotational equipment diagnostics, acoustic anomaly detection, and predictive maintenance._

#### I. Core Signal Processing & Analysis (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  MATLAB-compatible environment for FFT, PSD, spectrograms, filters, order tracking & envelope detection.

- **SciPy / NumPy / Matplotlib (Free/Open)** — full Python DSP workflow: filtering, FFT, STFT, cepstrum, correlation.

- **SoX (Free/Open)** — https://sox.sourceforge.net  
  Command-line DSP tool for audio capture, frequency-domain analysis, spectrograms, filtering.

- **librosa (Free/Open)** — https://librosa.org  
  Audio feature extraction: MFCC, chroma, spectral roll-off, ideal for sound-based anomaly detection.

- **PyWavelets (Free/Open)** — wavelet analysis for bearing failure detection and transient extraction.

#### II. Vibration Diagnostics (Free/Open)

- **VibrationData Suite (Free)** — https://www.vibrationdata.com  
  Massive library of scripts, tutorials and tools: PSD, SDOF/MDOF analysis, shock response spectrum, fatigue damage.

- **midasNDT / OpenVibe-Acoustic GitHub Tools (Free/Open)** — open vibration analysis and NDT computation scripts.

- **VibrationToolbox for Python (Free/Open)** — https://vibrationtoolbox.github.io  
  Rotordynamics, shaft unbalance, modal analysis, orbit plots.

- **PyDSP / SigROS GitHub Tools (Free/Open)** — vibration FFT / PSD pipelines for rotating machines & motors.

#### III. Predictive Maintenance / Anomaly Detection (Free/Open)

- **Edge Impulse Free Tier** — https://edgeimpulse.com  
  Build ML anomaly detectors using vibration + sound on MCUs/SBCs. Supports FFT + MFCC features and on-device classification.

- **Anomalib (Free/Open)** — https://github.com/openvinotoolkit/anomalib  
  SOTA anomaly detection for industrial sensors (acoustic/spectral).

- **Merlion (Free/Open)** — https://github.com/salesforce/Merlion  
  Time-series anomaly detection and forecasting for vibration telemetry.

- **River ML (Free/Open)** — streaming ML for real-time maintenance dashboards on edge gateways.

#### IV. Sensor Data Pipelines (Free/Open)

- **InfluxDB OSS + Grafana OSS (Free)** — telemetry storage, FFT trend charts, vibration heatmaps, alarms.

- **Telegraf (Free/Open)** — collect vibration/accelerometer data via MQTT, MODBUS, OPC-UA.

- **OpenMCT (Free/Open)** — real-time mission control dashboard for factory sensors.

- **Node-RED (Free/Open)** — MQTT → DSP → dashboard pipelines for machine health.

#### V. Acoustic & Machine Sound Diagnostics (Free/Open)

- **Audacity (Free/Open)** — https://www.audacityteam.org  
  Spectrogram, harmonic analysis, noise profiling, high-speed FFT for acoustic fault recording.

- **Praat (Free/Open)** — sound visualization, spectral envelopes, speech/noise analysis — useful for valve/pump diagnostics.

- **REW – Room EQ Wizard (Free)** — https://www.roomeqwizard.com  
  FFT & SPL measurement; helpful for acoustic/ultrasonic system testing.

- **TF-Lite + MicroPython Audio Classifiers (Free/Open)** — deploy tiny audio-based anomaly detectors to ESP32/MCUs.

#### VI. IoT Gateways: Condition Monitoring (Free/Open)

- **ThingsBoard Community Edition (Free/Open)** — telemetry, dashboards, ML rules.

- **KubeEdge (Free/Open)** — edge compute for vibration ML near machines.

- **Eclipse Kura (Free/Open)** — industrial IoT gateway with OPC-UA/MQTT logging from IMU/vibration sensors.

#### VII. Specialized Toolkits (Free/Open)

- **gprMax (Free/Open)** — ground-penetrating radar simulator, also useful for acoustic/ultrasonic waves in solids.

- **Open Modal Analysis Repos (Free/Open)** — extract mode shapes and natural frequencies for machine frames.

- **OpenAcoustics / Acoular (Free/Open)** — beamforming, microphone arrays, noise source localization.

#### VIII. Data Logging & File Formats

- **MCAP / ROS Bag (Free/Open)** — high-performance logging of vibration streams for offline FFT/ML.

- **HDF5 + Pandas (Free/Open)** — structured storage of multi-sensor time series.

- **Prometheus + Grafana (Free)** — scrape industrial sensors every second for degradation trend monitoring.

#### IX. Learning Resources (Free)

- **MIT Vibration / Applied Mechanics Courseware** — rotating machinery, dampers, FFT fundamentals.

- **NASA Machinery Diagnostics PDFs (Free)** — bearing/gearbox failure signatures and spectrum patterns.

- **NIST Fault Datasets (Free)** — public vibration datasets for ML benchmarking.


---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Compliance & Standards](compliance.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
