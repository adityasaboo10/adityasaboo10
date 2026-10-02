<div align="center">

# Aditya Saboo

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=650&lines=FPGA%2FRTL+%26+VLSI+Enthusiast;B.Tech+EE+%E2%80%94+IIT+Indore+(2028);Building+AI+%26+Custom+Hardware+Accelerators" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adityasaboo/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adisaboo10@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityasaboo10)

</div>

---

## 👨‍💻 About Me

I design FPGA accelerators and digital systems, from pipelined convolution engines and fixed-point datapaths to multi-engine CNN architectures and AXI-based SoC integration. My work focuses on RTL architecture, resource-efficient dataflows, hardware validation, and FPGA implementation, with broader interests in **VLSI and computer architecture**.

- ⚡ **Hardware Acceleration**: Building convolution engines, fixed-point arithmetic pipelines, and dedicated accelerator cores
- 🧠 **CNN Acceleration**: Developing layer-reconfigurable FPGA architectures for multi-channel convolution and LeNet-5 inference
- 🔌 **SoC Integration**: Integrating custom RTL using **AXI4-Lite**, **AXI4-Stream**, and **Xilinx AXI DMA**
- ⏱️ **Digital Design**: Working with pipelining, FSMs, clock-domain crossing, line buffering, synthesis, and FPGA resource optimization
- 🔬 **Hardware Validation**: Verifying RTL through simulation, software references and on-chip debugging
- 🎓 **Education**: B.Tech. in Electrical Engineering at **IIT Indore** (Class of 2028)

---

## 🚀 Featured Projects

> Hardware architectures, custom RTL pipelines, and embedded systems I have designed, implemented, and tested.

### 👁️ [Heterogeneous SoC CNN Accelerator](https://github.com/adityasaboo10/Heterogeneous-SoC-CNN-Accelerator)

**`Verilog` `FPGA` `LeNet-5` `AXI4-Stream` `AXI4-Lite` `Xilinx AXI DMA` `PYNQ-Z2`**

A layer-reconfigurable CNN accelerator developed from an earlier signed 2D convolution engine and deployed on the PYNQ-Z2.

- Designed a signed, pipelined 3×3 convolution accelerator with 9 DSP-backed MACs, achieving 2.26 ms latency for 256×256 images.
- Scaled it to six parallel vector engines and 54 DSP-backed MACs for parallel Conv1 filtering and six-channel Conv2 accumulation.
- Implemented **K−1 line buffering**, cutting BRAM use from **12 to 6 (50%)**, LUTs from **4,334 to 3,890 (10.2%)**, and FFs from **5,553 to 5,263**
- Achieved **0.261 ms Conv1** and **4.627 ms Conv2** latency, delivering **49.7× and 47.8× speedups** over ARM Cortex-A9 implementations
- Accelerated all LeNet-5 convolution layers by **47.9×**, completing them in **4.89 ms versus 233.96 ms** on the ARM processor
- Validated end-to-end inference with **bit-exact Conv1 outputs** and matching digit classification

---

### 🤖 [FPGA Maze Explorer Bot — e-Yantra](https://github.com/adityasaboo10/MazeSolver-bot)

**`Verilog` `Cyclone IV` `FSM` `Trémaux Algorithm` `SignalTap`**

A team-built autonomous maze-exploration robot implemented entirely in FPGA logic for the e-Yantra Robotics Competition (2025).

- Owned the movement logic, implementing a **seven-state body FSM** for corridor following, junction traversal, stops, encoder-gated turns, and recovery at **50 MHz**
- Designed the Trémaux navigation brain using an **81×4 directional mark memory** for maze traversal, backtracking, and path selection
- Developed a non-blocking **brain-body handshake** for wall-following and Trémaux modules to share the same movement logic
- Integrated motor, IR, ultrasonic, encoder, PWM, and UART modules and debugged live FPGA behavior using **SignalTap**

---

### 📐 [Quaternion Accelerator](https://github.com/adityasaboo10/Quaternion-Accelerator)

**`Verilog` `FPGA` `Fixed-Point Arithmetic` `Pipelining` `SPI` `CDC`**

A pipelined FPGA architecture for quaternion multiplication using live MPU6050 IMU data.

- Built a Verilog quaternion accelerator using IMU data transmitted over SPI through an Arduino interface
- Implemented a **four-stage pipelined Hadamard architecture**, reducing LUT utilization from **3,119 to 1,900 (39%)**
- Designed asynchronous FIFO buffers for safe clock-domain crossing between the SPI and FPGA domains
- Verified the architecture through RTL simulation and IMU-derived input datasets

