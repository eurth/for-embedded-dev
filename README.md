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

