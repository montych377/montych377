# 🚀 Manhwar Hasan — Embedded Systems Developer

<p align="center">
  <img src="https://img.shields.io/badge/Made%20in-India-orange?style=for-the-badge&logo=india" />
  <img src="https://img.shields.io/badge/Bare%20Metal%20Programmer-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MCU-Ninja-blue?style=for-the-badge" />
</p>

### 👨‍💻 Hello World, I’m **Manhwar Hasan**  
Passionate Embedded Systems Developer from 🇮🇳 India, mastering the art of **bare-metal programming** — one register at a time.

---

### 🛠️ MCU Arsenal

| Microcontroller | Mastery Level |
|-----------------|----------------|
| STM32 (HAL & LL) | 🔥🔥🔥🔥🔥 |
| AVR (ATmega, ATtiny) | 🔥🔥🔥🔥 |
| PIC (8-bit / 16-bit) | 🔥🔥🔥🔥 |
| ARM LPC1768 | 🔥🔥🔥🔥🔥 |

---

### 💻 Low-Level Protocols I Tame

| Protocol | Description |
|---------|-------------|
| 🟣 **UART** | Built dozens of interrupt-driven and DMA-based drivers |
| 🔵 **SPI** | Master-slave communication with sensors, displays & flash |
| 🟢 **I2C** | Bit-banging and hardware I2C both implemented |
| 🔴 **CAN** | Industrial-grade communication for automotive |
| 🛰️ **GPS** | Custom NMEA parsing and real-time coordinate tracking |
| 📶 **BLE** | BLE 4.0/5.0 integration for smart devices |
| 📡 **SNMP** | v1/v2/v3 stack integration for networked MCU devices |

---

### 🧠 Bare-Metal Belief System

- ⚡ No RTOS? No Problem.  
- 🪛 I build my own drivers when libraries fall short.  
- 🧩 I write **portable**, **memory-efficient**, and **register-level** code.  
- 🔐 Safety-critical mindset: watchdogs, brown-out detection, interrupts done right.

---

### 🚧 Recent Work

- 🔋 Smart energy monitoring system (STM32 + BLE + GPS + Web server)
- 🚗 CAN-based ECU simulator (LPC1768)
- 🌐 SNMP-managed IOT Gateway
- 📡 GNSS NAVIC tracking unit with custom UI on DGUS screen
- 📱 BLE mesh with mobile app sync

---

### ⚙️ Toolchain & Workflow

| Tool | Usage |
|------|-------|
| **Keil MDK / uVision** | ARM-based development (LPC, STM32) |
| **STM32CubeIDE** | STM32 + CubeMX + HAL/LL |
| **Atmel Studio / MPLAB X** | AVR & PIC |
| **VS Code + PlatformIO** | Cross-platform development |
| **Sigrok / Logic Analyzer** | Protocol sniffing and debugging |
| **DWIN DGUS / Nextion** | Smart display UI programming |
| **Git + GitHub** | Version control like a pro 🧠 |

---

### 🧰 Favorite Dev Stack

```c
// Clean, Efficient, Minimalist
void main(void) {
    Clock_Init();
    GPIO_Init();
    UART_Init();
    while (1) {
        Blink_LED();
        Process_Data();
    }
}