---

### 🦾 [RAC-01 — Robotic Arm Controller](https://github.com/adityasaboo10/RAC-01_Robotic-Arm-Controller_)

**`C++` `Arduino` `Bluetooth` `Servo Control` `Embedded Systems`**

A four-degree-of-freedom assistive robotic arm developed for the SSCS Arduino Competition 2025.

- Implemented joystick control, Bluetooth operation, mode selection, and programmable record-and-playback sequences
- Structured the embedded control flow using state-machine-driven firmware
- Added gradual servo-position updates to reduce abrupt mechanical movement
- Designed a separate high-current servo power rail using an 18650 battery pack and MINI560 buck converter to prevent brownouts

---

### ⚡ [DC–DC Boost Converter](https://github.com/adityasaboo10/Boost-Converter)

**`Power Electronics` `TL494` `TC4428A` `IRFZ44N` `Oscilloscope Testing`**

A discrete boost converter designed, assembled, and experimentally tested under different conduction modes.

- Built and tested a **10 V-to-20 V, 1 A** boost converter operating at **5 kHz**
- Implemented PWM control using the TL494, TC4428A gate driver, and IRFZ44N MOSFET
- Validated **continuous and discontinuous conduction modes** using oscilloscope measurements of inductor and diode waveforms
- Experimentally produced DCM operation by increasing the load resistance to **214 Ω**

---

## 🛠️ Tech & Tools

### HDLs & Languages

![Verilog](https://img.shields.io/badge/Verilog-00599C?style=for-the-badge&logo=c&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog%20Fundamentals-2F74C0?style=for-the-badge)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Digital Design & SoC Architecture

![AXI4](https://img.shields.io/badge/AXI4--Lite%20%2F%20AXI4--Stream-6366F1?style=for-the-badge)
![Xilinx AXI DMA](https://img.shields.io/badge/Xilinx%20AXI%20DMA-4F46E5?style=for-the-badge)
![Pipelined Datapaths](https://img.shields.io/badge/Pipelined%20Datapaths-4338CA?style=for-the-badge)
![FSM Design](https://img.shields.io/badge/FSM%20Design-3730A3?style=for-the-badge)
![CDC](https://img.shields.io/badge/Clock%20Domain%20Crossing-312E81?style=for-the-badge)
![Asynchronous FIFOs](https://img.shields.io/badge/Asynchronous%20FIFOs-1E3A8A?style=for-the-badge)
![BRAM and DSP](https://img.shields.io/badge/BRAM%20%26%20DSP%20Optimization-1E1B4B?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-0369A1?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-005A9C?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-003B64?style=for-the-badge)

### EDA & FPGA Tooling

![Xilinx Vivado](https://img.shields.io/badge/Xilinx%20Vivado-CC0000?style=for-the-badge&logo=xilinx&logoColor=white)
![Intel Quartus Prime](https://img.shields.io/badge/Intel%20Quartus%20Prime-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-005F73?style=for-the-badge)
![SignalTap](https://img.shields.io/badge/SignalTap-0068B5?style=for-the-badge&logo=intel&logoColor=white)
![MATLAB / Simulink](https://img.shields.io/badge/MATLAB%20%2F%20Simulink-ED8B00?style=for-the-badge&logo=mathworks&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-9B1B30?style=for-the-badge&logo=analogdevices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Hardware Testing

![Oscilloscope](https://img.shields.io/badge/Oscilloscope-0F766E?style=for-the-badge)
![Logic Analyzer](https://img.shields.io/badge/Logic%20Analyzer-0D9488?style=for-the-badge)
![Vector Network Analyzer](https://img.shields.io/badge/Vector%20Network%20Analyzer-14B8A6?style=for-the-badge)
![Multimeter](https://img.shields.io/badge/Multimeter-2DD4BF?style=for-the-badge)

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=adityasaboo10&show_icons=true&theme=tokyonight&title_color=6366F1&icon_color=6366F1&text_color=94A3B8&bg_color=0D1117&border_color=30363D&hide_border=false&hide_rank=true&count_private=true" alt="Aditya's GitHub Stats" height="165" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=adityasaboo10&layout=compact&theme=tokyonight&title_color=6366F1&text_color=94A3B8&bg_color=0D1117&border_color=30363D&hide_border=false" alt="Top Languages" height="165" />
</div>

---

<div align="center">
  <sub>⚡ <i>"Between RTL and reality, there's only synthesis."</i></sub>
</div>
