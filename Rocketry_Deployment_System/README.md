# Orion Deton — Parachute Deployment System (Avionics)

**Role:** Lead PCB & electronics design for Orion Deton (deployment module).  
**Tools / Platform:** Altium Designer (4-layer PCB), ATSAME51 microcontroller, INA238 current monitor, TCAN1046 CAN transceiver.

**Overview**
Orion Deton is the mission-critical module responsible for managing parachute deployment sequences. It communicates over CAN and integrates current sensing and safe actuation channels.

**Highlights**
- Up to four independent actuation channels with redundancy and current monitoring.
- Safety logic implemented on ATSAME51: hardware interlocks, resettable fuses, and status indicators included.
- Validated in lab and in flight: EuRoC 2024 (payload Eros) and Valkyrie (Jul 2025). Full mission success reported.
