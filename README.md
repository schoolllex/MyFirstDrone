# MyFirstDrone
A custom 3-inch 3D-printed FPV Drone.

## Overview

This project is a lightweight 3-inch FPV drone featuring a 3D-printed frame (PLA+/PETG structure with a TPU canopy) and custom FPV electronics for agile flight and video streaming to a Meta Quest headset or standard FPV goggles.

## Features

- **Flight Controller & ESCs (All-In-One):**
  - **DarwinFPV ELRS AIO F411 15A**: Integrated F4 Flight Controller, 15A 4-in-1 ESC, and SPI ELRS 2.4GHz receiver in a single board.

- **Motors & Propulsion:**
  - **4x 1404 Brushless Motors** (3800KV / 4500KV).
  - **3-inch Props** (HQProp 3016 / Gemfan 3018).

- **FPV Video System:**
  - **Camera:** Caddx Ant Nano (or RunCam Nano 4) analog FPV camera.
  - **Video Transmitter (VTX):** Eachine Nano VTX 5.8GHz (25mW to 400mW adjustable output with SmartAudio/Tramp support).
  - **Goggles / Display:** 5.8GHz UVC Receiver (Skydroid / Eachine ROTG02) plugged into a Meta Quest headset via USB-C or standard FPV goggles.

- **Power & Safety:**
  - **Batteries:** 3S LiPo 650mAh (XT30 connector).
  - **Protection:** 35V 470uF Low-ESR Capacitor to filter voltage spikes and video noise.

- **Frame & Canopy:**
  - **Chassis / Arms:** 3D printed in PETG or PLA+ for optimal rigidity.
  - **Canopy / Mounts:** 3D printed in flexible TPU 95A for crash protection and impact absorption.

---

## Getting Started

1. **Printing the Frame:**
   - Print the base frame and arms in **PETG** or **PLA+** (high infill density, 70–100%).
   - Print the canopy and camera mount in **TPU** (slow print speed, ~30 mm/s).

2. **Assembly & Soldering:**
   - Mount the 1404 brushless motors on the printed arms.
   - Solder the 4 motors to the DarwinFPV AIO FC.
   - Solder the Caddx Ant Nano camera and Eachine VTX to the designated AIO pads.
   - Solder the XT30 pigtail and the 35V 470uF capacitor in parallel to the main power pads.

3. **Configuration:**
   - Plug the AIO board into your PC using a USB cable.
   - Open **Betaflight Configurator** to verify motor directions, accelerometer calibration, and receiver (ELRS) binding.
   - Assign arming and flight mode switches on your **RadioMaster Pocket ELRS** transmitter.

4. **FPV Video Setup on Meta Quest:**
   - Plug the 5.8GHz UVC USB receiver into your Meta Quest's USB-C port.
   - Launch an Android USB Camera app (via SideQuest) or Meta HDMI Link.
   - Power on the drone (3S LiPo), tune the receiver to the VTX channel, and enjoy the flight!

---

![MyFirstDrone](https://halflife.hackclub-assets.com/hackclub-half-life/covers/mj5cMWFuMGw4LFI1frfhyRVjiQ12tH3u/c27b971b1349ed37a88f259fccb96114c7832440ad5205148394606d8fd5488b.png)
