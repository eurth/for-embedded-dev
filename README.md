# Free for Embedded

A curated list of **free tools, resources and references** for Embedded, IoT and Hardware Engineers.

Community contributions are welcome.  
Add entries under the correct category with a one-line description and official link.

---

## A) Hardware Design

### 1. Schematic & PCB Design Tools
### 2. Simulation & Circuit Analysis
### 3. Mechanical / Enclosure / CAD Tools
### 4. BOM, DFM, DFA & Manufacturing Tools
### 5. Electronics References & Calculators
### 6. Component Search & Datasheets
### 7. Reference Designs & Open Hardware

---

## B) Firmware & Embedded Software

### 8. MCU SDKs & Toolchains
### 9. RTOS / Operating Systems
### 10. Drivers, Stacks & Middleware
### 11. Firmware Debugging & Reverse Engineering
### 12. Bootloaders & OTA Update Systems
### 13. Memory / Flash / Filesystem Utilities

---

## C) Connectivity & Networking

### 14. On-Device Communication Protocols  
(UART, I2C, SPI, CAN, Modbus, RS-485, BLE stacks etc.)

### 15. Network & IoT Protocols  
(MQTT, CoAP, HTTP, WebSockets, DDS, OPC-UA)

### 16. LPWAN / LoRa / Cellular IoT

### 17. Gateways, Packet Brokers & Network Servers

---

## D) Debugging, Testing & Measurement

### 18. Logic Analyzers & Protocol Decoders
### 19. Emulators / Simulators / Virtual Labs
### 20. Power Measurement & Energy Profiling
### 21. Firmware-Hardware Bring-Up & Validation Checklists

---

## E) Cloud, Dashboards & DevOps

### 22. Hosted Backends / Serverless / APIs
### 23. MQTT Brokers / Pub-Sub Platforms
### 24. Databases / Object Storage / Time-Series Storage
### 25. OTA Device Management Platforms
### 26. Dashboards / Monitoring / Telemetry
### 27. CI/CD, Code Hosting & Artifacts

---

## F) Security

### 28. Crypto Libraries & Secure Boot
### 29. Post-Quantum & Hardware Security
### 30. Certificate, Key & TLS Tools

---

## G) Compliance & Certification

### 31. EMI/EMC Pre-Compliance Tools
### 32. Safety Standards & Testing References
### 33. Battery & Environmental Certification
### 34. RF Certification & Spectrum Resources

---

## H) Edge AI / TinyML

### 35. Model Training & Conversion
### 36. MCU Inference Runtimes
### 37. Datasets & Testing Tools

---

## I) Learning & Reference Resources

### 38. Electronics Learning Platforms
### 39. Firmware & Protocol Learning
### 40. Datasheet Libraries & Application Notes
### 41. RF / Signal Integrity / Power Design Guides
### 42. Community Tools, Forums & Repositories

---

## How to Contribute
- Add a tool under the correct category  
- One-line description + official link  
- Only free tiers or open-source tools  
- No affiliate or paid promotional links  


## A) Hardware Design

### 1. Schematic & PCB Design Tools

- **KiCad** — https://www.kicad.org  
  Full EDA suite for schematic, PCB, 3D viewer, DRC/ERC, SPICE integration. 100% free with no board size or layer limits.

- **EasyEDA (Free Tier)** — https://easyeda.com  
  Browser-based schematic + PCB editor with JLCPCB integration. Free for public projects, limited private storage on free plan.

- **Flux** — https://flux.ai  
  Modern cloud-based PCB design with collaborative editing, AI-assist part placement and auto-routing. Free plan available with public projects & limited private designs.

- **JITX (AI-assisted PCB)** — https://www.jitx.com  
  Hardware design automation (code-driven PCB creation). Community/academic access has a free tier for experimentation.

- **DSN / DeepPCB AI** — https://deeppcb.ai  
  AI-assisted PCB auto-routing and component placement. Free usage with constraints and limited board complexity.

- **LibrePCB** — https://librepcb.org  
  Fully open-source schematic + PCB suite with modern UX. No licensing, no feature limits.

- **DesignSpark PCB** — https://www.rs-online.com/designspark/pcb-software  
  Free PCB tool from RS Components; export Gerbers and 3D. Some pro libraries/outputs require registration.

- **Upverter** — https://upverter.com  
  Browser-based, collaborative PCB design. Free for open and public hardware projects.

- **PCBFlow (Autodesk)** — https://www.autodesk.com/products/eagle/blog/introducing-pcbflow  
  Cloud PCB DFM tool from Autodesk. Free for basic manufacturability checks & small boards.

- **Autodesk Fusion 360 for Personal Use** — https://www.autodesk.com/products/fusion-360/personal  
  Includes basic PCB + mechanical CAD. Free for personal, non-commercial use with feature limits.

- **Autodesk EAGLE (Legacy Free Version)** — https://www.autodesk.com/products/eagle/overview  
  Old free hobbyist licenses still usable; legacy version supports small boards.

- **Osmond PCB** — https://www.osmondpcb.com  
  macOS PCB design with unlimited board size, layers, and components for free.

- **PCB Artist** — https://www.4pcb.com/free-pcb-layout-software.html  
  Free Windows PCB layout software with no board size limits when manufacturing through Advanced Circuits.

- **Fritzing** — https://fritzing.org  
  Beginner-friendly schematic + PCB editor. Open-source (free to compile), simple paid binary downloads.

- **CircuitMaker (Altium Community Edition)** — https://circuitmaker.com  
  Free PCB design tool for hobby/open projects. Unlimited layers, advanced routing, but designs are public.

- **TinyCAD** — https://sourceforge.net/projects/tinycad  
  Free schematic capture tool for Windows; library of standard symbols.

- **gEDA / PCB** — http://wiki.geda-project.org/  
  Classic open-source schematic + PCB tools used in Linux environments.

- **XCircuit** — http://opencircuitdesign.com/xcircuit  
  Open-source schematic capture tool with LaTeX-quality outputs.

- **Pad2Pad** — https://www.pad2pad.com  
  Free schematic + PCB software tied to their fabrication. No size limits if ordering boards.

- **ZenitPCB** — http://www.zenitpcb.com  
  Free Windows PCB tool for small/medium boards. Gerber export supported.

- **ExpressPCB Free** — https://www.expresspcb.com  
  Free PCB layout software; simple, beginner-friendly. Export limited unless ordering manufacturing.

- **Horizon EDA** — https://horizon-eda.org  
  Modern open-source PCB tool with constraint management and hierarchical schematics.

- **Protogen by Flux** — https://flux.ai/protogen  
  AI-driven schematic generation from natural language. Free tier with limitations.

- **PCB Droid** — https://pcbdroid.com  
  Android-based PCB editor, free for simple 2-layer boards and hobby layouts.

- **CzechCAD KiKit + Interactive HTML BOM** — https://github.com/yaqwsx/KiKit  
  Companion tools to KiCad for panelization, assembly outputs, and interactive BOMs (free & open).

- **OpenBoardView** — https://openboardview.org  
  Free viewer for boardview repair files — useful for reverse engineering and servicing hardware.

### 2. Simulation & Circuit Analysis

- **LTspice** — https://www.analog.com/ltspice  
  Industry-standard SPICE simulator for analog/power circuits. Fully free with no node limits; large library of power devices.

- **QUCS (Quite Universal Circuit Simulator)** — http://qucs.sourceforge.net  
  Open-source analog + RF circuit simulator with schematic capture and AC/DC/transient/noise analysis.

- **QUCS-S (QUCS + SPICE backend)** — https://ra3xdh.github.io/  
  Modern fork of QUCS with SPICE compatibility and improved stability; free and open-source.

- **Ngspice** — http://ngspice.sourceforge.net  
  Open-source mixed-signal SPICE simulator used in universities and embedded power design. Integrates with KiCad.

- **Micro-Cap 12 (Free)** — https://micro-cap.com  
  Formerly commercial SPICE simulator, now fully free. Powerful analog/digital simulation and waveform analysis.

- **Fritzing Simulation Mode** — https://fritzing.org  
  Beginner-friendly simulator for simple breadboard circuits; free as open-source, limited depth.

- **Falstad Circuit Simulator** — https://falstad.com/circuit  
  Browser-based visual circuit simulator for analog/digital basics; great for teaching and block-level debugging.

- **EveryCircuit** — https://everycircuit.com  
  Visual circuit simulator for web/mobile with animations; free tier supports small circuits.

- **CircuitJS (SPICE Web Simulator)** — https://circuitjs.org  
  Open-source web-based simulation of analog/digital circuits derived from Falstad; free with export/import support.

- **OpenEMS** — https://openems.de  
  Open-source electromagnetic field simulation (FDTD) — useful for antenna, RF, EMC studies. Fully free.

- **4NEC2** — http://www.qsl.net/4nec2/  
  Free antenna simulation (NEC2 engine) for dipoles, RF front-ends, matching networks.

- **AppCAD** — https://www.broadcom.com/support/resources/appcad  
  RF design tool with calculators for S-parameters, line matching, filters. Free download.

- **RFSim99** — https://www.electronics-lab.com/project/rfsim99-rf-simulation-software  
  Classic free RF circuit simulator for filters, amplifiers, matching networks.

- **Scilab/Xcos** — https://www.scilab.org  
  Free Matlab-like environment with control-systems and circuit simulation blocks; useful for PID, PLL, filters.

- **GNU Octave** — https://octave.org  
  Matlab-compatible, free tool for control systems, DSP, and circuit math. Large community libraries.

- **KiCad SPICE Integration** — https://kicad.org  
  KiCad includes Ngspice integration for board-level analog simulation; 100% free.

- **QucsStudio** — https://qucsstudio.de  
  Enhanced analog + RF simulator based on Qucs with modern GUI; free for Windows.

- **SimulIDE** — https://simulide.com  
  Real-time simulation of microcontrollers (AVR, PIC, Arduino) with simple circuits; free and open-source.

- **Logisim Evolution** — https://github.com/reds-heig/logisim-evolution  
  Digital logic simulator and circuit-builder used for teaching CPU design; open-source.

- **DigitalJS** — https://digitaljs.tilk.eu  
  Browser-based digital logic simulator for gates, flip-flops, CPUs; free.

- **Verilator** — https://www.veripool.org/verilator  
  Open-source Verilog simulator for high-speed digital testbenches; used in FPGA/ASIC flows.

- **Cocotb (Python for RTL simulation)** — https://www.cocotb.org  
  Free, open-source co-simulation for digital designs — Python testbenches driving HDL sims.

- **QSPICE** — https://qspice.com  
  High-performance SPICE simulator from Qorvo; free to use and good for switching power supplies.

- **PowerEsim** — https://www.poweresim.com  
  Online SMPS simulation and transformer design tool; free for basic power supply modeling.

- **TI Webench Power Designer** — https://webench.ti.com  
  Power stage design, component selection, thermal analysis, simulation — free with TI devices.

- **ST eDesignSuite** — https://edesignsuite.st.com  
  ST’s free design/simulation tools for SMPS, motor control, and analog circuits.

- **Microchip MPLAB Mindi** — https://www.microchip.com/mplab/mindi  
  SPICE simulation for Microchip analog/power ICs; free with device libraries.

- **iCircuit** — https://icircuitapp.com  
  Simple analog/digital visual simulator (Windows/macOS/iPad). Free demo tier.

- **OpenModelica** — https://openmodelica.org  
  Open-source modeling and simulation environment for system-level electronics, thermal, mechanics.

- **Simscape (MATLAB Online Trial)** — https://mathworks.com/products/simscape.html  
  Not fully free, but free trial + academic/free-online access for learning system modeling.

### 3. Mechanical / Enclosure / CAD Tools

- **Fusion 360 (Personal / Startup License)** — https://www.autodesk.com/products/fusion-360/personal  
  Full 3D CAD, CAM, simulation, PCB/mech integration. Free for personal/hobby use and eligible startups with limitations on advanced toolpaths and team management.

- **FreeCAD** — https://www.freecad.org  
  Open-source parametric 3D CAD for mechanical parts, enclosures, assemblies. 100% free, large community, Python automation.

- **Onshape Free Plan** — https://www.onshape.com  
  Cloud CAD for mechanical design with version control and assemblies. Free plan for public projects (designs are visible to community).

- **Tinkercad** — https://www.tinkercad.com  
  Browser-based 3D modeling for basic enclosures and STL exports. Free, widely used for fast mockups & 3D prints.

- **Blender** — https://www.blender.org  
  Open-source 3D modeling + sculpting tool; used for organic enclosures and printed devices. Fully free.

- **SolveSpace** — https://solvespace.com  
  Lightweight parametric 3D CAD, constraints, assemblies, 2D drawings. Small download, fully open-source.

- **OpenSCAD** — https://openscad.org  
  Script/programming-based CAD for parametric enclosures. Free and open-source, great for repeatable designs.

- **Wings3D** — http://www.wings3d.com  
  Free polygonal modeler useful for enclosure concepts, snap fits, and organic housings.

- **Meshmixer (Autodesk)** — https://www.meshmixer.com  
  Free mesh repair and editing tool for 3D printed enclosure workflows.

- **Microsoft 3D Builder** — https://www.microsoft.com/store/productId/9NBLGGH42THS  
  Free STL viewer/editor included on Windows; good for simple enclosure adjustments.

- **PrusaSlicer** — https://www.prusa3d.com/prusaslicer/  
  Free slicer with support material tuning and printability checks for enclosure designs.

- **Bambu Studio** — https://bambulab.com/bambu-studio  
  Free slicer for FDM printers; supports part orientation optimization and strength analysis.

- **Shapr3D (Free Basic)** — https://www.shapr3d.com  
  Easy CAD for iPad/Windows with direct modeling. Free basic plan allows small projects and STL/STEP export.

- **SelfCAD (Free Tier)** — https://www.selfcad.com  
  Browser-based 3D modeling with boolean ops and STL export. Free plan for simple designs.

- **V-Cut PCB Enclosure Generators (Scripted SCAD Tools)** — e.g., https://github.com/yaqwsx/KiKit  
  Parameterized 3D enclosure tools linked to PCB dimensions; free and open-source.

- **Cura (Ultimaker)** — https://ultimaker.com/software/ultimaker-cura  
  Free slicer with printability simulation and design recommendations for enclosure strength.

- **MakeHuman** — http://www.makehumancommunity.org  
  Free modeling reference for anthropometric sizes in wearable device design.

- **Fusion 360 Generative Design (Trial / Limited Free)** — https://www.autodesk.com/products/fusion-360/features/generative-design  
  Generative shape optimization for lightweight parts. Limited access under personal license or trial.

- **FreeCAD A2Plus / Assembly4 Workbenches** — https://wiki.freecadweb.org/Workbenches  
  Fully free assembly constraint systems inside FreeCAD for mechanical designs.

- **OpenJSCAD** — https://openjscad.org  
  Web-based programmable CAD for enclosures using JavaScript; free and open-source.

### 4. BOM, DFM, DFA & Manufacturing Tools

- **KiKit (Panelization + Assembly automation)** — https://github.com/yaqwsx/KiKit  
  Open-source tool for KiCad panelization, fabrication files, pick-and-place, and interactive BOM. Completely free.

- **Interactive HTML BOM** — https://github.com/openscopeproject/InteractiveHtmlBom  
  Auto-generates clickable BOM + component highlighting for assembly. Free and open-source.

- **PartStack** — https://partstack.com  
  Free component explorer with alternates, lifecycle status, and supplier data. Free plan for individuals.

- **Octopart** — https://octopart.com  
  Component search, pricing, lifecycle and datasheets from multiple suppliers. Free to use publicly.

- **LCSC** — https://lcsc.com  
  Free component search, pricing, alternates; integrates with JLCPCB manufacturing.

- **JLCPCB Assembly Tools** — https://jlcpcb.com  
  Free BOM & CPL parsing, DFM checks, stock parts database. Manufacturing paid, tooling free.

- **PCBWay DFM Tool** — https://pcbway.com  
  Online DFM rule check for PCB fabrication. Free to use before manufacturing.

- **Macrofab BOM Tool** — https://macrofab.com  
  Free BOM upload, alternate suggestions, and instant PCBA quotes.

- **Mouser Part Database** — https://mouser.com  
  Free access to datasheets, alternates, lifecycle status and stock across suppliers.

- **Digikey KiCad Plugin** — https://www.digikey.com/en/kicad  
  Free tool to import symbols/footprints and push BOM from KiCad to Digikey.

- **Ultra Librarian (Free Tier)** — https://www.ultralibrarian.com  
  Free downloads of many PCB footprints and 3D models (limited free pulls per month).

- **SnapEDA (Free Tier)** — https://www.snapeda.com  
  Free symbols/footprints for many components; paid for bulk/pro features.

- **SamacSys Library Loader (Free)** — https://componentsearchengine.com  
  Free footprints and symbols for KiCad, Altium, Eagle, etc.

- **Digi-X (DigiKey BOM Manager)** — https://www.digikey.com/en/resources/digix  
  Free BOM management, parametric search, alternates, lifecycle notifications.

- **Zuken CADSTAR “Lite” / Free Viewer** — https://www.zuken.com  
  Free viewer and limited design capability for BOM and rule checking.

- **PartQuest** — https://www.partquest.com  
  Free online schematic symbols and models with BOM management tie-ins.

- **ComponentSearchEngine** — https://componentsearchengine.com  
  Free component library + lifecycle data + CAD models.

- **SiliconExpert Free Trials & Feeds** — https://www.siliconexpert.com  
  Not fully free, but usable free trial for lifecycle, RoHS, alternates — good for risk analysis.

- **CalcuQuote (Free Quotation Tools)** — https://calcuquote.com  
  Free tools to estimate PCBA assembly costs and lead times for small runs.

- **PCB Panelizer by JLCPCB** — https://jlcpcb.com/panelizer  
  Free online panelization rules and DFM checks; manufacturing is paid.

- **OpenBOM (Free Tier)** — https://openbom.com  
  Cloud BOM and inventory management. Free individual usage; paid team features.

- **BOMIST** — https://bomist.com  
  Local inventory and BOM management with free hobby license.

- **LibrePCB Assembly Outputs** — https://librepcb.org  
  Free BOM, pick-and-place, netlist, fabrication output generation.

- **Tracealyzer (Free Trial)** — https://percepio.com/tracealyzer  
  Not fully free, but free trial useful for DFA of firmware/RTOS scheduling and bottlenecks.

- **FitFab (3D Print DFM Checker)** — https://fitfab.io  
  Free tools to check enclosure orientation, support requirement, manufacturability for FDM prints.

- **Fusion 360 Assembly Export Tools (Free Personal License)** — https://autodesk.com/products/fusion-360/personal  
  Exports STEP/STL for enclosure + PCB fit checks; useful for DFA.

- **DigiKey BOM Tool / CSV Import** — https://www.digikey.com  
  Free BOM comparison, stock alerts, lifecycle, price breaks and alternates.

- **Mouser BOM Tool / RoHS Check** — https://mouser.com  
  Free BOM manager with RoHS and REACH compliance lookup.

### 5. Electronics References & Calculators

- **AllAboutCircuits** — https://www.allaboutcircuits.com  
  Free electronics articles, calculators, tutorials, and reference guides widely used by students and professionals.

- **Electronics-Tutorials** — https://www.electronics-tutorials.ws  
  Free learning site covering analog, digital, op-amps, filters, RF basics, power electronics, and math.

- **EEVblog / EEVblog Forum** — https://www.eevblog.com/forum  
  Massive free electronics community and practical hardware reverse engineering discussions.

- **CircuitLab Free Simulator** — https://www.circuitlab.com  
  Browser-based circuit sketching and calculators. Free mode supports basic simulations and sharing.

- **Falstad Circuit Calculator** — https://falstad.com/circuit  
  Free visual SPICE calculations for filters, op-amp stages, oscillators, etc.

- **Okawa-Denshi (Electronics Calculators)** — https://www.iztok-jr.si/okawa  
  Excellent free calculators for RC filters, op-amp gain, impedance, LC resonant circuits.

- **MeowCAD Calculators** — https://meowcad.com  
  Free web collection of electronics calculators and symbol libraries.

- **Analog Devices Tools** — https://analog.com/en/design-center/design-tools  
  Free calculators and design tools (filter wizard, amplifier designer, power estimators).

- **Texas Instruments Webench Calculators** — https://www.ti.com/design-resources/design-tools  
  Free online calculators for power, LDOs, op-amps, EMI, impedance matching.

- **Murata SimSurfing / LC Filter Designer** — https://www.murata.com/en-eu/tool  
  Free RF and filter calculators with real Murata parts.

- **Keysight RF Tools** — https://www.keysight.com/find/apps  
  Free RF calculators for transmission line, VSWR, S-parameters, antenna match.

- **Mini-Circuits Toolbox** — https://www.minicircuits.com/applications  
  Free RF filter and attenuator calculators with real component models.

- **RF Tools by Pasternack** — https://www.pasternack.com/t-calculators.aspx  
  Free online calculators for coax, S-parameters, waveguides, antennas.

- **Saturn PCB Design Toolkit (Free)** — https://www.saturnpcb.com/saturn-pcb-toolkit  
  Free Windows tool for impedance, via calculators, differential pair routing, PCB stackups.

- **PCB Toolkit (Saturn Alternatives)** — https://www.4pcb.com/software/pcb-toolkit.html  
  Free impedance and PCB manufacturing calculators for stackup and controlled impedance.

- **PowerEsim (Free Power Calculators)** — https://www.poweresim.com  
  SMPS, transformer, MOSFET loss, thermal modelling — free for basic use.

- **EEWeb Tools** — https://www.eeweb.com/tools  
  Free online calculators for electronics: op-amps, RC, LC, ADC resolution, ladder networks.

- **Digikey Calculators** — https://www.digikey.com/en/resources/conversion-calculators  
  Free practical calculators for electronics and PCB design, including LED resistor calc, trace width, derating, etc.

- **Omni Electronics Calculators** — https://www.omnicalculator.com/tag/electronics  
  Free calculators for components, circuits, RF, and measurement.

- **Electrical4U** — https://www.electrical4u.com  
  Free educational content about electronics, control systems, sensors, and power engineering.

- **Programming & Logic Diagram Symbols (NXP / TI)** — https://www.ti.com/lit/ug/sn544632/sn544632.pdf  
  Free logic families and reference designators handbook.

- **Analog Devices MT-Series Tutorials** — https://www.analog.com/en/education/education-library/tutorials/mt-series.html  
  High-quality free analog electronics + op-amp + DSP notes.

- **Texas Instruments TI Precision Labs** — https://training.ti.com/ti-precision-labs  
  Free structured electronics training: op-amps, ADCs, isolation, power.

- **MIT OpenCourseWare: Analog & Digital Circuits** — https://ocw.mit.edu  
  Free university-level courses on electronics design.

- **Allied Electronics Parametric Search** — https://www.alliedelec.com  
  Useful for finding alternates and part replacements.

### 6. Component Search & Datasheets

- **Octopart** — https://octopart.com  
  Universal electronic component search with lifecycle, pricing, stock, datasheets. Free to use for unlimited searches.

- **FindChips** — https://findchips.com  
  Global distributor search with pricing, availability, alternates, and datasheets. Free to search.

- **LCSC** — https://lcsc.com  
  Massive low-cost parts catalog; datasheets, alternates, stock, and symbols for many components. Free to search.

- **Digikey** — https://digikey.com  
  Complete parametric search, datasheets, 3D models, lifecycle. All search tools free.

- **Mouser** — https://mouser.com  
  Free parametric search, datasheets, RoHS, stock, alternates, cross-referencing.

- **Arrow** — https://arrow.com  
  Free search with live distributor pricing, datasheets, and lifecycle for many semiconductors.

- **RS Components** — https://in.rsdelivers.com  
  Free datasheets, alternates, environmental compliance, distributor inventory.

- **Allied Electronics** — https://www.alliedelec.com  
  Free distributor search with datasheets, 3D models, and alternates.

- **TME (Transfer Multisort Elektronik)** — https://www.tme.eu  
  Free global component search with datasheets and pricing.

- **SnapEDA (Free Tier)** — https://snapeda.com  
  Free symbols & footprints for many components + datasheets. Paid for bulk/pro features.

- **Ultra Librarian (Free Tier)** — https://www.ultralibrarian.com  
  Free downloads of CAD models for many components each month.

- **SamacSys / ComponentSearchEngine** — https://componentsearchengine.com  
  Free footprints, symbols, 3D models, and datasheets.

- **PartStack** — https://partstack.com  
  Free component explorer with lifecycle state, alternates, datasheets and supply chain hints.

- **Nexperia Parametric Search** — https://www.nexperia.com/products  
  Free search for logic families, MOSFETs, discretes with datasheets and SPICE models.

- **Infineon Product Finder** — https://www.infineon.com/cms/en/product/  
  Free MOSFET, power stage, motor controller search with datasheets & thermal data.

- **ADI (Analog Devices) Cross-Ref & Models** — https://www.analog.com/en/products  
  Free datasheets, SPICE models, and cross-reference tools.

- **Texas Instruments Parametric Search** — https://www.ti.com  
  Free part finder with datasheets, CAD models, and guaranteed stock sources.

- **STMicroelectronics Part Selector** — https://www.st.com  
  Free datasheets, errata, footprints, application notes.

- **Microchip Parametric Search** — https://www.microchip.com  
  Free datasheets, IBIS models, symbols, footprints, app notes.

- **ON Semiconductor / onsemi** — https://www.onsemi.com  
  Free datasheets and cross-reference finder.

- **Vishay, Murata, TE Connectivity Libraries**  
  - Vishay: https://www.vishay.com  
  - Murata: https://www.murata.com  
  - TE: https://www.te.com  
  All provide free datasheets, symbols, 3D models for passives, RF and connectors.

- **OpenBoardView** — https://openboardview.org  
  Free tool to view boardview files for repair, rework and reverse engineering.

- **DatasheetCatalog** — https://www.datasheetcatalog.com  
  Large free archive of older and obscure component datasheets.

- **Alldatasheet** — https://www.alldatasheet.com  
  Huge free repository of semiconductor datasheets.

- **Datasheet4U** — https://www.datasheet4u.com  
  Free datasheet search for legacy and discontinued parts.

- **SemiWiki (Free Articles & Datasheets)** — https://www.semiwiki.com  
  Industry insight, design articles, and device references. Mostly free.

- **ChipEstimate (Free RNA/EDA Models)** — https://www.chipestimate.com  
  Free access to chip estimations, some datasheets, and IP libraries (mixed content).

### 7. Reference Designs & Open Hardware

- **Arduino Hardware Reference Designs** — https://github.com/arduino/ArduinoCore-schematics  
  Free, open-source schematics and PCB files for all Arduino boards.

- **ESP32 / ESP8266 Reference Designs (Espressif)** — https://www.espressif.com/en/support/download/documents  
  Free schematics, PCB files, antenna layouts, power design notes.

- **Raspberry Pi Hardware Docs** — https://www.raspberrypi.com/documentation/computers/raspberry-pi.html  
  Free official schematics and HAT design guides, including GPIO and PSU rules.

- **Adafruit Open Hardware** — https://github.com/adafruit  
  Hundreds of open-source PCB designs, sensors, modules, power circuits, wearable electronics.

- **SparkFun Open Hardware** — https://github.com/sparkfun  
  Completely open PCB designs for sensor boards, power management, microcontrollers, BLE modules.

- **Pine64 Hardware Designs** — https://wiki.pine64.org  
  Open hardware laptops, SBCs, and accessories with full schematics, board files.

- **Purism Librem Hardware** — https://source.puri.sm  
  Open-source laptop and phone hardware with security-focused circuit design.

- **BeagleBone Open Hardware** — https://github.com/beagleboard  
  Open-source hardware for BeagleBone SBCs with full schematics and layouts.

- **OpenCompute Project** — https://www.opencompute.org  
  Open-source hardware standards for servers, power supplies, and networking gear.

- **Open Electronics** — https://www.open-electronics.org  
  Free PCB designs, power circuits, sensor boards, IoT modules.

- **FOSSi Foundation (Open Silicon)** — https://fossi-foundation.org  
  Free RISC-V SoCs, open FPGA tools, hardware IP cores.

- **Open Source Ecology** — https://opensourceecology.org  
  Open-source hardware machines and control electronics for industrial designs.

- **OSHWA (Open Source Hardware Association)** — https://www.oshwa.org  
  Certified open-hardware database and guidelines for licensing and publishing PCB designs.

- **Hackaday.io Projects** — https://hackaday.io  
  Thousands of open-source hardware projects, schematics and PCB files.

- **Thingiverse Electronics Projects** — https://www.thingiverse.com  
  Free 3D-printable enclosure and hardware designs for electronics builds.

- **NI / LabVIEW Open Reference Designs** — https://github.com/NI  
  Free open hardware reference designs for DAQ, motor control, instrumentation.

- **Microchip Reference Designs** — https://www.microchip.com/en-us/tools-resources/reference-designs  
  Free MCU, power, and wireless designs with full schematics and Gerbers.

- **STMicroelectronics Hardware Reference Designs** — https://www.st.com/en/evaluation-tools.html  
  Free ST-based power, motor, sensor, RF designs with schematics and layout files.

- **Texas Instruments Reference Designs** — https://www.ti.com/tool-reference-designs  
  Massive free database of power, motor, analog, sensing reference designs.

- **Analog Devices Circuits from the Lab** — https://www.analog.com/en/design-center/reference-designs.html  
  Professional-grade analog reference designs with schematics and test results.

- **Nordic Semiconductor HW Designs** — https://www.nordicsemi.com/Products/Development-hardware  
  Free BLE, Zigbee, Thread reference PCBs & RF layout files.

- **NXP Reference Designs** — https://www.nxp.com/design/design-resources:DESIGN-RESOURCES  
  Free motor control, power, audio, industrial IoT designs with PCB files.

- **SiLabs Open Hardware** — https://www.silabs.com/development-tools/reference-designs  
  Free Zigbee/BLE reference designs and RF layout guidelines.

- **RISC-V Open Boards** — https://github.com/riscv  
  Open-source SoC, dev boards, and toolchains.

- **Dangerous Prototypes** — http://dangerousprototypes.com  
  Open hardware tools like BusPirate, Logic Sniffer, power boards and analyzers.

- **DP Live Projects Repo** — https://github.com/DangerousPrototypes  
  Full PCB sources for dozens of open hardware tools.

- **Great Scott Gadgets** — https://github.com/greatscottgadgets  
  Open hardware including HackRF SDR, GoodFET, Yardstick-One.

- **Libre Solar** — https://github.com/LibreSolar  
  Open-source solar charge controllers and energy hardware.

- **OpenMV (Open Hardware Camera Modules)** — https://github.com/openmv  
  TinyML camera boards with full PCB files and reference designs.

- **OpenBikeSensor, OpenBikeComputer** — https://github.com/openbikesensor  
  Open hardware IoT devices with PCB and enclosure.

- **OSH Park Shared Projects** — https://oshpark.com/shared_projects  
  Thousands of public PCB designs free to view/download.

- **OpenHardware.io** — https://www.openhardware.io  
  Database of open-source electronics projects and PCBs.

## B) Firmware & Embedded Software

### 8. MCU SDKs & Toolchains

- **ESP-IDF (Espressif)** — https://github.com/espressif/esp-idf  
  Official free SDK for ESP32/ESP8266 with FreeRTOS, Wi-Fi, BLE, OTA, mesh, drivers, and CLI tools. 100% open-source.

- **Arduino Core (Open Source)** — https://github.com/arduino  
  Free toolchain & HAL libraries for ESP32, AVR, ARM, RP2040, STM32 and more. Massive community libraries.

- **PlatformIO** — https://platformio.org  
  Free cross-platform build system + library manager + debugger for 1000+ MCUs. Integrates with VSCode.

- **STM32CubeMX / STM32CubeIDE** — https://www.st.com/en/development-tools/stm32cubemx.html  
  Free code generator + HAL drivers + IDE for STM32. Includes peripheral config and clock tree generator.

- **Zephyr RTOS SDK** — https://zephyrproject.org  
  Open-source RTOS & SDK for STM32, NRF, ESP32, NXP, TI, RISC-V and ARM MCUs. Linux-like dev environment.

- **Nordic nRF Connect SDK** — https://www.nordicsemi.com/Products/Development-software/nRF-Connect-SDK  
  Free Zephyr-based SDK for BLE, Zigbee, Thread, LTE-M, NB-IoT with secure boot and OTA.

- **RP2040 Pico SDK** — https://github.com/raspberrypi/pico-sdk  
  Free C/C++ SDK + examples, peripherals, USB stack, multicore support for Raspberry Pi Pico.

- **Microchip MPLAB XC Compilers (Free Mode)** — https://www.microchip.com/mplab  
  Free C compilers for PIC, dsPIC, AVR and SAM MCUs. Reduced optimization on free tier but fully usable.

- **Atmel START / AVR Toolchain** — https://start.atmel.com  
  Free code generator + ASF driver libraries for AVR and SAM MCUs.

- **NXP MCUXpresso SDK & IDE** — https://www.nxp.com/mcuxpresso  
  Free IDE + drivers/middleware for Kinetis & LPC MCUs. Includes FreeRTOS and USB middleware.

- **TI MSP430 & SimpleLink SDK** — https://www.ti.com/tool/SIMPLELINK-SDK  
  Free toolchains and HAL for MSP430 and TI wireless MCUs. BLE, Zigbee, Sub-GHz stacks included.

- **Silicon Labs Gecko SDK** — https://www.silabs.com/developers  
  Free SDK for EFR32 (BLE, Zigbee, Thread, Sub-GHz), with Simplicity Studio IDE.

- **Renesas Flexible Software Package (FSP)** — https://www.renesas.com/software-tool/fsp  
  Free SDK for RA/RX MCUs with Azure RTOS, USB, crypto, and drivers.

- **Infineon ModusToolbox** — https://www.infineon.com/modustoolbox  
  Free SDK and IDE for PSoC, AIROC BLE/Wi-Fi, XMC motor-control MCUs.

- **ST Motor Control SDK (Free)** — https://www.st.com/en/embedded-software/stsw-stm32100.html  
  Free FOC/PMSM motor libraries with current loops, observers, startup profiles.

- **CMSIS (ARM Cortex HAL)** — https://www.arm.com/why-arm/technologies/cmsis  
  Free Cortex-M HAL, DSP, RTOS abstraction, drivers; used across STM32, NXP, NRF, TI, etc.

- **mbed OS (Arm Mbed)** — https://os.mbed.com  
  Free RTOS and SDK for Cortex-M boards, OTA, networking, TLS, cloud connectors.

- **Apache Mynewt** — https://mynewt.apache.org  
  Open-source RTOS + networking stack; supports BLE, image bootloaders, OTA.

- **TinyUSB** — https://github.com/hathach/tinyusb  
  Free USB device stack for ESP32-S2/S3, RP2040, STM32, NRF.

- **LittleFS** — https://github.com/littlefs-project/littlefs  
  Free fault-tolerant filesystem for MCUs; flash-safe with power-loss protection.

- **LVGL (Graphics Library)** — https://lvgl.io  
  Free embedded GUI library for MCUs, displays, and RTOS. Works on ESP32, STM32, RP2040, Zephyr.

- **Wokwi (Simulator SDK)** — https://wokwi.com  
  Free cloud simulation of Arduino, AVR, ESP32, STM32 with real-time UART, I2C and debug.

- **GCC ARM Embedded Toolchain** — https://developer.arm.com/downloads  
  Free compiler, assembler, linker and libs for ARM Cortex-M. Industry standard.

- **RISC-V GCC Toolchain** — https://github.com/riscv-collab/riscv-gnu-toolchain  
  Free compiler and libs for RISC-V MCUs and SoCs.

- **Clang/LLVM Embedded Toolchain** — https://clang.llvm.org  
  Free modern compiler backend for C/C++ embedded development.

- **OpenOCD** — http://openocd.org  
  Free JTAG/SWD debug server for STM32, ESP32, RISC-V, Nordic, and more.

- **Picotool (Raspberry Pi)** — https://github.com/raspberrypi/picotool  
  Free command-line utility for flashing/debugging RP2040.

- **uf2conv & Drag-and-Drop Bootloaders** — https://github.com/microsoft/uf2  
  Free UF2 flashing for Arduino/RP2040 boards (mass-storage bootloaders).

- **AVRDUDE** — https://github.com/avrdude/avrdude  
  Free programming tool for AVR and Arduino bootloaders.

- **PicoBoot / rp2040-uf2** — https://github.com/raspberrypi/picoboot  
  Free ROM bootloader utilities for Pico.

- **SDCC (Small Device C Compiler)** — http://sdcc.sourceforge.net  
  Free C compiler for 8051, STM8, Z80, PIC16/18 and other small cores.

- **OpenSTM32 (System Workbench)** — http://www.openstm32.org  
  Free Eclipse-based IDE and toolchain for STM32.

- **ChibiOS HAL + RTOS** — http://chibios.org  
  Open-source HAL, drivers, RTOS and bootloader for STM32, NRF, Kinetis.

- **Zephyr West + CMake Tooling** — https://github.com/zephyrproject-rtos/west  
  Free meta-tool for building multi-module embedded projects (Zephyr, drivers, modules).

- **MCUboot** — https://github.com/mcu-tools/mcuboot  
  Free, secure bootloader for ARM, ESP32, NRF, Zephyr; supports DFU, signature validation, rollback.

- **RIOT OS** — https://riot-os.org  
  Free IoT RTOS for ARM, AVR, MSP430, ESP32, RISC-V with low memory footprint and 6LoWPAN/CoAP stacks.

- **FreeRTOS (Amazon)** — https://www.freertos.org  
  Free MIT-licensed RTOS for practically every MCU; TCP/IP, MQTT, OTA, TLS, and debugging add-ons.

- **TI-RTOS / TI SysConfig** — https://www.ti.com/tool/SYSCONFIG  
  Free RTOS + driver config for SimpleLink Wi-Fi/BLE/Sub-GHz and MSP430 MCUs.

- **Azure RTOS (ThreadX, FileX, NetX)** — https://github.com/azure-rtos  
  Formerly commercial, now free/open for STM32, NXP, Renesas, TI; RTOS + filesystem + networking + USB.

- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls  
  Free TLS, crypto and X.509 library for MCUs; works on FreeRTOS and Zephyr.

- **wolfSSL / wolfMQTT (Free Tier)** — https://www.wolfssl.com  
  Free TLS/MQTT/crypto stack for hobby and open-source projects (dual-licensed).

- **tinycrypt** — https://github.com/intel/tinycrypt  
  Ultra-small crypto library for Cortex-M and 8-bit MCUs; free and open-source.

- **TinyUSB** — https://github.com/hathach/tinyusb  
  Small, free USB Device stack for ESP32-S2/S3, RP2040, STM32, NRF.

- **OpenBLDC** — https://github.com/open-bldc  
  Free motor control firmware and tools for BLDC drivers.

- **SimpleFOC** — https://simplefoc.com  
  Free field-oriented motor control library for Arduino, STM32, ESP32.

- **ChibiOS/NIL** — http://chibios.org  
  Tiny free RTOS + HAL for very small MCUs (STM32, AVR, NRF, Kinetis, etc.).

- **libopencm3** — https://libopencm3.org  
  Free open-source peripheral libraries for ARM Cortex-M (STM32, LPC, Kinetis, EFM32…).

- **mbed-cli** — https://github.com/ARMmbed/mbed-cli  
  Free build/flash/debug tool for Mbed OS boards and SDKs.

- **ESP-AT SDK** — https://github.com/espressif/esp-at  
  Free AT command firmware for ESP32/ESP8266 as Wi-Fi/BLE modems.

- **ESP-MDF (Mesh Development Framework)** — https://github.com/espressif/esp-mdf  
  Free mesh networking SDK for ESP32.

- **ESP-Zigbee / ESP-Thread SDK** — https://github.com/espressif/esp-zigbee-sdk  
  Free Zigbee and Thread stacks for ESP32-H2/H4 platforms.

- **ESP-RainMaker** — https://github.com/espressif/esp-rainmaker  
  Cloud-connected SDK with OTA, provisioning, and phone app integration; free tier.

- **LoRaMac-node** — https://github.com/Lora-net/LoRaMac-node  
  Free reference LoRaWAN MAC implementation for SX126x/SX127x and STM32.

- **Semtech SX126x Drivers (Free)** — https://github.com/Lora-net/sx126x_driver  
  Free HAL drivers for LoRa transceivers.

- **Adafruit BusIO** — https://github.com/adafruit/Adafruit_BusIO  
  Free I2C/SPI/UART abstraction for Arduino/ESP32/RP2040/STM32.

- **OpenMV ML Firmware** — https://github.com/openmv/openmv  
  Free MicroPython firmware for vision + ML on Cortex-M7 boards.

- **MicroPython** — https://micropython.org  
  Free Python interpreter for microcontrollers like ESP32, RP2040, STM32, NRF.

- **CircuitPython** — https://circuitpython.org  
  Adafruit fork of MicroPython with thousands of free hardware libraries.

- **TinyGo** — https://tinygo.org  
  Free Go compiler for microcontrollers (nRF, STM32, RP2040, ESP32).

- **Rust Embedded HAL** — https://github.com/rust-embedded  
  Free HAL, drivers, RTIC scheduler and tooling for safely writing firmware in Rust.

- **RTIC (Real-Time Interrupt-Driven Concurrency)** — https://rtic.rs  
  Free Rust real-time framework for Cortex-M with zero-cost abstractions.

- **Zig Embedded Tooling** — https://github.com/ZigEmbedded  
  Free toolchains and drivers for Zig-language MCU development.

- **pico-sdk-python / MicroPython Type Hints** — https://github.com/raspberrypi  
  Free Python tools for Pico hardware and debugging.

- **OpenOCD** — http://openocd.org  
  Free JTAG/SWD server used by GDB, PlatformIO, Zephyr.

- **pyOCD** — https://github.com/pyocd/pyOCD  
  Free SWD debugger for ARM Cortex-M; CMSIS-DAP probes; flash & RAM debugging.

- **Black Magic Probe (Firmware + Host Tools)** — https://github.com/blackmagic-debug/blackmagic  
  Open-source JTAG/SWD debugger firmware and GDB server.

- **Segger J-Link Edu License (Free)** — https://www.segger.com/products/debug-probes/j-link/models/j-link-edu/  
  Free for personal/non-commercial embedded debugging with J-Link hardware.

- **OpenBLT Bootloader** — https://github.com/feaser/openblt  
  Free open-source bootloader for STM32, NXP, TI, Atmel; supports CAN/USB/UART/SD.

- **MCUBoot + imgtool** — https://github.com/mcu-tools/mcuboot  
  Free secure image signing, OTA, rollback, versioning for Cortex-M.

- **LittleFS** — https://github.com/littlefs-project/littlefs  
  Free fault-tolerant filesystem with wear-leveling for SPI/QSPI flash.

- **FatFS** — http://elm-chan.org/fsw/ff/00index_e.html  
  Free FAT filesystem for MCUs with SD/QSPI storage.

- **LVGL** — https://lvgl.io  
  Free graphics library with UI widgets, animations, input, EV-charts for displays.

- **uGFX (Free License for Non-Commercial)** — https://ugfx.io  
  Small foot-print graphics library for MCUs; free hobby license.

- **uLisp** — http://www.ulisp.com  
  Lisp interpreter for microcontrollers; free and open.

### 9. RTOS / Operating Systems

- **FreeRTOS** — https://www.freertos.org  
  Industry-standard real-time kernel for almost every MCU (ARM, RISC-V, ESP32, AVR). 100% free under MIT with TCP/IP, MQTT, OTA, TLS add-ons.

- **Zephyr RTOS** — https://zephyrproject.org  
  Modern, Linux-style RTOS for ARM, RISC-V, ARC, x86, ESP32, NRF. Open-source, secure boot, BLE, mesh, USB, networking stacks included.

- **Apache Mynewt** — https://mynewt.apache.org  
  Modular RTOS for BLE devices, secure boot, and OTA firmware updates. 100% free & open-source.

- **RT-Thread** — https://www.rt-thread.io  
  POSIX-like RTOS for Cortex-M, RISC-V, Xtensa, with GUI, networking, filesystem. Open-source; commercial extensions optional.

- **Mbed OS** — https://os.mbed.com  
  ARM Cortex-M RTOS with TLS, Wi-Fi, BLE, TCP/IP, OTA, cloud clients. Free & open-source.

- **RIOT OS** — https://riot-os.org  
  RTOS for low-power IoT MCUs (ARM, AVR, MSP430, ESP32). Built-in 6LoWPAN, CoAP, RPL networking. Fully open-source.

- **NuttX (Apache)** — https://nuttx.apache.org  
  POSIX-compliant RTOS powering many real products (including some drones). Free, open-source, large driver ecosystem.

- **ThreadX / Azure RTOS** — https://github.com/azure-rtos  
  Previously commercial, now free/open on STM32, NXP, Renesas. Includes FileX, NetX, USBX & secure boot.

- **ChibiOS / NIL** — http://www.chibios.org  
  Free light-weight RTOS + HAL for STM32, Kinetis, NRF, AVR. Hobby license free, full source open.

- **µC/OS-II / µC/OS-III (Micrium)** — https://github.com/weston-embedded/uCOS-III  
  Classic commercial RTOS with now-free source code under GPL for many MCUs.

- **TinyUSB + TinyUF2 Boot RTOS** — https://github.com/hathach/tinyusb  
  Not a full OS, but lightweight RTOS-friendly USB stack widely used with FreeRTOS/Zephyr.

- **VxWorks 653 Eval / Free Trial** — https://www.windriver.com/products/vxworks  
  Commercial RTOS, but free trial useful for learning safety-critical RTOS concepts.

- **Contiki-NG** — https://github.com/contiki-ng/contiki-ng  
  IPv6, 6LowPAN, RPL RTOS for ultra-low-power devices. 100% open-source, great for wireless sensing networks.

- **TinyOS** — https://github.com/tinyos  
  Free OS for low-power sensor nodes with active academic community.

- **Miosix RTOS** — http://miosix.org  
  Free, open RTOS for Cortex-M MCUs with POSIX threads, FAT, C++17 support.

- **SafeRTOS (Eval)** — https://www.highintegritysystems.com/safertos  
  Commercial safety-certified RTOS, but free evaluation version for experimentation.

- **RTEMS** — https://www.rtems.org  
  FAA-grade real-time OS for aerospace/industrial applications. Fully open-source.

- **NutOS / Ethernut** — http://www.ethernut.de/en/  
  Free RTOS and networking stack for ARM/AVR devices, Ethernet-ready.

- **embOS (emEval)** — https://www.segger.com/products/rtos/embos/  
  Commercial RTOS, but free “evaluation kits” available for education and prototyping.

- **Atomthreads** — http://atomthreads.com  
  Simple free RTOS for small MCUs (ARM, AVR, PIC). Open-source.

- **FemtoOS** — http://www.femtoos.org  
  Extremely small open-source RTOS for 8-bit MCUs (AVR).

- **PicoOS** — https://sourceforge.net/projects/picoos/  
  Tiny RTOS for 8/16-bit MCUs. Free & open-source.

- **RIOT Rust Bindings** — https://github.com/RIOT-OS/rust-riotbuild  
  Free Rust toolchain support for RIOT-OS on MCUs.

- **FreeRTOS-MPU** — https://www.freertos.org/RTOS-MPU.html  
  Memory-protected RTOS variant for safety-critical MCUs. Free under MIT.

- **Tock OS** — https://www.tockos.org  
  Open-source secure RTOS for Cortex-M and RISC-V with kernel/user isolation.

- **LiteOS (Huawei Open-Source)** — https://github.com/LiteOS  
  Open-source IoT OS for ARM and RISC-V with networking and sensor framework.

- **Zephyr MCUboot Integration** — https://github.com/mcu-tools/mcuboot  
  Free secure bootloader integrated with Zephyr for OTA, rollback, signatures.

- **Amazon FreeRTOS+TLS+OTA** — https://github.com/aws/amazon-freertos  
  Free networking, OTA and cloud SDK extension on top of FreeRTOS.

### 10. Drivers, Stacks & Middleware
#### 10A. Connectivity & Networking Stacks

- **LWIP (Lightweight IP)** — https://savannah.nongnu.org/projects/lwip  
  Free TCP/IP stack for MCUs with sockets, DHCP, DNS, PPP. Used in ESP32, STM32, TI, NXP, etc.

- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls  
  Free TLS, crypto, X.509 library used widely in MCUs and IoT devices.

- **wolfSSL / wolfMQTT (Free Tier)** — https://www.wolfssl.com  
  Free TLS and MQTT libraries for non-commercial/hobby use; very small footprint.

- **tinycrypt** — https://github.com/intel/tinycrypt  
  Ultra-small cryptography library for ARM Cortex-M and 8-bit devices.

- **micro-ecc** — https://github.com/kmackay/micro-ecc  
  Tiny elliptic-curve crypto library used in BLE stacks and secure boot.

- **Mongoose Embedded Networking Library (Free for FOSS)** — https://mongoose.ws  
  Free HTTP/MQTT/WebSocket/CoAP stack for MCUs under GPL/community license.

- **nanopb** — https://github.com/nanopb/nanopb  
  Small Protocol Buffers implementation for Cortex-M. Free and open-source.

- **CoAP (libcoap)** — https://libcoap.net  
  Free CoAP protocol implementation for embedded Linux and MCUs.

- **libmodbus** — https://libmodbus.org  
  Free Modbus RTU/TCP stack used in industrial MCUs and gateways.

- **can-utils / SocketCAN** — https://github.com/linux-can  
  Free CAN bus drivers, analysis tools, and libraries for embedded Linux and MCUs.

- **ESP-MQTT** — https://github.com/espressif/esp-mqtt  
  MQTT client library optimized for ESP32. Free with reconnection, TLS, QoS, and LWT.

- **paho-mqtt (Embedded C)** — https://github.com/eclipse/paho.mqtt.embedded-c  
  Free MQTT client libraries for small microcontrollers.

- **Wakaama (LwM2M)** — https://github.com/eclipse/wakaama  
  Lightweight M2M device management protocol for constrained devices.

- **AIoT CoAP / LwM2M Client SDK** — https://github.com/eclipse/leshan  
  Free CoAP + LwM2M stack for device provisioning & telemetry.

- **LoRaMac-node** — https://github.com/Lora-net/LoRaMac-node  
  Reference LoRaWAN stack supporting Class A/B/C, ADR, and secure join.

- **liblora** — https://github.com/sandeepmistry/arduino-LoRa  
  Free LoRa driver for SX127x-based boards (Arduino/ESP32).

- **6LoWPAN Stack for RIOT/Contiki-NG** — https://github.com/RIOT-OS  
  Free IPv6 over low-power wireless mesh networks.

- **OpenThread** — https://openthread.io  
  Free Thread networking stack from Google; used in Matter IoT devices.

- **ESP-Thread & ESP-Zigbee SDKs** — https://github.com/espressif/esp-thread  
  Free Zigbee & Thread support for ESP32-H2/H4.

- **Zigbee EmberZNet SDK (Silicon Labs - Free)** — https://www.silabs.com/developers  
  Free Zigbee + Thread stack with Simplicity Studio (device required).

- **OpenMQTTGateway** — https://github.com/1technophile/OpenMQTTGateway  
  Free library that bridges BLE, IR, RF433, LoRa, and sensors to MQTT.

- **nRF5 SDK for Thread & Zigbee** — https://www.nordicsemi.com  
  Free Thread, Zigbee, BLE-Mesh, 802.15.4 stacks for Nordic MCUs.

- **BLE Mesh (ESP-IDF & Zephyr)** — https://github.com/espressif/esp-idf  
  Free BLE-Mesh with provisioning, OTA, and low-power features.

- **aws-iot-device-sdk-c** — https://github.com/aws/aws-iot-device-sdk-embedded-C  
  Free MQTT/TLS/OTA libraries for constrained devices.

- **azure-iot-sdk-c** — https://github.com/Azure/azure-iot-sdk-c  
  Free MQTT/AMQP/HTTP clients with provisioning and device twin.

- **ThingsBoard C SDK** — https://github.com/thingsboard/thingsboard-c-client-sdk  
  Free MQTT/HTTP client for dashboards, OTA, and telemetry.

- **TinyTCP/IP (uIP fork)** — http://www.sics.se/~adam/uip/  
  Minimal TCP/IP stack for <10 KB RAM devices, still used in many bare-metal designs.

- **nanostack (ARM)** — https://os.mbed.com/docs/mbed-os-latest/apis/nanostack.html  
  Free 6LoWPAN stack for Mbed OS devices.

- **Eclipse Cyclone DDS** — https://github.com/eclipse-cyclonedds/cyclonedds  
  Free DDS stack for robotics, autonomous systems and industrial IoT.

- **uMQTTClient (Arduino/ESP)** — https://github.com/knolleary/pubsubclient  
  Free minimal MQTT client for AVR/ESP in <10 KB Flash.

- **libesphttpd** — https://github.com/Spritetm/libesphttpd  
  Free tiny HTTP server for embedded devices.

### 10B. USB, HID, Audio & Video Stacks

- **TinyUSB** — https://github.com/hathach/tinyusb  
  Free USB Device stack for ESP32-S2/S3, RP2040, STM32, NRF, and more. Supports CDC, HID, MSC, MIDI, WebUSB.

- **LwUSB / USB Device Core (STM32 HAL)** — https://github.com/STMicroelectronics  
  Free USB Device + Host stack integrated with STM32Cube HAL libraries.

- **CHIBIOS USB HAL** — http://www.chibios.org  
  Free USB stack with CDC/HID/Mass Storage support for Cortex-M MCUs using ChibiOS.

- **libopencm3 USB** — https://libopencm3.org/wiki/USB  
  Free low-level USB stack for ARM Cortex-M (STM32, LPC, Kinetis, etc.).

- **LUFA (USB for AVR)** — https://github.com/abcminiuser/lufa  
  Free/open-source USB stack for ATmega32U4/AT90USB devices; supports HID, CDC, storage, MIDI.

- **ESP-IDF USB Host/Device Stack** — https://github.com/espressif/esp-idf  
  Free USB core for ESP32-S2/S3 with CDC, MSC, HID, and WebUSB examples.

- **NuttX USB Device/Host** — https://nuttx.apache.org  
  Free POSIX RTOS with USB device & host, HID, networking, audio class support.

- **USBX (Azure RTOS)** — https://github.com/azure-rtos/usbx  
  Free USB stack with HID, CDC, Mass Storage, Audio class; runs on STM32, Renesas, NXP.

- **uac2-uac1 USB Audio Class Examples** — https://github.com/ARMmbed  
  Free USB audio class demos for ARM Cortex-M devices.

- **ESP-ADF (Audio Development Framework)** — https://github.com/espressif/esp-adf  
  Free audio framework for ESP32 with I2S codecs, MP3/AAC decoding, echo cancellation, and VoIP pipelines.

- **STM32 Audio Framework (Free)** — https://www.st.com/en/embedded-software/x-cube-audio.html  
  Free STM32 audio software: MP3 decode, AEC, beamforming, noise reduction (license-free binary libs).

- **OpenMAX IL (Raspberry Pi)** — https://github.com/raspberrypi/firmware/tree/master/hardfp/opt/vc  
  Free hardware-accelerated audio/video codecs for Pi SoCs.

- **GStreamer (Embedded Linux)** — https://gstreamer.freedesktop.org  
  Free streaming/audio/video pipeline used in embedded Linux boards.

- **libcamera (Pi & Linux)** — https://libcamera.org  
  Free open-source camera library for embedded Linux and Pi.

- **ArduCam Open Camera Drivers** — https://github.com/ArduCAM  
  Free drivers for SPI/I2C camera modules for ESP32, STM32, RP2040 and Arduino.

- **OpenCV (MCU + Embedded Linux Support)** — https://opencv.org  
  Free computer vision library; runs on embedded Linux and many SoCs.

- **LVGL Video / Display HAL** — https://github.com/lvgl/lvgl  
  Free embedded GUI engine with display drivers, buffering, input and animations.

- **uGFX (Free non-commercial)** — https://ugfx.io  
  Small footprint embedded graphics and display library; free hobby license.

- **libdrm + kms for Embedded GPUs** — https://dri.freedesktop.org  
  Free graphics stack for embedded Linux SoCs with display output.

- **OpenH264** — https://github.com/cisco/openh264  
  Free H.264 codec used in embedded VoIP/video devices (free binary distribution allowed).

- **WebRTC Native Stack (Free)** — https://webrtc.org  
  Free real-time audio/video streaming library for embedded Linux devices.

- **Opus Codec (BSD)** — https://opus-codec.org  
  Free high-quality compressed audio codec for MCUs and embedded VOIP.

- **Speex DSP** — https://github.com/xiph/speexdsp  
  Free acoustic echo cancellation, AGC and noise suppression for microphones.

- **minimp3 / tiny-audio-codec** — https://github.com/lieff/minimp3  
  Tiny free MP3 decoder for MCUs.

### 10C. Sensor, Display & Peripheral Driver Libraries

- **Adafruit Sensor Libraries (Free/Open-Source)** — https://github.com/adafruit  
  Huge free collection of I2C/SPI sensor drivers for IMUs, gas sensors, ADCs, current sensors, temperature, displays, GPS, and more.

- **Adafruit BusIO** — https://github.com/adafruit/Adafruit_BusIO  
  Free unified I2C, SPI, UART abstraction layer used by hundreds of drivers.

- **SparkFun Sensor Libraries** — https://github.com/sparkfun  
  Free open-source drivers for IMUs, GNSS, power monitors, distance, RF, environment sensors.

- **Bosch SensorTech Drivers (BME/BMP/BMI/BHA)** — https://github.com/BoschSensortec  
  Free official drivers for the most common IMUs, pressure, gas sensors used in wearables and IoT.

- **ST Sensor Drivers (LIS3, LPS, HTS, VL53L0X ToF)** — https://github.com/STMicroelectronics  
  Free HAL drivers for accelerometer/gyro, pressure, humidity and ToF sensors.

- **InvenSense/TDK Motion Drivers** — https://invensense.tdk.com/developers  
  Free IMU drivers for MPU-6050/9250/6500 and newer smart motion processors.

- **Nordic nRF Sensor Drivers** — https://github.com/NordicSemiconductor  
  Free sensor abstraction for BLE/Thread MCUs.

- **ESP-IDF Sensor Examples** — https://github.com/espressif/esp-idf  
  Free drivers/examples for ADC, DAC, capacitive touch, I2C, SPI, Hall sensor, temperature sensors.

- **libiio (Industrial IO)** — https://github.com/analogdevicesinc/libiio  
  Free IIO interface for ADC/DAC/sensor hardware from Analog Devices — widely used in SDR and instrumentation.

- **LVGL Display Drivers** — https://github.com/lvgl/lvgl  
  Free embedded display library with drivers for TFT, OLED, LCD, ePaper, touch controllers, GUI widgets.

- **TFT_eSPI** — https://github.com/Bodmer/TFT_eSPI  
  Free high-performance display driver for ESP32/ESP8266 with SPI TFT controller support.

- **U8g2** — https://github.com/olikraus/u8g2  
  Free display library for small OLEDs, LCDs, VFDs; works on Arduino/ESP/AVR/ST.

- **GxEPD2** — https://github.com/ZinggJM/GxEPD2  
  Free e-paper display driver for ESP and Arduino boards.

- **ESP32 Camera Drivers / ESP32-CAM** — https://github.com/espressif/esp32-camera  
  Free camera support for OV2640, OV3660; JPEG capture on ESP32.

- **ArduCam Open Drivers** — https://github.com/ArduCAM  
  Free camera drivers for SPI/I2C camera modules for ESP32, RP2040, STM32.

- **Adafruit GFX** — https://github.com/adafruit/Adafruit-GFX-Library  
  Free graphics core for displays — text, bitmaps, shapes; works with OLED/TFT/ePaper.

- **SSD1306 / SH1106 OLED Drivers** — https://github.com/ThingPulse/esp8266-oled-ssd1306  
  Free OLED drivers for ESP8266/ESP32 with I2C/SPI.

- **ADS1115 / ADC Drivers** — https://github.com/adafruit/Adafruit_ADS1X15  
  Free ADC drivers for ADS1105/ADS1115 high-precision I2C converters.

- **INA219 / INA226 Power Monitor Drivers** — https://github.com/adafruit/Adafruit_INA219  
  Free drivers for shunt-based current/power monitoring ICs.

- **MAX17043/46 Fuel Gauge Drivers** — https://github.com/adafruit/Adafruit_MAX1704X  
  Free drivers for Li-ion SoC estimation chips.

- **BQ24295 / Li-ion Charger Drivers** — https://github.com/jeremyjh/BQ24295  
  Free battery charger driver for ESP32/Arduino projects.

- **VL53L0X / VL53L1X Time-of-Flight Drivers** — https://github.com/pololu/vl53l0x-arduino  
  Free distance ToF drivers widely used in robotics and IoT.

- **MPU6050 / DMP Drivers** — https://github.com/ElectronicCats/mpu6050  
  Free IMU drivers with DMP motion processing.

- **BNO055 & BNO080 Fusion Libraries** — https://github.com/adafruit/Adafruit_BNO055  
  Free sensor fusion drivers for orientation/IMU modules.

- **HX711 Load Cell ADC Drivers** — https://github.com/bogde/HX711  
  Free load-cell ADC driver — widely used in scales and instrumentation.

- **PN532 NFC/RFID Drivers** — https://github.com/adafruit/Adafruit-PN532  
  Free drivers for NFC, Mifare, RFID reading and card emulation.

- **RC522 RFID Drivers** — https://github.com/miguelbalboa/rfid  
  Free MIFARE reader/writer driver for Arduino/ESP.

- **WS2812 / NeoPixel LED Drivers** — https://github.com/adafruit/Adafruit_NeoPixel  
  Free control library for individually addressable RGB LEDs.

- **FastLED** — https://github.com/FastLED/FastLED  
  Free high-performance LED driver and color animation library.

- **Motor/Encoder Drivers (A4988, DRV8825, TMC)** — https://github.com/teemuatlut/TMCStepper  
  Free stepper driver library for TMC2130/2208/2209/2660/5160.

- **SimpleFOC Drivers** — https://github.com/simplefoc  
  Free BLDC Field-Oriented Control drivers for robotics and motion systems.

- **Servo, ESC, PWM Drivers (ESP/AVR/STM)** — https://github.com/arduino-libraries/Servo  
  Free servo/ESC driver library for robotics, drones, RC.

- **INA260 Power Monitor Drivers** — https://github.com/adafruit/Adafruit_INA260  
  Free precision current/power measurement driver.

- **OneWire & DS18B20 Temp Sensor** — https://github.com/PaulStoffregen/OneWire  
  Free OneWire bus and DS18B20 sensor drivers.

- **DHT11/DHT22 Temp/Humidity Drivers** — https://github.com/adafruit/DHT-sensor-library  
  Free temperature/humidity sensor drivers for IoT.

### 10D. File Systems, Storage & Memory Middleware

- **LittleFS** — https://github.com/littlefs-project/littlefs  
  Free fault-tolerant filesystem for NOR flash and SPI/QSPI storage; power-loss safe, wear-levelling, very small footprint.

- **FatFS** — http://elm-chan.org/fsw/ff/00index_e.html  
  Free FAT filesystem for SD/QSPI with long filename support; widely used in STM32, ESP32, AVR, PIC.

- **SPIFFS** — https://github.com/pellepl/spiffs  
  Free tiny filesystem for SPI flash; small RAM usage; used in many ESP8266/ESP32 designs.

- **ext2/3/4 on Embedded Linux** — https://www.kernel.org  
  Free Linux filesystems used on SBCs (Raspberry Pi, BeagleBone, i.MX boards).

- **YAFFS2** — https://yaffs.net  
  Free NAND flash filesystem for embedded Linux and RTOS; power-loss safe.

- **UBIFS** — https://www.kernel.org/doc/Documentation/filesystems/ubifs.txt  
  Free filesystem for raw NAND flash with wear-levelling and compression.

- **JFFS2** — https://www.sourceware.org/jffs2/  
  Free journaling filesystem for NOR/NAND storage on embedded Linux.

- **Mbed LittleFileSystem** — https://os.mbed.com/docs/mbed-os/latest/apis/littlefilesystem.html  
  Free flash-friendly FS for Mbed OS devices.

- **Zephyr File System Layer** — https://docs.zephyrproject.org/latest/services/file_system  
  Free VFS layer supporting FATFS, LittleFS, NVS, and RAM FS, under Zephyr RTOS.

- **ESP-IDF VFS & Partition Manager** — https://github.com/espressif/esp-idf  
  Free virtual filesystem layer for SPIFFS, FATFS, LittleFS, wear-levelling, OTA partitions.

- **Adafruit FRAM / EEPROM Drivers** — https://github.com/adafruit  
  Free drivers for I2C/SPI FRAM/EEPROM/NVRAM storage support.

- **I2C EEPROM Library (24xx Series)** — https://github.com/RobTillaart/EEPROM  
  Free library for 24LCxx/AT24Cxx EEPROM chips.

- **SD Library (Arduino/ESP)** — https://github.com/arduino-libraries/SD  
  Free SD card read/write, FAT filesystem support.

- **SDFat (High-Performance SD Library)** — https://github.com/greiman/SdFat  
  Free fast FAT filesystem for SD/QSPI; lower RAM use than default SD libs.

- **NVS Flash Storage (ESP32)** — https://github.com/espressif/esp-idf  
  Free key-value storage for configuration/calibration data.

- **Zephyr NVS / NFFS** — https://docs.zephyrproject.org/latest/services/storage/nvs  
  Free non-volatile storage for configuration and telemetry.

- **UBoot Bootloader / FW Images** — https://source.denx.de/u-boot/u-boot  
  Free embedded bootloader for ARM/RISC-V with flash filesystems and secure boot support.

- **MCUBoot + imgtool** — https://github.com/mcu-tools/mcuboot  
  Free secure firmware image format, signing, rollback, versioning.

- **OpenBLT Bootloader** — https://github.com/feaser/openblt  
  Free bootloader with SD/USB/CAN/UART firmware update methods.

- **libopencm3 Flash Drivers** — https://libopencm3.org  
  Free drivers for flash erase/write operations on ARM Cortex-M.

- **Linux MTD (Memory Technology Device)** — https://www.kernel.org/doc/html/latest/driver-api/mtd  
  Free raw flash driver layer for NAND/NOR on embedded Linux SoCs.

- **dm-crypt + LUKS (Embedded Linux Encryption)** — https://gitlab.com/cryptsetup/cryptsetup  
  Free full-disk encryption for embedded Linux devices.

- **SquashFS** — https://github.com/plougher/squashfs-tools  
  Free compressed read-only filesystem for firmware rootfs images.

- **romfs** — https://romfs.sourceforge.net  
  Free tiny read-only filesystem for MCUs with extremely small storage.

- **FRAM Wear-Leveling Libraries** — https://github.com/andrealombardi/FRAMWearLeveling  
  Free wear-levelling layer for I2C/SPI FRAM.

- **Zlib / miniz (Compression)** — https://github.com/richgel999/miniz  
  Free tiny compression library for firmware logs & storage.

- **heatshrink** — https://github.com/atomicobject/heatshrink  
  Free lightweight compression for MCUs with <16 KB RAM.

### 10E. DSP, Math, Control & Motor Libraries

- **CMSIS-DSP** — https://github.com/ARM-software/CMSIS-DSP  
  Free optimized DSP library for Cortex-M MCUs: FFT, FIR/IIR filters, PID, matrix/vector math, statistical ops.

- **CMSIS-NN** — https://github.com/ARM-software/CMSIS-NN  
  Free neural-network inference kernels optimized for Cortex-M, used in low-power TinyML deployments.

- **KissFFT** — https://github.com/mborgerding/kissfft  
  Free small-footprint FFT library for MCUs; works on bare-metal and RTOS.

- **FFTS (Fastest Fourier Transform in the South)** — https://github.com/anthonix/ffts  
  Free high-speed FFT implementation for ARM/MIPS-based embedded Linux platforms.

- **pocketfft (NumPy core)** — https://github.com/pyFFTW/pocketfft  
  MIT-licensed FFT used in CPython/NumPy; portable to embedded Linux SBCs.

- **libfixmath** — https://github.com/PetteriAimonen/libfixmath  
  Free fixed-point math library for MCUs without FPU; trig, sqrt, mul/div, Q-format.

- **uGFX Math / Graphics Math Helpers** — https://ugfx.io  
  Free math helper routines for embedded graphics and animations.

- **STM32 Advanced Motor Control SDK** — https://www.st.com/en/embedded-software/stsw-stm32100.html  
  Free FOC, PMSM, BLDC libraries with observers, torque control, startup sequences.

- **SimpleFOC** — https://simplefoc.com  
  Free open-source Field-Oriented Control (FOC) for BLDC & gimbal motors. Arduino/STM32/ESP32 ready.

- **MotorLib (BLDC/PMSM C library)** — https://github.com/MotorLibHQ/MotorLib  
  Free motor-control framework with observers, SVPWM, current loops, tuning helpers.

- **OpenBLDC** — https://github.com/open-bldc  
  Free BLDC motor control firmware and utilities for robotics.

- **spin-torq PID Controls** — https://github.com/thybaud/spin-torq  
  Free PID speed/position control library for brushed/bldc motors.

- **Arduino PID Library** — https://github.com/br3ttb/Arduino-PID-Library  
  Free, widely used PID controller implementation for MCUs.

- **libopencm3 PWM/Timer Drivers** — https://libopencm3.org  
  Free HAL for timers, PPM, PWM, encoders and motor-control on ARM Cortex-M.

- **OpenFOAM (Embedded Linux CFD)** — https://www.openfoam.com  
  Free CFD solver for SBC-based motor/magnetics cooling system simulations.

- **QCustomPlot / Qt Charts (Embedded Linux)** — https://www.qcustomplot.com  
  Free visualization library for real-time DSP plots on SBC GUIs.

- **Eigen C++** — https://eigen.tuxfamily.org  
  Free header-only matrix/vector math for MCU and embedded Linux; widely used in SLAM, control systems.

- **MicroTensor / TinyML DSP kernels** — https://github.com/tensorflow  
  Free optimized signal-processing kernels for ML on microcontrollers.

- **DSPFilters** — https://github.com/vinniefalco/DSPFilters  
  Free C++ IIR/FIR filter library for embedded audio and instrumentation.

- **SpeexDSP** — https://github.com/xiph/speexdsp  
  Free acoustic echo cancellation, AGC, noise suppression for mic/speaker systems.

- **minimp3** — https://github.com/lieff/minimp3  
  Free tiny MP3 decoder for Cortex-M and SBCs; extremely small footprint.

- **libsamplerate (SRC)** — https://github.com/libsndfile/libsamplerate  
  Free high-quality sample-rate conversion for audio processing.

- **ArduinoFFT** — https://github.com/kosme/arduinoFFT  
  Free FFT implementation for Arduino/ESP MCUs.

- **arm_math (CMSIS DSP standalone port)** — https://github.com/kgreenek/arm_math  
  Repackaged CMSIS-DSP for platforms outside STM32/ARM toolchains.

- **tiny-AES-C** — https://github.com/kokke/tiny-AES-c  
  Small AES encryption for sensor data streams, DSP pipelines, and embedded communication.

- **kissSVM / tinyML classifiers** — https://github.com/pmh47/kissSVM  
  Small C/C++ classifiers used in audio and sensor DSP on MCUs.

- **micro-hal FFT/IIR kernels** — https://github.com/microHAL  
  Free signal processing kernels for small Cortex-M GPS/IMU fusion.

### 10F. Compression, Serialization, Logging & Utilities

- **nanopb (Protocol Buffers for MCUs)** — https://github.com/nanopb/nanopb  
  Free tiny Protocol Buffers implementation for Cortex-M and 8-bit MCUs. Extremely low RAM usage.

- **FlatBuffers (Google)** — https://github.com/google/flatbuffers  
  Free zero-copy serialization used in MCU + embedded Linux systems.

- **CBOR (tinycbor)** — https://github.com/intel/tinycbor  
  Free Concise Binary Object Representation parser for constrained devices.

- **cJSON** — https://github.com/DaveGamble/cJSON  
  Free small JSON parser for embedded systems; works on bare-metal and RTOS.

- **frozen** — https://github.com/cesanta/frozen  
  Free tiny JSON parser embedded in Mongoose networking library.

- **miniz** — https://github.com/richgel999/miniz  
  Free single-file DEFLATE/zlib compression for MCUs.

- **heatshrink** — https://github.com/atomicobject/heatshrink  
  Free lightweight streaming compression for microcontrollers with <16KB RAM.

- **liblzf** — http://software.schmorp.de/pkg/liblzf.html  
  Free extremely fast LZ compression used in embedded logging.

- **tiny-AES-C** — https://github.com/kokke/tiny-AES-c  
  Free, small AES implementation for firmware encryption and secure storage.

- **xxHash / CRC32 / CRC16 Libraries** — https://github.com/Cyan4973/xxHash  
  Free checksum and hashing libraries for integrity checks in communication and storage.

- **ringbufferc / Circular Buffer** — https://github.com/wjwwood/ringbuffer  
  Free ring buffers and FIFO utilities for UART and sensor data.

- **Embedded-Printf (Minimal printf)** — https://github.com/mpaland/printf  
  Free tiny printf() replacement for MCUs with small Flash.

- **miniprintf** — https://github.com/cjlano/miniprintf  
  Free micro printf formatter without heavy stdlib.

- **log.c (embedded logger)** — https://github.com/rxi/log.c  
  Free thread-safe logging with levels and color output.

- **plog (embedded logging)** — https://github.com/SergiusTheBest/plog  
  Free header-only C++ logging for MCUs and SBCs.

- **SEGGER RTT (Free for debug)** — https://www.segger.com/products/debug-probes/j-link/technology/about-real-time-transfer/  
  Free real-time debug logging for MCUs when using J-Link and RTT Viewer.

- **Tracealyzer (Free trial)** — https://percepio.com  
  RTOS trace & logging visualization; free license available for small projects/education.

- **ETL – Embedded Template Library** — https://github.com/ETLCPP/etl  
  Free STL-like containers & utilities designed for MCUs without dynamic memory.

- **micro-ecc** — https://github.com/kmackay/micro-ecc  
  Free tiny ECC crypto library used for secure boot, BLE pairing and signing.

- **libsodium (Embedded)** — https://github.com/jedisct1/libsodium  
  Free cryptography library, ports exist for embedded Linux & some MCUs.

- **tinycrc** — https://github.com/tomritt/tinycrc  
  Free lightweight CRC routines for data integrity.

- **kazuhiko-json (tiny JSON parser)** — https://github.com/kazuho/picojson  
  Free single-header JSON parser for firmware.

- **tiny-http-parser** — https://github.com/h2o/picohttpparser  
  Free HTTP parser for small TCP/IP stacks and MCU webservers.

- **fsm-generator** — https://github.com/szafranek/static-fsm  
  Free finite state machine generator for firmware logic.

- **etl.statechart (Hierarchical FSM)** — https://www.etlcpp.com/state-chart.html  
  Free UML-style state machine library for MCUs.

- **cspot – minimal Spotify client** — https://github.com/khenkel/cspot  
  Free embedded client for SBCs with audio streaming.

- **ArduinoJson (Free Tier)** — https://arduinojson.org  
  Free modern JSON builder/parser for embedded systems (limited features in free license).

- **Base64 encoder/decoder (tiny)** — https://github.com/littlstar/b64.c  
  Free tiny Base64 routines for firmware telemetry and OTA images.

- **minIni (Tiny INI Parser)** — https://github.com/compuphase/minini  
  Free configuration parser for small MCUs.

### 11A. IDEs & Code Editors

- **VS Code (Free)** — https://code.visualstudio.com  
  Most popular free editor for embedded development; supports PlatformIO, Cortex-Debug, CMake, Zephyr, ESP-IDF, STM32, Docker, SSH.

- **PlatformIO IDE (Free)** — https://platformio.org  
  Free cross-platform MCU IDE on top of VS Code; project templates, debugging, libraries, device monitor.

- **STM32CubeIDE (Free)** — https://www.st.com/en/development-tools/stm32cubeide.html  
  Free Eclipse-based IDE for STM32 MCUs with peripheral configuration, live debugging, RTOS viewer.

- **Eclipse + CDT (Free)** — https://www.eclipse.org/cdt  
  Classic free IDE for embedded C/C++ development with OpenOCD & GDB integration.

- **Arduino IDE (Free)** — https://www.arduino.cc/en/software  
  Beginner-friendly MCU IDE for AVR, ESP, STM32, RP2040 and more. Free libraries and serial monitor.

- **Espressif VS Code Extension & ESP-IDF IDE (Free)** — https://github.com/espressif/vscode-esp-idf-extension  
  Free, full ESP32 development environment: CMake, flash, debug, device monitor, trace, IDF GUI.

- **Microchip MPLAB X IDE (Free)** — https://www.microchip.com/mplab  
  Free IDE for PIC, AVR, SAM MCUs with simulators, compilers, and debugging.

- **NXP MCUXpresso IDE (Free)** — https://www.nxp.com/mcuxpresso  
  Free IDE for LPC/Kinetis MCUs; FreeRTOS middleware, config tools, USB stacks.

- **Infineon ModusToolbox IDE (Free)** — https://www.infineon.com/modustoolbox  
  Free Eclipse-based IDE for PSoC, AIROC WiFi/BLE, XMC motor control MCUs.

- **Silicon Labs Simplicity Studio (Free)** — https://www.silabs.com/developers  
  Free IDE for EFR32 BLE/Zigbee/Thread/Sub-GHz MCUs with energy profiler and network analyzer.

- **Renesas e² Studio (Free)** — https://www.renesas.com/software-tool/e2studio  
  Free IDE for RX, RA, RL78 MCUs with code generation, debugging, trace, RTOS plugins.

- **Segger Embedded Studio (Free for Non-Commercial)** — https://www.segger.com/products/development-tools/embedded-studio/  
  Free for personal use; professional IDE with RTT, SWO, code analysis, memory insight.

- **Keil MDK (Free Community Edition)** — https://developer.arm.com/Tools%20and%20Software/Keil-MDK  
  Free limited version for ARM Cortex-M, good for learning and evaluation.

- **IAR Embedded Workbench (Free Size-Limited Kickstart)** — https://www.iar.com  
  Free “KickStart” edition for small code size; good learning tool for Cortex-M/AVR.

- **LiteIDE (Free) for TinyGo + Embedded Go** — https://github.com/visualfc/liteide  
  Free IDE for Go-based firmware (TinyGo, embedded Linux).

- **VSCode + Cortex-Debug (Free)** — https://github.com/Marus/cortex-debug  
  Free GDB+OpenOCD/SWD debugging inside VSCode for ARM MCUs.

- **Wokwi Cloud IDE (Free Tier)** — https://wokwi.com  
  Free browser IDE and MCU simulator for Arduino, ESP32, STM32 — compile, simulate, serial monitor.

- **EIDE (Embedded IDE for VS Code)** — https://github.com/github0null/eide  
  Free VS Code plugin for STM32, GD32, ESP, ATmega — project templates, flashing, debugging.

- **Code::Blocks (Free)** — https://www.codeblocks.org  
  Free C/C++ IDE with debug support; works with AVR-GCC, ARM-GCC, SDCC and custom toolchains.

- **Mbed Studio (Free)** — https://os.mbed.com/studio  
  Free IDE for Mbed OS targets with project templates and debug support.

- **Geany + ARM-GCC (Free)** — https://www.geany.org  
  Lightweight IDE for low-power laptops used in embedded learning labs.

- **CLion (Free Student/Edu or Open-Source Projects)** — https://www.jetbrains.com/clion  
  Paid IDE, but **free for students or open-source firmware development**; great for CMake-based embedded builds.

### 11B. Firmware Debugging & Hardware Debug Tools

- **OpenOCD** — http://openocd.org  
  Free JTAG/SWD debug server supporting STM32, ESP32, NRF, RISC-V, NXP, TI and dozens of probes.

- **pyOCD** — https://github.com/pyocd/pyOCD  
  Free SWD debugger for ARM Cortex-M using CMSIS-DAP probes; flash, breakpoint, GDB server.

- **GDB (GNU Debugger)** — https://www.gnu.org/software/gdb  
  Free debugger for ARM, RISC-V, Xtensa, AVR, embedded Linux and FPGA soft-cores.

- **Segger J-Link Software (Free with J-Link EDU)** — https://www.segger.com/downloads/jlink/  
  Free non-commercial debugging: RTT, SWO, flash programming, memory inspection.

- **Black Magic Probe (Open Source)** — https://github.com/blackmagic-debug/blackmagic  
  Free firmware + GDB server built into the probe; no OpenOCD needed.

- **PicoProbe (RP2040 SWD Probe)** — https://github.com/raspberrypi/picoprobe  
  Free SWD debug firmware for Raspberry Pi Pico (turns it into a JTAG/SWD probe).

- **ST-Link Utilities (Free)** — https://www.st.com  
  Free flashing, debugging, memory viewing for STM32 devices.

- **ESP-IDF Monitor & Trace (Free)** — https://github.com/espressif/esp-idf  
  Real-time logging and JTAG debugging for ESP32-S2/S3/C3.

- **MPLAB Snap / PICkit 4 Tools (Free)** — https://www.microchip.com/mplab  
  Free programming & debugging for PIC/AVR/SAM MCUs.

- **EnergyTrace++ (TI — Free)** — https://www.ti.com/tool/ENERGYTRACE  
  Free energy consumption profiling for MSP430 & SimpleLink MCUs.

- **nRF Power Profiler Kit Software (Free)** — https://www.nordicsemi.com  
  Free energy profiler + BLE sniffer tools.

- **sigrok + PulseView** — https://sigrok.org  
  Free logic analyzer + protocol decoder supporting Saleae clones, FX2, FTDI, LA104 etc.

- **Saleae Logic (Free Basic)** — https://www.saleae.com  
  Free logic analyzer software and protocol decode (full features require paid license).

- **UART / SWO / RTT Viewers (Free)** — https://github.com/segger  
  Free real-time logging for debugging without printf slowing firmware.

- **Ghidra Embedded Loader** — https://github.com/NationalSecurityAgency/ghidra  
  Free reverse-engineering suite with ARM/RISC-V/AVR/Xtensa support.

- **Renode (Embedded Simulation)** — https://github.com/antmicro/renode  
  Free complex hardware simulation for STM32, NRF, RISC-V, Zephyr, Linux, allowing full debugging.

- **QEMU (Embedded Targets)** — https://www.qemu.org  
  Free emulator for ARM, RISC-V, MIPS, PPC used for firmware debugging without hardware.

- **Valgrind (SBC/Linux Debugging)** — https://valgrind.org  
  Free memory checking and profiling for embedded Linux targets.

- **perf / strace / gdbserver (Free)** — https://kernel.org  
  Free Linux debug & profiling tools for SBC-based embedded systems.

- **Arm Keil ULINK2/plus Tools (Free Utils)** — https://developer.arm.com  
  Some debug utilities free without full license; useful for cortex-M boards.

### 11C. Reverse Engineering, Disassembly & Protocol Analysis

- **Ghidra** — https://ghidra-sre.org  
  Free disassembler/decompiler for ARM, AVR, RISC-V, MIPS, Xtensa. Professional-grade (NSA open source).

- **radare2 / rizin** — https://github.com/rizinorg/rizin  
  Free reverse engineering toolkit for firmware binaries, ELF, bootloaders, MCUs.

- **binwalk** — https://github.com/ReFirmLabs/binwalk  
  Free firmware extraction, filesystem carving, packed binary analysis.

- **firmware-mod-kit** — https://github.com/rampageX/firmware-mod-kit  
  Free tools to unpack/modify embedded Linux firmware images.

- **ghidra-xtensa / ARM loaders** — https://github.com/ghidraninja/ghidra-xtensa  
  Free plugins to reverse ESP32 and ARM firmware.

- **Hex-Rays IDA Free** — https://hex-rays.com  
  Free limited version of IDA disassembler (32-bit support, educational use).

- **JTAGulator (Open Hardware)** — https://github.com/grandideastudio/jtagulator  
  Open-source tool to find JTAG/SWD pins on unknown hardware.

- **URH – Universal Radio Hacker** — https://github.com/jopohl/urh  
  Free RF reverse-engineering tool for wireless protocols, rolling codes, ASK/FSK.

- **Sigrok + PulseView (Protocol Decode)** — https://sigrok.org  
  Free decoders for I2C, SPI, UART, CAN, 1-Wire, Modbus, I2S, SWD, JTAG and dozens more.

- **LogicAnalyzer Open Firmware (Saleae clones)** — https://sigrok.org/wiki/Supported_hardware  
  Free firmware/software support for low-cost analyzers.

- **Wireshark (Free)** — https://www.wireshark.org  
  Free protocol analyzer for TCP/IP, Ethernet, MQTT, Zigbee, BLE, USB, Modbus, CAN (with ext).

- **BLE Sniffer (nRF Sniffer for BLE)** — https://www.nordicsemi.com  
  Free BLE traffic capture & decode with Wireshark.

- **USBPcap + Wireshark** — https://desowin.org/usbpcap  
  Free USB packet capture and decoding.

- **Aircrack-ng** — https://www.aircrack-ng.org  
  Free Wi-Fi packet analysis and penetration testing for IoT devices.

- **ChipWhisperer (Open Hardware/Software)** — https://chipwhisperer.io  
  Free side-channel analysis tool for hardware crypto testing; open hardware + software.

- **Open Source JTAG Tools** — https://github.com/jeffmer/gas-gdb-swd  
  Free SWD/JTAG scan utilities.

- **Flashrom** — https://github.com/flashrom/flashrom  
  Free firmware flasher for SPI flash chips.

- **OpenOCD TCL Scripting** — http://openocd.org  
  Free scripting interface for automated reverse-engineering and boundary scan.

### 12A. General & Secure Bootloaders

- **MCUboot** — https://github.com/mcu-tools/mcuboot  
  Free, secure, hardware-agnostic bootloader supporting signed images, rollback, fail-safe upgrade, and DFU for Cortex-M, ESP32, and Zephyr RTOS.

- **OpenBLT** — https://github.com/feaser/openblt  
  Free open-source bootloader for STM32, NXP, Renesas, TI, Microchip. Supports UART, CAN, USB, SD, and RS-485 updates.

- **UF2 Bootloader / Drag-and-Drop** — https://github.com/microsoft/uf2  
  Free mass-storage bootloader for RP2040, SAMD21/51, ESP32-S2/S3. Firmware dropped as a `.uf2` file – great for production support.

- **TinyUF2** — https://github.com/adafruit/tinyuf2  
  Free UF2 bootloader for low-flash MCUs used in Adafruit and custom boards.

- **LittleFS-based Bootloaders** — https://github.com/espressif/esp-idf  
  Free power-safe flashing & rollback support using partition tables and wear-levelled flash.

- **STM32 Serial / USB DFU Bootloaders (Open Source Hosts)** — https://github.com/devanlai/dapboot  
  Free DFU class bootloader that turns STM32 into USB DFU device (no programmer needed).

- **libopencm3 Bootloader Examples** — https://github.com/libopencm3/libopencm3-examples  
  Free simple bootloaders for STM32, LPC, Kinetis MCUs.

- **Arduino Caterina Bootloader** — https://github.com/arduino/ArduinoCore-avr  
  Free USB bootloader for Arduino Uno/Leonardo/Micro (ATmega32U4/328).

- **Optiboot** — https://github.com/Optiboot/optiboot  
  Free tiny UART bootloader for AVR (2 KB) used by many Arduino boards.

- **PX4 Bootloader (Drone / UAV)** — https://github.com/PX4/PX4-Bootloader  
  Free multi-target bootloader used by PX4 autopilots, STM32, and drone flight controllers.

- **APBoot / APM Bootloader** — https://github.com/ArduPilot  
  Free UAV bootloader supporting USB, CAN, telemetry-based firmware upgrades.

- **Dual-bank & A/B Bootloaders (examples)** — https://github.com/ARM-software/CMSIS-RTOS  
  Free examples for Cortex-M enabling rollback-safe updates.

- **uC/OS-III Bootloader (Free GPL)** — https://github.com/weston-embedded/uCOS-III  
  GPL bootloader for many Cortex-M MCUs with CRC checks.

### 12B. Vendor Bootloaders & Update Tools

- **STM32 ROM Bootloader (Free)** — https://www.st.com/resource/en/application_note/cd00167594.pdf  
  Every STM32 ships with a factory bootloader supporting UART, USB DFU, CAN, I2C, SPI — no programmer required.

- **STM32CubeProgrammer (Free)** — https://www.st.com/en/development-tools/stm32cubeprog.html  
  Free flashing, CRC verify, secure firmware signing, DFU upgrades.

- **ESP-IDF OTA + Secure Boot + Flash Encryption** — https://github.com/espressif/esp-idf  
  Official ESP32 OTA system with HTTPS verification, A/B rollback, partition tables, encrypted flash.

- **ESP-AT OTA** — https://github.com/espressif/esp-at  
  Free OTA update for ESP modules used as Wi-Fi modems.

- **nRF Secure DFU Bootloader (BLE / USB / Serial)** — https://github.com/NordicSemiconductor/nrf-bootloader  
  Free signed update support over BLE, USB, UART for Nordic nRF52/nRF53 MCUs.

- **nRF OTA DFU PC Tool (Free)** — https://github.com/NordicSemiconductor/pc-nrfutil  
  Free dfu-package creator and flasher.

- **NXP MCUBootUtility (Free)** — https://github.com/JayHeng/NXP-MCUBootUtility  
  Free GUI tool for secure boot image signing/flashing of i.MX RT crossover MCUs.

- **NXP LPC DFU Bootloader** — https://www.nxp.com  
  USB-based DFU bootloader for LPC MCUs, no programmer needed.

- **Microchip USB HID Bootloader** — https://github.com/MicrochipTech  
  Free USB HID bootloader for PIC18/24/32 with GUI loader.

- **Microchip SAM-BA Bootloader** — https://www.microchip.com  
  Free serial/USB bootloader for SAM Cortex-M MCUs.

- **Renesas FSP Secure Boot** — https://github.com/renesas/fsp  
  Free secure boot & firmware update for RA/RX families.

- **TI Uniflash (Free)** — https://www.ti.com/tool/UNIFLASH  
  Free flashing tool for MSP430, SimpleLink Wi-Fi/BLE/Sub-GHz with secure image support.

- **Silicon Labs Gecko Bootloader** — https://www.silabs.com/documents/public/application-notes/an1086-gecko-bootloader.pdf  
  Free secure bootloader for EFR32, supports SPI, UART, USB, Bluetooth OTA.

- **Infineon ModusToolbox Bootloaders** — https://www.infineon.com/modustoolbox  
  Free secure boot & OTA example projects for PSoC and AIROC Wi-Fi/BLE.

- **Raspberry Pi USB Boot (SBC Bootloader)** — https://github.com/raspberrypi/usbboot  
  Free bootloader + image loader for Pi Zero/Compute modules.

- **BeagleBone SPL/U-Boot (Free)** — https://www.beagleboard.org  
  Free bootloaders supporting SD, eMMC, USB, and network boot.

### 12C. Wireless OTA Update Systems

- **ESP-IDF OTA (HTTPS + A/B + rollback)** — https://github.com/espressif/esp-idf  
  First-class OTA for ESP32 over HTTPS, MQTT, webserver, or local network. Secure boot + flash encryption optional.

- **ESP-MQTT OTA Examples** — https://github.com/espressif/esp-mqtt  
  Free MQTT-based update pipeline with chunking and resume.

- **ESP-HTTP-Server OTA** — https://github.com/espressif/esp-idf  
  Free HTTP OTA (upload through webserver) for Wi-Fi products.

- **nRF Secure DFU OTA (BLE)** — https://github.com/NordicSemiconductor/nrf-bootloader  
  BLE-based signed image update system; widely used in wearables and medical IoT.

- **Zephyr MCUboot + BLE OTA** — https://docs.zephyrproject.org  
  Free BLE DFU pipeline integrated into Zephyr for STM32, Nordic, NXP, ESP32.

- **Mbed OS HTTPS OTA** — https://os.mbed.com  
  Free OTA framework for Wi-Fi/LTE connected Cortex-M devices.

- **AWS IoT OTA (Free SDK)** — https://github.com/aws/amazon-freertos  
  Free MQTT/TLS OTA service for FreeRTOS devices; signed images, rollback.

- **Azure IoT OTA (Free SDK)** — https://github.com/Azure/azure-iot-sdk-c  
  Free OTA for Azure-connected embedded devices.

- **LwM2M OTA (Wakaama/Leshan)** — https://github.com/eclipse/wakaama  
  Free IoT device management + firmware update protocol for constrained nodes.

- **LoRaWAN FUOTA (Fragmented Updates)** — https://lora-alliance.org  
  Free reference for LoRaWAN firmware-over-the-air using fragmentation & multicast.

- **ThingsBoard OTA** — https://github.com/thingsboard/thingsboard  
  Free MQTT OTA support for ESP, STM32, Linux gateways.

- **Mongoose Firmware OTA** — https://github.com/cesanta/mongoose  
  Free HTTP/MQTT OTA for STM32, ESP32, ESP8266.

- **Particle Device OS (Free Tier)** — https://github.com/particle-iot  
  Free OTA for Wi-Fi/LTE embedded modules.

- **NanoMQ / Mosquitto OTA examples** — https://mosquitto.org  
  Free MQTT servers that support firmware delivery.

### 12D. Embedded Linux OTA Systems

- **Mender (Free Community Edition)** — https://mender.io  
  Free OTA platform for Linux devices with A/B partitions, delta updates, rollback and fleet management.

- **SWUpdate** — https://sbabic.github.io/swupdate  
  Free embedded Linux OTA framework supporting A/B, compressed firmware, encrypted images.

- **RAUC** — https://rauc.io  
  Free robust A/B update system for Yocto, Buildroot, OpenWRT devices. Signed images and rollback.

- **Balena (Free for small fleets)** — https://balena.io  
  Free tier provides OTA updates, container deployments, dashboards for IoT devices.

- **Hawkbit (Eclipse)** — https://www.eclipse.org/hawkbit  
  Free OTA deployment server for embedded Linux and MCUs via MQTT/HTTP.

- **Debian/Ubuntu OTA (APT + unattended-upgrades)** — https://wiki.debian.org/UnattendedUpgrades  
  Free OTA upgrades for SBCs with rollback via snapshots (btrfs/zfs).

- **OpenWrt Sysupgrade** — https://openwrt.org  
  Free OTA upgrades for Wi-Fi routers & IoT gateways.

- **Rauc + Mender Yocto Integration Layers** — https://github.com/rauc/meta-rauc  
  Free meta-layers for Yocto-based Linux devices.

- **U-Boot FIT & Verified Boot** — https://source.denx.de/u-boot/u-boot  
  Free secure boot + firmware verification for embedded Linux devices.

- **OSTree / libostree** — https://ostreedev.github.io/ostree  
  Free image-versioning system enabling rollback, atomic updates.

### 13. Memory / Flash / Filesystem Utilities

- **LittleFS** — https://github.com/littlefs-project/littlefs  
  Free, power-loss-safe filesystem for NOR flash with wear leveling and very small RAM usage. Used in STM32, ESP32, RP2040, NRF.

- **FatFS** — http://elm-chan.org/fsw/ff/00index_e.html  
  Free FAT/exFAT filesystem for SD/QSPI devices with long filenames and directory caching. Embedded standard.

- **SPIFFS** — https://github.com/pellepl/spiffs  
  Small footprint FS for SPI flash — good for ESP8266/low-RAM MCUs. Wear-levelled, crash-safe.

- **FFat / FATFS over SPI Flash (ESP-IDF)** — https://github.com/espressif/esp-idf  
  Free FAT implementation for QSPI/NAND/SPI flash via wear-levelled partition.

- **UBIFS** — https://www.kernel.org/doc/Documentation/filesystems/ubifs.txt  
  Free Linux filesystem for raw NAND flash with compression, wear-leveling, power-safety.

- **YAFFS2** — https://yaffs.net  
  Free robust filesystem optimized for NAND on embedded Linux and RTOS.

- **JFFS2** — https://www.sourceware.org/jffs2  
  Journaling filesystem for NOR/NAND on embedded Linux SBCs.

- **SquashFS** — https://github.com/plougher/squashfs-tools  
  Free compressed read-only filesystem for firmware images and OTA partitions.

- **romfs** — https://romfs.sourceforge.net  
  Tiny read-only filesystem for extremely small MCUs (fits in a few KB).

- **ext2/ext3/ext4 (Linux)** — https://www.kernel.org  
  Free standard filesystems for SBCs, gateways, routers, embedded Linux.

- **btrfs / zfs (Linux)** — https://github.com/openzfs/zfs  
  Free advanced FS with snapshots and rollback — useful in OTA pipelines.

- **Mbed LittleFileSystem** — https://os.mbed.com/docs/mbed-os/latest/apis/littlefilesystem.html  
  Flash-friendly filesystem for ARM Cortex-M devices.

- **Zephyr File System Layer** — https://docs.zephyrproject.org/latest/services/file_system  
  Supports FATFS, LittleFS, NVS, RAMFS, and flash-backed KV stores. Free and modular.

- **NVS Flash Storage (ESP32)** — https://github.com/espressif/esp-idf  
  Free key-value flash storage for calibration/config data with wear-leveling.

- **STM32 QSPI Flash Driver (Cube HAL)** — https://github.com/STMicroelectronics  
  Free driver templates for NOR/NAND/QSPI with memory-mapped mode and DMA.

- **Nordic Flash Data Storage (FDS)** — https://infocenter.nordicsemi.com  
  Free flash storage with garbage collection, wear-leveling and virtual pages.

- **NXP Flash & NVM Drivers** — https://www.nxp.com/mcuxpresso  
  Free flash/EEPROM emulation drivers for LPC/Kinetis/RT MCUs.

- **Infineon Flash & XMC NVM Drivers** — https://www.infineon.com/modustoolbox  
  Free flash abstraction and Em_EEPROM for PSoC, XMC platforms.

- **Microchip Data EEPROM Emulation** — https://github.com/MicrochipTech  
  Free EEPROM emulation on flash for PIC24, PIC32, dsPIC.

- **FRAM Wear-Levelling Library** — https://github.com/andrealombardi/FRAMWearLeveling  
  Free wear-leveling algorithm for SPI/I2C FRAM chips.

- **24LCxx / AT24Cxx EEPROM Libraries** — https://github.com/RobTillaart/EEPROM  
  Free EEPROM drivers for I2C memory parts.

- **FlashDB** — https://github.com/armink/FlashDB  
  Free lightweight flash database (KV + Time-series) for MCUs.

- **SQLite Embedded (Free)** — https://sqlite.org  
  Free database used on embedded Linux/SBCs for structured storage.

- **Berkeley DB (Embedded Free Edition)** — https://www.oracle.com/database/berkeley-db  
  Free transactional KV store used in storage-critical devices.

- **Flashrom** — https://github.com/flashrom/flashrom  
  Free flashing tool for SPI flash chips (Winbond, GD, Macronix) used in routers, SBCs, laptops.

- **pyspiflash** — https://github.com/kevinoconnor/pyspiflash  
  Free Python utility to read/write SPI flash directly through FTDI/SWD interfaces.

- **STM32CubeProgrammer (Free)** — https://www.st.com/en/development-tools/stm32cubeprog.html  
  Free flash programmer for STM32: read, write, verify, secure image encryption.

- **nRF nrfjprog & nrfutil Flash Tools** — https://www.nordicsemi.com  
  Free flashing/DFU/package tools for NRF52/NRF53.

- **OpenOCD Flash Drivers** — http://openocd.org  
  Free flashing for STM32, ESP32, NRF, GD32, NXP, TI, etc.

- **esptool.py** — https://github.com/espressif/esptool  
  Free ESP32/ESP8266 flashing, partition create/erase, encrypted image support.

- **picotool (RP2040 Flash Manager)** — https://github.com/raspberrypi/picotool  
  Free flashing, UF2 generation, reset, memory read/write.

- **stm32flash** — https://github.com/stm32duino/stm32flash  
  Free serial/USART flashing utility for factory STM32 ROM bootloader.

- **ufsboot / dfu-util** — https://dfu-util.sourceforge.net  
  Free USB DFU flashing tool for STM32, NXP, GD32 and Linux SBCs.

- **SPI Flash File System Benchmarks** — https://github.com/littlefs-project/littlefs  
  Free performance & wear-leveling test harnesses for flash endurance validation.

- **nandwrite / flash_erase / mtd-utils** — https://www.linux-mtd.infradead.org  
  Free raw NAND manipulation tools on embedded Linux.

- **spi-tools (Linux)** — https://github.com/cpb-/spi-tools  
  Free SPI flash read/write, erase, verify directly from Linux shell.

- **crc32, xxHash, SHA256 libs** — https://github.com/Cyan4973/xxHash  
  Free checksum libraries for flash integrity validation.

- **badblockscan & bbt utils** — https://github.com/dangiob/flashbench  
  Free NAND bad-block scanning & benchmarking tools on SBCs.

- **memfault coredump storage (Free Tier)** — https://github.com/memfault/memfault-firmware-sdk  
  Free tools to store MCU crash dumps in flash and upload on restart.

### 14A. UART / I2C / SPI / GPIO Utilities & Drivers

- **libopencm3 Peripheral Drivers** — https://libopencm3.org  
  Free HAL for UART, USART, SPI, I2C, DMA, timers, GPIO on ARM Cortex-M (STM32, LPC, Kinetis, EFM32).

- **STM32 HAL / LL Drivers (Free)** — https://github.com/STMicroelectronics  
  Vendor-supplied free drivers with DMA, interrupt, low-power and multi-slave bus handling.

- **ESP-IDF Drivers** — https://github.com/espressif/esp-idf  
  Free UART, SPI, I2C, I2S, RMT, DMA, GPIO, soft-SPI/I2C, RS485 modes, and bus arbitration.

- **Nordic nrfx Drivers** — https://github.com/NordicSemiconductor/nrfx  
  Free low-level drivers for UART, SPIM, TWIM, PWM, PDM; used in BLE/Thread devices.

- **Arduino Wire / SPI / Serial** — https://www.arduino.cc/en/Reference/Libraries  
  Free, simple buses for AVR / SAMD / ESP / STM32 with huge ecosystem support.

- **mbed HAL** — https://os.mbed.com  
  Free HAL APIs for GPIO, UART, I2C, SPI, I2S and DMA across multiple vendors.

- **ChibiOS HAL** — http://www.chibios.org  
  Free multi-vendor HAL with async DMA transfers, driver callback hooks, threads.

- **pigpio (Raspberry Pi)** — http://abyz.me.uk/rpi/pigpio  
  Free low-latency GPIO, SPI, I2C, servo and timing library on embedded Linux.

- **wiringPi (Pi)** — https://github.com/WiringPi/WiringPi  
  Free GPIO/SPI/I2C library for Raspberry Pi, widely used in SBC demos.

- **Linux spidev + i2c-tools (Free)** — https://www.kernel.org  
  Free command-line tools for scanning buses, reading/writing registers, probing sensors.

- **I2C-Tools (`i2cdetect`, `i2cget`, `i2cset`, `i2cdump`)** — https://github.com/groeck/i2c-tools  
  Free diagnostic suite for embedded Linux systems.

- **spidev-test + spi-tools** — https://github.com/cpb-/spi-tools  
  Free SPI data capture, transfer test, bus validation tools.

- **libgpiod** — https://git.kernel.org/pub/scm/libs/libgpiod/libgpiod.git  
  Free GPIO library replacing sysfs interface on modern Linux kernels.

- **gpiomon / gpioset utilities** — https://git.kernel.org/pub/scm/libs/libgpiod/libgpiod.git  
  Free GPIO testing and edge monitoring on Linux SBCs.

- **UART Ring Buffer Libraries** — https://github.com/wjwwood/ringbuffer  
  Free circular buffer utilities for serial data handling on MCUs.

- **SoftUART, SoftI2C, SoftSPI Libraries** — https://github.com/prampec/I2CSoftWire  
  Free bit-banged implementations for boards with limited hardware buses.

- **onewire & DS18B20 Drivers** — https://github.com/PaulStoffregen/OneWire  
  Free 1-Wire bus implementation for thousands of sensors.

- **Modbus RTU over UART libraries** — https://github.com/armink/Modbus-Master-Slave-for-RTU  
  Free Modbus RTU over UART/RS-485.

- **FPGA-based bit-bang analyzers (sigrok)** — https://sigrok.org  
  Free logic & bus decoding tools (UART, SPI, I2C, 1-Wire, I2S, SWD).

### 14B. CAN / LIN / RS-485 / Industrial Buses

- **CANopenNode** — https://github.com/CANopenNode/CANopenNode  
  Free CANopen stack for STM32, ESP32, Linux and many MCUs.

- **SocketCAN (Linux)** — https://github.com/linux-can  
  Free kernel-level CAN stack for embedded Linux SBCs; includes cansend, candump, cangen.

- **can-utils** — https://github.com/linux-can/can-utils  
  Free command-line suite: capture, inject, replay CAN traffic.

- **CANopenStack** — https://github.com/CANopenNode/CANopenNode  
  Free CANopen implementation with SDO/PDO, NMT, sync, emergency, heartbeat.

- **libcanard (CAN + UAVCAN)** — https://github.com/UAVCAN/libcanard  
  Free lightweight UAVCAN v1 implementation for flight controllers and robotics.

- **UAVCAN GUI Tool** — https://github.com/UAVCAN/gui_tool  
  Free diagnostic, flashing and parameter configuration over CAN.

- **LIN Stack (Free)** — https://github.com/johndoe31415/arduino-linbus  
  Free LIN bus implementation for MCUs (entry-level automotive).

- **RS-485 Drivers (Free)** — https://github.com/espressif/esp-idf  
  Free hardware RS-485 with UART, DMA, DE/RE pin control.

- **Modbus RTU Master/Slave (Free)** — https://github.com/armink/Modbus-Master-Slave-for-RTU  
  Free RTU stack for MCU over RS-485.

- **ModbusSniffer (Free)** — https://github.com/0x2A-74/ModbusSniffer  
  Free Python/sniffing tool for RS-485 Modbus traffic.

- **J1939 Stack (Free)** — https://github.com/ttl-j/j1939-arduino  
  Free CAN-based heavy vehicle protocol implementation.

- **ISO-TP (CAN Transport Protocol)** — https://github.com/pylessard/python-can-isotp  
  Free ISO-TP support; used in automotive ECUs.

- **python-can (Free)** — https://github.com/hardbyte/python-can  
  Free CAN interface for Linux, USB-CAN adapters, virtual CAN, SocketCAN.

- **CANable Hardware + Candlelight Firmware (Open Source)** — https://github.com/candle-usb/candleLight_fw  
  Free firmware + USB-CAN adapter compatible with SocketCAN.

- **LIN Sniffer / Analyzers (Free)** — https://sigrok.org/wiki/Decoders  
  Supports CAN, LIN, Modbus, UART, SPI, I2C.

### 14C. Modbus / Industrial Protocol Stacks

- **libmodbus** — https://libmodbus.org  
  Free Modbus TCP/RTU library for Linux/MCU gateways.

- **FreeMODBUS (FreeRTOS)** — https://github.com/armink/FreeModbus_Slave-Master-RTT-RTOS  
  Free RTOS-based Modbus master and slave stack for STM32, ESP32, LPC.

- **Modbus TCP over LWIP examples** — https://github.com/lwip-tcpip/lwip  
  Free reference implementation for Modbus TCP on MCU.

- **OpenPLC (Free)** — https://github.com/thiagoralves/OpenPLC_v3  
  Free IEC-61131 PLC runtime supporting Modbus, DNP3, Ethernet/IP.

- **OpenDNP3 (Free)** — https://github.com/dnp3/opendnp3  
  Free DNP3 implementation for industrial SCADA and energy meters.

- **Free BACnet Stack** — https://github.com/bacnet-stack/bacnet-stack  
  Free BACnet/IP and BACnet/MSTP stack used in BMS and HVAC controllers.

- **OpenZCL / Zigbee cluster library (Free)** — https://github.com/zigpy/zcl  
  Free Zigbee cluster services for gateways and embedded Linux.

- **OpenDLMS / COSEM** — https://www.dlms.com  
  Free smart-meter protocol used in utility metering.

### 14D. I²S / Audio / Sensor-Bus & Timing Utilities

- **TinyI2S (MCU)** — https://github.com/hathach/tinyusb  
  Free I²S drivers part of TinyUSB ecosystem.

- **ESP-IDF I2S Drivers** — https://github.com/espressif/esp-idf  
  Free DMA-based I²S with PDM microphone, DAC, ADC, audio streaming.

- **STM32 I²S HAL / SAI** — https://github.com/STMicroelectronics  
  Free audio interface drivers for STM32 (I²S, TDM, SAI).

- **PDM Microphone Drivers (Free)** — https://github.com/ARMmbed  
  Free drivers to read PDM MEMS microphones on Cortex-M boards.

- **PulseAudio + ALSA (Linux)** — https://www.alsa-project.org  
  Free audio stack for embedded Linux SBCs and gateways.

- **OpenSL ES (Free)** — https://github.com/android/ndk  
  Free embedded audio API for ARM SoCs and audio streaming devices.

- **libiio (Analog Devices)** — https://github.com/analogdevicesinc/libiio  
  Free IIO framework for ADC/DAC sensors and SDR devices.

- **libsigrokdecode** — https://sigrok.org  
  Free logic/protocol decoders for I²S, SPI, UART, CAN, 1-Wire and more.

- **High-Resolution Timer Libraries** — https://github.com/kayman-mk/embedded-time  
  Free timestamping and scheduling utilities for MCU sensor timing.

### 14E. High-Speed & Modern Protocols (MIPI, SLVS-EC, I3C, HyperBus, SDIO...)

- **MIPI Alliance Resources (Free Specifications Overview)** — https://mipi.org/specifications  
  Free public documents and developer resources explaining CSI-2 (cameras), DSI (displays), I3C sensors, A-PHY automotive SerDes.

- **MIPI CSI-2 Linux Kernel Drivers** — https://github.com/torvalds/linux/tree/master/drivers/media  
  Free open-source drivers for Raspberry Pi, NVIDIA Jetson, i.MX, TI, RK3399 platforms using CSI-2 camera sensors.

- **MIPI DSI Panel Drivers (Linux DRM/KMS)** — https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git  
  Free open-source display drivers for DSI LCD/OLED panels.

- **libcamera (CSI-2 abstraction)** — https://libcamera.org  
  Free camera framework for MIPI CSI-2 sensors on embedded Linux.

- **GStreamer + V4L2 (CSI to Video Pipelines)** — https://gstreamer.freedesktop.org  
  Free framework for camera/video capture, encoding, streaming on CSI cameras.

- **SLVS-EC (Sony Sensors) Reference Kernel Drivers** — https://github.com/sony  
  Free Linux drivers and docs for high-speed SLVS-EC image sensors.

- **FPD-Link III (TI) Free Drivers & Tools** — https://www.ti.com/techhub/  
  Free SerDes drivers and reference designs for automotive camera/sensor links.

- **HYPERBUS / HyperFlash / HyperRAM (Cypress/Infineon)** — https://www.infineon.com/hyperram  
  Free open-source drivers and RTOS/LWIP integrations for high-speed external RAM/Flash.

- **SDIO Host Driver (Linux)** — https://www.kernel.org/doc/html/latest/mmc/index.html  
  Free SDIO host stack for Wi-Fi modules (BCM4339, ESP-hosted, RTL).

- **ESP-Hosted (Wi-Fi over SDIO / SPI)** — https://github.com/espressif/esp-hosted  
  Free SDIO/SPI interface making ESP32 an external Wi-Fi/BLE modem.

- **I3C (MIPI) Linux Drivers** — https://github.com/torvalds/linux/tree/master/drivers/i3c  
  Free next-gen sensor bus (replacement for I2C): higher speed, multi-controller, in-band interrupts.

- **I3C Slave/Controller Stacks (Zephyr)** — https://github.com/zephyrproject-rtos/zephyr  
  Free RTOS support for I3C master/slave mode on Cortex-M.

- **AXI / AHB / APB Bus Models (Open-Source)** — https://github.com/alexforencich/verilog-axi  
  Free Verilog/VHDL AXI/AHB/APB bus components for FPGA-based SoCs.

- **Wishbone Bus (OpenCores)** — https://opencores.org  
  Free open-standard SoC interconnect for FPGA/ASIC systems.

- **OpenFPGA HDMI / TMDS Transmitters** — https://github.com/hdl-util/hdmi  
  Free FPGA HDMI video output cores.

- **DisplayPort (DP) Linux DRM/KMS)** — https://git.kernel.org  
  Free drivers for embedded DisplayPort on i.MX, RK3399, TI AM335x.

- **MIPI A-PHY / SerDes Overview** — https://mipi.org/specifications/a-phy  
  Free intro docs for automotive high-speed links (radars, cameras, sensors).

- **ASIL / Automotive Ethernet 100BASE-T1 Drivers** — https://github.com/microsoft/is-kernel  
  Free automotive ethernet PHY drivers on Linux.

- **LVDS Display & Camera Drivers (Linux)** — https://github.com/torvalds/linux/tree/master/drivers/gpu/drm  
  Free LVDS panel and bridge-chip drivers (SN65DSI83, LT8912, SIL9022).

- **FPGA MIPI D-PHY Implementations (OSS/Permissive Licenses)** — https://github.com/xesscorp/mipi-dphy  
  Free FPGA D-PHY RX/TX implementation for CSI-2 experiments.

### 14F. Protocol Simulators & Virtual Buses

- **Renode (Antmicro)** — https://github.com/antmicro/renode  
  Free full-system simulator for ARM, RISC-V, Cortex-M, NRF, STM32, ESP32. Supports UART, SPI, I2C, CAN, Ethernet and virtual sensors. Great for CI and Zephyr development.

- **QEMU (Embedded Targets)** — https://www.qemu.org  
  Free emulator for ARM, RISC-V, MIPS, PowerPC and softcores. Supports virtual UART, I2C, SPI, networking and Linux-based SBCs.

- **Linux Virtual CAN (`vcan`)** — https://github.com/linux-can  
  Free kernel module that simulates CAN bus traffic without hardware. Used with `candump`, `cansend`, `cangen`.

- **python-can (Virtual Bus)** — https://github.com/hardbyte/python-can  
  Free high-level API to simulate CAN frames, replay logs, build PC-based test benches.

- **SocketCAN Virtual Devices** — https://www.kernel.org/doc/Documentation/networking/can.rst  
  Free software-only CAN interface on embedded Linux.

- **CANoe/CANalyzer Alternatives (Free Tier) – cantools** — https://github.com/eerimoq/cantools  
  Free DBC parser and CAN signal encoding/decoding; useful for virtual testing.

- **Open Source LIN Simulator** — https://github.com/johndoe31415/arduino-linbus  
  Free LIN master/slave simulation for MCU testing.

- **SoftUART / SoftI2C / SoftSPI Simulators** — https://github.com/prampec/I2CSoftWire  
  Free bit-bang simulation used to test protocol handling without peripherals.

- **Modbus Simulator (Free)** — https://sourceforge.net/projects/modrssim2/  
  Free Modbus RTU/TCP simulation tool to test PLC/MCU communications.

- **MQTT Virtual Brokers (Mosquitto)** — https://mosquitto.org  
  Free broker for virtual IoT device simulations; supports protocol fuzzing.

- **FakeSPI / FakeI2C Drivers (Zephyr)** — https://github.com/zephyrproject-rtos/zephyr  
  Free virtual device drivers to simulate sensors and flash for CI.

- **GNU Radio + URH (Universal Radio Hacker)** — https://github.com/jopohl/urh  
  Free RF signal analysis and protocol reconstruction — simulate decoding of FSK/ASK/OOK packets.

- **socat (Virtual Serial Ports)** — http://www.dest-unreach.org/socat  
  Free tool to create virtual UART-to-TCP bridges or UART loops for testing firmware that expects a serial device.

- **com0com (Windows Virtual UART Pairs)** — https://sourceforge.net/projects/com0com/  
  Free virtual COM port pairs for Windows — great for Modbus, AT commands, PPP simulations.

- **PySerial Loopback + Virtual TTY** — https://github.com/pyserial/pyserial  
  Free tool to create virtual serial ports (`pty`) on Linux or pseudo COM ports.

- **Docker-based MCU Simulation (Renode/QEMU in CI)** — https://github.com/antmicro/renode-docker  
  Free containers to run firmware simulations inside CI/CD.

- **Virtual I3C/I2C Sensor Mocks** — https://github.com/zephyrproject-rtos/zephyr/tree/master/drivers/sensor  
  Free simulated sensor drivers (IMU, temperature, gas, ToF) for hardware-free testing.

- **FPGA Protocol Simulators (Open-Source)** — https://github.com/alexforencich/verilog-i2c  
  Free Verilog-based bus simulators for I2C, SPI, AXI, Wishbone — used for pre-silicon validation.

- **UART/USB Device Emulation (dummy_hcd, dummy_tty)** — https://github.com/torvalds/linux  
  Free Linux kernel gadget drivers allowing USB device simulation without physical hardware.

- **Virtual Modem / PPP Emulator** — https://linux.die.net/man/8/pppd  
  Free PPP stack simulation for cellular modem firmware testing.

### 15A. Logic Analyzers & Protocol Decoders

- **sigrok + PulseView** — https://sigrok.org  
  Free open-source logic analyzer software with 150+ protocol decoders (SPI, I2C, UART, CAN, LIN, Modbus, I²S, 1-Wire, SWD). Supports low-cost Saleae clones & FX2/FTDI devices.

- **Saleae Logic Software (Free Basic Tier)** — https://www.saleae.com  
  Free tier supports capture, decode and visualization; full features require paid license. Supports USB logic analyzers & protocol decoders.

- **Open Logic Sniffer** — https://github.com/jawi/ols  
  Free open-source logic analyzer firmware + client software for FPGA-based analyzers.

- **fx2lafw (Firmware for Cheap Analyzers)** — https://github.com/sigrokproject/fx2lafw  
  Free firmware that turns FX2-based USB boards into sigrok-compatible logic analyzers.

- **dslogic / DreamSourceLab Tools (Free SW)** — https://www.dreamsourcelab.com  
  Free logic analyzer GUI for DSLogic/DreamSourceLab hardware with high-speed capture.

- **PulseView Protocol Decoders** — https://github.com/sigrokproject/libsigrokdecode  
  Free decoders for hundreds of buses: MIPI D-PHY, I3C (partial), SDIO, HDMI-CEC, UART, I2C, SPI, I²S, CAN, LIN, JTAG, SWD.

- **ScanaStudio (Free Tier)** — https://www.ikalogic.com  
  Free version for IKALOGIC analyzers with many protocol decoders.

- **LA104 Pocket Analyzer (Open Firmware)** — https://github.com/DPTechnics/LA104  
  Free open-source firmware for portable logic analyzer/oscilloscope.

- **Bus Pirate (Open Hardware)** — https://github.com/BusPirate  
  Free multi-protocol debugging tool: UART/SPI/I2C/1-Wire sniffing, bitbang, boundary scan.

- **Glasgow Interface Explorer** — https://github.com/GlasgowEmbedded/glasgow  
  Free open-source programmable hardware for I2C/SPI/UART sniffing & device analysis.

- **OpenBench Logic Sniffer** — https://github.com/GadgetFactory/Logic-Sniffer  
  Open logic analyzer platform with free client software.

- **STM32-based DIY Logic Analyzer (sigrok-supported)** — https://sigrok.org/wiki/Supported_hardware  
  Free firmware to turn BluePill/BlackPill boards into logic analyzers.

- **Arduino Logic Analyzer (Sigrok compatible)** — https://github.com/gillham/logic-analyzer  
  Free firmware turning an Arduino into a small logic analyzer.

- **rtl_433** — https://github.com/merbanan/rtl_433  
  Free decoding of 433 MHz RF protocols using SDR sticks — used for wireless sensor debug.

- **USBlyzer Free (Limited)** — https://www.usblyzer.com  
  Free basic USB sniffing on Windows (limited features in free edition).

- **USBPcap (With Wireshark)** — https://desowin.org/usbpcap  
  Free USB packet capture and protocol decode for USB HID, CDC, MSC, and vendor devices.

- **Beagle USB Protocol Analyzer (Free SW)** — https://www.totalphase.com/products/beagle-usb480/  
  Free software can analyze USB packets from TotalPhase hardware (hardware paid, software free).

- **UM232H/FT232H as logic analyzer** — https://sigrok.org/wiki/Hardware:FTDI  
  Free firmware/software to repurpose FTDI adapters for logic capture.

### 15B. JTAG / SWD / ISP / Programming & Debug Probes

- **OpenOCD** — http://openocd.org  
  Free JTAG/SWD debug & flash server supporting STM32, ESP32, NRF, RISC-V, NXP, TI, GD32, and many probes. Works with GDB, VS Code, PlatformIO.

- **pyOCD** — https://github.com/pyocd/pyOCD  
  Free SWD debug tool for ARM Cortex-M with CMSIS-DAP probes. Flashing, breakpoints, memory view, scripting & Python automation.

- **GDB (GNU Debugger)** — https://www.gnu.org/software/gdb  
  Free debugger for ARM, RISC-V, Xtensa, AVR, embedded Linux and FPGA softcores. Used with OpenOCD and Black Magic Probe.

- **Segger J-Link Software (Free with J-Link EDU)** — https://www.segger.com  
  Free non-commercial debug software including RTT, SWO, flash loader & device memory browser.

- **J-Link EDU Hardware (Low-Cost)** — https://www.segger.com/products/debug-probes/j-link/models/j-link-edu/  
  Affordable JTAG/SWD probe that works with Segger free software for hobby/education.

- **Black Magic Probe (Open Source)** — https://github.com/blackmagic-debug/blackmagic  
  Free open-source firmware and on-board GDB server — no OpenOCD needed. Supports STM32, NRF, ESP32-S2/S3, RP2040 etc.

- **CMSIS-DAP / DAPLink (Open Firmware)** — https://github.com/ARMmbed/DAPLink  
  Free interface firmware turning many boards into drag-and-drop flash & SWD debugger.

- **PicoProbe (RP2040 SWD Probe)** — https://github.com/raspberrypi/picoprobe  
  Free firmware that converts a Raspberry Pi Pico into a SWD debug probe with USB-UART bridge.

- **ST-Link / ST-Link Utility (Free)** — https://www.st.com  
  Free flashing & debugging for STM32 boards, SWD/JTAG access, memory viewer.

- **ESP-PROG (Free Software)** — https://github.com/espressif/esp-idf  
  Free JTAG debugger for ESP32-S2/S3/C3 chips. Works with OpenOCD & VS Code.

- **FTDI FT2232H / FT232H JTAG/SWD (OpenOCD supported)** — https://sigrok.org/wiki/Hardware:FTDI  
  Free drivers to turn low-cost FTDI boards into JTAG/SWD/debug tools.

- **AVRDUDE** — https://github.com/avrdude/avrdude  
  Free ISP flashing tool for AVR (ATmega/ATtiny); supports USBasp/USBtiny, Arduino-as-ISP, and serial bootloaders.

- **pymcuprog (Microchip)** — https://github.com/microchip-pic-avr-tools/pymcuprog  
  Free programming tool for AVR & PIC MCUs via UART/UPDI/EDBG.

- **dfu-util (USB DFU Programmer)** — https://dfu-util.sourceforge.net  
  Free device-firmware-update tool supporting STM32, NXP, GD32 and Linux gadget DFU.

- **ESPTool.py (Free)** — https://github.com/espressif/esptool  
  Free Python flasher for ESP32/ESP8266: erase flash, write binaries, read chip info, secure flash encryption.

- **flashrom** — https://github.com/flashrom/flashrom  
  Free SPI flash programmer for BIOS/routers/IoT devices using FTDI, CH341A, Raspberry Pi GPIO and more.

- **nRF Command Line Tools (Free)** — https://www.nordicsemi.com  
  Free SWD flashing, RTT logging, BLE sniffer integrations for NRF52/NRF53.

- **TI MSP430 Launchpad Debugger (Free)** — https://www.ti.com  
  MSP-FET and eZ-FET debug tools available free with their dev boards.

- **OpenTitan / RISC-V Debug Spec** — https://github.com/lowRISC/opentitan  
  Open-source debug architecture for RISC-V SoCs; example RTL + debug tooling.

- **SWD JTAG Boundary Scan Tools (OpenOCD TCL)** — http://openocd.org  
  Free scripting for pin testing, board bring-up and chain detection.

- **DAPBoot (Open Source USB DFU Bootloader)** — https://github.com/devanlai/dapboot  
  Bootloader + SWD bridge firmware for STM32 boards.

- **Versaloon (Open Source Multi-protocol Tool)** — https://github.com/versaloon  
  Free firmware to make STM32 a USB JTAG, SWD, SPI, I2C, UART bridge.

- **Bus Pirate (Open Hardware)** — https://github.com/BusPirate  
  Multi-protocol serial adapter usable for SPI/I2C/UART sniffing, bit-bang flashing, JTAG boundary scan.

### 15C. Oscilloscopes, Signal Generators & Virtual Instruments

- **sigrok-cli + PulseView (Free)** — https://sigrok.org  
  Free oscilloscope, logic analyzer, protocol decoder, pattern generator and MSO support. Works with many USB scopes (DSLogic, Hantek, etc.).

- **OpenHantek** — https://github.com/OpenHantek/OpenHantek6022  
  Free open-source oscilloscope software for Hantek 6022BE/BL USB scopes.

- **DSLogic / DreamSourceLab (Free Software)** — https://www.dreamsourcelab.com  
  Free Windows/Linux GUI for DSLogic hardware — deep capture, triggers, decoders.

- **OSC482 (Open Source Firmware)** — https://github.com/joaopauloschuler/osc482  
  Free firmware for STM32-based mini USB oscilloscopes.

- **LA104 (Open Firmware Pocket Scope/Analyzer)** — https://github.com/DPTechnics/LA104  
  Free open-source firmware for a handheld oscilloscope, logic analyzer, signal generator.

- **PicoScope 2000/3000 (Free Software Tier)** — https://www.picotech.com  
  Free PC software with basic triggering, FFT, decoding; works without paid license for core features.

- **OpenBench Logic Sniffer (FPGA-based)** — https://github.com/GadgetFactory/Logic-Sniffer  
  Open FPGA platform acting as logic analyzer + simple oscilloscope.

- **SoundCard Oscilloscope (Free)** — https://www.zeitnitz.de/Christian/scope_en  
  Free PC-based oscilloscope using sound card ADC for low-frequency signals. Useful for audio, sensors, PWM, RC filters.

- **Zelscope (Free Trial / Free Basic)** — https://www.zelscope.com  
  Windows sound-card oscilloscope and spectrum analyzer.

- **Visual Analyser (Free)** — http://www.sillanumsoft.org  
  Free Windows PC software for virtual oscilloscope, spectrum analyzer, signal generator, network analyzer.

- **SoX + Audacity (Free)** — https://www.audacityteam.org  
  Audio capture and FFT spectrum analysis on embedded signals through line-in/sound card.

- **GNU Radio (Free)** — https://www.gnuradio.org  
  Free DSP toolkit that can act as oscilloscope, spectrum analyzer, demodulator using SDR hardware.

- **rtl-sdr (Cheap SDR + Free Software)** — https://github.com/steve-m/rtl-sdr  
  $10 USB dongle + free software for wideband RF capture from kHz–1.8GHz; can be used as spectrum analyzer.

- **HackRF One (Open Hardware + Free SW)** — https://github.com/mossmann/hackrf  
  Open-source SDR that works with free tools (GNU Radio, SDR#, URH, sigrok) for RF analysis/signal generation.

- **SDR# / GQRX (Free)** — https://airspy.com/download/  
  Free spectrum analyzer front-end for SDR hardware.

- **AntScope2 + NanoVNA (Free Software)** — https://github.com/NanoVNA-Saver/nanovna-saver  
  Free PC software for NanoVNA — RF network analyzer for 50kHz–3GHz.

- **OpenVNA (Free)** — https://github.com/jankae/OpenVNA  
  Free firmware + software for open-source VNA hardware.

- **ESP32 Oscilloscope Projects** — https://github.com/joaopauloschuler/esp32-oscilloscope  
  Free MCU-based oscilloscope using ESP ADC + web UI.

- **Arduino Oscilloscope (Open Source)** — https://github.com/Otis852/Arduino_Oscilloscope  
  Free Arduino-based oscilloscope for low-frequency educational use.

- **Sigrok-supported USB scopes** — https://sigrok.org/wiki/Supported_hardware  
  List of dozens of USB oscilloscopes supported by free software.

- **WaveForms (Free Basic Tier)** — https://reference.digilentinc.com/waveforms  
  Free PC scope/generator/logic analyzer software for Analog Discovery hardware (with limited features in free tier).

- **OpenWave (OpenHW / Free GUI)** — https://github.com/OpenWave  
  Free open-source oscilloscope GUI for multiple USB scopes.

### 15D. RF / Wireless Analyzers, Sniffers & SDR Tools

- **Wireshark (Free)** — https://www.wireshark.org  
  Free packet analyzer with dissectors for Wi-Fi, BLE, Zigbee, Thread, USB, Modbus, CAN, MQTT. Works with PCAP, USBPcap, nRF Sniffer.

- **USBPcap (Free)** — https://desowin.org/usbpcap  
  Free USB packet capture for Windows; often used to decode BLE dongles, Wi-Fi adapters, 4G/5G LTE dongles.

- **nRF Sniffer for BLE (Free)** — https://www.nordicsemi.com  
  Free BLE packet sniffer with Wireshark integration. Works with nRF52 dongles; captures advertisements, connections, encrypted traffic metadata.

- **Zigbee2MQTT Sniffer Mode (Free)** — https://github.com/Koenkk/zigbee2mqtt  
  Free sniffer mode for Zigbee networks using CC2531/CC2652 modules; helps debug Zigbee devices and networks.

- **ESP32 Wi-Fi Sniffer (Free)** — https://github.com/espressif/esp-idf  
  Free monitor-mode code samples to capture Wi-Fi probe requests, beacons, RSSI, channel activity.

- **ESP32 BLE Sniffer (Free)** — https://github.com/esp32-sniffer/esp32-ble2mqtt  
  Free BLE advertisement scanner, useful for sensor debugging and reverse engineering consumer IoT.

- **ESP32 Zigbee/Thread Packet Capture** — https://github.com/espressif  
  Free packet monitoring for Zigbee and Thread on ESP32-H2 platforms.

- **Aircrack-ng Suite (Free)** — https://www.aircrack-ng.org  
  Free Wi-Fi analysis suite: monitor mode, packet capture, injection, WEP/WPA handshake capture — useful for IoT Wi-Fi debugging and penetration testing.

- **Kismet (Free)** — https://www.kismetwireless.net  
  Free Wi-Fi, BLE, ADS-B, Zigbee, and ISM-band spectrum monitor and intrusion analyzer. Works with SDR and wireless adapters.

- **Universal Radio Hacker (URH)** — https://github.com/jopohl/urh  
  Free RF reverse-engineering tool: demodulation, protocol decoding, symbol mapping, packet analysis for ASK/FSK/OOK, sub-GHz sensors, RF remotes, etc.

- **GNU Radio (Free)** — https://www.gnuradio.org  
  Free DSP framework for SDR signal visualization, demodulation, spectrum analysis and protocol experimentation.

- **rtl_433 (Free)** — https://github.com/merbanan/rtl_433  
  Free sub-GHz RF decoder for smart meters, weather stations, tire sensors, doorbells, environmental sensors. Works with $10 RTL-SDR dongles.

- **rtl_sdr (Free)** — https://osmocom.org/projects/rtl-sdr  
  Free SDR drivers for cheap Realtek dongles (24 MHz – 1.8 GHz); used as wideband receiver + spectrum analyzer.

- **SDR# (Free)** — https://airspy.com/download/  
  Free Windows SDR front-end for spectrum visualization, FM/AM/SSB demod, ADSB, AIS, trunked radio.

- **Gqrx (Free)** — https://gqrx.dk  
  Free SDR GUI running on Linux/macOS with waterfall, FFT and demodulators.

- **HackRF One (Open Hardware + Free Software)** — https://github.com/mossmann/hackrf  
  Open-source 1 MHz–6 GHz SDR transceiver; supported by GNU Radio, SDR#, URH and sigrok.

- **LimeSDR (Open Hardware)** — https://github.com/myriadrf  
  Full-duplex SDR platform with open drivers; used for GSM/LTE/NB-IoT experiments and advanced RF prototyping.

- **Pothos SDR (Free)** — https://github.com/pothosware/pothos  
  Free visual DSP environment for SDR pipelines and RF protocol experiments.

- **ADS-B Aircraft Decoder (dump1090)** — https://github.com/MalcolmRobb/dump1090  
  Free 1090MHz ADS-B decoder compatible with RTL-SDR.

- **AIS Ship Tracking (rtl_ais)** — https://github.com/dgiardini/rtl-ais  
  Free decoder for marine AIS packets using SDR receivers.

- **Spectrum Tools (Free)** — https://github.com/pavhofman/rtl-sdr-scanner  
  Free RF sweeper, waterfall plotter and channel usage scanner with RTL-SDR.

- **OpenSniffer CC2531 (Free)** — https://github.com/attify/firmware  
  Free firmware to turn TI CC2531 USB dongle into a Zigbee packet sniffer.

- **RFIDler (Open Hardware + Free SW)** — https://github.com/ApertureLabsLtd/RFIDler  
  Free RFID research tool supporting LF/HF RFID, cloning and protocol learning.

- **Yard Stick One (Open Hardware)** — https://github.com/atlas0fd00m/yso  
  Free firmware/software for ISM radios (sub-GHz sensing, sniffing, replay) built on TI CC1111.

- **SDRangel (Free)** — https://github.com/f4exb/sdrangel  
  Free cross-platform SDR suite for spectrum analysis and modulation/demodulation testing.

- **Raspberry Pi as RF Analyzer** — https://github.com/raspberrypi/piscope  
  Free GPIO waveform + RF edge timing viewer; works as a simple low-cost analyzer.

### 15E. PCB Test, Fault Analysis, Boundary Scan & ICT Tools

- **FreeDFM (Free)** — https://www.4pcb.com/free-dfm-file-check  
  Free automated DFM/DRC check for Gerbers, detecting shorts, opens, spacing, soldermask issues before manufacturing.

- **LibrePCB DRC/Net Checks (Free)** — https://librepcb.org  
  Free open-source schematic/PCB tool with ERC/DRC rules and net connectivity checks.

- **KiCad Electrical Rules Check (Free)** — https://www.kicad.org  
  Free ERC/DRC verification, unconnected nets highlight, footprint mismatch detection, 3D inspection.

- **OpenOCD Boundary Scan (Free)** — http://openocd.org  
  Free JTAG chain discovery, pin-level control, flash verification and boundary scan on JTAG-enabled chips.

- **UrJTAG (Free)** — http://urjtag.sourceforge.net  
  Free JTAG boundary-scan tester: IDCODE scan, pin toggle, flash programming, BSDL parsing, manufacturing test automation.

- **OpenOCD TCL Scripts (Boundary Tests)** — http://openocd.org  
  Free scripting to automate pin toggle tests, short/open detection, RAM/flash testing during bring-up.

- **Sigrok / PulseView Drive-Strength Testing (Free)** — https://sigrok.org  
  Measures rise/fall, glitching and protocol-level anomalies to detect marginal solder joints or noise issues.

- **OpenOCD “board bring-up” mode** — https://openocd.org/doc/html/  
  Free mode to detect JTAG chain faults, miswired SWD, incorrect pull-ups and swapped pins.

- **JTAGLive Clip (Free Basic Tier)** — https://www.jtag.com/products/jtaglive/  
  Free boundary-scan test for basic connectivity of BGAs, QFNs and high-pin-count ICs (limited features in free license).

- **XJTAG DFT Assistant for KiCad (Free)** — https://www.xjtag.com  
  Free KiCad plugin guiding DFT rules: test access, nets coverage, accessible nodes for in-circuit testing.

- **Boundary-Scan BSDL File Viewers (Free)** — https://github.com/bsdlparser  
  Free BSDL parser to view pin-level JTAG boundary scan capabilities of many ICs.

- **Netlist comparison tools (`netlistcmp`)** — https://github.com/gerbv/gerbv  
  Free tool to compare schematic vs PCB connectivity, detect mismatched pins, swapped nets or missing vias.

- **OpenTestPoint (Free)** — https://opentestpoint.com  
  Free distributed measurement framework allowing remote probing, RF and IO monitoring in IoT testbeds.

- **PCBeizer / Bed-of-nails testers DIY (Free)** — https://github.com  
  Open-source mechanical and PCB projects for pogo-pin test jigs for production testing.

- **ESP-Prog / CMSIS-DAP SWD boundary testing (Free)** — https://github.com/espressif/esp-idf  
  Free SWD/JTAG-based pin testing on ESP32 modules to validate PCB assembly.

- **DMM + SCPI Automation Tools (Python)** — https://github.com/hpssjellis/SCPI  
  Free Python libraries to automate multimeters and power supplies for production test racks.

- **sigrok-based ICT (I2C/SPI/UART test)** — https://sigrok.org/wiki/Supported_protocols  
  Free protocol-level functional test to verify assembled boards without custom firmware.

- **Raspberry Pi GPIO Automated Tester (Free)** — https://github.com/gillham/pitest  
  Free configurable functional tester for assembled PCBs using Pi GPIO + Python.

- **OpenFASOC / Open, source chip-level DFT** — https://github.com/idea-fasoc/OpenFASOC  
  Free IC-level test automation, useful as reference for advanced SoC bring-up.

- **Open-Hardware Flying Probe Testers (DIY)** — https://github.com/topics/flying-probe  
  Free mechanical designs + software for low-cost flying-probe inspection.

- **Open Hardware continuity tester** — https://github.com/pepaslabs/fixture  
  Free fixture/Pogo test setup for validating continuity and shorts in PCBA.

- **KiCad Gerber viewer + GerbView (Free)** — https://kicad.org  
  Free inspection of copper/paste/mask layers and drill hits to find DFM issues.

- **gerbv (Free)** — http://gerbv.geda-project.org  
  Free open-source Gerber & drill viewer supporting net highlight, mismatch detection.

- **pcb2gcode (Free)** — https://github.com/pcb2gcode/pcb2gcode  
  Free tool for generating isolation routing/milling paths and validating board geometry correctness.

- **LogiScope (Free)** — https://github.com/logiscope/  
  Free signal integrity and glitch capture on digital lines for hardware timing debug.

### 16A. Component Search Engines & Cross-Reference Tools

- **Octopart** — https://octopart.com  
  Free global search engine for electronic components with pricing, stock, parametric filters and lifecycle info.

- **Findchips** — https://www.findchips.com  
  Free distributor search, pricing comparison, stock alerts and alternates for ICs, sensors, passives and connectors.

- **SnapEDA** — https://www.snapeda.com  
  Free footprints, symbols and 3D models for millions of components. Supports KiCad, Eagle, Altium, OrCAD.

- **Ultra Librarian (Free Tier)** — https://www.ultralibrarian.com  
  Free downloads of symbols, footprints and STEP models from major manufacturers (limited quantity per month).

- **Digi-Key Part Search** — https://www.digikey.com  
  Free advanced parametric search, cross-reference, lifecycle flags, datasheets, sample ordering and reference designs.

- **Mouser Search** — https://www.mouser.com  
  Free parametric search, environmental compliance, lifecycle, EOL alerts and cross-references.

- **JLCPCB Part Library (Free)** — https://jlcpcb.com/parts  
  Free search of components stocked for low-cost PCBA production with pricing, availability and SMT/JLCPCB compatibility.

- **LCSC (Free)** — https://lcsc.com  
  Free search for low-cost components, especially useful for prototype & high-volume BOM optimization.

- **ComponentSearch (Free)** — https://componentsearchengine.com  
  Free federated search of manufacturer datasheets, footprints and 3D models.

- **PartInfo (Allegro / OrCAD)** — https://www.orcad.com  
  Free searchable library of footprints, 3D models and verified symbols.

- **OEMSecrets** — https://www.oemsecrets.com  
  Free price & stock comparison across global distributors.

- **PartsBox (Free Tier)** — https://partsbox.com  
  Cloud parts database with free search, stock tracking, BOM cost estimation and vendor linking.

- **Z2Data (Free Tier)** — https://z2data.com  
  Free access to risk reports, lifecycle, PCN, compliance and alternates (limited free access).

- **PartCross (Free)** — https://partcross.com  
  Free cross-reference lookup for semiconductors and passives.

- **Nexar (API, Free Tier)** — https://nexar.com  
  Free API access to Octopart part data for automated BOM validation & distributor filtering.

- **SamacSys (PCB Libraries)** — https://www.samacsys.com  
  Free symbols/footprints for KiCad, Altium, Eagle, OrCAD; vendor-verified models for many parts.

- **Open Symbol/Footprint Libraries (KiCad)** — https://github.com/KiCad  
  Free, community-maintained KiCad libraries covering MCUs, connectors, RF parts, power ICs, sensors and passives.

- **Datasheet Archive (Free)** — https://www.datasheetarchive.com  
  Free archive of legacy datasheets and discontinued parts.

- **AllDatasheet (Free)** — https://www.alldatasheet.com  
  Free repository of datasheets, parametric info and EOL component documents.

- **SemiWiki / Community Cross-Reference Lists (Free)** — https://www.semiwiki.com  
  Free discussions and comparisons of alternative ICs and replacements.

- **PassMark IC Search (Free)** — https://www.passmark.com  
  Free database for older CPUs/SoCs and power IC pin-compatibility.

- **3D ContentCentral (Free)** — https://www.3dcontentcentral.com  
  Free 3D CAD models for electronics enclosures, connectors and mechanical parts.

- **ElectroDroid (Free App)** — https://play.google.com/store/apps/details?id=it.android.demi.elettronica  
  Free mobile reference for component pinouts, resistor codes, SMD codes, op-amp pinouts, connectors.

- **EEVblog Forum Component Cross-References** — https://www.eevblog.com/forum  
  Free expert-driven cross-reference suggestions, especially for obsolete parts.

### 16B. Pricing, Distributors & Procurement Portals

- **Digi-Key** — https://www.digikey.in  
  Free part search with real-time pricing, stock, lead time, cut-tape orders and small-MOQ prototyping support worldwide.

- **Mouser Electronics** — https://www.mouser.in  
  Free sourcing with parametric search, lifecycle/EOL alerts, RoHS/REACH compliance, export documentation, small quantity availability.

- **Arrow Electronics (Free Account)** — https://www.arrow.com  
  Free global supply with better volume pricing, franchise lines, design support and online engineering resources.

- **Avnet** — https://www.avnet.com  
  Free sourcing with industrial & enterprise grade supply chain; strong in MCUs, FPGAs, wireless, memory & power.

- **Farnell / Newark / Element14** — https://in.element14.com  
  Free search and BOM procurement with fast small-lot delivery; also supports community/forum & design-center.

- **Future Electronics** — https://www.futureelectronics.com  
  Free procurement for industrial customers; good for memory, PMIC, RF and long-term availability forecasting.

- **RS Components / RS Online** — https://in.rsdelivers.com  
  Free order portal with no MOQ for most passives, connectors, sensors, enclosures and tools.

- **TME (Transfer Multisort Elektronik)** — https://www.tme.eu  
  Free global component search with aggressive pricing for passives, connectors, sensors & modules.

- **LCSC (Low-Cost Sourcing)** — https://lcsc.com  
  Free sourcing portal popular for prototypes & low-cost BOMs. Large Chinese inventory, low MOQ.

- **JLCPCB Assembled Parts Library** — https://jlcpcb.com/parts  
  Free part search directly tied to PCB assembly — pricing includes SMT assembly cost visibility.

- **Findchips** — https://www.findchips.com  
  Free global distributor price compare — Digikey, Mouser, Arrow, Avnet, TME, RS, LCSC etc.

- **OEMSecrets** — https://www.oemsecrets.com  
  Free aggregator that compares pricing and stock across 50+ suppliers in real time.

- **Nexar APIs (Octopart / Findchips Data) – Free Tier** — https://nexar.com  
  Free API for automated pricing, availability, lifecycle, and alternates — useful for BOM scripts & procurement bots.

- **UTSource** — https://www.utsource.net  
  Free sourcing for new & obsolete ICs; strong in replacement parts and component matching.

- **Rutronik24** — https://www.rutronik24.com  
  Free sourcing with strong European footprint; good passive + MCU line-up.

- **Aliexpress Engineering Stores (Caution Needed)** — https://www.aliexpress.com  
  Free access to the largest marketplace for modules, breakout boards, cables, connectors. (Good for development, prototype parts, not recommended for certified production without QA.)

- **Alibaba / 1688 (Bulk Sourcing)** — https://www.alibaba.com  
  Free access to factories for bulk sourcing of modules, passives, connectors, cables, housings and components.

- **Chip1Stop** — https://www.chip1stop.com  
  Free sourcing for Japan, South-east Asia; provides small MOQ imports.

- **Raspberry Pi Approved Resellers** — https://www.raspberrypi.com resellers  
  Free verified distributor list to avoid counterfeit Pi boards and modules.

- **eBay Engineering Parts Stores** — https://www.ebay.com  
  Free sourcing of old/legacy chips, programmer adapters, probes, breakout boards (use with caution).

- **EEM (Electronics Engineer’s Master) Price Compare** — https://www.eem.com  
  Free global search aggregator focused on Asia-Pacific distributors.

- **PartStack (Free BOM Price Check)** — https://www.partstack.ai  
  Free pricing and vendor comparison for BOMs; automated alternates, MOQ and delivery time.

- **PartsBox (Free Tier)** — https://partsbox.com  
  Free personal inventory management + supplier linking and pricing check.

- **Sourcengine (Free Catalog View)** — https://sourcengine.com  
  Free aggregator with realtime price quotes across manufacturers and authorized distributors.

- **Broker/Gray-Market Component Aggregators (use with caution)**  
  - **NetComponents** — https://netcomponents.com (free browsing, negotiation required)  
  - **IC-Source** — https://www.ic-source.com  
  Useful when parts are EOL/NRND/shortage.

### 16C. BOM Validation, Alternates, Lifecycle & NRND Alerts

- **Z2Data (Free Tier)** — https://z2data.com  
  Free access to lifecycle status, NRND/EOL warnings, PCN alerts, alternates and supply chain risk scoring (limited free access).

- **SiliconExpert Free Preview** — https://www.siliconexpert.com  
  Free lifecycle & risk preview for many parts; shows EOL, RoHS, and compliance status. (Full alerts are paid.)

- **PartsBox (Free Tier)** — https://partsbox.com  
  Free BOM correctness check, vendor linking, footprint consistency, and pricing aggregation for prototypes & labs.

- **Nexar API (Free Tier)** — https://nexar.com  
  Automated BOM validation through API: lifecycle, alternates, pricing, parametric matching, stock alerts.

- **Findchips BOM Tool** — https://www.findchips.com/bom  
  Free BOM compare across distributors, pricing history and shortages. Highlights unavailability & alternates.

- **Octopart BOM Tool** — https://octopart.com/bom  
  Free BOM validator with lifecycle, compliance, stock aggregation and cross-reference suggestions.

- **ComponentSearchEngine BOM Validator** — https://componentsearchengine.com  
  Free checking of datasheets, footprints, STEP models, compliance and stock.

- **SamacSys ECAD Model Checker (Free)** — https://www.samacsys.com  
  Free verification of footprints, symbols and parametric correctness to avoid PCB footprint mismatches.

- **FreeDFM (Advanced DFM Check for PCB)** — https://www.4pcb.com/free-dfm-file-check  
  Free netlist check and manufacturability validation detecting shorts/opens and mismatches between schematic/PCB/BOM.

- **KiCad BOM Tools & Scripts (Free)** — https://github.com/KiCad  
  Free plugin ecosystem for BOM cleaning, distributor tagging, and footprint-to-orderable mapping.

- **KiCad “Interactive BOM” Plugin** — https://github.com/openscopeproject/InteractiveHtmlBom  
  Free open-source BOM + PCBA visual tool linking footprint-to-reference and PCB position.

- **OpenBOM (Free Tier)** — https://www.openbom.com  
  Free cloud BOM manager with change history, alternates and vendor price linking.

- **Partstack (Free)** — https://www.partstack.ai  
  Free BOM cleanup, price matching, alternates, lifecycle visibility and MOQ-based optimization.

- **LibreBOM Tools (Open Source)** — https://github.com/search?q=librebom  
  Free scripts to normalize part numbers, map vendor ordering codes, detect duplicates.

- **BOMStorm (Free/Open Source)** — https://github.com/monostable/bomstorm  
  Free CLI for mass BOM manipulation, search, cost summation, distributor tagging.

- **BOMist (Free Tier)** — https://bomist.com  
  Free cloud BOM and inventory manager for prototypes; PDF importer auto-detects part names.

- **bom-builder (Open Source)** — https://github.com/eez-open/bom-builder  
  Free BOM aggregator and formatting tool for KiCad/Altium/OrCAD.

- **pytbom / BOM Tools for Python (Open Source)** — https://github.com/ldmberman/pytbom  
  Free python BOM parser; detect mismatches, missing fields, alternate suggestions.

- **Distributor Lifecycle Tags (Digikey/Mouser/RS)**  
  Free lifecycle icons: Active, NRND, Last Time Buy, Obsolete; helpful in early risk screening.

- **IPC-1752 Material Declaration (Free Standard)** — https://www.ipc.org  
  Free standard for RoHS/REACH and environmental compliance for BOM submission.

- **JLCPCB “Parts Status” Filters (Free)** — https://jlcpcb.com/parts  
  Free flags: Basic, Extended, In Stock, To Be Discontinued — useful for low-cost assembly BOMs.

- **LCSC EOL Alerts** — https://lcsc.com  
  Free flag-based alerts on discontinuation and replacements for low-cost supply chains.

- **Raspberry Pi Approved Reseller List** — https://www.raspberrypi.com resellers  
  Free to remove fake/counterfeit risk for Pi modules in BOMs.

- **eBay/AliExpress Counterfeit Checklists (Free Community Guides)**  
  EEVBlog, Dangerous Prototypes, and Reddit electronics forums maintain free guides for spotting fake ICs.

### 16C. BOM Validation, Alternates, Lifecycle & NRND Alerts

- **Z2Data (Free Tier)** — https://z2data.com  
  Free access to lifecycle status, NRND/EOL warnings, PCN alerts, alternates and supply chain risk scoring (limited free access).

- **SiliconExpert Free Preview** — https://www.siliconexpert.com  
  Free lifecycle & risk preview for many parts; shows EOL, RoHS, and compliance status. (Full alerts are paid.)

- **PartsBox (Free Tier)** — https://partsbox.com  
  Free BOM correctness check, vendor linking, footprint consistency, and pricing aggregation for prototypes & labs.

- **Nexar API (Free Tier)** — https://nexar.com  
  Automated BOM validation through API: lifecycle, alternates, pricing, parametric matching, stock alerts.

- **Findchips BOM Tool** — https://www.findchips.com/bom  
  Free BOM compare across distributors, pricing history and shortages. Highlights unavailability & alternates.

- **Octopart BOM Tool** — https://octopart.com/bom  
  Free BOM validator with lifecycle, compliance, stock aggregation and cross-reference suggestions.

- **ComponentSearchEngine BOM Validator** — https://componentsearchengine.com  
  Free checking of datasheets, footprints, STEP models, compliance and stock.

- **SamacSys ECAD Model Checker (Free)** — https://www.samacsys.com  
  Free verification of footprints, symbols and parametric correctness to avoid PCB footprint mismatches.

- **FreeDFM (Advanced DFM Check for PCB)** — https://www.4pcb.com/free-dfm-file-check  
  Free netlist check and manufacturability validation detecting shorts/opens and mismatches between schematic/PCB/BOM.

- **KiCad BOM Tools & Scripts (Free)** — https://github.com/KiCad  
  Free plugin ecosystem for BOM cleaning, distributor tagging, and footprint-to-orderable mapping.

- **KiCad “Interactive BOM” Plugin** — https://github.com/openscopeproject/InteractiveHtmlBom  
  Free open-source BOM + PCBA visual tool linking footprint-to-reference and PCB position.

- **OpenBOM (Free Tier)** — https://www.openbom.com  
  Free cloud BOM manager with change history, alternates and vendor price linking.

- **Partstack (Free)** — https://www.partstack.ai  
  Free BOM cleanup, price matching, alternates, lifecycle visibility and MOQ-based optimization.

- **LibreBOM Tools (Open Source)** — https://github.com/search?q=librebom  
  Free scripts to normalize part numbers, map vendor ordering codes, detect duplicates.

- **BOMStorm (Free/Open Source)** — https://github.com/monostable/bomstorm  
  Free CLI for mass BOM manipulation, search, cost summation, distributor tagging.

- **BOMist (Free Tier)** — https://bomist.com  
  Free cloud BOM and inventory manager for prototypes; PDF importer auto-detects part names.

- **bom-builder (Open Source)** — https://github.com/eez-open/bom-builder  
  Free BOM aggregator and formatting tool for KiCad/Altium/OrCAD.

- **pytbom / BOM Tools for Python (Open Source)** — https://github.com/ldmberman/pytbom  
  Free python BOM parser; detect mismatches, missing fields, alternate suggestions.

- **Distributor Lifecycle Tags (Digikey/Mouser/RS)**  
  Free lifecycle icons: Active, NRND, Last Time Buy, Obsolete; helpful in early risk screening.

- **IPC-1752 Material Declaration (Free Standard)** — https://www.ipc.org  
  Free standard for RoHS/REACH and environmental compliance for BOM submission.

- **JLCPCB “Parts Status” Filters (Free)** — https://jlcpcb.com/parts  
  Free flags: Basic, Extended, In Stock, To Be Discontinued — useful for low-cost assembly BOMs.

- **LCSC EOL Alerts** — https://lcsc.com  
  Free flag-based alerts on discontinuation and replacements for low-cost supply chains.

- **Raspberry Pi Approved Reseller List** — https://www.raspberrypi.com resellers  
  Free to remove fake/counterfeit risk for Pi modules in BOMs.

- **eBay/AliExpress Counterfeit Checklists (Free Community Guides)**  
  EEVBlog, Dangerous Prototypes, and Reddit electronics forums maintain free guides for spotting fake ICs.

### 16E. Inventory Management, PLM & Part Databases

- **PartsBox (Free Tier)** — https://partsbox.com  
  Free cloud inventory + part tracking, vendor links, lot control, internal part numbers, BOM costing and multi-project stock management.

- **OpenBOM (Free Tier)** — https://www.openbom.com  
  Free collaborative BOM & inventory tool for small teams; supports revisions, alternates, build history and vendor price syncing.

- **PartKeepr (Open Source)** — https://partkeepr.org  
  Free self-hosted part database with stock levels, storage locations, distributor links, part photos, QR labels and BOM association.

- **LibrePCB Library & Supply Manager (Free)** — https://librepcb.org  
  Free part & library manager with symbol/footprint mapping and designated manufacturers.

- **InvenTree (Open Source)** — https://github.com/inventree/InvenTree  
  Free self-hosted inventory, BOM management, tracking storage locations, purchase orders and barcode/QR scanning.

- **KiCad + BOM/QLR Plugins (Free)** — https://github.com/KiCad  
  Free plugin ecosystem that syncs footprints, part metadata, and supplier links.

- **Open ERP / Odoo Community (Free)** — https://www.odoo.com  
  Free community edition useful for manufacturing/procurement and stock tracking when integrated with BOMs.

- **OpenMFG / OpenMRP (Free Tier / Open-Source Options)** — https://www.opensourceerp.com  
  Free and open ERP/MRP solutions supporting purchasing, stock control, vendor management and production orders.

- **OpenPLM (Open Source)** — https://github.com/OpenPLM  
  Free PLM system supporting part revision control, CAD file association, documentation, ECO/ECN workflows.

- **Snipe-IT (Open Source)** — https://snipeitapp.com  
  Free IT asset management repurposed effectively for tools, fixtures, lab equipment and module tracking.

- **Parts Management in Git (Free)**  
  Using **YAML/CSV** + Git to track part revisions, footprint changes, approved vendors.  
  Example open frameworks:  
  - **Open Part Database** — https://github.com/openpartsdb  
  - **Open-Source YAML BOMs** — public repos for revision control.

- **Mouser Project Manager (Free)** — https://www.mouser.in/ProjectManager  
  Free tool to store BOMs, vendor alternates, and re-order lists.

- **Digi-Key Lists & Price Alerts (Free)** — https://www.digikey.in  
  Free watchlists for price changes, back-in-stock notifications, MOQ changes.

- **QR/Barcode Label Generators (Free/Open Source)**  
  - **zint** — https://github.com/zint/zint  
  - **qrencode** — https://fukuchi.org/works/qrencode  
  Free label generation for reel/tape inventory tracking.

- **pymongo + SQLite BOM Inventory Scripts (Open-Source)**  
  Free community scripts automating stock decrement with production batches (useful for in-house assembly).

- **ERPNext (Open Source Edition)** — https://erpnext.com  
  Free open-source ERP with stock, purchase orders, part catalogs, vendor database, and BOM linking.

- **Git + LFS for CAD & STEP Version Control**  
  Recommended free workflow for PLM-style revision history of enclosures, footprints and gerbers.

- **OpenPDM / Free PLM Community Projects**  
  Various open PLM initiatives for engineering file control and ECO workflows.

### 16F. India-Specific Sourcing Platforms

- **Mouser India** — https://www.mouser.in  
  India portal with GST billing, fast courier delivery, no minimum order, customs handled.

- **Digi-Key India** — https://www.digikey.in  
  GST invoices, priority shipping, import duty handled, fast lead times for prototypes.

- **Element14 / Farnell India** — https://in.element14.com  
  Wide inventory in India warehouses, local credit terms for businesses, cable/connectors/tools availability.

- **RS Components India** — https://in.rsdelivers.com  
  Local stock of tools, instrumentation, passives, connectors; GST and fast delivery.

- **TME India** — https://www.tme.eu  
  Shipments from EU with GST invoice and fast customs clearance; strong inventory of passives and modules.

- **ElectronicsComp** — https://www.electronicscomp.com  
  Hobby & engineering parts, sensors, connectors, breakout boards, displays, batteries; fast local shipping.

- **Rabyte** — https://www.rabyte.com  
  Authorized distributor for ST, Microchip, NXP, Nordic, Quectel; strong local support for OEMs.

- **ComKey** — https://comkey.in  
  India distributor for embedded modules, sensors, cables, RF parts, SBCs and test accessories.

- **MexoIndia** — https://mexoindia.com  
  Embedded modules, SBCs, displays, connectors, Wi-Fi/LoRa modules, cables, prototyping supplies.

- **Robu.in** — https://robu.in  
  Local warehouse for dev boards, sensors, actuators, Li-ion batteries, BMS, connectors, wheels and mechatronics.

- **Makerfabs India Distributors** — https://makerfabs.com (local resellers)  
  ESP32, RP2040, LoRa, displays, sensors, industrial modules; local re-sellers across India.

- **IOTStore India** — https://www.iotstore.in  
  ESP, STM32, LoRa, NB-IoT, gateways, antennas, power supplies, sensors for prototypes & pilots.

- **Cambay Tiger / Mouser Authorized India**  
  GST-compliant procurement for enterprises with credit/payment terms.

- **Electronics Bazaar** — https://electronicsbazaar.com  
  Marketplace for refurbished and surplus electronic components/modules, sometimes useful for legacy replacements.

#### ✅ India PCB & Assembly

- **JLCPCB India Shuttle (fast import)** — https://jlcpcb.com  
  Not India-based fabrication, but extremely fast and cost-effective imports with GST billing.

- **PCB Power** — https://www.pcbpower.com  
  India-based PCB fabrication, quick-turn prototype and small-batch production.

- **PCB Cart India Partners** — https://www.pcbcart.com  
  Global PCB fab with India distributors and GST billing.

- **LionCircuits** — https://lioncircuits.com  
  PCB + PCBA based in India; instant quoting, BOM sourcing, automated assembly reports.

- **NextPCB India Partners** — https://nextpcb.com  
  Fast PCB import with GST invoices and assembly option.

- **Circuit Digest PCB** — https://pcb.circuitdigest.com  
  India portal for small-batch boards and PCB services.

- **FabToLab / PCBToGoGo** — https://fabtolab.com  
  Prototyping, 3D printing, PCBs, hardware components.

#### ✅ Enclosures, CNC, 3D Printing, Sheet Metal

- **Raspberry Pi / Arduino Cases – Robu.in / FabtoLab / Thingbits**  
  Large stock of off-the-shelf plastic and metal enclosures.

- **3D Hubs India Network (now Hubs)** — https://www.hubs.com  
  3D printing, CNC machining & sheet-metal with India fulfillment.

- **Pune / Bangalore / Chennai Rapid Molding & CNC Shops**  
  Many accept DXF/STEP quotes directly; community-verified suppliers available on EEVBlog & Reddit India.

- **Enclosure Vendors on IndiaMart** — https://indiamart.com  
  Plastic injection molds, ABS enclosures, waterproof IP65/IP67 boxes, DIN-rail enclosures.

#### ✅ Cables, Harness, Connectors & Antennas

- **Deltron Components India** — https://deltroncomponents.com  
  Indian manufacturer of connectors, cable assemblies, sockets, military-spec hardware.

- **Molex India / TE Connectivity (local distributors)**  
  Available via Rabyte, Mouser India, and Farnell India.

- **RF Antennas & Coax – Sparkrf, Rhombus, Allied Electronics India**  
  Local sources for GSM/LTE/LoRa/NB-IoT antennas and RF cables.

#### ✅ Batteries, Power, Chargers & Power Supplies

- **Battery Packs & BMS – Robu.in / ElectronicsComp / IOTStore**  
  Cells, packs, 18650 holders, TP4056/MCP73831 boards, DC-DC modules.

- **SMPS / Chargers – MeanWell India distributors**  
  Local authorized partners listed on MeanWell website.

#### ✅ Indian Marketplace Platforms

- **IndiaMART** — https://indiamart.com  
  Free sourcing for vendors of PCBs, connectors, sheet metal, battery pack assembly, CNC machining, EMS.

- **TradeIndia** — https://tradeindia.com  
  Domestic B2B sourcing platform for electronics, mechanical parts, and fabrication.

- **IndustryBuying** — https://industrybuying.com  
  Components, tools, soldering equipment, power supplies and lab equipment.

### 17A. Datasheet Repositories & Application Note Libraries

- **Datasheet Archive (Free)** — https://www.datasheetarchive.com  
  Free archive of datasheets from 1970s to present, including obsolete and legacy parts.

- **AllDatasheet (Free)** — https://www.alldatasheet.com  
  Free datasheets, selection guides and parametric info for semiconductors, passives, and sensors.

- **Datasheet.com (Free)** — https://www.datasheet.com  
  Free datasheet lookup with filtering, cross-reference and revision history.

- **SemiWiki Design Docs (Free)** — https://www.semiwiki.com  
  Free expert-written articles, silicon errata, power & RF design notes.

- **Digikey TechForum (Free)** — https://forum.digikey.com  
  Free application notes, design examples, FAQs and BOM assistance.

- **Mouser Engineering Resource Center (Free)** — https://resources.mouser.com  
  Free app notes, whitepapers, parametric comparison tools and design guides.

- **EEVBlog Forum (Free)** — https://www.eevblog.com/forum/  
  Free community discussion, troubleshooting, real-world design failures and fixes.

- **EDN Network (Free)** — https://www.edn.com  
  Free engineering articles and application design insights for power, RF and embedded.

- **Arrow / AspenCore Design Hub (Free)** — https://www.arrow.com/en/research-and-events  
  Free reference designs, app notes, design guides and BOM suggestions.

- **Texas Instruments Application Notes (Free)** — https://www.ti.com/lit  
  Huge open library on power, motor control, isolation, sensors, op-amps, EMC, thermal, PCB layout.

- **STMicroelectronics Application Notes (Free)** — https://www.st.com/resource/en/applications  
  Free documentation for STM32, power electronics, MEMS sensors, PMIC, motor drivers.

- **Microchip Application Notes (Free)** — https://microchip.com/en-us/appnotes  
  Free ANs on low-power, crypto, USB, bootloaders, power stages, motor control, SMPS.

- **Atmel / Microchip AVR App Notes (Free)** — https://ww1.microchip.com/downloads  
  Free firmware and hardware ANs on AVR, PIC, SAM, capacitive touch, USB, BLE.

- **Espressif Docs (Free)** — https://docs.espressif.com  
  Free Wi-Fi/BLE application notes, OTA, power saving, antenna design, PCB reference layouts.

- **Nordic Semiconductor DevZone (Free)** — https://devzone.nordicsemi.com  
  Free ANs and reference projects for BLE, Thread, Matter, low-power and security.

- **NXP Application Notes (Free)** — https://www.nxp.com/docs/en/application-notes  
  Free for i.MX, LPC, Kinetis, power, automotive, NFC, secure elements.

- **Renesas Application Notes (Free)** — https://www.renesas.com/us/en/application  
  Free MCU + power electronics design notes, PCB guidelines, analog front-ends.

- **Infineon / Cypress App Notes (Free)** — https://www.infineon.com/cms/en/design-support/  
  Power MOSFET, IGBT, SiC, motor control, capacitive sensing, HyperBus, security.

- **Analog Devices Application Notes (Free)** — https://www.analog.com/en/design-center  
  Gold-standard analog, RF, precision measurement, power integrity and signal chain design notes.

- **Maxim Integrated (Now ADI) Design Notes (Free)** — https://www.analog.com/en/design-center  
  Free notes on PMICs, battery chargers, LED drivers, secure elements.

- **ON Semiconductor / Onsemi App Notes (Free)** — https://www.onsemi.com/resources  
  Free power, SiC, automotive design notes and PCB layout guidelines.

- **Qorvo / Skyworks RF Design Notes (Free)** — https://www.qorvo.com/design-hub  
  Free matching network guides, RF filters, PA/LNA reference designs.

- **Murata Application Notes (Free)** — https://www.murata.com/en-us  
  Free noise filtering, EMI, power integrity, capacitors/inductors selection, antenna design.

- **TDK / InvenSense Docs (Free)** — https://www.tdk.com  
  Free IMU/gyro/sensor integration notes, calibration, filtering.

- **TE Connectivity / Molex Product Notes (Free)**  
  Free connector pinout, impedance, high-speed routing and cable assembly guidelines.

- **Rohm Semiconductor App Notes (Free)** — https://www.rohm.com  
  Free battery chargers, LED drivers, SMPS, power MOSFET layout tips.

- **Vicor Design Hub (Free)** — https://www.vicorpower.com/design-tools  
  Free power-module design guides, layout & thermal tools.

- **Würth Elektronik Application Notes (Free)** — https://www.we-online.com  
  EMI/EMC, magnetics, power supplies, PCB layout, antenna placement — extremely practical for PCB engineers.

- **Keysight App Notes (Free)** — https://www.keysight.com/find/application-notes  
  Free RF, SI/PI, oscilloscope, signal integrity and impedance measurement guides.

- **Tektronix App Notes (Free)** — https://www.tek.com  
  Free measurement and debugging guides for oscilloscopes, logic analyzers, RF, serial protocols.

- **IEEE Xplore Open Access (Free Section)** — https://ieeexplore.ieee.org/browse/  
  Free access to certain peer-reviewed papers on embedded, RF, power.

### 17B. Reference Design Portals (MCUs, Wireless, Power, Sensors, IoT)

- **Texas Instruments Reference Designs (TI Designs)** — https://www.ti.com/reference-designs  
  Massive free library of verified PCB designs with schematics, Altium files, thermal, SI/PI data, and test reports (MCU, power, motor control, Wi-Fi, BLE, and industrial).

- **STMicroelectronics Reference Designs** — https://www.st.com/en/evaluation-tools  
  Free hardware designs for STM32, MEMS sensors, power modules, motor drivers, NFC and industrial IoT (X-NUCLEO shields, GR-LYWGPS, LoRa kits).

- **ST X-CUBE Expansion Packages** — https://www.st.com/en/embedded-software/x-cube-xxx.html  
  Free embedded middleware with reference schematics: BLE, LoRaWAN, SigFox, NFC, cloud connectors, secure boot.

- **Espressif Reference Designs & Schematics** — https://docs.espressif.com  
  Free ESP32-WROOM, WROVER, ESP32-C3/S2/S3 reference PCBs, certified RF layouts, antenna matching notes and power profiles.

- **Nordic Semiconductor Reference Designs** — https://www.nordicsemi.com/Products/Development-hardware  
  Free hardware files + firmware for nRF BLE/Thread/Matter products, Thingy:52, Thingy:91, DK boards, power measurement kits.

- **NXP Reference Designs** — https://www.nxp.com/design/design-resources/reference-designs  
  Free EVB schematics for i.MX, LPC, Kinetis, secure MCUs, automotive Ethernet, and industrial comms.

- **NXP ANs for i.MX SOM + Power Rails**  
  Reference power-tree + DDR layout guidelines — crucial for Linux SOM design.

- **Microchip Reference Designs** — https://www.microchip.com/en-us/design-centers/reference-designs  
  Free schematics & Gerbers for PIC, AVR, SAM, crypto, USB-C PD controllers, SMPS, PoE, touch sensing.

- **Silicon Labs Reference Designs** — https://www.silabs.com  
  Free Z-Wave, Zigbee, Matter reference boards, secure boot, Wi-Fi IoT modules, low-power sensor hubs.

- **Infineon (Cypress) Reference Designs** — https://www.infineon.com/design-support  
  Free hardware + firmware for PSoC, AIROC Wi-Fi/BLE, motor drives, battery chargers, SiC MOSFET power stages.

- **Analog Devices Circuits from the Lab** — https://www.analog.com/circuits-from-the-lab  
  Free precision analog & RF reference circuits with schematics, component selection and measured results.

- **Analog Devices Sensor & Signal Chain Reference Designs**  
  Free data acquisition, IMU front ends, vibration sensors, condition monitoring, high-accuracy ADC/DAC paths.

- **Maxim (ADI) Reference Designs** — https://www.analog.com/en/design-center  
  Free designs for PMICs, battery charging, fuel gauging, sensor signal conditioning, secure elements.

- **Qorvo RF Reference Boards** — https://www.qorvo.com/design-hub/reference-designs  
  Free PA/LNA, filter, and matching network layouts with measured S-parameters.

- **Skyworks Design Files** — https://www.skyworksinc.com  
  Free RF front-end and antenna-matching designs for cellular, GNSS, ISM, Wi-Fi.

- **Semtech LoRa Reference Designs** — https://www.semtech.com/lora  
  Free SX127x/SX126x radio modules, matching networks, PCB layouts, LoRaWAN gateway schematics.

- **Arduino Reference Designs (Open Hardware)** — https://www.arduino.cc/en/Main/Products  
  Free schematics, PCB files, BOMs for Uno, Nano, MKR, Portenta — great starting point for custom boards.

- **Raspberry Pi HAT Design Guide (Free)** — https://www.raspberrypi.com/documentation/hardware  
  Free specs + reference designs for HATs, PoE HATs, CM carrier boards.

- **BeagleBone Open Hardware Files** — https://beagleboard.org  
  Free Altium/KiCad designs for BeagleBone Black, PocketBeagle, I/O capes.

- **Open Source Hardware Projects (OSHPark Shared Projects)** — https://oshpark.com/shared_projects  
  Free community-shared KiCad/Eagle reference boards for sensors, motor drivers, audio, power, RF.

- **Dangerous Prototypes (Open Hardware)** — http://dangerousprototypes.com  
  Free schematics for Bus Pirate, digital PSU, IR Toy, logic tools.

- **OpenPower Electronics Projects** — https://github.com/search?q=power+electronics+reference  
  Free SMPS, buck/boost, motor drivers, inverters, BLDC drivers.

- **Würth Elektronik Reference Designs** — https://www.we-online.com  
  Free RF + power + antenna reference boards with BOM, Gerbers and EMI guidelines.

- **Microchip MCP738xx / BQ240xx Charger Reference Designs (TI/Microchip Docs)**  
  Free tested reference chargers, battery protectors, power-path circuits.

- **OpenEVSE (Open Hardware EV Charger)** — https://github.com/OpenEVSE  
  Free open-source AC charging reference design with safety, relays and metering.

- **Open Source SDR Boards (LimeSDR, Pluto SDR, HackRF, OAI)**  
  Free RF front-end and baseband reference schematics & layouts.

- **Open source drone autopilots (PX4, ArduPilot)** — https://px4.io  
  Free Pixhawk hardware reference layouts for STM32, IMU, PMIC, CAN, GPS.

- **ESPHome / Tasmota Compatible PCB Designs** — https://github.com  
  Free Sonoff-style smart home reference boards for ESP modules.

- **KiCad Example Designs** — https://github.com/KiCad/kicad-symbols  
  Free reference PCBs, power supplies, RF matching, sensors.

- **Hackaday.io Projects (Open Hardware)** — https://hackaday.io/projects  
  Thousands of free open-source designs, BOM, schematics & tips.

### 17C. Evaluation Boards, Dev Kits & Free Sample Programs

- **ST Nucleo / Discovery Boards** — https://www.st.com/en/evaluation-tools.html  
  Low-cost MCU boards with ST-LINK debugger, Arduino headers, and open hardware docs. Many come with free firmware examples and middleware.

- **STM32 SensorTile / STEVAL Kits (Free Docs & Schematics)** — https://www.st.com  
  Ready-to-use sensor + BLE boards for industrial sensing, AI, vibration, IMU research — full open design files.

- **Texas Instruments LaunchPad Series** — https://www.ti.com/tools-software/mcu-mpu-development-tools  
  Ultra-low-cost MSP430, CC32xx Wi-Fi, SimpleLink BLE, Tiva ARM Cortex-M, motor control kits. Powerful + cheap with full reference designs.

- **TI Booster Packs (Shields)** — https://www.ti.com/designkits  
  Add-on boards for sensors, audio, wireless, displays, power stages — all with schematics and firmware.

- **Espressif Dev Boards (ESP32, ESP8266, ESP-C3/S2/S3)** — https://docs.espressif.com  
  Very low-cost Wi-Fi/BLE boards with FCC-certified RF design and open hardware references.

- **NodeMCU / WROOM / WROVER Boards** — https://github.com  
  Open hardware design files + free SDKs, Arduino and ESP-IDF examples; widely used in IoT.

- **ESP32-Lyra, ESP32-Audio Dev Kits** — https://docs.espressif.com  
  Reference boards for AI, audio, DSP, voice commands, low-power IoT.

- **Nordic DK & Thingy Series** — https://www.nordicsemi.com  
  Thingy:52, Thingy:53, Thingy:91, DK boards — BLE/Thread/Matter with power-trace tools and open firmware examples.

- **NXP LPC & i.MX Evaluation Kits** — https://www.nxp.com/design/design-resources/evaluation-design-hardware  
  Industrial MCUs, Linux SoC boards, automotive/secure element modules, NFC kits — open source hardware + BSPs.

- **Microchip Curiosity & Xplained Boards** — https://www.microchip.com/developmenttools  
  PIC, AVR, SAM Cortex-M, CryptoAuth, USB, and motor control reference boards — full schematics & Gerbers.

- **Infineon PSoC & AIROC Kits** — https://www.infineon.com/design-support  
  BLE/Wi-Fi/Touch/MCU evaluation boards with ModusToolbox and certified reference designs.

- **Analog Devices Eval Boards** — https://www.analog.com  
  Precision ADC/DAC, RF transceivers, MEMS sensors, power management, vibration monitoring — free design files & eval software.

- **Maxim Integrated (ADI) Eval Boards** — https://www.analog.com  
  Battery charging, power, secure elements, PMICs, motor drivers — open docs and gerbers.

- **Silicon Labs Wireless Kits** — https://www.silabs.com/development-tools  
  Zigbee/Matter, sub-GHz, Wi-Fi + energy profiler support.

- **Renesas Eval & Starter Kits** — https://www.renesas.com  
  RA/RL/RX MCUs, PMICs, motor drives, USB Type-C controllers, power stage reference boards.

- **Arduino Boards (Open Hardware)** — https://www.arduino.cc  
  Uno, Nano, Mega, MKR, Portenta. Schematics + PCB files are free for custom board derivations.

- **Raspberry Pi Boards** — https://www.raspberrypi.com  
  CM modules, Pi Zero, Pico, HATs, PoE HAT — full detailed design docs.

- **BeagleBone (Open Hardware)** — https://beagleboard.org  
  BeagleBone Black, PocketBeagle, Blue — free Altium/KiCad files and full Linux BSP.

- **HiFive RISC-V Boards (Open Source)** — https://www.sifive.com  
  Open hardware RISC-V processors, reference SoC and firmware examples.

- **PYNQ / Zynq FPGA SBC** — https://www.pynq.io  
  Python + FPGA dev platform from Xilinx; educational + industrial prototyping.

- **Digilent Boards (Free Software + Student Access)** — https://digilent.com  
  Basys, Nexys, Analog Discovery, Arty FPGA boards; Vivado WebPACK is free.

- **Open-Source FPGA Boards (Lattice/ICE40)** — https://github.com/YosysHQ  
  Free tools (Yosys, nextpnr) + open hardware designs for small FPGA projects.

- **Particle Boards (Free Cloud Tier)** — https://particle.io  
  BLE / LTE / Wi-Fi modules with OTA, cloud, and secure boot — free tier available.

- **OpenEVSE** — https://github.com/OpenEVSE  
  Open-source EV charging hardware with schematics & firmware.

- **Pycom / LoRa / SigFox / NB-IoT Boards** — https://pycom.io  
  MicroPython wireless boards — many community open hardware forks.

- **Open Source Drone Autopilot Boards (PX4 / ArduPilot)** — https://px4.io  
  Pixhawk reference hardware with full PCB files.

- **HackRF / LimeSDR / Pluto SDR** — https://github.com/mossmann/hackrf  
  RF SDR boards with open schematics and reference designs.

- **OpenMV Cam** — https://openmv.io  
  MicroPython + camera AI board — open hardware schematics.

- **Google Coral Dev Boards (Free Docs)** — https://coral.ai  
  Edge TPU boards; schematics freely published.

#### ✅ Free Sample Programs (Semiconductors, Passives, RF)

- **Texas Instruments Free Samples** — https://www.ti.com  
  Free samples for MCUs, op-amps, ADC/DAC, PMIC, power ICs, wireless chips (limited quantities).

- **Analog Devices Free Samples** — https://www.analog.com  
  Free precision analog parts, IMUs, RF front ends, ADC/DACs, power modules.

- **Microchip Free Samples** — https://www.microchip.com  
  PIC/AVR/ARM microcontrollers, crypto ICs, USB, PMICs.

- **NXP Free Samples** — https://www.nxp.com  
  MCUs, secure elements, NFC, power parts (limited availability).

- **STMicroelectronics Free Samples** — https://www.st.com  
  MCUs, sensors, PMICs, power MOSFETs, automotive parts.

- **Silicon Labs Samples** — https://www.silabs.com  
  BLE, Zigbee, Matter, Wi-Fi chips/modules.

- **Murata Passives & Modules (Samples)** — https://www.murata.com  
  Capacitors, inductors, filters, MEMS sensors, LoRa modules.

- **Qorvo / Skyworks RF Samples** —  
  RF filters, FEMs, LNAs, PAs commonly approved for engineers.

- **Molex / TE Connectivity Sample Kits** —  
  Connectors, crimp kits, wire assemblies for OEMs.

- **Würth Elektronik Sample Program** — https://www.we-online.com  
  Free inductors, EMI filters, RF components — engineers love this one.

- **Yageo / Vishay Samples (Passives)** —  
  Resistors, capacitors, RF passives samples offered through local reps.

### 18A. Regulatory Certifications, Safety Standards & Compliance (CE, FCC, BIS, WPC, UL, RoHS, etc.)

- **CE Marking (Official EU Portal – Free)** — https://ec.europa.eu/growth/single-market/ce-marking  
  Free guidance on CE declaration of conformity, required test standards, technical files, risk analysis, user manuals.

- **RED (Radio Equipment Directive) CE Guidelines (Free)** — https://ec.europa.eu  
  Free documents for RF modules, Wi-Fi/BLE/LoRa, EMC, SAR, safety, antenna specs and labeling rules.

- **FCC Rules & Certification Guide (Free)** — https://www.fcc.gov  
  Free Part 15 compliance docs for Wi-Fi, BLE, Zigbee, LoRa, sub-GHz devices, unintentional radiators and digital devices.

- **FCC Equipment Authorization System (EAS) – Public Search (Free)** — https://fccid.io  
  Free lookup of FCC-certified devices to study test reports, antennas, schematics and RF enclosures.

- **ANSI C63 EMC Standards (Free Overview)** — https://c63.org  
  Free overview of measurement setups for EMC pre-compliance and radiated emissions.

- **BIS (Bureau of Indian Standards) CRS Schemes (Free)** — https://www.bis.gov.in  
  Free listing of mandatory electronics/product safety certification requirements in India.

- **WPC ETA Guidelines for Wireless (India – Free)** — https://dot.gov.in  
  Free information on Equipment Type Approval for Wi-Fi, BLE, LoRa, RFID, 2.4GHz/5GHz modules.

- **TEC (Telecommunication Engineering Centre – Free Docs)** — https://tec.gov.in  
  Free standards for telecom and IoT devices used in Indian networks.

- **RoHS & REACH Compliance Guidelines (EU – Free)** — https://ec.europa.eu/environment  
  Free requirements for hazardous substances, material declarations, documentation templates.

- **UL / ETL Global Safety (Free Guidance Docs)** — https://ul.com  
  Free resources for power adapters, batteries, EV chargers, appliances, industrial controllers.

- **IEC & EN Standards (Public Overviews – Free)** — https://www.iec.ch  
  Free overview of safety standards: IEC 62368 (IT equipment), 60950, 60601 (medical), 61010 (test instruments), 300328 (RF).

- **IPC Standards & Guidelines (Free Overviews)** — https://www.ipc.org  
  Free overview docs on PCB fabrication, assembly, structural integrity, solder joints.

- **ISO/IEC 27001 & IoT Cybersecurity Guidance (Free Summaries)** — https://www.iso.org  
  Free overviews of cybersecurity standards, IoT data handling & secure product lifecycle.

- **NIST IoT Cybersecurity Framework (Free)** — https://www.nist.gov  
  Free best practices for secure boot, OTA updates, identity, crypto & cloud communication.

- **NIST Battery Safety & Thermal Runaway Docs (Free)**  
  Free safety notes for Li-ion battery testing, BMS design, certification procedures.

- **PTCRB Certification Guidelines (Free Overview)** — https://www.ptcrb.com  
  Free cellular certification requirements for GSM/LTE/NB-IoT devices.

- **Wi-Fi Alliance (Free Specs Overview)** — https://www.wi-fi.org  
  Free overviews of WPA2/WPA3, mesh, WPS, 802.11 specs for interoperability.

- **Bluetooth SIG (Free Spec Access)** — https://www.bluetooth.com  
  BLE specifications, radio requirements, protocol stack rules & qualification program.

- **LoRa Alliance (Free Technical Resources)** — https://lora-alliance.org  
  Free LoRaWAN certification test plans, PHY/MAC requirements, OTA, join process.

- **Matter / Thread / Zigbee Alliance Docs (Free)** — https://csa-iot.org  
  Free testing & certification guidelines for smart home and automation devices.

- **USB.org Compliance Framework (Free)** — https://usb.org  
  Free docs for USB-IF compliance, power negotiation, PD, Type-C, HID, CDC, MSC.

- **Open Certification Test Reports (Example References)** — https://fccid.io  
  Free access to actual RF test reports, SAR, EMC results — engineers can reverse-study certified device architectures and antenna layouts.

- **CE Declaration Templates (Free)**  
  - Open-source Declaration of Conformity templates  
  - Risk assessment templates  
  - Technical file checklists (available at multiple government portals)

- **Self Pre-Compliance Tools (Free)**  
  - **REEMF (Simple EMC Calc)** — open calculators for cable emissions  
  - **OET Bulletins** — FCC test references  
  - **OpenEMI** (Github projects) — community EMI guides.

### 18B. Compliance Testing Labs, RF Chambers & Pre-Compliance Tools

- **Sigrok + PulseView (Free)** — https://sigrok.org  
  Free protocol and signal analysis; useful for identifying noise, glitches, and EMI-related digital integrity issues.

- **Near-Field Probing (DIY)** — https://github.com/erikwilson/nf-probe  
  Free open-source near-field probe design for PCB-level EMI scanning using a spectrum analyzer or SDR.

- **DIY EMC Pre-Compliance Chamber (Open Designs)** — https://github.com/topics/emc-chamber  
  Free community designs for small anechoic chambers using ferrite tiles/absorber foams for pre-scan testing.

- **GNU Radio + SDR (Free)** — https://www.gnuradio.org  
  SDR-based spectrum analysis for emissions, harmonics and unintentional radiators (ISM bands, harmonics, clock noise).

- **rtl_sdr / Airspy SDR (Free Software)** — https://osmocom.org/projects/rtl-sdr  
  Free spectrum scanner with RTL Explorer, rtl_power, and waterfalls for detecting radiated emissions hot spots.

- **SDR# Spectrum Analyzer (Free)** — https://airspy.com/download/  
  Free wideband RF visualization for unlicensed emissions debug.

- **LimeSDR / HackRF with Free Software** — https://github.com/mossmann/hackrf  
  Open hardware SDRs with GNU Radio, SDR#, URH for RF emissions, harmonics, digital modulation quality.

- **OpenEMS (Free, Open-Source EM Solver)** — https://openems.de  
  Free full-wave EM simulation for antennas, enclosures, shielding and ground return issues.

- **Qucs-S (Free)** — https://ra3xdh.github.io  
  Free circuit simulator with RF models to analyze filters, matching networks and parasitic EMI.

- **EMCoS Studio (Free Student Tier)** — https://www.emcos.com  
  Free academic version for antenna, shielding and EMC modelling.

- **Ansys HFSS / CST Studio (Free Student Editions)**  
  Free limited student licenses for antenna simulation and EMI/EMC coursework.

- **KiCad High-Speed/EMI Design Rules (Free)** — https://kicad.org  
  Free design rules for controlled impedance, differential pairs, stitching vias and ground isolation.

- **Saturn PCB Toolkit (Free)** — https://saturnpcb.com/saturn-pcb-toolkit  
  Free impedance calculator, differential pair rules, return loss model, trace inductance/capacitance.

- **Murata EMI Design Guides (Free)** — https://www.murata.com  
  Free tutorials on decoupling, ferrites, power filtering, PCB layout and EMI suppression.

- **Würth Elektronik EMC Application Notes (Free)** — https://www.we-online.com  
  Free EMI/EMC layout checklists, choke selection, filtering and measurement techniques.

- **Keysight App Notes (Free)** — https://www.keysight.com  
  Free guides for spectrum analyzer setup, pre-compliance scans and radiated testing.

- **Tektronix EMC Guides (Free)** — https://www.tek.com  
  Free measurement app notes for RE/RF debug with oscilloscopes and probes.

- **R&S EMI Debug Notes (Free)** — https://www.rohde-schwarz.com  
  Free documentation for pre-compliance scanning and noise hunting.

#### ✅ Directories & Databases for Accredited Test Labs

- **FCC Certified Labs Directory (Free Search)** — https://apps.fcc.gov  
  Free search of accredited EMC/RF/EMI/SAR labs worldwide.

- **ANAB / A2LA Accredited Lab Search (Free)** — https://www.a2la.org  
  Free directory of global labs for EMC, RF, SAR, safety, environmental tests.

- **ILAC Accredited Labs (Global-Free)** — https://ilac.org  
  Free international search for test houses with recognized mutual acceptance.

- **TÜV Rheinland, TÜV SÜD, UL, Intertek, SGS, DEKRA Labs (Free Portals)**  
  Free contact & capability listings for compliance testing (RF, EMC, safety, battery, SAR, environmental).

#### ✅ India-Specific Compliance Labs (Searchable, Public)

- **BIS Approved Labs (Free Listing)** — https://www.bis.gov.in  
  Free list of Indian NABL-accredited labs for electronics, safety, and RF.

- **NABL Accredited Labs Directory (Free)** — https://nabl-india.org  
  Free list of accredited labs for EMC, RF, automotive, medical device and environmental testing.

- **TEC (Telecom Engineering Centre) Approved Labs** — https://tec.gov.in  
  Free directory for telecom/RF compliance labs in India.

- **STQC Labs (MeitY India)** — https://stqc.gov.in  
  Free listing of IT/embedded compliance labs and certification pathways.

- **Private EMC/EMI Labs in India (Searchable)**  
  - SGS India  
  - UL India (Bangalore, Pune)  
  - TÜV Rheinland India  
  - Intertek India  
  - DEKRA India  
  - Wipro PARI, CDAC labs

  All have free capability lists and PDF facility brochures.

#### ✅ DIY & Open-Source EMC Debug Kits

- **Near-Field Probe Open-Hardware** — https://github.com/erikwilson/nf-probe  
  Free probes + PCB design for EMI hot-spot scanning with SDR or spectrum analyzer.

- **DIY LISN (Line Impedance Stabilization Network) Projects** — https://github.com/topics/lisn  
  Free PCB designs for conducted EMI debugging.

- **Open TEM Cell & GTEM Cell (DIY)** — https://github.com/topics/gtem  
  Free mechanical + RF designs for pre-compliance radiated testing.

- **Spectrum Analyzer Software (Free)**  
  - rtl_power  
  - rtl_fm  
  - airspy_fft  
  - hackrf_sweep

### 18C. PCB Assembly Houses (Global & India), Turnkey EMS & Prototyping Services

#### 🌍 Global PCB + PCBA (Fast, Low-Cost, MOQ-Friendly)

- **JLCPCB (China)** — https://jlcpcb.com  
  Ultra-low-cost PCB & turnkey SMT assembly, 2–6 layer boards, stencil, testing. Integrates LCSC parts library. Great for prototypes → small runs.

- **PCBWay (China)** — https://pcbway.com  
  PCB + PCBA + SMT stencil + 3D printing + CNC machining. Strong online DFM check and global delivery.

- **Seeed Fusion (SeeedStudio)** — https://www.seeedstudio.com/fusion  
  Turnkey PCB/PCBA, parts sourcing, testing, custom enclosures. Good for IoT modules and low-volume.

- **NextPCB** — https://nextpcb.com  
  Fast-turn PCBA, ICT/testing options, RF/HDI support.

- **ALLPCB** — https://www.allpcb.com  
  Rapid PCB manufacturing + assembly with competitive pricing.

- **Aisler (EU)** — https://aisler.net  
  PCB + assembly in Europe with easy online quoting, transparent DFM.

- **OSH Park (USA)** — https://oshpark.com  
  High-quality purple PCBs made in the USA; assembly via OSH Stencils & partners.

- **MacroFab (USA/Mexico)** — https://macrofab.com  
  Turnkey EMS manufacturing, online BOM/CPL pricing, rapid prototypes to production runs.

- **PCBCart** — https://pcbcart.com  
  PCB + assembly with global delivery and DFM reports.

- **Screaming Circuits (USA)** — https://screamingcircuits.com  
  Prototype and low-volume assembly with online instant quoting.

- **Eurocircuits (EU)** — https://eurocircuits.com  
  European fabrication + assembly, strong DFM/DRC reports and online viewer.

- **Tempo Automation (USA)** — https://tempoautomation.com  
  Fast-turn, complex boards, HDI and high-reliability options.

- **Fabrica (Israel)** — https://www.fabrica.one  
  Automated PCB assembly with machine learning optimization.

- **PCB Assembly India Shuttle via JLC/PCBWay**  
  GST invoicing + fast import using DHL/FedEx; most Indian startups use this method for prototypes.

#### 🇮🇳 India PCB + PCBA (Local EMS, Prototype Friendly)

- **LionCircuits (India)** — https://lioncircuits.com  
  Online quoting, assembly, ICT, PCB fabrication, component sourcing, AoI inspection.

- **PCB Power (India)** — https://www.pcbpower.com  
  Indian PCB manufacturing (2-12 layers), stencil, assembly partners.

- **FabtoLab (India)** — https://fabtolab.com  
  PCB, assembly, 3D printing, CNC machining, prototyping components.

- **CircuitDigest PCB Service (India)** — https://pcb.circuitdigest.com  
  India-based fabrication and assembly for prototypes and hobby.

- **Sparkrf EMS (India)** — (searchable vendors; often custom quotes)  
  RF-friendly PCB/assembly and antenna integration.

- **Sion Semiconductors EMS Partners** — India-based EMS for industrial IoT and small batch.

- **Elin Electronics / Dixon Technologies** — Large-scale EMS for mass-market consumer electronics.

- **Foxconn / Flex / Jabil India** — High-volume EMS for consumer and industrial goods.

- **SMT Assembly Vendors on IndiaMART** — https://indiamart.com  
  Many small/medium EMS houses accept low-MOQ PCB assembly orders.

- **CDAC Techpark EMS Partnerships** — Advanced manufacturing partners for Indian deeptech startups.

#### 🔌 Cable Harness, Battery Pack Assembly, Box Build

- **Deltron Components (India)** — https://deltroncomponents.com  
  Cable harnesses, military connectors, custom cable assemblies.

- **Excella Electronics & IndiaMART Cable Vendors**  
  Harness assembly for small and large volumes.

- **Battery Pack Assemblers (India)**  
  Many local vendors support 18650/21700 pack design, BMS integration (via IndiaMART/TradeIndia).

#### 🧪 Testing, AoI, ICT, Programming, Calibration

Most global houses provide:
- AoI (Automated Optical Inspection)
- X-Ray BGA inspection (mid/high complexity)
- ICT / flying probe
- Functional testing
- Firmware flashing
- Conformal coating and reliability coatings

Local India EMS can also provide these with MOQ negotiation.

### 18D. Hardware QA — HALT/HASS, Lifecycle, Environmental Testing & Traceability

- **HALT/HASS Fundamentals (Free Guides)**  
  - NASA Technical Reports on HALT/HASS  
  - IPC/JEDEC reliability whitepapers  
  Free introductions to stress screening, thermal cycling, vibration, early-life failure detection.

- **JEDEC Reliability Standards (Public Summaries — Free)** — https://www.jedec.org  
  Free summaries of JESD22 standards for temperature cycle, humidity, vibration, ESD, solder joint reliability, component aging.

- **MIL-STD-810 (Free Public Summaries)** — https://quicksearch.dla.mil  
  Free overviews for shock, vibration, temperature, humidity, altitude — used by industrial/automotive/military devices.

- **IPC Reliability Documents (Free Overviews)** — https://www.ipc.org  
  Free guidance on board level reliability, solder joints, vibration, flex cycles, cleaning, coating.

- **NASA Parts Selection Lists (Free)** — https://nepp.nasa.gov  
  Free part derating rules, reliability curves, radiation guidelines, worst-case analysis tools.

- **IEC 60068 (Free Concept Summaries)** — https://www.iec.ch  
  Free summaries for vibration, shock, thermal shock, dust/water ingress, environmental stress.

- **NIST Hardware Cybersecurity Guidance (Free)** — https://www.nist.gov  
  Free lifecycle security guidelines: secure boot, secure firmware updates, identity, anti-rollback.

- **UL Safety & Reliability Notes (Free Guidance Docs)** — https://ul.com  
  Free environment, fire/smoke, power and isolation safety concepts.

- **IPC-1601 Moisture Handling & Baking Rules (Free Summary)**  
  Free process guidance for MSD (moisture-sensitive devices) handling, MSL levels.

#### ✅ Temperature, Humidity, Vibration & Stress Tests

- **DIY Temperature/Humidity Chamber (Open Hardware)** — https://github.com/topics/environmental-chamber  
  Free community mechanical + control designs for small pre-compliance chambers.

- **Open-Source Reflow Oven / Thermal Controllers** — https://github.com  
  Can also be used for limited thermal cycling with logging.

- **OpenVibration Table DIY Projects** — https://github.com/topics/vibration-table  
  Free mechanical + control designs for basic vibration stress testing.

- **Open-Source Shock/Drop Test Fixtures** — https://github.com/topics/drop-test  
  For mechanical robustness testing of consumer IoT.

- **Cheap Thermocouple + Data Logging Tools**  
  - Arduino + MAX31855/31856  
  - Free Python logging  
  Useful for temperature profiling and stress cycles.

#### ✅ Environmental & Reliability Test Houses (Global)

- **TÜV Rheinland / TÜV Süd / UL / Intertek / SGS**  
  All publish free capability lists and datasheets for:
  - HALT/HASS
  - Thermal cycling
  - IP rating (IP65/67/68)
  - Corrosion / salt spray
  - Battery safety (IEC62133)
  - Drop, shock, vibration

- **ILAC / A2LA Accredited Labs Search (Free)** — https://ilac.org / https://www.a2la.org  
  Free global directories for reliability & environmental labs.

#### ✅ India-Specific Test Houses (Public Listings)

- **NABL Accredited Environmental Labs (Free Directory)** — https://nabl-india.org  
  Lists labs with environmental chambers, temperature/humidity, corrosion, drop, IP testing.

- **BIS / STQC Labs (Free Listing)** — https://www.bis.gov.in / https://stqc.gov.in  
  Environmental + reliability testing for Indian certification schemes.

- **CDAC, SAMEER & CEERI Labs**  
  Environmental and reliability testing for IoT, RF, industrial and consumer projects.

#### ✅ Traceability, QA Documentation, Failure Analysis

- **OpenBOM / PartsBox (Free Tier)** — https://openbom.com / https://partsbox.com  
  Free tracking of lots, serial numbers, test results and revisions.

- **InvenTree (Open Source)** — https://github.com/inventree/InvenTree  
  Free inventory + part traceability for production batches.

- **MES Lite / Production Log Scripts (Open-Source)**  
  Git+JSON based tracking for manufactured lots, failures, repairs and field returns.

- **Failure Analysis Checklists (Free)**  
  NASA / Bosch / TI release free guides on root cause analysis, FMEA, fishbone analysis.

- **Open-Source Burn-In Rigs (Heaters + Cycling + Logging)** — https://github.com/topics/burn-in  
  Free test rig designs for early-life failure detection.

- **IPC-A-610 (Free Summary)** — Acceptability of PCB assemblies overview.

#### ✅ IP / Waterproof / Dust Testing

- **Ingress Protection (IP) Free Guides**  
  Official IEC/EN standard overviews for IPX1–IPX8, IP5X/6X dust tests.

- **DIY Splash/Immersion Test Fixtures**  
  Open mechanical designs on GitHub + GoPro-style submersion timing rigs.

### 18E. Packaging, ESD Safety, Logistics & Export

#### ✅ ESD Safety & Handling (Free Guides / Tools)

- **IPC/JEDEC Moisture Sensitivity (MSL) Guides — Free Summaries**  
  Official handling rules for moisture-sensitive ICs, baking conditions, packaging, humidity indicators.

- **ESD Association – Free Technical Overviews** — https://www.esda.org  
  Free documents on ESD-safe handling, wrist straps, footwear, ionizers, static-dissipative mats and workspaces.

- **NASA ESD Control Handbook (Free)** — https://nepp.nasa.gov  
  Free comprehensive ESD control practices for PCB assembly, repair and aerospace hardware.

- **ANSI/ESD S20.20 Overview (Free)**  
  Free compliance summary for setting up ESD-safe workplaces.

- **Open-Source ESD Mat Grounding Testers** — https://github.com/topics/esd-tester  
  DIY grounding and monitoring circuits for small labs.

- **Static Calculator Tools (Free)** — community Python scripts calculating discharge risks for plastics/packaging.

#### ✅ Packaging Electronics & PCBs

- **IPC-1601 Moisture Handling (Free Summary)**  
  Free rules for bagging, vacuum sealing, desiccants, MSL labels, baking before reflow.

- **Moisture Barrier Bags (MBB) + Humidity Indicator Cards (HIC) Guides**  
  Standard free resources from Digi-Key, Mouser, and ESD Association.

- **Vacuum Sealing for PCBs (DIY)** — https://github.com/topics/pcb-packaging  
  Community guides for low-cost vacuum sealing and desiccant packing.

- **ESD Shielding & Conductive Bags**  
  Free education resources from 3M, Desco and SCS.

- **Packing for Drop/Vibration**  
  Tektronix / Keysight free docs for foam, corrugated boxes, protective layers, shock sensors in shipping.

#### ✅ Battery Shipping & Lithium Regulations (Free Resources)

- **IATA Lithium Battery Guidance (Free)** — https://www.iata.org  
  Free rules for shipping Li-ion/Li-poly battery packs, UN38.3 test summary needs, packaging and quantity limits.

- **UN38.3 Testing Overview (Free)**  
  Free requirements for drop, thermal, vibration and short-circuit tests.

- **ICAO / DG Rules (Free)**  
  Free high-level guidance for shipping batteries via air cargo.

- **DHL / FedEx Battery Shipping Guidelines (Free PDFs)**  
  Step-by-step packaging instructions for electronics with batteries.

#### ✅ Export & Import for Electronics

- **Harmonized System (HS) Codes Lookup — Free**  
  - https://www.wto.org  
  - https://www.fedex.com/en-in/shipping/international/hs-codes.html  
  Free identification of correct tariff codes for PCBAs, modules, batteries, antennas, and development kits.

- **Export Documentation Checklists (Free PDFs)**  
  - Commercial invoice  
  - Packing list  
  - CE/FCC declarations (if needed)  
  - MSDS for batteries  
  - UN38.3 summary  
  Available via DHL/FedEx/UPS portals.

- **DGFT (India) Export Guidelines (Free)** — https://www.dgft.gov.in  
  Free resources for exporting electronics hardware from India.

- **Local GST Export Under LUT (Free Steps)**  
  Government portal offers free documentation steps for GST-free exports under LUT (Letter of Undertaking).

#### ✅ Logistics Choices Used by Hardware Teams

- **DHL Express (Fast and reliable)** — https://www.dhl.com  
  Preferred for shipping prototypes, PCBAs, modules, small batches internationally.

- **FedEx International Priority** — https://www.fedex.com  
  Common for shipping dev kits, eval boards, components, batteries (with DG paperwork).

- **UPS / TNT / Aramex**  
  Popular for devices and PCBs when shipping between Asia, EU, USA, India.

- **Shiprocket / Delhivery / BlueDart (India)**  
  For domestic shipments of prototypes, modules, PCBs, cables.

- **India Post Speed Post**  
  Cost-effective option for domestic engineering shipments; slower but reliable.

#### ✅ Special Packaging for RF / Antenna Products

- 3M free guidelines for RF-absorbing foam, shielding, Faraday bags for sensitive RF modules.
- Digikey/Mouser app notes for antenna connectors, SMA cables, PCB-mounted antennas and protection covers.

#### ✅ Protective Packaging for Production Units

- Free guidelines for:
  - Conformal coating protection during shipping  
  - Anti-corrosion VCI bags for metal components  
  - Silica gel desiccants  
  - ShockWatch / Drop indicator stickers

19. Secure Hardware Design, Cryptography, Secure Boot & MCU Security

### 19A. Secure Boot, Firmware Encryption & OTA Security

- **MCUBoot (Open Source)** — https://github.com/mcu-tools/mcuboot  
  Widely used secure bootloader for ARM Cortex-M (STM32, NRF, NXP, ESP32 via ports). Supports image signing (RSA/ECDSA), rollback protection, anti-replay counters and OTA via BLE, LoRaWAN, HTTP, UART.

- **Tock Bootloader / Tock OS (Open Source)** — https://github.com/tock/tock  
  Secure embedded OS with built-in isolation and signed boot. Supports MPU protection, process sandboxing and secure firmware loads.

- **Trusted Firmware-M (TF-M)** — https://www.trustedfirmware.org  
  ARM’s open secure boot + trusted execution implementation for Cortex-M. PSA-certified, includes secure key storage, attestation, and crypto services.

- **ARM PSA Certified Secure Boot (Reference Code)** — https://www.arm.com/psa  
  Free reference architecture, secure provisioning flows, root of trust and attestation docs for MCU/IoT.

- **Zephyr RTOS Secure Boot + MCUboot Integration** — https://zephyrproject.org  
  Zephyr ships with built-in MCUboot support, encrypted images and anti-rollback. Works with STM32, NRF, ESP32, NXP, Silabs etc.

- **ESP-IDF Secure Boot (Free)** — https://docs.espressif.com  
  ESP32 HW Secure Boot, flash encryption, anti-rollback fuses, JTAG disable, signed OTA images. Full reference code + docs free.

- **ESP32 Flash Encryption (Free)** — part of ESP-IDF  
  AES-XTS flash encryption, secure key-generation on-chip, encrypted OTA updates, secure boot chain.

- **NRF Secure DFU (Free)** — https://www.nordicsemi.com  
  BLE & serial OTA with ECDSA-signed images, anti-rollback, key revocation. Used in wearables & medical IoT.

- **STM32 Secure Boot + SBSFU (Open Source)** — https://github.com/STMicroelectronics  
  STM32 Secure Boot & Secure Firmware Update with AES image encryption, signature verify, secure key storage and anti-rollback.

- **Microchip ATECC608A Secure Boot & OTA Reference** — https://www.microchip.com  
  Free sample firmware for secure element–based boot verification, signed images and key protection.

- **NXP Trusted Execution Environment (Free Docs)** — https://www.nxp.com  
  i.MX Secure Boot (HAB), encrypted boot images, fuse-based keys, secure JTAG, high-assurance boot ROM.

- **OpenAsymmetricFlashLoader (Open Source)** — https://github.com  
  Open secure image validation for MCUs when using external SPI flash.

- **wolfBoot (Open Source)** — https://github.com/wolfSSL/wolfBoot  
  FIPS-ready lightweight secure bootloader with RSA/ECC image signing and firmware encryption. Supports ARM, RISC-V, x86, PowerPC.

- **U-Boot Verified Boot (Open Source)** — https://github.com/u-boot  
  Uses FIT images, RSA/ECDSA signature verification, secure boot chain for Linux boards (i.MX, RK, AM335x, Zynq).

- **OP-TEE (Open Source)** — https://www.op-tee.org  
  Trusted Execution on ARMv7/ARMv8 SoCs; secure boot + trusted applications, key storage.

- **Yocto + RAUC Secure OTA (Open Source)** — https://rauc.io  
  Signed & encrypted OTA updates for Linux devices with rollback, slot management and A/B partitioning.

- **Mender OTA (Open Source Tier)** — https://mender.io  
  Secure OTA framework for Linux devices, supports signature verification, A/B updates, delta updates, rollback.

- **Hawkbit + MCUboot (Open Source)** — https://www.eclipse.org/hawkbit  
  Cloud OTA server with signed MCUboot payloads; works with STM32, NRF, ESP32, Zephyr.

- **SWUpdate (Open Source)** — https://sbabic.github.io/swupdate  
  Signed update bundles, built-in rollback, compressed & encrypted images; used in industrial Linux devices.

- **Hash-Based SW Integrity Checks (Free)**  
  SHA-256, HMAC-SHA and CRC-digests stored in boot header; basic secure-boot for resource-constrained MCUs.

- **Secure JTAG / Debug-Lock References (Free)**  
  - ESP32: eFuse JTAG lock  
  - STM32: RDP Level 2  
  - NXP: Secure JTAG challenge-response  
  Prevents firmware dumping and unsigned flashing.

### 19B. Secure Elements, TPM/HSM & Crypto Co-processors

- **Microchip ATECC608A / 608B (Trust&GO / TrustFLEX / TrustCUSTOM)** — https://www.microchip.com/en-us/solutions/security/authentication  
  I²C secure element for device identity, TLS client auth, secure boot keys, ECDSA/ECDH, AES, monotonic counters. Free Trust Platform tools, Arduino/C host libs, and PKCS#11.

- **Microchip TA100 (Trust Anchor for Automotive/Industrial)** — https://www.microchip.com/en-us/products/security/cryptoautomotive  
  I²C secure element with ECC, ECDSA/ECDH, AES-CCM/GCM, secure boot/firmware trust & CAN-FD MACs. Free host libs + security app notes.

- **Microchip Trust Platform (Provisioning)** — https://www.microchip.com/trustplatform  
  Free tooling + cloud scripts to pre-provision keys/certs into ATECC/TA100 (TNG = pre-loaded certs, TFLX = field-configurable).

- **NXP EdgeLock SE05x (SE050/SE051/SE052)** — https://www.nxp.com/edge/edgelock/se050  
  I²C secure element with ECC/RSA/Ed25519, AES-GCM/CCM, TLS offload, secure counters, filesystem; Free **Plug & Trust** middleware, PKCS#11, PSA Crypto, Zephyr/FreeRTOS ports.

- **NXP A71CH / A71XX (Legacy but common)** — https://www.nxp.com  
  Low-power ECC identity SE; free host lib and Arduino/MCU examples (use SE05x for new designs).

- **NXP EdgeLock 2GO (Provisioning)** — https://www.nxp.com/edgelock-2go  
  Free tier/device tooling to provision keys/certs remotely; sample code + scripts.

- **Infineon OPTIGA™ Trust M / Trust X** — https://www.infineon.com/optiga  
  I²C secure elements for IoT identity and TLS; ECC, ECDH, AES; free **OPTIGA Trust M host library**, mbedTLS/wolfSSL examples, AWS/BtSIG guides.

- **Infineon OPTIGA™ TPM SLB 9670 (TPM 2.0, SPI)** — https://www.infineon.com/tpm  
  Discrete TPM 2.0 for Linux/SBCs; secure storage, attestation, measured boot. Free TSS stacks (tpm2-tss), systemd/Kernel integrations.

- **Infineon OPTIGA™ Trust Charge / Authenticate** — https://www.infineon.com/optiga  
  Secure elements for USB-C PD/auth and accessory authentication; free host libs, reference code.

- **ST STSAFE-A110 / STSAFE-TPM** — https://www.st.com/stsafe  
  I²C secure elements (ECC identity, TLS, message auth) and TPM options. Free X-CUBE-STSAFE middleware and application notes.

- **Renesas (IDT) Secure Authenticators / RA TSIP** — https://www.renesas.com  
  Secure elements & MCU crypto IP (TSIP) with free drivers: AES, RSA/ECC, secure boot, key wrap.

- **Ambiq / Silabs / Nordic “Secure Vault/ARM CryptoCell”** — vendor docs  
  MCU-integrated H/W crypto (AES/SHA/ARC4/ECC), true RNG, secure key storage, anti-rollback; free SDK APIs (nRF Crypto/CC310/CC312, Silabs Secure Vault, Ambiq Secure).

- **Trusted Platform Module (TPM2) Software Stack (tpm2-tss)** — https://github.com/tpm2-software/tpm2-tss  
  Free OSS user-space stack for TPM2.0 (Linux/embedded). Includes tools (tpm2-tools) and PKCS#11.

- **wolfCrypt / wolfBoot + PKCS#11** — https://www.wolfssl.com  
  Free/open (GPLv2) crypto library + secure boot; hardware offload, TPM2/SE adapters, FIPS-ready options.

- **mbedTLS (ARM)** — https://github.com/Mbed-TLS/mbedtls  
  Free lightweight TLS/crypto with PSA Crypto API; many vendor SE/TPM integrations.

- **libsodium (NaCl)** — https://libsodium.org  
  Free modern crypto (Ed25519/X25519, AEAD) with embedded-friendly builds; refs for SE offload.

- **TinyCrypt / micro-ecc** — https://github.com/intel/tinycrypt / https://github.com/kmackay/micro-ecc  
  Free tiny ECC/AES/SHA libs for Cortex-M; commonly combined with secure elements for key isolation.

- **PKCS#11 for MCUs (ref impls)** —  
  - **AWS IoT Device SDK (Free)** with PKCS#11 ports (ATECC, SE05x, OPTIGA)  
  - **NXP Plug & Trust** PKCS#11  
  - **Infineon OPTIGA Host Lib** PKCS#11  
  Free C examples to bind TLS stacks to SE/TPM.

- **PSA Crypto / TF-M (TrustZone-M)** — https://www.trustedfirmware.org/projects/tf-m/  
  Free secure services (crypto, attestation, secure storage) for ARMv8-M; integrates MCUboot, mbedTLS, Zephyr/FreeRTOS.

- **OP-TEE (TrustZone-A)** — https://www.op-tee.org  
  Free TEE for ARMv7-A/v8-A SoCs; secure key storage, trusted apps, measured boot; U-Boot/Linux integration.

- **Secure Provisioning Services (Cloud-assisted)** —  
  - **Microchip Trust Platform** — scripts & free tools for cert/key injection  
  - **NXP EdgeLock 2GO** — device on-boarding & cert lifecycle, free tier  
  - **Infineon CIRRENT™ Cloud ID** — pre-provisioned X.509, free SDKs  
  - **ST SAFE Provisioning Guides** — scripts & X-CUBE packages

- **Reference TLS Integrations (Free)** —  
  - **ESP-IDF** mbedTLS with ATECC608/flash-enc/secure boot  
  - **Zephyr**: PSA + MCUboot + SE05x/OPTIGA samples  
  - **Linux**: OpenSSL engine for TPM2 (tpm2-engine), pkcs11-engine, systemd-cryptsetup with TPM

### 19C. Trusted Execution, Secure Debug/JTAG, Anti-Tamper & Physical Security

#### ✅ Trusted Execution Environments (TEE) & Isolation

- **ARM TrustZone-M (Free Docs & Code)** — https://developer.arm.com  
  Hardware isolation on Cortex-M33/M23 enabling “Secure” vs “Non-secure” partitions, secure boot keys, protected crypto, secure GPIO/flash/RAM.

- **TrustedFirmware-M (TF-M) (Open Source)** — https://www.trustedfirmware.org/projects/tf-m/  
  PSA-certified secure services: crypto, secure storage, attestation, protected APIs. Integrates with MCUboot, Zephyr, FreeRTOS.

- **OP-TEE (Open Source)** — https://www.op-tee.org  
  Trusted Execution Framework on Cortex-A SoCs. Used on NXP i.MX, TI AM335/AM6. Supports secure apps, key storage, secure boot + Linux.

- **M-bed PSA Crypto API (Free)** — https://github.com/Mbed-TLS/mbedtls  
  Abstract API for crypto & secure storage. Works with SE05x, OPTIGA, TPM, MCUboot.

- **RISC-V PMP / HSM Extensions (Docs & Open Examples)**  
  Physical Memory Protection, enclave-style isolation; open implementations in Tock OS and LiteX SoCs.

- **Tock OS (Open Source)** — https://www.tockos.org  
  Embedded OS with process isolation + capability-based kernel. Ideal for multi-tenant IoT devices.

- **Zephyr “TrustZone + Secure Storage + MCUboot” (Free)** — https://zephyrproject.org  
  Ready-made secure execution reference for STM32L5, NRF5340, NXP LPC55Sxx, Silabs EFR32.

#### ✅ Secure Debug, JTAG Lock, Flash Read-out Protection

- **ESP32 Secure JTAG/eFuse Lock (Free Docs)** — https://docs.espressif.com  
  JTAG can be locked using challenge-response; anti-rollback and flash encryption integrated.

- **STM32 RDP Levels (Free)** — https://www.st.com  
  Readout Protection Level 1/2 to block flash dumping; with SBSFU and OTP key storage.

- **NXP Secure JTAG (i.MX, LPC)** — https://www.nxp.com  
  Challenge-response “SJTAG” protecting debug access and memory readout.

- **Microchip PIC/AVR/SAM Lockbits (Free)** — https://www.microchip.com  
  Fuse bits prevent debug attach and flash reads.

- **Nordic nRF “APPROTECT” (Free)** — https://www.nordicsemi.com  
  Protects flash & memory regions; used in wearables, BLE beacons.

- **Raspberry Pi / Linux SBC Secure Boot + Signed Kernel**  
  With U-Boot + Verified Boot; combines TPM2 or secure element for measured boot.

- **Segger J-Link Secure Flash Loader Templates (Free)** — https://www.segger.com  
  Protects production firmware from being read during programming.

#### ✅ Anti-Tamper & Hardware Protection

- **Tamper Switches (Free Reference Designs)**  
  Open examples for micro-switch, membrane switch, Hall or light-sense tamper detection. Often tied to secure RTC or SE counter.

- **Secure Storage in SE/Microcontroller OTP**  
  ESP eFuse, STM32 OTP, NXP CAAM/OCOTP, NRF KMS — free docs on storing keys + monotonic counters.

- **Voltage/Clock Fault Injection Mitigation (Free Application Notes)**  
  - NXP, Microchip, ST publish ANs on glitch detection, voltage monitors and reset traps.  
  - On Linux SoCs: secure watchdog + tamper GPIO + monotonic counters.

- **Physical Anti-Probe Mesh (Free Guides)**  
  Application notes from Microchip/NXP/Infineon on PCB shield meshes, metal can enclosures, RF shielding, conformal coating.

- **Conformal Coating / Potting (Free Guides)**  
  Protects MCU & flash from probing; vendor free docs (HumiSeal, MG Chemicals) list PCB rules, thickness and safe compounds.

- **Secure Real-Time Clock with Tamper Inputs**  
  MCUs with RTC tamper pins can detect case opening or probing — free STM32/NXP examples.

#### ✅ Key Management & Provisioning Security

- **Provisioning Guides from Microchip/NXP/Infineon (Free)**  
  End-to-end provisioning, X.509 key injection, cert chaining, secure personalization at factory.

- **PSA Root-of-Trust Architecture Docs (Free)** — https://www.psacertified.org  
  Defines device identity, secure boot, firmware lifecycle, secure debug, attestation tokens.

- **MCU Key Derivation from PUF (Free)**  
  Intrinsic ID (PUF) whitepapers & open-source examples using SRAM startup patterns to derive device-unique keys.

- **Open-Source PKCS#11 & mbedTLS Demos**  
  Offload key storage to secure elements; prevents extraction via flash dumping or debug attach.

#### ✅ Anti-Cloning & Counterfeit Prevention

- **Unique IDs (Free Examples)**  
  STM32 UID, ESP32 MAC/EFUSE, nRF FICR UID → used as part of key derivation or licensing.

- **Message Authentication Codes**  
  Use ECC/AES keys in Secure Element for device-to-cloud authentication (free AWS/Azure/MCU SDK examples).

- **Encrypted Firmware Images**  
  ESP flash encryption, STM32 SBSFU, wolfBoot AES → free examples to protect IP.

- **Secure Boot Chains**  
  MCUboot, TF-M, U-Boot Verified Boot + OP-TEE → prevent cloned devices from running unsigned firmware.

#### ✅ Production-Level Security Checklists (Free)

- NXP, ST, Espressif, Microchip publish secure manufacturing checklists:
  - Disable debug & secure erase keys after programming  
  - Lock fuses and read-out protection  
  - Use secure OTA with signatures + anti-rollback  
  - Unique per-device keys, not shared keys  
  - Rotate certs, maintain revocation lists  
  - Protect serial ports/UART bootloaders in production

### 19D. Post-Quantum Crypto (PQC) Libraries, Tooling & Patterns

- **PQClean** — https://github.com/PQClean/PQClean  
  Free, audited, portable C implementations of NIST PQC finalists/winners (Kyber/ML-KEM, Dilithium/ML-DSA, SPHINCS+), machine-generated bindings.

- **liboqs (Open Quantum Safe)** — https://github.com/open-quantum-safe/liboqs  
  Free C library implementing KEMs (ML-KEM/Kyber, Classic McEliece, HQC) & signatures (ML-DSA/Dilithium, SPHINCS+); easy to wrap for embedded Linux gateways.

- **OQS-OpenSSL / oqs-provider** — https://github.com/open-quantum-safe/openssl  
  Free OpenSSL 3 provider to use PQC algos in TLS/X.509/CMS; supports **hybrid** key exchange/certs (e.g., X25519+ML-KEM, ECDSA+ML-DSA).

- **pqm4 (Cortex-M PQC)** — https://github.com/mupq/pqm4  
  Free, size/speed-optimized PQC implementations for ARM Cortex-M (benchmark harness + reference builds).

- **Mbed TLS (PQC forks / PSA)** — https://github.com/Mbed-TLS/mbedtls  
  Free TLS/crypto; community forks + PSA Crypto make it straightforward to plug liboqs or vendor PQC into PSA drivers.

- **wolfSSL + wolfCrypt (PQC builds)** — https://github.com/wolfSSL/wolfssl  
  Free GPL builds; commercial also available. PQC KEX/sign support via OQS integrations; good MCU footprint and FIPS options.

- **TinyCrypt / micro-ecc (classical fallback)** — https://github.com/intel/tinycrypt / https://github.com/kmackay/micro-ecc  
  Free tiny ECC/AES/SHA for hybrid deployments (classical + PQC) on very small MCUs.

- **Kyber (ML-KEM) / Dilithium (ML-DSA) / SPHINCS+ (SLH-DSA)** — https://pq-crystals.org / https://sphincs.org  
  Free reference code and papers for the NIST-standardized KEM/signature suites used in PQ TLS/OTA.

- **Classic McEliece (KEM)** — https://classic.mceliece.org  
  Free reference for code-based KEM (large pubkeys, strong long-term security; fits gateways more than tiny MCUs).

- **IETF COSE + CBOR for PQC** — https://datatracker.ietf.org/wg/cose/  
  Free specs enabling PQC signatures in COSE/CBOR (used in SUIT manifests, LwM2M objects, CBOR Web Tokens).

- **CTest/Wycheproof (classical vectors)** — https://github.com/google/wycheproof  
  Free test vectors for classical crypto; use alongside liboqs test suites for regression.

#### Practical patterns (production-friendly)
- **Hybrid TLS now:** do **X25519 + ML-KEM** key exchange and **ECDSA + ML-DSA** certs on gateways/SBCs (OQS-OpenSSL).  
- **MCUs today:** keep **classical TLS** on constrained nodes; terminate **hybrid PQ** at your **gateway** (edge proxy).  
- **Signing/OTA:** sign firmware with **ML-DSA** (or classical+PQC dual signatures) inside **COSE/SUIT**; verify on gateway/SMU or on MCU if budget allows.

### 19D. Embedded TLS & Secure Transport (MCU-friendly, Free)

- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls  
  Free, small TLS 1.2/1.3 with PSA Crypto; widely ported (Zephyr, FreeRTOS, ESP-IDF, MCUboot).

- **wolfSSL** — https://github.com/wolfSSL/wolfssl  
  Free GPL; tiny footprint TLS 1.3, DTLS 1.2, hardware crypto offload, FIPS ready; PQ via OQS integration.

- **BearSSL** — https://bearssl.org  
  Free minimal TLS for small MCUs, constant-time primitives, good for memory-tight designs (classical crypto).

- **tinyDTLS** — https://github.com/eclipse/tinydtls  
  Free DTLS 1.2 for CoAP/UDP constrained devices.

- **gnutls / OpenSSL (SBC/Gateway)** — https://www.gnutls.org / https://www.openssl.org  
  Free full-fat TLS for embedded Linux; use **OQS-OpenSSL** to enable PQC/hybrid.

- **Noise Protocol Framework (C)** — https://github.com/rweather/noise-c  
  Free lightweight AKE for device-to-device links; classical today, easy to adapt to PQ KEMs in gateways.

### 19D. IoT Security Frameworks, Manifests & Identity (Free)

- **IETF SUIT Manifests (Firmware Updates)** — https://datatracker.ietf.org/wg/suit/  
  Free standard for signed firmware metadata (COSE/CBOR), rollback protection; works with MCUboot/Zephyr/Mender/RAUC.

- **PSA Certified / TF-M** — https://www.psacertified.org / https://www.trustedfirmware.org  
  Free secure-by-design framework (Root of Trust, attestation, secure storage) for Cortex-M; integrates MCUboot + Mbed TLS.

- **FDO (FIDO Device Onboard)** — https://fidoalliance.org  
  Free/on-prem provisioning protocol for zero-touch onboarding; device credentials + supply-chain integrity.

- **LwM2M (OMA) + Security Objects** — https://www.openmobilealliance.org  
  Free device management with DTLS/OSCORE and SUIT integration; supports cert-based or PSK flows, CBOR payloads.

- **Matter / Thread Security** — https://csa-iot.org  
  Free specs for smart-home with CASE/PASE, operational certs (PAI/DA model); good reference for consumer IoT identity.

- **OPC UA (open62541)** — https://github.com/open62541/open62541  
  Free industrial protocol with security profiles, certs, and PubSub; usable on gateways/SBCs.

- **OSCORE / EDHOC (IETF)** — https://datatracker.ietf.org/wg/lake/  
  Free object security for CoAP (OSCORE) and lightweight AKE (EDHOC); ideal for constrained nodes with CBOR/COSE.

### 19D. Key Management, APIs & Secure Storage (Free)

- **PKCS#11** — ubiquitous C API for keys/certs; vendor SE/TPM stacks provide free PKCS#11 modules.

- **PSA Crypto API** — unified crypto/key store interface for MCUs (TF-M, Mbed TLS); makes swapping classical→PQC easier later.

- **TPM2-TSS + tpm2-tools** — https://github.com/tpm2-software/tpm2-tss  
  Free user-space stack/tools for TPM 2.0 (attestation, sealed storage, measured boot) on gateways.

- **Secure Elements (SE05x / OPTIGA / ATECC)** — free host libs & PKCS#11 adaptors; isolate TLS/PQC keys from MCU flash.

### 19D. Migration Playbook (concise)

1) **Segment:** keep tiny MCUs on classical TLS; terminate **hybrid PQ TLS** at an **edge gateway**.  
2) **Manifests:** move firmware signing to **COSE/SUIT**; pilot **ML-DSA** signatures alongside ECDSA.  
3) **Identity:** use **PKCS#11/PSA** so keys can live in **SE/TPM**; plan for PQ certs later (OQS-X.509).  
4) **Transport:** enable **OQS-OpenSSL** on Linux gateways (hybrid KEX today).  
5) **Bench:** use **pqm4** + **PQClean** to measure MCU timing/flash; define per-SKU cut-offs (which devices can verify PQC on-device).  
6) **Rollout:** start with **gateway-only PQC**, then migrate higher-resource endpoints; retain rollback-safe classical fallback.  


### 19D. Post-Quantum Cryptography (PQC), Secure Elements & Hardware Root-of-Trust

#### ✅ Post-Quantum Crypto Libraries (Free & Open-Source)

- **Open Quantum Safe (OQS) Project** — https://openquantumsafe.org  
  Open-source PQC algorithms (Dilithium, Kyber, Falcon) integrated with OpenSSL and liboqs for MCUs, Linux gateways and cloud backends.

- **CRYSTALS-Kyber & Dilithium (NIST PQC Winners)** — https://pq-crystals.org  
  Reference C implementations, test vectors, KEM + signatures. Free for academic and commercial use.

- **PQClean (Portable C Implementations)** — https://github.com/PQClean/PQClean  
  Clean, portable, auditable implementations of all NIST Round 3 PQC schemes, targeting small microcontrollers.

- **MBedTLS + PQC (Community Ports)** — https://github.com/Mbed-TLS/mbedtls  
  Community extensions to integrate PQC KEMs/signatures into TLS/DTLS, suitable for constrained nodes.

- **WolfSSL PQC Support (Free Tier / GPL)** — https://www.wolfssl.com  
  Falcon/Kyber integrated into TLS 1.3, DTLS, secure boot examples for embedded Linux and RTOS devices.

---

#### ✅ Secure Elements & Hardware Roots of Trust (Free SDKs)

- **NXP SE050 & EdgeLock SE** — https://www.nxp.com  
  PQC-ready key storage, ECDSA/ECDH, AES/GCM, TLS offload. Free host libraries + reference firmware.

- **Infineon OPTIGA Trust M / Trust X** — https://www.infineon.com  
  Secure key storage, attestation, X.509 handling. Free Arduino, STM32, ESP32 libraries.

- **Microchip ATECC608A** — https://www.microchip.com  
  Crypto co-processor with secure key storage, ECC, TLS, JWT. Free CryptoAuthLib, I2C secure element drivers.

- **Intel TPM2 / Linux TPM Software Stack (TSS)** — https://github.com/tpm2-software  
  Full open-source TPM2 stack for Linux SBCs, gateways and edge servers.

- **Azure / AWS Secure Element Reference Designs**  
  Free MCU SDKs showing secure onboarding and attestation via ATECC/SE05x.

---

#### ✅ Secure Bootloaders with PQC or Modern Crypto

- **MCUboot (Open Source)** — https://www.mcuboot.com  
  Image authentication, anti-rollback, RSA/ECC support; community PQC forks emerging.

- **wolfBoot (Open Source)** — https://www.wolfssl.com/products/wolfboot/  
  Lightweight bootloader for Cortex-M, RISC-V. Secure boot, encrypted images, rollback protection. GPL + commercial license.

- **ARM TF-M + Bootloader Stack** — https://www.trustedfirmware.org  
  Secure boot chain + attestation + protected storage, runs on TrustZone-M MCUs.

- **U-Boot Verified Boot (Open Source)** — https://source.denx.de/u-boot/u-boot  
  Signed kernels, FIT images, measured boot with TPM2 on Linux SBCs and gateways.

---

#### ✅ PQC in IoT Protocols (MQTT, CoAP, TLS/DTLS)

- **mosquitto + OQS-OpenSSL (Free)** — https://mosquitto.org  
  MQTT broker compiled with PQC-OpenSSL adds PQC-TLS for IoT device authentication.

- **mbedTLS + PQC (Community Ports)** — https://github.com/Mbed-TLS/mbedtls  
  Used with Zephyr/FreeRTOS to build PQC-TLS clients for MCUs (<256KB RAM cases shown).

- **WolfSSL PQC-TLS** — https://www.wolfssl.com  
  PQC handshake + hybrid modes (ECDH + Kyber) for embedded Linux and gateways.

- **Zephyr + OQS** — https://github.com/zephyrproject-rtos  
  Community integrations for PQC-TLS with constrained IoT endpoints.

---

#### ✅ Device Attestation & Identity

- **FIDO Device Onboard (FDO) Open Source** — https://fidoalliance.org  
  Secure onboarding for IoT devices without shared secrets. Free specs + reference stacks.

- **DICE (Device Identity Composition Engine)** — https://trustedcomputinggroup.org  
  Hardware-anchored identity for MCUs without TPMs. Free open specifications + C examples.

- **EAT / CWT Token Attestation** — https://www.ietf.org  
  Free IETF standards for attestation tokens on constrained devices (CBOR based).

---

#### ✅ Open Hardware HSM / Crypto Projects

- **Tillitis TKey (Open Hardware)** — https://tillitis.se  
  Open-source hardware security token with verifiable firmware.

- **Nitrokey (Open Hardware)** — https://www.nitrokey.com  
  Secure storage, FIDO2, encrypted mass storage. Open firmware + schematics.

- **SoloKey (Open Hardware)** — https://solokeys.com  
  FIDO2/U2F keys with open MCU firmware and USB interfaces.

---

#### ✅ Reference Threat Models & Security Guidance (Free)

- **PSA Certified Threat Models** — https://www.psacertified.org  
  Free security models for IoT endpoints, gateways and industrial devices.

- **IoT Security Foundation Best Practices** — https://iotsecurityfoundation.org  
  Free compliance checklists, secure lifecycle guidance.

- **ENISA Hardware Security Guidelines (Free PDF)** — https://www.enisa.europa.eu  
  Guidance on supply chain, PCB probing, side-channel, secure debug, fault injection.

- **NIST 800-193 Platform Firmware Resilience** — https://csrc.nist.gov  
  Free guidance on secure boot, measured boot and recovery.


### 20A. TinyML Frameworks & Libraries

- **TensorFlow Lite for Microcontrollers (TFLM)** — https://www.tensorflow.org/lite/microcontrollers  
  Google’s ultra-light inference engine for MCUs (as low as ~16–32KB RAM). Free, open-source, supports CMSIS-NN, ESP32, NRF, STM32, RP2040.

- **Edge Impulse Open-Source Inference SDK** — https://docs.edgeimpulse.com  
  Fully free inference SDK with DSP blocks for audio, vibration, IMU, keyword spotting and vision. Runs on Cortex-M, ESP32, K210, Linux.

- **microTVM (Apache TVM Project)** — https://tvm.apache.org  
  Compiler stack that generates highly optimized MCU inference code for NPUs/DSPs. Open-source, Python toolchain for edge deployment.

- **CMSIS-NN (Arm)** — https://github.com/ARM-software/CMSIS-NN  
  Optimized neural network kernels for Cortex-M DSP extensions, improving inference speed and memory footprint. 100% free.

- **uTensor (Arm Mbed)** — https://github.com/uTensor/uTensor  
  Minimalistic inference engine for ARM Cortex-M with static memory allocation. Integrated with Mbed. Completely open-source.

- **STM X-CUBE-AI** — https://www.st.com/en/embedded-software/x-cube-ai.html  
  Model converter generating C inference code for STM32 MCUs. Free ST toolchain, supports Keras/TFLite/ONNX.

- **Espressif ESP-DL** — https://github.com/espressif/esp-dl  
  Optimized NN operators and quantizers for ESP32 series (ESP32-S3 vector acceleration). Open-source, TinyML friendly.

- **Sony Neural Network Console for Microcontrollers** — https://dl.sony.com/  
  Free model conversion tool for Sony Spresense (CXD5602). Generates MCU-optimized inference code.

- **NXP eIQ ML Software** — https://www.nxp.com/design/software/development-software/eiq-ml-software:eIQ  
  Free inference runtime for i.MX RT and MCUs; integrates TFLM and CMSIS-NN. Supports voice/vision pipelines.

- **Himax WE-I Plus SDK** — https://www.himax.com.tw/products/ai-sensing/  
  Always-on low-power vision MCU with free SDK + sample TinyML vision models.

- **Kendryte K210 / MaixPy AI Runtimes** — https://github.com/kendryte  
  RISC-V SoC with hardware KPU accelerator; free SDK, examples for face detection, KWS, object recognition.

### 20C. AutoML, Edge Training, Quantization & Optimization Tools (Free tiers)

- **Edge Impulse Studio (Free Tier)** — https://edgeimpulse.com  
  Cloud AutoML for signal processing + classification + regression. Free tier: unlimited projects, dataset tools, DSP blocks, on-device deployment (MCU, ESP32, K210, Linux).

- **SensiML Analytics Toolkit (Community Edition)** — https://sensiml.com  
  Free tier for small datasets and IMU/gesture recognition pipelines. Export firmware for Cortex-M & ESP32.

- **Qeexo AutoML (Trial/Academic Tier)** — https://qeexo.com  
  Drag-and-drop sensor pipeline, feature extraction, and model training. Deploy to Cortex-M0/M3/M4/M7.

- **ONNX Runtime for Mobile (Free)** — https://onnxruntime.ai  
  Compress and optimize models (quantization, pruning) for ARM Cortex-A/Linux SBCs. Free + open-source.

- **NVIDIA TAO Toolkit (Community)** — https://developer.nvidia.com/tao  
  Transfer learning and AutoML with edge deployments. Free for Jetson devices.

- **OpenVINO Toolkit (Free)** — https://docs.openvino.ai  
  Optimizes TFLite/ONNX models for Intel edge devices with quantization, pruning, NPU acceleration. Free, open-source tools.

- **TensorFlow Model Optimization Toolkit** — https://www.tensorflow.org/model_optimization  
  Quantization-aware training, pruning, clustering to reduce size for MCUs and NPUs. Fully free.

- **TensorFlow Lite Model Maker** — https://www.tensorflow.org/lite/models/modify/model_maker  
  No-code transfer learning for image/audio/text datasets. Exports TFLite & TFLite Micro models free.

- **MLIR (Compiler for Edge Inference Optimization)** — https://mlir.llvm.org  
  Open-source compiler used in TFLite and TVM to reduce RAM/flash footprints for edge hardware.

- **Apache TVM AutoScheduler / Autoscaling (Free)** — https://tvm.apache.org  
  Automatically produces optimized inference kernels for ARM MCUs, NPUs, DSPs. Fully open-source.

- **Google Model Search (AutoML - Open Source)** — https://github.com/google/model_search  
  Automatic architecture search to generate compressed models for edge. Open-source.

- **Larq / BNN Quantization (Free)** — https://larq.dev  
  Binarized neural networks (1-bit weights) for ultra-low-memory inference on MCUs. Fully open-source.

- **Neural Magic Deepsparse (Free Community)** — https://neuralmagic.com  
  Model sparsification + quantization for edge CPUs. Free tier + open-source runtime.

- **Hummingbird (Microsoft)** — https://github.com/microsoft/hummingbird  
  Converts ML models (sklearn/xgboost) into tensor operations for efficient MCU/SBC inference. Free + open-source.

- **Micromlgen (Arduino + TinyML)** — https://micromlgen.surigao.xyz  
  Auto-generates MicroPython/C code from scikit-learn models. Free.

- **Neuton TinyML (Free Tier)** — https://neuton.ai  
  No-code AutoML that generates tiny neural networks (<10KB). Free plan allows unlimited MCUs.

- **AIfES (Artificial Intelligence for Embedded Systems)** — https://github.com/Fraunhofer-IMS/AIfES  
  Train small neural networks directly on microcontrollers. Open-source.

- **OpenML Datasets & AutoML Tools** — https://www.openml.org  
  Free datasets, AutoML runners, pre-processing pipelines for TinyML research.

- **Google Colab (Free GPU/CPU notebooks)** — https://colab.google  
  Free cloud compute for training quantized TinyML models and exporting TFLite Micro binaries.

- **NXP eIQ Portal (Free with NXP Boards)** — https://www.nxp.com  
  Model training, quantization, dataset tools for i.MX and RT MCUs. Free when using NXP devkits.

- **ST-AI Model Zoo + STM32 AIRunner (Free)** — https://www.st.com/en/embedded-software/x-cube-ai.html  
  Auto quantization + C code generator for STM32 MCUs. Free for ST hardware.

### 20D. AI-Optimized Hardware / Accelerators (Free SDKs, Toolchains & Model Compilers)

- **Google Coral Edge TPU (USB, PCIe, SOM)** — https://coral.ai  
  Ultra-low-power TPU for edge vision and NN inference. Free TensorFlow compiler + Python/C++ runtime.

- **Kendryte K210 / Sipeed MAiX** — https://github.com/kendryte  
  RISC-V SoC with KPU NPU accelerator. Free SDK, NN compilers, and MaixPy firmware for image/audio ML.

- **Espressif ESP32-S3 / ESP32-C6 AI Acceleration** — https://github.com/espressif/esp-dl  
  Vector instructions for vision/audio ML. Free ESP-DL library + TFLM example models.

- **Himax WE-I Plus AI MCU** — https://www.himax.com.tw/products/ai-sensing/  
  Ultra-low-power always-on vision/audio MCU. Free SDK, sample models, and open reference firmware.

- **STM32H7 + STM32 X-CUBE-AI** — https://www.st.com/en/embedded-software/x-cube-ai.html  
  Converts Keras/TF/ONNX models into optimized STM32 inference C code. Free tool with ST boards.

- **NXP i.MX RT + eIQ ML** — https://www.nxp.com  
  MCU/MPU inference with DSP acceleration and quantization. Free eIQ SDK & model zoo for i.MX RT/MPUs.

- **Hailo-8 / Hailo-10 Edge AI Modules** — https://hailo.ai  
  PCIe and SOM accelerators with free compiler + model zoo. Efficient for real-time vision and detection.

- **Intel Movidius Myriad X (Neural Compute Stick 2)** — https://software.intel.com/openvino  
  USB edge inference accelerator. Free OpenVINO toolkit, quantization and high-performance CV kernels.

- **Nordic Thingy:53 + Edge Impulse** — https://www.nordicsemi.com  
  BLE/IMU platform with nRF5340 dual-core + free Edge Impulse deployment.

- **Sipeed RV Boards with K210/K510** — https://wiki.sipeed.com  
  Affordable RISC-V NPUs. Free MaixPy + NNCase model converter.

- **Sony Spresense (CXD5602)** — https://developer.sony.com  
  Multi-core MCU with DSP audio pipeline. Free Neural Network Console for model export.

- **Qualcomm QCS610/QCS612 Snapdragon Edge Kits** — https://developer.qualcomm.com  
  AI camera modules for low-power vision. Free Snapdragon Neural Processing SDK.

- **OpenMV H7 / RT / K210 Boards** — https://openmv.io  
  Vision-focused MCU boards with free OpenMV IDE, NN support (TFLM/KPU) and camera drivers.

- **Raspberry Pi + HW NN Accelerators**  
  Pi + Coral USB/PCIe + Myriad X, all with free compilers and TFLite/ONNX support.

- **Microchip PolarFire SoC FPGA** — https://www.microchip.com  
  RISC-V + FPGA fabric enables hardware ML accelerators. Free Libero IDE (base edition) + open reference designs.

- **GreenWaves GAP8/GAP9** — https://greenwaves-technologies.com  
  Ultra-low-power parallel compute MCUs for vision/audio TinyML. Free GAP SDK and NN toolchains.

- **Rockchip RK3588 / RK3399 NPU Boards**  
  Vision NPUs with free RKNN Toolkit to convert ONNX/TFLite/PyTorch to NPU kernels.

- **Kneron KL520 Edge AI Modules** — https://www.kneron.com  
  Low-power vision recognition accelerators. Free model compiler + SDK.

- **ADI MAX78000 AI MCU** — https://www.analog.com  
  Ultra-low-power MCU with CNN accelerator. Free Model Compiler and reference CNNs.

- **Syntiant NDP120 Always-On Audio AI Chips** — https://www.syntiant.com  
  Tiny always-on speech/wake-word acceleration. Free SDK for supported devkits.

- **ENSEMBLE / Sipeed RVV Boards (RVV Vector AI)** — https://sipeed.com  
  RISC-V Vector ISA acceleration for ML. Free toolchains + demos.

### 21A. Robotics Frameworks, OS & Control Stacks (Free / Open-Source)

- **ROS 2 (Robot Operating System)** — https://ros.org  
  Industry-standard robotics framework with navigation, SLAM, sensor fusion, path planning, ROS middleware (DDS). Free + open-source.

- **micro-ROS (ROS2 for MCUs)** — https://micro-ros.github.io  
  ROS 2 client stack for Cortex-M & RTOS systems (Zephyr, FreeRTOS, NuttX). Free; integrates with STM32, ESP32, NXP, Microchip.

- **PX4 Autopilot** — https://px4.io  
  Open-source flight-control stack for drones, ground vehicles and marine robots. Supports GPS/IMU fusion, autopilot, MAVLink. Free.

- **ArduPilot** — https://ardupilot.org  
  Autopilot/robotics firmware for fixed-wing, multicopters, cars, boats, submarines. Open-source, runs on STM32 and Linux SBCs.

- **Open Robotics Navigation Stack** — https://navigation.ros.org  
  Full ROS2 navigation system: localization, obstacle avoidance, mapping, path planning. Free.

- **MoveIt! Motion Planning** — https://moveit.ros.org  
  Robot arm manipulation, IK, planning, collision detection. Free ROS2 integration.

- **Gazebo / Ignition Robotics Simulator** — https://gazebosim.org  
  Free, open-source 3D physics simulator for robots, SLAM, testing motor control and sensor systems.

- **Webots Robotics Simulator** — https://cyberbotics.com  
  Professional robotics simulator with physics, sensors, ROS — free open-source edition.

- **MAVSDK & MAVROS** — https://mavsdk.mavlink.io  
  MAVLink-based control libraries for drones/UGVs. Free C++/Python APIs.

- **Open-RMF (Robotics Middleware Framework)** — https://open-rmf.org  
  Fleet management for AMRs, AGVs, delivery robots — traffic control, maps, routing. Free & open-source.

- **OpenCV Robotics Modules** — https://opencv.org  
  Computer vision for robotics: feature detection, optical flow, SLAM components, stereo depth. Fully open-source.

- **Orocos Kinematics & Control** — https://orocos.org  
  Real-time robot control & kinematics framework used in industrial arms. Free & open-source.

- **Cartographer (Google SLAM)** — https://cartographer.io  
  2D/3D SLAM, LIDAR mapping and localization. Free open-source library.

- **RPLIDAR & Slamtec Toolchains (Free)** — https://www.slamtec.com  
  Free SDKs for cheap LIDAR sensors used in robotics and SLAM.

- **TurtleBot 3 Ecosystem** — https://turtlebot3.robotis.com  
  Open-source mobile robot platform based on ROS. Free firmware, CAD, and control stacks.

- **OpenManipulator** — https://emanual.robotis.com/docs/en/platform/openmanipulator/  
  Open-source robotic arm with free firmware, ROS interfaces and kinematics.

- **NVIDIA Isaac ROS (Free Container Images)** — https://developer.nvidia.com/isaac-ros  
  Optimized ROS2 packages for Jetson robots: perception, depth mapping, SLAM, DNN inference acceleration.

### 21B. Motor Drivers, BLDC/Stepper Control & FOC Libraries (Free / Open-Source)

- **SimpleFOC (Arduino + STM + ESP)** — https://simplefoc.com  
  Open-source FOC motor control for BLDC, gimbal and stepper motors. Free drivers for AS5600, MA730, and common motor drivers.

- **ST Motor Control SDK (X-CUBE-MCSDK)** — https://www.st.com  
  Free FOC, sensorless control, PMSM/BLDC, auto-tuning + GUI Workbench. Runs on STM32F0/F3/F4/F7/G4/H7.

- **TI InstaSPIN-FOC (LaunchPad)** — https://www.ti.com/tool/INSTASPIN-MOTION  
  Sensorless FOC with auto-ID of motor parameters. Free for TI C2000 LaunchPads.

- **Microchip MotorBench Development Suite** — https://www.microchip.com  
  Free tool for PMSM parameters, sensorless tuning and code generation for dsPIC & SAM MCUs.

- **Trinamic TMC Drivers (Eval Tools & APIs)** — https://www.analog.com/en/parametricsearch/11776#/  
  Free stepper/servo control tools, SPI/UART config, FOC drivers. Widely used in 3D printers, robotics.

- **Odrive Firmware (Open-Source)** — https://odriverobotics.com  
  High-performance BLDC servo controller firmware. Supports robotics, CNC, mobility robots.

- **FOC with Field-Oriented Library (NXP FreeMASTER)** — https://www.nxp.com  
  Free PMSM/BLDC control with FreeMASTER real-time tuning and motor observer algorithms.

- **DRV8xxx EVM Firmware (TI)** — https://www.ti.com  
  Free firmware + MCC scripts for TI motor drivers (stepper/brushless/BDC) for robotics and gimbals.

- **Mechaduino Open-Source Servo Stepper** — https://github.com/jcchurch/Mechaduino-Firmware  
  Turns stepper motors into closed-loop servos using STM32. Free firmware and hardware files.

- **Hoverboard BLDC Open Firmware** — https://github.com/EmanuelFeru/hoverboard-firmware-hack  
  Open BLDC controller for hoverboard motors (FOC, torque mode, steering). Used by DIY robots and AGVs.

- **VESC Tool (Benjamin Vedder)** — https://vesc-project.com  
  Open-source BLDC/FOC motor control for e-bikes, robotics, skates, AGVs. Free tuning + telemetry.

- **DRV8313/DRV8305/DRV8323 Sensorless FOC Examples** — https://www.ti.com  
  Free TI example firmware + motor SDK integration for BLDCs.

- **ST B-GW-FOC Reference Designs** — https://www.st.com  
  Hardware + firmware reference for drone BLDCs, PMSM robotics, and gimbal stabilization.

- **TMCStepper (Arduino Library)** — https://github.com/teemuatlut/TMCStepper  
  Open-source SPI/UART control for Trinamic drivers (TMC2130/2209/5160). Free for 3D printers and robots.

- **DRVStep (Open Source Stepper Control)** — https://github.com/DRV-STEP  
  Community project for precise stepper control with microstepping and stall detection.

- **OpenServo (Open Firmware for Hobby Servos)** — https://github.com/lnlp/OpenServo  
  Replaces hobby servo firmware with open closed-loop control.

- **Gimbal-FOC Open Firmware** — https://github.com/simplefoc/  
  Lightweight FOC control for camera gimbals and stabilization systems.

- **Roboteq Free Evaluation Firmware** — https://www.roboteq.com  
  Free firmware for BLDC/DC motor controllers used in AGVs and mobile robots.

- **Infineon Motor Control ICs (Free ModusToolbox SDK)** — https://www.infineon.com  
  Free firmware libraries for BLDC, stepper, PFC stages, with FOC support.

- **Atmel/Microchip Motor Control Apps** — https://www.microchip.com  
  Free app notes + code examples for dsPIC, SAMD, and AVR BLDC/FOC/stepper control.

- **OpenModelica + Motor Simulation (Free)** — https://openmodelica.org  
  Simulate motor dynamics and control loops before firmware deployment.

### 21C. Servo Control, Encoders, Kinematics & Trajectory Libraries (Free / Open-Source)

- **ROS-Control & ros2_control** — https://github.com/ros-controls/ros2_control  
  Standardized hardware abstraction for servo drives, joint control, feedback loops, PID, and trajectory controllers. Free and widely used in robots/AMRs.

- **MoveIt Kinematics + IKFast** — https://moveit.ros.org  
  Generates kinematic solvers (FK/IK) from robot geometry. Free solver code for manipulators and robotic arms.

- **OROCOS KDL (Kinematics and Dynamics Library)** — https://orocos.org/kdl.html  
  High-performance forward and inverse kinematics, Jacobians, dynamics, chain solvers. Open-source, C++.

- **Ruckig (Real-time Motion Planner)** — https://github.com/pantor/ruckig  
  Real-time jerk-limited trajectory generation for robotic arms, CNC, 3D printers, and AGVs. Free MIT license.

- **Trapezoidal & S-curve Profiling (OpenLib)** — https://github.com/madcowswe/ODrive  
  ODrive firmware includes free motion profiling for smooth servo moves.

- **EtherCAT Servo Stack (SOEM)** — https://github.com/OpenEtherCATsociety/SOEM  
  Free EtherCAT master used for industrial servo drives, CNC, humanoid robots.

- **SimpleFOC Encoder + Magnetic Sensor Drivers** — https://simplefoc.com  
  Free AS5048, AS5600, MT6701, ABI, SPI encoder libraries for BLDC and stepper feedback.

- **AS5600/AS5048 Arduino Libraries (Free)** — https://github.com/ajfisher  
  Free open-source magnetic encoder drivers, used in robotics and manipulators.

- **OpenServo** — https://github.com/lnlp/OpenServo  
  Open-source firmware replacing RC servo internals with closed-loop control.

- **Dynamixel SDK (Free)** — https://emanual.robotis.com  
  Free cross-platform SDK for Dynamixel servos: torque control, PID, synchronous multi-servo motion.

- **Mechaduino Servo Firmware** — https://github.com/jcchurch/Mechaduino-Firmware  
  Stepper → servo conversion with encoder feedback and closed-loop control. Free hardware + firmware.

- **Teensy Encoder / FastEncoder libs** — https://github.com/PaulStoffregen/Encoder  
  Free, high-speed quadrature decoding for robotic wheels and CNC spindles.

- **OpenIMU API** — https://developers.aceinna.com  
  Real-time orientation and INS, used for balancing robots and navigation. Free API + calibration tools.

- **Trajectory Planner for 3D Printers & CNC (Marlin / Klipper)** — https://github.com/MarlinFirmware/Marlin  
  Open-source jerk-limited motion planner used in 3D printers and CNC bots.

- **Open Motion Planning Library (OMPL)** — https://ompl.kavrakilab.org  
  Sampling-based motion planning: RRT, PRM, etc. Free and widely integrated with ROS.

- **Realtime EtherCAT for Linux (Free)** — https://github.com/OpenEtherCATsociety/SOEM  
  Allows multi-axis industrial servo drives and synchronized motion.

- **SymPy Robotics Kinematics Toolkit (Python)** — https://github.com/cdsousa/SymPyBotics  
  Symbolic FK/IK for robotic arms. Open-source.

- **OpenRAVE** — http://openrave.org  
  Full motion planning + IK library for manipulators. Open-source.

- **Robotics Toolbox for Python (Peter Corke)** — https://github.com/petercorke/robotics-toolbox-python  
  Kinematics, trajectory generation, dynamics, simulation. Free & research-grade.

### 22A. IMU, AHRS, Orientation & Sensor Fusion (Free / Open-Source)

- **Madgwick AHRS Filter (MIT License)** — https://x-io.co.uk/open-source-imu-and-ahrs-algorithms/  
  Ultra-lightweight quaternion-based AHRS for IMUs. Works on 8-bit/32-bit MCUs. Free source in C/C++/Python.

- **Mahony Filter (Open-Source)** — https://x-io.co.uk/open-source-imu-and-ahrs-algorithms/  
  Low-compute AHRS for robots, gimbals, drones. Free implementations for ARM/Arduino.

- **OpenIMU (Aceinna)** — https://developers.aceinna.com  
  INS fusion, GPS, IMU calibration, open C firmware, and free web tools for data logging + tuning.

- **ST MotionFX Library (Free)** — https://www.st.com  
  Free orientation, 6-axis/9-axis fusion, pedometer, tilt, quaternion outputs for STM32.

- **Bosch BNO055 & BHI260 + BSEC Lite** — https://www.bosch-sensortec.com/software-tools  
  On-sensor fusion with free drivers + BSEC Lite for air quality / CO2-equivalent fusion. Free SDK.

- **Google Cartographer IMU Integration (Open-Source)** — https://cartographer.io  
  Real-time 2D/3D SLAM using IMU, LIDAR and wheel odometry. Free C++ library.

- **Open-source PX4 EKF2 / IMU Fusion** — https://px4.io  
  Extended Kalman Filter for drones and mobile robots. Free code for IMU + GPS + barometer fusion.

- **Kalman Filter Library in C (Free)** — https://github.com/insane-adding-machines/kalman  
  Lightweight KF implementations for embedded IMU fusion and smoothing.

- **TinyEKF (C)** — https://github.com/simondlevy/TinyEKF  
  Small-footprint EKF library for IMU and INS on MCUs/Arduino/STM32.

- **uNav INS / Fusion for UAVs (Open-Source)** — https://github.com/rosflight  
  IMU + barometer + GPS fusion for flight controllers. Free C/C++ implementation.

- **RTIMULib (Open-Source) IMU Fusion** — https://github.com/richards-tech/RTIMULib2  
  Sensor fusion, IMU calibration, magnetometer offsets. Works on Linux SBCs and embedded.

- **Arduino_LSM9DS1 / LSM6DS3 / BMI160 Drivers (Free)** — https://github.com/arduino-libraries  
  Sensor fusion and orientation examples for Arduino boards.

- **MSP430 + TI Sensor Fusion Library (Free)** — https://www.ti.com  
  IMU sensor fusion and tilt detection for low-power robotics and wearables.

- **InvenSense MotionDriver & DMP Firmware** — https://invensense.tdk.com  
  Free SDK with on-chip fusion for MPU6050/9250/ICM-20xxx; calibrations and quaternion output.

- **ROS IMU Tools** — https://github.com/ccny-ros-pkg/imu_tools  
  Free IMU filters, calibration and data conversion for ROS robots.

- **OpenSensorHub (OSH)** — https://opensensorhub.org  
  Distributed sensor fusion platform for UAVs, robots and geospatial sensors; free and open-source.

- **OpenRTK (Aceinna)** — https://developers.aceinna.com  
  Open-source RTK-GNSS + IMU fusion for ground robots and AGVs. Free reference software.

- **FilterPy (Python)** — https://github.com/rlabbe/filterpy  
  KF, EKF, UKF implementations used for IMU and INS prototyping. Free MIT license.

- **IMU Calibration Tool (Free)** — https://github.com/zulns  
  Open-source IMU calibration scripts for bias, scale, alignment, magnetometer distortion.

### 22B. Environmental, Air Quality, Gas, Industrial Sensors (Free SDKs, Docs, Tools)

- **Bosch BSEC Lite (Environmental Fusion)** — https://www.bosch-sensortec.com/software-tools  
  Free SDK for BME680/BME688 providing IAQ, CO2-equivalent, humidity, temperature, breath/VOC detection.

- **Bosch BME AI-Studio for BME688** — https://www.bosch-sensortec.com/software-tools  
  Free machine-learning tool for gas classification (cooking, smoke, VOC patterns). Export C firmware for MCUs.

- **Sensirion Environmental Sensor SDKs** — https://sensirion.com  
  Free drivers and calibration code for SHT humidity, SPS PM2.5, SCD CO2 sensors. Open-source C/C++.

- **SGP40/SGP30 Air Quality Reference Drivers (MIT)** — https://github.com/Sensirion  
  Free C drivers + algorithms for VOC index and air quality estimation.

- **Plantower PMS / Nova PM Lidar Sensors** — https://github.com/avaldebe/AQmon  
  Free open-source PMS/PM1006/PM5003 drivers and data logging tools.

- **Honeywell Air Quality Sensor SDKs (Free)** — https://sensing.honeywell.com  
  Free Python/C driver examples for CO2, PM, toxic gas sensors.

- **Amphenol CCS811 + iAQ-Core Drivers** — https://github.com/adafruit/Adafruit_CCS811  
  Free, open-source drivers for low-power CO2/VOC sensors used in smart indoor systems.

- **MQ Series Gas Sensors (Open Libraries)** — https://github.com/swatish17/MQSensorLib  
  Free calibration + heater compensation libraries for MQ-2/3/4/7/135 etc.

- **Infineon XENSIV Sensors** — https://github.com/Infineon  
  Free SDKs for PAS CO2, DPS barometric sensors, radar presence sensors.

- **Texas Instruments HDC3xxx & TMP Series** — https://www.ti.com  
  Free code examples for humidity/temperature with calibration and drift correction.

- **ST HTS221 / LPS22HB Drivers** — https://github.com/STMicroelectronics  
  Official free drivers for humidity, pressure, temperature sensors.

- **SparkFun / Adafruit Sensor Libraries (Open-Source)** — https://github.com/sparkfun / https://github.com/adafruit  
  Free Arduino + Python drivers for hundreds of environmental sensors (TVOC, eCO2, PM2.5, barometer, UV).

- **UV Index / Radiation Sensor Drivers (Open-Source)**  
  VEML6075, SI1133, GUVA-S series — free drivers on GitHub for Arduino/STM32/ESP32.

- **Weather Station Reference Projects (Free)** — https://github.com/adafruit/Adafruit_Weather_Station  
  Free firmware + sensor examples for met stations using BME280 + wind/rain gauges.

- **Industrial Temperature & PT100/RTD Amplifier Libraries** — https://github.com/adafruit/MAX31865  
  Free open-source libraries for MAX31865/RTD/PT100/PT1000 amplifiers.

- **Gas & Industrial Sensing Datasets (Free)** — https://archive.ics.uci.edu  
  Open datasets (gas leakage, air quality, VOC patterns) for calibration and TinyML training.

- **Water Quality Sensor Libraries (pH/ORP/TDS)** — https://github.com/DFRobot  
  Free C/C++/Arduino drivers for pH, conductivity, dissolved oxygen, turbidity.

- **SEAL Environmental Sensor Suite (Open Tools)** — https://github.com/SEAL-Project  
  Open-source environmental sensing and calibration toolchain.

- **Smart Dustbin / IAQ Open-Source Projects**  
  Free ESP32/Arduino IAQ systems: PMS5003 + CCS811 + BME680 dashboards.

- **Modbus Industrial Sensor Examples (Free)** — https://github.com/arduino-libraries/ArduinoModbus  
  Open-source drivers to read industrial air-quality probes via RS485.

- **OpenLog Environmental Logging Tools** — https://github.com/sparkfun/OpenLog_Artemis  
  Free data logger firmware for PM + CO2 + weather sensors.

### 22C. Vision, Depth Cameras & Edge CV SDKs (Free / Open-Source)

- **OpenCV (Computer Vision Library)** — https://opencv.org  
  The standard CV toolkit: object tracking, feature detection, SLAM building blocks, OCR, DNN. Free and open-source (C++/Python/MCU ports).

- **OpenMV Camera Boards** — https://openmv.io  
  STM32- and K210-based AI camera with free OpenMV IDE and MicroPython CV libraries (face detect, color track, QR, AprilTag).

- **Intel RealSense Depth Cameras** — https://github.com/IntelRealSense/librealsense  
  Free cross-platform SDK for depth, RGB-D, SLAM, skeleton tracking. Works on Linux SBCs + ROS.

- **Luxonis / OpenCV AI Kit (OAK-D)** — https://github.com/luxonis/depthai  
  Free DepthAI SDK for Myriad-X-based stereo + AI inference. Spatial AI, object detection, tracking.

- **Raspberry Pi Camera + Libcamera** — https://libcamera.org  
  Free camera stack with CSI cameras, HDR, ISP, Python/C++ APIs. Works on all Pi boards.

- **NVIDIA Jetson + VisionWorks / DeepStream (Free SDK)** — https://developer.nvidia.com  
  Free CV/DNN accelerated pipelines for Jetson Nano/Xavier. Supports object detection, multi-cam, tracking.

- **Arducam Open-Source Drivers** — https://www.arducam.com  
  Free drivers for CSI/MIPI cameras on Raspberry Pi, ESP32-S3, Jetson, and STM32.

- **ESP32-S3 / ESP32-CAM (Free SDK)** — https://github.com/espressif  
  Free ESP-IDF drivers and examples for JPEG, face-detection, streaming, high-res PSRAM cameras.

- **OpenMV AprilTag & QR Libraries** — https://github.com/openmv/openmv  
  Free on-board tag detection, marker tracking and object recognition for robotics.

- **V4L2 (Video for Linux 2)** — https://linuxtv.org  
  Standard free Linux camera framework. Works with USB webcams, CSI cameras, industrial cameras.

- **Open3D (Free 3D Vision Library)** — http://www.open3d.org  
  Free SLAM, point cloud filtering, ICP, voxel mapping. Works with RealSense, OAK-D, LIDAR.

- **ZED Stereo Camera (Free Python/C++ SDK)** — https://www.stereolabs.com  
  Free SDK for depth, tracking and spatial mapping (Jetson + Linux).

- **Pixy2 CMUcam (Open Firmware + SDKs)** — https://pixycam.com  
  Small vision system with free firmware, color tracking, object detection.

- **Pylon SDK for Basler Industrial Cameras (Free)** — https://www.baslerweb.com  
  Free SDK + GenICam support for high-speed machine vision applications.

- **Allied Vision / Vimba SDK (Free)** — https://www.alliedvision.com  
  Free C/C++/Python SDK for GigE and USB3 machine vision cameras.

- **OpenVINO Toolkit (Free)** — https://docs.openvino.ai  
  Free DNN acceleration on Intel edge platforms. Converts ONNX/TFLite models for cameras + SBCs.

- **GStreamer (Free multimedia framework)** — https://gstreamer.freedesktop.org  
  Free pipeline for camera capture, streaming, analysis and video encoding.

- **Dlib Vision Toolkit (Free)** — http://dlib.net  
  Open-source face recognition, landmark tracking, HOG detectors. Works on SBCs.

- **OpenPose (Community Edition)** — https://github.com/CMU-Perceptual-Computing-Lab/openpose  
  Free human pose estimation for robotics, AI cameras and Jetson.

- **Open Source Motion Tracking Tools (Free)** — https://github.com/CMU-Perceptual-Computing-Lab  
  CV pipelines for activity recognition and motion capture.

- **CSI/USB Cameras with Python (OpenCV + Libcamera)**  
  Full open-source pipeline for embedded AI cameras on Pi/Jetson/AMD Xilinx edge boards.

### 22D. Radar, ToF, Lidar & UWB Sensors (Free SDKs, Drivers & Tools)

#### ✅ Lidar & 2D/3D Scanners

- **RPLIDAR (A1/A2/A3/S1) SDK** — https://github.com/Slamtec/rplidar_sdk  
  Free C++ SDK for 360° laser scanners used in robots, AMRs, mapping. Works on Linux, Windows, ROS, microcontrollers.

- **Hokuyo URG/UST Open-Source Drivers** — https://github.com/ros-drivers/urg_node  
  Free ROS + C/C++ drivers for industrial safety Lidar sensors (2D mapping and SLAM).

- **Ouster OS-Series Lidar SDK (Free)** — https://github.com/ouster-lidar/ouster_example  
  Free Python/C++ drivers for 3D Lidar, point clouds, multi-return intensity.

- **Livox Lidar SDK (Free)** — https://github.com/Livox-SDK/Livox-SDK  
  Free SDK for Livox Mid/Avia series. Supports SLAM, mapping, ROS2.

- **Velodyne LiDAR Drivers (Open-Source)** — https://github.com/ros-drivers/velodyne  
  Free ROS + C++ drivers for Velodyne 3D scanners.

- **LIDAR-Lite v4 Drivers (Free)** — https://github.com/garmin/LIDARLite_Arduino_Library  
  Free Arduino/C drivers for Garmin’s low-cost ToF lidar.

- **LD06 / LD19 Budget Lidar Drivers (Open-Source)** — https://github.com/iliasam  
  Free C++/Python drivers for low-cost scanning Lidars used in robots and mapping bots.


#### ✅ Time-of-Flight (ToF) Distance Sensors

- **STM VL53L0X / VL53L1X / VL53L5CX ToF Drivers** — https://github.com/STMicroelectronics  
  Free C/C++ drivers and ranging algorithms for ToF distance & multi-zone sensors.

- **Benewake TFmini / TFMicro (Free SDK)** — https://github.com/budryerson/TFMini-Plus  
  Free Arduino & ROS drivers for small ToF modules used in drones and AGVs.

- **VL6180X Ranging + Ambient Light Drivers** — https://github.com/adafruit/Adafruit_VL6180X  
  Free open-source drivers for ToF ranging + ALS.


#### ✅ UWB (Ultra-Wideband) Ranging & Localization

- **Decawave / Qorvo DW1000 / DW3000 DWM1001 SDK (Free)** — https://github.com/Decawave  
  Free UWB ranging, TDoA/ToF, RTLS, and indoor positioning firmware.

- **MDEK1001 RTLS Tools (Free)** — https://www.qorvo.com  
  Free Python + gateway tools for UWB anchors and tags.

- **Pozyx UWB SDK (Community)** — https://www.pozyx.io  
  Free SDK/API for UWB localization on Linux SBCs, Python, and ROS.

- **ESP32 + UWB (Decawave-based)** — https://github.com/sparkfun/Qwiic_UWB  
  Free C++ libraries for ESP32-based UWB positioning modules.


#### ✅ mmWave & Radar (Doppler / Range / Presence / Safety)

- **TI mmWave Radar (IWR/LWR series) SDK** — https://www.ti.com  
  Free mmWave Studio + SDK for presence detection, Doppler, range, angle estimation. Used in robotics, safety and industrial sensing.

- **Infineon XENSIV Radar (BGT60TR13C / BGT60LTR11)** — https://github.com/Infineon  
  Free radar fusion SDKs for presence detection, people counting, speed sensing.

- **Acconeer A111 Pulsed Radar SDK (Free Tier)** — https://developer.acconeer.com  
  Free Python + C SDK for distance, gesture and breathing-rate radar.

- **OpenRadar (GNU Radio Based)** — https://github.com/OpenRadarGuru/OpenRadar  
  Free radar processing blocks for SDR + simulated mmWave systems.

- **mmWave ROS Drivers (Open-Source)** — https://github.com/robosavvy/ti_mmwave_rospkg  
  ROS1/ROS2 drivers for TI radar sensors.


#### ✅ Automotive-Grade ADAS (Free Toolchains)

- **OpenPilot Radar Interfaces (Comma.ai)** — https://github.com/commaai/openpilot  
  Open-source ADAS stack, includes radar fusion, tracking and lane-level perception.

- **OpenFusion Radars (Free)** — https://github.com/ArduPilot  
  Radar + IMU + GPS fusion for autonomous drones.


#### ✅ Point Cloud Processing, SLAM & Visualization

- **PCL (Point Cloud Library)** — https://pointclouds.org  
  Free C++ library for filtering, segmentation, plane fitting, clustering and 3D SLAM.

- **Open3D** — http://www.open3d.org  
  Free 3D vision tool for point clouds, mesh reconstruction, ICP mapping.

- **CloudCompare** — https://www.cloudcompare.org  
  Free point cloud viewer, segmentation, registration & mesh processing.

- **RTAB-Map SLAM** — https://introlab.github.io/rtabmap  
  Graph-based SLAM supporting stereo, RGB-D, Lidar, UWB. Free ROS tools.

- **Cartographer (Google SLAM)** — https://cartographer.io  
  free 2D/3D SLAM with IMU + Lidar fusion.

### 22E. Calibration Tools, Datasets & Benchmark Suites (Free / Open-Source)

#### ✅ Sensor Calibration Tools (IMU, Lidar, Cameras, UWB)

- **Kalibr (Camera-IMU Calibration)** — https://github.com/ethz-asl/kalibr  
  Industry-standard calibration for camera intrinsics/extrinsics, IMU parameters, rolling shutter, time offsets. Free and open-source.

- **OpenCV Camera Calibration Toolkit** — https://opencv.org  
  Free chessboard/homography-based calibration for lens distortion, intrinsics & stereo setup.

- **AprilTag Calibration Tools** — https://github.com/AprilRobotics/apriltag  
  Free fiducial-based calibration for robotics localization, precision pose estimation.

- **ROS Camera Calibration** — https://github.com/ros-perception/camera_calibration  
  Free GUI tool for mono/stereo camera calibration in ROS robots and drones.

- **IMU Calibration Scripts (Free)** — https://github.com/zulns  
  Open-source calibration for bias, noise, soft/hard iron magnetometer distortion.

- **Lidar-Camera Calibration (Autoware)** — https://github.com/autowarefoundation  
  Free tools to align Lidar point clouds with RGB cameras for autonomous robots.

- **UWB Anchor/Tag Calibration Tools** — https://github.com/Decawave/dwm1001-examples  
  Free UWB RTLS calibration & positioning reference projects.

- **OpenVINS Calibration** — https://github.com/rpng/open_vins  
  Visual-Inertial calibration and SLAM evaluation tools. Free C++.

- **Lidar to IMU Extrinsic Calibration (Free)** — https://github.com/irapkaist/lidar_mapping  
  Used in drones and autonomous mapping robots.

---

#### ✅ Open Datasets for TinyML, Robotics & IoT Sensors

- **UCI Machine Learning Repository** — https://archive.ics.uci.edu  
  Hundreds of free datasets used for IMU classification, anomaly detection, industrial sensors, gas/VOC datasets.

- **Google’s Speech Commands Dataset** — https://arxiv.org/abs/1804.03209  
  Free keyword spotting dataset for microphones and TinyML audio models.

- **DCASE Audio Classification Datasets** — http://dcase.community  
  Free environmental sound datasets for tiny audio models (machines, alarms, human activity).

- **HAR / IMU Activity Recognition Datasets** — https://archive.ics.uci.edu/ml/datasets  
  Free IMU datasets for gesture, activity, health and wearable ML.

- **Edge Impulse Public Datasets** — https://edgeimpulse.com/publicprojects  
  Community open datasets for vibration, motors, fall detection, audio, agriculture, air quality.

- **RobustML (Adversarial Sensor Datasets)** — https://github.com/RobustBench  
  Free datasets for evaluating model robustness on embedded/edge hardware.

- **OpenRadar Dataset** — https://github.com/OpenRadar/Opendataset  
  Free mmWave radar raw data for learning range-Doppler/angle.

- **KITTI Vision Benchmark** — http://www.cvlibs.net/datasets/kitti  
  Widely used open dataset for autonomous driving (Lidar + camera + IMU).

- **TUM RGB-D Dataset** — https://vision.in.tum.de/data/datasets/rgbd-dataset  
  Free indoor depth + IMU sequences for SLAM and visual inertial odometry.

- **CMU Motion Capture Dataset** — http://mocap.cs.cmu.edu  
  Free human motion capture data for robotics/gesture models.

---

#### ✅ Synthetic Data & Simulation Suites (Free)

- **Gazebo / Ignition Robotics** — https://gazebosim.org  
  Free physics + sensor simulation (Lidar, depth, IMU, radar) for robots and drones.

- **Unity Perception Toolkit** — https://github.com/Unity-Technologies/com.unity.perception  
  Free synthetic data generator for object detection, segmentation with metadata.

- **CARLA Autonomous Driving Simulator** — https://carla.org  
  Free, open-source autonomous driving simulation for Lidar/camera/radar evaluation.

- **AirSim (Microsoft)** — https://github.com/Microsoft/AirSim  
  Free drone/ground vehicle simulator with camera + IMU/Lidar data logging.

- **OpenRobotSimulation + Webots** — https://cyberbotics.com  
  Free data capture from virtual sensors for ML training and calibration.

---

#### ✅ Benchmark Suites & Evaluation Kits (Free)

- **MLPerf Tiny Benchmark (Free)** — https://mlcommons.org  
  Free benchmark for MCUs and TinyML inference (audio, vision, anomaly detection).

- **MCU MicroML Benchmarks (Open-Source)** — https://github.com/mlcommons  
  Evaluate RAM/flash usage and inference time on microcontrollers.

- **RoboticsSLAM Benchmarks (TUM / KITTI)**  
  Free SLAM benchmarks for evaluating odometry, visual-inertial performance.

- **EEMBC ULPMark (Free Specs & Results)** — https://www.eembc.org/ulpmark  
  Free benchmarking for ultra-low-power MCUs used in IoT.

- **DVS Neuromorphic Datasets (Free)** — https://research.ibm.com  
  Event-based camera datasets for low-power vision.

### 23A. Embedded & Local Databases (Free / Open-Source)

- **SQLite (Public Domain)** — https://sqlite.org  
  Zero-config embedded SQL database used in millions of devices. Fits in <500KB, supports transactions, journaling, encryption extensions.

- **LittleFS + Wear-Levelled KV Stores** — https://github.com/ARMmbed/littlefs  
  Free, flash-friendly file system with small KV database patterns for MCUs (config, logs, counters).

- **UnQLite (NoSQL Embedded DB)** — https://unqlite.org  
  Zero-conf NoSQL store for embedded Linux & SBC gateways. In-memory or flash-backed, BSD license.

- **RocksDB (Facebook)** — https://rocksdb.org  
  Fast key-value storage for edge gateways and rugged IoT servers. SSD/flash optimized, free & open-source.

- **LevelDB (Google)** — https://github.com/google/leveldb  
  Lightweight NoSQL KV store for local caching, telemetry buffering and offline IoT apps.

- **LiteDB (C# Embedded DB)** — https://www.litedb.org  
  BSON document DB for .NET applications running on edge devices or Windows/Linux gateways. MIT license.

- **Realm (Open-Source Edition)** — https://github.com/realm/realm-core  
  Local database for mobile/edge apps with sync capability. Free community edition for embedded Android gateways.

- **DuckDB (In-Process OLAP DB)** — https://duckdb.org  
  Embedded analytics engine for edge logs and local queries. Free & open-source.

- **PicoDB (Tiny NoSQL DB)** — https://github.com/orestisf1993/picoDB  
  Very small KV database for microcontrollers and wearables.

- **TInyDB (Python TinyDB)** — https://tinydb.readthedocs.io  
  JSON-based embedded database for Python edge apps on Raspberry Pi / Jetson.

- **LiteX BIOS + FlashFS (Open-Source SoC Framework)** — https://github.com/enjoy-digital/litex  
  Tiny filesystem and storage blocks for RISC-V SoCs, FPGA SoCs, and soft processors.

- **Ignition / Gazelle Log Replay (Free)** — https://gazebosim.org  
  Local data logging & query for robotics sensor data; used for debugging and playback.

- **Zephyr & FreeRTOS KV Stores (Open-Source Samples)** — https://github.com/zephyrproject-rtos  
  Free embedded KV databases for logs, configs and firmware state.

- **MCU Flash-Based Ring Buffers (Open Implementations)** — https://github.com/embeddedartistry/libcircular  
  Free circular/ring buffer libraries for log persistence and fault events.

- **TinyCDB (Constant DB)** — https://www.corpit.ru/mjt/tinycdb.html  
  Minimal C DB for tiny embedded Linux systems. Public domain.

- **File-backed MQTT Store (Mosquitto Persistence)** — https://mosquitto.org  
  Free built-in persistent offline storage for MQTT gateways and edge brokers.

### 23B. Time-Series & IoT Databases / MQTT Query Engines (Free / Open-Source)

- **InfluxDB (Open-Source Edition)** — https://www.influxdata.com  
  Popular time-series DB for sensor telemetry. Local edge installation is free, supports retention policies and dashboards.

- **TimescaleDB (Community Edition)** — https://timescale.com  
  PostgreSQL extension for time-series + IoT analytics. Free CE version supports compression and continuous aggregates.

- **CrateDB (Open-Source)** — https://crate.io  
  Distributed SQL database optimized for IIoT data ingestion. Free community edition for edge servers/SBCs.

- **QuestDB (Open-Source)** — https://questdb.io  
  Ultra-fast SQL time-series engine. Free CE with real-time ingestion and Grafana support.

- **Prometheus (Free, CNCF)** — https://prometheus.io  
  Time-series scraping + alerting for gateways and on-prem IoT servers. Works with exporters and Grafana.

- **RRDTool (Free)** — https://oss.oetiker.ch/rrdtool  
  Classic ring-buffer time-series database for resource-limited Linux gateways. Zero cost, low footprint.

- **Graphite (Open-Source)** — https://graphiteapp.org  
  Metrics and time-series monitoring for edge clusters and industrial servers.

- **VictoriaMetrics (Free OSS)** — https://victoriametrics.com  
  Time-series database with high compression; free OSS server ideal for IoT telemetry.

- **OpenTSDB** — http://opentsdb.net  
  Time-series data over HBase; free and used in industrial/logging scenarios.

- **EMQX MQTT Broker (Open Source)** — https://www.emqx.io  
  Free clustered MQTT broker with rule engine to store messages into InfluxDB, MySQL, PostgreSQL, MongoDB.

- **Mosquitto MQTT Broker (Free)** — https://mosquitto.org  
  Small-footprint MQTT broker with file persistence. Suitable for gateways and low-cost servers.

- **HiveMQ CE (Free)** — https://github.com/hivemq/hivemq-community-edition  
  Free MQTT broker with WebSockets support and plugin API.

- **Mainflux (Open-Source IoT Cloud)** — https://mainflux.com  
  MQTT/CoAP HTTP ingestion + storage into Postgres/Influx. Fully open-source and edge-friendly.

- **ThingsBoard Community Edition** — https://thingsboard.io  
  Free IoT backend with rule engine, ingestion pipelines, time-series DB, dashboards and OTA.

- **NanoMQ (Lightweight MQTT) — Nanomq** — https://nanomq.io  
  Very small MQTT broker for embedded Linux and RT-OS gateways. Free & open-source.

- **KubeEdge Edge-Storage/SQL Lite** — https://kubeedge.io  
  Edge-native storage for devices and telematics; open-source under CNCF.

- **NoSQL for Gateways: MongoDB Community Edition** — https://www.mongodb.com  
  Free CE supports IoT telemetry, document storage and offline-first edge apps.

- **Druid (Open-Source)** — https://druid.apache.org  
  Real-time analytics DB for streaming sensor data; used in industrial IoT.

- **ReductStore (Open-Source TSDB)** — https://www.reduct.store  
  Simple time-series blob store for edge logging. Free to self-host.

### 23C. Real-Time Streaming & Analytics on the Edge (Free / Open-Source)

- **Apache Kafka (Free Community Edition)** — https://kafka.apache.org  
  High-throughput event streaming platform for IoT gateways and industrial servers. Free Kafka Connect + KSQL for stream queries.

- **Apache NiFi (Free)** — https://nifi.apache.org  
  Drag-and-drop real-time data pipelines for IoT ingestion, transformation, routing. Runs on SBCs and edge servers.

- **Node-RED (Open-Source)** — https://nodered.org  
  Visual flow programming for MQTT/HTTP/serial data. Free dashboards, rules, alerts. Runs on Raspberry Pi, Jetson, gateways.

- **EMQX Rule Engine (Free Open-Source Edition)** — https://www.emqx.io  
  Real-time streaming SQL rules on MQTT messages. Push to DBs, HTTP, Kafka, InfluxDB. Free to self-host.

- **Mosquitto + Telegraf (Free)** — https://mosquitto.org / https://www.influxdata.com  
  Mosquitto for MQTT + Telegraf for edge processing, metrics, filtering and data export to TSDBs.

- **EdgeX Foundry (LF Edge, Open-Source)** — https://www.edgexfoundry.org  
  Industrial edge framework: device services, real-time pipelines, rules engine. Completely open-source.

- **KubeEdge (CNCF Project)** — https://kubeedge.io  
  Kubernetes at the edge with real-time data sync, device twin, MQTT bridge and local analytics. Open-source.

- **Flink (Open-Source)** — https://flink.apache.org  
  Real-time stream analytics with low-latency processing. Works on edge clusters + industrial servers.

- **Spark Structured Streaming (Free)** — https://spark.apache.org  
  Batch + streaming analytics for industrial IoT. Runs on edge x86 or ARM servers.

- **FastAPI with MQTT & WebSockets (Free)** — https://fastapi.tiangolo.com  
  Lightweight Python real-time pipelines for notifications, dashboards, telemetry APIs.

- **KSQL / ksqlDB (Free)** — https://ksqldb.io  
  SQL queries over Kafka streams. Used in IoT pipelines for filtering, aggregation and anomaly detection.

- **Benthos Stream Processor (Free, MIT-licensed)** — https://www.benthos.dev  
  Single binary stream processor for MQTT/Kafka/AMQP/HTTP. Extremely lightweight for edge deployments.

- **MQTT to InfluxDB / Postgres Gateways (Free)** — https://github.com  
  Open-source bridges converting MQTT sensor streams to SQL/TSDB storage.

- **OpenFaaS (Free)** — https://www.openfaas.com  
  Run serverless functions at the edge to process sensor events, alerts, ML inference.

- **OpenWhisk (Apache)** — https://openwhisk.apache.org  
  Event-driven functions for IoT pipelines and analytics. Free and open-source.

- **StreamSets Data Collector (Free Core Edition)** — https://streamsets.com  
  Visual pipelines for IoT/log ingestion, MQTT connectors, transformations.

- **Logstash (Elastic Stack Free)** — https://www.elastic.co/logstash  
  Real-time ingestion and parsing of IoT logs and telemetry. Free open-source pipeline.

- **Fluentd / Fluent Bit (Free CNCF)** — https://fluentbit.io  
  Lightweight log & metrics streaming on Embedded Linux, routers, gateways. Free & open-source.

- **Eclipse Streamsheets (Free)** — https://www.eclipse.org/streamsheets  
  Excel-like real-time data processing for MQTT industrial systems.

### 23D. Dashboards & Visualization Tools (Free / Open-Source)

- **Grafana (Open-Source Edition)** — https://grafana.com  
  Industry-standard dashboard for timeseries, MQTT, InfluxDB, Prometheus, PostgreSQL. Free plugins and alerting.

- **ThingsBoard Community Edition** — https://thingsboard.io  
  Free IoT dashboard and rule engine with widgets, charts, maps, real-time telemetry, OTA and device management.

- **Node-RED Dashboard (Free)** — https://nodered.org  
  Drag-and-drop UI panels for MQTT/HTTP sensors, switches, gauges and charts.

- **Kibana (Free / Elastic OSS)** — https://www.elastic.co/kibana  
  Visualization for logs, metrics, security events and dashboards. Works with Elasticsearch and Beats on edge.

- **Chronograf (Open-Source)** — https://docs.influxdata.com/chronograf  
  InfluxDB dashboards and alerting. Free and lightweight for Raspberry Pi / gateway servers.

- **Metabase (Open-Source)** — https://metabase.com  
  Easy SQL dashboards for PostgreSQL, MySQL, Timescale, CrateDB, SQLite. Free for on-prem/self-host.

- **Redash (Free, Open-Source)** — https://redash.io  
  Dashboards and query editor for SQL, InfluxDB, JSON, REST and MQTT backends.

- **Superset (Apache)** — https://superset.apache.org  
  Modern web BI dashboard for SQL/NoSQL timeseries and IoT data warehouses. Free, open-source.

- **Freeboard / Freeboard.io (Open-Source)** — https://github.com/Freeboard/freeboard  
  IoT-focused dashboards: charts, gauges, maps. Free and lightweight for small embedded projects.

- **EMQX Dashboard (Free OSS)** — https://www.emqx.io  
  Free MQTT broker dashboard with real-time subscription/device monitoring, metrics, rule engine UI.

- **Mainflux UI (Open-Source)** — https://mainflux.com  
  Free web UI for IoT devices, channels, events and subscriptions.

- **OpenHAB (Free)** — https://www.openhab.org  
  Smart home / IoT dashboards with MQTT, Modbus, KNX, BACnet. Open-source.

- **Homer Dashboard (Free OSS)** — https://github.com/bastienwirtz/homer  
  Lightweight static dashboard for gateway servers with links to services, metrics and logs.

- **Shiny (R/Open-Source)** — https://shiny.rstudio.com  
  Web dashboards for sensor data analytics and plotting. Free and open-source.

- **Plotly Dash (Community)** — https://plotly.com/dash  
  Python dashboards for real-time IoT charts. Free open-source edition.

- **Streamlit (Open-Source)** — https://streamlit.io  
  Build sensor dashboards with Python in minutes. Free to self-host on SBCs or x86 edge servers.

- **Grafana Loki + Promtail (Free)** — https://grafana.com/oss/loki  
  Free log dashboard for embedded Linux / gateways.

- **Eclipse Streamsheets (Free)** — https://www.eclipse.org/streamsheets  
  Spreadsheet-style dashboard for MQTT, Kafka, Modbus. Runs on PCs and edge servers.

## 24. Test Equipment, RF Analyzers & Open Hardware Tools

### 24A. Logic Analyzers & Protocol Tools (Open Hardware / Free SDKs)

- **Sigrok + PulseView (Open-Source)** — https://sigrok.org  
  Free multi-platform logic analyzer UI with I2C/SPI/UART/CAN/LIN/1-Wire decoders. Supports dozens of USB analyzers.

- **Saleae Logic (Free Basic Software)** — https://www.saleae.com  
  High-quality analyzers; free software for protocol decode and measurements (full features with hardware).

- **DSLogic Open-Source Analyzer** — https://www.dreamsourcelab.com  
  Affordable open hardware logic analyzers with free Sigrok/PulseView support.

- **Bus Pirate (Open Hardware)** — http://dangerousprototypes.com  
  Free, open-source multi-protocol tool for SPI, I2C, UART, SWD sniffing and scripting.

- **GreatFET One (Open Hardware)** — https://greatscottgadgets.com/greatfet/  
  USB hardware hacking tool for GPIO, SPI/I2C sniffing, glitching, logic capture.

- **Logic Sniffer (OLA, Open Logic Analyzer)** — https://github.com/OpenLogicSniffer  
  Open-source FPGA-based logic analyzer with Sigrok support.

- **Arduino as Logic Analyzer (Free Firmware)** — https://github.com/felhr85/USB-Serial-Analyzer  
  Turns Arduino boards into basic logic analyzers for UART/SPI debugging.

- **ESP32 Logic Analyzer Firmware (Free)** — https://github.com/ESP32DE/ESP32-logic-analyzer  
  ESP32 firmware to capture GPIO and decode common serial protocols.

- **fx2lafw (Open Firmware for FX2LA USB)** — https://github.com/sigrokproject/fx2lafw  
  Free firmware enabling cheap FX2-based analyzers to work with Sigrok/PulseView.

- **Beagle USB/I2C Protocol Analyzers (Free SDK)** — https://www.totalphase.com  
  Commercial hardware, but free software & protocol analyzers usable without license.

### 24B. Digital Oscilloscopes, Mixed-Signal Scopes & Open-Source Firmware / Tools

- **OpenHantek (Open-Source Oscilloscope UI)** — https://github.com/OpenHantek  
  Free PC software for many Hantek USB scopes. Better UI, FFT, protocol decode without vendor software.

- **PulseView (Sigrok GUI)** — https://sigrok.org  
  Free visualization of oscilloscope & logic traces. Protocol decode for UART/I2C/SPI/CAN. Works with many USB PC scopes.

- **Owon/UNI-T/ATTEN USB Scope Support (Sigrok)** — https://sigrok.org/wiki/Supported_hardware  
  Many budget PC USB scopes work with Sigrok for free decoding and capture.

- **FrogScope (Open-Source FPGA Oscilloscope)** — https://github.com/RobertBaruch/frogscope  
  DIY FPGA-based oscilloscope with free HDL + PC UI.

- **Scoppy (Android Oscilloscope via ESP32/RPI Pico/STM32)** — https://github.com/fhdm-dev/Scoppy  
  Turns ESP32 or Raspberry Pi Pico into a basic oscilloscope + logic analyzer using an Android phone. Free and open-source.

- **Arduino Oscilloscope Projects (Free)** — https://github.com/yoggy/arduino-oscilloscope  
  Multiple open projects turning Arduino into a sampling oscilloscope with PC UI.

- **Siglent SDS/MSO (Free SCPI/Remote Software)** — https://www.siglent.com  
  Free remote PC control, SCPI automation, CSV/trace exports, Bode plots.

- **Rigol UltraScope (Free)** — https://rigolna.com/software  
  Free PC control software for Rigol DS/MSO scopes. Automates captures, measurements, screenshots.

- **Hantek DSO2000/5000/6000 Open Tools** — https://github.com/OpenHantek/openhantek  
  Open-source analysis, waveform capture, exporting and scripting.

- **PicoScope Software (Free, No License)** — https://www.picotech.com  
  PC oscilloscope UI for PicoScopes — free decoding, math channels, FFT. Runs on Windows/Linux/Raspberry Pi.

- **Red Pitaya (Open-Source Oscilloscope/Analyzer)** — https://redpitaya.com  
  STEMlab boards with free open-source oscilloscope, spectrum analyzer, logic analyzer + FPGA templates.

- **Analog Discovery 2 (WaveForms – Free Software)** — https://digilent.com  
  Mixed-signal USB scope & analyzer. Free WaveForms software (logic, spectrum, protocol decode).

- **OpenScope MZ (Digilent — Open Firmware)** — https://digilent.com  
  Wi-Fi oscilloscope + logic analyzer with open-source firmware and PC/web UI.

- **LabNation SmartScope (Open-Source)** — https://lab-nation.com  
  Open-source FPGA oscilloscope with free cross-platform UI + protocol decoding.

- **BitScope Micro (Free Software)** — https://bitscope.com  
  Low-cost USB mixed-signal scope; free PC software for waveform capture & logic decode.

- **Scilab + Serial/DAQ Oscilloscope Plugins (Free)** — https://www.scilab.org  
  Free numerical oscilloscope using USB/DAQ devices for signal capture and math processing.

- **Jupyter Notebook + PyVisa Automation (Free)** — https://pyvisa.readthedocs.io  
  Free automation for Rigol/Siglent/Keysight scopes via VISA/SCPI for automated testing & logging.

- **LabTool (Open-Source MSO by Xilinx Students)** — https://github.com/mrk-its/labtool  
  FPGA-based MSO with open PC UI and protocol decode.

- **STM32 Discovery + OpenMSO Firmware** — https://github.com/azonenberg/openfpga/tree/master/tools/openmso  
  Turns STM32 discovery boards into very basic oscilloscopes/signal capture tools.

- **Real-time Web Oscilloscopes (Free)**  
  - WebUSB/WebSerial tools for ESP32/STM32 pico-scopes  
  - Open-source dashboards streaming ADC data to browser UI

- **OscLogger / OscExport Tools** — https://github.com  
  Open-source utilities for exporting scope CSVs, converting to VCD, Matplotlib, Excel.

### 24C. RF Spectrum Analyzers, SDR Platforms & RF Toolchains (Free / Open-Source)

#### ✅ SDR Hardware (Open Hardware or Free SDK Support)

- **RTL-SDR (USB SDR)** — https://www.rtl-sdr.com  
  Cheapest SDR platform (24 MHz – ~1700 MHz). Free drivers + support for GNU Radio, SDR#, GQRX.

- **HackRF One (Open Hardware SDR)** — https://greatscottgadgets.com/hackrf/  
  1 MHz – 6 GHz half-duplex SDR. Free firmware, gateware, host tools. Ideal for RF labs and education.

- **LimeSDR / LimeSDR Mini (Open Hardware)** — https://limemicro.com  
  Full-duplex up to 3.8 GHz with FPGA access. Free LimeSuite for tuning, calibration, streaming.

- **BladeRF (Open Hardware)** — https://www.nuand.com  
  300 MHz – 3.8 GHz SDR with FPGA fabric. Free host drivers, FPGA gateware, GNU Radio blocks.

- **PlutoSDR (Analog Devices)** — https://wiki.analog.com/university/tools/pluto  
  325 MHz – 3.8 GHz SDR. Free libiio drivers and GNU Radio support.

- **USRP (Ettus Research)** — https://github.com/EttusResearch  
  Free UHD drivers, open FPGA reference designs. Works with GNU Radio & RFNoC.

- **KerberosSDR (4-channel coherent SDR)** — https://www.rtl-sdr.com/kerberossdr  
  Free direction-finding software + beamforming tools.

- **OpenWiFi SDR (FPGA Open Source)** — https://github.com/open-sdr/openwifi  
  Full open-source Wi-Fi PHY on FPGA. Free Verilog implementation.

- **SatNOGS Ground Station (Open Hardware)** — https://satnogs.org  
  Free open-source satellite ground station SDR with antenna rotator, tracking, demodulation.

---

#### ✅ RF & SDR Software (Free Tools)

- **GNU Radio (Open-Source)** — https://gnuradio.org  
  Standard SDR toolkit. Modular blocks for FM/AM, ADS-B, GSM/LTE, satellite reception.

- **GQRX (GUI Spectrum Analyzer)** — https://gqrx.dk  
  Free waterfall and spectrum UI for RTL-SDR/HackRF/PlutoSDR.

- **QSpectrumAnalyzer** — https://github.com/xmikos/qspectrumanalyzer  
  Free RF spectrum analyzer UI that runs on Linux, supports RTL-SDR/HackRF/Pluto/LimeSDR.

- **SDR# (SDRSharp)** — https://airspy.com  
  Free Windows SDR software with FM/AM/Digital decode, ADS-B plugins.

- **CubicSDR** — http://cubicsdr.com  
  Multi-platform SDR & waterfall visualizer. Free and simple for beginners.

- **Fosphor (GPU accelerated spectrum)** — https://github.com/osmocom/gr-fosphor  
  Real-time GPU spectrum visualization for SDRs. Open-source.

- **Dump1090 (ADS-B Aircraft Tracking)** — https://github.com/flightaware/dump1090  
  Free ADS-B decoder for RTL-SDR; aircraft position & telemetry.

- **GQRX + GSM Receivers** — https://github.com/ptrkrysik/gr-gsm  
  Open-source GSM decoding on SDR for educational/demonstration purposes.

- **OpenWebRX (Web-based SDR Receiver)** — https://github.com/jketterl/openwebrx  
  Stream SDR radio over the web. Free, open-source.

---

#### ✅ SDR Toolchains for SATCOM, GPS, Radio Astronomy

- **Pypredict + GNURadio SATCOM** — https://github.com/EA4GPZ/pypredict  
  Free satellite modem + ground telemetry tooling.

- **SatDump (Open-Source)** — https://github.com/altillimity/SatDump  
  Free multi-satellite signal decoder (NOAA, METEOR, GOES). Uses RTL-SDR & LimeSDR.

- **GNU Radio GPS SDR** — https://github.com/osqzss/gps-sdr-sim  
  GPS signal simulation and analysis. Open-source.

- **Radio Astronomy with SDR (Open Tools)** — https://github.com/0xCoto/RadioSky  
  Free tools for hydrogen line, pulsar, and solar SDR experiments.

---

#### ✅ Antenna Analysis, Network Tools, RF Calculators

- **RTLSDR Scanner** — https://github.com/EliasOenal/rtl-sdr-scanner  
  Free spectrum sweep and level measurement for cheap SDRs.

- **OpenVNA / LibreVNA** — https://github.com/jankae/LibreVNA  
  Open-source Vector Network Analyzer firmware + PC UI. Sweeps S11/S21, antenna tuning.

- **NanoVNA (Open Firmware + Tools)** — https://nanovna.com  
  Very cheap VNA with open-source analyzer software.

- **RFSim99 (Free)** — https://rf-tools.com  
  Free RF circuit simulation for filters and matching networks.

- **RTL Power** — https://github.com/keenerd/rtl_power  
  Wideband power scanning & CSV exports for RF characterization.

- **SatNOGS Network Dashboard** — https://network.satnogs.org  
  Free open satellite observations from global SDR ground stations.

- **PySDR (Free SDR Textbook)** — https://pysdr.org  
  Free digital signal processing lessons & code for SDR experiments.

---

#### ✅ RF Gateware, FPGA & PHY Layers (Open-Source)

- **Open5GS / srsRAN (LTE/NR Stack)** — https://open5gs.org / https://github.com/srsran/srsRAN  
  Full open-source 4G/5G core + PHY. Can run with SDR hardware (USRP/BladeRF/LimeSDR).

- **OpenWiFi SDR (Verilog)** — https://github.com/open-sdr/openwifi  
  Full open PHY for Wi-Fi 802.11 on FPGA. End-to-end open-source.

- **Osmocom (SDR GSM/ TETRA Tools)** — https://osmocom.org  
  Open-source SDR implementations of GSM, TETRA, SDR PHY layers.

- **FPGA-DSP SDR Cores (Free)** — https://github.com  
  Many free HDL building blocks: FIR filters, CIC decimators, mixers, FFT cores.

### 24D. Network Analyzers, Antenna Tuning, Signal Generators & EMC Tools

#### ✅ Vector Network Analyzers (VNA) & Antenna Test Tools

- **NanoVNA (Open Firmware + Free PC Tools)** — https://nanovna.com  
  Ultra-low-cost VNA with open-source firmware + free PC software for S11/S21, antenna tuning, impedance, SWR plots.

- **LibreVNA (Open Hardware)** — https://github.com/jankae/LibreVNA  
  True 2-port VNA with open firmware + open-source desktop GUI. Exports Touchstone files for RF simulation.

- **OpenVNA (OSS PC Software)** — https://github.com/zirias/openvna  
  Free VNA analyzer UI for NanoVNA clones & open hardware devices.

- **VNA Windows/Linux Tools (Sigrok support)** — https://sigrok.org/wiki/Supported_hardware  
  Free VNA data capture, CSV logs, sweep exports, antenna plots.

- **Antenna Analyzer using RTL-SDR (Free)** — https://github.com  
  Open scripts that sweep RTL-SDR tuning range to approximate antenna resonances.

- **Open Source TDR (Time-Domain Reflectometry)** — https://github.com/gogo2/tiny-tdr  
  Free DIY TDR tool for cable/antenna debugging, impedance mismatch detection.

- **SatNOGS Ground Station (Open Hardware)** — https://satnogs.org  
  Includes free antenna build files, rotator control, satellite signal evaluation.

- **ADIF & Touchstone File Viewers (Free)** — https://github.com  
  Open-source antenna data visualizers compatible with NanoVNA/LimeSDR logs.


#### ✅ Signal Generators, RF Sources & Calibration Tools

- **RFSim99 (Free)** — https://rf-tools.com  
  Free RF circuit simulator for filters, matching networks, and impedance design.

- **NWT (NetzWekT) Signal Analyzer Tools (Free)** — https://github.com  
  Open-source UI for low-cost NWT/FA-NWT RF sweepers.

- **Open-Source SIGGEN Python Tools** — https://github.com/pavel-demin/red-pitaya-notebooks  
  Convert RedPitaya into signal generator, frequency sweep, Bode plotter.

- **Arduino Signal Gen Projects (Free)** — https://github.com/bborncr/AD9850  
  Free waveform generator code for DDS chips (AD9850/51, Si5351, AD9833).

- **Siglent/Rigol SCPI Control (Free)** — https://github.com/labters/labrador  
  Automate sine/square/RF sweeps with free Python libraries.


#### ✅ Impedance, S-Parameters & RF Simulation

- **QUCS / QucsStudio (Free RF Simulation)** — https://qucs.sourceforge.io  
  Free GNU RF circuit simulator for S-parameters, filters, Smith charts.

- **SimSmith (Free)** — https://www.ae6ty.com  
  Free Smith chart analysis tool for RF matching networks and coax tuning.

- **ADS Touchstone Analyzers (Free Scripts)** — https://github.com  
  Open-source Python tools to plot S11/S21 from VNA data.

- **RF Toolbox for Octave (Free)** — https://gnu.org/software/octave  
  Open MATLAB-like RF modeling for filters, antennas, and microwave elements.


#### ✅ EMC / RF Compliance Test Utilities (Free)

- **EMCview Free Edition (Tekbox)** — https://www.tekbox.com  
  Free near-field EMI scanning software with low-cost probes.

- **OpenEMS (Free FDTD Simulator)** — https://www.openems.de  
  Full 3D EM simulation for antennas, shielding, waveguides, PCB EMI fields.

- **NEC2 Antenna Simulator (Free)** — https://www.qsl.net  
  Free antenna EM solver; widely used by RF hobbyists and professionals.

- **EM Field Visualizer (Free)** — https://github.com/thliebig/emfield  
  Open-source EM simulation/visualization tools for research.

- **KiCad RF Tools (Free)** — https://kicad.org  
  Includes free PCB impedance calculators, differential pair tuning, RF routing helpers.


#### ✅ Open RF Test Projects / DIY Hardware

- **Red Pitaya (Open FPGA Oscilloscope/VNA/SA)** — https://redpitaya.com  
  Free open-source signal analyzer, VNA, and RF scope apps + FPGA code.

- **LimeSDR Calibration Tools (Free)** — https://github.com/myriadrf  
  Automatic IQ balance, filter calibration, RF gain levelers.

- **TinySA (Open Firmware)** — https://tinysa.org/wiki/pmwiki.php  
  Handheld spectrum analyzer with free firmware + PC UI.

- **RTL-SDR Noise Source Calibration (Free)** — https://github.com  
  Open projects for building & calibrating noise sources to measure filter bandwidth and LNA gain.

- **Open Hardware RF Switch/Attenuator** — https://github.com  
  Community-designed RF switch/step-attenuator boards for SDR test rigs.


#### ✅ RF Reference Calculators (Free)

- **RF Tools Online Calculator Suite** — https://rf-tools.com  
  Free microstrip calculator, impedance, power, VSWR, LC filter design.

- **Mini-Circuits Calculator Tools (Free)** — https://www.minicircuits.com  
  Free coax loss calculator, S-parameter models, Smith chart tools.

- **Microwave Office Student Tools (Free)** — academic free license available on request.

### 24E. Power Analyzers, Battery Profiling, HIL Testing & Device Emulators (Free / Open-Source)

#### ✅ Power & Energy Measurement Tools (Free Software / Open Hardware)

- **Monsoon Power Monitor (Free Software)** — https://www.msoon.com  
  Hardware is commercial, but software + APIs are free. Used for MCU and IoT power profiling (µA–A range).

- **Otii Arc Software (Free Tier)** — https://www.qoitech.com  
  Free UI for energy debugging, current logging, and power vs. time plots with Otii hardware.

- **Joulescope (Open Software)** — https://joulescope.com  
  High-precision current measurement (nA to A). Free open-source UI and Python automation.

- **Texas Instruments EnergyTrace (Free)** — https://www.ti.com  
  Free real-time MCU power profiling with TI LaunchPads (MSP430/CC13xx/CC26xx).

- **ST Power Profiler (Free)** — https://www.st.com  
  Free GUI for STM32 platforms measuring average/run/sleep power.

- **Nordic Power Profiler Kit II (Free Software)** — https://www.nordicsemi.com  
  Free PC UI + automation for BLE/802.15.4 low-power systems.

- **INA219/INA226 Open-Source Logs** — https://github.com/TheKitty  
  Free Python/Arduino tools for current logging and battery profiling.


#### ✅ Battery Testing, Charge/Discharge Profiling, Fuel Gauges

- **BQ Studio (Texas Instruments)** — https://www.ti.com  
  Free GUI for TI fuel gauges and battery monitor ICs. Data logging + cell optimization.

- **OpenBMS Projects (Free, Open Hardware)** — https://github.com/LibreSolar/bms-firmware  
  Open-source BMS firmware, logging tools and Coulomb counting.

- **Battery Cycler Tools (Community)** — https://github.com/OpenBattery  
  Free C/Python cycler software for Li-Ion/NiMH discharge & lifetime tests.

- **Adafruit Battery Tester Firmware (Free)** — https://github.com/adafruit  
  Arduino-based battery logging, capacity tests, curve plots.


#### ✅ HIL (Hardware-In-the-Loop) Testing & Simulation

- **OpenSTF (Smartphone/Device Farm)** — https://github.com/openstf  
  Free device farm framework for testing embedded Android devices remotely.

- **Renode (Open-Source HIL Simulator)** — https://renode.io  
  Free MCU/SoC emulator with networked peripherals for CI and hardware-in-the-loop testing.

- **QEMU (Open-Source System Emulator)** — https://www.qemu.org  
  Free emulation of ARM, RISC-V, x86 MCUs/SBCs. Used in IoT CI pipelines.

- **Robot Framework (Free Test Automation)** — https://robotframework.org  
  Free automation for embedded Linux testing via SSH/Shell/Serial/UART.

- **PyTest + PySerial (Free)** — https://github.com/pyserial  
  Free Python framework to automate UART/CAN/I2C tests and golden-sample comparisons.

- **Mbed Greentea (Free)** — https://os.mbed.com  
  Free automated firmware test framework for Cortex-M boards.


#### ✅ Device Emulators & Virtual Boards

- **ESP-IDF QEMU Emulator (Free)** — https://github.com/espressif/qemu  
  Free QEMU port for ESP32; runs firmware without hardware.

- **Zephyr QEMU Targets (Free)** — https://github.com/zephyrproject-rtos  
  Emulate Cortex-M boards, Nordic nRF, STM32, RISC-V for CI testing.

- **Linux User Mode Networking (Free)** — https://www.kernel.org  
  Test network code without real hardware. Good for gateway prototypes.


#### ✅ Fault Injection, Fuzzing, Security Testing

- **PULP Platform (Open Hardware RISC-V)** — https://pulp-platform.org  
  Fault-tolerant RISC-V research cores with open test benches.

- **gr-bladeRF / gr-hackrf Clock/Glitch Tools** — https://github.com/osmocom  
  Fault injection experiments for side-channel research. Free with SDRs.

- **AFL / libFuzzer for Embedded Linux** — https://github.com/google/AFL  
  Free fuzzing for IoT gateway services and parsers.

- **MCUboot + Crypto Fuzz Tests (Free)** — https://github.com/mcuboot/mcuboot  
  Free fuzzing for bootloader image validation.


#### ✅ Production & Regression Test Frameworks (Free)

- **pytest-embedded (Free)** — https://github.com/esp-rs/pytest-embedded  
  Automates embedded device tests via serial, JTAG, logging comparison.

- **OpenHTF (Google)** — https://github.com/google/OpenHTF  
  Free Python test framework for factory production lines and automated test jigs.

- **TestStand Alternatives (Free/Open)** —  
  - Robot Framework (Python scripts)  
  - PyTest with serial/CAN logs  
  - LabVIEW Community Edition for personal/educational use


#### ✅ USB, BLE, Wi-Fi Testing

- **Wireshark (Free)** — https://wireshark.org  
  Free packet analyzer for Wi-Fi, BLE, Ethernet. With BLE decoders and USBCAP Wi-Fi capture.

- **nRF Sniffer (Free)** — https://www.nordicsemi.com  
  Free BLE sniffer software for Nordic dongles.

- **PacketSquirrel / USB Armory (Open Hardware)** — https://github.com/inversepath  
  Pen-test and traffic capture tools for embedded testing.


### 24F. Production Jigs, Programming Tools, Boundary-Scan & Functional Test Rigs (Free / Open-Source)

#### ✅ Production Programming & Flashing Tools

- **OpenOCD (Open-Source Debug & Flash Tool)** — http://openocd.org  
  Free flashing/debugging for ARM Cortex-M, RISC-V, ESP32, STM32, NXP, Nordic with SWD/JTAG. Works on low-cost probes (ST-Link, J-Link EDU, FT2232).

- **PyOCD (Free)** — https://github.com/pyocd/pyOCD  
  Python-based flashing & debug for Cortex-M microcontrollers. Ideal for automated production scripts.

- **esptool.py (Free)** — https://github.com/espressif/esptool  
  Free ESP8266/ESP32 flashing, secure boot provisioning, eFuse burning, encryption, production batch tools.

- **STM32CubeProgrammer (Free)** — https://www.st.com  
  Free flashing over UART/SWD/JTAG/USB-DFU. Works in scripts for automated factory programming.

- **nRF Util & Programmer (Free)** — https://www.nordicsemi.com  
  Scriptable DFU, JTAG/SWD flashing, secure boot signing and mass production programming.

- **Renesas Flash Programmer (Free tier)** — https://www.renesas.com  
  Free tool for RA/RL/RX MCUs, supports secure boot signing and OTP programming.

- **UF2 Bootloader (Open-Source)** — https://github.com/microsoft/uf2  
  Mass-production friendly drag-and-drop firmware flashing for RP2040, SAMD, nRF, ESP32-S3.

- **Teensy Loader / TyCommander (Free)** — https://github.com/Koromix/tytools  
  Automates programming and serial log capture for PJRC Teensy in production.


#### ✅ Boundary-Scan, JTAG Chains & Board Bring-Up

- **UrJTAG (Open-Source)** — http://urjtag.org  
  Open JTAG/boundary-scan for testing solder joints, reading IDCODE, toggling GPIO pins on many MCUs/FPGAs.

- **OpenOCD JTAG Chain Scans** — built-in support  
  Detects JTAG chains, IDs multiple devices, verifies soldering in production.

- **JTAGenum (Open-Source)** — https://github.com/cyphunk/JTAGenum  
  Finds unknown JTAG pinouts on PCBs — useful when reverse-engineering boards.

- **Boundary Scan with BSDL Files (Free)**  
  Many vendors provide BSDL files free for continuity & net testing (NXP, ST, TI, Microchip).


#### ✅ Automated Production Test Frameworks

- **OpenHTF (Google)** — https://github.com/google/OpenHTF  
  Python-based automated test stations for factories. Logging, USB/UART control, sensor verification, pass/fail reports.

- **pytest + pySerial Test Rigs (Free)** — https://github.com/pyserial  
  Automate UART/CAN/I2C/USB tests, compare golden sample logs, verify responses.

- **Robot Framework (Free)** — https://robotframework.org  
  Scriptable test automation for gateways, embedded Linux and serial devices.

- **LabVIEW Community Edition (Free for Personal/Non-Commercial)** — https://www.ni.com  
  Full drag-and-drop test automation for hobby / non-profit labs.


#### ✅ Bed-of-Nails, Test Fixtures & Probe Boards (Open Designs)

- **Open Fixture Project** — https://github.com/OpenFixture  
  Open-source mechanical designs for spring-pin bed-of-nails jigs.

- **KiCad Testpad Generators** — https://kicad.org  
  Free plugins to auto-generate test pads, pogo-pin interfaces and net coverage checks.

- **OpenJig (Community Project)** — https://github.com/DoESLiverpool/OpenJig  
  Open mechanical fixture library for PCBs, pogo pin layouts, clamps and alignment pins.

- **3D-Printed Test Cages / Pogo Fixtures (Free CAD)** — https://github.com  
  Hundreds of open designs for alignment jigs, multi-board testing frames.


#### ✅ Device Provisioning, Serial Numbering & Logging

- **OpenHTF + SQLite/CSV Logging (Free)**  
  Store serial numbers, MAC addresses, test results, firmware versions in local DB.

- **Python Barcode & QR Generators (Free)** — https://github.com/lincolnloop/python-qrcode  
  Auto-generate QR labels for serial tracking and manufacturing traceability.

- **Zebra label printing scripts (Free)** — https://github.com  
  Free Python scripts to print production labels via ZPL.

- **OTP & Secure Key Injection Tools (Vendor Free SDKs)**  
  - ESP32: eFuse + secure boot provisioning via esptool.py  
  - STM32: SBSFU + OTP programming via CubeProgrammer  
  - Microchip: CryptoAuthLib for ATECC secure element injection


#### ✅ Firmware Validation, Golden Sample & Regression Testing

- **Serial Test Harness (Free)** — Python + PyTest + OpenHTF  
  Compare real device output vs. golden reference automatically.

- **Power-on Self-Test Logging (Free Samples)** — https://github.com  
  Open-source POST templates for verifying Flash, RAM, sensors on boot.

- **AteCC608A / SE05x Secure Element Test Kits (Free SDK)** — https://github.com/MicrochipTech / https://github.com/NXPMicro  
  Verify crypto signatures, cert chains, secure boot provisioning in production.


#### ✅ Commercial Hardware Supported by Free Software

- **SEGGER J-Link (Free J-Flash Lite)** — https://www.segger.com  
  Free programming tool (no license) for single-image flash on STM32, Nordic, NXP, etc.

- **ChipWhisperer-Lite (Open Hardware)** — https://chipwhisperer.io  
  Hardware-level glitching and side-channel testing with free software.

- **LibUSB Open Flashers (Free)** — https://libusb.info  
  Control USB programmers and load firmware in automated CI.

## 25. Hobbyist-Friendly Prototyping Ecosystems

### 25A. Rapid Prototyping Boards, Ecosystems & Kits (Free SDKs / IDEs / Tutorials)

- **Arduino Ecosystem (Free IDE + Libraries)** — https://arduino.cc  
  Massive open-source ecosystem for rapid firmware prototyping. Free IDE, libraries, drivers, bootloaders, and examples.

- **ESP32 / ESP-IDF (Free SDK)** — https://www.espressif.com  
  Low-cost Wi-Fi/BLE embedded SoC. Free RTOS-based SDK, Arduino core, cloud examples, OTA, secure boot, crypto.

- **Raspberry Pi + Raspberry Pi OS (Free)** — https://www.raspberrypi.com  
  Single-board Linux computers with GPIO, SPI, I2C, CSI/DSI. Free OS, Python libraries, camera support.

- **Raspberry Pi Pico (RP2040) + Free C SDK** — https://github.com/raspberrypi/pico-sdk  
  Dual-core M0+ MCU, free C SDK and MicroPython. Excellent for low-cost prototyping.

- **MicroPython (Free)** — https://micropython.org  
  Python on MCUs (STM32, ESP32, RP2040, NRF52). Free firmware, REPL, sensor drivers.

- **CircuitPython (Adafruit, Free)** — https://circuitpython.org  
  Python for STEM/prototypes. 300+ free libraries for sensors, displays, BLE.

- **Adafruit Feather Ecosystem** — https://adafruit.com  
  Wide range of MCU/LoRa/BLE/GPS/RTC “Feather” boards. Free CircuitPython & Arduino libraries.

- **SparkFun Qwiic Ecosystem** — https://sparkfun.com  
  I2C plug-and-play sensors and modules. Free Arduino/Python drivers + PCB KiCad files for many boards.

- **Seeed Studio Grove Ecosystem** — https://wiki.seeedstudio.com  
  Plug-and-play sensors and actuators with free Arduino, Python, and ESP32 examples.

- **Particle Photon / Argon (Free Particle Cloud Tier)** — https://particle.io  
  Wi-Fi/LTE IoT modules with free cloud tier, OTA, dashboards, and open-source DFU tools.

- **STM32 Nucleo/Discovery (Free STM32Cube Tools)** — https://www.st.com  
  Nucleo boards with Arduino headers + free HAL/LL drivers, CubeMX code gen, USB, sensors.

- **Nordic nRF52 DKs (Free SDK)** — https://www.nordicsemi.com  
  BLE/Thread/Matter prototyping boards with free SDK, secure DFU, power profiler tools.

- **M5Stack (Extensible ESP32 System)** — https://m5stack.com  
  ESP32-based modular stackable IoT kits with free UIFlow, Arduino and ESP-IDF support.

- **OpenMV Cam (Free IDE)** — https://openmv.io  
  Tiny AI camera for prototypes. Free IDE, face/object detection, ML, AprilTags, I/O.

- **PyCom Boards (Free MicroPython SDK)** — https://pycom.io  
  Wi-Fi + BLE + LoRa + LTE NBIoT modules for IoT prototypes with Python APIs.

- **BBC micro:bit (MakeCode Free)** — https://microbit.org  
  Education-friendly ARM MCU with free block coding, Python and Bluetooth support.

- **Wio Terminal (Seeed, Free)** — https://wiki.seeedstudio.com/Wio-Terminal-Getting-Started/  
  Arduino + MicroPython with LCD, sensors, BLE/Wi-Fi add-ons. Free drivers/projects.

- **BeagleBone Black/AI (Free)** — https://beagleboard.org  
  Open hardware Linux SBCs with PRUs, industrial I/O, robotics libraries.

- **Coral Dev Board (Google, Free Edge TPU SDK)** — https://coral.ai  
  TensorFlow Lite acceleration on-device, free compiler + model zoo.

- **Jetson Nano Developer Kit (Free JetPack SDK)** — https://developer.nvidia.com/embedded  
  Linux SBC with CUDA and DeepStream. Free AI vision pipelines.

- **PYNQ FPGA Boards (Free Python + FPGA Overlays)** — http://www.pynq.io  
  Python control of FPGA accelerators. Free overlays for CV, crypto, DSP.

- **Tinkerforge Ecosystem (Open-Source)** — https://www.tinkerforge.com  
  Modular industrial-grade plug modules with free APIs (Python/C/C#/MATLAB).

- **Tessel 2 (Open Hardware)** — https://tessel.io  
  JavaScript on embedded Linux; GPIO, I2C, SPI with free Node.js libraries.

- **OpenEnergyMonitor (Free Hardware + Firmware)** — https://openenergymonitor.org  
  Arduino/RPi-based energy monitoring ecosystem with free dashboards, power libraries.

- **Eurorack modular electronics DIY (Open Designs)** — https://github.com  
  Hundreds of free schematics/firmware for hobby electronics & synthesis modules.

- **TinyPICO / FeatherS3 (Open Source)** — https://github.com/UnexpectedMaker  
  ESP32-S3 boards with open-source hardware, Arduino & ESP-IDF support.

### 25B. Plug-and-Play HATs, Shields, Click Boards & Modular Sensor Ecosystems (Free Drivers/Libraries)

- **Raspberry Pi HAT Ecosystem (Free Drivers)** — https://www.raspberrypi.com  
  Huge collection of open HATs for displays, sensors, motor control, PoE, LoRa, SDR. Free Linux drivers, Device Tree overlays.

- **Arduino Shields (Open-Source Hardware + Libraries)** — https://arduino.cc  
  Motor shields, sensor shields, Ethernet/Wi-Fi, GPS, GSM, relay boards — all with free Arduino libraries.

- **micro:bit Edge Connectors + Shields** — https://microbit.org  
  Plug-and-play expansion boards for LEDs, motors, sensors. Free MakeCode + MicroPython drivers.

- **micro:bit Grove Shield + Qwiic Adapters** — https://wiki.seeedstudio.com  
  Connect Grove/Qwiic sensors directly to micro:bit with free example codes.

- **Adafruit FeatherWings (Open-Source)** — https://adafruit.com  
  Modular stackable wings: OLEDs, motor drivers, GPS, LoRa, sensors. Free CircuitPython/Arduino libraries.

- **SparkFun Qwiic System** — https://sparkfun.com  
  I²C plug-and-play sensors (IMU/ENV/GPS/PM). Free Arduino/Python drivers, KiCad files available for many modules.

- **Seeed Grove Plug-and-Play System** — https://wiki.seeedstudio.com  
  Simple connectors for hundreds of sensors/actuators. Free drivers in Arduino, MicroPython, ESP32, STM32.

- **MikroElektronika Click Boards (Open Drivers)** — https://www.mikroe.com/click  
  1000+ Click modules (BLE, LoRa, GNSS, ENV sensors). Free MikroSDK & Arduino/ESP32 libraries.

- **Pimoroni Breakout Garden** — https://shop.pimoroni.com  
  Slot-based plug boards for Pi, Pico, ESP32. Free MicroPython/Arduino drivers.

- **Pimoroni PICO HAT-based Ecosystem**  
  IMU, ToF, RGB, motor drivers for RP2040 and ESP32 boards. Fully open-source firmware.

- **M5Stack Units & HATs** — https://m5stack.com  
  Modular sensors, LoRa, RFID, UWB, GPS with UIFlow, Arduino, ESP-IDF drivers.

- **Grove Industrial Sensors (4-20 mA / RS485)** — https://wiki.seeedstudio.com  
  Free Modbus RTU and 4–20 mA interface examples (Arduino, STM32, ESP32).

- **Qwiic-to-Feather & Grove-to-Pi Bridges** — free open hardware adapters  
  Let you mix ecosystems — all with free example code.

- **SparkFun MicroMod Ecosystem** — https://sparkfun.com/micromod  
  Swappable processor boards (ESP32 / NRF52 / RPi RP2040). Free Arduino/Python drivers.

- **Pololu Robotics Plug-In Modules** — https://pololu.com  
  Motor controllers, IMU, regulators — all with free Arduino/C libraries.

- **Adafruit STEMMA / STEMMA-QT** — https://learn.adafruit.com  
  USB-C + Qwiic/Grove-compatible sensors with free open-source drivers.

- **Adafruit Crickit (Robotics HAT)** — https://learn.adafruit.com/adafruit-crickit  
  Robotics I/O: motors, servos, capacitive touch, speaker. Free CircuitPython/Arduino SDKs.

- **Open-Source Motor Shields (L298N/TB6612FNG)** — https://github.com  
  Free Arduino/ESP32 code and PCB files widely available.

- **Dragino LoRa I/O HATs & Shields (Free SDK)** — https://www.dragino.com  
  LoRaWAN modules for Pi, Arduino, ESP32 with free AT/OpenWRT SDKs.

- **Seeed LoRa-E5 Dev Boards + Grove Modules** — https://wiki.seeedstudio.com  
  LoRaWAN + STM32WLE MCUs with free LoRaMac-node stack and HAL drivers.

- **Particle Feather Wings (Free Particle Cloud Tier)** — https://particle.io  
  BLE/LTE/WiFi wings with OTA, cloud rules, free developer tier.

- **Waveshare HATs/Breakouts (Free Libraries)** — https://www.waveshare.com  
  E-Ink, displays, sensors, motor drivers — free C/Python examples for Pi/Pico/ESP.

- **Open-Source CANBus & OBD-II Shields** — https://github.com  
  MCP2515, MCP2551 CAN modules with free drivers.

- **Open-Source RS485 Modbus Shields** — https://github.com  
  Free libraries for industrial sensor integration (Modbus RTU).

- **USB-C PD Trigger / Power Boards (Open Designs)** — https://github.com  
  Open hardware Type-C power modules for prototyping power systems.

- **IKEA VINDRIKTNING / TRÅDFRI Hacks (Open Firmware)** — https://github.com  
  Open-source firmware and sensor expansions turning consumer gadgets into prototyping modules.

- **Wio Terminal + Grove Sensors (Free Drivers)** — https://github.com/Seeed-Studio  
  LCD-equipped rapid prototyping platform with drag-and-drop sensor kits.

- **OpenEnergyMonitor Shields** — https://openenergymonitor.org  
  Energy monitoring shields and nodes with free firmware + dashboards.

- **NCD Industrial I/O boards (Free Libraries)** — https://ncd.io  
  RS485, MQTT, I2C industrial sensor modules with free cloud dashboards.

### 25C. Hobby-Grade Robotics Stacks & Maker-Friendly Robot Kits (Free Firmware / Libraries)

- **TurtleBot 3 (Open-Source Robot)** — https://turtlebot3.robotis.com  
  Affordable modular ROS robot platform with LiDAR + SLAM. Free ROS1/ROS2 firmware, CAD, navigation stacks, teleop.

- **TurtleBot 4 (With Raspberry Pi + ROS2)** — https://turtlebot4.ros.org  
  Budget ROS2 AMR with Nav2, OpenCV, SLAM, depth camera. Free mapping & navigation packages.

- **Open Source Rover (JPL / NASA)** — https://github.com/nasa-jpl/open-source-rover  
  Full 6-wheel rocker-bogie Mars Rover clone. Free CAD, BOM, firmware, Python control, vision modules.

- **OpenMower (DIY Robot Lawn Mower)** — https://github.com/ClemensElflein/OpenMower  
  Free RTK GPS robot mower platform with open firmware, CAD and motor control.

- **DIY “DonkeyCar” (Autonomous RC Car)** — https://www.donkeycar.com  
  Raspberry Pi + camera self-driving RC car platform. Free Python, deep-learning steering model, datasets.

- **OpenDog / SpotMicro (Quadruped Robot, Open Hardware)** — https://github.com/spotmicro/spotmicro  
  Open-source quadruped hardware + servo drivers + ROS support.

- **OpenCat (Nyanko/Max)** — https://github.com/PetoiCamp  
  Open-source robotic cat using ESP32/Arduino servos. Free locomotion firmware and Mobile app.

- **3DoT / Romi / Mini-Sumo Robot Kits (Free Code)** — https://pololu.com  
  Small wheeled robots with free Arduino/Nucleo sample firmware and line-following/IMU sensors.

- **OTTO DIY Humanoid / Biped Robots (Open Firmware)** — https://ottodiy.com  
  Fully open-source 3D printable humanoid robots with free Arduino libraries and servo control.

- **M5Stack RoverC / M5CardPrinter / ServoBots** — https://m5stack.com  
  ESP32 robots with free drivers, UIFlow, micropython control, and expansion kits.

- **ESP32 Line-Follower & Maze Solvers (Free Reference Projects)** — https://github.com  
  Open codebases for PID line following, optical encoding, wall following.

- **PiCar-X / PiCar-S (SunFounder)** — https://github.com/sunfounder  
  Raspberry Pi autonomous robotics kits with free Python/ROS examples and camera tracking.

- **Raspberry Pi “Arducam PTZ Camera Robot” (Free)** — https://github.com/ArduCAM  
  PTZ robot rover with face tracking and streaming code.

- **JetBot (NVIDIA Jetson Nano)** — https://github.com/NVIDIA-AI-IOT/jetbot  
  Open-source autonomous robot with free AI modules for object avoidance, person tracking.

- **Arduino Control of Continuous Rotation Servos (Free Libraries)** — https://github.com/arduino-libraries  
  Free libraries for servo robotics, wheel encoders, IMU balancing.

- **L298N/TB6612 Motor Driver Shields (Open Libraries)** — https://github.com  
  Free motor control libraries for line bots, robot arms, mobile robots.

- **OpenMV Robot Kits** — https://openmv.io  
  Vision-enabled robots with face/object detection, line tracking. Free MicroPython firmware.

- **DFRobot Robot Platforms (Free Sample Code)** — https://github.com/DFRobot  
  Track robots, mecanum wheels, line followers with free Arduino/ESP32 libraries.

- **Seeed JetRacer & JetBot Kits (Free ROS/AI)** — https://wiki.seeedstudio.com  
  Free ROS / AI inference notebooks for racing robots and autonomous navigation.

- **Open-Source Balancing Robot Libraries** — https://github.com  
  Free PID control implementations for 2-wheel self-balancing bots with MPU6050/BMI160.

- **Raspberry Pi Pico “TinyRobot” Projects (Free)** — https://github.com  
  Free MicroPython + motor driver examples for cheap robot builds.

- **Lego Mindstorms EV3dev (Linux + Python, Free)** — https://www.ev3dev.org  
  Turn Mindstorms into open Linux-based robot platform with Python + ROS tools.

- **Blockly / MakeCode Robots (Free)** — https://makecode.microbit.org  
  Block-based robotics coding for micro:bit, ESP32, Adafruit, Lego.

- **Robot Operating System on Pi/ESP32 (micro-ROS, Free)** — https://micro-ros.github.io  
  Run ROS2 nodes directly on micro-controllers for hobby robotics.

- **Open-Source Robotic Arm Kits (uArm, EEZYBotARM)** — https://github.com  
  3D printable robotic arms with free Python/Arduino/ROS control.

### 25D. Multi-Sensor Data Loggers, Wearables & Maker-IoT Boards (Free Firmware / SDKs)

#### ✅ Multi-Sensor Data Loggers (Environmental, Motion, GPS)

- **OpenLog / OpenLog Artemis (SparkFun)** — https://github.com/sparkfun/OpenLog_Artemis  
  Low-power IMU/environmental data logger with free open-source firmware, CSV logging to microSD, Arduino IDE support.

- **SparkFun 9DoF IMU + Datalogger Shields (Free Code)** — https://github.com/sparkfun  
  Plug-and-play IMU logging for Arduino/ESP32/Pi; free libraries for MADGWICK/Mahony fusion and CSV output.

- **StratoLogger / High-Altitude Logger (Open Projects)** — https://github.com  
  Open-source altimeter + IMU loggers for balloons and drones.

- **OpenEnergyMonitor emonTx / emonPi** — https://openenergymonitor.org  
  Open-source electricity + environmental logging with free dashboards and MQTT/Influx publishers.

- **Adafruit Feather + Data Logging Wing (Free Libraries)** — https://learn.adafruit.com  
  MicroSD + RTC plug-in wings with open-source firmware for sensor data collection.

- **OpenDAQ Projects (Free)** — https://github.com  
  Community dataloggers for CO2, PM2.5, IMU, GPS with Arduino/ESP32 code.

- **Balena Sense (Free)** — https://github.com/balena-io-projects/balena-sense  
  Raspberry Pi multi-sensor logger with free dashboard + InfluxDB + Grafana in Docker, zero code required.

- **Wio Terminal Data Logger (Free Example Codes)** — https://wiki.seeedstudio.com  
  LCD + IMU + environmental sensors + microSD with ready logging firmware.

- **Qwiic/Grove Sensor Loggers (Free)** — https://sparkfun.com / https://wiki.seeedstudio.com  
  One-line examples to log any I2C sensor to CSV/JSON using ESP32 or RP2040.

---

#### ✅ GPS / GNSS / Tracker Boards

- **Adafruit Ultimate GPS + Datelogger (Free Libraries)** — https://learn.adafruit.com  
  Free Arduino/Python libraries, NMEA parsing, time stamping, SD storage.

- **uBlox GPS Modules (Free u-Center Tools)** — https://www.u-blox.com  
  NMEA logging, GNSS configuration, Bluetooth/GPS experiments with free u-center PC software.

- **ESP32 + A9G/A7 GPS Tracker Projects (Free)** — https://github.com  
  Open-source firmware for low-cost GPS+GSM trackers, MQTT uploads, SD logging.

- **Pi + GPS HATs (Free Drivers)** — https://github.com/raspberrypi  
  Open-source Linux drivers and PPS timing support.

- **OpenNTRIP / RTKLIB (Free)** — https://rtklib.com  
  Open-source RTK + GPS/GLONASS/Galileo correction logging for high-accuracy survey/robotics.

---

#### ✅ Wearables & Health Sensor Platforms (Free Firmware)

- **Arduino Nicla Sense ME** — https://store.arduino.cc  
  Bosch environmental + IMU + pressure sensors with free Edge-ML examples and logging code.

- **Xiao nRF52 / Xiao ESP32S3 (Seeed)** — https://wiki.seeedstudio.com  
  Super-tiny wearable boards with free sensor libraries, BLE, battery support, IMU logging.

- **LilyGO T-Watch Series (Free ESP-IDF/Arduino Code)** — https://github.com/Xinyuan-LilyGO  
  Open-source smartwatch platforms with IMU, GPS, BLE, Wi-Fi and SD logging.

- **DFRobot Beetle BLE & Beetle ESP32C3** — https://github.com/DFRobot  
  Tiny wearable IoT boards with free drivers and Arduino libraries.

- **MyOpenEEG / OpenBCI (Open Hardware)** — https://openbci.com  
  Open-source EEG/biometric wearable logging with free Python/GUI tools.

- **MAX30102 / MAX86150 Wearable Bio-Sensor Libraries** — https://github.com/oxullo  
  Free SpO2 + heart-rate logging libraries for ESP32/Arduino.

- **Xsens DOT (Free SDK)** — https://www.xsens.com  
  Bluetooth inertial wearables with free mobile/PC SDK for IMU streaming and logging.

---

#### ✅ BLE / Wireless IoT Boards for Field Logging

- **ESP32-C3 / ESP32-S3 (Free ESP-IDF & Arduino)** — https://github.com/espressif  
  Wi-Fi+BLE logging, OTA updates, HTTPS cloud uploads, SD card data logging.

- **nRF52840 DK (Free nRF Connect SDK)** — https://www.nordicsemi.com  
  BLE/Thread/Matter with low-power IMU/ENV loggers, secure DFU, free power profiler.

- **Particle Argon/Boron (Free Cloud Tier)** — https://particle.io  
  BLE/LTE/Wi-Fi boards with free OTA, console logs, dashboards, rule engine.

- **Helium/LoRa Tracker Nodes (Free Arduino/LMIC)** — https://github.com  
  Open-source LoRa trackers with GPS + IMU + SD card.

---

#### ✅ Open-Source Wearable OS / Frameworks

- **FreeRTOS Wearable Templates** — https://github.com/FreeRTOS  
  Free RTOS + sensor + BLE logging templates.

- **Zephyr SensorHub (Free)** — https://github.com/zephyrproject-rtos  
  Free driver stack for IMU/ENV sensors, BLE logging, power optimization.

- **Espruino (Free JavaScript on MCU)** — https://www.espruino.com  
  Wearable-friendly JavaScript firmware with free logging libraries.

---

#### ✅ Companion Dashboards & Mobile Apps (Free)

- **Blynk (Free Community Tier)** — https://blynk.io  
  Mobile dashboards for BLE/WiFi IoT loggers (ESP32, Arduino, STM).

- **Adafruit IO (Free Tier)** — https://io.adafruit.com  
  Free cloud logging dashboards for Feather, ESP32, Raspberry Pi.

- **Grafana (Open-Source)** — https://grafana.com  
  Free dashboards for long-term sensor logging (InfluxDB, MQTT, SQLite).

- **Node-RED Dashboard (Free)** — https://nodered.org  
  Real-time charts for BLE/WiFi/GPS loggers.

### 25E. DIY Electronics Essentials — Power Modules, Prototyping PCBs, Soldering & Lab Tools (Free/Open)

#### ✅ Breadboard Power Modules & Safe Power Supplies

- **Open-Source Breadboard PSU (LM1117/AMS1117 designs)** — https://github.com  
  5V/3.3V regulated plug-in PSU modules; open PCB + BOM for beginners.

- **USB-C PD Trigger Boards (Open Hardware)** — https://github.com  
  Power breadboard circuits from USB-C chargers (5V/9V/12V/15V/20V). Free open-source KiCad files.

- **Open DC-DC Buck Boost Modules (MT3608/MP1584)** — https://github.com  
  Free PCB designs and test code for adjustable 3.3V/5V rails in prototyping.

- **Open UPS for Raspberry Pi (Free Designs)** — https://github.com  
  UPS HATs with supercaps/Li-ion charging, free firmware + PCB.

- **USB Safety Testers (Open)** — https://github.com/ava702  
  Open USB-C/USB-A power measurement dongles for current/voltage logging.

- **Open-Source Lithium Charging Boards (TP4056/MCP73831)** — https://github.com  
  Free PCB layouts and safe-charge firmware examples for IoT prototypes.

---

#### ✅ Universal Prototyping PCBs & Adapter Boards

- **Open-Source Breakout Boards (KiCad)** — https://github.com  
  Thousands of free footprints: QFN → DIP, QFP → DIP, SOIC → DIP for breadboard testing.

- **Proto Hat / Proto Shield (Free Designs)** — https://github.com  
  Open HATs/shields with GPIO breakout, SD, power rails for Raspberry Pi / ESP32 / Arduino.

- **Open Breadboard PCB (Free KiCad)** — https://github.com/ai03-2725/OpenBreadboard  
  Open hardware PCB that routes like a soldered breadboard.

- **Feather/Qwiic/Grove Adapter Boards (Free Hardware)** — https://github.com  
  Convert between ecosystems; free KiCad + BOM.

- **Solderable Breadboards (Stripboard/Perfboard CAD)** — https://github.com  
  Open Perfboard/Veroboard footprint files for planning production-ready prototypes.

---

#### ✅ Soldering, Hot-Air, Reflow & Rework (Open Tools)

- **TS100 / TS80P Open Firmware (IronOS)** — https://github.com/Ralim/IronOS  
  Open-source firmware for portable soldering irons with PID control, sleep mode, OLED UI.

- **Miniware Hot-Air & Iron Tools (Open Firmware)** — https://github.com/DmytroBashativ  
  Free open firmware for temperature control and profiles.

- **Reflow Oven Controller (Open Hardware)** — https://github.com/UnifiedEngineering/Reflowduino  
  Open-source PID temperature controller for converting toaster ovens into SMT reflow ovens.

- **OpenPnP (Free Pick-and-Place Software)** — https://openpnp.org  
  Free machine vision-based PnP software for DIY small-run PCB assembly machines.

- **USB Microscope Open-Source Software** — https://github.com  
  Free capture + measurement tools compatible with cheap USB microscopes.

---

#### ✅ Hand Tools, Test Jigs, Fixtures & CAD

- **3D-Printed PCB Holders / Solder Jigs (Free STL)** — https://thingiverse.com  
  Open mechanical fixtures for soldering headers, pogo pins, programming connectors.

- **Open-Source PCB Clamps & Third-Hand Tools** — https://github.com  
  Fully printable clamps for rework, soldering and strain relief.

- **Cable Harness & Crimp Tools (Free Guides)** — https://github.com  
  Open wiring guides + pinout libraries for JST, Dupont, Molex, automotive connectors.

- **Open Test-Point & Pogo-Pin Holders** — https://github.com  
  Free designs for test cages, hinge jigs, alignment fixtures.

- **Open-Source Wire Strippers & Mini Tools (STL files)** — https://thingiverse.com  
  Printable cable cutters, wire gauges and dispensers.

---

#### ✅ Open Multimeter & Instrument Firmware/Tools

- **Sigrok Meter Support (Free)** — https://sigrok.org  
  Many low-cost DMMs supported for PC logging, CSV export, calibration UI.

- **Open-Hardware Multimeter Projects** — https://github.com/OpenDMM  
  Open-source DMM with KiCad schematics and firmware.

- **USB-to-UART/RS485 Breakouts (Free Designs)** — https://github.com  
  Open FT232/CH340/CP2102 adapter boards for breadboards and test rigs.

---

#### ✅ Breadboard-Friendly Microcontrollers & ISP Tools

- **CH552/CH32, ATTiny, STM32 “Blue Pill” Open Toolchains** — https://github.com  
  Free compilers, Arduino cores, USB bootloader scripts.

- **PICkit 3/4 Open-Source Alternatives (Free)** — https://github.com  
  DIY programmers for PIC/AVR devices with open firmware.

- **AVR ISP + USBasp (Open Hardware)** — https://github.com/obdev/usbasp  
  Open-source USB programmer for AVR chips, widely used by hobbyists.

---

#### ✅ Quick Prototyping Adapters & Debug Tools

- **Logic Level Shifter Boards (Open PCBs)** — https://github.com  
  Free PCBs for 1.8V ↔ 3.3V ↔ 5V I/O translation, open KiCad files.

- **SWD/JTAG Breakout Adapters (Free PCB Files)** — https://github.com  
  SWD pogo adapters, ST-Link headers, ESP32 programming docks.

- **Clip-On SOIC/SOP Test Clips (Community Firmware)** — https://github.com  
  Free SPI flash dump/program scripts for SOIC clips + flashrom.

- **flashrom (Open-Source)** — https://flashrom.org  
  Free command-line flashing tool for SPI NOR chips using USB programmers.

## 26. Open-Source Cloud Backend Templates for IoT

### 26A. Ready-to-Deploy Open-Source IoT Backends (Self-Host / Free)

- **ThingsBoard Community Edition (Open-Source)** — https://thingsboard.io  
  Fully-featured IoT backend: MQTT/HTTP/CoAP ingestion, dashboards, OTA, alarms, rule engine, device provisioning. Free CE for self-host and on Raspberry Pi.

- **Node-RED + Mosquitto + InfluxDB + Grafana Stack (All Free)** — https://nodered.org  
  Classic free open-source IoT backend combo. Real-time dashboards, MQTT flow-control, DB storage and alerts. Runs on Pi, Docker, VM.

- **EMQX Community Edition (Free)** — https://www.emqx.io  
  Enterprise-grade MQTT broker with clustering, MQTT5, rule engine, SQL-based routing and dashboards. Free CE up to unlimited devices.

- **ChirpStack (LoRaWAN Stack, Open-Source)** — https://www.chirpstack.io  
  Free LoRaWAN Network Server + device registry + gateway management + MQTT integration + dashboards.

- **Mainflux (Cloud-Native IoT Platform, Open-Source)** — https://mainflux.com  
  Secure, microservices-based IoT backend with MQTT/HTTP/CoAP, dashboards, device management, and integrations.

- **Kaa IoT Platform CE (Open-Source)** — https://www.kaaiot.io  
  Production-quality IoT platform with device twins, telemetry, dashboards, firmware updates. Free Community Edition.

- **OpenRemote (Open-Source, Smart City + BMS + IoT)** — https://openremote.io  
  Complete IoT suite with rules, dashboards, multi-tenant support. Free Manager for self-host.

- **Home Assistant (Open-Source)** — https://www.home-assistant.io  
  IoT automation and dashboards for smart building/edge. MQTT, Modbus, Zigbee, BLE. Free and self-hostable.

- **OpenHAB (Free, Open-Source)** — https://openhab.org  
  Local-first IoT backend for automation and dashboards. Supports MQTT, KNX, Modbus, Zigbee.

- **Thingspeak (MathWorks – Free tier)** — https://thingspeak.com  
  Free cloud analytics + MATLAB scripting. Ideal for sensor dashboards and ML.

- **Eclipse Ditto (Digital Twin Backend, Free)** — https://www.eclipse.dev/ditto  
  Open-source digital twin platform with MQTT/REST/WS APIs for device management and shadows.

- **Eclipse Hono (IoT Messaging Platform, Free)** — https://www.eclipse.org/hono  
  Device connectivity and telemetry ingestion for HTTP/MQTT/CoAP/AMQP. Free and cloud-native.

- **Eclipse Kapua (IoT Management)** — https://www.eclipse.org/kapua  
  Open-source IoT cloud platform with device provisioning, telemetry, dashboards.

- **FIWARE IoT Backend Framework (Free)** — https://www.fiware.org  
  Modular smart city/edge IoT platform with context brokers and open APIs.

- **OpenIoT Platform (Research Grade, Free)** — https://github.com/OpenIoTOrg/openiot  
  Cloud-native IoT stack for device data, queries, analytics and cloud storage.

- **Domoticz (Free, Open-Source)** — https://www.domoticz.com  
  Lightweight IoT automation server with dashboards and scripting.

- **Mosquitto MQTT Broker (Free)** — https://mosquitto.org  
  Ultra-light MQTT broker for millions of devices; integrates with Node-RED & Grafana for a free backend.

- **VerneMQ (Free Community Edition)** — https://vernemq.com  
  Open-source MQTT broker with clustering and high concurrency.

- **CrateDB (Free Community)** — https://crate.io  
  Edge-friendly, time-series DB with SQL for IoT ingestion. Works with MQTT/REST.

- **Grafana + Loki Stack (Free OSS)** — https://grafana.com/oss  
  Dashboards + logs for IoT gateways or Linux edge devices.

- **devicehub.net (Open-Source Build)** — https://github.com/OpenIoTHub  
  Lightweight IoT backend for Raspberry Pi and ESP devices.

- **WiFiManager + Firebase DIY Backend (Free)** — https://github.com  
  Open templates for ESP32/ESP8266 logging to free Firebase tier.

- **InfluxDB Community Edition** — https://www.influxdata.com  
  Free time-series database, MQTT/MQTT-Telegraf ingestion, dashboards and alerts.

- **Prometheus (Free)** — https://prometheus.io  
  Metric-based IoT backend for embedded Linux devices, with Grafana dashboards.

- **OpenTSDB / RRDTool (Free)** — https://github.com/OpenTSDB  
  Time-series database for low-resource IoT gateways with free visualization.

- **Kubernetes IoT Edge Templates (Free Helm Charts)** — https://artifacthub.io  
  Ready-to-deploy Helm charts for MQTT brokers, InfluxDB, Grafana, Node-RED.

- **BalenaCloud (Free Tier for Developers)** — https://balena.io  
  OTA + container orchestration for Pi & edge nodes. Free tier for personal projects.

- **Open Horizon (IBM – Open-Source)** — https://github.com/open-horizon/anax  
  Distributed IoT/Edge orchestration with zero-trust and secure OTA. Free to self-host.

- **ThingsBoard Microservices Helm (Free)** — https://github.com/thingsboard/thingsboard-helm  
  Self-deploy IoT platform on Kubernetes with dashboards, OTA, rule engine.

- **NATS.io (Free)** — https://nats.io  
  Extremely fast MQTT-like messaging for IoT. Free, small-footprint, clusterable.

- **MQTT Sparkplug B (Open-Standard)** — https://www.eclipse.org/tahu  
  Open interoperability framework for industrial MQTT SCADA.

- **Open Source Zigbee2MQTT** — https://www.zigbee2mqtt.io  
  Free Zigbee gateway exposing sensors to MQTT/Node-RED/InfluxDB.

- **OpenThread Border Router** — https://openthread.io  
  Thread/Matter low-power mesh with free cloud integration.

- **OpenMQTTGateway** — https://github.com/1technophile/OpenMQTTGateway  
  Free gateway bridging BLE, LoRa, IR, RF433 to MQTT dashboards.

- **MySensors Gateway (Free)** — https://www.mysensors.org  
  Arduino sensor mesh to MQTT, Grafana, Influx.

- **Homebridge (Free)** — https://homebridge.io  
  IoT automation backend with NodeJS plugins.

- **IoTivity (Open-Source, OCF)** — https://iotivity.org  
  Secure IoT communication stack with free device identity & provisioning.

### 26B. MQTT + Dashboards + Device Management Bundles (Free / Open-Source / Self-Host)

#### ✅ Complete IoT Bundles (MQTT + DB + Dashboards + Rules)

- **ThingsBoard CE (MQTT + OTA + Rules + Dashboards)** — https://thingsboard.io  
  Out-of-the-box IoT platform with MQTT, CoAP, HTTP ingestion, OTA, alarms, device provisioning, rule engine, dashboards. Free Community Edition.

- **EMQX + Node-RED + InfluxDB + Grafana Stack (All Free)** — https://www.emqx.io  
  Production-grade MQTT5 broker with free rule engine → Node-RED for flows → InfluxDB for time-series → Grafana dashboards. Runs on Raspberry Pi or Docker in minutes.

- **ChirpStack + Mosquitto + Grafana (Open-Source)** — https://www.chirpstack.io  
  LoRaWAN server + MQTT broker + dashboard stack, free and self-hostable. Supports gateways, device registry, uplink/downlink rules.

- **Mainflux (MQTT/HTTP/CoAP + Dashboard)** — https://mainflux.com  
  Microservices-based IoT backend with device management, data persistence, JWT auth, and MQTT routing. Full open-source.

- **OpenRemote (MQTT + Dashboards + Rules Engine)** — https://openremote.io  
  Self-hosted cloud with automation rules, asset management, and MQTT broker integration. Used in smart cities & buildings. Fully open-source.

- **Kaa IoT Platform CE** — https://www.kaaiot.io  
  Device twins, dashboards, time-series storage, OTA, alerts. Fully free Community Edition.

- **Home Assistant + Mosquitto + InfluxDB + Grafana** — https://www.home-assistant.io  
  Local-first free IoT stack: MQTT broker, automation, dashboards, data logging and alerts. Works on Pi and Docker.

- **OpenHAB + Mosquitto** — https://openhab.org  
  Free automation & dashboard platform with MQTT binding. Stores sensor data, events, and charts.

- **FIWARE Smart IoT Stack** — https://www.fiware.org  
  Open-source context broker + MQTT ingestion + dashboards + analytics. Used in smart-city deployments.

- **Eclipse Kapua (MQTT + Device Mgmt + Analytics)** — https://www.eclipse.org/kapua  
  Free modular IoT cloud platform with messaging, dashboards, device registry, OTA options.

---

#### ✅ Lightweight Bundles for Raspberry Pi / Gateways

- **Balena Sense (MQTT + InfluxDB + Grafana)** — https://github.com/balena-io-projects/balena-sense  
  Runs sensors → MQTT → time-series DB → dashboards. One-click install on Pi.

- **Grafana + Loki (Logs) + Mosquitto (MQTT) + Telegraf** — https://grafana.com/oss  
  Fully open-source metrics + logs + MQTT ingestion for IoT gateways.

- **InfluxDB + Telegraf + Grafana (TIG Stack)** — https://github.com/influxdata  
  Very common free stack: MQTT → Telegraf → InfluxDB → Grafana dashboards.

- **Zigbee2MQTT → Node-RED → Grafana** — https://www.zigbee2mqtt.io  
  Free Zigbee bridge producing MQTT sensor events + visual dashboards.

- **Tasmota (MQTT-native firmware)** — https://tasmota.github.io  
  Free open-source firmware for ESP8266/ESP32 smart devices, integrates directly with MQTT brokers.

- **OpenMQTTGateway** — https://github.com/1technophile/OpenMQTTGateway  
  BLE, LoRa, IR, RF433 → MQTT gateway bridging many wireless devices into dashboards.

- **MySensors Gateway (MQTT-first)** — https://www.mysensors.org  
  Arduino sensor mesh → MQTT → dashboards.

---

#### ✅ Device Management, Provisioning & Twin Models (Free)

- **Eclipse Ditto (Digital Twin)** — https://www.eclipse.dev/ditto  
  MQTT/HTTP/WS Digital twins with JSON shadow storage, rules, and real-time updates.

- **Eclipse Hono** — https://www.eclipse.org/hono  
  MQTT/HTTP ingestion + identity + device credentials + device-to-cloud messaging. Free to self-host.

- **AWS IoT Greengrass Local (Free Local Mode)** — https://aws.amazon.com/greengrass  
  Local MQTT and rules engine on edge devices for free when operating offline.

- **Azure IoT Edge (Free Local Mode)** — https://azure.com/iotedge  
  Free for local message routing, MQTT ingestion, and containerized edge logic.

- **NATS.io (MQTT-like Broker + Streaming)** — https://nats.io  
  High-speed lightweight messaging for IoT; free clustering, ACL, TLS.

---

#### ✅ Docker-Compose Templates / Ready Deployments

- **Awesome IoT Stack (Free Templates)** — https://github.com/hobbyquaker/awesome-mqtt  
  Docker templates for MQTT + automation + visualization + storage.

- **IOTstack for Raspberry Pi** — https://github.com/gcgarner/IOTstack  
  Easy menu-driven installer: Mosquitto, Node-RED, InfluxDB, Grafana, ESPHome, Zigbee2MQTT.

- **Awesome Home Assistant Add-Ons (Free)** — https://github.com/home-assistant/addons  
  Free MQTT, Influx, Grafana, Prometheus, ESPHome, Zigbee2MQTT.

- **Node-RED Boilerplates (Free)** — https://github.com/node-red/node-red-docker  
  Quick-deploy MQTT + HTTP ingestion + dashboards + user auth.

---

#### ✅ Bonus: Free Cloud MQTT Brokers for Testing

- **Test.Mosquitto.org (Free Public Broker)** — https://test.mosquitto.org  
  Free public MQTT test broker for developers.

- **Hivemq Public Broker (Free)** — mqtt://broker.hivemq.com  
  Free MQTT 3.1.1 testing for devs.

- **EMQX Public Cloud Broker (Free Sandbox)** — https://www.emqx.com/en/mqtt/public-mqtt5-broker  
  Free MQTT5 sandbox with WebSocket support.

- **Shiftr.io Free Sandbox** — https://shiftr.io  
  Free visual MQTT dashboard for testing prototypes.

- **flespi MQTT Broker (Free Tier)** — https://flespi.com  
  Free MQTT broker + REST API for up to limited messages/devices.

### 26C. OTA Servers, Provisioning & Secure Firmware Distribution (Free / Open-Source)

#### ✅ Open-Source OTA Servers (Self-Host)

- **Eclipse hawkBit (Free/Open-Source)** — https://www.eclipse.org/hawkbit  
  Production-ready OTA server for embedded Linux & MCU devices. Campaign management, staged rollouts, rollback, device groups. Self-host for free.

- **Mender Community Edition (Open-Source)** — https://mender.io  
  Full OTA for Linux-based devices: A/B updates, delta updates, rollback, device inventory, fleet management. Entire server stack is free for self-host.

- **SWUpdate (Open-Source)** — https://sbabic.github.io/swupdate  
  OTA installer for embedded Linux: dual-bank, rollback, secure images, signed updates. Works with hawkBit or standalone.

- **RAUC (Open-Source)** — https://rauc.io  
  Robust A/B update system for embedded Linux with cryptographic signing & rollback. Can integrate with hawkBit.

- **BalenaCloud (Free Developer Tier)** — https://www.balena.io  
  OTA for fleets of Raspberry Pis & Linux gateways. Free tier for personal/development use with container-based updates.

- **OpenWRT + opkg Sysupgrade (Free)** — https://openwrt.org  
  Free OTA-like sysupdate system for IoT routers and gateways. Signed images, rollback scripts available.

- **Eclipse Kura (Free)** — https://eclipse.org/kura  
  IoT gateway platform with remote application updates via MQTT/REST.

- **ResinOS (Open) + balenaEngine** — https://github.com/balena-os  
  Open source OS enabling Docker OTA on embedded devices.

---

#### ✅ MCU / RTOS-Level Secure OTA

- **MCUboot (Open-Source)** — https://mcuboot.com  
  Cryptographically signed boot / OTA loader used by Zephyr, Mynewt, ESP32 ports, Nordic nRF Connect SDK.

- **Zephyr OS OTA (Free)** — https://zephyrproject.org  
  Built-in support for MCUBoot, DFU over BLE, USB, UART, and encrypted image updates.

- **Mynewt BLE Secure DFU (Free)** — https://mynewt.apache.org  
  Signed, encrypted DFU for BLE/MCU devices.

- **ESP-IDF OTA (Free)** — https://docs.espressif.com  
  A/B OTA partitions, HTTPS secure download, anti-rollback and image signing. Full open-source tooling.

- **ESP HTTP OTA + AWS IoT Core** (Free local mode) — https://github.com/espressif  
  ESP32 OTA via HTTPS + S3/mirror servers. Free CLI tools.

- **Nordic nRF Secure DFU (Open-Source)** — https://github.com/NordicSemiconductor/pc-nrfutil  
  Signed and encrypted updates over BLE, USB, serial. Works with nRF52832/840/9160.

- **STM32 SBSFU (Secure Boot & Secure Firmware Update)** — https://www.st.com  
  Free reference implementation for signed/encrypted OTA and secure boot.

- **MCUXpresso Secure OTA (NXP, Free)** — https://www.nxp.com  
  Free OTA, secure boot and image authentication in LPC/i.MX RT SDK.

- **Tuya Open-Source MCU OTA (Free)** — https://github.com/tuya  
  Free OTA firmware and tools for Tuya-ESP/Gateway MCUs.

---

#### ✅ Linux-Based Device Management With OTA

- **MENDER-ARTIFACT (Free CLI)** — https://github.com/mendersoftware  
  Create signed OTA images for Mender CE. A/B and delta updates.

- **HAWKBIT-UPDATER Agents (Free)** — https://github.com/eclipse/hawkbit  
  Free device-side updater for Linux SBCs and embedded gateways.

- **SWUpdate + CAN/RS485 Updates** — https://github.com/sbabic/swupdate  
  Free field-update templates over Ethernet, 4G, CAN, RS485.

- **RAUC + Yocto/Buildroot Integration** — https://rauc.readthedocs.io  
  Free integration into industrial Linux systems.

- **Debian APT + Repo-Signing (Free)** — https://wiki.debian.org/SecureApt  
  Fleet OTA through signed packages and private repos.

---

#### ✅ Device Provisioning / Key Injection (Free Tools)

- **mcumgr (Open-Source)** — https://github.com/apache/mynewt-mcumgr  
  Secure image management for MCUBoot, DFU, and key provisioning over UART/BLE.

- **esptool.py (Free)** — https://github.com/espressif/esptool  
  Burn secure boot keys, eFuses, flash encryption, encrypted OTA partitions.

- **nrfutil (Free)** — https://github.com/NordicSemiconductor/pc-nrfutil  
  Key generation, signing, DFU ZIP packages and device provisioning.

- **STM32CubeProgrammer CLI (Free)** — https://www.st.com  
  Scripted provisioning, OTP/fuses, secure-boot enabling, encrypted image flashing.

- **Microchip CryptoAuthLib (Free)** — https://github.com/MicrochipTech  
  Key injection and certificate provisioning to ATECC/Trust-Flex SEs.

- **TPM2-TSS Tools (Free)** — https://github.com/tpm2-software  
  Secure key provisioning, sealed storage, signing for Linux gateways.

---

#### ✅ Cloud + OTA (Free Tier Options)

- **Particle Cloud (Free Tier)** — https://particle.io  
  Free OTA for small fleets, device diagnostics, logs, variables, functions.

- **Tuya IoT Platform (Free Tier)** — https://developer.tuya.com  
  Free OTA updates, provisioning, cloud links for Tuya MCUs and Wi-Fi/BLE modules.

- **Golioth Developer Tier (Free)** — https://golioth.io  
  Zephyr-native cloud: OTA, logs, data streams. Free tier for development.

- **Blynk (Free Community Tier)** — https://blynk.io  
  Free OTA for ESP32/Arduino via Blynk.Air (limited dev tier).

---

#### ✅ Industrial / Fleet OTA (Open-Source Engines)

- **OTA Update with Kubernetes + balenaEngine** — https://github.com/balena-os  
  Container-based OTA for fleets of embedded Linux devices.

- **Yocto + RAUC + hawkBit** (Open-Source)  
  De-facto industrial pipeline for automotive/industrial devices. All free.

- **SWUpdate + U-Boot Verified Boot**  
  Secure chain-of-trust + signed A/B OTA images for ECUs, robotics, gateways.

### 26D. Low-Code / No-Code IoT Cloud Templates (Free / Open-Source / Free Tier)

#### ✅ Drag-and-Drop IoT Dashboards & Automation

- **Node-RED (Open-Source, Self-Host Free)** — https://nodered.org  
  Drag-and-drop flows for MQTT/HTTP/WebSockets/Modbus. Built-in dashboards, alerts, logging, APIs. Runs on Raspberry Pi, Docker.

- **Blynk (Free Community Tier)** — https://blynk.io  
  Mobile app + dashboards + over-the-air control for ESP32, Arduino, Raspberry Pi. Free tier for hobbyists.

- **ThingsBoard CE (Open-Source)** — https://thingsboard.io  
  Low-code rule engine, dashboards, OTA, alarms, device provisioning. Fully free to self-host.

- **Home Assistant (Free / Local-First)** — https://www.home-assistant.io  
  Drag-and-drop automation for MQTT, BLE, Zigbee, Modbus, KNX. Free dashboards and automations.

- **OpenHAB (Open-Source)** — https://openhab.org  
  Visual automation + rules for sensors, relays, HVAC, smart home IoT. Free dashboards and MQTT integration.

- **Freeboard (Open-Source)** — https://github.com/Freeboard/freeboard  
  Browser-based drag-and-drop IoT dashboard for MQTT, REST APIs, sensors. Fully free.

- **FRED – Cloud Node-RED (Free Tier)** — https://fred.sensetecnic.com  
  Node-RED hosted in the cloud with free tier for small flows and dashboards.

---

#### ✅ Device-to-Dashboard “No-code” Cloud Platforms

- **Thingspeak (Free)** — https://thingspeak.com  
  No-code dashboards + charts + MATLAB analytics. Free for academic/hobby use.

- **io.adafruit.com (Adafruit IO — Free Tier)** — https://io.adafruit.com  
  No-code dashboards, MQTT/Webhooks, triggers, data logs. Great for ESP32/Arduino.

- **Ubidots STEM (Generous Free Tier)** — https://ubidots.com/stem  
  Drag-and-drop dashboards, alerts, device management. Free tier for DIY/students.

- **MQTT Dash (Free App)** — Android MQTT dashboard app, no coding. Graphs, gauges, control switches.

- **MyDevices Cayenne (Free Maker Tier)** — https://developers.mydevices.com  
  No-code widgets for ESP32, Raspberry Pi, LoRaWAN. Drag-and-drop automation.

- **Grafana Cloud Free Tier** — https://grafana.com  
  Free limited dashboards + alerts for small projects. Works with MQTT → InfluxDB.

- **Tally + Webhooks + MQTT (Free Templates)** — https://tally.so  
  Zero-code dashboards & forms that ingest MQTT data through webhook adapters.

---

#### ✅ Automation + Webhooks + Integrations

- **IFTTT Maker Webhooks (Free Tier)** — https://ifttt.com  
  Trigger emails, SMS, Google Sheets, Telegram, based on sensor events.

- **Zapier Free Tier (Limited)** — https://zapier.com  
  MQTT → email → Slack → Google Sheets automation without code.

- **n8n.io (Open-Source)** — https://n8n.io  
  Fully free self-host workflow automation connecting MQTT/REST/Email/DB.

- **Huginn (Open-Source)** — https://github.com/huginn/huginn  
  Automation agents that watch MQTT feeds, APIs, weather, alerts — all free to self-host.

- **Node-RED + Telegram Bot (Free)**  
  Chatbot control for IoT devices using no-code flow templates.

---

#### ✅ No-code Apps / Visual Builders for Hardware

- **Arduino Cloud Free Tier** — https://cloud.arduino.cc  
  No-code dashboards, widgets, OTA, variables, and charts for Arduino/ESP32.

- **MIT App Inventor (Free)** — https://appinventor.mit.edu  
  Drag-and-drop Android app builder for IoT control over BLE/Wi-Fi/MQTT.

- **Kodular (Free Android App Builder)** — https://kodular.io  
  No-code Android apps connecting to MQTT/HTTP devices.

- **ESP RainMaker (Free)** — https://rainmaker.espressif.com  
  No-code provisioning + dashboards + Alexa/Google control for ESP32.

- **Tuya Cloud (Free Tier)** — https://developer.tuya.com  
  Zero-code provisioning, dashboards, OTA for Tuya Wi-Fi/BLE devices.

---

#### ✅ One-Click Deployable Templates (Docker Compose / Raspberry Pi)

- **IOTstack (Free)** — https://github.com/gcgarner/IOTstack  
  One-click installer for Mosquitto, Node-RED, InfluxDB, Grafana, Zigbee2MQTT.

- **BalenaBlocks (Free)** — https://www.balena.io/blocks  
  Pre-built Docker blocks for MQTT, dashboards, database, fleet OTA.

- **Awesome Home Assistant Add-Ons (Free)** — https://github.com/home-assistant/addons  
  One-click install: MQTT → Influx → Grafana → ESPHome → Zigbee2MQTT.

- **Mosquitto + Node-RED + Grafana Docker Bundle (Free)** — https://github.com  
  Community docker-compose templates for full IoT backend in one command.

---

#### ✅ Mobile Dashboards for Sensors (Free)

- **IoT MQTT Panel (Android — Free Tier)** — https://play.google.com  
  Live MQTT charts, gauges, controls for ESP32/RPi.

- **MQTT Explorer (Free)** — https://mqtt-explorer.com  
  GUI monitor for MQTT brokers with tree view and history.

- **Ruffy / BLE Serial Apps (Free)** — https://github.com  
  Quick BLE dashboard for hobby IoT.

### 26E. Self-Hostable Analytics & Visualization Bundles (Free / Open-Source)

#### ✅ Time-Series Databases (IoT-Friendly / Free)

- **InfluxDB Community Edition (Free & Open-Source)** — https://www.influxdata.com  
  High-performance time-series DB for sensor data. MQTT → Telegraf → Influx → Grafana is the classic free IoT stack.

- **TimescaleDB (Free Community Edition)** — https://www.timescale.com  
  PostgreSQL with time-series superpowers. Free community license; IoT metrics + SQL dashboards.

- **CrateDB (Free/Open)** — https://crate.io  
  Distributed SQL database optimized for IoT telemetry. Free community edition.

- **OpenTSDB (Free/Open)** — https://github.com/OpenTSDB  
  Time-series storage on top of HBase. Used for large-scale logging and IoT metrics.

- **RRDTool (Free)** — https://oss.oetiker.ch/rrdtool  
  Embedded-friendly round-robin DB for small gateways and SBCs.

- **Prometheus (Free/Open-Source)** — https://prometheus.io  
  Time-series metrics for embedded Linux/edge gateways. Often paired with Grafana free dashboards.

- **Druid (Apache)** — https://druid.apache.org  
  Fast columnar time-series DB with free SQL and dashboard plugins.

- **QuestDB (Free/Open-Source)** — https://questdb.io  
  SQL time-series engine with grafana support. Very fast ingestion.

---

#### ✅ BI Dashboards & Visualization Tools (Self-Host Free)

- **Grafana OSS (Free)** — https://grafana.com/oss  
  Industry-standard dashboarding for time-series. Free plugins, alerts, MQTT via Influx/Telegraf.

- **Apache Superset (Free/Open-Source)** — https://superset.apache.org  
  Modern BI dashboard for PostgreSQL, MySQL, Timescale, CrateDB, Mongo, etc.

- **Metabase (Free/Open-Source)** — https://metabase.com  
  Self-host dashboards and analytics for SQL/NoSQL. Ideal for internal, client or ops dashboards.

- **Redash (Free/Open-Source)** — https://redash.io  
  Lightweight SQL + charting dashboards for IoT telemetry. Works with InfluxDB, PostgreSQL, Timescale.

- **Chronograf (Free + Part of TICK stack)** — https://docs.influxdata.com/chronograf  
  Native InfluxDB dashboard and alert engine for IoT.

- **Kibana (Free / Elastic OSS)** — https://www.elastic.co/kibana  
  Visualization of logs, metrics, sensor traces. Pairs with Elasticsearch, beats, Logstash.

- **Loki + Grafana (Free/Open)** — https://grafana.com/oss/loki  
  Log storage and visualization for IoT gateways + edge computing.

- **Plotly Dash (Open-Source)** — https://plotly.com/dash  
  Self-host visual dashboards using Python.

- **Streamlit (Open-Source)** — https://streamlit.io  
  Build custom IoT dashboards with Python. Free to run locally or Docker.

---

#### ✅ Full “Analytics Bundles” (Plug-and-Play / Docker)

- **TIG Stack (Telegraf + InfluxDB + Grafana)** — https://github.com/influxdata  
  Free IoT monitoring bundle: MQTT ingestion, dashboards, alerts. Runs on Pi, PC, servers.

- **ELK Stack (Elasticsearch + Logstash + Kibana OSS)** — https://www.elastic.co  
  Open-source edition supports logs, metrics, dashboards for IoT & gateways.

- **MELT Stack (MongoDB + Express + Logstash + Telegraf + Grafana)** — https://github.com  
  Free Mongo-centric IoT logging and dashboards.

- **OpenTelemetry Collector (Free)** — https://opentelemetry.io  
  Free telemetry pipeline: ingest MQTT, gRPC, REST, export to Prometheus/Grafana.

- **QuestDB + Grafana Bundle** — docker-compose from QuestDB team  
  High-performance database + free dashboards for high-rate IoT sensors.

- **Druid + Superset Bundle** — https://github.com/apache/druid  
  Open-source analytic engine + BI dashboard for billions of events.

---

#### ✅ Self-Hosted MQTT + DB + Dashboard Starters

- **IOTstack (Free)** — https://github.com/gcgarner/IOTstack  
  Menu-based deployment for Mosquitto, Node-RED, Influx, Grafana, Zigbee2MQTT.

- **Awesome IoT Docker Templates (Free)** — https://github.com/hobbyquaker/awesome-mqtt  
  Turnkey stack: MQTT broker, DB, dashboards, automation.

- **Node-RED + Influx + Grafana (Free)** — https://github.com/node-red/node-red-docker  
  Classic OSS IoT pipeline deployable with a single docker-compose.

- **Mosquitto + Telegraf + TimescaleDB + Grafana** — free docker compose projects on GitHub.

---

#### ✅ Data Science + ML Tooling (Self-Host Free)

- **Jupyter Notebook/Lab (Free)** — https://jupyter.org  
  Local analytics, ML, visualization; can attach to MQTT and query DBs.

- **Apache Spark (Free/Open-Source)** — https://spark.apache.org  
  Big data analytics for large IoT datasets; works with Hadoop, S3, Kafka.

- **MLFlow (Free/Open-Source)** — https://mlflow.org  
  Model training, versioning and experiment tracking for IoT data science.

---

#### ✅ Embedded-Friendly Storage Options

- **SQLite (Free/Open-Source)** — https://sqlite.org  
  Lightweight DB ideal for gateways, SBCs, offline IoT data logging.

- **LiteFS (Free)** — https://fly.io/docs/litefs  
  SQLite replication for distributed edge nodes.

- **RRDTool for SBC / MCU gateways** — https://oss.oetiker.ch/rrdtool  
  Extremely small logger for memory-constrained devices.

### 27A. OPC-UA, Modbus, BACnet, PROFINET Free Stacks

#### ✅ OPC-UA (Free / Open-Source)

- **open62541 (Free & Open-Source C Stack)** — https://open62541.org  
  IEC62541-compliant OPC-UA SDK for embedded Linux and industrial gateways. Supports Client/Server, Pub/Sub, security, and address space modeling.

- **FreeOpcUa / python-opcua (Open-Source)** — https://github.com/FreeOpcUa/python-opcua  
  Python-based OPC-UA client/server implementation with certificates, subscriptions and historian support. Perfect for SCADA + cloud connectors.

- **Node-OPCUA (JavaScript OPC-UA)** — https://node-opcua.github.io  
  Full OPC-UA client/server in NodeJS. Ideal for industrial data pipelines, PubSub and edge-to-cloud bridging.

- **S2OPC (Secure & Safety OPC-UA)** — https://gitlab.com/systerel/s2opc  
  Security-focused OPC-UA C stack used in high-reliability and nuclear-grade systems. Free and safety-oriented.

- **OpenDS-OPC (Java OPC-UA SDK)** — https://github.com/opends/opends-opc  
  OPC-UA tools and Java SDK with discovery, security and address model support.

---

#### ✅ Modbus (RTU/TCP) — Free Stacks & Tools

- **libmodbus (Free/Open-Source)** — https://libmodbus.org  
  C library for Modbus TCP/RTU. Runs on embedded Linux, RTOS and SBC gateways.

- **pymodbus (Python Modbus)** — https://github.com/pymodbus-dev/pymodbus  
  Async Modbus TCP/RTU implementation with client/server support. Perfect for polling industrial sensors and PLCs.

- **MinimalModbus (Python)** — https://minimalmodbus.readthedocs.io  
  Simplified Modbus RTU/TCP client for Raspberry Pi and Linux edge nodes.

- **Jamod (Java Modbus)** — http://jamod.sourceforge.net  
  Java Modbus client/server stack for SCADA, industrial gateways and virtual PLCs.

- **FreeModbus (Embedded Master/Slave)** — https://github.com/armink/FreeModbus_Slave-Master-RTT-STM32  
  Lightweight Modbus RTU/TCP implementation for STM32 and RT-Thread RTOS.

---

#### ✅ BACnet (Building Automation / HVAC)

- **BACnet-Stack (Open-Source C)** — https://github.com/bacnet-stack/bacnet-stack  
  Full BACnet/IP stack in C for embedded controllers, HVAC and building automation.

- **OpenBACnet (Python)** — https://github.com/OpenBACnet/OpenBACnet  
  BACnet/IP toolkit for simulation, testing, and research.

- **BACnet-SC Tools (Secure BACnet)** — https://github.com/bacnet-stack/bacnet-sc  
  Implements BACnet Secure Connect (BACnet/SC) with secure TLS tunnels for modern building automation.

---

#### ✅ Wireless M-Bus / Smart Metering

- **OpenMBUS (Free/Open-Source)** — https://www.openmbus.org  
  Wireless M-Bus (EN13757/OMS) open-source stack for smart metering, sub-GHz radios and gateways.

---

#### ✅ Industrial MQTT (Sparkplug-B)

- **Eclipse Tahu / Sparkplug-B (Free/Open-Source)** — https://github.com/eclipse/tahu  
  Industry-standard MQTT payload specification for SCADA/HMI data models and edge-to-cloud interoperability.

---

#### ✅ PROFINET / PROFIBUS Tools

- **PROFINET Packet Sniffer (Free)** — https://github.com/klonyyy/profinet-sniffer  
  Open-source PROFINET packet analyzer for debugging and industrial protocol diagnostics.

### 27B. SCADA Dashboards (Free / Community Editions)

- **ScadaBR (Free/Open-Source)** — http://www.scadabr.com.br  
  Web-based SCADA built on Java. Supports Modbus, OPC, BACnet, MQTT and charts. Self-host friendly for industrial monitoring.

- **OpenEMS UI (Free/Open-Source)** — https://github.com/OpenEMS/openems  
  Modular energy management SCADA with dashboards, alarms, PLC logic, MQTT/Modbus. Runs on edge gateways + servers.

- **Rapid SCADA (Community Edition – Free)** — https://rapidscada.org  
  Complete SCADA suite with device polling, storage, trending and alarms. Modbus TCP/RTU, SNMP, MQTT supported.

- **OpenPLC HMI (Free / Web-Based HMI)** — https://www.openplcproject.com  
  Built-in HMI for OpenPLC runtime. Free visual dashboard with ladder logic integration and Modbus/OPC-UA.

- **Ignition Perspective (Maker Edition Free)** — https://inductiveautomation.com/ignition  
  Maker Edition free for personal/home/education SCADA. Dashboards, tags, MQTT Sparkplug-B, scripting.

- **Mycodo (Free/Open)** — https://github.com/kizniche/Mycodo  
  Python-based automation + dashboard + control loops. Works for PLC-lite industrial automation on Raspberry Pi.

- **Grafana OSS (SCADA Use-Case)** — https://grafana.com/oss  
  Not a SCADA engine, but widely used as free HMI/dashboard for Modbus/MQTT/Influx/Sparkplug-B pipelines.

- **Nodered Dashboard (Free/Open-Source)** — https://github.com/node-red/node-red-dashboard  
  Visual web dashboard on top of Node-RED flows. Commonly used for small SCADA/HMI and asset dashboards.

- **PyScada (Free/Open-Source)** — https://github.com/pyscada/pyscada  
  Web SCADA and logging platform using Python + Django. Supports Modbus, BACnet, OPC-UA, MQTT and PostgreSQL.

- **ThingsBoard Community Edition** — https://thingsboard.io  
  Full open-source IoT/SCADA suite with dashboards, alarms, rules engine and MQTT/CoAP/HTTP device connectivity.

- **OpenHAB (Free/Open-Source)** — https://www.openhab.org  
  Automation + dashboards for industrial labs and buildings. Supports Modbus, KNX, MQTT, BACnet via addons.

- **Eclipse Kapua (Open-Source)** — https://www.eclipse.org/kapua  
  Industrial IoT management + dashboards, telemetry store, device management.

- **OpenIndustrial.io Projects (Free)** — https://openindustrial.io  
  Collection of open SCADA/HMI tools, Modbus/OPC-UA gateways, edge visualization components.

- **Conpot SCADA Honeypot (Free/Open)** — https://github.com/mushorg/conpot  
  Not for production dashboards, but useful for training, research, security testing of SCADA environments.

- **PVServer / OpenEMS UI** — part of OpenEMS ecosystem  
  Web SCADA dashboard for DER, microgrid and industrial energy systems.

### 27C. PLC Simulators, Ladder Logic & Virtual PLCs (Free / Open-Source)

- **OpenPLC (Free/Open-Source Virtual PLC)** — https://www.openplcproject.com  
  Fully open-source IEC 61131-3 runtime supporting Ladder, ST, FBD, and Modbus. Works on Linux, Windows, Raspberry Pi and ESP32.

- **PLC Ladder Simulator (Android – Free)** — https://play.google.com/store/apps/details?id=com.mango_apps.plc_ladder_sim  
  Mobile-based ladder logic simulator for education and quick testing. Good for teaching PLC basics.

- **LDmicro (Free/Open-Source)** — http://cq.cx/ladder.pl  
  Generates firmware from ladder logic for microcontrollers (AVR, PIC, ARM). Turns MCUs into mini-PLCs.

- **Do-more Designer Simulator (Free)** — https://www.automationdirect.com  
  Full ladder logic IDE + PLC simulator for AutomationDirect Do-more PLCs. Completely free software mode.

- **Codesys (Free Runtime Simulation Mode)** — https://www.codesys.com  
  Free SoftPLC simulation mode allows ladder/FBD/ST testing without hardware. Supports Modbus, OPC-UA, MQTT via add-ons.

- **Factory I/O (Free Trial / Education mode)** — https://factoryio.com  
  3D virtual factory with PLC connections (Modbus, OPC-UA). Limited free use for training and education.

- **LogixPro SLC-500 Simulator (Free Trial / Academic)** — https://www.thelearningpit.com/logixpro  
  Rockwell-compatible ladder training and system simulations. Widely used in industrial training labs.

- **QModMaster (Free)** — https://sourceforge.net/projects/qmodmaster  
  Modbus master simulator with register visualization. Good companion tool for PLC and HMI testing.

- **MBSim (Free/Open)** — https://github.com/mbsim-env/mbsim  
  Multibody simulation used for robotics and PLC-driven mechanical systems.

- **Beremiz (Free/Open-Source IEC 61131 IDE)** — https://beremiz.org  
  IEC 61131 programming with SoftPLC, Modbus & CANopen support. Free ladder logic editor and runtime.

- **MATIEC (Free/Open – IEC Compiler)** — https://github.com/beremiz/matiec  
  Open-source IEC 61131-3 compiler used with Beremiz and custom SoftPLC solutions.

- **Classic Ladder (Free/Open-Source)** — https://github.com/ClassicLadder/ClassicLadder  
  Lightweight ladder logic editor and runtime for Linux and embedded platforms.

- **Open-Virtual-PLC (Experimental/Open-Source)** — https://github.com/Open-Virtual-PLC  
  Research-grade virtual PLC used for testing IEC logic and cyber-security scenarios.

- **FUXA (Open-Source HMI/SCADA + PLC Simulator)** — https://github.com/frangoteam/FUXA  
  Free HMI designer with tags, alarms, trends and Modbus simulator for small SCADA/PLC systems.

- **ModRSsim2 (Free)** — https://sourceforge.net/projects/modrssim2  
  Modbus RTU/TCP slave simulator for testing PLC masters, HMIs and SCADA polling.

### 27D. IIoT Edge Gateways & Industrial Protocol Tools (Free / Open-Source)

#### ✅ Edge Gateway Frameworks (Linux / SBC / Industrial PCs)

- **EdgeX Foundry (Free/Open-Source)** — https://www.edgexfoundry.org  
  Full edge platform: device services, MQTT, Modbus, BACnet, REST, rules engine, storage and dashboards. Runs on Pi, x86, industrial gateways.

- **ThingsBoard Gateway (Free/Open-Source)** — https://thingsboard.io  
  Industrial gateway supporting MQTT, OPC-UA, Modbus, BLE and LCD displays. Connects edge devices to ThingsBoard or any MQTT broker.

- **KubeEdge (Free/Open-Source)** — https://kubeedge.io  
  Kubernetes for the edge. Run containers, analytics, and ML on gateways or factories with offline tolerance.

- **OpenEMS Edge (Free/Open-Source)** — https://github.com/OpenEMS/openems  
  Industrial energy + microgrid management gateway with Modbus, MQTT, storage, scheduling and HMI.

- **FIWARE Edge Components (Free)** — https://www.fiware.org  
  Open-source building blocks for IIoT – context broker, device adapters, MQTT ingestion, dashboards, AI analytics.

- **balenaOS + balenaEngine (Free/Open)** — https://www.balena.io  
  Docker-based embedded Linux OS for edge gateways and industrial Raspberry Pi fleets with free-tier device management.

- **OpenWRT (Free/Open-Source)** — https://openwrt.org  
  Embedded Linux for routers & gateways. Add MQTT, Modbus, BACnet, WireGuard, VPN, Prometheus exporters.

- **Home Assistant OS (Free/Open)** — https://www.home-assistant.io  
  Popular automation OS but also used in industrial labs: Modbus, BACnet, KNX, Zigbee, MQTT, dashboards.

---

#### ✅ IIoT Protocol Adapters & Translators

- **Node-RED (Free/Open-Source)** — https://nodered.org  
  Low-code automation, MQTT, Modbus, BACnet, OPC-UA, CAN, BLE. Most popular IIoT gateway tool.

- **nodered-contrib-opcua (Free)** — https://github.com/mikakaraila/node-red-contrib-opcua  
  Full OPC-UA support on Node-RED: clients, servers, subscriptions, browse, history.

- **MQTT Sparkplug-B Tools (Free/Open)** — https://github.com/eclipse/tahu  
  Reference implementation for industrial MQTT interoperability (ISA-95, SCADA, EFM).

- **Modbus-Gateway Templates (Free)** — thousands of docker-compose repos to map Modbus → MQTT, OPC-UA → MQTT, etc.

- **BACpypes (Free/Open-Source BACnet)** — https://github.com/JoelBender/bacpypes  
  BACnet/IP application layer toolkit in Python. Used for building custom BACnet gateways.

- **OpenCAN / SocketCAN (Free)** — https://github.com/linux-can/can-utils  
  Linux CAN bus gateway utilities for industrial CAN controllers, motor drives and robotics.

- **Knx.js (Free)** — https://github.com/knx-js/knx.js  
  KNX/IP interface in NodeJS for industrial building automation.

- **OpenZWave (Free/Open)** — https://github.com/OpenZWave/open-zwave  
  Z-Wave stack for industrial labs, smart building automation and gateways.

- **Zigbee2MQTT (Free/Open-Source)** — https://github.com/Koenkk/zigbee2mqtt  
  Bridge thousands of Zigbee devices into MQTT/SCADA systems. Runs on Raspberry Pi and industrial gateways.

- **LoRaWAN Packet Forwarder (Free/Open)** — Semtech UDP forwarder + Chirpstack gateway OS for industrial LoRa gateways.

---

#### ✅ Industrial Protocol Drivers (Free Stacks)

- **libiec61850 (Free/Open)** — https://libiec61850.com/libiec61850  
  Free IEC 61850 stack for substation automation, IEDs, SCADA, GOOSE and MMS.

- **OpenDNP3 (Free/Open-Source)** — https://www.dnp3.org  
  DNP3 stack for power systems, utilities and substations. Secure authentication supported.

- **OpenFMB (Open Microgrid Interop)** — https://github.com/openenergymonitor/openfmb  
  Publish/subscribe framework for energy assets, DER, switches and SCADA.

- **Open62541 + MQTT/Sparkplug Bridge Projects** — community repositories linking OPC-UA → SCADA brokers.

---

#### ✅ Edge Database & Data Historian Tools (Free)

- **InfluxDB OSS + Telegraf** — free time-series logging on edge gateways.  
- **TimescaleDB Community Edition** — SQL historian for IIoT assets.  
- **QuestDB OSS** — real-time time-series DB used in high-speed telemetry.

---

#### ✅ Edge ML / Predictive Maintenance Tools (Free/Open)

- **TensorFlow Lite (Free/Open)** — edge on Linux gateways + MCUs.  
- **OpenVINO Toolkit (Free/Open)** — Intel edge inference for cameras + industrial inspection.  
- **Edge Impulse Self-Host** — free Docker deployment for small teams.  
- **MLFlow (Free/Open)** — model versioning + inference pipelines on factories.

---

#### ✅ Industrial Gateway OS & Firmware Platforms

- **ChirpStack Gateway OS (Free/Open)** — https://www.chirpstack.io  
  LoRaWAN gateway OS with MQTT, TLS and packet forwarders.

- **ResinOS / balenaOS (Free Tier)** — reliable fleet update system for edge Linux.

- **Ubuntu Core (Free)** — https://ubuntu.com/core  
  Secure snap-based OS for industrial gateways and IIoT appliances.

- **Yocto Project (Free/Open)** — https://www.yoctoproject.org  
  Build custom Linux for industrial gateways with OPC-UA, Modbus, WireGuard, MQTT, TSDB and drivers.

- **Industrial Doppelganger Images (Free)** — many vendors provide Yocto-built images with Modbus/MQTT drivers (Codesys, OpenPLC integration).

---

#### ✅ Industrial Network Sniffers & Diagnostics (Free/Open)

- **Wireshark (Free/Open)** — https://wireshark.org  
  Decodes PROFINET, EtherCAT, Modbus, IEC104, DNP3, MQTT, BACnet and CAN.

- **Scapy (Python – Free/Open)** — https://scapy.net  
  Custom packet analysis for industrial protocols and fuzzing.

- **profinet-sniffer (Free/Open)** — https://github.com/klonyyy/profinet-sniffer  
  Dedicated PROFINET diagnostic capture tool.

- **OpenPOWERLINK Wireshark Plugins** — free to inspect POWERLINK traffic.

---

#### ✅ Industrial Edge Automation / Rules Engines (Free)

- **Node-RED (Open-Source)** — flows, alarms, dashboards, MQTT/Modbus/OPC-UA.  
- **Eclipse Kura (Free/Open)** — full industrial gateway stack with VPN, OPC-UA, watchdogs, mDNS, MQTT, digital IO.  
- **ThingsBoard Rule Engine (Community)** — alarms, triggers, scripting at edge.

---

#### ✅ Small Enterprise / Startup-Friendly Free Tiers

- **Balena Cloud Free Tier** — deploy up to a few devices for free.  
- **AWS IoT Greengrass (Free Tier)** — edge compute + ML inference.  
- **Azure IoT Edge (Free Tier)** — containerized edge modules, OPC-UA, Modbus, MQTT connectors.  
- **HiveMQ Edge (Free)** — OPC-UA → MQTT gateway.

---
### 27E. MQTT Sparkplug-B, Industrial Data Historians & Asset Modeling (Free / Open-Source)

#### ✅ MQTT Sparkplug-B Stacks & Gateways (Free/Open)

- **Eclipse Tahu (Sparkplug-B Reference Implementation)** — https://github.com/eclipse/tahu  
  Official Sparkplug-B payload + state model. Used by SCADA, historians, PLC gateways and IIoT platforms.

- **HiveMQ Edge (Free Edition)** — https://www.hivemq.com/editions/edge  
  Free edge broker + OPC-UA → MQTT → Sparkplug-B bridging. Ideal for brownfield PLC modernisation.

- **Ignition Maker Edition (Free – Personal/Training)** — https://inductiveautomation.com/ignition  
  Fully functional Ignition with Sparkplug-B support for education/labs. Dashboards, tags, historians.

- **ThingsBoard Gateway + Sparkplug (Free/Open)** — https://thingsboard.io  
  Community plugins allow Sparkplug-B ingestion, device registry and alarms.

- **Node-RED Sparkplug Nodes (Free)** — https://flows.nodered.org/node/node-red-contrib-sparkplug  
  MQTT Sparkplug-B encoder/decoder nodes for building custom industrial bridges and asset models.

- **MQTT-Engine for Ignition (Free Community)** — Adds intelligent Sparkplug-B tag handling on gateways and servers.

---

#### ✅ Industrial Historians / Time-Series Storage (Free/Open)

- **InfluxDB OSS (Time-Series Historian)** — https://www.influxdata.com  
  Classic free historian for IIoT: MQTT/Modbus → Telegraf → Influx → Grafana.

- **TimescaleDB Community Edition** — https://www.timescale.com  
  SQL historian with retention policies, compression and Grafana support.

- **QuestDB OSS** — https://questdb.io  
  Ultra-fast ingestion for vibration, power-quality, energy meters and PLC telemetry.

- **Apache Druid (Open-Source)** — https://druid.apache.org  
  Industrial-scale analytics on billions of telemetry datapoints. Used in utility/energy monitoring.

- **RRDTool (Embedded Historian)** — https://oss.oetiker.ch/rrdtool  
  Round-robin DB ideal for edge gateways, ARM boards and low-storage devices.

- **OpenTSDB (Free/Open)** — https://github.com/OpenTSDB  
  Time-series on top of HBase for large utility/substation logging projects.

---

#### ✅ Industrial Asset Models / Semantics (Free/Open)

- **Asset Administration Shell (AASX / Eclipse BaSyx)** — https://www.eclipse.org/basyx  
  Open-source Industry 4.0 digital asset modeling, OPC-UA, REST, dashboards and simulators.

- **OPC-UA Information Modeling Tools (Free)** — multiple open-source code generators for UA nodesets, assets and complex object types.

- **Eclipse Volttron (Free/Open)** — https://volttron.org  
  Industrial distributed control platform with semantic metadata for building/energy assets.

- **Eclipse Kapua Device Registry (Free/Open)** — https://www.eclipse.org/kapua  
  Open-source fleet and asset manager with telemetry history and dashboards.

- **OpenHAB Semantic Model** — https://www.openhab.org  
  Semantic tagging of industrial/building entities, alarms and automation flows.

---

#### ✅ Industrial ETL / Telemetry Pipelines (Free)

- **OpenTelemetry Collector (Free/Open)** — https://opentelemetry.io  
  Collect sensor data via MQTT/REST, transform and push to timeseries DBs. Free and self-hostable.

- **Logstash OSS (Free)** — https://github.com/elastic/logstash  
  ETL for Modbus/MQTT/REST → Elasticsearch/Influx. Works as plant data bridge.

- **Fluent Bit (Free/Open)** — https://fluentbit.io  
  Lightweight collector for edge devices with 1–2 MB memory footprint.

- **Telegraf (Free/Open)** — https://github.com/influxdata/telegraf  
  250+ plugins including Modbus, MQTT, OPC-UA, SNMP, BACnet. Gold standard for edge ingestion.

- **NiFi (Free/Open)** — https://nifi.apache.org  
  Industrial ETL and streaming pipelines for high-volume telemetry and historian feeds.

---

#### ✅ Industrial Analytics / Predictive Tools (Free/Open)

- **Grafana OSS** — https://grafana.com/oss  
  Free dashboards, alarms and drilling for historians.

- **Chronograf (Free)** — https://docs.influxdata.com/chronograf  
  Native UI for InfluxDB with alerts and dashboards.

- **Superset (Apache Free)** — https://superset.apache.org  
  SQL BI dashboards for Timescale/QuestDB/Druid.

- **Metabase (Free/Open)** — https://metabase.com  
  Self-host analytics for PLC, sensor and SCADA data.

- **Redash (Free/Open)** — https://redash.io  
  Visual builder + charts for historians and SQL backends.

- **Open-Source Predictive Maintenance Repos** — Python notebooks + models for vibration, anomaly detection, power quality forecasting (GitHub community).

---

#### ✅ Complete IIoT Historian Bundles (Self-Host)

- **TIG Stack (Telegraf + InfluxDB + Grafana)** — free docker templates for SCADA historians.  
- **Druid + Superset** — open-source analytics for grid, energy and utility telemetry.  
- **QuestDB + Grafana** — high-speed historian with dashboards.  
- **OpenTelemetry + Prometheus + Grafana** — free metric logging + visualization.

---

### 28A. Digital Twin Frameworks (Open-Source / Free Cloud Tiers)

#### ✅ Full Digital Twin Platforms (Free / Open-Source)

- **Eclipse Ditto (Free/Open-Source)** — https://www.eclipse.org/ditto  
  Digital twin platform for IoT devices, sync state, commands, MQTT/HTTP/WS APIs. Used with Kubernetes and edge gateways.

- **FIWARE Digital Twin Components (Free/Open)** — https://www.fiware.org  
  Context broker + twins + NGSI-LD semantic models. Open-source framework powering EU smart city and industrial projects.

- **Eclipse BaSyx AAS (Free/Open-Source)** — https://www.eclipse.org/basyx  
  Industry 4.0 Asset Administration Shell (AAS) twins with OPC-UA, REST, dashboards and simulators.

- **OpenDSS (Electric Grid Digital Twin)** — https://github.com/dss-extensions/OpenDSS  
  Open-source electric power distribution system simulator. Used in smart-grid planning and digital twin research.

- **OpenModelica (Free/Open)** — https://openmodelica.org  
  Equation-based modeling for digital twins, physics simulation, cyber-physical systems and real-time co-simulation.

- **OpenEMS Digital Twin Layer** — https://github.com/OpenEMS/openems  
  Create digital twins of energy assets with forecasting, scheduling and SCADA/HMI integration.

- **Gazebo / Ignition Robotics (Free/Open-Source)** — https://gazebosim.org  
  High-fidelity physics simulation for robots, AGVs and mobile industrial systems – often used for digital twins of factories.

---

#### ✅ Industrial Cloud Digital Twins (Free Community / Free Tiers)

- **Azure Digital Twins (Free Tier)** — https://azure.microsoft.com  
  Graph-based digital twin modeling for factories, sensors, telemetry and BACnet/OPC-UA ingestion. Free transactions/month.

- **AWS IoT TwinMaker (Free Tier)** — https://aws.amazon.com/iot-twinmaker  
  Build 3D scenes, tags, alarms, historian links. Free tier for prototyping digital twins.

- **Siemens/Mindsphere Free Developer Tier** — limited digital twin & IoT data modeling for education and pilot use.

- **Bosch IoT Things (Free Developer Tier)** — https://bosch-iot-suite.com  
  Digital twins, device registry, semantics and MQTT connectivity on a free developer account.

---

#### ✅ Simulation + Digital Twin Integration (Free/Open)

- **Simulink Community Models (Free Examples)** — many open-source industrial models for co-simulation and digital twins.

- **OpenAI Gym + ROS (Free/Open)** — https://www.ros.org  
  Robotics/AGV twins with reinforcement learning, sensor fusion and multi-robot factories.

- **CARLA (Free/Open-Source)** — https://carla.org  
  Automotive digital twin simulator used in ADAS testing, LIDAR/camera simulation and autonomous vehicle R&D.

- **AirSim (Microsoft Open-Source)** — https://github.com/microsoft/AirSim  
  Realistic digital twin simulator for drones, AGVs and autonomous robots.

- **OpenROAD / OpenEDA Twins** — open-source chip design digital twins for EDA workflows and hardware verification.

---

#### ✅ AAS, Semantics, Industry 4.0 Digital Twin Tools

- **AASX Package Explorer (Free/Open)** — https://github.com/admin-shell-io/aasx-package-explorer  
  Create, edit and validate Industry 4.0 Asset Administration Shell digital twins.

- **Eclipse AAS Toolchain (Free/Open)** — Companion editors, simulators, OPC-UA gateways and dashboards for digital twins.

- **NGSI-LD Tools (Free/Open)** — semantic digital twin modeling for smart factories and cities (used in FIWARE ecosystem).

- **JPS Base Library (Knowledge Graph Twins)** — https://github.com/cambridge-cares/TheWorldAvatar  
  Knowledge-graph based digital twins for industrial plants and smart cities.

---

#### ✅ Real-Time Co-Simulation (Free/Open)

- **Open Simulation Platform (OSP)** — https://opensimulationplatform.com  
  Co-simulation for maritime, mechanical and cyber-physical digital twins.

- **FMU / FMI Standard Tools (Free/Open)** — https://fmi-standard.org  
  Functional Mock-up Interface to connect physics models, PLC logic and control systems.

- **mosaik (Free/Open-Source)** — https://mosaik.offis.de  
  Large-scale co-simulation for energy grids and smart-factory digital twins.

---

#### ✅ Physics-Based 3D Twin Engines (Free/Open)

- **Bullet Physics (Free/Open)** — https://github.com/bulletphysics/bullet3  
  Real-time physics engine used in Gazebo, robotics and industrial digital twins.

- **PyBullet (Free/Open)** — python bindings for Bullet used in control, robotics and digital twin research.

- **OpenCascade (Free/Open)** — https://www.opencascade.com  
  3D CAD kernel used to simulate geometry and kinematics in mechanical twins.

---
### 28B. Physics-Based Simulation Tools (Free / Open-Source)

#### ✅ Multi-Physics Simulation (Thermal, Mechanical, EM, Fluids)

- **OpenFOAM (Free/Open-Source CFD)** — https://openfoam.org  
  Industry-grade computational fluid dynamics for airflow, cooling, thermal simulations, aerodynamics and HVAC twins.

- **Elmer FEM (Free/Open-Source)** — https://www.csc.fi/web/elmer  
  Multiphysics FEM solver: heat, structural mechanics, electromagnetics, acoustics. Used in industrial digital twin modeling.

- **FreeFEM (Free/Open)** — https://freefem.org  
  FEM framework for mechanical, thermal and electromagnetic simulation with scripting-style workflow.

- **CalculiX (Free/Open-Source)** — http://www.calculix.de  
  Structural mechanics and thermal FEM, alternative to Abaqus for small-scale mechanical simulations.

- **SU2 (Free/Open)** — https://su2code.github.io  
  Aerospace-grade CFD + adjoint optimization. Used in academic/industrial design and digital twins of moving systems.

---

#### ✅ Electromagnetic / RF / Power Systems Simulation (Free / Open)

- **ngspice (Free/Open-Source SPICE)** — http://ngspice.sourceforge.net  
  Circuit-level simulation for analog, power electronics, SMPS and EMI analysis.

- **OpenEMS (Free/Open)** — https://www.openems.de  
  Electromagnetic field solver for antennas, waveguides, RF twins, PCB EMC and near-field coupling studies.

- **Qucs-S (Free/Open)** — https://ra3xdh.github.io  
  RF and microwave circuit simulator integrating SPICE, S-parameters and harmonic balance.

- **OpenDSS (Free/Open)** — https://github.com/dss-extensions/OpenDSS  
  Power systems simulator for distribution networks, PV, EV, storage and substation digital twins.

- **PowerFactory Education Edition (Free Academic)** — limited free edition for grid and power system studies.

---

#### ✅ Robotics & Cyber-Physical Simulation

- **Gazebo / Ignition Robotics (Free/Open)** — https://gazebosim.org  
  3D physics engine with sensors, actuators, SLAM and robot control. Used for digital twins of AGVs and factory robots.

- **Webots (Free/Open)** — https://cyberbotics.com  
  Real-time robot simulation: mobile platforms, robotic arms, machine vision, conveyor systems.

- **V-REP / CoppeliaSim (Free Educational)** — https://www.coppeliarobotics.com  
  Advanced robot simulator: ROS interfaces, path planning, kinematics, physics modeling.

- **Open Dynamics Engine (Free/Open)** — http://www.ode.org  
  Rigid-body physics engine used in robotics, industrial twins and control algorithm prototyping.

---

#### ✅ Mechanical & Kinematics Simulation

- **MBDyn (Free/Open-Source)** — http://www.mbdyn.org  
  Multibody dynamics simulator for mechanical systems, linkages, vehicles, manipulators.

- **OpenModelica (Free/Open)** — https://openmodelica.org  
  Supports hybrid modeling: mechanical + electrical + thermal co-simulation. Used for complex industrial twins.

- **Scilab Xcos (Free/Open)** — https://www.scilab.org  
  Block-diagram modeling and co-simulation for mechanical and control systems.

- **Dynawo (Free/Open)** — https://dynawo.github.io  
  Power system dynamic simulations for grid and industrial energy management twins.

---

#### ✅ Real-Time Simulation / HIL (Free & Community)

- **OpenRTI (HLA RTI – Free/Open)** — https://github.com/open-rti/openrti  
  Real-time infrastructure for distributed co-simulation (HLA standard). Used for cyber-physical twin research.

- **FMI/FMU Tools (Free/Open)** — https://fmi-standard.org  
  Functional mock-up interface for connecting PLC models, power converters, drives and simulators.

- **RT-LAB Community (Free Limited)** — real-time simulation for control and power electronics education.

---

#### ✅ Digital Manufacturing / Factory Flow Simulation

- **FlexSim Express (Free Edition)** — https://www.flexsim.com  
  Factory layout, conveyor flow, warehouse simulation — limited free but useful for prototyping twins.

- **JaamSim (Free/Open)** — https://jaamsim.com  
  Process and factory workflow simulator, discrete-event twin modeling.

- **SimPy (Free/Open)** — https://simpy.readthedocs.io  
  Python discrete-event simulation for modeling industrial processes, queues, conveyors and AGVs.

---

#### ✅ Thermal + Mechanical for Electronics

- **OpenRadioss (Free/Open)** — https://www.openradioss.org  
  Structural and crash simulation, used in mechanical shock/vibration digital twins.

- **Thermal Desktop Lite / Open Source Heat Transfer Tools** — community tools for heat flow modeling in electronics & enclosures.

---
### 28C. IT/OT Integration Tools (Open-Source / Free-Tier) for Digital Twins

#### ✅ OT → IT Bridges (OPC-UA, Modbus, BACnet, CAN → Cloud)

- **Node-RED (Free/Open-Source)** — https://nodered.org  
  Industry-favorite low-code integration for Modbus, BACnet, OPC-UA, MQTT, Sparkplug-B, REST, SQL and dashboards.

- **Eclipse Kura (Free/Open-Source)** — https://www.eclipse.org/kura  
  Industrial gateway platform with Modbus, OPC-UA, watchdogs, VPN, cellular failover, MQTT and digital IO drivers.

- **ThingsBoard Community Gateway (Free/Open)** — https://thingsboard.io  
  Collects Modbus, BLE, OPC-UA, MQTT and pushes to cloud/backends. Fully open-source with rule-engine.

- **FIWARE IoT Agents (Free/Open)** — https://github.com/FIWARE  
  Bridges industrial devices into NGSI-LD digital twins. Supports MQTT, OPC-UA, CoAP, HTTP and Modbus agents.

- **OpenHAB (Free/Open)** — https://www.openhab.org  
  Industrial building automation gateway with KNX, Modbus, BACnet, Zigbee, Z-Wave, MQTT and semantic models.

- **BACpypes (Free/Open)** — https://github.com/JoelBender/bacpypes  
  Python BACnet/IP toolkit for building automation and IT/OT bridging.

- **Zigbee2MQTT (Free/Open)** — https://github.com/Koenkk/zigbee2mqtt  
  Bridge thousands of Zigbee endpoints into MQTT/SCADA or digital twin platforms.

- **Can-utils / SocketCAN (Free/Open)** — https://github.com/linux-can/can-utils  
  Linux CAN bus interface for logging, control, gateways and simulation.

---

#### ✅ Data Pipelines for Telemetry → Digital Twins

- **OpenTelemetry Collector (Free/Open)** — https://opentelemetry.io  
  Moves telemetry from edge devices to cloud historians, Prometheus, Grafana, Timescale, etc.

- **Telegraf (Free/Open)** — https://github.com/influxdata/telegraf  
  Plugin-based ingestion for Modbus, MQTT, OPC-UA, BACnet, SNMP. The de-facto industrial pipeline tool.

- **Logstash OSS (Free)** — https://github.com/elastic/logstash  
  Ingest industrial telemetry and forward to Elasticsearch, Influx, Kafka or cloud.

- **Fluent Bit (Free/Open)** — https://fluentbit.io  
  Very lightweight OT-to-IT pipeline (1–2 MB RAM). Ideal for edge-gateways.

- **Apache NiFi (Free/Open)** — https://nifi.apache.org  
  Drag-drop data flow builder for OT → cloud, SCADA → historians, large data ingestion.

- **MQTT Sparkplug-B (Eclipse Tahu)** — https://github.com/eclipse/tahu  
  Standard payload for industrial telemetry, gateway health, alarms and digital twin state sync.

---

#### ✅ Industrial Connectors & Middleware

- **HiveMQ Edge (Free Edition)** — https://www.hivemq.com/editions/edge  
  OPC-UA → MQTT bridge, Sparkplug-B support, secure edge-to-cloud messaging.

- **ChirpStack Gateway OS (Free/Open)** — https://www.chirpstack.io  
  LoRa/LoRaWAN packet forwarder with MQTT pipeline to digital twins and cloud apps.

- **Eclipse Vorto (Free/Open)** — https://github.com/eclipse/vorto  
  Semantic information modeling for IoT devices, creates OT → IT model adapters.

- **Eclipse Hono (Free/Open)** — https://www.eclipse.org/hono  
  Device messaging platform for MQTT, HTTP, AMQP. Bridges OT messages to cloud microservices.

- **Greybus (Free/Open)** — https://github.com/projectara/greybus  
  Protocol to bridge Linux and embedded systems for modular hardware, sensors and hot-swap devices.

- **Eclipse Mita / Edgex Device Services** — OT connectors for various sensors and PLCs.

---

#### ✅ Industrial Identity, Registry, Digital Thread

- **Eclipse Ditto (Free/Open)** — https://www.eclipse.org/ditto  
  Sync device shadows, commands and asset state; ideal twin integration from field data.

- **Eclipse Kapua (Free/Open)** — https://www.eclipse.org/kapua  
  Device registry + telemetry integration + dashboards for industrial fleets.

- **FIWARE Orion-LD Context Broker (Free/Open)** — https://fiware-orion.readthedocs.io  
  Standardized semantic context layer for IT/OT data, enabling large-scale digital twins.

- **Asset Administration Shell Tooling (Free)** — Industry 4.0 AAS metadata exchange, OPC-UA gateways, REST endpoints.

---

#### ✅ Cloud-Free / Air-Gapped IT/OT Integration

- **Node-RED on Industrial SBCs / IPCs** — full offline workflows for Modbus → SQLite → Grafana dashboards.

- **InfluxDB OSS + Grafana** — offline historian + dashboards in power plants, factories, labs.

- **Mosquitto MQTT (Free/Open)** — secure broker for OT networks; integrate SCADA/HMI → edge DBs.

- **OpenPBS / SLURM** — job scheduling and compute orchestration in private industrial clusters (HPC digital twins).

---

#### ✅ Protocol Simulators for IT/OT Testing

- **ModRSsim2 (Free)** — Modbus slave simulator for SCADA/PLC testing.  
- **QModMaster (Free/Open)** — Modbus master simulator + register visualization.  
- **open62541 Server/Client Simulators** — OPC-UA test servers for OT pipelines.  
- **bacnet-stack tools** — BACnet/IP simulators and routers.

---

### 28D. Cyber-Physical Modeling Tools (Free / Open-Source)

#### ✅ Cyber-Physical Systems (CPS) Modeling & Co-Simulation

- **OpenModelica (Free/Open-Source)** — https://openmodelica.org  
  Unified modeling of mechanics, electronics, thermal and control systems. Core CPS tool for co-simulation and real-time twins.

- **FMI / FMU Standard Tools (Free/Open)** — https://fmi-standard.org  
  Functional Mock-up Units to exchange models between PLC simulators, SPICE, MATLAB, Modelica, etc. Core building block of CPS workflows.

- **mosaik (Free/Open-Source)** — https://mosaik.offis.de  
  Co-simulation framework for complex distributed systems — smart grids, industrial plants, microgrids, renewable twins.

- **Open Simulation Platform (OSP) (Free/Open)** — https://opensimulationplatform.com  
  Maritime + industrial CPS co-simulation framework. Supports FMU/FMI and real-time controllers.

- **ROS (Robot Operating System – Free/Open)** — https://www.ros.org  
  Standard middleware for cyber-physical robotics and AGVs. Works with Gazebo, AirSim, MoveIt for real-world CPS validation.

- **Gazebo / Ignition Robotics (Free/Open)** — https://gazebosim.org  
  Real-time physics simulator with sensors, actuators, digital I/O and control loops. Used heavily for factory automation CPS.

- **CoppeliaSim / V-REP (Free Educational)** — https://www.coppeliarobotics.com  
  CPS simulator with robotic arms, conveyors, AGVs, machine vision and PLC/ROS interfaces.

- **Webots (Free/Open)** — https://cyberbotics.com  
  Real-time robot + CPS simulations for automated handling, AMRs and cyber-physical factories.

---

#### ✅ Control Systems Simulation (Free/Open)

- **Scilab + Xcos (Free/Open-Source)** — https://www.scilab.org  
  Block-diagram control modeling similar to Simulink. Used to model CPS involving motors, drives, converters and PLC logic.

- **Octave-Control (Free/Open)** — https://octave.org  
  MATLAB-compatible CPS + control loops, PID tuning, signal processing for cyber-physical plants.

- **PyControl / Python-Control (Free/Open)** — https://python-control.readthedocs.io  
  Control theory library for CPS, modeling, linear systems, Bode/Root-locus design.

- **FREEMAT (Free)** — MATLAB-like environment used in teaching control + CPS math.

---

#### ✅ Discrete-Event & System-Level CPS Simulation

- **SimPy (Free/Open)** — https://simpy.readthedocs.io  
  Discrete-event CPS simulator for manufacturing flows, conveyor automation, machine coordination, transport & AGV fleets.

- **JaamSim (Free/Open)** — https://jaamsim.com  
  Factory + logistics CPS simulator, visual modeling of bottlenecks, stations, sensor triggers, queueing and control decisions.

- **OMNeT++ (Free/Open-Source)** — https://omnetpp.org  
  Network + CPS simulator used for wireless sensor networks, industrial IoT, TSN scheduling and cyber-security experiments.

- **NS-3 (Free/Open)** — https://www.nsnam.org  
  Accurate network simulation for CPS where latency, jitter, TSN, Wi-Fi, LTE/5G and industrial protocols matter.

- **SUMO (Free/Open)** — https://www.eclipse.org/sumo  
  Traffic and mobility simulator for autonomous cyber-physical systems, AV fleets and logistics twins.

---

#### ✅ Energy Systems & Power Electronics CPS

- **OpenDSS (Free/Open)** — https://github.com/dss-extensions/OpenDSS  
  Cyber-physical twin of distribution networks, DER, EVs, storage, microgrids and substations.

- **GridLAB-D (Free/Open-Source)** — https://www.gridlabd.org  
  CPS simulator for smart-grid decision systems, forecasting, demand response and renewable integration.

- **PSCAD Free Educational** — limited free licenses used for power-electronics CPS and protection relays.

- **PLECS Free Student Edition** — simplified CPS simulation for converters, inverters, SMPS, drives and controllers.

---

#### ✅ CPS Security, Pen-Testing & Fault Simulation (Free/Open)

- **Conpot (Free/Open-Source SCADA Honeypot)** — https://github.com/mushorg/conpot  
  Emulates PLC/SCADA devices for cyber-attack simulation, digital twin of industrial control systems.

- **MiniCPS (Free/Open)** — https://github.com/scy-phy/minicps  
  CPS security simulator integrating network, sensors, actuators and control logic for cyber-attack modeling.

- **S3 (System Security Simulator) (Free)** — open tools for simulating CPS failures, cyber events and resiliency testing.

- **OpenPLC + Attack Repos (Free)** — virtual PLC with cyber-security scenarios and CPS threat research.

---

#### ✅ Hardware-in-the-Loop & Real-Time CPS (Community / Free)

- **OpenRTI (Free/Open)** — https://github.com/open-rti/openrti  
  Real-time distributed CPS simulation based on HLA standard.

- **OPAL-RT Community Models (Free Examples)** — free HIL sample models for power electronics / drives education.

- **FMI-based co-simulation with Python** — multiple open repositories connecting PLC logic <--> physics models <--> control loops.

---
### 28E. Predictive Maintenance & Analytics (Free / Open-Source)

#### ✅ Vibration, Fault Detection & Machine Health (Free/Open)

- **Edge Impulse (Self-Host Free Tier / Open Models)** — https://edgeimpulse.com  
  Build vibration and anomaly detection models for motors, pumps, compressors. Free tier + on-prem Docker for small teams.

- **TensorFlow Lite + Audio/Vibration Models (Free/Open)** — https://www.tensorflow.org/lite  
  ML models for bearing faults, FFT, anomaly detection on edge gateways and MCUs.

- **pyOD (Python Outlier Detection – Free/Open)** — https://github.com/yzhao062/pyod  
  40+ anomaly detection algorithms for predictive maintenance pipelines.

- **sktime (Free/Open)** — https://www.sktime.net  
  Time-series fault prediction, forecasting, feature extraction on machine sensor data.

- **river (Online ML – Free/Open)** — https://riverml.xyz  
  Real-time machine learning for streaming sensor data — ideal for continuous-condition monitoring.

- **tsfresh (Free/Open)** — https://github.com/blue-yonder/tsfresh  
  Automatic extraction of time-series features from vibration, current, temperature logs.

- **Darts (Free/Open)** — https://github.com/unit8co/darts  
  Forecasting toolkit for equipment wear, remaining useful life (RUL) and predictive analytics.

- **Merlin (Free/Open)** — https://github.com/NVIDIA/Merlin  
  GPU-accelerated feature engineering + anomaly detection for large industrial datasets.

- **OpenEIS (Open Energy Information System)** — https://github.com/openEIS/openEIS  
  Analytics for HVAC, industrial energy systems, fault detection and optimization.

---

#### ✅ Data Pipelines: Ingestion → Feature Extraction → Models

- **OpenTelemetry Collector (Free/Open)** — https://opentelemetry.io  
  Collect PLC/MQTT/REST sensor data and route to Prometheus, Influx, Kafka or ML services.

- **Telegraf (Free/Open)** — https://github.com/influxdata/telegraf  
  250+ plugins: Modbus, OPC-UA, MQTT → InfluxDB → Grafana for analytics and maintenance dashboards.

- **Kafka Community Edition (Free/Open)** — https://kafka.apache.org  
  Streaming pipelines for high-rate vibration, power-quality and telemetry logs.

- **Fluent Bit (Free/Open)** — https://fluentbit.io  
  Lightweight log collector for embedded gateways and industrial PCs.

---

#### ✅ Time-Series / Predictive Maintenance Databases (Free/Open)

- **InfluxDB OSS** — https://www.influxdata.com  
  Classic historian for vibration, thermal, current sensors with retention and queries.

- **TimescaleDB Community Edition** — https://www.timescale.com  
  SQL + time-series compression + continuous aggregates for predictive maintenance pipelines.

- **QuestDB OSS** — https://questdb.io  
  Very high-throughput ingestion for high-frequency accelerometer data.

- **Prometheus (Free/Open)** — https://prometheus.io  
  Metrics + alerts for process control, motors, compressors, valves.

---

#### ✅ Analytics & Visualization for Maintenance

- **Grafana OSS (Free)** — https://grafana.com/oss  
  Dashboards, alarms, FFT plots, trends, thresholds for equipment monitoring.

- **Superset (Apache Free)** — https://superset.apache.org  
  BI dashboards for SQL historians, quality analytics, uptime and RUL predictions.

- **Metabase (Free/Open)** — https://metabase.com  
  Simple queries, charts, drill-down for factory maintenance teams.

- **Redash (Free/Open)** — https://redash.io  
  SQL visualizations for failure logs and SCADA telemetry.

---

#### ✅ Asset Monitoring Frameworks (Free / Open-Source)

- **Eclipse Kapua (Free/Open)** — https://www.eclipse.org/kapua  
  Asset registry, telemetry ingestion, dashboards — supports offline plants and edge deployments.

- **Eclipse Ditto (Free/Open)** — https://www.eclipse.org/ditto  
  Digital twin state sync + rules for anomaly detection.

- **OpenEMS (Free/Open)** — https://github.com/OpenEMS/openems  
  Predictive analytics for energy storage, inverters, microgrids, utility assets.

---

#### ✅ Open Datasets & Research Repos (Free)

- **NASA Bearing Vibration Datasets** — widely used for predictive maintenance research.  
- **Case Western Reserve Bearing Dataset** — classic vibration failure dataset.  
- **SEU Machine Fault Database** — motor/gearbox failure signals.  
- **PHM Society Datasets** — turbofan, battery health, industrial failures.

---

#### ✅ Edge ML Deployment (Free/Open)

- **TensorFlow Lite** — deploy vibration & anomaly detection on SBCs.  
- **ONNX Runtime (Free/Open)** — fast inference on ARM/Linux gateways.  
- **OpenVINO Toolkit (Free/Open)** — Intel acceleration for cameras and defect inspection.  
- **TFMicro (Free/Open)** — MCU-level inference for predictive sensors.

---

### 29A. Documentation Generators & Technical Writing Tools (Free / Open-Source)

#### ✅ Code & API Documentation

- **Doxygen (Free/Open-Source)** — https://www.doxygen.nl  
  Industry-standard documentation generator for C/C++/Python/Java. UML diagrams, call graphs, HTML/PDF output.

- **Sphinx (Free/Open-Source)** — https://www.sphinx-doc.org  
  Documentation generator for Python and embedded Python tooling. Supports C/C++ API docs using Breathe + Doxygen.

- **MkDocs (Free/Open-Source)** — https://www.mkdocs.org  
  Markdown → static documentation with search, themes, navigation. Excellent for project docs and firmware manuals.

- **MkDocs Material Theme (Free/Open)** — https://squidfunk.github.io/mkdocs-material  
  Most popular theme for engineering docs: tabs, TOC, mermaid diagrams, versioning, dark mode.

- **Doxybook2 (Free/Open)** — https://github.com/matusnovak/doxybook2  
  Converts Doxygen XML output into MkDocs or GitBook-style Markdown docs. Perfect for embedded API + docs websites.

- **Breathe (Free/Open)** — https://breathe.readthedocs.io  
  Bridge between Doxygen and Sphinx for documenting C/C++ APIs with Python developers.

- **JSDoc (Free/Open)** — https://jsdoc.app  
  JavaScript documentation generator for embedded tools, dashboards and cloud backends.

- **Rustdoc (Free/Open)** — built into Rust toolchain  
  Auto-generate docs from embedded Rust crates with examples, code snippets and search.

---

#### ✅ Markdown → Documentation Sites (Free)

- **GitBook Open-Source Templates** — community static site generators for Markdown docs (fully free self-host).  
- **Docsify (Free/Open)** — https://docsify.js.org  
  Turns Markdown files into an instant documentation website with no build step.

- **Starlight (Free/Open)** — https://starlight.astro.build  
  Easy docs site generator with MDX, search, navigation and components.

- **Hugo (Free/Open)** — https://gohugo.io  
  Large static site generator with themes for technical documentation.

---

#### ✅ Architecture & Diagram Tools (Free/Open)

- **Mermaid (Free/Open)** — https://mermaid.js.org  
  Generate diagrams from text: sequence, flowcharts, class diagrams, state machines, Gantt, ERD — embedded docs friendly.

- **PlantUML (Free/Open)** — https://plantuml.com  
  UML, state, activity, sequence diagrams via plaintext. Integrates with Doxygen, MkDocs, Sphinx.

- **Graphviz (Free/Open)** — https://graphviz.org  
  Render block diagrams, call-graphs, state machines. Used in Doxygen output.

- **Draw.io / Diagrams.net (Free)** — https://app.diagrams.net  
  Browser-based diagramming stored as SVG/PNG/JSON in Git repos. Widely used for hardware architecture.

- **Krocus / Mermaid for MkDocs** — plugins for embedding diagrams in static sites.

---

#### ✅ Writing + Versioning Combo (Free/Open)

- **Obsidian (Free)** — https://obsidian.md  
  Markdown knowledge base for firmware and hardware docs, stored locally with Git sync.

- **Zettlr (Free/Open)** — https://www.zettlr.com  
  Markdown editor with citation management, PDF export, engineering note-keeping.

- **Typora (Free Trial)** — visual Markdown editor for clean documentation.

- **VSCode Markdown Preview / Mermaid** — write docs alongside code with live preview.

---

#### ✅ Books, PDFs & Manuals (Static Output)

- **Pandoc (Free/Open)** — https://pandoc.org  
  Convert Markdown → PDF/Word/HTML/LaTeX for user manuals, datasheets and API guides.

- **LaTeX (Free/Open)** — https://www.latex-project.org  
  High-quality technical reports, engineering papers and hardware documentation.

- **TeXstudio (Free/Open)** — https://www.texstudio.org  
  Popular LaTeX editor for structured reports.

---

#### ✅ Documentation Site Hosting (Free Tiers)

- **GitHub Pages (Free)** — static hosting of MkDocs, Sphinx, Doxygen and Markdown sites.

- **Netlify Free Tier** — deploy MkDocs/Hugo/Gatsby docs from GitHub.

- **Vercel Free Tier** — deploy documentation websites with SSL + CDN.

---

#### ✅ Bonus – Internal Hardware/Firmware Wiki (Free/Open)

- **Wiki.js (Free/Open)** — https://wiki.js.org  
  Markdown-based wiki for engineering teams with Git integration and diagrams.

- **BookStack (Free/Open)** — https://www.bookstackapp.com  
  Clean documentation platform used as internal wiki for hardware and firmware teams.

- **MediaWiki (Free/Open)** — https://www.mediawiki.org  
  Same engine as Wikipedia; useful for deep technical knowledge bases in R&D teams.

---
### 29B. Version Control, CI/CD for Embedded (Free / Open-Source)

#### ✅ Source Code Repositories (Free)

- **GitHub Free Tier** — https://github.com  
  Unlimited public repos, private repos, GitHub Actions (CI), project boards, issues. Widely used for firmware/hardware projects.

- **GitLab Community Edition (Free/Open-Source)** — https://gitlab.com  
  Self-hostable DevOps platform with Git repos, runners, CI/CD pipelines, artifacts, issue tracking and wiki.

- **Gitea (Free/Open-Source)** — https://gitea.io  
  Lightweight self-hosted Git server. Perfect for small hardware teams, local labs, air-gapped networks.

- **Codeberg (Free/Open-Source hosting)** — https://codeberg.org  
  Privacy-friendly Git hosting for open hardware and firmware projects.

- **SourceHut (Free/Open Tier)** — https://sourcehut.org  
  Minimal Git hosting with CI and email-based patch workflows.

---

#### ✅ CI/CD for Embedded (Free/Open)

- **GitHub Actions (Free Tier)** — Linux/Windows/macOS runners for building firmware, running unit tests, static analysis, building containers.

- **GitLab CI/CD (Free CE + Free Hosted Tier)** — pipelines for compiling firmware, unit tests, coverage reports, building documentation.

- **CircleCI (Free Tier)** — supports ARM cross-compilers, Docker, build matrices for embedded toolchains.

- **Drone CI (Free/Open-Source)** — https://www.drone.io  
  Container-native CI for self-hosted labs, automotive and aerospace teams.

- **Woodpecker CI (Free/Open)** — https://woodpecker-ci.org  
  Drone-compatible, lightweight CI for small embedded teams.

- **Jenkins (Free/Open-Source)** — https://www.jenkins.io  
  Classic CI server, heavily used in manufacturing/enterprise to build firmware and test pipelines.

- **Buildbot (Free/Open-Source)** — https://buildbot.net  
  Python-based CI for long-running hardware tests, automated firmware builds, regression tests.

- **Zuul (Free/Open)** — https://zuul-ci.org  
  CI gate system used in telecom and cloud infrastructure; works well with complex hardware/firmware repos.

---

#### ✅ Artifact Management & Firmware Distribution (Free/Open)

- **JFrog Artifactory OSS** — https://jfrog.com/open-source  
  Host firmware binaries, Docker images, packages and artifacts. Free self-hosted OSS edition.

- **Nexus Repository OSS** — https://www.sonatype.com  
  Store firmware updates, bootloader images, package feeds for Yocto/Ubuntu.

- **GitHub Releases / Packages (Free Tier)** — distribute firmware artifacts, build logs and release notes.

- **GitLab Packages / Container Registry (Free)** — store firmware packages, Docker images, OTA binaries.

---

#### ✅ Code Review & Collaboration (Free/Open)

- **Gerrit (Free/Open-Source)** — https://www.gerritcodereview.com  
  Code review used extensively in Android, automotive and Linux kernel workflows.

- **Phabricator (Free/Open-Source)** — https://phacility.com (archived but open)  
  Code reviews, task boards and build pipelines for complex hardware/firmware repos.

- **Review Board (Free/Open)** — https://www.reviewboard.org  
  Code reviews for patches, diff-based workflow for embedded teams.

- **GitHub/GitLab code review tools (Free)** — comments, suggestions, PR approvals, branch protections.

---

#### ✅ Build Automation & Tooling

- **CMake (Free/Open)** — https://cmake.org  
  Standard build system for embedded C/C++ projects. Integrates with Ninja, GCC, Clang, etc.

- **Meson + Ninja (Free/Open)** — https://mesonbuild.com  
  Fast build system for modern embedded firmware projects.

- **Bazel (Free/Open)** — https://bazel.build  
  Used in robotics, automotive and large firmware builds with reproducible pipelines.

- **Yocto Project BitBake (Free/Open)** — https://yoctoproject.org  
  Build system for embedded Linux, images, toolchains and custom packages.

---

#### ✅ Self-Host CI/CD for Air-Gapped Labs

- **GitLab CE + Runners (Free/Open)** — complete DevOps with offline runners for manufacturing plants.

- **Drone / Woodpecker CI (Free/Open)** — container-based CI for local networks.

- **Jenkins (Free/Open)** — integrate hardware-in-loop test rigs, serial flashing, power-cycle testers.

- **Buildbot (Free/Open)** — used for long hardware cycles (RF tests, functional QA, power tests).

---

#### ✅ YAML-Pipeline Generators for Embedded

- **Renovate (Free/Open)** — auto-update dependencies, docker images, toolchains.

- **GitHub Dependabot (Free Tier)** — firmware repo security updates (if using Python/CMake/containers).

- **pre-commit (Free/Open)** — enforce code formatting, linting, commit scans before CI runs.

---

#### ✅ Extras: Versioned Documentation & Releases

- **MkDocs + GitHub Pages (Free)** — publish versioned docs per firmware release.

- **Sphinx + ReadTheDocs (Free)** — continuous docs build on new commits.

- **Changelogger / Conventional Commits (Free)** — structured release notes for embedded.

---

### 29C. Agile & Hardware Workflow Tools (Free / Open-Tier)

#### ✅ Agile / Kanban / Scrum for Hardware & Firmware Teams

- **Trello (Free Tier)** — https://trello.com  
  Visual Kanban boards for sprint planning, backlog, QA, release tracking. Useful for hardware BOM tasks, firmware tickets, PCB iterations.

- **Jira Free Plan** — https://www.atlassian.com/software/jira  
  Free plan for small teams: agile boards, sprints, epics, bug tracking. Firmware + hardware task management.

- **ClickUp Free Tier** — https://clickup.com  
  Agile boards, docs, sprint points, time tracking, automation. Works well for cross-functional hardware teams.

- **Taiga (Free/Open-Source)** — https://taiga.io  
  Agile project management platform supporting Scrum & Kanban. Self-host free and perfect for R&D hardware labs.

- **OpenProject Community Edition (Free/Open)** — https://www.openproject.org  
  Self-host agile boards, Gantt charts, requirements, documentation and releases.

- **Wekan (Free/Open-Source)** — https://wekan.github.io  
  Trello-like Kanban board, self-hostable, used widely in internal hardware labs.

- **GitHub Projects / Boards (Free)** — https://github.com  
  Kanban + Issues + CI/CD pipeline integration for firmware/EDA repos.

- **GitLab Boards (Free CE)** — https://gitlab.com  
  Integrated boards, issues, epics, dependencies for hardware-firmware workflows.

---

#### ✅ Requirements / Specs / Traceability (Free/Open)

- **Doorstop (Free/Open-Source)** — https://doorstop.readthedocs.io  
  Requirements management stored as files in Git. Perfect for firmware specs, PCB requirements and traceability.

- **ReqView Free Plan** — https://reqview.com  
  Document requirements, traceability links, exports. Free local version available.

- **Alloy (Formal Modeling – Free/Open)** — https://alloytools.org  
  Formal specification and constraint modeling for safety-critical hardware/firmware.

- **PlantUML + Markdown (Free/Open)** — embed sequence, state and block diagrams inside requirement docs.

- **Mermaid in GitHub/GitLab (Free)** — requirements + workflows + pipelines in docs.

---

#### ✅ BOM, Change Management & Hardware Workflows (Free/Open)

- **PartKeepr (Free/Open-Source)** — http://www.partkeepr.org  
  Inventory + parts tracking for PCB design and lab stock.

- **OpenBOM Free Personal** — https://www.openbom.com  
  Cloud-based BOM management, part lists, change logs and costing.

- **KiCad + BOM Plugins (Free/Open)** — auto-generate BOM + placement files + change logs for manufacturing.

- **OpenPDN / OMT Tools** — community open hardware lifecycle management.

---

#### ✅ Team Collaboration / Documentation (Free/Open)

- **Wiki.js (Free/Open)** — https://wiki.js.org  
  Internal engineering wiki with Markdown, diagrams and Git sync.

- **BookStack (Free/Open)** — https://www.bookstackapp.com  
  Used to maintain hardware guides, firmware release manuals, SOPs for testing teams.

- **Notion Free Tier** — https://notion.so  
  Knowledge base, SOP repository, checklists, BOM change logs.

- **Obsidian (Free)** — https://obsidian.md  
  Markdown note-taking with Git for schematics, debug logs, test results.

---

#### ✅ Sprint Reporting, Issues & QA

- **Redmine (Free/Open-Source)** — https://www.redmine.org  
  Issue tracking, Gantt charts, wikis, release planning for hardware/testing cycles.

- **MantisBT (Free/Open)** — https://www.mantisbt.org  
  Bug tracker for firmware and validation logs.

- **Trac (Free/Open)** — https://trac.edgewall.org  
  Lightweight wiki + issue tracker for embedded R&D teams.

- **GitHub Issues (Free)** — default option for firmware teams with Actions for CI, labeling, milestones.

---

#### ✅ Hardware Change / Revision Control

- **Git + KiCad (Free/Open)** — diff-able hardware repo with revision tracking.

- **OpenHardware Repository CI Templates** — free community workflows for Gerbers, 3D, BOM auto-generation.

- **GitLab Releases & Artifacts (Free)** — version hardware output files per commit.

---

#### ✅ Cloud-Enabled Collaboration (Free Tier)

- **Figma Free Tier** — mechanical enclosure collaboration diagrams and UI mockups for HMIs.

- **Diagrams.net (Free)** — block diagrams, wiring, harness diagrams committed to Git repos.

- **Google Docs/Sheets (Free)** — shareable design docs, BOMs and quality checklists.

---

### 29D. Requirements Tracking, FMEA, Issue Tracking (Free / Open)

#### ✅ Requirements Management (Free / Open-Source / Free Tier)

- **Doorstop (Free/Open-Source)** — https://doorstop.readthedocs.io  
  Store requirements as plain text in Git. Full traceability between specs, tests, firmware commits and releases.

- **ReqView (Free Local Edition)** — https://reqview.com  
  Requirement documents, traceability matrices, export to Word/PDF. Free for single-user projects.

- **Polarion XTRIAL (Free Trial / Academic)** — widely used in automotive/embedded for requirements & traceability.

- **OpenProject Community Edition (Free/Open)** — https://www.openproject.org  
  Self-hosted requirements, tasks, Gantt, baselines, docs.

- **GitLab Issues + Epics (Free)** — requirements as issues with labels, milestones, CI checks.

- **GitHub Projects + Issues (Free)** — lightweight requirements tracking with PR reviews and automated checks.

- **Alloy (Formal Spec – Free/Open)** — https://alloytools.org  
  Model safety-critical requirements and system constraints formally.

---

#### ✅ FMEA, Risk Analysis, Safety Tools (Free/Open)

- **Xfmea Free Templates (Community)** — community Excel/Sheets templates for FMEA & DFMEA workflows.

- **OpenFTA (Free/Open)** — https://www.openfta.com  
  Fault tree analysis for safety-critical hardware and firmware systems.

- **Cafta (Free Academic)** — used for reliability and fault tree analysis.

- **ISO 26262 / DO-178C Checklists (Free Community)** — open sets of safety checklist docs maintained by universities/communities.

- **YEd Graph Editor (Free)** — model block diagrams, event trees, failure paths visually and export to PDF/SVG.

- **Mermaid / PlantUML (Free/Open)** — generate fault trees, block diagrams and event sequences directly in docs.

- **FTA Tools in Python (Free/Open)** — multiple GitHub repos performing failure modeling and Monte-Carlo reliability analysis.

---

#### ✅ Issue Tracking & Test Tracking (Free/Open)

- **Redmine (Free/Open-Source)** — https://www.redmine.org  
  Complete issue tracking, Gantt, wiki, release planning. Used in firmware labs and manufacturing QA.

- **MantisBT (Free/Open)** — https://www.mantisbt.org  
  Lightweight bug tracker for firmware issues, validation logs, QA feedback loops.

- **Trac (Free/Open)** — https://trac.edgewall.org  
  Wiki + tickets + revision linking for embedded R&D teams.

- **Taiga (Free/Open)** — https://taiga.io  
  Agile boards + backlog + sprint issues. Free for small teams and open-source projects.

- **Phabricator (Free/Open)** — https://phacility.com  
  Code review + ticket system + wiki for hardware/firmware collaboration.

- **Fossil SCM (Free/Open)** — https://fossil-scm.org  
  Built-in wiki, ticketing and version control in one binary. Compact tool for labs.

- **Jira Free Plan** — https://www.atlassian.com/software/jira  
  Limited free tier for small teams with boards, epics and bug tracking.

---

#### ✅ Traceability / Verification (Free/Open)

- **Robot Framework (Free/Open)** — https://robotframework.org  
  Test automation for embedded, REST APIs, UI, hardware-in-loop setups.

- **PyTest (Free/Open)** — unit testing framework often used with firmware simulators and hardware abstraction.

- **CTest (Free/Open)** — part of CMake; integrates with CI for firmware unit testing.

- **GitHub Actions / GitLab CI (Free)** — automated verification on each commit, traceable to requirements.

- **Check (C unit testing – Free/Open)** — https://libcheck.github.io/check  
  Unit test framework for C code in embedded projects.

---

#### ✅ Safety / Compliance Documentation Generators (Free/Open)

- **Pandoc + LaTeX** — generate compliance docs, safety manuals, hardware validation reports.

- **MkDocs Material + Versioning** — versioned hardware requirements + trace logs.

- **Sphinx + Breathe** — combine code/API docs with requirements for complete traceability.

---

### 29E. PCB & Firmware Quality, Linting, Static Analysis Tools (Free / Open-Source)

#### ✅ Firmware Linting, Code Quality & Static Analysis (Free/Open)

- **Cppcheck (Free/Open)** — http://cppcheck.sourceforge.net  
  Static analysis for C/C++: detects memory leaks, null dereferences, bounds issues. Widely used in embedded CI pipelines.

- **Clang-Tidy (Free/Open)** — https://clang.llvm.org/extra/clang-tidy  
  Code style, bug detection, MISRA-ish checks, modern C++ guidelines. Integrates with CMake and GitHub Actions.

- **Clang Static Analyzer (Free/Open)** — https://clang-analyzer.llvm.org  
  Deep path analysis for C/C++ firmware. Finds real defects, nulls, leaks, logic pitfalls.

- **PVS-Studio Free for FOSS** — https://pvs-studio.com  
  Advanced analysis for C/C++/C#/Java. Free for open-source firmware and academic use.

- **SonarQube Community Edition (Free/Open)** — https://www.sonarqube.org  
  Quality dashboards for C/C++/Python. Detects bugs, smells, complexity. Self-hostable and works with CI.

- **Flawfinder (Free/Open)** — https://dwheeler.com/flawfinder  
  Security vulnerability scanner for C/C++ firmware.

- **Infer (Free/Open)** — https://fbinfer.com  
  Facebook static analyzer used in mobile and systems code. Detects concurrency bugs, nulls, logic issues.

- **cpp-lint / cpplint (Free/Open)** — Google C++ style checker. Works with microcontroller repos.

- **ESLint / Pylint / Rust Clippy (Free/Open)** — free linters for embedded dashboards, Python scripts, Rust firmware.

---

#### ✅ MISRA, CERT, Safety Compliance – Free Tools

- **clang-tidy MISRA Profiles (Community Free)** — unofficial rule checks for MISRA-C.

- **cppcheck MISRA addons (Community)** — rule checks for safety-critical firmware.

- **SuperTest Community Suites (Free limited)** — MISRA, AUTOSAR rule validation (academic/open).

- **Open-Source MISRA checkers in GitHub CI** — multiple action templates applying MISRA & CERT scans.

---

#### ✅ Unit Testing Frameworks (Free/Open)

- **Unity (Free/Open)** — http://www.throwtheswitch.org/unity  
  Microcontroller-focused C unit test framework. Works with CMock and Ceedling.

- **Ceedling (Free/Open)** — http://www.throwtheswitch.org/ceedling  
  Full embedded test harness with mocks, runners, reports.

- **CMock (Free/Open)** — auto mock generator for C interfaces and drivers.

- **GoogleTest (Free/Open)** — https://github.com/google/googletest  
  C++ unit testing for embedded host-side tests.

- **CTest (Free/Open)** — part of CMake; CI-friendly test runner.

- **PyTest (Free/Open)** — Python test automation for HAL simulators, hardware-in-loop scripts.

---

#### ✅ Code Coverage & Profiling (Free/Open)

- **gcov / lcov (Free/Open)** — GCC code coverage and HTML reporting. Ideal for embedded unit tests.

- **GProf (Free/Open)** — profiling CPU time and hotspots in firmware running on host/sim.

- **Valgrind (Free/Open)** — detect memory corruption, leaks, undefined behavior in host builds.

---

#### ✅ Hardware/PCB Quality & Rule Checking (Free/Open)

- **KiCad DRC/ERC (Free/Open)** — https://kicad.org  
  Electrical rule checking, net violations, clearances, differential pairs. Free for PCB design quality.

- **OpenDRC / Gerbv (Free/Open)** — https://gerbv.github.io  
  Gerber viewer and rule checks for PCB manufacturing validation.

- **LibrePCB (Free/Open)** — https://librepcb.org  
  Open PCB CAD with DRC, BOM, lattice checking.

- **FreeDFM by OSHpark (Free)** — https://oshpark.com  
  Upload Gerbers and run manufacturing DFM checks free.

- **PCBWay DFM Test (Free)** — free manufacturability checks online.

- **JLCPCB Gerber Analyzer (Free)** — free fabrication rule validation.

- **KiCad StepUp (Free)** — mechanical clearance validation with FreeCAD.

---

#### ✅ Hardware Test Automation (Free/Open)

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Production test automation for boards, fixtures, DUT stimulus, functional validation.

- **pytest + PyVisa + SCPI (Free/Open)** — automate oscilloscopes, PSUs, loads for PCB bring-up.

- **OpenAPS / Hardware-in-loop scripts** — community frameworks for automated device testing.

---

#### ✅ Continuous Quality Dashboards (Free)

- **SonarQube Community + GitHub Actions** — free quality gates for C/C++ firmware.

- **GitLab Code Quality Reports** — pipeline that flags defects on MR/PR.

- **Codecov Free Tier** — uploads gcov/lcov coverage to dashboards (public repos free).

- **Coveralls Free Tier** — free code coverage for open-source firmware.

---
### 30A. Free Embedded Books / PDFs / Online Material

#### ✅ MCU & Embedded Systems Books (Free/PDF)

- **“The Definitive Guide to ARM Cortex-M0/M3/M4” (Free PDFs online via vendors)**  
  Vendor-distributed editions covering architecture, registers, interrupts, firmware and RTOS basics.

- **“The Art of Assembly Language” (Free/Open PDF)** — https://www.plantation-productions.com/Webster/  
  Classic deep guide to assembly and low-level CPU operations.

- **“Dive Into Systems” (Free/Open PDF)** — https://diveintosystems.org  
  Beginner-friendly book on computer architecture and low-level programming.

- **“Mastering Microcontrollers (on AVR/PIC)” (Community PDFs)**  
  Free educational editions from multiple universities; covers C programming & peripherals.

- **“BeagleBone Cookbook” (Free Online)** — various open chapters for Linux-based embedded systems.

- **“Operating Systems: Three Easy Pieces (OSTEP)” (Free PDF)** — https://pages.cs.wisc.edu/~remzi/OSTEP  
  Great OS fundamentals for embedded Linux engineers.

- **“Control Systems Lectures (K. Ogata)” – Free educational slides/PDFs**  
  Found in many university portals, covers control fundamentals for robotics and drives.

- **“Digital Design” (M. Mano) – University-provided PDFs**  
  Widely shared for logic design fundamentals.

---

#### ✅ Linux, IoT & Networking Books (Free)

- **“Linux From Scratch (LFS)” (Free/Open)** — https://www.linuxfromscratch.org  
  Step-by-step instructions to build Linux from source. Perfect for embedded Linux developers.

- **“The Linux Command Line” (Free PDF)** — http://linuxcommand.org  
  Beginner to advanced shell guidance — must-read for embedded Linux.

- **“Beej’s Guide to Network Programming” (Free)** — https://beej.us/guide/bgnet  
  Socket programming and TCP/UDP fundamentals used in IoT firmware & gateways.

- **“Beej’s Guide to C Programming” (Free)** — https://beej.us/guide/bgc  
  Excellent free C guide for MCU programmers.

- **“Beej’s Guide to Pipe/Pipe2/IPC” — free complementary networking material.**

- **“Embedded Linux Primer” (Free excerpts)** — several free legally hosted chapters online.

---

#### ✅ RTOS, Firmware Architecture & Drivers

- **FreeRTOS Reference Manual (Free PDF)** — https://www.freertos.org  
  Official kernel API documentation, task scheduling, memory, MCU ports.

- **Zephyr Project Documentation (Free/Open)** — https://docs.zephyrproject.org  
  Driver model, device tree, subsystems — open documentation for modern embedded systems.

- **“μC/OS-III Real-Time Kernel Book” (Free Download from Micrium)**  
  Detailed RTOS internals, scheduling, synchronization and porting.

- **LVGL Documentation (Free/Open)** — https://docs.lvgl.io  
  Graphics and UI stack for embedded displays.

- **STM32, NXP, TI, Renesas, Infineon Training PDFs (free vendor portals)**  
  Driver tutorials, HAL examples, power modes, bootloaders.

---

#### ✅ Electronics, Power & PCB Design (Free)

- **“All About Circuits” (Free Online Book)** — https://www.allaboutcircuits.com  
  Electronics fundamentals, circuits, microcontrollers and PCB basics.

- **“Lessons in Electric Circuits” (Free/Open Book)** — https://www.ibiblio.org/kuphaldt/electricCircuits/  
  Full electronics textbook series, completely open.

- **“The Free Range VHDL Book / Verilog Book” (Free PDFs)** — widely used in FPGA basics.

- **“Chua’s Circuit & Nonlinear Electronics Books” (Free/Open)** — advanced analog material online.

- **Switching Power Supply Design (TI/NXP/ADI Free Guides)** — vendor reference books on SMPS, DC-DC, EMI.

---

#### ✅ Robotics & Control (Free)

- **“Modern Robotics” (MIT Press) – Free PDF** — http://hades.mech.northwestern.edu/index.php/Modern_Robotics  
  Kinematics, dynamics, motion planning, control — gold standard.

- **ROS Tutorials & Books (Free/Open)** — https://www.ros.org  
  Full open robot middleware documentation.

- **MIT Control Theory Notes (Free PDFs)** — openly hosted lecture collections.

---

#### ✅ Cybersecurity, IoT Security & Cryptography (Free)

- **“Crypto101” (Free/Open Book)** — https://crypto101.io  
  Introduction to cryptography, ciphers, MAC, hashes, crypto attacks.

- **“The Joy of Cryptography” (Free PDF)**  
  Academic-style walkthrough of crypto fundamentals.

- **Free IoT Security Training PDFs (ENISA, OWASP IoT, NIST)** — official open reports and best practices.

- **WolfSSL / MBedTLS Docs (Free/Open)** — embedded TLS, secure boot, crypto APIs.

---

#### ✅ MCU Vendor Training Books & Handbooks

- **STM32 Blue Pill & Nucleo Labs (Free PDFs & Guides)** — community manuals & HAL tutorials.

- **ESP-IDF Programming Guides (Free)** — https://docs.espressif.com  
  Networking, drivers, Wi-Fi/BLE stacks, OTA.

- **Nordic DevAcademy (Free)** — BLE, Zephyr, nRF52 SDKs.

- **TI MCU Academy (Free)** — C2000, MSP430, driver/RTOS training.

- **Microchip Developer Help (Free)** — PIC/AVR/ARM tutorials, app notes, books.

---

### 30B. Free MCU Vendor Training / Learning Portals

#### ✅ ESP32 / ESP-IDF / RISC-V (Espressif)

- **Espressif ESP-IDF Docs & API Guides (Free)** — https://docs.espressif.com  
  Full SDK documentation, examples, Wi-Fi/BLE stacks, OTA, drivers, secure boot, partitioning.

- **Espressif Training Portal (Free)** — https://www.espressif.com/en/support/training  
  Official training videos, hands-on labs and certification pathways.

- **ESP Academy (Community Free)** — curated lectures + practical firmware labs for ESP32/ESP8266.

---

#### ✅ STMicroelectronics (STM32 / STM8)

- **STM32Cube MCU Training (Free)** — https://www.st.com/en/development-tools/stm32cubemx.html  
  HAL drivers, CubeMX, power modes, middleware, bootloaders, X-CUBE stacks.

- **STM University Program (Free PDFs & Labs)** — open training courseware for embedded teachers and students.

- **STM32 MOOC (Free)** — official free video courses on ARM Cortex-M, RTOS, connectivity and security.

---

#### ✅ Nordic Semiconductor (nRF5x / nRF52 / BLE / Zephyr)

- **Nordic DevAcademy (Free Online Courses)** — https://academy.nordicsemi.com  
  BLE, Zephyr RTOS, power profiling, security, DFU/OTA, sensor integration.

- **nRF Connect SDK Docs (Free)** — https://developer.nordicsemi.com  
  BLE Mesh, Thread/Matter, secure boot, OpenThread, LTE-M/NB-IoT examples.

---

#### ✅ Texas Instruments (TI – MSP430, C2000, Sitara)

- **TI “MCU Academy” (Free)** — https://dev.ti.com  
  Deep training for MSP430, C2000, real-time motor control, DSP, power systems.

- **TI University Program (Free)** — lecture slides, lab manuals, student books.

- **Power Electronics Training (Free)** — reference designs & SMPS training for industrial/automotive.

---

#### ✅ Microchip (PIC / AVR / SAM / PIC32)

- **Microchip Developer Help (Free)** — https://microchipdeveloper.com  
  Tutorials for PIC, AVR, ARM SAM, Harmony, MPLAB X IDE, bootloaders, drivers.

- **MPLAB X University Courses (Free)** — complete labs for timers, ADC, UART, SPI, I2C.

- **Atmel Software Framework Legacy Docs (Free)** — still widely used for AVR and Cortex-M0+.

---

#### ✅ NXP (Kinetis, LPC, i.MX, FreeRTOS)

- **NXP eLearning Portal (Free)** — https://nxp.com  
  Cortex-M firmware, security, Matter, MCUXpresso, FreeRTOS and USB stacks.

- **MCUXpresso SDK + Examples (Free)** — device drivers, middleware, RTOS examples, power modes, TrustZone.

---

#### ✅ Renesas (RL78, RX, RA, Synergy)

- **Renesas Online Training (Free)** — https://www.renesas.com  
  Modules on RTOS, security, power efficiency, toolchains, Bluetooth LE.

- **RA Smart Configurator Labs (Free)** — drag-and-drop peripheral setup plus code gen.

- **Renesas University Program (Free)** — slides, labs and teaching kits.

---

#### ✅ Infineon (PSoC, XMC, Aurix, Wi-Fi/BLE)

- **Infineon Developer Training (Free)** — https://www.infineon.com/cms/en/training  
  PSoC, XMC motor control, Wi-Fi, BLE, Matter, hardware security.

- **ModusToolbox Code Examples (Free)** — drivers, connectivity, OTA, cloud.

---

#### ✅ Silicon Labs (EFR32, Zigbee, Matter)

- **Silabs Training Portal (Free)** — https://silabs.com  
  Zigbee, Matter, Thread, OpenThread, RTOS, Secure Boot, PSA-Level security.

- **Simplicity Studio Labs (Free)** — onboarding for EFR32 with full examples.

---

#### ✅ Raspberry Pi & RP2040 (Pico)

- **Pico C SDK Book (Free PDF)** — https://www.raspberrypi.com/documentation/microcontrollers  
  GPIO, PIO, DMA, C/C++ firmware development.

- **Pico Python SDK Docs (Free)** — MicroPython training for beginners.

---

#### ✅ STM32, ESP32, nRF & TI Community Labs (Free)

- Thousands of open GitHub labs + tutorials teaching drivers, RTOS, MQTT, BLE, OTA and cloud integration.

---

### 30C. Free IoT Security Courses, Bootcamps & Certifications

#### ✅ Official / Government / Standards Bodies

- **ENISA IoT Security Training (Free PDFs & Videos)** — https://www.enisa.europa.eu  
  Courses and guidelines on embedded security, secure update, key management, supply-chain risks.

- **NIST IoT Security Guidelines (Free PDFs, Reference Frameworks)** — https://www.nist.gov  
  Best practices, secure boot, crypto, IoT lifecycle, device identity, patching, vulnerability disclosure.

- **OWASP IoT Security Project (Free/Open)** — https://owasp.org/www-project-internet-of-things  
  Free labs, top-10 IoT vulnerabilities, testing guides and firmware security checklists.

- **IoT Security Foundation (Free Resources)** — https://iotsecurityfoundation.org  
  Free rules, checklists, compliance overviews, secure design principles for embedded devices.

---

#### ✅ Embedded Security Courses (Free / Open)

- **CyberSecurityBase (Free Course)** — University of Helsinki  
  Covers secure software development, threat modeling, crypto mistakes and mitigations.

- **Crypto101 (Free/Open Book & Course)** — https://crypto101.io  
  Beginner to intermediate cryptography for firmware and hardware engineers.

- **Let’s Encrypt Ciphers / TLS Academy (Free Online Modules)** — TLS basics for embedded Linux / IoT gateways.

- **MBedTLS / WolfSSL Docs (Free)** — secure TLS, ECC, X.509, DTLS for constrained devices.

- **Nordic Semiconductor Security Training (Free)** — pairing, bonding, BLE security, confidentiality and OTA DFU signing.

---

#### ✅ Firmware & Reverse Engineering Training (Free)

- **Ghidra Courses (Free/Open)** — https://ghidra-sre.org  
  Reverse engineering basics for firmware, ELF binaries, RTOS images.

- **Intro to Embedded Security (Free YouTube Courses)** — exploitation of UART, JTAG, SWD, bootloaders and unsigned firmware.

- **IoT Pentesting Online Labs (Free/Open)** — firmware extraction, UART consoles, emulators, binwalk, QEMU.

- **Project Zero Write-ups (Free)** — deep dives into real firmware vulnerabilities, secure boot bypasses.

---

#### ✅ Wireless Security (Free)

- **HackRF & SDR Security Tutorials (Free/Open)** — replay attacks, protocol fuzzing, sub-GHz IoT traffic.

- **WPA3/WPA2 Security Labs (Free)** — Wi-Fi encryption, certificates, EAP-TLS, authentication flows.

- **BLE Security Tutorials (Free)** — MITM, pairing, bonding, GATT exploits, sniffer tools.

---

#### ✅ Secure Boot, TPM, PQC (Free/Open)

- **PQShield & NIST PQC Resources (Free)** — post-quantum crypto overviews, open reference code.

- **OpenTitan Docs (Free/Open)** — hardware root-of-trust, secure boot chain.

- **MCUboot Docs (Free/Open)** — signing, AES encryption, rollback prevention.

- **Trusted Firmware-M (Free/Open)** — PSA Certified security framework for Cortex-M.

---

#### ✅ University-Level Cybersecurity Courses (Free/PDF)

- **Stanford CS155 Notes (Free)** — security engineering fundamentals.  
- **MIT OCW Cybersecurity Courses (Free)** — threat modeling, crypto, secure coding.  
- **Georgia Tech OMSCS “Intro to Information Security” (Free Videos)** — overview of applied security.

---

### 30D. Free Academic Repositories & Research Papers (Embedded / IoT / Electronics)

#### ✅ University Research Paper Libraries (Free Access / Open Repos)

- **arXiv (Free/Open)** — https://arxiv.org  
  World’s largest open repository of academic papers. Huge sections on embedded systems, IoT security, signal processing, robotics, ML on microcontrollers.

- **HAL Archives (Free)** — https://hal.science  
  European open archive for research in electronics, wireless sensing, CPS, embedded computing and energy systems.

- **CERN Document Server (Free/Open)** — https://cds.cern.ch  
  Deep research on electronics, FPGAs, radiation-tolerant hardware, particle detector embedded systems.

- **NASA Technical Reports Server (Free)** — https://ntrs.nasa.gov  
  Aerospace electronics, high-reliability embedded systems, radiation effects, fault-tolerant computing, power electronics.

- **MIT OpenCourseWare (Free)** — https://ocw.mit.edu  
  Full lecture modules, PDFs, assignments on digital systems, control theory, operating systems, embedded robotics.

- **Stanford Online / CS Resources (Free Notes)** — free slides & PDFs on computer architecture, networks, security.

---

#### ✅ IoT Security, Wireless & Protocol Research

- **IACR ePrint (Free/Open)** — https://eprint.iacr.org  
  Latest crypto research including PQC, ECC, secure boot, signatures for embedded devices.

- **NIST PQC & Lightweight Crypto Submissions (Free)** — all algorithm specs, reference code, and papers for post-quantum candidates.

- **LoRa/LPWAN Academic Papers (Public Free Links)** — IEEE preprints and university-backed open datasets on LoRa, ChirpStack, gateways, localization.

- **ResearchGate (Free Access Papers)** — many authors share PDFs of embedded, IoT, power electronics research.

- **OpenWSN Papers & Theses (Free)** — 6TiSCH, TSCH, low-power wireless stacks for industrial IoT.

---

#### ✅ Robotics, SLAM & Digital Twin Research

- **IEEE RAS Open Access Papers (Free)** — robotics algorithms, SLAM, kinematics, motion planning.

- **Open Robotics Research Library** — ROS, Gazebo, multi-robot planning papers uploaded by researchers.

- **CARLA & AirSim Papers (Free/Open)** — open research on autonomous systems, digital twins, photorealistic simulation.

- **OpenDSS / GridLAB-D Papers** — energy digital twin research, smart grid control, forecasting.

---

#### ✅ Embedded AI / TinyML Research & Datasets

- **TinyML Foundation Resources (Free)** — presentations, whitepapers, model benchmarks, MCU case-studies.

- **MLCommons / MLPerf Tiny (Free/Open)** — performance benchmarks and open datasets for embedded ML.

- **UCI Machine Learning Repository (Free)** — datasets for classification and sensor-time-series (faults, vibrations, environmental).

- **NASA Turbofan / Bearing Datasets (Free)** — classic predictive maintenance datasets.

---

#### ✅ Hardware Security, Fault Injection & Side-Channel (Free Repos)

- **OpenTitan (Free/Open)** — https://opentitan.org  
  Open silicon root-of-trust; full research papers, hardware security architecture.

- **ChipWhisperer Research (Free)** — https://chipwhisperer.io  
  Side-channel attack papers, labs, firmware injection, power analysis.

- **Side-Channel Analysis Repositories (Community Open)** — multiple free datasets & tools for CPA/DPA.

- **Trusted Firmware Docs (Free/Open)** — secure boot, PSA Certified architecture for Cortex-M.

---

#### ✅ FPGA, VLSI & Open Hardware Research

- **OpenROAD Project Papers (Free/Open)** — autonomous RTL-to-GDSII flow research.

- **RISC-V Papers (Free/Open)** — specs, ISA docs, extensions, hardware verification.

- **FPGA4Student / Academic VHDL/Verilog (Free)** — open projects, labs and research references.

- **Open-Core designs (Free/Open)** — academic CPU, AI accelerators, SoC papers.

---

#### ✅ Archive Collectors & Search Engines (Free)

- **Semantic Scholar (Free)** — https://www.semanticscholar.org  
  AI-powered paper search, PDF links, citation graphs for embedded/IoT/robotics.

- **CORE.ac.uk (Free/Open)** — aggregates millions of free-access research papers globally.

- **Directory of Open Access Journals (DOAJ)** — https://doaj.org  
  Journals with open-access electronics and engineering publications.

---

### 30E. Free Simulators & Sandboxes for Learning (Embedded, IoT, Networks)

#### ✅ Microcontroller & Firmware Simulators (Free / Open)

- **Wokwi (Free Online MCU Simulator)** — https://wokwi.com  
  Browser-based simulation for Arduino, ESP32, STM32, sensors, displays, logic analyzers. Great for quick prototyping and teaching.

- **SimulIDE (Free/Open-Source)** — https://simulide.com  
  Real-time MCU + electronics simulator supporting AVR, PIC, Arduino and digital circuits.

- **EdSim51 (Free)** — http://edsim51.com  
  8051 microcontroller simulator with peripherals, LCD, ADC, serial port.

- **Online GDB / Compiler Explorer (Free)** — https://compiler-explorer.com  
  Compile C/C++ firmware, inspect assembly and optimization outputs.

- **Proteus Demo (Free Limited)** — valuable for education: MCU + circuit simulation, virtual instruments.

- **MCU8051IDE (Free/Open)** — integrated 8051 simulator for academics.

- **Tinkercad Circuits (Free)** — https://www.tinkercad.com  
  Beginner-friendly electronics + Arduino simulation with circuit editor.

---

#### ✅ Industrial Protocol & SCADA Sandboxes (Free)

- **Conpot (Free/Open)** — https://github.com/mushorg/conpot  
  SCADA/PLC honeypot for learning industrial protocols, cyber-security, Modbus, S7.

- **OpenPLC Runtime (Free)** — https://www.openplcproject.com  
  Experimental SoftPLC to test ladder logic, Modbus TCP/RTU and digital IO virtually.

- **QModMaster (Free)** — Modbus master simulator with register browser.

- **ModRSsim2 (Free)** — Modbus slave simulator to test SCADA clients, HMIs and PLCs.

- **nodered.org (Free)** — live browser sandbox for industrial flows, MQTT and dashboards.

---

#### ✅ Networking & IoT Protocol Simulators (Free/Open)

- **NS-3 (Free/Open-Source)** — https://www.nsnam.org  
  Network simulator for Wi-Fi, LTE, 5G, TCP/UDP, TSN and IoT protocols.

- **OMNeT++ (Free/Open)** — https://omnetpp.org  
  Powerful IoT networking simulation with plugins for LoRa, Zigbee, 6LoWPAN, TSCH.

- **Cooja (Free/Open)** — https://github.com/contiki-ng/cooja  
  IoT simulator for Contiki-NG. Emulates low-power wireless stacks and sensor motes.

- **TOSSIM (Free/Open)** — TinyOS network simulator for low-power sensor networks.

- **Riverbed Modeler Academic Edition (Free)** — network behavior modeling used in educational IoT labs.

---

#### ✅ Robotics, Machine Vision & Digital Twin Sandboxes (Free/Open)

- **Gazebo / Ignition Robotics (Free/Open)** — https://gazebosim.org  
  3D dynamic robot + sensor simulator with HD cameras, LiDAR, IMU. Perfect for AGVs, warehouse robots and twins.

- **Webots (Free/Open)** — https://cyberbotics.com  
  Real-time robotics simulator with ROS integrations, controllers and sensors.

- **CARLA (Free/Open)** — https://carla.org  
  Autonomous driving simulator — sensor fusion, SLAM, perception, control.

- **AirSim (Free/Open)** — https://github.com/microsoft/AirSim  
  Drone + ground robot simulator with depth cameras, IMUs, GPS and physics.

- **OpenCV Playground (Free)** — online notebooks for beginner computer vision tasks.

---

#### ✅ Embedded Linux & Cloud IoT Sandboxes

- **AWS Free Tier IoT Core sandbox** — MQTT, rules engine, shadow devices for IoT learning.

- **Azure Free Tier IoT Hub sandbox** — device registry, telemetry ingestion, digital twins.

- **Google Cloud Free Tier IoT Core (legacy examples)** — MQTT ingestion demos, cloud functions.

- **Balena Free Tier** — deploy containers to Raspberry Pis for practical IoT training.

- **QEMU (Free/Open)** — emulate ARM/RISC-V boards, Linux boot, kernel drivers, custom OS for embedded Linux learning.

---

#### ✅ Power Electronics & Motor Control Simulators (Free)

- **LTspice (Free)** — SMPS, converters, gate drivers, motor drivers, thermal analysis.

- **PLECS / PSIM Student Editions (Free)** — converter + motor drive simulation with waveforms.

- **EMotorSim (Free)** — basic motor models and inverter control for education.

---

#### ✅ Drones & Wireless Labs (Free)

- **ArduPilot SITL (Free/Open)** — https://ardupilot.org  
  Drone flight controller simulation, sensor models, MAVLink telemetry.

- **PX4 SITL (Free/Open)** — https://px4.io  
  UAV autopilot simulator supporting Gazebo and AirSim.

---

## G) Compliance & Certification

---

### 31. EMI/EMC Pre-Compliance Tools (Free / Open-Source / Free-Tier)

- **EMCStudio Lite (Free Edition)** — https://emcstudio.com  
  Basic EMC simulation & near-field visualisation for pre-compliance checks.

- **OpenEMS (Free/Open-Source)** — https://www.openems.de  
  Full-wave electromagnetic solver (FDTD) for PCB, antenna and enclosure EMI analysis.

- **Qucs-S (Free/Open)** — https://ra3xdh.github.io  
  RF/EMC circuit simulation: S-parameters, filters, matching networks.

- **KiCad EMC Plugins (Free/Open)** — https://kicad.org  
  DRC for differential pairs, return paths, decoupling, stitching vias — used for EMI-aware PCB layout.

- **Gerbv (Free/Open)** — https://gerbv.github.io  
  Gerber viewer to validate copper pours, keep-outs, polygon splits that may cause EMC issues.

- **Near-Field Probe DIY Projects (Open)** — community GitHub repos for low-cost pre-compliance PCB sniffers.

- **LTspice (Free)** — https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html  
  SMPS ringing, ground-bounce, switch-node overshoot — critical input to EMC debugging.

- **OpenVDB / FEMM (Free/Open)** — electromagnetic field modeling around coils, inductors, transformers.

- **Sigrok + Open-Source Analyzers (Free)** — https://sigrok.org  
  Digital protocol timing + noise identification via logic analyzers.

- **R&S “EMC Pocket Guide” (Free PDF)** — free pre-compliance reference from Rohde & Schwarz.

- **Tektronix Pre-Compliance App Notes (Free)** — LISN setup, radiated/conducted guidelines & checklists.

- **MiniVNA / NanoVNA (Open Firmware Tools)** — calibration files + free software to test RF filters/antennas for spurious harmonics.

---

### 32. Safety Standards & Testing References (Free / Open)

- **IEC, UL, ISO Summary Sheets (Free Public Summaries)**  
  High-level guidance for IEC 62368-1, IEC 61010, UL 60730, medical, industrial, household electronics.

- **TÜV Rheinland Knowledge Base (Free)** — general safety design tips for consumer electronics and IoT.

- **CE Marking Guides (Free EU Docs)** — self-declaration, documentation, technical files, DoC templates.

- **OSHA Electrical Safety Guides (Free)** — wiring, creepage/clearance, protective earth, leakage current.

- **Creepage / Clearance Calculators (Free Web Tools)** — CTI, pollution degree, altitude corrections.

- **Fuses / PTC Selection Guides (Free PDFs)** — LittelFuse, Bourns, Eaton application notes.

- **Safety-Critical MCU Design Guides (TI/NXP/ST – Free PDFs)** — watchdogs, brown-out, lockstep CPUs.

- **OpenFTA (Free/Open-Source)** — https://www.openfta.com  
  Fault tree analysis for safety compliance projects.

- **MIT Open Courseware – Safety Engineering (Free)** — risk analysis, redundancies, SIL levels.

- **Automotive Safety (ISO 26262) Free Checklists** — community spreadsheets & training PDFs.

- **Medical Compliance Basics (Free PDFs)** — 60601-1 intro docs, leakage current examples, isolation standards.

---

### 33. Battery & Environmental Certification (Free Resources)

- **UN38.3, IEC 62133 Quick Guides (Free PDFs)** — public labs and certification bodies publish step-by-step requirements.

- **Battery University (Free)** — https://batteryuniversity.com  
  Safety, thermal runaway, pack design, balancing, certification basics.

- **TI/NXP/Analog Battery App Notes (Free)** — cell balancing, fuel gauges, thermal fusing, protections.

- **UL 2054 & UL 1642 Public Summaries** — design rules for consumer lithium packs.

- **IEC Transportation Checklists (Free)** — packaging, MSDS, shipping docs for air/road logistics.

- **RoHS / WEEE / REACH Documentation Templates (Free)** — EU compliance declarations, material reports.

- **IPC-1752A Material Declarations (Free Tools)** — XML templates for RoHS BOM compliance.

- **Free SDS/MSDS Databases** — cell chemistry, electrolyte safety sheets, transport hazard classifications.

- **Environmental Stress Testing Guides (Free)** — drop, humidity, thermal cycling tutorials from major labs.

---

### 34. RF Certification & Spectrum Resources (Free / Open)

- **FCC Equipment Authorization Guides (Free)** — https://www.fcc.gov  
  Radio testing, modular radios, antenna changes, labeling, SAR/EMI requirements.

- **ETSI Free Docs (Europe)** — https://www.etsi.org  
  Harmonized EN standards for SRD, Wi-Fi, BLE, Zigbee, LoRa; power limits, duty cycles, band plans.

- **India WPC / ETA Guidelines (Free PDFs)** — permitted ISM bands, power limits, licensing requirements.

- **LoRa Alliance Regional Parameters (Free)** — band plans for AS923, EU868, US915, IN865.

- **Spectrum Analyzer Open Tools (Free)**  
  - Open-source firmware for RTL-SDR  
  - sigrok decoders for RF modulation analysis  
  - GNURadio (Free/Open) for protocol analysis

- **Antenna Calculators (Free Tools)** — quarter-wave, helical, PCB trace antenna calculators for 433/868/915/2.4GHz.

- **RF Exposure & SAR Guidelines (Free)** — FCC/ICNIRP public guidance.

- **ITU Frequency Allocations (Free Maps)** — global band plans for IoT, cellular, satellite.

- **Chip Vendor RF Design Guides (Free)** — Nordic, Espressif, TI, Microchip PCB antenna tuning and matching docs.

- **Open-Source VNA Software (Free)** — nanoVNA-Saver for tuning antennas and filters.

- **VSWR / Smith Chart Web Tools (Free)** — compute matching networks, S11, return loss.

- **Rohde & Schwarz “EMI Debugging Guide” (Free)** — locating harmonics, board re-spin checklists.

### 35. Automotive / ISO 26262 / Functional Safety (Free / Open Resources)

#### ✅ Automotive Safety Standards & Guidance (Free/Public Docs)

- **ISO 26262 Public Overviews (Free Summaries)** — official summaries & safety lifecycle basics published by multiple certification labs.
- **ASIL Determination Guides (Free PDFs)** — community spreadsheets & checklists for hazard analysis and risk classification.
- **Automotive SPICE Quick Guides (Free PDFs)** — maturity models for automotive software and firmware development.
- **NHTSA Safety Publications (Free)** — US automotive safety guidelines, electronic subsystem safety notes.
- **UNECE UN R155 / R156 Cybersecurity & OTA (Free PDFs)** — cybersecurity and OTA compliance requirements for automotive ECUs.

---

#### ✅ Automotive Functional Safety Training (Free)

- **MIT OpenCourseWare – Safety Engineering (Free)** — hazard reduction, redundancy, failure modeling.
- **ISO 26262 Crash Courses (YouTube/University Free Lectures)** — lecture series walking through safety cases and safety goals.
- **Texas Instruments Functional Safety Training (Free)** — automotive MCU safety, lockstep cores, ECC, watchdogs, diagnostics.
- **NXP Safety Training (Free)** — SafeAssure training for safety-certified microcontrollers & automotive design.

---

#### ✅ Safety-Certified MCU / SoC References (Free Docs)

- **TI Hercules MCUs (Free Safety Manuals)** — lockstep ARM cores, ECC, diagnostics, BIST, safety app notes.
- **Infineon AURIX Safety Docs (Free)** — automotive-grade MCUs with safety architecture whitepapers.
- **NXP S32 Safety Guide (Free)** — safety mechanisms, fault responses, ASIL decomposition examples.
- **Renesas RH850 Safety Pack (Free)** — safety features, memory protection, watchdog design.

---

#### ✅ Automotive ECU Reference Designs & App Notes (Free)

- **TI / Infineon / NXP Automotive Reference Designs (Free PDFs)** — BMS, motor control, ADAS sensors, power rails, EMI.
- **ST Automotive App Notes (Free)** — CAN-FD, LIN, FlexRay, diagnostics, high-voltage drivers.
- **Microchip Automotive CAN/LIN Stacks (Free)** — application notes and driver examples.

---

#### ✅ Open-Source Automotive Stacks

- **CANopenNode (Free/Open)** — https://github.com/CANopenNode/CANopenNode  
  CANopen stack used in automotive and industrial ECUs.

- **SocketCAN (Free/Open)** — https://github.com/linux-can/can-utils  
  Native Linux CAN bus drivers, logging, traffic replay, ECU diagnostics.

- **OpenBLT (Free/Open)** — https://www.feaser.com  
  Bootloader with automotive-grade CAN, UART, TCP/IP update capabilities.

- **FreeRTOS & SafeRTOS Docs (Free)** — free documentation for safety-related Cortex-M systems.

- **AUTOSAR Open-Source Components (Community)** — limited open tooling and config generators for education/research.

---

#### ✅ Diagnostic & Automotive Tools (Free/Open)

- **UDS / ISO 14229 Open Repos (Free/Open)** — GitHub projects implementing diagnostic protocols for ECUs.
- **OBD-II PID Libraries (Free/Open)** — used in vehicle monitoring and telematics.
- **SavvyCAN (Free/Open)** — https://github.com/collin80/SavvyCAN  
  CAN traffic logger, analyzer, DBC import for vehicle networks.

- **Cantact / CANtact Pro Firmware (Free/Open)** — low-cost CAN interfaces for testing automotive networks.

- **cangaroo / can-utils (Free/Open)** — Linux CAN utilities for replay/testing.

---

#### ✅ Safety Analysis & Verification (Free/Open)

- **OpenFTA (Free/Open)** — https://www.openfta.com  
  Fault Tree Analysis for identifying safety failures and root causes.

- **FMEA Templates (Free/Open)** — community spreadsheets for DFMEA, PFMEA with severity/occurrence ratings.

- **Fault Injection Labs (Open Repos)** — GitHub repositories for simulating stuck-at, bit-flip, and transient failures on embedded systems.

- **QEMU for ECU Emulation (Free/Open)** — test bootloaders, diagnostics, secure updates on emulated ARM cores.

---

#### ✅ Automotive Cybersecurity (Free)

- **UN R155 Cybersecurity Docs (Free PDFs)** — official regulations for OEMs and ECU suppliers.
- **ETSI EN 303 645 (Free Spec)** — IoT/automotive cybersecurity baseline requirements.
- **OWASP Automotive Security Guidance (Free)** — threat modeling, ECU attack surface, secure boot.

---

#### ✅ Compliance Checklists (Free)

- ISO 26262 Safety Case template (community shared)
- ASIL determination spreadsheet
- DFMEA / PFMEA spreadsheets
- Safety Manual template
- Safety requirements traceability matrix

---

### 36. Medical / IEC 60601 / FDA / Pharma Device Compliance (Free / Public Resources)

#### ✅ Medical Safety & Electrical Standards (Free Summaries / Guides)

- **IEC 60601 Overview Guides (Free PDFs)** — public summaries from certification bodies on electrical safety, leakage currents, insulation, creepage, touch current.
- **IEC 62304 Software Lifecycle (Free Overviews)** — medical software development lifecycle, risk control, documentation requirements.
- **IEC 61010 Public Summaries (Free)** — laboratory and measurement equipment safety fundamentals.
- **AAMI / UL Quick Guides (Free)** — widely shared summaries for compliance basics in medical devices.

---

#### ✅ FDA & Regulatory Guidance (Free Official Docs)

- **FDA Medical Device Guidance (Free)** — https://www.fda.gov/medical-devices  
  510(k) submissions, quality systems (QSR), essential performance, cybersecurity, risk files, software validation.
- **FDA Predicates & 510(k) Database (Free)** — search device predicates and learn from approved submissions.
- **FDA Design Controls Handbook (Free PDFs)** — requirements for verification, validation, traceability & documentation.
- **FDA Human Factors Guidance (Free)** — usability engineering and validation guidelines.
- **FDA Cybersecurity Guidance (Free)** — secure boot, authentication, patching, vulnerability disclosure.

---

#### ✅ Medical Quality & Risk Management

- **ISO 14971 Risk Management (Free Summaries)** — hazard identification, risk control, benefit-risk analysis, residual risk.
- **FMEA Templates (Free/Open)** — DFMEA/System-FMEA sheets tailored for medical devices.
- **Fault Tree Analysis Tools (Free/Open)** — OpenFTA for identifying root causes in medical systems.
- **Failure Reporting Databases (Free)** — MAUDE (FDA) for real-world device failure reports and lessons.

---

#### ✅ Electrical & EMC for Medical Devices

- **Rohde & Schwarz Medical EMC Guides (Free)** — pre-compliance testing for medical standards.
- **Keysight Medical EMC Tutorials (Free)** — EMI/EMC design tips, shielding, isolation, filtering.
- **3rd-Party Lab “Pre-Compliance Checklists” (Free PDFs)** — LISN setup, radiated immunity, ESD, conducted emissions.

---

#### ✅ Medical Software & Firmware Validation (Free/Open)

- **Open-Source IEC 62304 Checklists** — software requirements, traceability, test reports.
- **Robot Framework (Free/Open)** — automate V&V testing for medical UI, Bluetooth, data logging.
- **PyTest + USB/Serial/HIL scripts (Free/Open)** — validation of medical embedded firmware in simulated conditions.
- **Open-Source Doxygen + Sphinx setups** — trace software requirements to implementation & tests.

---

#### ✅ Cybersecurity for Medical Devices (Free)

- **UL 2900 Public Summaries (Free)** — cybersecurity requirements for connected medical systems.
- **NIST Cybersecurity for IoT (Free)** — secure boot, crypto, key management for healthcare.
- **OWASP IoT Top 10 (Free/Open)** — foundational vulnerability reference for medical device design.
- **OpenTitan & TrustedFirmware-M (Free/Open)** — secure boot chain for medical wearables & patient data security.

---

#### ✅ Documentation & Quality Systems (Free Access)

- **ISO 13485 Guidance Documents (Free Summaries)** — quality management system for medical devices.
- **QMS Templates (Free Community)** — SOPs, CAPA, change control, manufacturing checklists.
- **Device Master Record / History Record Templates (Free)** — documentation structure for FDA submissions.

---

#### ✅ Human Factors, Clinical & Usability (Free)

- **FDA Human Factors Engineering Guidance (Free)** — user studies, UI errors, validation, labeling requirements.
- **NIH & ISO Public Usability Guides (Free)** — clinical handling and risk reduction references.
- **Free sample usability test protocols** — used in low-risk wearable medical devices.

---

#### ✅ Useful Free Databases & Sandboxes

- **FDA 510(k) Database (Free)** — compare similar approved products.
- **Drugs & Devices Adverse Event Databases (Free)** — failure trends, recalls, safety bulletins.
- **QEMU + Medical Device Firmware Emulation (Free)** — emulate firmware for cybersecurity testing.

---

### 37. Cybersecurity Certification (PSA Certified, ETSI EN 303 645, UL 2900, Common Criteria)

#### ✅ Consumer & IoT Cybersecurity Standards (Free / Public Docs)

- **ETSI EN 303 645 (Free Spec)** — https://www.etsi.org  
  The global baseline for IoT product security: passwords, secure update, crypto, data protection, lifecycle security.

- **ETSI TS 103 701 (Free Spec)** — vulnerability disclosure policy requirements for IoT/CE products.

- **OWASP IoT Top 10 (Free/Open)** — https://owasp.org/www-project-internet-of-things  
  Top IoT vulnerabilities, secure design guidance, firmware testing and checklists.

- **IoT Security Foundation Best Practices (Free)** — https://iotsecurityfoundation.org  
  Free guidance for secure design, secure provisioning, crypto, secure update, compliance checklists.

---

#### ✅ PSA Certified (Arm Platform Security Architecture)

- **PSA Certification Framework (Free Docs)** — https://www.psacertified.org  
  Open security model for MCUs and IoT SoCs—secure boot, attestation, crypto, isolation.

- **TrustedFirmware-M (Free/Open)** — https://www.trustedfirmware.org  
  Reference implementation used to meet PSA security objectives on Cortex-M.

- **PSA Crypto API (Free/Open)** — unified crypto API for MCUs, supported by Arm & silicon vendors.

- **PSA Attestation Samples (Free)** — MCU examples showing signed boot, attestation tokens and secure services.

---

#### ✅ UL 2900 – Cybersecurity Standard (Free Public Summaries)

- **UL 2900-1 Public Overview (Free)** — software and network cybersecurity testing requirements.

- **UL 2900-2 (Medical / Industrial)** — free summary PDFs outlining penetration testing, crypto strength, fuzzing, robustness.

- **UL Secure Components Database (Free)** — search certifiable modules, Wi-Fi, BLE, secure MCUs.

---

#### ✅ Common Criteria (CC) – Evaluation Assurance

- **Common Criteria Portal (Free)** — https://www.commoncriteriaportal.org  
  Public security targets, certification reports for secure MCUs, TPM, secure elements, smartcards.

- **Security Target Templates (Free)** — community documents to write device security claims.

- **Open-Source Reference Targets (GitHub)** — examples for secure boot, attestation, key management.

- **EAL1/EAL2 Guidance (Free Docs)** — how to build low-level CC submissions for IoT products.

---

#### ✅ Firmware Security Testing & Hardening (Free / Open)

- **Ghidra (Free/Open)** — https://ghidra-sre.org  
  Reverse-engineering, binary analysis, symbol recovery, secure coding audits.

- **Binwalk (Free/Open)** — https://github.com/ReFirmLabs/binwalk  
  Firmware unpacking, signature detection, crypto fingerprinting.

- **QEMU Emulation (Free/Open)** — emulate Cortex-M or embedded Linux to run dynamic security analysis.

- **Firmadyne / Firmwalker (Open)** — extract config, secrets, hardcoded keys from embedded Linux images.

- **OpenSCAP (Free/Open)** — vulnerability scanning and security compliance checks for embedded Linux.

- **OpenVAS / Greenbone (Free/Open)** — network vulnerability testing for gateways and IoT appliances.

---

#### ✅ Secure Boot & Crypto Compliance (Free / Open)

- **MCUboot (Free/Open)** — https://mcuboot.com  
  Secure firmware signing, encryption, rollback protection. Fits PSA / ETSI update requirements.

- **OpenTitan (Free/Open)** — https://opentitan.org  
  Hardware root-of-trust: secure boot chain, key ladder, lifecycle states.

- **mbedTLS / WolfSSL (Free/Open)** — embedded TLS 1.3, secure key storage, X.509, hardware acceleration.

- **libOQS (Free/Open)** — https://openquantumsafe.org  
  Post-quantum crypto for future-proof secure boot & updates.

- **Trusted Firmware-M (Free/Open)** — PSA-certified secure services on Cortex-M (crypto, attestation, secure partitions).

---

#### ✅ Vulnerability Disclosure & Threat Modeling (Free)

- **MITRE ATT&CK for ICS (Free)** — adversary techniques targeting OT/embedded systems.

- **NVD/CVE Databases (Free)** — check vulnerabilities in OS, libraries, Wi-Fi/BLE stacks.

- **STRIDE Threat Modeling (Free)** — templates to model spoofing, tampering, info disclosure, DoS, elevation-of-privilege.

- **Microsoft Threat Modeling Tool (Free)** — model trust boundaries, data flows, assets in IoT devices.

---

#### ✅ Secure Update & SBOM (Free Tools)

- **Uptane (Free/Open)** — secure OTA system for automotive/IoT, metadata-based rollback and key protection.

- **in-toto (Free/Open)** — supply-chain security and signed artifacts.

- **Syft / Grype (Free/Open)** — generate SBOMs and scan firmware dependencies for CVEs.

- **Sigstore (Free/Open)** — cryptographic signing of firmware/container images for secure update pipelines.

---

### 38. Functional Safety Test Tools / SIL / PLC Safety (Free / Open-Source)

#### ✅ Functional Safety Standards (Free Summaries / Guides)

- **IEC 61508 Quick Guides (Free PDFs)** — safety lifecycle for industrial control, PLCs, sensors and actuators.
- **SIL Determination Spreadsheets (Free Community Templates)** — SIL 1–4 risk scoring, PFH/PFD calculations.
- **EN ISO 13849-1 Public Summaries** — machinery safety, PL rating, MTTFd & DCavg calculation rules.
- **ISA / TÜV Safety Checklists (Free)** — safety architecture, redundancy, diagnostics, fault handling.

---

#### ✅ Soft PLC & Safety PLC Simulators (Free/Open)

- **OpenPLC (Free/Open-Source)** — https://www.openplcproject.com  
  Full IEC 61131-3 runtime supporting ladder, structured text, function blocks. Run virtual PLCs for safety logic testing.

- **PLC Ladder Simulator (Free)** — educational tool for learning basic ladder safety logic.

- **CODESYS Free Training Version** — limited free version used to test PLC logic, MODBUS, OPC-UA offline.

- **LOGO! / Siemens Demo Tools (Free)** — basic safety logic training, virtual I/Os.

---

#### ✅ Fault Injection & Reliability Tools (Free/Open)

- **OpenFTA (Free/Open)** — https://www.openfta.com  
  Fault tree analysis for identifying single-point faults, latent conditions and common cause failures.

- **FTA / FMEA Open Templates** — community spreadsheets for PFH/PFD calculations, diagnostic coverage.

- **MINIX/QEMU Fault Injection Labs (Free/Open)** — inject memory corruption, timing jitter, watchdog trips.

- **Renode (Free/Open)** — https://renode.io  
  Emulate multi-SoC systems to test firmware safety under fault conditions, message loss, bus failures.

---

#### ✅ Industrial Protocol Safety (Free/Open)

- **OPC-UA Safety Profiles (Free Docs)** — public specifications for safe field-level communication.

- **Safety over EtherCAT (FSoE) – Public Whitepapers** — architecture and principles (actual standard not open).

- **Safety Fieldbus Whitepapers (Free)** — PROFIsafe, CIP Safety conceptual docs from vendors.

- **TSN / Real-Time Ethernet Open Repos** — test determinism & recovery in harsh industrial networks.

---

- **Conpot (Free/Open)** — simulate PLC devices for cybersecurity & resilience testing.

- **QModMaster / ModRSsim2 (Free)** — simulate safe communication / watchdog behavior in Modbus.

---

#### ✅ Safety-Certified MCU Reference Material (Free)

- **TI Hercules Safety App Notes (Free PDFs)** — lockstep CPU, ECC, PBIST, LBIST, watchdogs, diagnostic libraries.

- **NXP S32 Safety Manual (Free)** — fault handling, ASIL decomposition, runtime self-test.

- **Infineon AURIX Safety Docs (Free)** — multi-core lockstep, safety watchdogs, HSM, crypto accelerators.

- **Renesas RH850 Safety Pack (Free)** — safety mechanisms and diagnostic features.

---

#### ✅ SIL, MTTFd, PFH Calculation Tools (Free)

- **MTTFd Online Calculators (Free Web Tools)** — compute reliability for sensors, relays, contactors, e-stops.

- **PFD/PFH Excel Sheets (Community Free)** — measure residual risk based on diagnostics and test intervals.

- **Reliability Block Diagram Tools (Free/Open)** — online RBD editors to model redundancies and fault tolerance.

---

#### ✅ HIL & Safety Testing (Free/Open)

- **OpenHTF (Google) (Free/Open)** — production test automation for boards, sensors, safety relays and interlocks.

- **PyVISA + SCPI + pytest (Free/Open)** — automate safety tests with oscilloscopes, power supplies, loads.

- **QEMU + fault injection (Free/Open)** — emulate MCU behavior under watchdog, reset, BOD, CRC failures.

- **Renode + Zephyr + CANopen safety** — simulate multi-node safety systems.

---

#### ✅ Documentation & Certification Support (Free)

- **Safety Case Templates (Community)** — structure safety goals, hazards, mitigations, test evidence.

- **Traceability Matrices (Free Sheets)** — map safety requirements → design → code → tests.

- **Safe Software Update Checklists (Free)** — redundancy, rollback, signature verification.

- **CE & EU Machinery Directive Quick Guides (Free)** — documentation required for machine safety.

---

### 39. Automotive Diagnostic Tools & Telematics (Free / Open-Source / Free-Tier)

#### ✅ Automotive Diagnostic Stacks (Free/Open)

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

---

#### ✅ CAN, LIN, FlexRay Tools (Free/Open)

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

---

#### ✅ GPS / GNSS / Telemetry Tools (Free/Open)

- **gpsd (Free/Open)** — https://gpsd.gitlab.io/gpsd  
  Collect GNSS data and feed it to telematics systems. Supports USB GPS modules, NMEA, RTK modules.

- **Traccar (Free/Open)** — https://www.traccar.org  
  Self-hosted telematics server with dashboards, geofencing, alerts, multiple protocol/device support.

- **OwnTracks (Free/Open)** — https://owntracks.org  
  MQTT-based location tracking and telematics reporting platform.

- **OpenStreetMap (Free/Open)** — https://www.openstreetmap.org  
  Open mapping data for routing, geofencing, fleet visualizations.

---

#### ✅ Fleet / Telematics Platforms (Free-Tier / Open)

- **ThingsBoard Community (Free/Open)** — https://thingsboard.io  
  Asset tracking, telemetry dashboards, rules engine, MQTT integrations for vehicle data.

- **Grafana OSS with GPS Plugins (Free/Open)** — https://grafana.com  
  Geospatial dashboards for telematics.

- **Traccar + InfluxDB + Grafana (Open Stack)** — popular free self-host setup for vehicle fleets.

---

#### ✅ Vehicle Reverse Engineering (Free/Open)

- **Kayak (Free/Open)** — https://github.com/dschanoeh/Kayak  
  GUI CAN tool for sniffing, injecting, decoding and DBC editing.

- **CANalyze (Free/Open)** — https://github.com/jonathankang/canalyze  
  Python-based CAN signal reverse-engineering toolkit.

- **CANard (Free/Open)** — https://github.com/ericevenchick/canard  
  Script CAN frames, fuzz ECUs, explore diagnostics.

- **PyOBD / OBD Auto Doctor (Free Editions)** — basic OBD-II analysis.

---

#### ✅ Vehicle-to-Everything (V2X) / DSRC / C-V2X (Free Resources)

- **OpenC2X (Free/Open)** — https://github.com/OpenC2X/openc2x  
  Open-source V2X stack for DSRC and ETSI ITS-G5 research.

- **Vanetza (Free/Open)** — https://github.com/riebl/vanetza  
  ETSI ITS-G5 communication stack used in autonomous car research.

- **Open Source C-V2X Repos (Free)** — reference implementations from academia for V2X PHY/MAC.

---

#### ✅ Telematics Hardware / Firmware (Free/Open)

- **OpenXC Vehicle Interface (Free/Open)** — https://github.com/openxc  
  Open hardware for capturing CAN data over USB/Bluetooth and exporting normalized metrics.

- **Arduino OBD-II Libraries (Free/Open)** — ELM327 + UART stacks for DIY telematics.

- **Raspberry Pi CAN HAT Tools (Free/Open)** — SocketCAN enabled, ready-to-use telematics edge node.

- **TTGO/ESP32 CAN Modules (Open Firmware Projects)** — multiple community projects for BLE+CAN telemetry.

---

#### ✅ Cloud Integrations for Telematics (Free-Tier)

- **AWS IoT Core Free Tier** — MQTT ingestion, rules, dynamodb/logging.
- **GCP Pub/Sub & BI Free Tier** — pipeline for telematics data.
- **Azure IoT Hub Free Tier** — registry, commands, digital twins.
- **Balena (Free Tier)** — remote OTA for in-vehicle SBC gateway.

---

#### ✅ Bonus — Automotive Dashboards (Free/Open)

- **Grafana Map Panels (Free/Open)** — live GPS, fleet, route, idling analysis.
- **InfluxDB + Chronograf (Free)** — telematics metrics, speed, fuel usage.
- **OpenStreetMap Tile Servers (Free/Open)** — self-hostable maps for fleets.

---

## 40. Open Hardware Security & Fault Injection Benches  
_Free and open-source tools, projects, and research frameworks for hardware security testing, side-channel analysis, and physical attack experimentation on embedded systems._

---

#### ✅ Hardware Security Research Frameworks (Free / Open-Source)

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

---

#### ✅ Side-Channel Analysis (SCA) Tools (Free/Open)

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

---

#### ✅ Fault Injection & Glitching (Free/Open)

- **ChipWhisperer Glitch Module (Free/Open)** — included in ChipWhisperer hardware.  
  Used to perform voltage, clock, and EM glitching attacks on MCUs, SoCs, and smartcards.

- **ChipFail (Free/Open)** — https://github.com/ChipFail/ChipFail  
  Repository of open-source EMFI, laser fault injection, and glitching experiments with reproducible setups.

- **GlitchKit (Free/Open)** — community scripts and firmware for low-cost fault injection using MCUs and GPIO-based timing control.

- **uGlitcher (Free/Open)** — https://github.com/uglich/uGlitcher  
  Python-based framework for glitching using Raspberry Pi or STM32 hardware.

- **GlitchThis (Free/Open)** — https://github.com/AlessandroAU/GlitchThis  
  Minimal open-source power glitching and trigger control system.

---

#### ✅ Reverse Engineering & Debug Tools (Free/Open)

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

---

#### ✅ Secure Element & TPM Research Tools (Free/Open)

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

---

#### ✅ Hardware Forensics & Board Analysis Tools (Free/Open)

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

---

#### ✅ Hardware Security Education & Labs (Free/Open)

- **HardwareSecurity.training (Free)** — https://hardwaresecurity.training  
  Collection of open labs and resources for hardware hacking, side-channel, and tamper analysis.

- **Hackaday.io Hardware Security Projects (Free)** — https://hackaday.io/projects  
  DIY open projects for EMFI, glitching, secure element programming, board decapping.

- **NYU OSIRIS Lab Hardware Labs (Free)** — https://osiris.cyber.nyu.edu  
  Academic lab materials for fault injection, chip analysis, and side-channel attacks.

- **Cyber-Security Evaluation Lab (Free/Open)** — https://www.ciselab.com (academic repositories)  
  Reference frameworks for hardware trust and countermeasure validation.

---

#### ✅ Bonus — Post-Quantum & Hardware Crypto Research (Free/Open)

- **libOQS (Free/Open)** — https://openquantumsafe.org  
  Open quantum-safe crypto library for benchmarking hardware implementations.

- **PQShield Whitepapers (Free)** — https://pqshield.com/resources  
  Open educational resources on post-quantum cryptography and hardware secure elements.

- **OpenCryptoHW (Free/Open)** — https://github.com/OpenCryptoProject  
  Collection of open-source hardware cryptography IP cores for FPGA/ASIC evaluation.

---

## 41. Post-Silicon Validation & Chip Debug Tools  
_Free / open-source utilities for validating SoCs, MCUs, and processors after fabrication — covering JTAG/SWD, firmware loading, trace, boundary-scan, fault isolation and silicon bring-up._

---

### ✅ Low-Level Debug & Bring-Up Tools (Free/Open)

- **OpenOCD (Free/Open-Source)** — https://openocd.org  
  Universal JTAG/SWD debugging for ARM, RISC-V, ESP32 and custom SoCs. Supports GDB, boundary-scan, flash programming and secure debug workflows.

- **PyOCD (Free/Open)** — https://github.com/pyocd/pyOCD  
  JTAG/SWD debug for Cortex-M. Includes flash loader, memory viewer, RTOS thread view and scripting in Python.

- **OpenTitan ‘Silicon Creator’ Tools (Free/Open)** — https://opentitan.org  
  Secure boot ROM bring-up, post-silicon self-test, debug unlock flows, life-cycle states.

- **ESP-IDF Open Debug Stack (Free/Open)** — https://github.com/espressif/esp-idf  
  Post-silicon validation with OpenOCD + GDB for ESP32 family; JTAG, boundary-scan and trace features.

- **J-Link OpenOCD Interface (Free/Open)** — community drivers enabling J-LINK hardware with open debug stacks.

---

### ✅ JTAG, Scan Chain & Boundary-Scan (Free/Open)

- **UrJTAG (Free/Open-Source)** — http://urjtag.org  
  Boundary-scan testing, flash programming, BSDL parsing — used for board-level post-silicon validation.

- **Jtagulator (Open Hardware + Free Tooling)** — https://github.com/grandideastudio/jtagulator  
  Automatic JTAG/SWD/UART pin-out detection for unknown SoCs. Essential for silicon bring-up and reverse engineering.

- **JTAGenum (Free/Open)** — https://github.com/cyphunk/JTAGenum  
  Detect JTAG signals on unknown PCBs to enable debug access.

- **BSV / Open Boundary-SCAN Viewers (Free)** — several GitHub projects letting you check BSDL nets for post-silicon faults.

---

### ✅ Logic Analyzers & Trace (Free/Open)

- **sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Open logic analyzer suite with 100+ protocol decoders. Used for validating SPI/I2C/UART timing, busses and bring-up.

- **Saleae Logic Open SDK (Free APIs)** — APIs for automated validation traces and signal inspection in manufacturing.

- **LAP-C / FX2LA open firmware (Free/Open)** — cheap FX2-based logic analyzers with open firmware + sigrok support.

- **OpenTrace (Free/Open)** — open trace-capture tools for proprietary debug interfaces (community maintained).

---

### ✅ Silicon-Level Fault Isolation (Free/Open)

- **ChipWhisperer Analyzer (Free/Open)** — https://chipwhisperer.io  
  Useful during post-silicon security validation to detect timing glitches, power faults, or side-channel leakage.

- **GlitchKit / ChipFail (Free/Open)** — open hardware fault-injection methods to test glitch resistance of SoCs & secure boot.

- **Renode (Free/Open)** — https://renode.io  
  Co-simulate SoC peripherals + firmware to reproduce silicon bugs and compare against real hardware logs.

- **QEMU + Plugins (Free/Open)** — emulate ARM/MIPS/RISC-V for differential testing vs real silicon behavior.

---

### ✅ RISC-V / Open Silicon Validation (Free/Open)

- **RISC-V DV (Free/Open)** — https://github.com/google/riscv-dv  
  Random instruction generator + compliance suite for post-silicon CPU verification.

- **OpenHW Group CORE-V Verification (Free/Open)** — https://github.com/openhwgroup  
  Full UVM-based verification environment for open RISC-V cores.

- **OpenTitan DV (Free/Open)** — https://github.com/lowRISC/opentitan  
  Industrial-grade verification framework: UVM, testbenches, assertions, coverage dashboards.

- **riscv-compliance (Free/Open)** — official compliance suite for validating RISC-V ISA behavior on new silicon.

---

### ✅ FPGA SoC Bring-Up (Free/Open)

- **LiteX (Free/Open)** — https://github.com/enjoy-digital/litex  
  Build FPGA SoCs + debug buses, logic analyzers, UART prints — excellent for early silicon prototyping.

- **Migen + LiteScope (Free/Open)** — embedded logic analyzer for on-chip waveform capture.

- **OpenFPGA Tools (Free/Open)** — SymbiFlow, Verilator, GHDL for validating soft-cores before tape-out.

---

### ✅ Board-Level Post-Silicon Test (Free/Open)

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Production test automation for boards: power-on tests, UART/JTAG scriptable bring-up, functional validation.

- **pytest + PyVISA + SCPI (Free/Open)** — automation for oscilloscopes, PSUs, SMUs — log waveforms, power tests, startup timing.

- **Open Manufacturing Bench Repos (Free)** — community Python fixtures to automate flashing, current measurement, thermal tests.

---

### ✅ Manufacturing & Yield Debug (Free/Open)

- **InfluxDB OSS + Grafana OSS (Free)** — capture yield metrics, flash failures, boot failures, calibration logs during silicon bring-up.

- **Elasticsearch + Kibana (Free/Open)** — log thousands of board results, find systematic silicon or solder-joint issues.

- **Open Serial Loggers (Free)** — automatic logging of boot traces, crashes, panic dumps for lot screening.

---

### ✅ Datasheet & Model Verification (Free)

- **SVUnit (Free/Open)** — https://github.com/svunit/svunit  
  SystemVerilog unit testing for HDL — validate RTL fixes discovered during post-silicon bring-up.

- **Verilator (Free/Open)** — https://www.veripool.org/verilator  
  Fast SystemVerilog simulator to reproduce silicon bugs offline.

- **GHDL (Free/Open)** — https://github.com/ghdl/ghdl  
  VHDL simulator for verifying behavioral and gate-level issues.

---

## 42. Open-Source Robotics / AGV / Warehouse Automation Stacks  
_Free and open-source software frameworks for autonomous robots, industrial AGVs/AMRs, warehouse automation, motion planning, perception and control._

---

### ✅ Full Robotics Frameworks (Free / Open-Source)

- **ROS (Robot Operating System) (Free/Open)** — https://www.ros.org  
  Global standard robotics middleware: navigation, SLAM, mapping, drivers, hardware abstraction. Huge ecosystem.

- **ROS 2 (Free/Open)** — https://docs.ros.org/en/rolling  
  Industrial-grade real-time ROS using DDS. Used for AGVs, collaborative robots, factory automation.

- **ROS-Industrial (Free/Open)** — https://rosindustrial.org  
  Industrial extensions: real robot drivers, motion planners, vision, conveyor integration, safety.

- **YARP (Free/Open)** — https://www.yarp.it  
  Modular robotics framework for humanoids, manipulators, service robots.

- **Player/Stage/Gazebo Stack (Free/Open)** — legacy but still used in education and research.

---

### ✅ Motion Planning Libraries (Free/Open)

- **MoveIt (Free/Open)** — https://moveit.ros.org  
  Widely used motion-planning framework: kinematics, collision avoidance, trajectory generation, robot arms & manipulators.

- **OMPL – Open Motion Planning Library (Free/Open)** — https://ompl.kavrakilab.org  
  Sampling-based motion planning library used in MoveIt and custom AGV navigation.

- **CHOMP / STOMP / TrajOpt (Free/Open)** — advanced motion planners for industrial robots.

- **Tesseract (Free/Open)** — https://github.com/tesseract-robotics/tesseract  
  Industrial motion planning and environment modeling used in automation.

---

### ✅ SLAM, Perception & Localization (Free/Open)

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

---

### ✅ Navigation & AGV Stacks (Free/Open)

- **ROS Navigation Stack (Free/Open)** — https://wiki.ros.org/navigation  
  Global planning, local planning, obstacle avoidance, costmaps for warehouse AGVs.

- **ROS2 Navigation2 (Free/Open)** — https://navigation.ros.org  
  Next-gen real-time navigation — AMRs, multi-robot dispatching.

- **Open-RMF (Open Robotics Fleet Management) (Free/Open)** — https://openrmf.org  
  Fleet orchestration for multiple AMRs/AGVs, traffic control, elevators, doors, charging, scheduling.

- **MRPT (Free/Open)** — https://www.mrpt.org  
  Perception, SLAM, localization, math blocks — C++ robotics toolkit.

- **Mobile Robot Programming Toolkit (MRPT) Datasets (Free)** — SLAM and localization benchmark data.

---

### ✅ Low-Level Control, Kinematics, Dynamics

- **Orocos (RTT) (Free/Open)** — https://www.orocos.org  
  Real-time control framework for industrial manipulators and automation.

- **Drake (MIT) (Free/Open)** — https://drake.mit.edu  
  Dynamics, control, trajectory optimization for robotic systems.

- **Pinocchio (Free/Open)** — https://github.com/stack-of-tasks/pinocchio  
  Fast kinematics and dynamics library used in humanoids and industrial arms.

- **Rigid Body Dynamics Library (RBDL) (Free/Open)** — https://rbdl.readthedocs.io  
  Efficient rigid-body dynamics for simulation and control.

---

### ✅ Vision & Object Detection (Free/Open)

- **OpenCV (Free/Open)** — https://opencv.org  
  Full computer vision toolkit, used for barcode readers, object pick-and-place, conveyors, safety zones.

- **Darknet / YOLO (Free/Open)** — https://github.com/AlexeyAB/darknet  
  Real-time object detection for robots, pickers, palletizers.

- **OpenPTrack (Free/Open)** — https://openptrack.org  
  Multi-camera people tracking, used in warehouse and HMI robotics.

---

### ✅ Simulators for Robot Labs (Free/Open)

- **Gazebo / Ignition Robotics (Free/Open)** — https://gazebosim.org  
  3D physics simulator with sensors, conveyors, forklifts, pallet movers, machine vision.

- **Webots (Free/Open)** — https://cyberbotics.com  
  Virtual factory floors, manipulators, conveyor belts, AGVs.

- **AirSim (Free/Open)** — https://github.com/microsoft/AirSim  
  Drones & ground vehicles with depth cameras, IMU, GPS.

- **CoppeliaSim (Free Student/Open)** — https://www.coppeliarobotics.com  
  Pick-and-place cells, robotic arms, conveyors, PLC links.

---

### ✅ Multi-Robot Coordination / Warehouse Automation

- **Open-RMF Dispatcher (Free/Open)** — https://openrmf.org  
  Orchestration for dozens of AMRs/AGVs, traffic control, shared resources, elevators and pathways.

- **Fleet Management Plugins for ROS2 (Free/Open)** — GitHub packages enabling missions, dispatching, charging logic.

- **Rapyuta.io Free Tier (Cloud Robotics)** — https://rapyuta.io  
  Cloud-based fleet, teleop, logging, route planning (free developer tier).

---

### ✅ AGV Hardware / Firmware (Free/Open)

- **ROS-Control (Free/Open)** — motion control and actuator drivers for mobile robots.

- **ROS Serial / Micro-ROS (Free/Open)** — https://micro.ros.org  
  Use STM32/ESP32/PIC for low-level control communicating with ROS2 over DDS.

- **Open Motor Controller Repos** — BLDC/FOC/H-bridge drivers for AMRs (VESC, ODrive are open software stacks).

- **Open-Source LIDAR Stacks** — RPLIDAR, Slamtec, YDLIDAR ROS drivers.

---

### ✅ Mapping / Geofencing / Dispatch Dashboards

- **RViz & RViz2 (Free/Open)** — ROS visualization of map, trajectories, LiDAR, obstacles.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Robotics data visualization: logs, LIDAR, IMU, CAN, maps — browser dashboards.

- **Grafana OSS + InfluxDB (Free/Open)** — live monitoring of fleet health, battery, uptime, missions.

---

### ✅ Robotics Learning & Academic Repos (Free/Open)

- **Modern Robotics (Free Online Course)** — kinematics, motion planning, dynamics.
- **MIT OCW Robotics (Free)** — perception, control, SLAM.
- **ETH Zurich Autonomous Systems Labs (Free Papers)** — advanced AMR/AGV work.
- **OpenSLAM Paper Library (Free)** — collection of SLAM algorithms & datasets.

---

## 43. Satellite & Space-Grade Hardware Tools  
_Free/open tools for space avionics, satellite communications, RF link planning, space-grade electronics design, radiation testing, orbital mechanics and mission simulation._

---

### ✅ Satellite Mission Design & Orbital Mechanics (Free/Open)

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

---

### ✅ Ground Stations & SDR for SatCom (Free/Open)

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

---

### ✅ Space-Grade Electronics, Radiation & Reliability (Free/Public)

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

---

### ✅ Satellite SDR Demodulators (Free/Open)

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio blocks for decoding dozens of CubeSat and amateur satellite telemetry formats.

- **DireWolf (Free/Open)** — https://github.com/wb2osz/direwolf  
  AX.25, APRS, telemetry decoding — used by amateur satellites.

- **OpenLST Modem (Free/Open)** — open-source robust satcom modem (FSK/GFSK) with flight heritage.

- **CSP + FreeRTOS Satellite Stacks (Open)** — real flight-ready nanosat firmware examples.

---

### ✅ Flight Software, GNC & Satellite OS (Free/Open)

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

---

### ✅ Satellite Simulation & Digital Twins (Free/Open)

- **NOS Engine (Free/Open)** — open network-layer simulator for flight software testing.

- **GMAT Mission Simulation (Free/Open)** — full dynamics modeling for thrusters, staging, attitude control.

- **POLYSAT Sims (Free)** — open academic tools for small satellite bus simulation.

- **CSP-in-the-loop Simulators (Free/Open)** — simulate CubeSat comms networks and ground station telemetry.

---

### ✅ Thermal, Power & Reliability Tools (Free/Public)

- **Thermal Desktop Free Samples (Docs)** — spacecraft thermal control whitepapers.

- **NASA Thermal Control Handbook (Free PDFs)** — radiator, heater, coating models.

- **CubeSat Power Budget Tools (Free Sheets)** — community spreadsheets for solar, battery, eclipse time.

- **ESA Propulsion & Power Handbooks (Free)** — thruster sizing, reaction wheels, momentum dumping.

---

### ✅ Amateur Radio & Education (Free/Open)

- **AMSAT Resources (Free/Open)** — https://www.amsat.org  
  Educational satellites, telemetry formats, SDR tutorials.

- **CubeSat Design Spec (Free PDF)** — Cal Poly CubeSat specification for educational missions.

- **SatNOGS Ground Station Hardware (Open Hardware)** — 3D printed rotors, LNA designs, SDR builds.

---

## 43. Satellite & Space-Grade Hardware Tools  
_Free/open tools for space avionics, satellite communications, RF link planning, space-grade electronics design, radiation testing, orbital mechanics and mission simulation._

---

### ✅ Satellite Mission Design & Orbital Mechanics (Free/Open)

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

---

### ✅ Ground Stations & SDR for SatCom (Free/Open)

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

---

### ✅ Space-Grade Electronics, Radiation & Reliability (Free/Public)

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

---

### ✅ Satellite SDR Demodulators (Free/Open)

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio blocks for decoding dozens of CubeSat and amateur satellite telemetry formats.

- **DireWolf (Free/Open)** — https://github.com/wb2osz/direwolf  
  AX.25, APRS, telemetry decoding — used by amateur satellites.

- **OpenLST Modem (Free/Open)** — open-source robust satcom modem (FSK/GFSK) with flight heritage.

- **CSP + FreeRTOS Satellite Stacks (Open)** — real flight-ready nanosat firmware examples.

---

### ✅ Flight Software, GNC & Satellite OS (Free/Open)

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

---

### ✅ Satellite Simulation & Digital Twins (Free/Open)

- **NOS Engine (Free/Open)** — open network-layer simulator for flight software testing.

- **GMAT Mission Simulation (Free/Open)** — full dynamics modeling for thrusters, staging, attitude control.

- **POLYSAT Sims (Free)** — open academic tools for small satellite bus simulation.

- **CSP-in-the-loop Simulators (Free/Open)** — simulate CubeSat comms networks and ground station telemetry.

---

### ✅ Thermal, Power & Reliability Tools (Free/Public)

- **Thermal Desktop Free Samples (Docs)** — spacecraft thermal control whitepapers.

- **NASA Thermal Control Handbook (Free PDFs)** — radiator, heater, coating models.

- **CubeSat Power Budget Tools (Free Sheets)** — community spreadsheets for solar, battery, eclipse time.

- **ESA Propulsion & Power Handbooks (Free)** — thruster sizing, reaction wheels, momentum dumping.

---

### ✅ Amateur Radio & Education (Free/Open)

- **AMSAT Resources (Free/Open)** — https://www.amsat.org  
  Educational satellites, telemetry formats, SDR tutorials.

- **CubeSat Design Spec (Free PDF)** — Cal Poly CubeSat specification for educational missions.

- **SatNOGS Ground Station Hardware (Open Hardware)** — 3D printed rotors, LNA designs, SDR builds.

---

## 44. FPGA / ASIC Open Toolchains  
_Free and open-source EDA flows, HDL tools, soft-core CPUs, simulation, synthesis, place-and-route, verification and post-silicon debug for FPGA & ASIC design._

---

### ✅ Full FPGA Open Toolchains (RTL → Bitstream)

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

---

### ✅ HDL Synthesis & Simulation (Free/Open)

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

---

### ✅ Open Soft-Core CPUs for FPGA & ASIC

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

---

### ✅ Open ASIC Flows (RTL → GDS)

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

---

### ✅ Physical Verification / Layout Tools (Free/Open)

- **Magic VLSI (Free/Open)** — http://opencircuitdesign.com/magic  
  Classic open silicon layout + DRC/LVS — used in real tape-outs.

- **KLayout (Free/Open)** — https://klayout.de  
  GDS viewer/editor with DRC, LVS, scripting.

- **Netgen (Free/Open)** — http://opencircuitdesign.com/netgen  
  LVS comparison between schematic and layout.

- **OpenSTA (Free/Open)** — https://github.com/The-OpenROAD-Project/OpenSTA  
  Static timing analysis for ASIC signoff.

---

### ✅ FPGA SoC Frameworks

- **LiteX (Free/Open)** — https://github.com/enjoy-digital/litex  
  Build FPGA SoCs: CPUs, DDR, Ethernet, PCIe, HDMI, soft peripherals, Wishbone/AXI.

- **Migen (Free/Open)** — Python HDL for building FPGA logic, compatible with LiteX cores.

- **LiteScope (Free/Open)** — embedded logic analyzer for FPGA internal waveforms.

- **Amaranth HDL (Free/Open)** — https://github.com/amaranth-lang/amaranth  
  Python HDL successor to Migen, supports Yosys flows.

---

### ✅ FPGA Debug / Post-Silicon (Free/Open)

- **Sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Works with many USB logic analyzers for FPGA pinwave debugging.

- **OpenFPGAloader (Free/Open)** — flash/program a wide range of FPGAs via USB/JTAG.

- **Open JTAG / FTDI Tools (Free/Open)** — open drivers for programming/debugging over FT2232H.

- **OpenTAP (Free/Open)** — https://github.com/opentap/opentap  
  Automated testing for FPGA/ASIC bring-up and production.

---

### ✅ Educational / Learning Repos

- **FPGA4Student (Free/Open)** — Verilog/VHDL mini-projects, ALU, UART, VGA controllers.

- **nand2tetris (Free/Open)** — build a computer from logic gates to running programs.

- **MIT 6.111 Labs (Free)** — FPGA digital design and signal processing labs.

- **Berkeley EECS RISC-V Classes (Free)** — open lecture notes + labs.

---

## 45. Semiconductor Failure Analysis & Reliability Tools  
_Free / open-source references for failure diagnosis, reliability modeling, thermal analysis, ESD/LU protection, PCB/component aging and silicon defect investigation._

---

### ✅ Failure Analysis Frameworks & Databases (Free/Public)

- **NASA Lessons Learned Database (Free)** — https://llis.nasa.gov  
  Real-world spacecraft and electronics failures, root-cause break-downs, corrective actions.

- **NASA NEPP – Electronics Parts & Packaging Program (Free)** — https://nepp.nasa.gov  
  Failure reports, derating guides, reliability data for COTS parts exposed to radiation, thermal stress and vibration.

- **MIL-HDBK-338 / MIL-HDBK-217 (Free PDFs)**  
  Free military handbooks for reliability predictions, stress models, MTBF calculations.

- **ESA Space Components Docs (Free)** — https://escies.org  
  Failure reports, radiation data, PCB material aging, tin whisker mitigation.

- **JEDEC JESD Guides (Free Public Summaries)** — moisture sensitivity, reflow reliability, ESD/latch-up immunity basics.

---

### ✅ Reliability Calculation Tools (Free/Open)

- **Reliability Block Diagram Tools (Free/Open)** — online RBD editors for modeling redundant systems & single-point failures.

- **Weibull Tool / Weibull++ Community Sheets (Free)** — spreadsheets for lifetime distribution and wear-out analysis.

- **MTBF/MTTF Calculators (Free)** — online tools using MIL-217 or Telcordia factors for ICs, passives, PCB assemblies.

- **PARTSIM / LTspice (Free)** — thermal/electrical stress simulation of MOSFETs, gate drivers, SMPS to predict field failures.

---

### ✅ Thermal, Stress & Aging Analysis (Free/Open)

- **OpenFOAM (Free/Open)** — https://openfoam.org  
  CFD simulation for PCB cooling, heatsinks, airflow inside enclosures, hotspot detection.

- **Thermal Desktop & SINDA/FLUINT (Docs/Samples Free)** — aerospace-grade thermal modeling references (limited free).

- **FEMM (Free/Open)** — https://www.femm.info  
  Magnetic/electrical field modeling for motors, inductors, transformers → thermal stress correlation.

- **FreeCAD + KiCad StepUp (Free/Open)** — PCB + mechanical thermal fit, enclosure interference, hotspot airflow modeling.

- **SimScale Community Edition (Free Tier)** — limited free CFD/thermal simulation for enclosures & PCBs.

---

### ✅ Board-Level Testing & Fault Isolation (Free/Open)

- **sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Capture intermittent faults, bus glitches, marginal signal timing and decoupling failures.

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automated production testing to detect marginal PCBs, cold solder, intermittent connectors.

- **PyVISA + SCPI (Free/Open)** — automate stress/soak testing using power supplies, SMUs, scopes & chambers.

- **Boundary Scan Tools (UrJTAG) (Free/Open)** — http://urjtag.org  
  Detect open BGA balls, shorts, incomplete assembly, trace faults without powered boot.

---

### ✅ PCB Reliability & Material Guides (Free/Public)

- **IPC-2221 / 9592 Public Summaries (Free)** — creepage, clearance, thermal relief, copper weight reliability.

- **NASA Tin Whisker Mitigation Guidelines (Free PDF)** — prevent whisker-related shorts in long-life electronics.

- **UL PCB Flammability & CTI Guides (Free PDFs)** — insulation aging, tracking & high-voltage failures.

- **Thermal Cycling & Vibration Testing Guides (Free)** — from ESA & NASA for PCB fatigue and solder joint cracking.

---

### ✅ ESD, Latch-Up & Transient Protection (Free/Public)

- **ESD Association Public Articles (Free)** — best practices for ESD-safe design & manufacturing.

- **TI/Analog Devices ESD App Notes (Free)** — TVS sizing, IEC 61000-4-2 testing, surge/transient mitigation.

- **Latch-Up Testing Basics (Free PDFs)** — JEDEC summaries for CMOS latch-up screening & design rules.

- **Open EMFI & glitch repos (Free/Open)** — used to detect silicon weak spots / reliability under transient stress.

---

### ✅ Semiconductor Reliability Data (Free/Public)

- **NASA Radiation Test Reports (Free)** — SEE, SEL, SEU results for COTS ICs.

- **ESA Radiation Handbook (Free PDF)** — TID models, shielding, component derating for space electronics.

- **NSIT/OEIS Public Reliability Data (Free)** — failure rate statistics for passives, ICs, connectors.

---

### ✅ Failure Debug & Reverse Engineering (Free/Open)

- **Binwalk (Free/Open)** — extract firmware dumps to study corrupted NVM or flash retention issues.

- **OpenScanLab (Free/Open)** — community tools for board inspection, X-ray dataset references.

- **OpenBoardView (Free/Open)** — view PCB pad connectivity; helps locate broken traces & via failures.

- **Ghidra (Free/Open)** — analyze crashes from firmware aging / memory corruption in long-life systems.

---

### ✅ Checklists & Templates (Free)

- FMEA / DFMEA / PFMEA spreadsheets  
- Stress test plan templates (thermal soak, vibration, HALT/HASS)  
- Derating charts for capacitors, MOSFETs, power supplies  
- Burn-in & soak testing logs  
- Failure reporting & corrective action (FRACAS) sheets  

---

## 46. Space-Grade RF & Antenna Design Tools  
_Free / open-source modeling tools, antenna optimizers, RF link calculators, propagation simulators and space-rated RF references for satellite and deep-space missions._

---

### ✅ RF & Antenna Simulation (Free/Open)

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

---

### ✅ RF Link Budget & Propagation Tools (Free)

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Build satellite modems, telemetry decoders, digital downconverters, demodulators.

- **Gpredict (Free/Open)** — https://gpredict.oz9aec.net  
  Satellite tracking with Doppler correction and radio control for uplink/downlink planning.

- **SatNOGS (Free/Open)** — https://satnogs.org  
  Open ground station network with waterfall plots, demodulators and dashboards.

- **SatSim / GPTools (Free/Open)** — open-source link calculators for LEO/MEO/GEO orbits.

- **ITU Propagation Models (Free Docs)** — official models for atmospheric loss, rain fade, ground reflection.

- **FCC / NTIA Free Databases** — satellite and RF spectrum allocations, permissible EIRP levels.

---

### ✅ PCB Antenna Design & Tuning (Free/Open)

- **KiCad RF Tools (Free/Open)** — https://kicad.org  
  Impedance calculators, microstrip/CPW tuning, stack-up design for S-band/L-band PCBs.

- **OpenEMS + KiCad Step Export (Free/Open)** — simulate real PCB geometries for antenna pattern.

- **RFSim99 (Free)** — lightweight Smith-chart matching and filter design (runs in Wine).

- **TX-Line (Free)** — microstrip and CPW calculators for RF traces and controlled impedance.

- **Qucs-S (Free/Open)** — https://ra3xdh.github.io  
  RF circuit simulation with S-parameters, filters, LNAs.

---

### ✅ Space-Grade RF / High-Rel Design (Free/Public)

- **NASA RF Design Guidelines (Free PDFs)** — waveguides, S-band, X-band, Q/V-band links, low-noise amplifiers, radomes, filters.

- **ESA ECSS RF Standards (Free)** — PCB materials, coax selection, PCB stack-up, microstrip radiation constraints.

- **NASA Parts & Materials Radiation Guides (Free)** — multi-layer board aging, contamination, dielectric breakdown.

- **NASA Antenna Handbook (Free PDF)** — link equations, directivity, radome effects, spacecraft mounting.

- **Navy Antenna Handbook (Free)** — military-grade antenna design principles (reflectors, helical, log periodic).

---

### ✅ SDR Tools for Satellite & Deep Space (Free/Open)

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio modules for decoding CubeSat and amateur satellite telemetry.

- **CSP – CubeSat Space Protocol (Free/Open)** — https://github.com/libcsp/libcsp  
  Lightweight IP-like protocol for nanosatellite radios.

- **Direwolf (Free/Open)** — https://github.com/wb2osz/direwolf  
  AX.25 and APRS packet decoding used in amateur sat missions.

- **OpenLST (Free/Open)** — https://github.com/openlst/openlst  
  Robust telemetry radio used on NASA small-sat missions.

---

### ✅ Antenna Optimization & AI-Based Design (Free/Open)

- **PyGMO (Free/Open)** — https://esa.github.io/pygmo2  
  ESA’s evolutionary optimization library — used by researchers for RF antenna shape optimization.

- **OpenAntenna Optimizers (Free/Open)** — GitHub projects coupling NEC2/OpenEMS with genetic algorithms.

- **Meep + Python (Free/Open)** — run sweeps to minimize VSWR, maximize gain, and optimize dielectric patterns.

---

### ✅ Manufacturing & Measurement (Free/Public)

- **NanoVNA + NanoVNA-Saver (Free/Open)** — https://github.com/NanoVNA-Saver/nanovna-saver  
  Open-source VNA software to measure return loss, S11, tuning space-grade patches, feeds and filters.

- **RTL-SDR (Free/Open Firmware)** — low-cost SDR for receiving satellite beacons and telemetry.

- **Orbitron (Free)** — satellite pass prediction and Doppler planning for antenna tracking.

- **Hamlib (Free/Open)** — rig control for rotors and radios, often used with SatNOGS/Gpredict setups.

---

## 47. Open-Source DSP / SDR ASIC Cores  
_Free and open-source digital signal processing blocks, modem cores, FPGA/ASIC IP, and complete software-defined radio pipelines for communications, radar, and wireless PHY development._

---

### ✅ Full SDR PHY Stacks (Free/Open)

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

---

### ✅ Modem & Communication IP Cores (Open-Source)

- **OpenCores DSP & Modem Cores (Free/Open)** — https://opencores.org  
  OFDM, QPSK, QAM, CORDIC, FIR, FFT/IFFT, Viterbi decoders for FPGA/ASIC.

- **Free-Cores Viterbi / Turbo / LDPC IP (Free/Open)** — community IP for forward-error correction PHYs.

- **CSP – CubeSat Space Protocol (Free/Open)** — https://github.com/libcsp/libcsp  
  Space-grade lightweight networking stack.

- **OpenOFDM (Free/Open)** — GitHub projects implementing OFDM PHY in Verilog/VHDL.

- **OpenLTE (Free/Open)** — https://github.com/EURECOM-SW/OpenAirInterface  
  LTE PHY + UE/eNodeB reference designs for FPGAs.

---

### ✅ DSP Engines & Math Accelerators (Open IP)

- **PicoRV32 + DSP Extensions (Free/Open)** — extremely small RISC-V core with multiply–accumulate units.

- **VexRiscv + FPU/DSP Plugins (Free/Open)** — configurable soft-core with SIMD/DSP options.

- **CORDIC Core (Free/Open)** — https://github.com/korayws/Verilog_CORDIC  
  Trigonometric/IP cordic blocks for FPGA signal processing.

- **FIR/IIR Filter IP (Free/Open)** — OpenCores & GitHub repos for parametric digital filters.

- **FFT/IFFT cores (Free/Open)** — multiple Verilog/VHDL implementations for radar, OFDM, audio DSP.

---

### ✅ SDR Front-Ends & RF Gateware (Open)

- **LimeSDR Gateware (Free/Open)** — https://github.com/myriadrf  
  Complete FPGA signal chain for LimeSDR boards; AGC, mixers, DDC/DUC, filters.

- **BladeRF Gateware (Free/Open)** — https://github.com/Nuand/bladeRF  
  FPGA source for RF frontend and streaming.

- **USRP UHD (Free/Open)** — https://github.com/EttusResearch/uhd  
  Open host drivers + FPGA reference designs for Ettus USRP radios.

- **gr-satellites (Free/Open)** — https://github.com/daniestevez/gr-satellites  
  GNU Radio blocks for decoding dozens of satellite waveforms.

---

### ✅ Radar & Sensing DSP (Free/Open)

- **pyUHD + GNU Radio Radar blocks (Free/Open)** — implement FMCW, pulse radar, doppler processing.

- **PySAR / openSAR (Free/Open)** — community SAR image processors for satellite & UAV radar.

- **OpenPulse (Free/Open)** — pulse compression, matched filters, range-Doppler FFT pipelines.

- **KFR DSP (Free/Open)** — https://github.com/kfrlib/kfr  
  High-performance DSP library for filtering, FFT, convolution (C++) suitable for embedded Linux SDR.

---

### ✅ Audio / Voice DSP (Free/Open)

- **SpeexDSP (Free/Open)** — high-efficiency audio processing: filters, AGC, echo cancel, noise suppression.

- **Opus Codec (Free/Open)** — https://opus-codec.org  
  Voice + audio codec used in SDR voice links and low-latency comms.

- **SoX DSP (Free/Open)** — https://sox.sourceforge.net  
  Filters, resampling, equalizers for embedded PCM pipelines.

---

### ✅ Coding & FEC Engines (Free/Open)

- **OpenFEC (Free/Open)** — https://openfec.org  
  Reed-Solomon and RaptorQ FEC for lossy RF links.

- **Kodo C++/Python Community Editions (Free)** — network coding for satellite/mesh networks (limited free).

- **LDPC / Turbo Implementations (OpenCores/GitHub)** — modular HDL blocks for high-rate links.

---

### ✅ DSP Simulation, Testing & Tooling (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  MATLAB-compatible numerical computing for filters, modulation, signal analysis.

- **SciPy / NumPy / Matplotlib (Free/Open)** — Python numeric and signal processing stack.

- **Sigrok + PulseView (Free/Open)** — logic analyzer suite ideal for verifying digital baseband and high-speed GPIO/serial DSP streams.

- **Qucs-S (Free/Open)** — RF circuit simulation with S-parameters, mixers, filters.

- **Scilab (Free/Open)** — https://www.scilab.org  
  Numerical DSP analysis/visualization environment.

---

### ✅ Learning Repos & Academic Datasets (Free/Open)

- **GNU Radio Tutorials & Courseware (Free/Open)** — official examples and university labs.

- **MIT OpenCourseWare DSP (Free)** — full lecture notes, labs and assignments.

- **Stanford EE104 / EE264 (Free Notes)** — advanced DSP, filter design, sampling theory.

- **DSP-Related Kaggle/AIR datasets (Free)** — RF signal classification, radar echoes.

---

## 48. High-Voltage & Power Electronics Simulation Tools  
_Free / open-source tools for SMPS design, HV converters, motor drives, insulation coordination, switch transients, magnetics and thermal-electrical co-simulation._

---

### ✅ Power Electronics Circuit Simulation (Free/Open)

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

---

### ✅ Magnetics, Transformers & Inductors (Free/Open)

- **FEMM (Free/Open)** — https://www.femm.info  
  2D FEM simulation for magnetics: transformer cores, inductors, flux leakage, saturation and eddy losses.

- **MagNet (Free Student Version)** — limited electromagnetic design for high-power transformers & chokes.

- **IncaMag / OpenMagnetics (Free/Open)** — open magnetic device design with winding losses, AC effects, core selection.

- **Texas Instruments Inductor & Transformer Tools (Free)** — application notes for flyback/forward, coupled inductors, current ripple.

- **PowerEsim (Free-Tier)** — https://www.poweresim.com  
  Online SMPS magnetics calculator, thermal checks, loss estimation, BOM suggestions.

---

### ✅ High-Voltage Isolation, Creepage & Clearance (Free Resources)

- **Creepage/Clearance Calculators (Free Web Tools)** — map altitude, CTI, insulation classes to PCB spacing.

- **UL / IEC Public Guides (Free Summaries)** — mains isolation rules for SMPS, EV chargers, battery packs.

- **Bourns / Littelfuse App Notes (Free)** — fuse sizing, MOV/TVS selection, surge and lightning protection.

- **Pulse/High-Voltage Transformer App Notes (Free PDFs)** — design rules for reinforced insulation windings.

---

### ✅ Motor Drive & Inverter Simulation (Free/Open)

- **Motor Control Workbench (ST) (Free)** — generate FOC/BLDC code + motor models for STM32 MCUs.

- **TI MotorWare / InstaSPIN Labs (Free)** — motor modeling, FOC, SMO observers, Hall/encoder setups.

- **SVPWM/FOC Reference Repos (Free/Open)** — GitHub C/STM32/ESP32/PIC implementations.

- **SimulIDE + MCU + Gate Drivers (Free/Open)** — small tool to simulate PWM control and inverter switching.

---

### ✅ GaN/SiC & Fast Switching (Free/Public)

- **GaN Systems / Transphorm App Notes (Free)** — gate driver layout, EMI mitigation, ZVS/ZCS design.

- **Wolfspeed SiC Design Tools (Free)** — thermal models, switching waveforms, loss calculators.

- **TI GaN Power Stages (Free)** — SPICE models and layout rules for high-frequency converters.

---

### ✅ Power Integrity / EMI Pre-Compliance (Free/Open)

- **OpenEMS (Free/Open)** — https://www.openems.de  
  FDTD electromagnetic simulation for radiated emissions, shielding, cable currents.

- **Sigrok + PulseView (Free/Open)** — logic + power switch timing, shoot-through, ringing detection.

- **LTspice + parasitic modeling (Free)** — simulate switch-node ringing, diode recovery, gate loops.

---

### ✅ Thermal & Reliability (Free/Public)

- **OpenFOAM (Free/Open)** — PCB airflow and heatsink analysis for HV power supplies/chargers.

- **SimScale Community (Free Tier)** — CFD/thermal for enclosures, forced cooling, hotspots.

- **PowerEsim Thermal (Free Tier)** — junction temperature, heatsink sizing, SOA stress.

---

### ✅ Test Automation & HIL (Free/Open)

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automate power-on tests, surge tests, calibration, efficiency logs for SMPS prototypes.

- **PyVISA + SCPI (Free/Open)** — control electronic loads, scopes, SMUs for soak testing.

- **Renode/QEMU (Free/Open)** — co-simulate power control firmware with virtual peripherals.

---

### ✅ High Voltage Safety & Compliance (Free/Public)

- **IPC-2221 / UL Summaries (Free)** — PCB spacing & creepage design.

- **IEC 60601-1 / 62368 Summaries (Free)** — reinforced isolation rules for offline SMPS, medical supplies.

- **NASA Power System Design Guides (Free PDFs)** — grounding, fault protection, radiation derating.

---

## 49. Open Embedded Operating Systems for Space / Defense / Safety-Critical  
_Free / open-source operating systems and RTOS frameworks used in aerospace, defense, satcom, nuclear, industrial safety, and mission-critical embedded systems._

---

### ✅ Space-Grade Flight Software Frameworks (Free/Open)

- **NASA cFS – Core Flight System (Free/Open)** — https://cfs.gsfc.nasa.gov  
  Flight-proven satellite OS framework with modular apps, telemetry, command, data handling, fault management.

- **F´ (F Prime) by NASA JPL (Free/Open)** — https://fprime.jpl.nasa.gov  
  Component-based flight SW platform used on Mars Helicopter & CubeSats. Includes ground station + codegen.

- **NOS3 (Free/Open)** — https://github.com/nasa/nos3  
  Virtual hardware simulation + CubeSat flight software + ground systems. Full training environment.

- **OpenSatKit (Free/Open)** — https://github.com/OpenSatKit  
  Hands-on flight software, ground station, telemetry viewer, training lab (built around cFS).

---

### ✅ Real-Time Operating Systems for Aerospace & Safety (Free/Open)

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

---

### ✅ Secure / Defense-Oriented OS & Middleware (Free/Open)

- **OpenTitan Firmware Stack (Free/Open)** — https://opentitan.org  
  Secure boot chain, attestation, crypto services for defense/Aero MCUs.

- **Trusted Firmware-M (Free/Open)** — https://www.trustedfirmware.org  
  PSA-Certified secure partitions for Cortex-M: crypto, secure storage, attestation.

- **PSA Crypto + mbedTLS (Free/Open)** — https://github.com/ARMmbed/mbedtls  
  Security stack for RTOS and microcontrollers, used in secure telemetry and command uplinks.

- **AeroKernel (Free/Open)** — academic OS kernels for high-assurance systems.

---

### ✅ High-Assurance Linux / Embedded Linux (Free/Open)

- **Buildroot (Free/Open)** — https://buildroot.org  
  Minimal secure Linux for aerospace SBCs. Reproducible builds, signed kernels, custom packages.

- **Yocto Project (Free/Open)** — https://www.yoctoproject.org  
  Hardened Linux for satellites/ground stations, supports secure boot & SELinux.

- **OpenWrt (Free/Open)** — https://openwrt.org  
  Trusted networking Linux used in secure gateways and telemetry concentrators.

- **SELinux / AppArmor (Free/Open)** — MAC frameworks for critical Linux deployments.

---

### ✅ Safety-Certified & Standards Alignment (Free/Public Docs)

- **MISRA-C Guidelines (Free Summaries)** — safe C coding rules used in avionics/defense.

- **DO-178C Summaries (Free)** — avionics software certification checklists, traceability goals.

- **ISO 26262 & IEC 61508 Summaries (Free)** — functional safety rules for embedded RTOS and devices.

- **ARINC 653 Public Guides (Free)** — time/space partitioning, inter-partition messaging.

---

### ✅ Testing, Simulation & Fault Injection (Free/Open)

- **Renode (Free/Open)** — https://renode.io  
  Simulate satellite or defense nodes with RTOS + radios + sensors for pre-flight testing.

- **Gazebo / Webots / AirSim (Free/Open)** — simulate drones, rovers, robots & sensors in mission environments.

- **QEMU (Free/Open)** — emulate ARM/RISC-V flight software and validate memory safety, watchdog behavior.

- **OpenHTF (Free/Open)** — automate hardware-in-loop tests for avionics boards and radios.

- **Syft / Grype (Free/Open)** — generate SBOMs and scan firmware for security vulnerabilities.

---

### ✅ Helpful Open Tools for Flight DevOps

- **OpenMCT (Free/Open)** — https://github.com/nasa/openmct  
  NASA’s modern mission control dashboard for telemetry and command.

- **InfluxDB + Grafana OSS (Free/Open)** — ground station telemetry storage + charts.

- **SatNOGS (Free/Open)** — global telemetry reception network.

- **cFS + COSMOS Ground Station Bundles (Free/Open)** — command/telemetry UI with scripting.

---

### ✅ Academic & Learning Resources

- **NASA FSW Training (Free)** — public lecture slides for space-grade software.

- **MIT Space Systems Classes (Free)** — avionics, redundancy, control, fault tolerance.

- **CubeSat Design Specification (Free)** — system-level avionics, radios, FSW expectations.

---

## 50. Advanced Semiconductor Packaging & Assembly Tools  
_Free / open-source tools and reference resources for IC packaging, wirebonding, flip-chip, 2.5D/3D packaging, PCB assembly, thermal-mechanical modeling, and high-reliability electronic assembly._

---

### ✅ Packaging Design / Layout / Footprint Tools (Free/Open)

- **KiCad (Free/Open)** — https://kicad.org  
  Full PCB + footprint + 3D package modeling. Supports BGA, QFN, CSP, wafer-level, stacked leadframes, HDI microvias.

- **LibrePCB (Free/Open)** — https://librepcb.org  
  PCB and packaging editor with 3D CAD generation, assembly BOM exports.

- **OpenBOM (Free/Open)** — https://www.openbom.com  
  Free tier for BOM creation, variants, assembly documentation.

- **OpenBoardView (Free/Open)** — https://openboardview.org  
  Package pinout and pad-level reverse engineering of assembly faults (BGA shorts, open vias, pad voids).

---

### ✅ Thermal-Mechanical & Warpage Simulation (Free/Open/Public)

- **OpenFOAM (Free/Open)** — https://openfoam.org  
  Thermal simulations for underfill, die attach, heatsink, spreader modeling and airflow on high-power ICs.

- **FEMM (Free/Open)** — https://www.femm.info  
  FEM for magnetics and thermal conduction—useful for package inductors, SiC/GaN power modules.

- **SimScale (Free Community Tier)** — https://simscale.com  
  Web-based FEA/CFD for heat dissipation, warpage, CTE mismatch in multi-layer packages.

- **ANSYS & COMSOL Academic Repos (Free Demos)** — public tutorials on solder fatigue, BGA reliability, thermal cycling.

---

### ✅ Wirebond, Flip-Chip, BGA & HDI Reference (Free/Public)

- **IPC-7351B Public Summaries (Free)** — package footprint standards (QFN/BGA/CSP).

- **JEDEC JESD Guides (Free Public Summaries)** — moisture sensitivity (MSL), reflow, warpage, board reliability.

- **NASA/ESA Assembly & Soldering Standards (Free)** — https://nepp.nasa.gov / https://escies.org  
  Space-grade rules for flux, vias, underfill, whisker mitigation, conformal coat, tin/lead reliability.

- **IPC-7093 (Free Summaries)** — Design/reliability for bottom termination components (QFN/DFN/LGA).

- **“Tin Whisker Mitigation” NASA Guides (Free PDF)** — whisker suppression for long-life boards.

---

### ✅ 2.5D / 3D Packaging, Interposers, TSV (Free/Open/Public)

- **Open3DFlow (Free/Open)** — research-level open 3D IC design flow (interposers, TSV routing).

- **ASU PTM Models (Free/Open)** — https://ptm.asu.edu  
  Advanced FinFET/TSV reliability, thermal and parasitics models.

- **Chiplet Interconnect Open Specs (Free/Public)** — Bunch of Wires, ODSA, AIB open chiplet PHY references.

- **DARPA CHIPS Program Docs (Free PDFs)** — assembly, chiplets, interposers, thermal management.

---

### ✅ Semiconductor Reliability & Aging (Free/Public)

- **MIL-HDBK-338 / 217 (Free PDFs)** — failure rate prediction for ICs, packaging, interconnects.

- **ARRL/IPC Solder Joint Fatigue Guides (Free)** — lead-free reliability, BGA cracking, voiding, underfill strategies.

- **JEDEC J-STD-020 / 033 (Free Summaries)** — moisture/reflow sensitivity and bake-out rules.

- **NASA Workmanship Standards (Free)** — cable harnessing, conformal coat, staking, crimping, high-rel aerospace assembly.

- **Coffin-Manson & Miner Fatigue Calculators (Free Sheets)** — predict solder/joint fatigue over thermal cycling.

---

### ✅ X-Ray, AOI & Manufacturing Debug (Free/Open)

- **OpenScanLab (Free/Open)** — datasets and algorithms for PCB/X-ray defect classification.

- **sigrok + PulseView (Free/Open)** — detect intermittent assembly failures, broken power nets, marginal BGA solder.

- **OpenHTF (Free/Open)** — https://google.github.io/openhtf  
  Automate functional tests in assembly lines: boot-tests, JTAG-tests, UART logs.

- **PyVISA + SCPI (Free/Open)** — automate AOI, ICT and boundary-scan driven tests.

---

### ✅ PCB/Package Co-Design & Co-Simulation (Free/Open)

- **OpenEMS (Free/Open)** — https://www.openems.de  
  Electromagnetic co-simulation for package + PCB transitions, controlled impedance, HF loss.

- **TX-Line (Free)** — microstrip/CPW calculators for BGA breakout, SerDes, DDR escape.

- **Qucs-S (Free/Open)** — S-parameter simulation for package to board transitions.

---

### ✅ SMT, Reflow, Soldering, Assembly Guides (Free/Public)

- **J-STD-001 Summaries (Free)** — soldering workmanship for high-rel electronics.

- **NASA Workmanship Standards (Free)** — staking, conformal coat, potting, cable harness.

- **IPC-A-610 (Free Summaries)** — Acceptability of electronic assemblies.

- **IPC-2221 (Free Summaries)** — insulation, creepage, clearance for high-voltage assemblies.

- **Fritzing (Free/Open)** — visualization of assembly, through-hole/SMD mixed boards.

---

### ✅ Bonding / Die Attach / Underfill (Free/Public)

- **Henkel/Loctite Application Notes (Free)** — underfill, epoxy, die attach reliability.

- **Dow Corning Thermal Gel Guides (Free)** — TIM/gel selection for SoC and SiC/GaN modules.

- **Nordson/Dage App Notes (Free PDFs)** — X-ray analysis, voiding, delamination.

---

### ✅ Useful Checklists & Templates (Free)

- BGA escape routing checklist  
- MSL storage + drying logs  
- X-ray inspection checklist  
- Reflow profiling templates  
- Reliability qualification matrix (HTOL, HAST, TC, drop, vibration)

---

## 51. Acoustic / Ultrasonic / Piezo Simulation Tools  
_Free / open-source tools and reference material for designing ultrasonic sensors, piezo drivers, acoustic waveguides, MEMS microphones, sonar, NDT transducers, and acoustic lenses._

---

### ✅ Acoustic Wave & Ultrasonic Simulation (Free/Open)

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

---

### ✅ Piezoelectric Modeling (Free/Open)

- **Elmer PZ Module (Free/Open)** — models piezo-actuated devices (ultrasonic cleaners, NDT probes, buzzers).

- **FEMM (Free/Open)** — https://www.femm.info  
  Magnetic models for piezo drivers and ultrasonic transducers using transformer-coupled piezo power stages.

- **OpenPZ / Piezoelectric GitHub Projects (Free/Open)** — open scripts and FEM models for PZT resonant tuning, beam/shell effects.

---

### ✅ Acoustics for Speakers, MEMS Mics, Audio Devices (Free/Open)

- **REW – Room EQ Wizard (Free)** — https://www.roomeqwizard.com  
  Acoustic response measurement, FFT, impulse response, echo/reflection analysis.

- **HornResp (Free)** — classic tool for horn-loaded speaker and acoustic waveguide analysis.

- **PulseAudio + ALSA Tools (Free/Open)** — capture and analyze microphone streams, latency, filtering.

- **Audacity (Free/Open)** — https://www.audacityteam.org  
  FFT, spectrograms, filtering, harmonic distortion checks for sonic/ultrasonic signals.

---

### ✅ Filter, Beamforming & DSP (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  Acoustic signal processing: FFT, FIR/IIR, beamforming, matched filters, STFT.

- **SciPy/NumPy (Free/Open)** — Python scientific stack for acoustic DSP, windowing, simulation and correlation.

- **Liquid-DSP (Free/Open)** — https://github.com/jgaeddert/liquid-dsp  
  Optimized DSP blocks: filters, decimators, modulation for ultrasonic comms & sonar.

- **MATLAB Online + Free Toolboxes (Limited)** — university-hosted acoustic and beamforming examples.

---

### ✅ MEMS Microphones, Hydrophones & Transducers (Free/Public)

- **Analog Devices MEMS Mic App Notes (Free)** — beamforming arrays, noise filtering, ultrasonic drivers.

- **TDK/InvenSense App Notes (Free)** — MEMS mic frequency response, acoustic ports, SNR modeling.

- **Piezo Driver App Notes (Free)** — TI, ADI, ST: resonant drive, class-D, high voltage, impedance tuning.

- **Underwater Acoustics Free Texts (Public)** — sonar basics, hydrophone placement, propagation losses.

---

### ✅ NDT / Industrial Ultrasonic (Free/Open)

- **OpenUT (Free/Open)** — community libraries for ultrasonic thickness and flaw detection systems.

- **OpenPulse / Ultrasonic Pulse Compression (Free/Open)** — matched filtering and chirp compression for NDT.

- **gprMax (Free/Open)** — https://www.gprmax.com  
  FDTD simulation tool for Ground Penetrating Radar—also applicable to ultrasonic inspection mediums.

---

### ✅ Measurement, Visualization & Logging (Free/Open)

- **Sigrok + PulseView (Free/Open)** — https://sigrok.org  
  Capture transducer drive waveforms, PWM drivers, and resonant ringing.

- **SoX (Free/Open)** — advanced audio analysis, filtering, spectrograms.

- **OpenMCT + Grafana OSS (Free)** — visualize long-term acoustic telemetry from sensor arrays.

---

### ✅ Learning Resources (Free)

- **MIT Acoustics Courseware (Free)** — fundamentals of sound waves, cavity modes, filters, microphones.

- **Coursera / edX Acoustics Modules (Free Audit)** — DSP, transducers, psychoacoustics.

- **Ultrasonic NDT PDFs (Free/Public)** — flaw detection, phased-array transducers.

---

## 52. LiDAR / Radar Development Stacks (Free/Open)  
_Free and open-source tools for LiDAR / mmWave radar signal processing, point cloud handling, mapping, tracking, perception, SLAM and embedded radar DSP._

---

### ✅ LiDAR Processing & Point Cloud Libraries (Free/Open)

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

---

### ✅ LiDAR SLAM, Mapping & Perception (Free/Open)

- **Cartographer (Free/Open)** — https://google-cartographer.readthedocs.io  
  2D/3D SLAM for mobile robots and warehouse AMRs.

- **LOAM / A-LOAM / LIO-SAM (Free/Open)** — LiDAR odometry and mapping libraries for autonomous cars & robots.

- **Hector SLAM (Free/Open)** — http://wiki.ros.org/hector_slam  
  Fast 2D SLAM for LIDAR on AMRs and service robots.

- **LeGO-LOAM (Free/Open)** — robust outdoor LiDAR mapping for drones and UGVs.

- **ETH ASL Mapping Repos (Free/Open)** — top research implementations for LiDAR odometry & loop closure.

- **ROS Navigation + Costmaps (Free/Open)** — https://wiki.ros.org/navigation  
  Use LiDAR for obstacle detection, path planning and collision avoidance.

---

### ✅ LiDAR Visualization & Playback (Free/Open)

- **RViz / RViz2 (Free/Open)** — part of ROS; visualize point clouds, maps, trajectories, IMU, LiDAR scans.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Modern web-based LiDAR viewer with time sync, TF trees, bag file playback, robot telemetry.

- **ROSBAG (Free/Open)** — record & replay sensor data (LIDAR+IMU+Odom) for offline analysis.

---

### ✅ Radar / mmWave DSP Frameworks (Free/Open)

- **tiRadar / mmWave-TI Open SDK (Free)** — TI public SDK for IWR/ AWR mmWave sensors: FFT, range-Doppler, CFAR, tracking.

- **GNU Radio (Free/Open)** — https://www.gnuradio.org  
  Build SDR-based radar pipelines: FMCW, pulse radar, Doppler, matched filters.

- **gr-radar (Free/Open)** — GNU Radio radar blocks for FMCW, pulse compression, range-Doppler maps.

- **OpenPulse (Free/Open)** — pulse compression, match filtering, range FFT, CFAR.

- **pyUHD + USRP (Free/Open)** — build custom SDR radars for automotive, drone altimeters, proximity sensors.

---

### ✅ Radar Tracking, Kalman Filtering, Sensor Fusion

- **Robot Localization (Free/Open)** — https://github.com/cra-ros-pkg/robot_localization  
  EKF/UKF sensor fusion for LiDAR + radar + wheel odom + IMU.

- **FilterPy (Free/Open)** — https://github.com/rlabbe/filterpy  
  Python Kalman filters for tracking, SLAM, target detection.

- **Stone Soup (Free/Open)** — https://github.com/dstl/Stone-Soup  
  Advanced tracking framework: data association, multi-target tracking, radar/LiDAR fusion.

- **OpenCV + Open3D Fusion (Free/Open)** — Combine camera + LiDAR for object detection and mapping.

---

### ✅ Automotive & Robotics LiDAR Stacks (Free/Open)

- **Autoware.AI / Autoware.Auto (Free/Open)** — https://www.autoware.org  
  AV perception stack: LiDAR detection, tracking, HD mapping, route planning.

- **Apollo (Free/Open)** — https://github.com/ApolloAuto/apollo  
  Apollo autonomous driving stack: LiDAR detection, fusion, SLAM, prediction.

- **OpenPilot (Free/Open)** — radar-camera fusion, ACC/adaptive cruise, lane keeping (community automotive).

- **ROS2 Navigation2 (Free/Open)** — https://navigation.ros.org  
  Real-time LiDAR-based navigation and multi-robot fleet control.

---

### ✅ Industrial Sensing / NDT / Robotics (Free/Open)

- **gprMax (Free/Open)** — https://www.gprmax.com  
  FDTD GPR simulator for subsurface radar; also used for ultrasonic & dielectric imaging.

- **Open3D + ICP Pipelines** — robotic arm inspection, warehouse pallet picking, environment modeling.

- **CloudCompare Deviation Maps** — compare scanned vs CAD to check mechanical tolerances.

---

### ✅ LiDAR / Radar Hardware Drivers (Free/Open)

- **RPLIDAR / YDLIDAR ROS Drivers (Free/Open)** — ROS support for low-cost 360° LiDARs.

- **Velodyne / Ouster ROS Drivers (Free/Open)** — high-resolution point clouds for robotics & self-driving.

- **Livox ROS Drivers (Free/Open)** — fast point cloud streaming for SLAM and drones.

- **Open IWR mmWave Drivers (Free/Open)** — TI mmWave demo visualizer + Python tools.

---

### ✅ Tools for Data Logging, Analysis & Replay (Free/Open)

- **ROS Bag / rosbag2 (Free/Open)** — record LiDAR + IMU + radar for regression testing.

- **MCAP (Foxglove) (Free/Open)** — high-performance logging format for large LiDAR datasets.

- **InfluxDB + Grafana OSS (Free)** — telemetry storage and dashboards for fleet sensing.

- **OpenMCT (Free/Open)** — mission control dashboard for sensor telemetry.

---

### ✅ Datasets for Testing & AI Models (Free/Open)

- **KITTI Vision Benchmark (Free)** — autonomous driving LiDAR, stereo, radar sets.

- **Waymo Open Dataset (Free)** — full-scale AV LiDAR perception dataset.

- **Nuscenes (Free)** — AV dataset with radar + LiDAR + camera.

- **Ford Autonomous Dataset (Free)** — LiDAR + radar + GPS/IMU mapping data.

---

## 53. Industrial Imaging / Computer Vision Toolkits (Free/Open)  
_Free / open-source frameworks for machine vision, industrial inspection, barcode/QR, object tracking, defect detection, and production-line automation._

---

### ✅ Core Computer Vision Libraries (Free/Open)

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

---

### ✅ Industrial Inspection & SMT/PCB Vision (Free/Open)

- **OpenPnP (Free/Open)** — https://openpnp.org  
  Open-source pick-and-place vision system: fiducial recognition, nozzle alignment, part inspection.

- **OpenCV + Halcon-like pipelines (Free/Open)** — camera calibration, perspective correction, barcode, presence/absence checks.

- **KiKit (Free/Open)** — https://github.com/yaqwsx/KiKit  
  PCB panelization + fiducial placement for machine vision alignment.

- **Gerber2Gcode Open Tools (Free)** — fiducials and inspection image generation from gerbers.

- **BGA/QFN X-ray Dataset Repos (Free/Open)** — community datasets for solder joint defect training.

---

### ✅ Barcode / OCR / Industrial Scanners (Free/Open)

- **ZBar (Free/Open)** — https://github.com/mchehab/zbar  
  Reads QR, EAN, UPC, DataMatrix; used in warehouse scanners and traceability.

- **ZXing (Free/Open)** — https://github.com/zxing/zxing  
  Barcode/QR reading — works on embedded Linux cameras and scanners.

- **Tesseract OCR (Free/Open)** — https://github.com/tesseract-ocr/tesseract  
  OCR for labels, part numbers, packaging, expiry dates.

---

### ✅ Factory Robotics / Vision Pipelines (Free/Open)

- **ROS + image_pipeline (Free/Open)** — https://wiki.ros.org/image_pipeline  
  Camera drivers, calibration, rectification, stereo depth for robotics.

- **ROS MoveIt + perception plugins (Free/Open)** — object picking, pose estimation.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Visualize real-time camera feeds, 3D point clouds, image topics, factory telemetry.

- **NVIDIA Jetson Multi-Camera (Free/Open Samples)** — object detection for conveyor belts, palletizers.

---

### ✅ Edge Inference / ONNX Tooling (Free/Open)

- **ONNX Runtime (Free/Open)** — https://onnxruntime.ai  
  Deploy models on embedded CPUs/NPUs/GPUs, production-ready, supports OpenCV integration.

- **TensorRT OSS Samples (Free/Open)** — CUDA-accelerated inference for Nvidia Jetson.

- **Edge Impulse Free Tier** — https://edgeimpulse.com  
  Train + deploy anomaly detection & CV models to MCUs/SBCs (free developer tier).

---

### ✅ 3D Vision / Stereo / Depth Cameras (Free/Open)

- **Intel RealSense SDK (Free/Open)** — https://github.com/IntelRealSense/librealsense  
  Depth cameras for robotic picking, warehouse automation.

- **Open3D (Free/Open)** — 3D scene segmentation, CAD comparison, warehouse mapping.

- **ElasticFusion (Free/Open)** — real-time 3D reconstruction from RGB-D cameras.

---

### ✅ Defect Detection / Quality Control (Free/Open)

- **Anomalib (Free/Open)** — https://github.com/openvinotoolkit/anomalib  
  Industrial anomaly detection (scratches, dents, missing components) with SOTA deep learning models.

- **OpenCV + scikit-image (Free/Open)** — thresholding, blob detection, color threshold inspection.

- **Segmentation Models Pytorch (Free/Open)** — pretrained semantic segmentation for factory defects.

- **Ultralytics YOLOv8 (Open)** — fast segmentation/defect detection models with free usage on local compute.

---

### ✅ Annotation, Labeling & Dataset Tools (Free/Open)

- **CVAT (Free/Open)** — https://cvat.org  
  Annotation tool from Intel. Label objects, polygons, defects, OCR zones, barcodes for training CV models.

- **LabelMe / LabelImg (Free/Open)** — lightweight dataset labeling tools.

- **Roboflow Free Tier** — dataset management and augmentation for small industrial projects.

---

### ✅ Visualization & Data Logging

- **OpenMCT (Free/Open)** — telemetry dashboards for cameras, robots, production sensors.

- **MCAP / ROS Bag (Free/Open)** — record camera streams for regression testing.

- **Grafana OSS (Free/Open)** — runtime vision system monitoring (fps, latency, anomalies).

---

### ✅ Learning Material

- **OpenCV Python Courses (Free)** — official samples + notebooks.

- **MIT CV Lectures (Free)** — fundamentals of computer vision and robotics perception.

- **Kaggle Industrial Vision Datasets (Free)** — PCB defects, metal surface scratches, product inspection.

---

## 54. Autonomous Drones / UAV Firmware & Ground Systems  
_Free / open-source autopilot stacks, flight controllers, simulators, ground stations, telemetry radios, swarm frameworks, and computer vision pipelines for UAVs._

---

### ✅ Autopilot Firmware (Free/Open)

- **ArduPilot (Free/Open)** — https://ardupilot.org  
  Industry-leading open-source autopilot: multirotor, fixed-wing, VTOL, rover, boat, sub, antenna tracking. Supports GPS, RTK, ADS-B, obstacle avoidance.

- **PX4 (Free/Open)** — https://px4.io  
  Professional autopilot for drones and VTOL aircraft. Modular flight stack, MAVLink, offboard control, companion computers.

- **Paparazzi UAV (Free/Open)** — https://wiki.paparazziuav.org  
  Research-oriented autopilot with advanced guidance and swarm behaviors.

- **LibrePilot (Free/Open)** — older but popular with hobby drones, F4 flight controllers.

- **Cleanflight / Betaflight / iNav (Free/Open)** — FPV/racing flight stacks with PID tuning, telemetry, OSD, advanced filters.

---

### ✅ Ground Control Stations (Free/Open)

- **QGroundControl (Free/Open)** — http://qgroundcontrol.com  
  Mission planning, telemetry, parameter tuning, video streaming, companion computer integration.

- **Mission Planner (Free/Open)** — https://ardupilot.org/planner  
  Data logging, mission planning, sensor calibration, flight replay for ArduPilot.

- **MAVProxy (Free/Open)** — Python-based GCS and command-line control for MAVLink.

- **OpenMCT (Free/Open)** — https://github.com/nasa/openmct  
  NASA mission control UI usable for drone telemetry, map overlays, and flight logs.

- **Foxglove Studio (Free/Open)** — https://foxglove.dev  
  Visualize telemetry, IMU, LiDAR, video, CAN/serial logs for autonomous drones.

---

### ✅ Simulation & Digital Twins (Free/Open)

- **Gazebo / Gazebo Garden (Free/Open)** — https://gazebosim.org  
  Physically accurate simulation with drone models, sensors, wind, payloads, PX4 plugins.

- **AirSim (Free/Open)** — https://github.com/microsoft/AirSim  
  Unreal/Unity drone sim with camera, LiDAR, GPS, IMU, computer vision pipelines.

- **RotorS (Free/Open)** — ROS-based multirotor simulator for research and SLAM.

- **jsbsim (Free/Open)** — flight dynamics engine used in FlightGear; PX4/ArduPilot integration.

---

### ✅ Companion Computer / CV / Perception (Free/Open)

- **ROS + MAVROS (Free/Open)** — ROS → MAVLink bridge to control drones with onboard compute.

- **RTAB-Map, OpenVSLAM, ORB-SLAM2 (Free/Open)** — onboard visual SLAM for GPS-denied navigation.

- **OpenCV, TensorFlow Lite, YOLO (Free/Open)** — onboard object detection and tracking.

- **Autoware Lite / Apollo (Free/Open)** — for ground robots; can be adapted for drone perception & autonomy.

---

### ✅ Swarming, Fleet Control & UTM (Free/Open)

- **Open-RMF (Free/Open)** — multi-robot fleet coordination; can adapt to UAV scheduling & routing.

- **Swarm UAV Open Frameworks (GitHub)** — decentralized mission coordination, formation flight.

- **MAVSDK (Free/Open)** — https://mavsdk.mavlink.io  
  Control multiple UAVs using APIs (Python/C++).

- **DroneCAN (Free/Open)** — CAN-bus ecosystem for UAV payloads, ESCs, GPS, airspeed sensors.

---

### ✅ Telemetry, Radios, Links (Free/Open)

- **MAVLink (Free/Open)** — https://mavlink.io  
  Lightweight messaging protocol used in PX4/ArduPilot.

- **QoS telemetry via ROS2 DDS (Free/Open)** — robust multi-robot telemetry backbone.

- **RTL-SDR + GNU Radio (Free/Open)** — receive ADS-B, telemetry, custom downlinks.

---

### ✅ Flight Logs, Analysis & Replay (Free/Open)

- **Flight Review / Mavlink Flight Analyzer (Free/Open)** — online and local tools to analyze UAV logs (battery, PID, GPS, vibration).

- **Mission Planner Log Viewer (Free)** — graphs, FFT analysis for motor/prop vibration.

- **PX4 uLog + plot_juggler (Free/Open)** — real-time and replay dashboards for flight data.

---

### ✅ Hardware Repos (Free/Open)

- **OpenDroneID Project (Free/Open)** — standard for broadcast remote ID.

- **Open-Source ESC / BLDC Firmware (Free/Open)** — BLHeli, SimonK, VESC — motor control for drones.

- **Open-Hardware Flight Controllers (Free/Open)** — PX4/ArduPilot compatible boards on GitHub.

---

### ✅ Learning Resources (Free)

- **PX4 Developer Guide (Free)** — architecture, autopilot internals, HITL, SITL.

- **ArduPilot Docs (Free)** — tuning guides, GPS + RTK, vision-based landing.

- **MIT / ETH UAV Lectures (Free)** — dynamics, control, SLAM, autonomy, multi-robot systems.

---

## 55. Audio / Vibration Analysis & Condition Monitoring Stacks (Free/Open)  
_Free or open-source tools for machine health monitoring, FFT/Spectrogram analysis, rotational equipment diagnostics, acoustic anomaly detection, and predictive maintenance._

---

### ✅ Core Signal Processing & Analysis (Free/Open)

- **GNU Octave (Free/Open)** — https://octave.org  
  MATLAB-compatible environment for FFT, PSD, spectrograms, filters, order tracking & envelope detection.

- **SciPy / NumPy / Matplotlib (Free/Open)** — full Python DSP workflow: filtering, FFT, STFT, cepstrum, correlation.

- **SoX (Free/Open)** — https://sox.sourceforge.net  
  Command-line DSP tool for audio capture, frequency-domain analysis, spectrograms, filtering.

- **librosa (Free/Open)** — https://librosa.org  
  Audio feature extraction: MFCC, chroma, spectral roll-off, ideal for sound-based anomaly detection.

- **PyWavelets (Free/Open)** — wavelet analysis for bearing failure detection and transient extraction.

---

### ✅ Vibration Diagnostics (Free/Open)

- **VibrationData Suite (Free)** — https://www.vibrationdata.com  
  Massive library of scripts, tutorials and tools: PSD, SDOF/MDOF analysis, shock response spectrum, fatigue damage.

- **midasNDT / OpenVibe-Acoustic GitHub Tools (Free/Open)** — open vibration analysis and NDT computation scripts.

- **VibrationToolbox for Python (Free/Open)** — https://vibrationtoolbox.github.io  
  Rotordynamics, shaft unbalance, modal analysis, orbit plots.

- **PyDSP / SigROS GitHub Tools (Free/Open)** — vibration FFT / PSD pipelines for rotating machines & motors.

---

### ✅ Predictive Maintenance / Anomaly Detection (Free/Open)

- **Edge Impulse Free Tier** — https://edgeimpulse.com  
  Build ML anomaly detectors using vibration + sound on MCUs/SBCs. Supports FFT + MFCC features and on-device classification.

- **Anomalib (Free/Open)** — https://github.com/openvinotoolkit/anomalib  
  SOTA anomaly detection for industrial sensors (acoustic/spectral).

- **Merlion (Free/Open)** — https://github.com/salesforce/Merlion  
  Time-series anomaly detection and forecasting for vibration telemetry.

- **River ML (Free/Open)** — streaming ML for real-time maintenance dashboards on edge gateways.

---

### ✅ Sensor Data Pipelines (Free/Open)

- **InfluxDB OSS + Grafana OSS (Free)** — telemetry storage, FFT trend charts, vibration heatmaps, alarms.

- **Telegraf (Free/Open)** — collect vibration/accelerometer data via MQTT, MODBUS, OPC-UA.

- **OpenMCT (Free/Open)** — real-time mission control dashboard for factory sensors.

- **Node-RED (Free/Open)** — MQTT → DSP → dashboard pipelines for machine health.

---

### ✅ Acoustic & Machine Sound Diagnostics (Free/Open)

- **Audacity (Free/Open)** — https://www.audacityteam.org  
  Spectrogram, harmonic analysis, noise profiling, high-speed FFT for acoustic fault recording.

- **Praat (Free/Open)** — sound visualization, spectral envelopes, speech/noise analysis — useful for valve/pump diagnostics.

- **REW – Room EQ Wizard (Free)** — https://www.roomeqwizard.com  
  FFT & SPL measurement; helpful for acoustic/ultrasonic system testing.

- **TF-Lite + MicroPython Audio Classifiers (Free/Open)** — deploy tiny audio-based anomaly detectors to ESP32/MCUs.

---

### ✅ IoT Gateways: Condition Monitoring (Free/Open)

- **ThingsBoard Community Edition (Free/Open)** — telemetry, dashboards, ML rules.

- **KubeEdge (Free/Open)** — edge compute for vibration ML near machines.

- **Eclipse Kura (Free/Open)** — industrial IoT gateway with OPC-UA/MQTT logging from IMU/vibration sensors.

---

### ✅ Specialized Toolkits (Free/Open)

- **gprMax (Free/Open)** — ground-penetrating radar simulator, also useful for acoustic/ultrasonic waves in solids.

- **Open Modal Analysis Repos (Free/Open)** — extract mode shapes and natural frequencies for machine frames.

- **OpenAcoustics / Acoular (Free/Open)** — beamforming, microphone arrays, noise source localization.

---

### ✅ Data Logging & File Formats

- **MCAP / ROS Bag (Free/Open)** — high-performance logging of vibration streams for offline FFT/ML.

- **HDF5 + Pandas (Free/Open)** — structured storage of multi-sensor time series.

- **Prometheus + Grafana (Free)** — scrape industrial sensors every second for degradation trend monitoring.

---

### ✅ Learning Resources (Free)

- **MIT Vibration / Applied Mechanics Courseware** — rotating machinery, dampers, FFT fundamentals.

- **NASA Machinery Diagnostics PDFs (Free)** — bearing/gearbox failure signatures and spectrum patterns.

- **NIST Fault Datasets (Free)** — public vibration datasets for ML benchmarking.

---


