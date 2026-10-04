# 🛠️ VLSI & Engineering Toolchain

I work across different stages of the semiconductor design flow — from **transistor-level simulation and custom layout to RTL, synthesis, physical design, timing analysis, FPGA implementation and verification.**

---

## 🔬 Analog IC Design & Circuit Simulation

<p align="center">
  <img src="https://img.shields.io/badge/Cadence%20Virtuoso-Analog%20IC-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cadence%20Spectre-Circuit%20Simulation-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LTspice-Circuit%20Simulation-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microwind-CMOS%20Design-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Ngspice-SPICE%20Simulation-green?style=for-the-badge" />
</p>

**Experience / Areas**

`CMOS Design` • `Analog IC` • `6T SRAM` • `Sense Amplifier`
`Flash ADC` • `TIQ` • `Op-Amp` • `Current Mirrors`
`gm/ID` • `PVT Corners` • `Monte Carlo` • `Parasitic Extraction`
`DRC` • `LVS`

---

# 🏭 ASIC / Physical Design Toolchain

<p align="center">
  <img src="https://img.shields.io/badge/OpenLane-RTL--to--GDSII-1f6feb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Yosys-Synthesis-ff6b35?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenROAD-Physical%20Design-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenSTA-STA-8b5cf6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Magic-DRC%2FLVS-555555?style=for-the-badge" />
  <img src="https://img.shields.io/badge/KLayout-Layout-00a896?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cadence%20Innovus-Physical%20Design-red?style=for-the-badge" />
</p>

### 🔄 RTL → GDSII

```text
┌──────────┐
│   RTL    │
└────┬─────┘
     ↓
┌──────────┐
│  Yosys   │
│ Synthesis│
└────┬─────┘
     ↓
┌──────────┐
│ OpenROAD │
│   P&R    │
└────┬─────┘
     ↓
┌──────────┐
│ OpenSTA  │
│   STA    │
└────┬─────┘
     ↓
┌──────────┐
│  Magic   │
│ DRC/LVS  │
└────┬─────┘
     ↓
┌──────────┐
│ KLayout  │
│  GDSII   │
└──────────┘
```

### Physical Design Skills

`Synthesis` • `Floorplanning` • `Power Planning`
`Placement` • `CTS` • `Routing`
`SDC` • `Setup/Hold` • `Clock Skew`
`Critical Path Analysis` • `Timing Closure`
`DRC` • `LVS` • `GDSII`

---

# 💻 RTL Design & Verification

<p align="center">
  <img src="https://img.shields.io/badge/Verilog-HDL-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SystemVerilog-RTL%20%26%20Verification-1f1f1f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Icarus%20Verilog-Simulation-444444?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GTKWave-Waveform%20Analysis-4c8bf5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ModelSim-Simulation-orange?style=for-the-badge" />
</p>

### RTL Concepts

`FSM` • `Pipelining` • `Hazard Detection`
`Data Forwarding` • `CDC` • `Metastability`
`FIFO` • `UART` • `RISC-V RV32I`
`Self-Checking Testbenches` • `Simulation` • `Waveform Debugging`

---

# 🧠 Processor & Digital Design

### RISC-V RV32I

```text
             ┌──────────────┐
             │ Instruction │
             │    Fetch    │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │ Instruction │
             │    Decode   │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │   Execute    │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │    Memory    │
             └──────┬───────┘
                    ↓
             ┌──────────────┐
             │ Write Back   │
             └──────────────┘
```

**Focus:**

`RV32I` • `Pipeline Architecture` • `Hazard Handling`
`Forwarding` • `Branch Flush` • `Timing Closure`

---

# ⚡ FPGA Development

<p align="center">
  <img src="https://img.shields.io/badge/Xilinx-Vivado-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FPGA-Design-6f42c1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ModelSim-FPGA%20Verification-orange?style=for-the-badge" />
</p>

### FPGA Skills

* RTL synthesis
* Constraint definition
* Timing analysis
* FPGA implementation
* Resource utilization analysis
* Timing closure
* Simulation & debugging

⚡ **Achieved 100 MHz timing closure on the RISC-V processor.**

---

# 📡 Communication & Embedded Hardware

<p align="center">
  <img src="https://img.shields.io/badge/UART-RTL%20Design-0066cc?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Arduino%20IDE-Embedded-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP32-Embedded-000000?style=for-the-badge&logo=espressif&logoColor=white" />
</p>

### Areas

`UART` • `SPI` • `I2C` • `GPIO` • `Embedded Systems`
`ESP32` • `Arduino` • `Motor Control` • `Hardware Interfaces`

---

# 🔌 PCB Design & Hardware

<p align="center">
  <img src="https://img.shields.io/badge/KiCad-PCB%20Design-314CB6?style=for-the-badge&logo=kicad&logoColor=white" />
  <img src="https://img.shields.io/badge/Gerber-PCB%20Manufacturing-333333?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PCBWay-Manufacturing-FF6600?style=for-the-badge" />
</p>

### PCB Skills

`Schematic Design` • `PCB Layout` • `2-Layer / 4-Layer PCB`
`Ground Planes` • `Thermal Vias` • `ERC` • `DRC`
`Gerber Generation` • `BOM` • `Pick & Place`
`Power Electronics` • `Motor Driver Interfaces`

