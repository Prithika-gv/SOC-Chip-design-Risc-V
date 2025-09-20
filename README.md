# RISC-V Reference SoC Tapeout Program
**Week 0 Assignment**

**Name:** PRITHIKA G  
**University:** Chennai Institute of Technology  
**Program:** RISC-V Reference SoC Tapeout Program  
**Week:** 0

---

## 1. Getting Started with Digital VLSI SoC Design
This week, I explored the fundamentals of digital VLSI (Very Large Scale Integration) and System-on-Chip (SoC) design. I learned that an SoC integrates multiple components, such as processors, memory, and peripheral interfaces, into a single chip. This integration improves performance, reduces power consumption, and enhances overall system efficiency.

I also reviewed the key steps in an SoC project lifecycle, including:

- **Specification:** Defining design goals, features, and performance targets.  
- **Architecture Design:** Planning processor cores, memory hierarchy, and peripheral interfaces.  
- **RTL Design & Verification:** Developing hardware descriptions using Verilog and verifying functionality.  
- **Physical Design & Tapeout:** Converting the verified design into a manufacturable chip layout.

Understanding these stages gave me a strong foundation for the upcoming practical exercises.

---

## 2. Tool Installation and Setup
As part of Week 0, I installed and configured all the essential tools required for RISC-V SoC development:

- **Git:** Installed and configured for version control and GitHub submissions.  
- **Docker:** Set up to enable isolated and reproducible development environments.  
- **Yosys:** Installed for RTL synthesis.  
- **OpenROAD/OpenLane:** Configured for automated physical design and layout tasks.  
- **iverilog:** Set up for simulation and verification of Verilog code.  
- **RISC-V GNU Toolchain:** Installed for compiling and running RISC-V programs.

The installation process was smooth, with minor environment variable configurations resolved using official documentation and support forums. After completing the setup, all tools were verified to be functioning correctly.

---

## 3. RISC-V ISA Overview
RISC-V is an open-source instruction set architecture (ISA) known for its simplicity, modularity, and extensibility. Unlike proprietary ISAs, RISC-V allows designers to implement custom extensions for specific applications. Its key features include:

- Minimal and clean base instruction set for efficient hardware implementation.  
- Modular design that supports custom extensions.  
- Open-source availability that promotes innovation and collaboration in SoC development.

I explored the RISC-V instruction set and learned how it provides flexibility while maintaining a simple architecture for hardware designers.

---

## 4. “Hello, World!” RTL Simulation
As my first practical exercise, I executed a simple “Hello, World!” simulation using iverilog with the provided testbench. The simulation ran successfully and produced the expected output.

**Sample Output Log:**

Hello, World!

Simulation finished.

This confirmed that my development environment was correctly configured and ready for more advanced RTL and SoC experiments.

---

## 5. Week 0 Reflections
The Week 0 activities provided a solid introduction to digital VLSI, SoC design, and the RISC-V ecosystem. Completing the tool installations and running my first RTL simulation helped me gain confidence in the setup and workflow.

I am now well-prepared to dive deeper into RTL design, synthesis, verification, and physical design in the coming weeks.

---

## 6. Submission
All required files, logs, and this summary have been added to the `week0` folder in my GitHub repository for review.

I am excited to continue my learning journey in the RISC-V Reference SoC Tapeout Program!
