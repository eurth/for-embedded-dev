# 🚀 Quick Reference Cards

> **One-page cheat sheets for common embedded development workflows**

---

## 📋 Table of Contents

1. [MCU Selection Guide](#mcu-selection-guide)
2. [RTOS Quick Start](#rtos-quick-start)
3. [Protocol Cheat Sheet](#protocol-cheat-sheet)
4. [Debug Probe Setup](#debug-probe-setup)
5. [Power Consumption Optimization](#power-consumption-optimization)
6. [PCB Design Checklist](#pcb-design-checklist)
7. [IoT Cloud Platforms](#iot-cloud-platforms)
8. [Compliance Testing](#compliance-testing)

---

## 🎯 MCU Selection Guide

### Decision Tree

```
Need Wireless?
├─ Yes
│  ├─ Wi-Fi → ESP32/ESP8266
│  ├─ BLE → nRF52, ESP32
│  └─ Cellular → nRF9160
│
└─ No
   ├─ Low Power → STM32L, MSP430
   ├─ High Performance → STM32H7, i.MX RT
   ├─ Budget → RP2040, CH32V
   └─ Automotive → STM32, NXP S32K
```

### Popular MCU Families

| MCU | Core | Speed | RAM | Best For | Price |
|-----|------|-------|-----|----------|-------|
| **ESP32-C3** | RISC-V | 160MHz | 400KB | Wi-Fi/BLE IoT | $1 |
| **STM32F4** | Cortex-M4 | 180MHz | 256KB | General purpose | $2-5 |
| **nRF52840** | Cortex-M4 | 64MHz | 256KB | BLE, Thread, Zigbee | $3-5 |
| **RP2040** | Cortex-M0+ | 133MHz | 264KB | Budget, dual-core | $0.70 |
| **STM32L4** | Cortex-M4 | 80MHz | 128KB | Ultra-low-power | $2-4 |
| **STM32H7** | Cortex-M7 | 480MHz | 1MB | High-performance | $8-15 |

---

## 🔄 RTOS Quick Start

### FreeRTOS Task Creation

```c
// Create a task
xTaskCreate(
    vTaskFunction,      // Task function
    "TaskName",         // Task name (debug)
    1000,              // Stack size (words)
    NULL,              // Parameters
    1,                 // Priority (0-configMAX_PRIORITIES)
    &xTaskHandle       // Task handle
);

// Task function template
void vTaskFunction(void *pvParameters) {
    for(;;) {
        // Task code here
        vTaskDelay(pdMS_TO_TICKS(1000)); // Delay 1000ms
    }
}
```

### Zephyr Task Creation

```c
// Define thread
K_THREAD_DEFINE(my_thread, 
    1024,              // Stack size
    my_thread_entry,   // Entry function
    NULL, NULL, NULL,  // Parameters
    5,                 // Priority
    0,                 // Options
    0);                // Delay

void my_thread_entry(void *p1, void *p2, void *p3) {
    while(1) {
        k_sleep(K_MSEC(1000)); // Sleep 1000ms
    }
}
```

---

## 📡 Protocol Cheat Sheet

### UART Configuration

```c
// ESP-IDF
uart_config_t uart_config = {
    .baud_rate = 115200,
    .data_bits = UART_DATA_8_BITS,
    .parity = UART_PARITY_DISABLE,
    .stop_bits = UART_STOP_BITS_1,
    .flow_ctrl = UART_HW_FLOWCTRL_DISABLE
};
uart_param_config(UART_NUM_0, &uart_config);
```

### I²C Quick Reference

| Speed Mode | Frequency | Pull-up Resistor |
|------------|-----------|------------------|
| Standard | 100 kHz | 4.7kΩ - 10kΩ |
| Fast | 400 kHz | 2.2kΩ - 4.7kΩ |
| Fast Plus | 1 MHz | 1kΩ - 2.2kΩ |

**Common I²C Addresses:**
- 0x27, 0x3F: LCD displays
- 0x68: MPU6050 (IMU)
- 0x76, 0x77: BME280 (temp/humidity)
- 0x48-0x4F: ADS1115 (ADC)

### SPI Pin Names

| Signal | Alternative Names | Direction |
|--------|------------------|-----------|
| MOSI | SDI, DI, DIN | Master → Slave |
| MISO | SDO, DO, DOUT | Slave → Master |
| SCK | SCLK, CLK | Master → Slave |
| CS | SS, NSS, CE | Master → Slave |

---

## 🔍 Debug Probe Setup

### OpenOCD Quick Commands

```bash
# Start OpenOCD (STM32)
openocd -f interface/stlink.cfg -f target/stm32f4x.cfg

# Start OpenOCD (ESP32)
openocd -f board/esp32-wrover-kit-3.3v.cfg

# GDB commands
arm-none-eabi-gdb firmware.elf
(gdb) target remote localhost:3333
(gdb) monitor reset halt
(gdb) load
(gdb) continue
```

### Common Debug Interfaces

| Interface | Speed | Pins | Best For |
|-----------|-------|------|----------|
| **SWD** | Fast | 2 (SWDIO, SWCLK) | ARM Cortex-M |
| **JTAG** | Medium | 4-5 (TMS, TCK, TDI, TDO, TRST) | Universal |
| **UART** | Slow | 2 (TX, RX) | Basic debugging |

### Typical SWD Connection

```
MCU          Debug Probe
───────────  ─────────────
SWDIO   ←→   SWDIO
SWCLK   ←─   SWCLK
GND     ─→   GND
3.3V    ←─   VCC (optional)
NRST    ←─   RESET (optional)
```

---

## 🔋 Power Consumption Optimization

### ESP32 Power Modes

| Mode | Current | Use Case |
|------|---------|----------|
| Active (WiFi TX) | 160-260 mA | Data transmission |
| Active (WiFi RX) | 80-120 mA | Data reception |
| Modem Sleep | 15-50 mA | CPU active, WiFi off |
| Light Sleep | 0.8 mA | Wake on GPIO/timer |
| Deep Sleep | 10-150 µA | Wake on timer/ext0/ext1 |
| Hibernation | 5 µA | Wake on GPIO |

### STM32 Low-Power Modes

| Mode | Current | Wakeup Source |
|------|---------|---------------|
| Sleep | ~1 mA | Any interrupt |
| Stop | 2-30 µA | RTC, EXTI, WDG |
| Standby | 0.3-2 µA | RTC, WKUP pin |

### Optimization Checklist

- [ ] Disable unused peripherals
- [ ] Use DMA for data transfers
- [ ] Lower CPU frequency
- [ ] Enable sleep modes between tasks
- [ ] Use hardware timers instead of busy-wait
- [ ] Disable debug interfaces in production
- [ ] Use external RTC for deep sleep
- [ ] Add 100nF decoupling caps near ICs

---

## 🎨 PCB Design Checklist

### Pre-Layout

- [ ] Schematic reviewed and approved
- [ ] All components have footprints
- [ ] Power tree calculated (current draw)
- [ ] Decoupling caps added (0.1µF near ICs)
- [ ] Pull-up/pull-down resistors on inputs
- [ ] ESD protection on exposed connectors

### Layout

- [ ] Board size fits enclosure
- [ ] Component placement (hot parts away from sensors)
- [ ] Power traces wide enough (use online calculator)
- [ ] Ground plane on layer 2 (or solid pour)
- [ ] High-speed signals: short, matched length
- [ ] Crystal traces: short, shielded
- [ ] RF traces: 50Ω impedance
- [ ] Mounting holes placed
- [ ] Silkscreen labels readable

### Pre-Manufacturing

- [ ] Design Rule Check (DRC) passed
- [ ] Electrical Rule Check (ERC) passed
- [ ] 3D view checked for clearances
- [ ] Gerbers generated (RS-274X format)
- [ ] Drill files exported (Excellon format)
- [ ] BOM exported (CSV with manufacturer PNs)
- [ ] Assembly drawing created

---

## ☁️ IoT Cloud Platforms

### Quick Setup: ThingsBoard

1. **Install ThingsBoard** (Docker):
   ```bash
   docker run -d -p 9090:9090 --name tb thingsboard/tb-postgres
   ```

2. **Create Device**:
   - Login → Devices → Add Device
   - Copy Access Token

3. **Publish Data** (MQTT):
   ```bash
   mosquitto_pub -h THINGSBOARD_HOST -t v1/devices/me/telemetry \
     -u ACCESS_TOKEN -m '{"temperature":25.5}'
   ```

4. **ESP32 Code**:
   ```cpp
   #include <WiFi.h>
   #include <PubSubClient.h>
   
   WiFiClient espClient;
   PubSubClient client(espClient);
   
   void setup() {
     WiFi.begin("SSID", "password");
     client.setServer("THINGSBOARD_IP", 1883);
   }
   
   void loop() {
     String payload = "{\"temperature\":" + String(25.5) + "}";
     client.publish("v1/devices/me/telemetry", payload.c_str());
     delay(5000);
   }
   ```

### Quick Setup: AWS IoT Core

```bash
# 1. Create thing
aws iot create-thing --thing-name MyDevice

# 2. Create certificate
aws iot create-keys-and-certificate --set-as-active \
  --certificate-pem-outfile cert.pem \
  --public-key-outfile public.key \
  --private-key-outfile private.key

# 3. Attach policy to certificate
aws iot attach-policy --policy-name MyPolicy --target CERT_ARN
```

---

## ✅ Compliance Testing

### FCC Part 15B (Unintentional Radiators)

**Required Tests:**
- Radiated emissions (30 MHz - 1 GHz)
- Conducted emissions (150 kHz - 30 MHz)

**Limits (Class B, 3m):**
- 30-88 MHz: 100 µV/m
- 88-216 MHz: 150 µV/m
- 216-960 MHz: 200 µV/m

### CE Marking (EMC Directive)

**Required Standards:**
- EN 55032: Emissions
- EN 55035: Immunity
- EN 61000-4-2: ESD immunity
- EN 61000-4-3: Radiated immunity

### Pre-Compliance Tools

- **Near-field probe** ($50-200)
- **Spectrum analyzer** (or RTL-SDR $30)
- **EMC calculator** (online, free)
- **Ferrite beads** on high-speed signals
- **Shielded enclosure** (if applicable)

---

## 🔗 Quick Links

- [← Back to Main](../README.md)
- [Hardware Design](hardware-design.md)
- [Firmware Development](firmware.md)
- [Connectivity](connectivity.md)
- [Debugging & Testing](debugging-testing.md)
- [Cloud & DevOps](cloud-devops.md)
- [Compliance](compliance.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
