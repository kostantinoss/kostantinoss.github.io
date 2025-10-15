---
layout: page
title: Projects
---

## Featured Projects

### STM32F401 Interactive Shell

A comprehensive debugging and monitoring shell for STM32F401 microcontrollers with UART interface, command history, and real-time peripheral monitoring. This advanced embedded systems project demonstrates sophisticated hardware interaction and debugging capabilities.

*Key Features:*
- **Interactive Terminal** - Full command-line interface over UART (115200 baud) with command history and arrow key navigation
- **System Information** - Real-time display of MCU specs, clock frequencies, and HAL version
- **Register Inspection** - Direct register dumps with hex and binary representation for GPIO, UART, and RCC peripherals
- **Hardware Control** - LED control (on/off/toggle) and GPIO state monitoring
- **Memory Efficient** - Only 2.1KB RAM usage (2.12% of 96KB) and 13KB Flash (2.48% of 512KB)
- **Modular Architecture** - Clean separation of shell engine, UART driver, and GPIO driver components
- **Interrupt-Driven** - Non-blocking UART communication with automatic error recovery
- **Educational Focus** - Comprehensive documentation and build instructions for learning embedded systems

*Project Links:*
- [GitHub Repository](https://github.com/kostantinoss/STM32F401-Interactive-Shell)
- [Project Documentation](https://github.com/kostantinoss/STM32F401-Interactive-Shell#readme)

### SysTick Driver

A bare-metal STM32F401RE project demonstrating SysTick peripheral implementation for ARM Cortex-M4 microcontrollers. This educational project showcases direct hardware register manipulation without HAL drivers, focusing on learning the fundamentals of embedded systems timing.

*Key Features:*
- **Bare-Metal Programming** - Pure C implementation without HAL drivers
- **SysTick Peripheral** - Direct ARM Cortex-M4 SysTick register manipulation
- **Educational Focus** - Learn about ARM Cortex-M4 processor timing fundamentals
- **STM32F401RE Target** - Complete project structure with Core, Inc, and Startup files

*Project Links:*
- [GitHub Repository](https://github.com/kostantinoss/SysTick_driver)
- [Project Documentation](https://github.com/kostantinoss/SysTick_driver#readme)

## More Projects Coming Soon

**Upcoming Projects:**
- IoT sensor data collection system
- Local network proxy (Go, Docker)
- Real-time operating system for ARM Cortex-M
- Custom bootloader implementation
- Self hosted local password manager (Go or Rust)
