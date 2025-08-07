# Picobug 🪲

An RP2040-based devboard with an integrated picoprobe debugger

## Features 🔧
- USB-C
- Integrated debug probe with UART,* which you can snap off if not needed and use as a separate devboard
- Integrated microSD card reader
- Colour silkscreen to show pin numbers:<img width="1231" height="486" alt="image" src="https://github.com/user-attachments/assets/4ef7062e-cd5c-42ef-9563-ff9181e19fc2" />

- Pin-compatible with the original Pico
- 16MB flash (instead of the default 2MB)**

* Use GPIO16 and 17 for UART instead of the default GPIO0 and 1

** Only the main Pico has 16MB flash, the debugger has 2MB.
