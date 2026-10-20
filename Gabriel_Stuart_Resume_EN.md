# **GABRIEL S. STUART**

**Automation, Computer Vision & Systems Simulation Developer**  
Florianópolis, Brazil · [gabrielst13@outlook.com](mailto:gabrielst13@outlook.com) · [utczbr.github.io](https://utczbr.github.io/) · [github.com/utczbr](https://github.com/utczbr) · [linkedin.com/in/gabriel-s-stuart](https://linkedin.com/in/gabriel-s-stuart)

---

Builds end-to-end multiphysics digital twins, industrial process simulators, and automated computer-vision pipelines in Python, C/C++, and Java — coupling first-principles thermodynamic/electrochemical models with cognitive multi-agent systems, discrete-event TSN networks, and statistical validation frameworks tested in clinical-trial data extraction.

---

## **KEY TECHNICAL SKILLS**

- **Languages & Simulation:** Python (3.11+, Numba JIT, Cython), C/C++, Java 17; PEM/SOEC electrolysis & ATR thermodynamics, CoolProp EOS, PEMFC electrochemistry, event-driven & NER engines, gRPC co-simulation
- **Networks & Multi-Agent Systems:** OMNeT++ 6.4 / INET 4.7 (IEEE 802.1Qbv TSN, Scheduled MAC), JaCaMo/Jason (BDI), PROSA/ADACOR, Contract-Net, 2PC, Cooperative A* AMR routing
- **Vision, Validation & DevOps:** OpenCV, YOLO (Detection/Pose), ONNX, PaddleOCR, PROSAC/RANSAC, Lin's CCC, Cohen's Kappa, ECDF, CAPEX/OPEX & LCOH, Pytest, Hypothesis, GitHub Actions, Docker, PyQt6, PCB design

---

## **PROFESSIONAL EXPERIENCE**

### **External Developer (Remote Contractor) — ROGER Renewable Energy**
*11/2025 – 05/2026*

- Developed a dynamic physical simulation proof-of-concept (PoC) for a digital green hydrogen plant balancing PEM and SOEC electrolyzer production under variable load profiles.
- Modeled byproduct oxygen (O₂) recovery from PEM/SOEC stacks to partially fuel an Autothermal Reforming (ATR) unit, coupling mass/energy balances and leading CAPEX/OPEX & LCOH validation.

### **Hardware & Robotics Developer (Builder) — Robota Competition Team (UFSC)**
*07/2022 – 09/2023*

- Designed custom printed circuit boards (PCBs) integrating reflectance sensors, power regulation, and motor drivers, and planned line-follower control trajectories for competitive robotics tournaments.

---

## **FEATURED ENGINEERING PROJECTS**

### **Plot-in & Generator — Clinical Chart Extraction & Synthetic Vision**
[Plot-in](https://github.com/utczbr/Plot-in) · [Generator](https://github.com/utczbr/Generator) · *Python, ONNX, PyQt6*

- Built a vision pipeline (Plot-in) extracting data from PDFs/images across 8 chart types via YOLO detection/pose, PaddleOCR, and PROSAC/RANSAC subpixel calibration; in validation with pharmaceutical professionals extracting clinical-trial data.
- Created a 3-stage synthetic chart generator (Generator) inspecting Matplotlib Agg Artists in memory for pixel-exact boxes and YOLO-pose keypoints; backed by 290+ Pytest/Hypothesis tests, Lin's CCC & Cohen's Kappa validation, and CI/CD installers.

### **h2_plant — Modular Dual-Path Hydrogen Plant Simulator**
[github.com/utczbr/h2_plant](https://github.com/utczbr/h2_plant) · *Python, Numba, PyQt6*

- Engineered a 6-layer event-driven simulator covering PEM/alkaline electrolysis and ATR routes, oxygen buffers, BESS, water treatment, compression, and gas mixing with a YAML topology builder and PyQt6 visual node editor.
- Accelerated thermodynamic evaluations via lookup tables (LUTManager) and Numba JIT compilation, integrating checkpointed FlowTracker conservation checks, OPEX/LCOH techno-economic modeling, and 95%+ Pytest coverage.

### **Matrix_Factory & Matrix-Network — PEMFC & TSN Digital Twin**
[Matrix_Factory](https://github.com/utczbr/Matrix_Factory) · [Matrix-Network](https://github.com/utczbr/Matrix-Network) · *Python, Java, C++*

- Coupled a Numba/Cython Python physics engine with Java 17 (JaCaMo/Jason) PROSA/ADACOR holonic agents over gRPC in Matrix_Factory, modeling 5 PEMFC stations (Kamal-Sourour cure, slot-die coating, 316L stamping wear, VDI 2230 torque, 1D stack polarization) with Contract-Net, Cooperative A* AMR routing, and 30 parallel JVM Monte Carlo instances.
- Built custom C++ OMNeT++ 6.4 / INET 4.7 modules (ScheduledDcf MAC, DeadlineSink) in Matrix-Network and ran a 10,560-run full-factorial campaign across FIFO, 802.1Q, and 802.1Qbv TSN backbones and scheduled wireless access (850 μs State / 560 μs Order slots, 90 ms cycle) to export empirical ECDF latency/loss lookup tables.

---

## **EDUCATION & LANGUAGES**

### **UFSC (Federal University of Santa Catarina) — B.S. in Control and Automation Engineering**
*Expected 2027*

- **Graduate Coursework (PPGEAS/UFSC, 2024–2026):** Completed 7 Master's-level courses as an undergraduate special student: *AI, Concurrency & Real-Time Systems, Renewable Energy Systems, Machine Learning, Mobile Robotics, Linear Dynamic Systems,* and *Multiagent Systems*.

### **Languages**
- **Portuguese:** Native
- **English:** Advanced