---

# 📐 Electromagnetic / RF & Simulation Tools

<p align="center">
  <img src="https://img.shields.io/badge/CST%20Studio%20Suite-EM%20Simulation-0057B8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LTspice-SPICE-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GTKWave-Waveform%20Viewer-4c8bf5?style=for-the-badge" />
</p>

Areas of interest:

`Electromagnetic Simulation` • `Signal Integrity`
`Circuit Simulation` • `Waveform Analysis` • `SPICE`

---

# 🐍 Programming & Development

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,matlab,git,github,vscode&perline=7" />
</p>

### Languages & Tools

**Programming**

`Python` • `C` • `C++` • `MATLAB`

**Development**

`Git` • `GitHub` • `VS Code` • `Linux`

---

# 🧰 Complete Tool Arsenal

| Category                | Tools                                               |
| ----------------------- | --------------------------------------------------- |
| 🔬 Analog IC            | Cadence Virtuoso, Spectre, LTspice, Microwind       |
| 🧠 Digital RTL          | Verilog, SystemVerilog                              |
| 🏭 ASIC                 | OpenLane, Yosys, OpenROAD                           |
| ⏱️ STA                  | OpenSTA, SDC                                        |
| 📐 Layout               | Cadence Virtuoso, KLayout, Magic                    |
| ✅ Physical Verification | DRC, LVS                                            |
| 🖥️ FPGA                | Xilinx Vivado                                       |
| 🧪 Simulation           | ModelSim, Icarus Verilog, GTKWave, Spectre, LTspice |
| 📡 Embedded             | Arduino IDE, ESP32                                  |
| 🔌 PCB                  | KiCad                                               |
| 📡 EM / RF              | CST Studio Suite                                    |
| 💻 Programming          | Python, C, C++, MATLAB                              |
| 🌐 Version Control      | Git, GitHub                                         |
| 🐧 Environment          | Linux / Ubuntu                                      |

---

# 📸 My VLSI Design Flow

<p align="center">

### 🔬 Circuit Design

**Cadence Virtuoso → Spectre → PVT → Monte Carlo**

⬇️

### 🎨 Custom Layout

**Layout → Parasitics → DRC → LVS**

⬇️

### 💻 RTL Design

**Verilog/SystemVerilog → Simulation → Verification**

⬇️

### 🏭 ASIC Physical Design

**Synthesis → Floorplan → Placement → CTS → Routing**

⬇️

### ⏱️ Timing

**SDC → STA → Setup/Hold → Timing Closure**

⬇️

### 📦 Final Implementation

**GDSII → DRC/LVS → KLayout**

</p>

---

# 📊 My Engineering Numbers

<p align="center">

<img src="https://img.shields.io/badge/CPI-8.80%2F10-00AEEF?style=for-the-badge"/>

<img src="https://img.shields.io/badge/SRAM%20SNM-322%20mV-8A2BE2?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Sense%20Amp-220%20ps-FF6600?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Flash%20ADC-1.2%20ns-00A86B?style=for-the-badge"/>

<img src="https://img.shields.io/badge/ADC%20Power-0.8%20mW-E63946?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Parasitic%20Reduction-25%25-6A5ACD?style=for-the-badge"/>

<img src="https://img.shields.io/badge/FPGA%20Timing-100%20MHz-008080?style=for-the-badge"/>

</p>

---

# 🏆 Certifications & Achievements

### Certifications

🎓 Verilog HDL — **Maven Silicon**
🎓 MATLAB — **MathWorks**
🎓 RTL-to-GDSII VLSI Flow
🎓 Analog IC & CMOS Layout

### Achievements

🏆 100-Day Verilog Coding Challenge
🏆 4+ RTL Projects Published
🏆 322 mV SRAM Read SNM
🏆 220 ps Sense-Amplifier Delay
🏆 1.2 ns Flash ADC Delay
🏆 25% Layout Parasitic Reduction

---

# 🎯 Areas I'm Interested In

```text
Physical Design
       │
       ├── Floorplanning
       ├── Placement
       ├── CTS
       ├── Routing
       └── STA
       
Analog IC / Layout
       │
       ├── CMOS
       ├── SRAM
       ├── ADC
       ├── Op-Amp
       └── Custom Layout

RTL / ASIC
       │
       ├── Verilog
       ├── SystemVerilog
       ├── RISC-V
       ├── CDC
       └── Verification
```

---

# 🚀 Currently Learning

* Advanced Physical Design
* Static Timing Analysis
* Clock Tree Synthesis
* IR Drop & EM
* Advanced Analog Layout
* SystemVerilog
* UVM
* ASIC Design Methodologies
* Advanced Verification

---

# 📫 Connect With Me

<p align="center">

<a href="mailto:saurabhswami1166@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/saurabh-swami">
<img src="https://img.shields.io/badge/LinkedIn-Saurabh%20Swami-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/saurabhs84">
<img src="https://img.shields.io/badge/GitHub-saurabhs84-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

---

<p align="center">

## ⚡ Design • Verify • Optimize • Build Silicon

### *Turning ideas into hardware, one transistor and one RTL block at a time.*

</p>
