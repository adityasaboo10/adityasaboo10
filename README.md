<div align="center">

# Aditya Saboo

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=650&lines=FPGA%2FRTL+%26+VLSI+Enthusiast;B.Tech+EE+%E2%80%94+IIT+Indore+(2028);Building+AI+%26+Custom+Hardware+Accelerators" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adityasaboo/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adisaboo10@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityasaboo10)

</div>

---

## 👨‍💻 About Me

I design FPGA-based accelerators and digital systems, from pipelined convolution engines and fixed-point datapaths to AXI-based SoC integration. My work focuses on RTL architecture, resource optimization, verification, and hardware-software co-design, with a broader interest in **VLSI and computer architecture**.

- ⚡ **Hardware Acceleration**: Designing convolution engines, fixed-point arithmetic pipelines, and dedicated accelerator cores
- 🔌 **SoC Integration**: Integrating custom RTL using **AXI4-Lite**, **AXI4-Stream**, and **Xilinx AXI DMA**
- ⏱️ **Digital Design**: Working with pipelining, finite-state machines, clock-domain crossing, synthesis, and FPGA resource optimization
- 🔄 **HW/SW Co-Design**: Connecting Python/PYNQ control software and embedded firmware with Verilog RTL accelerators
- 🎓 **Education**: B.Tech. in Electrical Engineering at **IIT Indore** (Class of 2028)
---

## 🚀 Featured Projects

> Hardware architectures, custom RTL pipelines, and embedded control systems I've designed, simulated, and deployed.

### 👁️ [Heterogeneous SoC Vision Accelerator](https://github.com/adityasaboo10/Heterogeneous-SoC-Vision-Accelerator)
**`Verilog` `FPGA` `AXI4-Stream` `AXI4-Lite` `Xilinx AXI DMA` `PYNQ-Z2`**

A signed, pipelined 3×3 convolution accelerator integrated with the ARM processing system on a PYNQ-Z2.

- Achieved **2.26 ms hardware latency** and **8.20 ms end-to-end latency** for a 256×256 image, compared with **53.47 ms** on the ARM Cortex-A9
- Streamed image data between DDR and custom RTL through **Xilinx AXI DMA**, avoiding per-pixel CPU transfers
- Scaled the architecture to **six parallel convolution engines** and demonstrated LeNet-5 inference with Conv1 and Conv2 executed on FPGA and the remaining layers on ARM/Python
- Demonstrated matching digit classification while validating FPGA intermediate outputs against the software implementation

---

### 🤖 [FPGA Maze Explorer Bot — e-Yantra](https://github.com/adityasaboo10/MazeSolver-bot)
**`Verilog` `FPGA` `FSM` `Trémaux Algorithm` `SignalTap`**

A team-built autonomous FPGA maze-exploration robot developed for the e-Yantra Robotics Competition.

- Contributed movement and state-transition logic and integrated the navigation brain with the robot's sensing and actuation modules
- Implemented and tested **wall-following and Trémaux-based navigation**, including maze-memory and backtracking logic
- Integrated swappable navigation modules with a common hardware body through a defined brain-body interface
- Debugged internal FPGA signals on hardware using the **SignalTap Logic Analyzer**

---

### 📐 [Quaternion Accelerator](https://github.com/adityasaboo10/Quaternion-Accelerator)
**`Verilog` `FPGA` `Fixed-Point Arithmetic` `Pipelining` `SPI` `CDC`**

A pipelined FPGA architecture for quaternion multiplication and IMU-based orientation-processing experiments.

- Implemented direct and Hadamard-based quaternion multiplication architectures in Verilog
- Reduced LUT utilization from **3,119 to 1,900**, a **39% reduction**, using a four-stage pipelined Hadamard architecture
- Designed asynchronous FIFO buffering for clock-domain crossing between the Arduino SPI interface and FPGA logic
- Verified the architecture using simulation and IMU-derived input datasets

---

### 🦾 [RAC-01 — Robotic Arm Controller](https://github.com/adityasaboo10/RAC-01_Robotic-Arm-Controller_)
**`C++` `Arduino` `Servo Control` `Embedded Systems`**

An Arduino-based four-servo robotic arm developed for the SSCS Arduino Competition 2025.

- Implemented joystick, mode-selection, Bluetooth, and press-and-play control modes
- Recorded and replayed sequences of servo movements for repetitive tasks
- Added gradual servo-position updates to reduce abrupt mechanical motion
- Designed a separate high-current servo power rail using an 18650 battery pack and buck converter to prevent Arduino brownouts

---

## 🛠️ Tech & Tools

### HDLs & Languages
![Verilog](https://img.shields.io/badge/Verilog-00599C?style=for-the-badge&logo=c&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/-SystemVerilog%20(Learning)-2F74C0?style=for-the-badge)![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Protocols & Architecture
![AXI4](https://img.shields.io/badge/AXI4%20%2F%20AXI--Stream-6366F1?style=for-the-badge&logo=microchip&logoColor=white)
![Xilinx AXI DMA](https://img.shields.io/badge/Xilinx%20AXI%20DMA-4F46E5?style=for-the-badge)
![Pipelined Datapaths](https://img.shields.io/badge/Pipelined%20Datapaths-4338CA?style=for-the-badge&logo=fastapi&logoColor=white)
![FSM Design](https://img.shields.io/badge/FSM%20Design-3730A3?style=for-the-badge&logo=diagram-next&logoColor=white)
![CDC](https://img.shields.io/badge/CDC-312E81?style=for-the-badge&logo=clock&logoColor=white)
![SoC Architecture](https://img.shields.io/badge/SoC%20Architecture-1E1B4B?style=for-the-badge&logo=processor&logoColor=white)
![I2C](https://img.shields.io/badge/I2C-005A9C?style=for-the-badge&logo=circuitverse&logoColor=white)
![UART](https://img.shields.io/badge/UART-003B64?style=for-the-badge&logo=circuitverse&logoColor=white)

### EDA & Hardware Tooling
![Xilinx Vivado](https://img.shields.io/badge/Xilinx%20Vivado-CC0000?style=for-the-badge&logo=xilinx&logoColor=white)
![Intel Quartus Prime](https://img.shields.io/badge/Intel%20Quartus%20Prime-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-005F73?style=for-the-badge&logo=siemens&logoColor=white)
![MATLAB / Simulink](https://img.shields.io/badge/MATLAB%20%2F%20Simulink-ED8B00?style=for-the-badge&logo=mathworks&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-9B1B30?style=for-the-badge&logo=analogdevices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

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
