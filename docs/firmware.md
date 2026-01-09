# ⚙️ B) Firmware & Embedded Software

> **Complete guide to MCU SDKs, RTOS, drivers, debugging tools, and bootloaders**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Tools Count | Quick Jump |
|---------|-------------|------------|
| [8. MCU SDKs & Toolchains](#8-mcu-sdks--toolchains) | 50+ | ESP-IDF, STM32Cube, PlatformIO |
| [9. RTOS](#9-rtos--operating-systems) | 20+ | FreeRTOS, Zephyr, RIOT, Mbed OS |
| [10. Drivers & Middleware](#10-drivers-stacks--middleware) | 100+ | USB, Graphics, Network stacks |
| [11. Debugging](#11-firmware-debugging--reverse-engineering) | 30+ | GDB, OpenOCD, Ghidra, Renode |
| [12. Bootloaders & OTA](#12-bootloaders--ota-update-systems) | 20+ | MCUboot, OpenBLT, ESP OTA |
| [13. Memory & Filesystems](#13-memory--flash--filesystem-utilities) | 25+ | LittleFS, FatFS, Flash tools |

---

## 🆚 Quick Comparison: RTOS

| RTOS | Footprint | Tick Rate | Safety | Best For | License |
|------|-----------|-----------|--------|----------|---------|
| **FreeRTOS** | 9KB | Configurable | ✅ SafeRTOS | General MCU, AWS IoT | MIT |
| **Zephyr** | 50KB+ | 1ms typ | 🟡 In progress | Modern IoT, security | Apache 2.0 |
| **ChibiOS** | 12KB | 1ms | ❌ | STM32, low latency | GPL |
| **RIOT** | 15KB | 1ms | ❌ | 6LoWPAN, IoT | LGPL |
| **Azure RTOS** | 8KB | Configurable | ✅ Certified | STM32, NXP, Renesas | MIT |
| **Mbed OS** | 100KB+ | 1ms | ❌ | Cortex-M, cloud | Apache 2.0 |
| **NuttX** | 50KB+ | 10ms | ❌ | POSIX apps, drones | Apache 2.0 |

---

## 8. MCU SDKs & Toolchains

### 🌟 Top Universal SDKs

#### **PlatformIO** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://platformio.org

**The universal embedded development platform**

- ✅ Supports 1,000+ boards and MCUs
- ✅ Unified build system (Arduino, ESP, STM32, nRF, RISC-V)
- ✅ Library manager with 10,000+ libraries
- ✅ VS Code integration
- ✅ Built-in debugger support
- ✅ Unit testing framework
- ✅ CI/CD friendly

**Perfect for**: Multi-platform projects, modern workflows, professional development  
**Replaces**: Arduino IDE, vendor IDEs for many use cases

---

#### **Zephyr RTOS SDK** `[Platform: Win/Mac/Linux]` `[Level: Intermediate→Pro]` `[Status: 🟢Production]`
https://zephyrproject.org

**Modern, Linux-style RTOS for all MCUs**

- ✅ Supports 500+ boards (STM32, nRF, ESP32, NXP, TI, RISC-V)
- ✅ Device tree configuration
- ✅ Kconfig build system
- ✅ Secure boot, TLS, crypto built-in
- ✅ BLE, Thread, Matter, LoRaWAN stacks
- ✅ Professional-grade testing
- ✅ Long-term support

**Perfect for**: Commercial IoT products, security-critical devices, scalable architecture  
**Used by**: Nordic Semiconductor, NXP, ST, Intel

---

### 🎯 Vendor-Specific SDKs

<details>
<summary><b>ESP32/ESP8266 (Espressif)</b></summary>

#### **ESP-IDF** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/espressif/esp-idf

- ✅ Official ESP32/ESP8266 SDK
- ✅ FreeRTOS included
- ✅ Wi-Fi, BLE, Thread, Matter, Zigbee
- ✅ OTA updates, secure boot, flash encryption
- ✅ Mesh networking (ESP-MESH, ESP-NOW)
- ✅ Excellent documentation

**Also available:**
- **Arduino Core for ESP32** — https://github.com/espressif/arduino-esp32
- **ESP-AT Firmware** — https://github.com/espressif/esp-at (AT command modem)
- **ESP-MDF** — https://github.com/espressif/esp-mdf (Mesh)
- **ESP-RainMaker** — https://github.com/espressif/esp-rainmaker (Cloud SDK)

</details>

<details>
<summary><b>STM32 (STMicroelectronics)</b></summary>

#### **STM32CubeIDE** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.st.com/en/development-tools/stm32cubeide.html

- ✅ Complete IDE for STM32
- ✅ Graphical peripheral configuration (STM32CubeMX)
- ✅ HAL and LL drivers
- ✅ FreeRTOS, Azure RTOS, USB, networking
- ✅ Built-in debugger
- ✅ Eclipse-based, free forever

**Alternatives:**
- **libopencm3** — https://libopencm3.org (Open-source HAL)
- **STM32 Arduino Core** — https://github.com/stm32duino

</details>

<details>
<summary><b>Nordic Semiconductor (nRF52/nRF53)</b></summary>

#### **nRF Connect SDK** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://www.nordicsemi.com/Products/Development-software/nRF-Connect-SDK

- ✅ Based on Zephyr RTOS
- ✅ BLE, Thread, Matter, Zigbee, LTE-M, NB-IoT
- ✅ Secure boot, DFU, power management
- ✅ nRF Cloud integration

</details>

<details>
<summary><b>Raspberry Pi (RP2040)</b></summary>

#### **Pico SDK** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://github.com/raspberrypi/pico-sdk

- ✅ C/C++ SDK for RP2040
- ✅ Dual-core Cortex-M0+
- ✅ USB stack, PIO (programmable I/O)
- ✅ Arduino and MicroPython support
- ✅ Excellent documentation

**Tools:**
- **picotool** — https://github.com/raspberrypi/picotool (CLI flasher)
- **UF2 bootloader** — Drag-and-drop firmware updates

</details>

See [complete vendor SDK list](https://github.com/user/repo) for NXP, TI, Microchip, Renesas, Infineon, Silicon Labs...

---

## 9. RTOS / Operating Systems

### 🌟 Top RTOS Choices

#### **FreeRTOS** `[Platform: All MCUs]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.freertos.org

**The industry-standard real-time kernel**

- ✅ Supports virtually every MCU
- ✅ MIT licensed (truly free)
- ✅ Tiny footprint (9KB Flash, 256B RAM)
- ✅ Preemptive scheduling
- ✅ AWS IoT integration (FreeRTOS+)
- ✅ SafeRTOS available for safety-critical

**Perfect for**: Almost any real-time embedded project  
**Used by**: Millions of devices, every major vendor

---

#### **Zephyr RTOS** (Already covered in SDK section)

---

#### **RIOT OS** `[Platform: ARM, RISC-V, ESP32]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://riot-os.org

**IoT-focused RTOS with 6LoWPAN/CoAP**

- ✅ Ultra-low memory footprint (15KB)
- ✅ Built-in 6LoWPAN, CoAP, RPL
- ✅ POSIX-like API
- ✅ Real-time capabilities

**Perfect for**: Low-power IoT, wireless sensor networks

---

### 📦 More RTOS Options

<details>
<summary><b>Click to expand 15+ additional RTOS</b></summary>

- **Azure RTOS (ThreadX)** — https://github.com/azure-rtos  
  Formerly commercial, now free/open. FileX, NetX, USBX included. Safety certified.

- **Mbed OS** — https://os.mbed.com  
  ARM Cortex-M RTOS with cloud connectivity, TLS, OTA.

- **ChibiOS** — http://chibios.org  
  Tiny RTOS + HAL for STM32, NRF, Kinetis. GPL license.

- **NuttX** — https://nuttx.apache.org  
  POSIX-compliant RTOS for drones, automotive. Powers some PX4 autopilots.

- **Apache Mynewt** — https://mynewt.apache.org  
  BLE-focused RTOS with secure boot and OTA.

- **RT-Thread** — https://www.rt-thread.io  
  POSIX-like RTOS with GUI, networking, filesystem.

- **RTEMS** — https://www.rtems.org  
  Aerospace-grade RTOS used in satellites and spacecraft.

- **Contiki-NG** — https://github.com/contiki-ng/contiki-ng  
  6LoWPAN, RPL, CoAP for ultra-low-power wireless sensor networks.

- **TinyOS** — https://github.com/tinyos/tinyos-main  
  Event-driven OS for wireless sensor networks.

- **Tock OS** — https://www.tockos.org  
  Secure RTOS with memory protection for Cortex-M/RISC-V.

- **embOS (Eval)** — https://www.segger.com/products/rtos/embos  
  Commercial RTOS with free evaluation kits.

</details>

---

## 10. Drivers, Stacks & Middleware

This section covers connectivity stacks, USB, graphics, sensors, filesystems, and more.

### 🌐 Network & IoT Stacks

<details>
<summary><b>TCP/IP Stacks</b></summary>

- **lwIP** — https://savannah.nongnu.org/projects/lwip  
  Lightweight TCP/IP stack for MCUs. Used in ESP32, STM32, FreeRTOS.

- **FreeRTOS+TCP** — https://www.freertos.org/FreeRTOS-Plus/FreeRTOS_Plus_TCP  
  Native TCP/IP for FreeRTOS.

- **Zephyr networking** — Built into Zephyr RTOS

- **Azure RTOS NetX Duo** — https://github.com/azure-rtos/netx  
  IPv4/IPv6 stack with TLS.

</details>

<details>
<summary><b>TLS/Crypto Libraries</b></summary>

- **Mbed TLS** — https://github.com/Mbed-TLS/mbedtls  
  Industry-standard TLS, crypto, X.509 for MCUs.

- **wolfSSL** — https://www.wolfssl.com (Free for open-source)  
  Tiny TLS/crypto library.

- **tinycrypt** — https://github.com/intel/tinycrypt  
  Ultra-small crypto for Cortex-M.

- **micro-ecc** — https://github.com/kmackay/micro-ecc  
  Elliptic curve crypto for BLE and secure boot.

</details>

<details>
<summary><b>MQTT & IoT Protocols</b></summary>

- **ESP-MQTT** — https://github.com/espressif/esp-mqtt  
  MQTT client optimized for ESP32.

- **paho-mqtt-embedded** — https://github.com/eclipse/paho.mqtt.embedded-c  
  MQTT client for constrained devices.

- **Mongoose** — https://mongoose.ws (GPL for open-source)  
  HTTP/MQTT/WebSocket/CoAP stack.

- **libcoap** — https://libcoap.net  
  CoAP protocol implementation.

</details>

### 🔌 USB Stacks

<details>
<summary><b>USB Device Stacks</b></summary>

#### **TinyUSB** `[Platform: Many MCUs]` `[Status: 🟢Production]`
https://github.com/hathach/tinyusb

- ✅ USB Device stack for ESP32-S2/S3, RP2040, STM32, nRF
- ✅ Supports CDC, HID, MSC, MIDI, WebUSB
- ✅ Small footprint, no OS required
- ✅ Widely adopted

**Also:**
- **USBX (Azure RTOS)** — https://github.com/azure-rtos/usbx
- **ChibiOS USB** — Built into ChibiOS
- **LUFA (AVR)** — https://github.com/abcminiuser/lufa

</details>

### 🎨 Graphics & UI Libraries

<details>
<summary><b>Embedded GUI Libraries</b></summary>

#### **LVGL** `[Platform: All MCUs]` `[Status: 🟢Production]`
https://lvgl.io

- ✅ Free embedded GUI library
- ✅ Widgets, animations, input handling
- ✅ Works on ESP32, STM32, RP2040, Zephyr
- ✅ Display drivers for TFT, OLED, ePaper
- ✅ RTOS-friendly

**Also:**
- **uGFX** — https://ugfx.io (Free non-commercial)
- **emWin** — https://www.segger.com/products/user-interface/emwin (Free eval)
- **TouchGFX** — https://www.st.com/en/embedded-software/x-cube-touchgfx.html (Free for STM32)

</details>

### 📦 More Middleware

See [complete middleware list in original README](../README.md) for:
- Audio/Video stacks (ESP-ADF, OpenMAX)
- Sensor drivers (Adafruit, Bosch, ST, InvenSense)
- Display drivers (TFT_eSPI, U8g2, GxEPD2)
- Motor control (SimpleFOC, OpenBLDC)
- DSP libraries (CMSIS-DSP, KissFFT)

---

## 11. Firmware Debugging & Reverse Engineering

### 🌟 Essential Debug Tools

#### **OpenOCD** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
http://openocd.org

**Universal JTAG/SWD debug server**

- ✅ Supports STM32, ESP32, nRF, RISC-V, NXP, TI
- ✅ Works with GDB, VS Code, PlatformIO
- ✅ Flash programming
- ✅ Many debug probes supported

**Perfect for**: Professional debugging on any MCU

---

#### **GDB (GNU Debugger)** `[Platform: Win/Mac/Linux]` `[Level: Intermediate→Pro]` `[Status: 🟢Production]`
https://www.gnu.org/software/gdb

- ✅ Standard debugger for ARM, RISC-V, Xtensa, AVR
- ✅ Breakpoints, watchpoints, stack traces
- ✅ Works with OpenOCD, pyOCD, Black Magic Probe

---

#### **Ghidra** `[Platform: Win/Mac/Linux]` `[Level: Pro]` `[Status: 🟢Production]`
https://ghidra-sre.org

**NSA's open-source reverse engineering suite**

- ✅ Disassembler/decompiler for ARM, RISC-V, AVR, Xtensa
- ✅ Analyze firmware binaries
- ✅ Professional-grade tool

---

### 📦 Complete Debug Tool List

<details>
<summary><b>Click to expand debug probes, simulators, analyzers</b></summary>

**Debug Probes:**
- **Black Magic Probe** — https://github.com/blackmagic-debug/blackmagic
- **pyOCD** — https://github.com/pyocd/pyOCD
- **PicoProbe** — https://github.com/raspberrypi/picoprobe (RP2040 as probe)
- **CMSIS-DAP** — https://github.com/ARMmbed/DAPLink

**Simulators:**
- **Renode** — https://github.com/antmicro/renode (Full system simulation)
- **QEMU** — https://www.qemu.org (ARM, RISC-V emulation)
- **Wokwi** — https://wokwi.com (Cloud MCU simulator)

**Reverse Engineering:**
- **radare2/rizin** — https://github.com/rizinorg/rizin
- **binwalk** — https://github.com/ReFirmLabs/binwalk (Firmware extraction)

</details>

---

## 12. Bootloaders & OTA Update Systems

### 🌟 Top Bootloaders

#### **MCUboot** `[Platform: ARM, ESP32, RISC-V]` `[Status: 🟢Production]`
https://github.com/mcu-tools/mcuboot

**Secure bootloader for embedded devices**

- ✅ Signed firmware images
- ✅ Rollback protection
- ✅ A/B partition updates
- ✅ Works with Zephyr, FreeRTOS, Mbed OS
- ✅ Supports ARM, ESP32, nRF

---

#### **OpenBLT** `[Platform: Many MCUs]` `[Status: 🟢Production]`
https://github.com/feaser/openblt

**Open-source bootloader**

- ✅ Supports STM32, NXP, TI, Renesas, Microchip
- ✅ Update via UART, CAN, USB, SD, RS-485
- ✅ Extensive documentation

---

#### **ESP-IDF OTA** (Built into ESP-IDF)

- ✅ HTTPS OTA updates
- ✅ A/B partition rollback
- ✅ Secure boot + flash encryption

---

### 📦 More Bootloaders

<details>
<summary><b>Click to expand additional bootloaders</b></summary>

**Universal:**
- **UF2 Bootloader** — https://github.com/microsoft/uf2 (Drag-and-drop)
- **TinyUF2** — https://github.com/adafruit/tinyuf2

**Vendor-Specific:**
- **STM32 ROM Bootloader** — Built into every STM32
- **nRF Secure DFU** — https://github.com/NordicSemiconductor
- **DAPBoot** — https://github.com/devanlai/dapboot (STM32 USB DFU)

</details>

---

## 13. Memory / Flash / Filesystem Utilities

### 🌟 Top Filesystems

#### **LittleFS** `[Platform: All MCUs]` `[Status: 🟢Production]`
https://github.com/littlefs-project/littlefs

**Power-loss-safe filesystem for flash**

- ✅ NOR flash optimized
- ✅ Wear leveling
- ✅ Small RAM footprint
- ✅ Used in ESP32, RP2040, nRF, STM32

---

#### **FatFS** `[Platform: All MCUs]` `[Status: 🟢Production]`
http://elm-chan.org/fsw/ff/00index_e.html

**FAT filesystem for SD cards**

- ✅ Long filename support
- ✅ Low memory usage
- ✅ Widely used in embedded systems

---

### 📦 More Filesystem Options

<details>
<summary><b>Click to expand flash/storage tools</b></summary>

**Filesystems:**
- **SPIFFS** — https://github.com/pellepl/spiffs (Small flash)
- **NVS** — Built into ESP-IDF (Key-value storage)
- **UBIFS** — Linux filesystem for NAND flash
- **YAFFS2** — https://yaffs.net (NAND filesystem)

**Flash Tools:**
- **esptool.py** — https://github.com/espressif/esptool (ESP flash)
- **STM32CubeProgrammer** — https://www.st.com (STM32 flash)
- **picotool** — https://github.com/raspberrypi/picotool (RP2040 flash)
- **OpenOCD** — Flash programming for many MCUs

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Hardware Design](hardware-design.md)
- [→ Connectivity & Networking](connectivity.md)
- [→ Debugging & Testing](debugging-testing.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
