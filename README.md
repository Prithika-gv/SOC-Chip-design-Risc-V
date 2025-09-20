# SoC Chip Design Program – Week 0

## 📌 Introduction
This repository documents my learning journey in the **SoC (System-on-Chip) Design Program**.  
The program is focused on understanding the fundamentals of digital design, RISC-V architecture, and the complete RTL-to-GDSII flow using **open-source tools**.  

The goal of this course is to provide hands-on exposure to:
- Digital design using Verilog
- RTL simulation and waveform analysis
- Logic synthesis with Yosys
- Layout and physical design with Magic
- End-to-end flow automation using OpenLANE
- Exposure to open-source EDA ecosystem

This repository will be updated week by week with tasks, notes, and outcomes of each session.

---

## 📖 Task-1: Day-0 Tools Installation Summary

The Day-0 session introduced the environment setup required for the chip design program.  
The focus was on preparing our systems with the correct operating system, dependencies, and EDA tools.  

### 🔹 System Setup
- **OS**: Ubuntu 20.04+ (recommended via VirtualBox for Windows/Mac users)  
- **System Requirements**:  
  - 6 GB RAM  
  - 50 GB Disk space  
  - 4 vCPUs  

### 🔹 Tools Introduced
1. **Yosys** – Open-source logic synthesis  
2. **Icarus Verilog (iverilog)** – Verilog simulation  
3. **GTKWave** – Waveform viewing tool  
4. **Ngspice** – Circuit simulation (analog/mixed-signal)  
5. **Magic** – Layout and design visualization  
6. **OpenLANE** – Complete RTL-to-GDSII flow framework  

### 🔹 Installation Highlights
- Tools like **Icarus Verilog** and **GTKWave** can be installed directly with `apt-get`.  
- **Yosys** and **Magic** are cloned from GitHub and built using `make` and `make install`.  
- **Ngspice** requires downloading the tarball, configuring, compiling, and installing.  
- **OpenLANE** setup involves Docker installation, dependencies check, and cloning the OpenLane repo.

---

## 📝 Key Learnings
- Setting up a proper Linux environment is crucial for chip design workflows.  
- Open-source tools cover the complete design flow from RTL to GDSII.  
- Each tool has its own role — from RTL simulation to physical layout.  
- The program emphasizes **practical, hands-on learning** instead of only theory.  

---

## 🚀 Next Steps
With the environment setup complete, the next stages will involve:
- Writing and simulating Verilog programs  
- Synthesizing RTL with Yosys  
- Exploring layout design with Magic  
- Running OpenLANE flow for a simple SoC design  

This marks the beginning of the journey toward learning **VLSI design using open-source tools**.  

---

📌 *End of Task-1 (Day-0 Summary)*  
