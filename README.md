## STM32F411CEU6 Minimal Dev Board

## 🔌 Features
- **Micro-USB Input** with 3.3V LDO regulator (AMS1117)
- **STM32F411CEU6** (Cortex-M4, 512KB Flash, 128KB RAM)
- **MPU6050 IMU** (6-axis accel + gyro via I2C)
- **25MHz Crystal** for stable system clock
- **SWD Debug Header** for programming/debugging
- **GPIO, UART, SPI, I2C** breakouts for expansion
- **Power + Debug LEDs**
---
## 📁 Repo Structure
hardware/       # Schematics & layout images
README.md       # Project overview
---
## 🛠 Tools
- **IDE**: STM32CubeIDE / PlatformIO  
- **Debugger**: ST-Link V2  
- **PCB Design**: Altium Designer / KiCAD  
---

## 🧪 Quick Start
1. Flash firmware using ST-Link via SWD.
2. Power via USB.
3. Use I2C to communicate with MPU6050 (addr: `0x68`).

