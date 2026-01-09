# ⚖️ G) Compliance, Standards & Safety

> **Complete guide to certifications, safety standards, EMC testing, and regulatory compliance**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Topics | Quick Jump |
|---------|--------|------------|
| [30. Safety Standards](#30-safety-standards--certifications) | IEC 61508, ISO 26262, DO-178C | Functional safety |
| [31. EMC & RF Testing](#31-emc--rf-testing) | FCC, CE, CISPR | Electromagnetic compliance |
| [32. Security Standards](#32-cybersecurity-standards) | IEC 62443, Common Criteria | Embedded security |
| [33. Quality Systems](#33-quality-management-systems) | ISO 9001, CMMI, Automotive SPICE | Process standards |

---

## 🆚 Quick Comparison: Safety Standards

| Standard | Domain | SIL Levels | Tool Qualification | Region |
|----------|--------|------------|---------------------|--------|
| **IEC 61508** | General industrial | SIL 1-4 | Required for SIL 2+ | Global |
| **ISO 26262** | Automotive | ASIL A-D | Required for ASIL B+ | Global |
| **IEC 62304** | Medical devices | Class A/B/C | Required | Global |
| **DO-178C** | Aviation | DAL A-E | Required | Global |
| **IEC 61511** | Process industry | SIL 1-4 | Required for SIL 2+ | Global |
| **EN 50128** | Railway | SIL 0-4 | Required for SIL 2+ | Europe |

---

## 30. Safety Standards & Certifications

### 🌟 Top Safety Standards

#### **IEC 61508** — Functional Safety of Electrical/Electronic Systems
https://www.iec.ch/functionalsafety

**The umbrella standard for functional safety**

- ✅ Covers Safety Integrity Levels (SIL 1-4)
- ✅ Lifecycle management
- ✅ Tool qualification requirements
- ✅ Basis for domain-specific standards

**Key requirements:**
- Static analysis (MISRA C, CERT C)
- Code reviews
- Unit testing (100% coverage for SIL 3+)
- Tool qualification
- Traceability

---

#### **ISO 26262** — Functional Safety for Road Vehicles
https://www.iso.org/standard/68383.html

**Automotive safety standard (based on IEC 61508)**

- ✅ ASIL A (lowest) to ASIL D (highest)
- ✅ Covers hardware + software
- ✅ Mandatory for automotive suppliers

**ASIL Levels:**
- **ASIL A**: Minor injuries (e.g., indicator lights)
- **ASIL B**: Moderate injuries (e.g., airbag sensors)
- **ASIL C**: Severe injuries (e.g., ESC)
- **ASIL D**: Life-threatening (e.g., steering, braking)

**Compliant Tools:**
- **Polyspace** — https://www.mathworks.com/products/polyspace.html (Commercial)
- **LDRA** — https://ldra.com (Commercial)
- **GNATprove** — https://www.adacore.com/about-gnat-pro (Ada/SPARK)

---

#### **IEC 62304** — Medical Device Software
https://www.iso.org/standard/38421.html

**Software lifecycle for medical devices**

- ✅ Class A (no harm), B (non-serious injury), C (death/serious injury)
- ✅ Risk management required (ISO 14971)
- ✅ FDA recognizes this standard

**Key requirements:**
- Comprehensive documentation
- Verification & validation
- Traceability matrices
- Change control

---

#### **DO-178C** — Airborne Software
https://www.rtca.org

**Aviation software standard**

- ✅ Design Assurance Levels (DAL) A-E
- ✅ Extremely rigorous (DAL A: no single failure can cause catastrophe)
- ✅ Used in commercial + military aviation

---

### 📦 More Safety Standards

<details>
<summary><b>Industry-Specific Standards</b></summary>

**Railway:**
- **EN 50128** — Software for Railway Control and Protection Systems
- **CENELEC EN 50126** — Railway Reliability, Availability, Maintainability, Safety (RAMS)

**Nuclear:**
- **IEC 61513** — Nuclear Power Plant Instrumentation & Control

**Process Industry:**
- **IEC 61511** — Functional Safety for Process Industry (based on IEC 61508)

**Machinery:**
- **ISO 13849** — Safety-Related Parts of Control Systems

</details>

---

### 🛠️ Safety Tools & Resources

<details>
<summary><b>Certified Compilers & Toolchains</b></summary>

**C/C++ Compilers:**
- **Green Hills MULTI** — https://www.ghs.com  
  DO-178C, ISO 26262 certified

- **IAR Embedded Workbench** — https://www.iar.com  
  Functional safety edition (certified for IEC 61508, ISO 26262)

- **TASKING** — https://www.tasking.com  
  Safety-certified toolchains

**RTOS:**
- **SafeRTOS** — https://www.freertos.org/FreeRTOS-Plus/Safety_Critical_Certified/SafeRTOS.html  
  IEC 61508 certified FreeRTOS variant

- **Zephyr Safety Certification** — https://docs.zephyrproject.org/latest/safety/index.html  
  IEC 61508 certification in progress

**Static Analysis:**
- **Polyspace** (MATLAB) — ISO 26262 tool qualification
- **LDRA** — Multi-standard qualification
- **GrammaTech CodeSonar** — https://www.grammatech.com

</details>

<details>
<summary><b>Coding Standards for Safety</b></summary>

**MISRA C** — https://www.misra.org.uk
- ✅ Most widely used embedded C standard
- ✅ 143 rules (MISRA C:2012)
- ✅ Mandatory for automotive, aerospace, medical
- ✅ Tools: PC-lint Plus, Cppcheck, LDRA

**CERT C** — https://wiki.sei.cmu.edu/confluence/display/c
- ✅ Carnegie Mellon SEI standard
- ✅ Security-focused
- ✅ Free PDF available

**AUTOSAR C++14** — https://www.autosar.org
- ✅ Modern C++ for automotive
- ✅ Based on MISRA C++

**SEI CERT Coding Standards** — C, C++, Java, Perl, Android

</details>

---

## 31. EMC & RF Testing

### 📡 Electromagnetic Compliance (EMC)

#### **FCC (United States)**
https://www.fcc.gov/engineering-technology/laboratory-division/general/equipment-authorization

**Federal Communications Commission**

- ✅ Part 15B: Unintentional radiators (digital devices)
- ✅ Part 15C: Intentional radiators (Wi-Fi, BLE, LoRa, ISM)
- ✅ FCC ID required for RF products

**Pre-Compliance Tools:**
- Near-field probes (Beehive, Tekbox)
- Spectrum analyzers
- EMC test receivers

---

#### **CE (Europe)**
https://ec.europa.eu/growth/single-market/ce-marking_en

**Conformité Européenne (European Conformity)**

**Key directives:**
- **EMC Directive 2014/30/EU** — Electromagnetic compatibility
- **RED 2014/53/EU** — Radio Equipment Directive (Wi-Fi, BLE)
- **LVD 2014/35/EU** — Low Voltage Directive (safety)
- **RoHS 2011/65/EU** — Restriction of Hazardous Substances

**Required Standards:**
- **EN 55032** — Emissions (CISPR 32)
- **EN 55035** — Immunity (CISPR 35)
- **EN 301 489** — EMC for radio equipment
- **EN 300 328** — 2.4 GHz (Wi-Fi, BLE)

---

<details>
<summary><b>Other Regional Certifications</b></summary>

**Canada:**
- **ISED (Innovation, Science and Economic Development Canada)**
- Similar to FCC

**Japan:**
- **TELEC (Telecom Engineering Center)**
- **VCCI** — EMC certification

**China:**
- **CCC (China Compulsory Certification)**
- **SRRC** — Radio type approval

**Australia:**
- **RCM (Regulatory Compliance Mark)**
- EMC + RF certification

**Korea:**
- **KC (Korea Certification)**

</details>

---

### 🛠️ EMC Design Resources

<details>
<summary><b>EMC Design Guidelines</b></summary>

**Free Resources:**
- **TI EMC Design Guide** — https://www.ti.com/lit/an/szza009/szza009.pdf
- **Analog Devices EMC Handbook** — https://www.analog.com
- **Henry Ott EMC** — http://www.hottconsultants.com

**Books:**
- **"EMC for Product Designers" by Tim Williams**
- **"Electromagnetic Compatibility Engineering" by Henry Ott**

**Tools:**
- **AppCAD** — https://www.broadcom.com/products/appcad (RF calculator)
- **QucsStudio** — https://qucsstudio.de (Free RF simulation)

</details>

---

## 32. Cybersecurity Standards

### 🔐 Top Security Standards

#### **IEC 62443** — Industrial Cybersecurity
https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards

**Standard for securing industrial automation systems**

- ✅ Security Levels (SL 1-4)
- ✅ Covers design, implementation, operation
- ✅ Widely adopted in IIoT, SCADA

---

#### **Common Criteria (ISO/IEC 15408)**
https://www.commoncriteriaportal.org

**International security evaluation standard**

- ✅ Evaluation Assurance Levels (EAL 1-7)
- ✅ Used for cryptographic modules, smart cards, embedded systems
- ✅ Government/military requirements

---

<details>
<summary><b>More Security Standards</b></summary>

**NIST Cybersecurity Framework**
https://www.nist.gov/cyberframework

**GDPR (EU Data Protection)**
https://gdpr.eu

**ETSI EN 303 645** — IoT Security Standard (Europe)
https://www.etsi.org/deliver/etsi_en/303600_303699/303645

**UL 2900** — Cybersecurity for Network-Connectable Products
https://www.ul.com/services/cybersecurity-assurance-program

</details>

---

### 🛠️ Security Tools

<details>
<summary><b>Embedded Security Tools</b></summary>

**Vulnerability Scanners:**
- **Nmap** — https://nmap.org
- **OpenVAS** — https://www.openvas.org

**Firmware Analysis:**
- **Binwalk** — https://github.com/ReFirmLabs/binwalk
- **Firmwalker** — https://github.com/craigz28/firmwalker
- **FACT (Firmware Analysis and Comparison Tool)** — https://fkie-cad.github.io/FACT_core

**Crypto Libraries:**
- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls
- **wolfSSL** — https://www.wolfssl.com
- **tinycrypt** — https://github.com/intel/tinycrypt

</details>

---

## 33. Quality Management Systems

### 🏆 Quality Standards

#### **ISO 9001** — Quality Management
https://www.iso.org/iso-9001-quality-management.html

**Universal quality standard**

- ✅ Process-based approach
- ✅ Continuous improvement
- ✅ Customer focus

---

#### **IATF 16949** — Automotive Quality
https://www.iatfglobaloversight.org

**Automotive industry standard (based on ISO 9001)**

- ✅ Required for automotive suppliers
- ✅ Covers design, production, installation, servicing

---

#### **Automotive SPICE (ASPICE)**
https://www.automotivespice.com

**Process assessment model for automotive software**

- ✅ Capability Levels 0-5
- ✅ Required by major OEMs (VW, BMW, Daimler)
- ✅ Focuses on software development processes

---

<details>
<summary><b>More Quality Standards</b></summary>

**CMMI (Capability Maturity Model Integration)**
https://cmmiinstitute.com

**AS9100** — Aerospace Quality Management

**IPC Standards** (PCB Assembly)
- **IPC-A-610** — Acceptability of Electronic Assemblies
- **IPC-J-STD-001** — Soldering Requirements
- **IPC-7711/7721** — Rework/Repair

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Documentation & Learning](documentation-learning.md)
- [→ Advanced Topics](advanced.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
