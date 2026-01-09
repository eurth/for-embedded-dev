# ☁️ E) Cloud Platforms & DevOps

> **Complete guide to IoT cloud platforms, DevOps tools, data visualization, and backend services**  
> [← Back to Main](../README.md)

---

## 📋 Quick Navigation

| Section | Tools Count | Quick Jump |
|---------|-------------|------------|
| [22. IoT Cloud Platforms](#22-iot-cloud-platforms--device-management) | 30+ | AWS IoT, Azure IoT, ThingsBoard |
| [23. Data Visualization](#23-data-visualization--dashboards) | 25+ | Grafana, InfluxDB, Node-RED |
| [24. Backend & APIs](#24-backend-services--apis) | 20+ | MQTT brokers, time-series databases |
| [25. DevOps for Embedded](#25-devops-tools-for-embedded) | 15+ | Docker, Ansible, Terraform |

---

## 🆚 Quick Comparison: IoT Cloud Platforms

| Platform | Free Tier | Best For | MQTT | HTTP | Protocols | Learning Curve |
|----------|-----------|----------|------|------|-----------|----------------|
| **AWS IoT Core** | 500K msgs/mo | Enterprise, scalable | ✅ | ✅ | MQTT, HTTPS, LoRaWAN | Steep |
| **Azure IoT Hub** | 8K msgs/day | Enterprise, Microsoft | ✅ | ✅ | MQTT, AMQP, HTTPS | Steep |
| **ThingsBoard** | Unlimited (self-hosted) | Open-source, flexible | ✅ | ✅ | MQTT, CoAP, HTTP | Moderate |
| **Blynk** | Limited devices | Hobbyist, fast prototyping | ✅ | ✅ | Custom | Easy |
| **Adafruit IO** | 30 msgs/min | Hobbyist, simple | ✅ | ✅ | MQTT, HTTP | Easy |
| **ThingSpeak** | 15s update rate | Education, analytics | ❌ | ✅ | HTTP, MQTT | Easy |

---

## 22. IoT Cloud Platforms & Device Management

### 🌟 Top Open-Source Platforms

#### **ThingsBoard** `[Platform: Self-hosted/Cloud]` `[Level: Intermediate→Pro]` `[Status: 🟢Production]`
https://thingsboard.io

**The best open-source IoT platform**

- ✅ Self-hosted (free forever) or managed cloud
- ✅ Device management, dashboards, rules engine
- ✅ MQTT, HTTP, CoAP support
- ✅ Time-series database (Cassandra/PostgreSQL)
- ✅ White-label mobile apps
- ✅ Multi-tenant support

**Perfect for**: Professional IoT products without vendor lock-in

---

#### **Node-RED** `[Platform: Self-hosted]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://nodered.org

**Visual programming for IoT**

- ✅ Drag-and-drop flow-based programming
- ✅ Connect MQTT, HTTP, databases, cloud services
- ✅ 4,000+ community nodes
- ✅ Perfect for prototyping
- ✅ Runs on Raspberry Pi, Docker, cloud

**Perfect for**: Rapid prototyping, automation, data pipelines

---

#### **Home Assistant** `[Platform: Self-hosted]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.home-assistant.io

**Open-source home automation**

- ✅ Integrates 2,000+ devices/services
- ✅ MQTT, Zigbee, Z-Wave, BLE support
- ✅ Powerful automation engine
- ✅ Local control (no cloud required)
- ✅ ESPHome integration

**Perfect for**: Smart home projects, local IoT control

---

### ☁️ Enterprise Cloud Platforms

<details>
<summary><b>AWS IoT Services</b></summary>

#### **AWS IoT Core** `[Platform: Cloud]` `[Level: Pro]` `[Status: 🟢Production]`
https://aws.amazon.com/iot-core

- ✅ Millions of devices supported
- ✅ MQTT, HTTPS, LoRaWAN
- ✅ Device shadows, fleet indexing
- ✅ Rules engine → Lambda, DynamoDB, S3
- ✅ 500,000 messages/month free tier

**Related AWS Services:**
- **AWS IoT Greengrass** — Edge computing runtime
- **AWS IoT Device Management** — Fleet provisioning, OTA updates
- **AWS IoT Analytics** — Data processing/ML
- **AWS IoT SiteWise** — Industrial data collection
- **FreeRTOS+AWS** — https://aws.amazon.com/freertos

</details>

<details>
<summary><b>Microsoft Azure IoT</b></summary>

#### **Azure IoT Hub** `[Platform: Cloud]` `[Level: Pro]` `[Status: 🟢Production]`
https://azure.microsoft.com/en-us/services/iot-hub

- ✅ MQTT, AMQP, HTTPS
- ✅ Device twins, direct methods
- ✅ Integration with Azure services
- ✅ 8,000 messages/day free tier

**Related Azure Services:**
- **Azure IoT Central** — No-code SaaS platform
- **Azure Digital Twins** — 3D modeling/simulation
- **Azure Sphere** — Secure IoT platform (MT3620 chip)

</details>

<details>
<summary><b>Google Cloud IoT</b></summary>

#### **Google Cloud IoT Core** (Retiring Aug 2023)
https://cloud.google.com/iot-core

- ⚠️ **Google is retiring this service**
- Migration path: Use third-party or self-hosted

**Alternatives:**
- ThingsBoard, AWS IoT, Azure IoT
- **Google Cloud Pub/Sub** for messaging

</details>

---

### 🛠️ Hobbyist & Developer Platforms

<details>
<summary><b>Beginner-Friendly Cloud Platforms</b></summary>

#### **Blynk** `[Platform: Cloud]` `[Level: Beginner]` `[Status: 🟢Production]`
https://blynk.io

- ✅ Drag-and-drop mobile app builder
- ✅ Arduino, ESP32, Raspberry Pi libraries
- ✅ Free plan (limited devices)
- ✅ HTTPS, MQTT support

---

#### **Adafruit IO** `[Platform: Cloud]` `[Level: Beginner]` `[Status: 🟢Production]`
https://io.adafruit.com

- ✅ Simple MQTT/HTTP API
- ✅ Dashboards, triggers, webhooks
- ✅ Free: 30 data points/min, 30-day retention
- ✅ Great for learning

---

#### **ThingSpeak** `[Platform: Cloud]` `[Level: Beginner]` `[Status: 🟢Production]`
https://thingspeak.com

- ✅ MATLAB analytics built-in
- ✅ Free: 3M messages/year, 15s update rate
- ✅ HTTP/MQTT API
- ✅ Owned by MathWorks

---

#### **Ubidots** `[Platform: Cloud]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://ubidots.com

- ✅ Education/STEM plan (free)
- ✅ Dashboards, alerts, events
- ✅ LoRaWAN, Sigfox integration

</details>

---

### 🔧 DIY & Self-Hosted Solutions

<details>
<summary><b>Self-Hosted IoT Platforms</b></summary>

- **Kaa IoT Platform** — https://www.kaaproject.org  
  Open-source IoT cloud (self-hosted or cloud)

- **Mainflux** — https://www.mainflux.com  
  Open-source IoT platform (Docker deployment)

- **DeviceHive** — https://devicehive.com  
  Open-source IoT data platform

- **EMQX** — https://www.emqx.io  
  Open-source MQTT broker (see section 24)

</details>

---

## 23. Data Visualization & Dashboards

### 🌟 Top Visualization Tools

#### **Grafana** `[Platform: Self-hosted/Cloud]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://grafana.com

**The standard for time-series dashboards**

- ✅ Beautiful real-time charts
- ✅ Connects to InfluxDB, Prometheus, PostgreSQL, MySQL, etc.
- ✅ Alerting and notifications
- ✅ Free forever (self-hosted)
- ✅ Cloud tier available

**Perfect for**: Professional monitoring dashboards

---

#### **InfluxDB** `[Platform: Self-hosted/Cloud]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://www.influxdata.com

**Time-series database for IoT**

- ✅ Optimized for time-series data
- ✅ SQL-like query language (InfluxQL/Flux)
- ✅ Downsampling, retention policies
- ✅ Free tier available

**Perfect pairing**: InfluxDB (storage) + Grafana (visualization)

---

#### **Node-RED Dashboard** (Built into Node-RED)
https://flows.nodered.org/node/node-red-dashboard

- ✅ Simple drag-and-drop dashboards
- ✅ Gauges, charts, buttons, switches
- ✅ No coding required

---

### 📦 More Dashboard Tools

<details>
<summary><b>Additional Visualization Platforms</b></summary>

- **Freeboard** — https://freeboard.io  
  Simple web-based dashboards

- **Metabase** — https://www.metabase.com  
  Open-source BI tool (SQL databases)

- **Redash** — https://redash.io  
  Open-source data visualization

- **Superset** — https://superset.apache.org  
  Apache's open-source data exploration

</details>

---

## 24. Backend Services & APIs

### 🌐 MQTT Brokers

#### **Mosquitto** `[Platform: Self-hosted]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://mosquitto.org

**The standard open-source MQTT broker**

- ✅ Lightweight, fast
- ✅ TLS support
- ✅ Authentication/ACL
- ✅ Bridge mode (multi-broker)
- ✅ Runs on Raspberry Pi, Linux, Docker

---

#### **EMQX** `[Platform: Self-hosted/Cloud]` `[Level: Intermediate→Pro]` `[Status: 🟢Production]`
https://www.emqx.io

**Scalable MQTT broker**

- ✅ Handles millions of concurrent connections
- ✅ MQTT 3.1.1 + MQTT 5.0
- ✅ WebSocket, CoAP support
- ✅ Rules engine, persistence
- ✅ Free open-source version

---

#### **HiveMQ** `[Platform: Cloud/Self-hosted]` `[Level: Pro]` `[Status: 🟢Production]`
https://www.hivemq.com

**Enterprise MQTT broker**

- ✅ High availability, clustering
- ✅ MQTT 5.0 compliant
- ✅ Free tier available
- ✅ Monitoring dashboards

---

### 🗄️ Time-Series Databases

<details>
<summary><b>Database Options for IoT</b></summary>

**Time-Series:**
- **InfluxDB** (Already covered above)
- **TimescaleDB** — https://www.timescale.com (PostgreSQL extension)
- **Prometheus** — https://prometheus.io (Monitoring + alerting)
- **VictoriaMetrics** — https://victoriametrics.com (Fast, low memory)

**General Databases:**
- **PostgreSQL** — https://www.postgresql.org
- **MongoDB** — https://www.mongodb.com (NoSQL)
- **SQLite** — https://www.sqlite.org (Embedded database)
- **Redis** — https://redis.io (In-memory cache/database)

</details>

---

## 25. DevOps Tools for Embedded

### 🐳 Containerization & Orchestration

#### **Docker** `[Platform: Win/Mac/Linux]` `[Level: Intermediate]` `[Status: 🟢Production]`
https://www.docker.com

**Containerize build environments**

- ✅ Consistent builds across teams
- ✅ PlatformIO, ESP-IDF, Zephyr Docker images available
- ✅ CI/CD friendly

**Example:**
```dockerfile
FROM python:3.9
RUN pip install platformio
WORKDIR /workspace
COPY . .
RUN platformio run
```

---

#### **Portainer** `[Platform: Docker]` `[Level: Beginner→Intermediate]` `[Status: 🟢Production]`
https://www.portainer.io

**Web UI for Docker management**

- ✅ Manage containers via web browser
- ✅ Deploy stacks (Docker Compose)
- ✅ Perfect for Raspberry Pi IoT gateways

---

### 🔧 Configuration Management

<details>
<summary><b>Infrastructure as Code</b></summary>

- **Ansible** — https://www.ansible.com  
  Configuration management for fleets of devices

- **Terraform** — https://www.terraform.io  
  Provision cloud infrastructure (AWS IoT, Azure IoT)

- **Balena** — https://www.balena.io  
  Fleet management for edge devices (Raspberry Pi, etc.)

</details>

---

### 📦 OTA Update Services

<details>
<summary><b>Over-the-Air Update Platforms</b></summary>

- **Mender** — https://mender.io  
  Open-source OTA for Linux devices

- **Balena** — https://www.balena.io  
  Cloud-based OTA for fleets

- **ESP RainMaker** — Built into ESP-IDF  
  OTA for ESP32

- **AWS IoT Jobs** — https://aws.amazon.com/iot-device-management  
  Fleet-wide OTA updates

</details>

---

## 🔗 Related Sections

- [← Back to Main](../README.md)
- [← Debugging & Testing](debugging-testing.md)
- [→ Documentation & Learning](documentation-learning.md)
- [→ Compliance & Standards](compliance.md)

---

<p align="center">
  <sub>Part of the Free Embedded Development Resources • Curated by Eurth Tech</sub>
</p>
