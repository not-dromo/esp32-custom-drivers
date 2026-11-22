# esp32-custom-drivers

drivers library in C for ESP32 (ESP-IDF) writen from scratch for study purposes

## Hardware
- ESP32 DevKit
- LED + resistor 220 Ω (GPIO 4)

## How to execute
1. Install VScode + PlatformIO
2. Clone this repository
3. `pio run -t upload`
4. `pio device monitor`

## Status
- [x] Step 1: LED blinking with ESP-IDF API
- [ ] Step 2: LED with registers
- [ ] Step 3: button with debounce
- [ ] Step 4: UART
- [ ] Step 5: joystick (ADC)
- [ ] Step 6: OLED (I²C)
- [ ] Step 7: modules and tests