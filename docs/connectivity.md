# 🌐 C) Connectivity & Networking

> **Complete guide to wireless protocols, network stacks, IoT platforms, and communication tools**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Tools Count | Quick Jump |
|---------|-------------|------------|
| [14. Wi-Fi & Ethernet](#14-wi-fi--ethernet-tools) | 40+ | ESP-AT, WiFi Manager, Mongoose |
| [15. Bluetooth & BLE](#15-bluetooth--ble) | 50+ | NimBLE, Bleak, nRF Connect |
| [16. LPWAN & Cellular](#16-lpwan-long-range--cellular) | 60+ | LoRaWAN, Sigfox, LTE-M, NB-IoT |
| [17. Industrial Protocols](#17-industrial-protocols--automation) | 30+ | Modbus, CAN, Profinet, EtherCAT |

---

## 🆚 Quick Comparison: IoT Connectivity

| Protocol | Range | Power | Data Rate | Topology | Best For |
|----------|-------|-------|-----------|----------|----------|
| **Wi-Fi** | 50-100m | High | 100+ Mbps | Star | High throughput, power available |
| **BLE** | 10-50m | Very Low | 1-2 Mbps | Star/Mesh | Wearables, sensors, battery |
| **Zigbee** | 10-100m | Low | 250 kbps | Mesh | Smart home, automation |
| **Thread** | 10-100m | Low | 250 kbps | Mesh | Matter, smart home |
| **LoRaWAN** | 2-15km | Very Low | 0.3-50 kbps | Star | Long-range sensors, outdoor |
| **NB-IoT** | 10+ km | Low | 10-100 kbps | Cellular | Remote monitoring, tracking |
| **LTE-M** | 10+ km | Medium | 1 Mbps | Cellular | Asset tracking, voice |
| **Sigfox** | 10-50km | Very Low | 100 bps | Star | Ultra-simple sensors |

---

## 14. Wi-Fi & Ethernet Tools

### 🌟 Top Wi-Fi Libraries & Tools

#### **ESP-AT Firmware** `[Platform: ESP32/ESP8266]` `[Level: Beginner]` `[Status: 🟢Production]`
https://github.com/espressif/esp-at

**Turn ESP32 into Wi-Fi modem with AT commands**

- ✅ Control Wi-Fi from any MCU via UART
- ✅ Pre-built firmware images
- ✅ Custom builds supported
- ✅ TCP/IP, HTTP, MQTT commands

**Perfect for**: Adding Wi-Fi to non-WiFi MCUs without learning ESP-IDF

---

#### **WiFiManager** `[Platform: ESP32/ESP8266]` `[Level: Beginner]` `[Status: 🟢Production]`
https://github.com/tzapu/WiFiManager

**Captive portal for easy Wi-Fi setup**

- ✅ Auto-generates config portal if Wi-Fi fails
- ✅ Users connect via phone/laptop to set SSID/password
- ✅ Save credentials in flash
- ✅ One of the most popular ESP libraries

**Perfect for**: Consumer IoT products needing easy setup

---

#### **Mongoose Networking Library** `[Platform: All MCUs]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://mongoose.ws

**Embedded web server & networking stack**

- ✅ HTTP/HTTPS, WebSocket, MQTT, CoAP
- ✅ Works on ESP32, STM32, RP2040, Linux
- ✅ RESTful APIs, file serving, TLS
- ✅ GPL for open-source, commercial license available

**Perfect for**: Building web interfaces on embedded devices

---

### 📦 Complete Wi-Fi/Ethernet List

<details>
<summary><b>Wi-Fi Libraries & Frameworks</b></summary>

**ESP32-Specific:**
- **ESP-IDF WiFi** — https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_wifi.html
- **ESP-WIFI-MESH** — https://github.com/espressif/esp-mdf
- **ESP-NOW** — Low-latency P2P protocol for ESP
- **ESP-RainMaker** — https://rainmaker.espressif.com (Cloud + app)

**Web Servers:**
- **ESPAsyncWebServer** — https://github.com/me-no-dev/ESPAsyncWebServer
- **WiFiServer** (Built into Arduino)
- **lwIP** — https://savannah.nongnu.org/projects/lwip (TCP/IP stack)

**Ethernet Drivers:**
- **Wiznet W5500** — https://github.com/Wiznet/ioLibrary_Driver
- **ENC28J60** — https://github.com/njh/EtherCard
- **DP83848/LAN8720** — Built into ESP32, STM32 HAL

</details>

<details>
<summary><b>Network Protocol Tools</b></summary>

**DNS/mDNS:**
- **mDNS** — Built into ESP-IDF, Zephyr (Bonjour/Zeroconf)
- **DNSServer** — Built into Arduino

**DHCP:**
- **lwIP DHCP** — Built into most SDKs
- **Azure RTOS NetX DHCP** — https://github.com/azure-rtos/netx

**HTTP Clients:**
- **curl** — https://curl.se (Embedded version available)
- **ESP HTTP Client** — https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/protocols/esp_http_client.html
- **HTTPClient** (Arduino)

</details>

---

## 15. Bluetooth & BLE

### 🌟 Top BLE Stacks

#### **NimBLE** `[Platform: ESP32, nRF, Zephyr]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/apache/mynewt-nimble

**Apache's lightweight BLE stack**

- ✅ Smaller than Bluedroid (ESP32 default)
- ✅ Better power consumption
- ✅ Central/Peripheral/Broadcaster/Observer roles
- ✅ Supports ESP32, nRF, Zephyr
- ✅ Mesh networking support

**Perfect for**: Battery-powered BLE devices on ESP32

---

#### **Bluedroid** `[Platform: ESP32]` (Built into ESP-IDF)

**ESP32's default BLE stack**

- ✅ Classic Bluetooth + BLE
- ✅ Audio profiles (A2DP, HFP)
- ✅ HID, SPP, GATT
- ✅ Mature and stable

---

#### **Zephyr BLE Stack** `[Platform: nRF, STM32WB, ESP32]` `[Status: 🟢Production]`
https://docs.zephyrproject.org/latest/connectivity/bluetooth

**Professional-grade BLE stack**

- ✅ Direction finding (AoA/AoD)
- ✅ BLE Mesh
- ✅ Long-range (Coded PHY)
- ✅ Audio (LE Audio, LC3 codec)

---

### 🛠️ BLE Development Tools

#### **BLE Throughput & Transfer Planner** `[Platform: Browser]` `[Level: Intermediate]` `[Status: 🟢Production]`

https://embeddednote.com/en/tools/ble-throughput-calculator/

**Free BLE GATT throughput and transfer-time estimator**

- ✅ Estimates transfer time using ATT MTU and protocol overhead.
- ✅ Models link-layer fragmentation and PHY airtime.
- ✅ Accounts for connection-event scheduling.
- ✅ Useful for ESP32, IoT, and BLE data transfer planning.
- ⚠️ Results are theoretical estimates, not measured device throughput.

**Perfect for**: Embedded BLE developers planning GATT data transfers.

---
<details>
<summary><b>BLE Testing & Debugging Tools</b></summary>

#### **nRF Connect for Mobile** `[Platform: iOS/Android]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-mobile

- ✅ The standard BLE scanner/debugger
- ✅ Read/write characteristics
- ✅ GATT database explorer
- ✅ Connection parameters tuning
- ✅ Advertising packet analyzer

---

#### **Bluetooth Sniffer Tools**

**nRF Sniffer**
https://www.nordicsemi.com/Products/Development-tools/nRF-Sniffer-for-Bluetooth-LE

- ✅ Capture BLE packets with nRF52840 Dongle
- ✅ Wireshark integration
- ✅ Industry-standard tool

**Alternatives:**
- **Ubertooth** — https://github.com/greatscottgadgets/ubertooth (Open hardware)
- **TI CC2540** — https://www.ti.com/tool/PACKET-SNIFFER

---

#### **BLE Development Libraries**

**Python:**
- **Bleak** — https://github.com/hbldh/bleak (Cross-platform BLE, Python)
- **Bluepy** — https://github.com/IanHarvey/bluepy (Linux BLE, Python)

**JavaScript:**
- **Noble** — https://github.com/abandonware/noble (Node.js BLE)
- **Web Bluetooth API** — https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API

**C/C++:**
- **SimpleBLE** — https://github.com/OpenBluetoothToolbox/SimpleBLE (Cross-platform C++)

</details>

<details>
<summary><b>BLE Services & Profiles</b></summary>

**Standard Profiles:**
- **GATT Services** — https://www.bluetooth.com/specifications/gatt
- **Nordic UART Service (NUS)** — https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/libraries/bluetooth_services/services/nus.html
- **HID over GATT** — Keyboard/mouse emulation

**Custom Profile Tools:**
- **Bluetooth SIG Profile Builder** — https://www.bluetooth.com
- **ESP BLE Examples** — https://github.com/espressif/esp-idf/tree/master/examples/bluetooth

</details>

---

## 16. LPWAN (Long-Range) & Cellular

### 🌟 LoRaWAN

#### **The Things Network (TTN)** `[Platform: Cloud]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.thethingsnetwork.org

**Free LoRaWAN network server**

- ✅ Free for community use
- ✅ Global coverage via community gateways
- ✅ MQTT, HTTP integrations
- ✅ Device management console
- ✅ 10-year battery life possible

**Perfect for**: Building LoRa projects without infrastructure

---

#### **LMIC-Arduino** `[Platform: Arduino]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://github.com/mcci-catena/arduino-lmic

**LoRaWAN MAC-in-C for Arduino**

- ✅ Supports SX1272, SX1276, SX1262
- ✅ Class A/B/C support
- ✅ Works with TTN, ChirpStack, AWS

---

#### **ChirpStack** `[Platform: Self-hosted]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.chirpstack.io

**Open-source LoRaWAN Network Server**

- ✅ Alternative to TTN for private networks
- ✅ MQTT, InfluxDB, PostgreSQL
- ✅ Multi-tenant support

---

### 📡 Other LPWAN Technologies

<details>
<summary><b>Sigfox</b></summary>

#### **Sigfox** `[Platform: Hardware modules]` `[Level: Beginner]` `[Status: 🟢Production]`
https://www.sigfox.com

- ✅ Ultra-simple (no network stack needed)
- ✅ 10-50km range
- ✅ 100 bps data rate
- ✅ Battery lasts 10+ years
- ✅ Global coverage (mostly EU/US)
- ❌ Proprietary, subscription required

**Modules:**
- **Wisol SFM10R** — https://www.digikey.com/en/products/detail/wisol/SFM10R1/6564721
- **LPWAN Click** — https://www.mikroe.com/lpwan-click

</details>

<details>
<summary><b>NB-IoT & LTE-M (Cellular IoT)</b></summary>

#### **NB-IoT / LTE-M Modules**

**Top Modules:**
- **Quectel BG96** — https://www.quectel.com/product/bg96.htm (NB-IoT + LTE-M)
- **u-blox SARA-R5** — https://www.u-blox.com/en/product/sara-r5-series
- **Nordic nRF9160** — https://www.nordicsemi.com/Products/nRF9160 (SiP with modem)

**Development Boards:**
- **nRF9160 DK** — https://www.nordicsemi.com/Products/Development-hardware/nRF9160-DK
- **LTE IoT 2 Click** — https://www.mikroe.com/lte-iot-2-click

**SDKs:**
- **nRF Connect SDK** — https://www.nordicsemi.com/Products/Development-software/nRF-Connect-SDK
- **AT Command Interface** — Most modules use standard AT commands

**Network Operators:**
- **Hologram** — https://www.hologram.io
- **1NCE** — https://1nce.com (Flat-rate IoT SIM)
- **Soracom** — https://soracom.io

</details>

<details>
<summary><b>Other Wireless Protocols</b></summary>

**Zigbee:**
- **Z-Stack** — https://www.ti.com/tool/Z-STACK (TI Zigbee SDK)
- **Zigbee2MQTT** — https://www.zigbee2mqtt.io (Bridge to MQTT)

**Thread:**
- **OpenThread** — https://github.com/openthread/openthread (Google's Thread stack)
- **nRF Connect SDK** — Thread support built-in

**Matter (CHIP):**
- **Project CHIP** — https://github.com/project-chip/connectedhomeip
- **ESP-Matter** — https://github.com/espressif/esp-matter

**6LoWPAN:**
- **Contiki-NG** — https://github.com/contiki-ng/contiki-ng
- **RIOT OS** — https://riot-os.org

**Sub-1 GHz:**
- **TI CC13xx** — https://www.ti.com/wireless-connectivity/sub-1-ghz/overview.html
- **RFM69** — https://github.com/LowPowerLab/RFM69

</details>

---

## 17. Industrial Protocols & Automation

### 🏭 Top Industrial Protocols

#### **Modbus** `[Platform: All MCUs]` `[Level: Intermediate]` `[Status: 🟢Production]`

**The most common industrial protocol**

- ✅ Modbus RTU (RS-485)
- ✅ Modbus TCP (Ethernet)
- ✅ Simple master-slave communication

**Libraries:**
- **libmodbus** — https://libmodbus.org (C library)
- **FreeModbus** — https://github.com/cwalter-at/freemodbus
- **ESP Modbus** — Built into ESP-IDF
- **pyModbusTCP** — https://github.com/sourceperl/pyModbusTCP (Python)

---

#### **CAN Bus** `[Platform: STM32, ESP32-S3, NXP]` `[Level: Intermediate]` `[Status: 🟢Production]`

**Controller Area Network for automotive/industrial**

- ✅ 1 Mbps max
- ✅ Multi-master bus
- ✅ Widely used in vehicles, industrial machines

**Libraries:**
- **ESP32 TWAI** — Built into ESP-IDF (CAN)
- **SocketCAN** — https://www.kernel.org/doc/html/latest/networking/can.html (Linux)
- **python-can** — https://github.com/hardbyte/python-can

**Hardware:**
- **MCP2515** — SPI-to-CAN controller
- **TJA1050/MCP2551** — CAN transceivers

---

<details>
<summary><b>More Industrial Protocols</b></summary>

**Profinet:**
- **P-Net** — https://github.com/rtlabs-com/p-net (Open-source Profinet stack)

**EtherCAT:**
- **SOEM** — https://github.com/OpenEtherCATsociety/SOEM (Simple Open EtherCAT Master)

**EtherNet/IP:**
- **OpENer** — https://github.com/EIPStackGroup/OpENer

**OPC UA:**
- **open62541** — https://open62541.org (Open-source OPC UA)

**MQTT-SN (MQTT for Sensors):**
- **Paho MQTT-SN** — https://github.com/eclipse/paho.mqtt-sn.embedded-c

**DMX512 (Lighting):**
- **esp_dmx** — https://github.com/someweisguy/esp_dmx

**RS-485:**
- **MAX485** — Standard transceiver IC
- **ESP-Modbus** — Built into ESP-IDF

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Firmware & Software](firmware.md)
- [→ Debugging & Testing](debugging-testing.md)
- [→ Cloud & DevOps](cloud-devops.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
