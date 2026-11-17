# Hi, I'm Jason Su 👋

**FPGA / RTL design engineer** · Computer Engineering @ Toronto Metropolitan University

I design digital hardware: RTL in VHDL and Verilog, IP integration in Vivado, and the C++ drivers that sit on top of it. I spent 16 months as an FPGA design engineering co-op at **Evertz Microsystems**, and I'm now looking for **hardware, RTL design and FPGA engineering roles**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jasonsu131-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jasonsu131)
[![Email](https://img.shields.io/badge/Email-jason.su131%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:jason.su131@gmail.com)

---

## 🔧 Experience

**FPGA Design Engineering Intern, Evertz Microsystems** (16-month co-op)

- Integrated and brought up high-speed IP on **AMD/Xilinx Zynq UltraScale+** devices in Vivado, including a runtime-switchable **10G/25G Ethernet** design with **RS-FEC**
- Debugged GT transceiver placement conflicts, MMCM/clocking violations and AXI register-control issues at the IP boundary
- Wrote **C++ driver code** for low-level register control: status, lock detection, error counters and mode switching

## 📌 Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**Cache Controller**](https://github.com/jasonsu131/cache-controller-FPGA-COE758) | Direct-mapped, write-back / write-allocate cache between a CPU and SDRAM model. Handles all four hit/miss cases; timing verified on hardware with ChipScope ILA captures | VHDL · Spartan-3E · ISE · ChipScope |
| [**FPGA Pong (VGA)**](https://github.com/jasonsu131/pong-vga-FPGA-COE758) | Two-player Pong in pure hardware: 640×480 @ 60 Hz VGA, no CPU or frame buffer, per-pixel rendering, LFSR serve, frame-synchronous game logic | VHDL · Spartan-3E · ISE |
| [**HDMI Colour Bars**](https://github.com/jasonsu131/hdmi-colourbars-zynq-fpga) | DVI/HDMI video output from scratch: VGA timing generator, MMCM pixel and 5× serial clocks, TMDS encoding via `rgb2dvi` | Verilog · Zynq-7000 · Vivado |
| [**32-bit RISC CPU**](https://github.com/jasonsu131/coe608) | Multi-cycle 32-bit CPU with a custom 26-instruction ISA: datapath, ALU, FSM control unit, memory, simulated and run on an FPGA | VHDL · Cyclone IV · Quartus · ModelSim |

## 🧰 Skills

**HDL & design:** VHDL, Verilog, FSM design, clock-domain and timing closure, AXI, memory hierarchies, video timing (VGA / DVI / HDMI)
**FPGA tools:** Vivado, Vivado IP Integrator, ILA / ChipScope, Xilinx ISE, Intel Quartus Prime, ModelSim
**Devices:** Zynq UltraScale+ MPSoC, Zynq-7000, Spartan-3E, Cyclone IV
**Interfaces & IP:** 10G/25G Ethernet, RS-FEC, GT transceivers, MMCM/PLL, TMDS
**Software:** C++, C, Python, HCS12 assembly
**Lab:** oscilloscope, logic analyser, board bring-up

## 🚧 Currently

- Final year of Computer Engineering at TMU
- Capstone: an **autonomous indoor delivery robot**. I own the drive platform: chassis, motors, motor drivers and power

---

<sub>Most projects include a full write-up (PDF) with block diagrams, state diagrams and waveform captures.</sub>
