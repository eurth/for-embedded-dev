# 🐛 D) Debugging & Testing

> **Complete guide to debugging tools, test frameworks, CI/CD, and quality assurance**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Tools Count | Quick Jump |
|---------|-------------|------------|
| [18. Hardware Test Equipment](#18-hardware-test-equipment) | 40+ | Logic analyzers, oscilloscopes, protocol analyzers |
| [19. Unit Testing](#19-unit-testing--test-frameworks) | 20+ | Unity, Ceedling, GoogleTest, pytest |
| [20. CI/CD & Automation](#20-cicd--build-automation) | 30+ | GitHub Actions, Jenkins, PlatformIO CI |
| [21. Static Analysis](#21-static-analysis--code-quality) | 20+ | Clang-Tidy, Cppcheck, SonarQube |

---

## 🆚 Quick Comparison: Debug Probes

| Probe | Speed | Price | Best For | Interface |
|-------|-------|-------|----------|-----------|
| **J-Link** | Fast | $300-500 | Professional use, ARM | JTAG/SWD |
| **ST-Link** | Medium | $20-30 | STM32 only | SWD |
| **Black Magic Probe** | Medium | $70 | Open-source, hackable | JTAG/SWD |
| **PicoProbe** | Slow | $5 | RP2040, budget | SWD |
| **CMSIS-DAP** | Medium | Varies | Universal, open | SWD |

---

## 18. Hardware Test Equipment

### 🔌 Essential Debug Hardware

#### **Logic Analyzers**

<details>
<summary><b>Top Logic Analyzers</b></summary>

#### **Saleae Logic** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.saleae.com

- ✅ Gold standard for digital protocol debugging
- ✅ 8-channel ($499) to 16-channel ($1,499)
- ✅ Protocol decoders: I²C, SPI, UART, CAN, USB, Ethernet, etc.
- ✅ Excellent software
- ✅ Up to 500 MS/s sampling

**Perfect for**: Professional debugging of any digital protocol

---

**Open-Source Alternatives:**

- **Sigrok/PulseView** — https://sigrok.org  
  `[Platform: Win/Mac/Linux]` `[Status: 🟢Production]`
  - ✅ Open-source logic analyzer software
  - ✅ Supports 100+ devices (fx2lafw, DSLogic, etc.)
  - ✅ Protocol decoders for 150+ protocols
  - ✅ FREE

- **fx2lafw** — https://github.com/sigrokproject/fx2lafw  
  - ✅ Turn $5 Cypress FX2 board into logic analyzer
  - ✅ 24 MS/s, 8 channels
  - ✅ Works with Sigrok

- **DSLogic Plus** — https://www.dreamsourcelab.com  
  - ✅ 400 MS/s, 16 channels, $149
  - ✅ Open hardware, works with Sigrok

</details>

---

#### **Oscilloscopes**

<details>
<summary><b>Top Budget & Mid-Range Scopes</b></summary>

**Handheld:**
- **DSO Nano** — https://www.seeedstudio.com  
  $100, 1 MHz, pocket-sized

**Desktop:**
- **Rigol DS1054Z** — https://www.rigol.com  
  $400, 50 MHz (hackable to 100 MHz), 4 channels, industry favorite for hobbyists

- **Siglent SDS1104X-E** — https://www.siglent.com  
  $400, 100 MHz, 4 channels, excellent value

**High-End:**
- **Keysight DSOX1204G** — $1,500, 200 MHz, professional
- **Rohde & Schwarz RTB2004** — $3,000+, lab-grade

**USB Oscilloscopes:**
- **Analog Discovery 2** — https://digilent.com  
  $279, 2-channel scope + logic analyzer + signal generator

- **PicoScope 2000 Series** — https://www.picotech.com  
  $200-$500, USB scope with excellent software

</details>

---

#### **Protocol Analyzers**

<details>
<summary><b>Specialized Protocol Debugging Tools</b></summary>

**USB:**
- **Beagle USB 480** — https://www.totalphase.com  
  $699, USB 2.0 analyzer
- **OpenVizsla** — https://github.com/openvizsla/ov_ftdi  
  Open-source USB analyzer

**I²C/SPI:**
- **Total Phase Beagle I2C/SPI** — https://www.totalphase.com  
  $399, dedicated I²C/SPI analyzer
- **Bus Pirate** — https://github.com/BusPirate/Bus_Pirate  
  $30, universal protocol debugger (I²C, SPI, UART, 1-Wire)

**CAN:**
- **PCAN-USB** — https://www.peak-system.com  
  $150, CAN bus analyzer
- **CANable** — https://canable.io  
  $30, USB-to-CAN adapter for Linux SocketCAN

**Bluetooth:**
- **nRF Sniffer** — https://www.nordicsemi.com/Products/Development-tools/nRF-Sniffer-for-Bluetooth-LE  
  $10 (nRF52840 Dongle), Wireshark BLE sniffer

**Wi-Fi:**
- **Wireshark** + **Monitor Mode Adapter** — https://www.wireshark.org  
  Free, capture Wi-Fi packets

</details>

---

#### **Power Measurement & Profiling**

<details>
<summary><b>Battery Life Optimization Tools</b></summary>

- **Power Profiler Kit II (PPK2)** — https://www.nordicsemi.com/Products/Development-hardware/Power-Profiler-Kit-2  
  $100, nanoamp to milliamp current measurement

- **Joulescope** — https://www.joulescope.com  
  $700, high-precision power analyzer

- **μCurrent Gold** — https://www.eevblog.com/product/ucurrent  
  $70, ultra-low current measurement

- **INA219/INA226** — I²C current/voltage sensor modules  
  $5, DIY power monitoring

</details>

---

## 19. Unit Testing & Test Frameworks

### 🌟 Top Embedded Test Frameworks

#### **Unity + Ceedling** `[Platform: C]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/ThrowTheSwitch/Unity  
https://github.com/ThrowTheSwitch/Ceedling

**The standard C unit testing framework**

- ✅ Lightweight, designed for embedded
- ✅ Ceedling automates test builds
- ✅ Mocking with CMock
- ✅ Works on host PC or target hardware

**Perfect for**: Professional C firmware testing

---

#### **GoogleTest/GoogleMock** `[Platform: C++]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/google/googletest

**Industry-standard C++ testing**

- ✅ Rich assertions
- ✅ Test fixtures, parameterized tests
- ✅ Mocking framework
- ✅ Works with PlatformIO, CMake

---

#### **Doctest** `[Platform: C++]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://github.com/doctest/doctest

**Lightweight C++ testing (single header)**

- ✅ Faster compile times than GoogleTest
- ✅ Simpler syntax
- ✅ Great for embedded

---

### 📦 More Testing Tools

<details>
<summary><b>Python Testing (for embedded scripts, automation)</b></summary>

- **pytest** — https://pytest.org  
  Standard Python test framework

- **pytest-embedded** — https://github.com/espressif/pytest-embedded  
  Espressif's framework for testing ESP32 firmware

- **Robot Framework** — https://robotframework.org  
  Keyword-driven testing for embedded systems

</details>

<details>
<summary><b>Hardware-in-the-Loop (HIL) Testing</b></summary>

- **Renode** — https://renode.io  
  Simulate entire embedded systems (multi-node networks, sensors, actuators)

- **QEMU** — https://www.qemu.org  
  ARM/RISC-V emulation for running firmware on PC

- **pytest + pySerial** — Automate firmware testing via serial

</details>

<details>
<summary><b>Continuous Testing Tools</b></summary>

- **PlatformIO Test** — https://docs.platformio.org/en/latest/plus/unit-testing.html  
  Built-in test framework for PlatformIO

- **ESP-IDF Unit Test** — https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/unit-tests.html  
  Unity-based testing for ESP32

</details>

---

## 20. CI/CD & Build Automation

### 🌟 Top CI/CD Platforms

#### **GitHub Actions** `[Platform: Cloud]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://github.com/features/actions

**Free CI/CD for public repos**

- ✅ 2,000 minutes/month free
- ✅ PlatformIO, ESP-IDF, STM32CubeIDE support
- ✅ Cross-platform (Linux, Mac, Windows)
- ✅ Artifact storage
- ✅ Matrix builds (test multiple targets)

**Example workflow:**
```yaml
name: PlatformIO CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v3
    - name: Set up Python
      uses: actions/setup-python@v4
    - name: Install PlatformIO
      run: pip install platformio
    - name: Build firmware
      run: platformio run
    - name: Run tests
      run: platformio test
```

---

#### **GitLab CI** `[Platform: Cloud/Self-hosted]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://about.gitlab.com/features/continuous-integration

- ✅ 400 minutes/month free
- ✅ Docker support for custom build environments
- ✅ Self-hosted runners

---

#### **Jenkins** `[Platform: Self-hosted]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.jenkins.io

- ✅ Open-source CI server
- ✅ 1,000+ plugins
- ✅ Full control for private networks

---

### 📦 More CI/CD Tools

<details>
<summary><b>Embedded-Specific CI</b></summary>

- **PlatformIO CI** — https://docs.platformio.org/en/latest/integration/ci/index.html  
  Native support for GitHub, GitLab, Travis, Jenkins

- **ESP-IDF CI** — https://github.com/espressif/esp-idf-ci  
  Espressif's internal CI (public examples)

- **Zephyr CI** — https://github.com/zephyrproject-rtos/zephyr  
  Automated testing via GitHub Actions

</details>

<details>
<summary><b>Build Systems</b></summary>

- **CMake** — https://cmake.org  
  Universal C/C++ build system

- **Make** — Traditional Unix build tool

- **Ninja** — https://ninja-build.org  
  Fast build system (used by PlatformIO, Zephyr)

- **Bazel** — https://bazel.build  
  Google's scalable build system

</details>

---

## 21. Static Analysis & Code Quality

### 🌟 Top Static Analyzers

#### **Clang-Tidy** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://clang.llvm.org/extra/clang-tidy

**LLVM's C++ linter**

- ✅ Finds bugs, style issues, modernization
- ✅ Auto-fixes available
- ✅ Integrates with VS Code, CMake, PlatformIO

---

#### **Cppcheck** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
http://cppcheck.sourceforge.net

**Free static analyzer for C/C++**

- ✅ Detects memory leaks, buffer overflows, null pointers
- ✅ No false positives (conservative)
- ✅ Fast

---

#### **SonarQube** `[Platform: Cloud/Self-hosted]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.sonarqube.org

**Enterprise code quality platform**

- ✅ Supports 20+ languages
- ✅ Security vulnerability detection
- ✅ Code coverage tracking
- ✅ Free for open-source

---

### 📦 More Analysis Tools

<details>
<summary><b>Code Coverage</b></summary>

- **gcov/lcov** — https://gcc.gnu.org/onlinedocs/gcc/Gcov.html  
  GCC code coverage tool

- **Codecov** — https://codecov.io  
  Free for open-source, integrates with CI

- **Coveralls** — https://coveralls.io  
  Free for open-source

</details>

<details>
<summary><b>Security Scanners</b></summary>

- **Coverity** — https://scan.coverity.com  
  Free for open-source, finds security bugs

- **Bandit** — https://github.com/PyCQA/bandit (Python)

- **Semgrep** — https://semgrep.dev  
  Fast, customizable static analysis

</details>

<details>
<summary><b>Linters & Formatters</b></summary>

- **clang-format** — https://clang.llvm.org/docs/ClangFormat.html  
  Auto-format C/C++ code

- **cpplint** — https://github.com/cpplint/cpplint  
  Google C++ style checker

- **shellcheck** — https://www.shellcheck.net  
  Bash script linter

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Connectivity & Networking](connectivity.md)
- [→ Cloud & DevOps](cloud-devops.md)
- [→ Documentation & Learning](documentation-learning.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
