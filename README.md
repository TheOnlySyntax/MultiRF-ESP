# MultiRF Marauder: Universal Radio Hacking and Analysis Tool

**MultiRF Marauder** is an all-in-one tool designed for analyzing and testing radio networks. With support for multiple frequency bands, including Wi-Fi, Bluetooth, and sub-GHz, this device is ideal for **ethical hacking**, **penetration testing**, and **radio frequency analysis**.

## Features

### 1. **Wi-Fi Analysis (Wi-Fi Marauder)**
- **Deauthentication Attacks (DeAuth)**: Perform attacks on Wi-Fi networks, disconnecting devices from the network.
- **Packet Sniffing**: Capture and analyze Wi-Fi packets to identify security weaknesses.
- **Probing**: Detect nearby Wi-Fi networks and devices.
- **Wi-Fi Network Information**: Display details about access points, such as SSID, MAC address, channel, and encryption type.

### 2. **Bluetooth Analysis (Bluetooth Marauder)**
- **Bluetooth Scanning**: Scan for Bluetooth (including BLE) devices.
- **Bluetooth Spoofing**: Change device addresses for security testing.
- **Bluetooth Jamming**: Create interference in the 2.4 GHz band to test Bluetooth and other devices.

### 3. **Sub-GHz RF Analysis (Sub-GHz Marauder)**
- **Sub-GHz Signal Analysis**: Detect and analyze radio signals in the 315 MHz, 433 MHz, 868 MHz, and 915 MHz frequency bands.
- **Sub-GHz Packet Sniffing**: Capture packets for analysis of communication in sub-GHz bands (e.g., remote controls, IoT devices).
- **Replay Attacks**: Replay captured packets to test the security of devices.

### 4. **User Interface (UI)**
- **OLED Display**: A small screen for displaying information such as Wi-Fi networks, Bluetooth devices, or sub-GHz signals.
- **Button Navigation**: Buttons for navigating through menus and selecting test options.

### 5. **Power and Portability**
- **Battery-powered**: Uses a rechargeable Li-Po or 18650 battery for portability.
- **Low Power Consumption**: Optimized design for long-lasting field use.

### 6. **Versatile Communication**
- **Multiple RF Modules**: Supports **ESP32** (Wi-Fi, Bluetooth), **CC1101** (Sub-GHz), and **nRF24L01+** (2.4 GHz), allowing comprehensive radio frequency analysis.

## Hardware Components

- **ESP32** (Main MCU for Wi-Fi and Bluetooth communication)
- **CC1101** (Sub-GHz RF module)
- **nRF24L01+** (2.4 GHz RF module)
- **OLED Display** (128x64, I2C/SPI)
- **Li-Po or 18650 Battery** (for portable power)
- **TP4056 Charging Module** (for battery charging)
- **AMS1117 Voltage Regulator** (for 3.3V regulation)
- **Buttons** (for navigation)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/MultiRF-Marauder.git
