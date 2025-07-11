# Smart Charging for ESP32 (Tasmota + Berry)

This project provides a Berry Script to enable smart charging cut-off functionality on an ESP32 device running Tasmota firmware.

## Features
- Smart detection of charging start and stop
- Dynamic baseline current analysis
- Debounce and tolerance for fluctuation
- Manual activation via physical button
- Works fully offline (no cloud needed)

## Instructions
1. Flash your ESP32 with Tasmota firmware.
2. Upload this script to the Berry scripting console in Tasmota.
3. Adjust GPIO and thresholds as needed.
4. Press the physical button to begin a smart charging session.

