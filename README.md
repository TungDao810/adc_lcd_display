# 🔋 ADC Voltage Display on LCD (AVR ATmega – Wokwi Simulation)

This project reads an analog voltage using the ADC on an ATmega microcontroller and displays the converted voltage value on a 16x2 LCD screen.

## 🎯 Features
- Direct register-level ADC configuration (`ADMUX`, `ADCSRA`)
- LCD control via 4-bit parallel interface
- Real-time voltage display (updated every 1 second)
- Simulated on Wokwi

## 🧰 Tools Used
- AVR ATmega
- 16x2 LCD
- C with avr-libc
- Wokwi Simulator

## 🖥️ Live Simulation
👉 [Run on Wokwi](https://wokwi.com/projects/400914648650467329)

## 📂 File Overview
- `main.ino`: Core program
- `README.md`: Project description

## 📝 Notes
The voltage is sampled via `ADC0` and scaled to simulate analog sensor input. The float value is converted and displayed via `dtostre()` on the LCD.
