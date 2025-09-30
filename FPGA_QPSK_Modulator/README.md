# QPSK Modulator on FPGA

**Role:** Digital hardware and embedded integration (custom IP, AXI interfaces).  
**Platform / Tools:** Zedboard Zynq-7000, Xilinx Vivado, VHDL, ADAU1761 audio codec, DDS compilers, UART.  

**What I did:** Designed and implemented a modular QPSK modulator IP, integrated with the processing system via AXI, and validated real-time symbol transmission through an audio codec and oscilloscope.

**Highlights**
- Implemented QPSK modulation with phase steps {0, π/2, π, 3π/2}.
- Real-time input via UART (keyboard) and analog output through ADAU1761 codec.
- Simulation in Vivado and lab validation with oscilloscope confirmed expected phase shifts.
