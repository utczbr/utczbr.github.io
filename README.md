# Gabriel S. Stuart

**Automation, Computer Vision & Systems Simulation Developer**  
Florianópolis, Brazil

[![Portfolio](https://img.shields.io/badge/Portfolio-utczbr.github.io-0284c7?style=flat-square&logo=googlechrome&logoColor=white)](https://utczbr.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-utczbr-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/utczbr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gabriel--s--stuart-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabriel-s-stuart)
[![Email](https://img.shields.io/badge/Email-gabrielst13%40outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:gabrielst13@outlook.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-E11D48?style=flat-square&logo=adobeacrobatreader&logoColor=white)](Resume.pdf)

---

## Overview

Builds end-to-end multiphysics digital twins, industrial process simulators, and automated computer-vision pipelines in **Python**, **C/C++**, and **Java** — coupling first-principles thermodynamic/electrochemical models with cognitive multi-agent systems, discrete-event TSN networks, and statistical validation frameworks tested in clinical-trial data extraction.

This repository hosts the source code for my interactive portfolio and system architecture map at **[utczbr.github.io](https://utczbr.github.io/)**, as well as my resume in [Markdown](Gabriel_Stuart_Resume_EN.md) and [PDF](Resume.pdf) formats.

---

## Key Technical Skills

| Domain | Technologies & Core Competencies |
| :--- | :--- |
| **Languages & Simulation** | **Python** (3.11+, Numba JIT, Cython), **C/C++**, **Java 17**; PEM/SOEC electrolysis & ATR thermodynamics, CoolProp EOS, PEMFC electrochemistry, event-driven & NER engines, gRPC co-simulation |
| **Networks & Multi-Agent Systems** | **OMNeT++ 6.4** / **INET 4.7** (IEEE 802.1Qbv TSN, Scheduled MAC), **JaCaMo/Jason** (BDI), PROSA/ADACOR, Contract-Net, Two-Phase Commit (2PC), Cooperative A* AMR routing |
| **Vision, Validation & DevOps** | **OpenCV**, **YOLO** (Detection/Pose), **ONNX**, **PaddleOCR**, PROSAC/RANSAC, Lin's CCC, Cohen's Kappa, ECDF, CAPEX/OPEX & LCOH, **Pytest**, **Hypothesis**, GitHub Actions, Docker, **PyQt6**, PCB design |

---

## Featured Engineering Projects

### [Plot-in](https://github.com/utczbr/Plot-in) & [Generator](https://github.com/utczbr/Generator) — Clinical Chart Extraction & Synthetic Vision
*Python, ONNX, PyQt6, OpenCV, PaddleOCR, Matplotlib Agg, SciPy*

- **Plot-in:** Automated computer-vision pipeline extracting quantitative data from scientific chart images and multi-page PDFs across 8 chart types (bar, line, scatter, box plot, histogram, heatmap, pie, and area) via YOLO detection/pose, PaddleOCR, and PROSAC/RANSAC subpixel axis calibration. Currently in field validation with pharmaceutical professionals for clinical-trial data extraction.
- **Generator:** 3-stage synthetic chart generator inspecting Matplotlib Agg Artists directly in memory to generate pixel-exact bounding boxes, arc-length resampled YOLO-pose keypoints, OCR metadata JSON, and scan-degraded training corpora for Plot-in.
- **Reliability & Delivery:** Backed by 290+ Pytest & Hypothesis property-based tests, Lin's CCC and Cohen's Kappa statistical validation, and cross-platform one-click desktop installers (.bat, .command, .sh) with automated GitHub Actions CI/CD.

### [h2_plant](https://github.com/utczbr/h2_plant) — Modular Dual-Path Hydrogen Plant Simulator
*Python, Numba JIT, CoolProp, PyQt6, PyYAML*

- **Architecture:** Engineered a 6-layer event-driven simulation system covering PEM/alkaline/SOEC electrolysis and autothermal reforming (ATR) routes, byproduct oxygen buffer recovery, BESS, water treatment, compression, and gas mixing.
- **Configurability & UI:** Declarative YAML topology builder and a 79-file PyQt6 P&ID visual node editor allowing full plant assembly without code changes.
- **Performance & Rigor:** Accelerated thermodynamic evaluations via lookup tables (`LUTManager`) and Numba JIT compilation; integrated checkpointed `FlowTracker` mass/energy conservation checks, proprietary OPEX/LCOH techno-economic modeling, and 95%+ Pytest test coverage.

### [Matrix_Factory](https://github.com/utczbr/Matrix_Factory) & [Matrix-Network](https://github.com/utczbr/Matrix-Network) — PEMFC & TSN Digital Twin
*Python, Java 17 (JaCaMo/Jason), C++ (OMNeT++ 6.4 / INET 4.7), gRPC*

- **Multiphysics Co-Simulation:** Coupled a Numba/Cython Python numerical physics engine with Java 17 PROSA/ADACOR holonic agents over gRPC, modeling 5 PEMFC manufacturing stations (Kamal-Sourour cure, slot-die coating, 316L stamping wear, VDI 2230 torque, 1D stack polarization) with Contract-Net negotiation, Cooperative A* AMR routing, and up to 30 parallel JVM Monte Carlo instances.
- **TSN & Wireless Network Study:** Built custom C++ OMNeT++ 6.4 / INET 4.7 modules (`ScheduledDcf` MAC, `DeadlineSink`) in Matrix-Network. Executed a 10,560-run full-factorial campaign across FIFO, 802.1Q, and IEEE 802.1Qbv TSN backbones and scheduled wireless access (850 μs State / 560 μs Order slots, 90 ms cycle) to export empirical ECDF latency and packet loss lookup tables.

---

## Professional Experience

### **External Developer (Remote Contractor) — ROGER Renewable Energy**
*11/2025 – 05/2026*
- Developed a dynamic physical simulation proof-of-concept (PoC) for a digital green hydrogen plant balancing PEM and SOEC electrolyzer production under variable load profiles.
- Modeled byproduct oxygen (O₂) recovery from PEM/SOEC stacks to partially fuel an Autothermal Reforming (ATR) unit, coupling mass/energy balances and leading CAPEX/OPEX & LCOH validation.

### **Hardware & Robotics Developer (Builder) — Robota Competition Team (UFSC)**
*07/2022 – 09/2023*
- Designed custom printed circuit boards (PCBs) integrating reflectance sensors, power regulation, and motor drivers.
- Planned line-follower control trajectories for competitive robotics tournaments.

---

## Education & Academic Background

### **UFSC (Federal University of Santa Catarina)**
**B.S. in Control and Automation Engineering** · *Expected 2027*

#### Graduate Coursework (PPGEAS/UFSC, 2024–2026)
Completed 7 Master's/PhD-level courses as an undergraduate special student in the Graduate Program in Automation and Systems Engineering:
1. **Artificial Intelligence** (Prof. Jomi Fred Hübner) — Search & CSP, knowledge representation, expert systems, and fuzzy logic.
2. **Concurrency & Real-Time Systems** (Prof. Carlos Barros Montez) — Threads, race conditions, deadlock, POSIX/RTOS real-time scheduling (RM, DM, EDF).
3. **Renewable Energy Systems Modeling & Control** (Prof. Marcus V. A. da Costa Filho) — Solar, wind, biomass, green hydrogen microgrids, and optimal load dispatch.
4. **Machine Learning** (Prof. Eric Aislan Antonelo) — Inductive learning, Bayesian networks, neural networks, reinforcement learning, and genetic algorithms.
5. **Mobile Robotics** (Prof. Edson Roberto De Pieri) — Locomotion, sensing, kinematics, navigation, SLAM, and cooperative robotics.
6. **Linear Dynamic Systems** (Prof. Daniel Ferreira Coutinho) — State-space & transfer function representations, controllability/observability, LQR/LQG, and Kalman filtering.
7. **Multiagent Systems** — BDI cognitive architectures (Jason/JaCaMo/CArtAgO), holonic manufacturing (PROSA/ADACOR), Contract-Net, and distributed coordination.

---

## Languages

- **Portuguese:** Native
- **English:** Advanced

---

## Interactive Portfolio Site

The root of this repository serves the live interactive portfolio at **[utczbr.github.io](https://utczbr.github.io/)**, featuring:
- An interactive force-directed graph (D3.js) mapping relationships between systems, engineering layers, domains, and technologies.
- Drill-down software architecture views for all flagship repositories.
- Fast, dependency-light responsive presentation styled with Tailwind CSS.