# Projects-With-ESP32-SeeedStudio-C3
## Introduction 
> **Seeed Studio XIAO ESP32C3** is an IoT mini development board based on the **Espressif ESP32-C3** WiFi/Bluetooth dual-mode chip, featuring a 32-bit RISC-V CPU that delivers powerful computing performance with its efficient architecture. It has excellent radio frequency performance, supporting IEEE 802.11 b/g/n WiFi, and Bluetooth 5 (BLE) protocols. This board comes included with an external antenna to increase the signal strength for your wireless applications. It also has a small and exquisite form-factor combined with a single-sided surface-mountable design. It is equipped with rich interfaces and has 11 digital I/O that can be used as PWM pins and 4 analog I/O that can be used as ADC pins. It supports four serial interfaces such as UART, I2C and SPI. There is also a small reset button and a bootloader mode button on the board. XIAO ESP32C3 is fully compatible with the Grove Shield for Seeeduino XIAO and Seeeduino XIAO Expansion board except for the Seeeduino XIAO Expansion board, the SWD spring contacts on the board will not be compatible.
> 
  <img width="252" height="320" alt="image" src="https://github.com/user-attachments/assets/2f2be7f9-c68e-4dc0-afd4-3cfbfa5a6d38" />

## Hardware
> This board is based on the ESP32-C3 with 4MB of flash, WiFi and BLE support. It has an USB-C port for programming and debugging, integrated battery charging and an U.FL external antenna connector. It is based on a standard XIAO 14 pin pinout.
> 
## Supported Features

- **Powerful CPU:** ESP32-C3, 32­bit RISC­-V single­core processor that operates at up to 160 MHz
- **Complete Wi­Fi subsystem:** Complies with IEEE 802.11b/g/n protocol and supports Station mode, SoftAP mode, SoftAP + Station mode, and promiscuous mode
- **Bluetooth LE subsystem:** Supports features of Bluetooth 5 and Bluetooth mesh
- **Ultra-Low Power:** Deep sleep power consumption is about 43μA
- **Better RF performance:** External RF antenna included
- **Battery charging chip:** Supports lithium battery charge and discharge management
- **Rich on-chip resources:** 400KB of SRAM, and 4MB of on-board flash memory
- **Ultra small size:** As small as a thumb(21x17.8mm) XIAO series classic form-factor for wearable devices and small projects
- **Reliable security features:** Cryptographic hardware accelerators that support AES-128/256, Hash, RSA, HMAC, digital signature and secure boot
- **Rich interfaces:** 1xI2C, 1xSPI, 2xUART, 11xGPIO(PWM), 4xADC, 1xJTAG bonding pad interface
- Single-sided components, surface mounting design
  
## Connections and IOs

  <img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/803bf47a-e051-434a-b013-5472658b2879" />
  
## Specifications 

## 🛠️ Technical Specifications: Seeed Studio XIAO ESP32-C3

<details>
<summary><b>Click to view detailed Hardware Specs</b></summary>

| Parameter | Description |
| :--- | :--- |
| **Processor** | ESP32-C3 SoC RISC-V single-core 32-bit chip, 160 MHz |
| **Wireless** | 2.4GHz Wi-Fi, BLE 5.0, Bluetooth Mesh |
| **Memory** | 400KB SRAM & 4MB Flash |
| **Interface** | 1x UART, 1x IIC, 1x SPI, 11x GPIO(PWM), 4x ADC |
| **Physical** | 1x Reset button, 1x Boot button |
| **Dimensions** | 21 x 17.8mm |
| **Power (Typ.)** | Max 3.3V Output Current: 500mA |
| **Input Voltage** | VIN: 5V / BAT: 3.7V |
| **Charging** | 380mA (Fast) / 40mA (Trickle) |
| **Temperature** | -40°C ~ 85°C |

</details>

<details>
<summary><b>Click to view Power Consumption Data</b></summary>

| Mode | Wi-Fi Enabled | BLE Enabled |
| :--- | :--- | :--- |
| **Active Mode** | 75 mA | - |
| **Modem-sleep** | 25 mA | 27 mA |
| **Light-sleep** | 4 mA | 10 mA |
| **Deep Sleep** | **44 μA** | - |

> **Note:** Test Condition: BAT Pin Input @ 3.8V | Source Capability: 3A

</details>
