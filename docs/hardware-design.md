# 🔧 A) Hardware Design

> **Complete guide to free PCB design, simulation, CAD tools, manufacturing, and reference designs**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Tools Count | Quick Jump |
|---------|-------------|------------|
| [1. PCB Design Tools](#1-schematic--pcb-design-tools) | 25+ | KiCad, EasyEDA, Flux, LibrePCB |
| [2. Circuit Simulation](#2-simulation--circuit-analysis) | 30+ | LTspice, Qucs-S, Falstad, OpenEMS |
| [3. Mechanical CAD](#3-mechanical--enclosure--cad-tools) | 20+ | FreeCAD, Fusion 360, OpenSCAD |
| [4. BOM & Manufacturing](#4-bom-dfm-dfa--manufacturing-tools) | 30+ | KiKit, Octopart, JLCPCB tools |
| [5. Calculators & References](#5-electronics-references--calculators) | 25+ | Saturn PCB, Webench, Filter designers |
| [6. Component Search](#6-component-search--datasheets) | 30+ | Octopart, LCSC, Digikey, Mouser |
| [7. Reference Designs](#7-reference-designs--open-hardware) | 40+ | Arduino, ESP32, STM32, Adafruit |

---

## 🆚 Quick Comparison Tables

### PCB Design Tools Comparison

| Tool | Type | Layers | Size Limit | Best For | License |
|------|------|--------|------------|----------|---------|
| **KiCad** `🟢` | Desktop | ∞ | None | Professional design | GPL |
| **EasyEDA** `🟢` | Browser | ∞ | None (public) | Quick prototypes + JLCPCB | Freemium |
| **Flux.ai** `🟡` | Browser | Limited | AI-assisted | Collaborative design | Freemium |
| **LibrePCB** `🟢` | Desktop | ∞ | None | Open-source alternative | GPL |
| **Fritzing** `🟡` | Desktop | 2 | Small | Beginners, breadboards | GPL |
| **Fusion 360** `🟢` | Desktop | 2 (free) | Personal use | PCB + Mechanical | Freemium |

🟢 Production-Ready • 🟡 Beta/Active Dev • 🔴 Experimental

### Circuit Simulation Tools

| Tool | Type | Engine | Best For | Platform |
|------|------|--------|----------|----------|
| **LTspice** | Desktop | SPICE | Power, analog | 🪟🍎🐧 |
| **Qucs-S** | Desktop | SPICE/Qucs | RF, mixed-signal | 🪟🐧 |
| **Falstad** | Browser | Visual | Learning, quick tests | ☁️ |
| **ngspice** | CLI | SPICE | Batch simulation | 🪟🍎🐧 |
| **OpenEMS** | Desktop | FDTD | EM fields, antennas | 🐧 |

---

## 1. Schematic & PCB Design Tools

### 🌟 Top Professional Tools (100% Free)

#### **KiCad** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.kicad.org

**The industry standard for open-source PCB design**

Full EDA suite for schematic capture, PCB layout, 3D viewer, DRC/ERC checks, and SPICE integration. 100% free with:
- ✅ **No board size limits**
- ✅ **Unlimited layers**
- ✅ **Professional DRC/ERC**
- ✅ **3D visualization**
- ✅ **SPICE simulation integration**
- ✅ **Python scripting**
- ✅ **Huge community libraries**

**Perfect for**: Professional boards, commercial products, complex multilayer designs  
**Used by**: SpaceX, CERN, NASA, thousands of companies

---

#### **LibrePCB** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://librepcb.org

**Modern, user-friendly open-source EDA**

Fully open-source schematic + PCB suite with:
- ✅ Modern, intuitive UI
- ✅ No licensing restrictions
- ✅ No feature limits
- ✅ Built-in library management
- ✅ Multi-board projects

**Perfect for**: Users who want simpler UX than KiCad  
**Good alternative to**: KiCad for beginners

---

### ☁️ Cloud-Based PCB Tools

#### **EasyEDA** `[Platform: Browser]` `[Level: Beginner]` `[Status: 🟢Production]`
https://easyeda.com

**Browser-based PCB editor with JLCPCB integration**

- ✅ Works in browser, no installation
- ✅ Direct JLCPCB manufacturing integration
- ✅ Free for public projects
- ✅ Huge component library
- ⚠️ Limited private project storage on free plan

**Perfect for**: Fast prototypes, JLCPCB ordering, beginners  
**Workflow**: Design → Order PCB + Assembly in one click

---

#### **Flux.ai** `[Platform: Browser]` `[Level: Pro]` `[Status: 🟡Beta]`
https://flux.ai

**Modern cloud PCB design with AI assistance**

- ✅ Real-time collaborative editing
- ✅ AI-assisted component placement
- ✅ AI auto-routing
- ✅ Git-like version control
- ⚠️ Limited free tier (public projects)

**Perfect for**: Teams, modern workflows, AI-assisted design  
**Unique feature**: Copilot-style AI for PCB layout

---

### 🤖 AI-Assisted PCB Tools

#### **JITX** `[Platform: Code-driven]` `[Level: Advanced]` `[Status: 🟡Experimental]`
https://www.jitx.com

**Hardware design automation (code-driven PCB)**

Write PCBs in code with:
- ✅ Algorithmic board generation
- ✅ Automated constraint checking
- ✅ Design-by-specification
- ⚠️ Community/academic free tier

**Perfect for**: Programmable hardware, design automation research

---

#### **DeepPCB AI** `[Platform: Cloud]` `[Level: Pro]` `[Status: 🟡Beta]`
https://deeppcb.ai

**AI-assisted auto-routing and placement**

- ✅ Machine learning-based routing
- ✅ Component placement optimization
- ⚠️ Free tier with complexity limits

**Perfect for**: Complex routing, HDI boards

---

### 🎯 Specialty & Legacy Tools

#### **Horizon EDA** `[Platform: Linux/Win]` `[Level: Pro]` `[Status: 🟢Production]`
https://horizon-eda.org

**Modern open-source PCB tool**

- ✅ Advanced constraint management
- ✅ Hierarchical schematics
- ✅ Interactive routing
- ✅ Git-friendly file format

**Perfect for**: Linux users, version-controlled hardware

---

#### **Fritzing** `[Platform: Win/Mac/Linux]` `[Level: Beginner]` `[Status: 🟡Active]`
https://fritzing.org

**Beginner-friendly breadboard → PCB tool**

- ✅ Visual breadboard view
- ✅ Easy for Arduino projects
- ✅ Open-source (free to compile)
- ⚠️ Paid binaries ($)

**Perfect for**: Arduino beginners, teaching, simple 2-layer boards

---

### 📦 Full Tool List

<details>
<summary><b>Click to expand complete list of 25+ PCB tools</b></summary>

#### Desktop Applications

- **DesignSpark PCB** — https://www.rs-online.com/designspark/pcb-software  
  Free PCB tool from RS Components; export Gerbers and 3D. Some pro features require registration.

- **CircuitMaker (Altium Community)** — https://circuitmaker.com  
  Free Altium-based tool for hobby/open projects. Unlimited layers but designs must be public.

- **TinyCAD** — https://sourceforge.net/projects/tinycad  
  Free schematic capture for Windows; standard symbol library.

- **gEDA / PCB** — http://wiki.geda-project.org  
  Classic open-source suite for Linux environments.

- **XCircuit** — http://opencircuitdesign.com/xcircuit  
  LaTeX-quality schematic outputs.

#### Cloud/Browser Tools

- **Upverter** — https://upverter.com  
  Collaborative cloud PCB design; free for open projects.

- **PCBFlow (Autodesk)** — https://www.autodesk.com/products/eagle/blog/introducing-pcbflow  
  Cloud DFM tool; free for basic checks.

#### Proprietary Free Tiers

- **Fusion 360 (Personal)** — https://www.autodesk.com/products/fusion-360/personal  
  PCB + mechanical CAD; free for personal/non-commercial use.

- **Autodesk EAGLE (Legacy)** — https://www.autodesk.com/products/eagle  
  Old free licenses still work; 2-layer limit.

- **Osmond PCB** — https://www.osmondpcb.com  
  macOS PCB design with unlimited size/layers.

- **PCB Artist** — https://www.4pcb.com/free-pcb-layout-software.html  
  Free Windows PCB tool (tied to Advanced Circuits manufacturing).

#### Regional/Specialty Tools

- **Pad2Pad** — https://www.pad2pad.com  
  Free if ordering boards from them.

- **ZenitPCB** — http://www.zenitpcb.com  
  Free Windows tool for small/medium boards.

- **ExpressPCB** — https://www.expresspcb.com  
  Simple beginner tool; limited export.

- **PCB Droid** — https://pcbdroid.com  
  Android PCB editor for simple boards.

#### Utilities & Companions

- **KiKit** — https://github.com/yaqwsx/KiKit  
  KiCad companion: panelization, assembly outputs, interactive BOM.

- **Interactive HTML BOM** — https://github.com/openscopeproject/InteractiveHtmlBom  
  Clickable BOM + component highlighting for assembly.

- **OpenBoardView** — https://openboardview.org  
  Viewer for repair/rework boardview files.

- **Protogen by Flux** — https://flux.ai/protogen  
  AI schematic generation from natural language (limited free tier).

</details>

---

## 2. Simulation & Circuit Analysis

### 🌟 Top Simulation Tools

#### **LTspice** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.analog.com/ltspice

**Industry-standard SPICE simulator**

- ✅ Unlimited nodes, no restrictions
- ✅ Huge library of power devices (Analog Devices)
- ✅ Fast waveform viewer
- ✅ Widely used in industry
- ✅ Free forever

**Perfect for**: Power supply design, analog circuits, motor drives  
**Used by**: Every power electronics engineer

---

#### **Qucs-S** `[Platform: Win/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://ra3xdh.github.io

**Modern SPICE + RF simulator**

- ✅ SPICE compatibility
- ✅ RF/microwave analysis
- ✅ AC/DC/transient/noise
- ✅ S-parameter simulation
- ✅ Improved stability over original Qucs

**Perfect for**: RF circuits, filter design, mixed-signal

---

#### **Falstad Circuit Simulator** `[Platform: Browser]` `[Level: Beginner]` `[Status: 🟢Production]`
https://falstad.com/circuit

**Visual, interactive circuit simulator**

- ✅ Real-time animation
- ✅ Runs in browser
- ✅ Great for teaching
- ✅ Instant feedback
- ✅ Save/share circuits

**Perfect for**: Learning, quick concept tests, teaching electronics

---

### 📦 Complete Simulation Tool List

<details>
<summary><b>Click to expand 30+ simulation tools</b></summary>

#### SPICE-Based Simulators

- **ngspice** — http://ngspice.sourceforge.net  
  Open-source SPICE; integrates with KiCad.

- **Micro-Cap 12** — https://micro-cap.com  
  Formerly commercial, now free; powerful analog/digital sim.

- **QSPICE** — https://qspice.com  
  High-performance SPICE from Qorvo; excellent for SMPS.

- **Qucs (Original)** — http://qucs.sourceforge.net  
  Classic open-source RF simulator.

- **KiCad SPICE** — Built into KiCad  
  Board-level analog simulation.

- **QucsStudio** — https://qucsstudio.de  
  Enhanced Qucs with modern GUI (Windows).

#### Web-Based Simulators

- **CircuitJS** — https://circuitjs.org  
  Falstad fork with import/export.

- **EveryCircuit** — https://everycircuit.com  
  Mobile/web simulator with animations (free tier).

- **CircuitLab** — https://www.circuitlab.com  
  Browser sketching + simulation (free basic).

#### Power & RF Tools

- **PowerEsim** — https://www.poweresim.com  
  Online SMPS/transformer design.

- **TI Webench** — https://webench.ti.com  
  Power stage design with TI parts (free).

- **ST eDesignSuite** — https://edesignsuite.st.com  
  SMPS, motor control simulation (ST parts).

- **Microchip MPLAB Mindi** — https://www.microchip.com/mplab/mindi  
  Analog/power IC simulation.

#### EM & RF Simulation

- **OpenEMS** — https://openems.de  
  Open-source FDTD electromagnetic simulator (antennas, RF, EMC).

- **4NEC2** — http://www.qsl.net/4nec2  
  Free antenna simulation (NEC2 engine).

- **AppCAD** — https://www.broadcom.com/support/resources/appcad  
  RF calculators: S-param, matching, filters.

- **RFSim99** — Legacy RF simulator (free).

#### Digital Logic Simulators

- **SimulIDE** — https://simulide.com  
  Real-time MCU + circuit simulation (AVR, PIC, Arduino).

- **Logisim Evolution** — https://github.com/reds-heig/logisim-evolution  
  Digital logic, CPU design teaching tool.

- **DigitalJS** — https://digitaljs.tilk.eu  
  Browser-based digital logic simulator.

- **Verilator** — https://www.veripool.org/verilator  
  High-speed Verilog simulator (FPGA/ASIC).

- **Cocotb** — https://www.cocotb.org  
  Python testbenches for HDL simulation.

#### System-Level Simulation

- **Scilab/Xcos** — https://www.scilab.org  
  Matlab-like; control systems, PID, filters.

- **GNU Octave** — https://octave.org  
  Matlab-compatible DSP/control system tool.

- **OpenModelica** — https://openmodelica.org  
  Multi-domain system modeling (electrical/thermal/mechanical).

#### Mobile/Tablet Simulators

- **iCircuit** — https://icircuitapp.com  
  Visual simulator for iPad/Windows (free demo).

</details>

---

## 3. Mechanical / Enclosure / CAD Tools

### 🌟 Top 3D CAD Tools

#### **FreeCAD** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://www.freecad.org

**Open-source parametric 3D CAD**

- ✅ 100% free, no restrictions
- ✅ Parametric design
- ✅ Assembly modeling
- ✅ Python scripting
- ✅ Large community
- ✅ Multiple workbenches

**Perfect for**: Complex mechanical parts, assemblies, automation  
**Comparable to**: SolidWorks, Inventor (with learning curve)

---

#### **Fusion 360 (Personal)** `[Platform: Win/Mac]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.autodesk.com/products/fusion-360/personal

**Professional CAD/CAM for personal use**

- ✅ Full 3D CAD + CAM
- ✅ Cloud collaboration
- ✅ Simulation (FEA)
- ✅ PCB integration
- ⚠️ Free for personal/startup use
- ⚠️ Feature limitations vs paid

**Perfect for**: Professional-grade designs, startups, integrated PCB+mechanical

---

#### **OpenSCAD** `[Platform: Win/Mac/Linux]` `[Level: Advanced]` `[Status: 🟢Production]`
https://openscad.org

**Programmer's CAD (code-based)**

- ✅ Script-based parametric design
- ✅ Perfect for repeatable designs
- ✅ Git-friendly (text files)
- ✅ Algorithmic geometry
- ✅ 100% free

**Perfect for**: Parametric enclosures, programmable designs, version control

---

### 📦 Complete CAD Tool List

<details>
<summary><b>Click to expand 20+ CAD & enclosure tools</b></summary>

#### Full CAD Suites

- **Onshape (Free Plan)** — https://www.onshape.com  
  Cloud CAD with version control; free for public projects.

- **SolveSpace** — https://solvespace.com  
  Lightweight parametric 3D CAD; small download, constraints, assemblies.

#### Beginner-Friendly Tools

- **Tinkercad** — https://www.tinkercad.com  
  Browser 3D modeling for basic enclosures; very easy STL export.

- **Blender** — https://www.blender.org  
  Open-source 3D modeling/sculpting; organic shapes, enclosures.

- **Shapr3D (Free Basic)** — https://www.shapr3d.com  
  iPad/Windows CAD; free plan for small projects.

- **SelfCAD (Free)** — https://www.selfcad.com  
  Browser 3D modeling with boolean ops.

#### Polygon/Mesh Modelers

- **Wings3D** — http://www.wings3d.com  
  Free polygonal modeler for organic housings.

- **Meshmixer** — https://www.meshmixer.com  
  Mesh repair/editing for 3D printing workflows.

- **Microsoft 3D Builder** — Windows Store (free)  
  Simple STL viewer/editor on Windows.

#### Slicers (3D Print Prep)

- **PrusaSlicer** — https://www.prusa3d.com/prusaslicer  
  Support tuning, printability checks.

- **Bambu Studio** — https://bambulab.com/bambu-studio  
  Part orientation, strength analysis.

- **Cura (Ultimaker)** — https://ultimaker.com/software/ultimaker-cura  
  Print simulation, design recommendations.

#### Parametric/Scripting Tools

- **OpenJSCAD** — https://openjscad.org  
  Web-based JavaScript CAD.

- **FreeCAD Workbenches** — Assembly4, A2Plus  
  Assembly constraint systems.

#### PCB-Integrated Tools

- **KiKit Enclosure Generator** — https://github.com/yaqwsx/KiKit  
  Generate enclosures from PCB dimensions (OpenSCAD).

</details>

---

## 4. BOM, DFM, DFA & Manufacturing Tools

### 🌟 Top BOM & Manufacturing Tools

#### **KiKit** `[Platform: Python/KiCad]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/yaqwsx/KiKit

**Complete KiCad manufacturing automation**

- ✅ Panelization
- ✅ Pick-and-place (CPL) generation
- ✅ Assembly drawings
- ✅ Interactive HTML BOM
- ✅ Fabrication files automation

**Perfect for**: KiCad users preparing boards for manufacturing

---

#### **Octopart** `[Platform: Web]` `[Level: All]` `[Status: 🟢Production]`
https://octopart.com

**Universal component search engine**

- ✅ Search across all major distributors
- ✅ Real-time pricing & stock
- ✅ Lifecycle status (active/NRND/obsolete)
- ✅ Parametric search
- ✅ BOM tool
- ✅ Datasheet library

**Perfect for**: Component sourcing, BOM validation, alternate finding

---

### 📦 Complete Manufacturing Tool List

<details>
<summary><b>Click to expand 30+ BOM, DFM, sourcing tools</b></summary>

#### BOM Generation & Management

- **Interactive HTML BOM** — https://github.com/openscopeproject/InteractiveHtmlBom  
  Clickable BOM + PCB visualization for assembly.

- **OpenBOM (Free Tier)** — https://openbom.com  
  Cloud BOM management; change tracking, vendor links.

- **BOMIST** — https://bomist.com  
  Local inventory + BOM tool (free hobby).

- **LibrePCB Assembly Outputs** — Built into LibrePCB  
  BOM, pick-and-place, netlist generation.

#### Component Search & Lifecycle

- **PartStack** — https://partstack.com  
  Component alternates, lifecycle, supplier data (free for individuals).

- **FindChips** — https://findchips.com  
  Global distributor search; pricing, availability, alternates.

- **LCSC** — https://lcsc.com  
  Low-cost parts catalog; integrates with JLCPCB.

- **Digikey KiCad Plugin** — https://www.digikey.com/en/kicad  
  Import symbols/footprints from Digikey.

- **Ultra Librarian (Free Tier)** — https://www.ultralibrarian.com  
  Free footprints/3D models (limited monthly).

- **SnapEDA (Free)** — https://www.snapeda.com  
  Symbols/footprints for components.

- **SamacSys Library** — https://componentsearchengine.com  
  Free footprints for KiCad/Altium/Eagle.

- **Digi-X (Digikey BOM)** — https://www.digikey.com/en/resources/digix  
  BOM management, alternates, lifecycle alerts.

- **PartQuest** — https://www.partquest.com  
  Schematic symbols + BOM tie-ins.

- **ComponentSearchEngine** — https://componentsearchengine.com  
  Library + lifecycle + CAD models.

- **SiliconExpert (Free Trial)** — https://www.siliconexpert.com  
  Lifecycle/RoHS/alternates (limited free).

#### DFM/DFA Checking

- **JLCPCB Assembly Tools** — https://jlcpcb.com  
  Free BOM/CPL parsing, DFM checks, stock database.

- **PCBWay DFM** — https://pcbway.com  
  Online DFM rule check before manufacturing.

- **Macrofab BOM Tool** — https://macrofab.com  
  BOM upload, alternates, instant PCBA quotes.

- **FreeDFM** — https://www.4pcb.com/free-dfm-file-check  
  Automated Gerber DFM check (shorts, spacing, mask).

- **FitFab (3D Print DFM)** — https://fitfab.io  
  Check enclosure printability.

- **Fusion 360 Assembly Export** — Built-in  
  STEP/STL for PCB fit checks.

#### Distributor Tools

- **Mouser Part Database** — https://mouser.com  
  Datasheets, alternates, lifecycle, stock.

- **Digikey BOM Tool** — https://www.digikey.com  
  BOM comparison, stock alerts, price breaks.

- **Mouser BOM Tool** — https://mouser.com  
  RoHS/REACH compliance lookup.

- **CalcuQuote** — https://calcuquote.com  
  PCBA cost estimation for small runs.

- **PCB Panelizer (JLCPCB)** — https://jlcpcb.com/panelizer  
  Panelization rules + DFM.

</details>

---

## 5. Electronics References & Calculators

### 🌟 Top Calculator & Reference Sites

#### **Saturn PCB Toolkit** `[Platform: Windows]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.saturnpcb.com/saturn-pcb-toolkit

**Professional PCB design calculator**

- ✅ Impedance calculators
- ✅ Via calculators
- ✅ Differential pair routing
- ✅ PCB stackup design
- ✅ Trace width/spacing

**Perfect for**: Controlled impedance, high-speed design, signal integrity

---

#### **TI Webench Calculators** `[Platform: Web]` `[Level: All]` `[Status: 🟢Production]`
https://www.ti.com/design-resources/design-tools

**Complete suite of power/analog calculators**

- ✅ Power supply design
- ✅ Op-amp circuits
- ✅ LDO selection
- ✅ EMI filtering
- ✅ Impedance matching

**Perfect for**: Power electronics, analog design

---

### 📦 Complete Calculator List

<details>
<summary><b>Click to expand 25+ calculator & reference resources</b></summary>

#### General Electronics Education

- **AllAboutCircuits** — https://www.allaboutcircuits.com  
  Articles, calculators, tutorials.

- **Electronics-Tutorials** — https://www.electronics-tutorials.ws  
  Analog, digital, op-amps, filters, RF, power.

- **EEVblog Forum** — https://www.eevblog.com/forum  
  Massive community, reverse engineering discussions.

#### Online Calculators

- **CircuitLab (Free)** — https://www.circuitlab.com  
  Browser circuit sketching + calculators.

- **Falstad Circuit** — https://falstad.com/circuit  
  Visual SPICE for filters, op-amps, oscillators.

- **Okawa-Denshi** — https://www.iztok-jr.si/okawa  
  RC filters, op-amp gain, impedance, LC circuits.

- **MeowCAD** — https://meowcad.com  
  Collection of electronics calculators.

- **EEWeb Tools** — https://www.eeweb.com/tools  
  Op-amps, RC, LC, ADC, ladder networks.

- **Digikey Calculators** — https://www.digikey.com/en/resources/conversion-calculators  
  LED resistor, trace width, derating.

- **Omni Electronics** — https://www.omnicalculator.com/tag/electronics  
  Components, circuits, RF, measurement.

#### Vendor Design Tools

- **Analog Devices Tools** — https://analog.com/en/design-center/design-tools  
  Filter wizard, amplifier designer, power estimators.

- **Murata SimSurfing** — https://www.murata.com/en-eu/tool  
  RF & filter calculators with real Murata parts.

- **Keysight RF Tools** — https://www.keysight.com/find/apps  
  Transmission line, VSWR, S-parameters, antenna.

- **Mini-Circuits Toolbox** — https://www.minicircuits.com/applications  
  RF filter, attenuator calculators.

- **Pasternack RF Tools** — https://www.pasternack.com/t-calculators.aspx  
  Coax, S-param, waveguide, antenna.

- **PCB Toolkit (4PCB)** — https://www.4pcb.com/software/pcb-toolkit.html  
  Impedance, stackup, controlled impedance.

- **PowerEsim** — https://www.poweresim.com  
  SMPS, transformer, MOSFET loss, thermal.

#### Educational Resources

- **Analog Devices MT-Series** — https://www.analog.com/en/education/education-library/tutorials/mt-series.html  
  Op-amp + DSP tutorials.

- **TI Precision Labs** — https://training.ti.com/ti-precision-labs  
  Structured training: op-amps, ADCs, isolation, power.

- **MIT OpenCourseWare** — https://ocw.mit.edu  
  University analog & digital circuits courses.

- **Electrical4U** — https://www.electrical4u.com  
  Electronics, control systems, sensors, power.

</details>

---

## 6. Component Search & Datasheets

### 🌟 Top Component Search Engines

#### **Octopart** (Already covered above)

#### **Digikey** `[Platform: Web]` `[Level: All]` `[Status: 🟢Production]`
https://digikey.com

**World's largest electronic component distributor**

- ✅ Parametric search
- ✅ Real-time stock
- ✅ Datasheets
- ✅ 3D models
- ✅ Lifecycle info
- ✅ Free samples program
- ✅ Global shipping

**Perfect for**: Everything; most comprehensive inventory

---

#### **LCSC** `[Platform: Web]` `[Level: All]` `[Status: 🟢Production]`
https://lcsc.com

**Low-cost component sourcing**

- ✅ Huge catalog (1M+ parts)
- ✅ Very low prices
- ✅ JLCPCB assembly integration
- ✅ Datasheets
- ✅ Fast China shipping

**Perfect for**: Prototypes, cost optimization, JLCPCB assembly

---

### 📦 Complete Component Search List

<details>
<summary><b>Click to expand 30+ search engines & datasheet sources</b></summary>

#### Major Distributors

- **Mouser** — https://mouser.com  
  Parametric search, RoHS, stock, alternates.

- **Arrow** — https://arrow.com  
  Live pricing, datasheets, lifecycle.

- **RS Components** — https://in.rsdelivers.com  
  Datasheets, alternates, compliance, inventory.

- **Allied Electronics** — https://www.alliedelec.com  
  Datasheets, 3D models, alternates.

- **TME** — https://www.tme.eu  
  Global search with pricing.

#### Search Aggregators

- **FindChips** — https://findchips.com  
  Multi-distributor search.

- **PartStack** — https://partstack.com  
  Lifecycle, alternates, supply chain.

#### Library Tools

- **SnapEDA** — https://snapeda.com  
  Symbols/footprints + datasheets.

- **Ultra Librarian** — https://www.ultralibrarian.com  
  CAD models for components (limited free).

- **SamacSys** — https://componentsearchengine.com  
  Footprints, symbols, 3D models.

#### Manufacturer Direct

- **Nexperia** — https://www.nexperia.com/products  
  Logic, MOSFETs, discretes + SPICE models.

- **Infineon** — https://www.infineon.com  
  MOSFET, power, motor controller search.

- **Analog Devices** — https://www.analog.com/en/products  
  Datasheets, SPICE models, cross-reference.

- **TI** — https://www.ti.com  
  Part finder, datasheets, CAD models.

- **STMicroelectronics** — https://www.st.com  
  Datasheets, errata, footprints, app notes.

- **Microchip** — https://www.microchip.com  
  Datasheets, IBIS models, symbols, app notes.

- **onsemi** — https://www.onsemi.com  
  Datasheets, cross-reference.

- **Vishay** — https://www.vishay.com  
  Passives datasheets, symbols, 3D models.

- **Murata** — https://www.murata.com  
  Passives, RF components.

- **TE Connectivity** — https://www.te.com  
  Connectors, datasheets, 3D models.

#### Legacy/Obsolete Parts

- **OpenBoardView** — https://openboardview.org  
  Boardview files for repair/reverse engineering.

- **DatasheetCatalog** — https://www.datasheetcatalog.com  
  Archive of older datasheets.

- **Alldatasheet** — https://www.alldatasheet.com  
  Huge semiconductor datasheet repository.

- **Datasheet4U** — https://www.datasheet4u.com  
  Legacy/discontinued parts.

#### Industry Resources

- **SemiWiki** — https://www.semiwiki.com  
  Industry insight, design articles.

- **ChipEstimate** — https://www.chipestimate.com  
  Chip estimations, IP libraries.

</details>

---

## 7. Reference Designs & Open Hardware

### 🌟 Top Reference Design Sources

#### **Arduino Hardware** `[Platform: Open Hardware]` `[License: CC-BY-SA]`
https://github.com/arduino/ArduinoCore-schematics

**Complete open-source Arduino board designs**

- ✅ Schematics for all Arduino boards
- ✅ PCB layouts
- ✅ BOMs
- ✅ Eagle/KiCad files
- ✅ Production files

**Perfect for**: Learning PCB design, creating custom Arduino-compatible boards

---

#### **ESP32/ESP8266 Reference Designs** `[Platform: Espressif]` `[License: Open]`
https://www.espressif.com/en/support/download/documents

**Official Espressif hardware references**

- ✅ Complete schematics
- ✅ PCB layout files
- ✅ RF antenna design guidelines
- ✅ Power supply recommendations
- ✅ Certified layouts

**Perfect for**: ESP32 product design, Wi-Fi/BLE certification

---

#### **Adafruit Open Hardware** `[Platform: GitHub]` `[License: Various Open]`
https://github.com/adafruit

**Hundreds of open-source designs**

- ✅ Sensor breakout boards
- ✅ Power modules
- ✅ Wearable electronics
- ✅ Microcontroller boards
- ✅ Display modules

**Perfect for**: Learning module design, sensor integration

---

### 📦 Complete Reference Design List

<details>
<summary><b>Click to expand 40+ reference design sources</b></summary>

#### Development Board Vendors

- **Raspberry Pi Docs** — https://www.raspberrypi.com/documentation  
  Schematics, HAT design guide, GPIO specs.

- **SparkFun** — https://github.com/sparkfun  
  Open PCB designs for sensors, power, MCUs, BLE.

- **Pine64** — https://wiki.pine64.org  
  Open laptops, SBCs, accessories.

- **BeagleBone** — https://github.com/beagleboard  
  Open hardware for SBCs.

- **Purism Librem** — https://source.puri.sm  
  Security-focused open hardware.

#### Open Hardware Projects

- **OpenCompute** — https://www.opencompute.org  
  Server, PSU, networking hardware standards.

- **Open Electronics** — https://www.open-electronics.org  
  PCB designs, power circuits, IoT modules.

- **FOSSi Foundation** — https://fossi-foundation.org  
  RISC-V SoCs, FPGA tools, IP cores.

- **Open Source Ecology** — https://opensourceecology.org  
  Industrial machine control electronics.

- **OSHWA** — https://www.oshwa.org  
  Certified open hardware database.

- **Hackaday.io** — https://hackaday.io  
  Thousands of open hardware projects.

- **Thingiverse Electronics** — https://www.thingiverse.com  
  3D printable enclosures for electronics.

- **OSH Park Shared Projects** — https://oshpark.com/shared_projects  
  Public PCB designs.

- **OpenHardware.io** — https://www.openhardware.io  
  Open-source electronics project database.

#### Vendor Reference Designs

- **NI/LabVIEW** — https://github.com/NI  
  DAQ, motor control, instrumentation.

- **Microchip** — https://www.microchip.com/en-us/tools-resources/reference-designs  
  MCU, power, wireless designs.

- **STMicroelectronics** — https://www.st.com/en/evaluation-tools  
  Power, motor, sensor, RF designs.

- **TI Reference Designs** — https://www.ti.com/tool-reference-designs  
  Massive database: power, motor, analog, sensing.

- **Analog Devices Circuits from Lab** — https://www.analog.com/circuits-from-the-lab  
  Professional analog references with test results.

- **Nordic Semiconductor** — https://www.nordicsemi.com  
  BLE, Zigbee, Thread reference PCBs.

- **NXP** — https://www.nxp.com/design/design-resources  
  Motor control, power, audio, industrial IoT.

- **Silicon Labs** — https://www.silabs.com/development-tools/reference-designs  
  Zigbee/BLE references, RF layout.

- **RISC-V Boards** — https://github.com/riscv  
  Open-source SoC and dev boards.

#### Tools & Test Equipment

- **Dangerous Prototypes** — http://dangerousprototypes.com  
  Bus Pirate, Logic Sniffer, power boards.

- **DP GitHub** — https://github.com/DangerousPrototypes  
  PCB sources for open tools.

- **Great Scott Gadgets** — https://github.com/greatscottgadgets  
  HackRF SDR, GoodFET, Yardstick-One.

- **Libre Solar** — https://github.com/LibreSolar  
  Solar charge controllers, energy hardware.

#### Specialty Hardware

- **OpenMV Camera** — https://github.com/openmv  
  TinyML camera boards, full PCB files.

- **OpenBikeSensor** — https://github.com/openbikesensor  
  IoT bike devices with PCB/enclosure.

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [→ Firmware & Software](firmware.md)
- [→ Connectivity & Networking](connectivity.md)
- [→ Debugging & Testing](debugging-testing.md)

---

## 🤝 Contributing

Found a missing tool or broken link? Please contribute!

See [main contributing guidelines](../README.md#how-to-contribute)

**Tag Format for This Section**:
```markdown
- **Tool Name** `[Platform: Win/Mac/Linux]` `[Level: Beginner/Pro]` `[Status: 🟢/🟡/🔴]` — URL  
  Description
```

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources collection • Curated by Eurth Tech</sub>
</p>
