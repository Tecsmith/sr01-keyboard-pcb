# ESP32 Microcontroller Comparison 

| Feature                      | ESP32                    | ESP32-C2                | ESP32-C3                 | ESP32-C6                 | ESP32-S2                  | ESP32-S3                    |
|------------------------------|--------------------------|-------------------------|--------------------------|--------------------------|---------------------------|-----------------------------|
| Core Architecture            | Dual-core Xtensa LX6     | Single-core RISC-V      | Single-core RISC-V       | Single-core RISC-V       | Single-core Xtensa LX7    | Dual-core Xtensa LX7        |
| WiFi Standard                | 802.11 b/g/n             | 802.11 b/g/n            | 802.11 b/g/n             | 802.11 b/g/n/ax          | 802.11 b/g/n              | 802.11 b/g/n                |
| Bluetooth                    | v4.2 (Classic + BLE)     | No                      | BLE only (v5.0)          | BLE only (v5.0)          | No                        | v5.0 (Classic + BLE)        |
| Flash Memory                 | External Flash (varies)  | 4MB (varies by model)   | 4MB (varies by model)    | 4MB (varies by model)    | 4MB (varies by model)     | 4MB (varies by model)       |
| PSRAM Support                | Optional                 | No                      | No                       | No                       | No                        | Yes (varies by model)       |
| GPIO Pins                    | 34                       | 20                      | 22                       | 22                       | 43                        | 45                          |
| USB Support                  | No                       | No                      | Yes (USB-CDC)            | Yes (USB-CDC)            | Yes (USB-OTG)             | Yes (USB-OTG)               |
| CPU Speed                    | 240 MHz                  | 160 MHz                 | 160 MHz                  | 160 MHz                  | 240 MHz                   | 240 MHz                     |
| Security Features            | Secure Boot, Flash Encryption | Secure Boot, Flash Encryption | Secure Boot, Flash Encryption | Secure Boot, Flash Encryption, WPA3 | Secure Boot, Flash Encryption | Secure Boot, Flash Encryption, AES acceleration |
| Ultra-Low Power Mode (ULP)   | Yes                      | Yes                     | Yes                      | Yes                      | Yes                       | Yes                         |
| Temperature Range            | -40°C to 85°C            | -40°C to 125°C          | -40°C to 125°C           | -40°C to 125°C           | -40°C to 85°C             | -40°C to 85°C               |
| Peripherals                  | ADC, DAC, PWM, I2C, SPI, UART | ADC, PWM, I2C, SPI, UART | ADC, PWM, I2C, SPI, UART | ADC, PWM, I2C, SPI, UART | ADC, DAC, PWM, I2C, SPI, UART | ADC, DAC, PWM, I2C, SPI, UART |
| Target Applications          | General IoT, Wearables   | Simple IoT Devices      | Battery-powered IoT Devices | IoT with WiFi 6, Low Power | WiFi Security Cameras, Sensor Nodes | AI Vision, Speech Processing |

### Summary
- **ESP32**:    Dual-core MCU used in various modules like ESP32-WROOM-32, ideal for general-purpose IoT and Bluetooth applications.
- **ESP32-C2**: RISC-V based MCU targeting simple IoT applications, focusing on cost-effectiveness with basic WiFi support.
- **ESP32-C3**: RISC-V based MCU focused on low power and cost-efficiency, great for battery-powered and BLE-only projects.
- **ESP32-C6**: RISC-V based MCU with WiFi 6 support, ideal for modern IoT applications requiring better WiFi performance and security.
- **ESP32-S2**: Single-core MCU with USB-OTG support and lower power consumption, suitable for sensor hubs and security applications.
- **ESP32-S3**: Dual-core MCU with AI capabilities, enhanced GPIO, and support for vision and speech recognition projects.
