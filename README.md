# VLSI Circuit Design Course Projects

> This collection of course-based VLSI projects focuses on the foundational design, simulation, and analysis of CMOS logic circuits. It includes hands-on modeling of MOS transistors, inverter design, and implementation of basic logic gates such as NAND and NOR using TSMC 0.4µm technology in Cadence Virtuoso.

---

### 📌 **Project Overview**
- **Objective:** To develop a practical understanding of CMOS digital circuit design, emphasizing SPICE modeling, delay optimization, and layout-aware considerations in VLSI systems.
- **Methodology:** The project started with transistor-level SPICE modeling of NMOS and PMOS devices. Device parameters were extracted from DC simulation plots. Using these models, inverters were designed and optimized for speed and power. The project concluded with the implementation and timing analysis of 2-input NAND and NOR gates.

---

### 💡 **Key Features**
- DC IV modeling for both NMOS and PMOS transistors using Cadence Virtuoso  
- Inverter design tuned for minimum propagation delay and optimal noise margins  
- Delay analysis of 2-input NAND and NOR gates under various load capacitances  
- Comparison of simulation results with theoretical expectations  
- Exploration of transistor sizing and its impact on rise/fall times and delay  

---

### 🧰 **Skills Used**
- CMOS SPICE modeling  
- Logic gate delay analysis  
- Transistor sizing and layout planning  
- Schematic capture in Cadence Virtuoso  
- Digital simulation techniques (DC & transient)  

---

### 🧪 **Technologies & Tools**
- Cadence Virtuoso (schematic editor, analog design environment)  
- TSMC 0.4μm PDK  
- DC & Transient Analysis Tools  
- Plot viewer for IV curves, delay comparison  

---

### 🔍 **Key Findings**
- **MOS Characteristics:** Extracted threshold voltage (Vth), saturation current (Idsat), and channel-length modulation for both NMOS and PMOS.  
- **Inverter Optimization:** Achieved sharp transitions and minimal skew by balancing pull-up and pull-down strengths.  
- **Gate Delay:** Observed delays as low as ~30–45 ps depending on transistor sizing and load conditions.  
- **Noise Margins:** Simulated NMH and NML verified against theoretical values.

---

### 🎓 **What I Learned**
- How transistor sizing directly influences the speed and power consumption of logic gates.  
- Importance of input/output capacitance in determining gate delay.  
- Design trade-offs between noise immunity, power, and area.  
- SPICE simulation workflow and interpretation of IV and VTC plots.  
- Practical debugging and simulation convergence challenges in Cadence.

---

### 🚀 **Future Work**
- Implement layout (stick diagrams and full layout) for DRC and LVS verification.  
- Automate gate-level netlist creation and simulate more complex combinational blocks like multiplexers and adders.  
- Perform PVT (Process, Voltage, Temperature) variation analysis.  
- Explore dynamic logic styles (e.g., domino logic) and power gating techniques.  
- Extend design to sequential logic: flip-flops, registers, and FSMs.

---

### 📂 **Files Attached**
- `MOS_IV_NMOS.raw` – NMOS device IV plot (DC simulation)  
- `MOS_IV_PMOS.raw` – PMOS device IV plot  
- `inverter_schematic.dsn` – Cadence schematic of the inverter circuit  
- `nand_gate_sim.raw` – Simulation output of NAND gate  
- `nor_gate_sim.raw` – Simulation output of NOR gate  
- `vlsi_design_report.pdf` – Project documentation covering objectives, designs, waveforms, and findings
