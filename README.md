The Pocket Hydra 🐙⚡

The Pocket Hydra is an all-in-one wireless multi-tool and protocol workstation powered by an ESP8266 NodeMCU. Designed for modularity and portability, it consolidates Wi-Fi intelligence, dual-frequency RF control, Bluetooth Low Energy (BLE) tracking, and Infrared (IR) transceiver capabilities into a single handheld device controlled via a 0.96-inch OLED display and tactile navigation buttons.
🚀 Features

    Visual Boot sequence: Custom 128x64 Nullsec bitmap logo splash screen on startup.

    Wi-Fi Reconnaissance: Scan local airwaves, list SSIDs, and log signal strengths (RSSI).

    Dual-Frequency RF Control: Independent or synchronized control over dual CC1101 modules for multi-band RF transmission/jamming (configured for 433MHz and 315MHz).

    Infrared Toolkit: Capture/read IR signals from standard remotes (NEC, Sony, RC5, RC6) and replay custom signal vectors.

    Bluetooth Low Energy (BLE): Integrated HM-10 module support for broadcasting beacon packets, scanning, and listening to serial data streams.

    Multi-Input Navigation: Local tactile buttons (Next, Prev, Select) plus full remote control via the Serial Monitor interface.

🛠️ Bill of Materials (Hardware Checklist)

    Microcontroller: ESP8266 NodeMCU (ESP-12E)

    Display: 0.96-inch OLED Display (I2C, 4-pin)

    RF Modules: 2x CC1101 Transceiver Modules (SPI)

    BLE Module: HM-10 (or AT-09) Bluetooth Low Energy Module

    IR Hardware:

        VS1838B IR Receiver Module

        IR Transmitter LED + 220Ω current-limiting resistor

    Input Interface: 3x Tactile Push Buttons

    Power: Stable 3.3V power supply rail
