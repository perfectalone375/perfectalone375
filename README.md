<div align="center">

# Gopi Naga Vignesh Thirupati
### Aerospace & Computational Simulation Software Engineer
#### 3-DoF/6-DoF Dynamics • SGP4 Orbit Propagation • Physics-Informed CFD • AI Model Evaluation (SWE-bench) • MCP Tools

[![GitHub Followers](https://img.shields.io/github/followers/perfectalone375?style=social)](https://github.com/perfectalone375)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/vignesh375)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-3776AB?logo=python&logoColor=white)](https://python.org)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://docker.com)
[![Model Context Protocol](https://img.shields.io/badge/MCP-Protocol%202024--11--05-8A2BE2.svg)](https://modelcontextprotocol.io)

</div>

---

### 👨‍💻 About Me

I am an **Aerospace & Computational Simulation Software Engineer** specializing in translating complex physical dynamics, orbital mechanics, and fluid flows into high-performance, test-driven software and **Model Context Protocol (MCP)** tools. My work enables autonomous AI systems (Claude, Cursor, Antigravity) to reason through and simulate atmospheric flight physics, satellite orbits, aerodynamic surfaces, and propulsion thermodynamics with deterministic precision.

- 🚀 **Core Focus:** Computational flight simulation, physics-informed AI surrogates, and authoring reproducible AI coding benchmarks (SWE-bench).
- 🛠️ **Engineering Stack:** Python (NumPy, SciPy, Matplotlib), C++, TypeScript, Pytest, Docker, GitHub Actions (CI/CD), Linux.
- 📐 **Domain Expertise:** 1976 U.S. Standard Atmosphere (0–86 km), Transonic Drag Divergence, Runge-Kutta (RK4) Solvers, SGP4/J2 Secular Perturbations, Vortex Panel Methods, Squire-Young Viscous Drag, Tsiolkovsky Rocket Propulsion.
- 🤖 **AI Benchmarking:** Designing deterministic fail-to-pass test harnesses and golden patches for LLM code evaluation across differential equations and physical singularities.

---

### 🏛️ Systems & Tooling Architecture

| Category | Technologies & Tools |
|---|---|
| **Languages** | Python 3.10–3.12 (NumPy, SciPy, Matplotlib), C++, TypeScript, Bash, SQL |
| **Software Engineering** | Pytest, Test-Driven Development (TDD), Docker, GitHub Actions, Ruff, Object-Oriented Design |
| **AI & Agent Tooling** | Model Context Protocol (MCP stdio/JSON-RPC), SWE-bench Benchmark Authoring, LLM Evaluation |
| **Aerospace & Flight Physics** | 3-DoF RK4 Trajectory, 1976 US Standard Atmosphere, Transonic Wave Drag Saturation, Parachute Descent |
| **Astrodynamics & Ground** | SGP4/J2 Secular Oblateness, WGS-84 Geodetic, Topocentric SEZ, Ground Station Pass Scheduling, RF Doppler Shift |
| **Computational Fluid Dynamics** | Lumped-Vortex Boundary Panel Method, Thwaites/Head Integral Boundary Layer, Squire-Young Profile Drag |
| **CAD & Mechanical Analysis** | Siemens NX CAD, ANSYS, CATIA, SolidWorks, Geometric Dimensioning & Tolerancing (GD&T) |

---

### 🌟 Featured Flagship Repositories

#### 1. 🔬 [aero-eval-benchmark](https://github.com/perfectalone375/aero-eval-benchmark)
> **Autonomous Evaluation Harness & SWE-bench Style Benchmark for Testing Coding LLMs on Aerospace & Physics Tasks**  
> *Python • SWE-bench Protocol • MCP Server • Multi-Python CI Matrix • MIT Licensed*

* **SWE-bench Standard Architecture:** Curated benchmark challenge matrix testing frontier LLMs on numerical singularities, transonic wave drag discontinuities, and orbital coordinate branch cuts.
* **Isolated Evaluation Harness:** Validates unified diff patches against rigorous fail-to-pass edge case tests while enforcing zero regressions on pass-to-pass baselines.
* **Frontier Model Leaderboard:** Benchmarked performance data for Claude 3.5 Sonnet, GPT-4o, DeepSeek-Coder, and Qwen-2.5-Coder on physical ODEs.
* **MCP Integration:** Exposes `aeroeval_list_tasks`, `aeroeval_get_task_spec`, and `aeroeval_evaluate_patch` for autonomous AI agents.

#### 2. 🌪️ [cfd-airfoil-surrogate](https://github.com/perfectalone375/cfd-airfoil-surrogate)
> **Physics-Informed CFD Aerodynamic Surrogate Model for Instantaneous Pressure ($C_p$) & Polar Curves**  
> *Python • Docker • MCP Server • UIUC Wind Tunnel Validation • 14 Automated Tests • MIT Licensed*

* **Instantaneous Prediction (<2 ms):** Generates chordwise surface pressure distributions ($C_p(x/c)$) and aerodynamic polars ($C_L, C_D, C_M, L/D$) 23,000x faster than 2D OpenFOAM RANS.
* **Vortex Panel Solver:** Enforces boundary flow tangency Neumann conditions with cosine leading-edge clustering and trailing-edge Kutta closure.
* **Integral Boundary Layer:** Couples Thwaites laminar and Schlichting turbulent solvers with Squire-Young profile drag and boundary layer separation stall roll-off.
* **Tooling:** Native `aeroml` CLI, Docker container, and MCP server for direct AI tool calling.

#### 3. 🛰️ [orbital-telemetry-agent](https://github.com/perfectalone375/orbital-telemetry-agent)
> **Autonomous Satellite Orbit Propagator, Ground Station Pass Tracker & Model Context Protocol (MCP) Server**  
> *Python • Docker • Multi-Python CI Matrix • 10 Automated Tests • MIT Licensed*

* **Astrodynamics & J2 Perturbation:** Keplerian orbit propagator modeling Earth oblateness ($J_2 = 1.08263 \times 10^{-3}$), nodal regression ($\dot{\Omega}$), and argument of perigee precession ($\dot{\omega}$).
* **Ground Station Tracking:** Topocentric SEZ coordinate transformation predicting satellite Acquisition of Signal (AOS), Loss of Signal (LOS), max elevation, and pass schedules.
* **RF Doppler Telemetry:** Real-time line-of-sight range rate and RF Doppler frequency shift calculations for satellite radios.
* **MCP Server Integration:** Native JSON-RPC 2.0 tools for Claude Desktop and Cursor to query real-time orbits, ground station passes, and Doppler shifts.

#### 4. 🚀 [aero-flight-dynamics](https://github.com/perfectalone375/aero-flight-dynamics)
> **High-Fidelity 3-DoF Aerospace Simulation Engine & Model Context Protocol (MCP) Server**  
> *Python • Docker • Multi-Python CI Matrix • 33 Automated Tests • MIT Licensed*

* **MCP Server Integration:** Exposes JSON-RPC 2.0 tools for Claude Desktop, Cursor, and AI agents to simulate rocket trajectories, evaluate atmospheric layers, and analyze NACA airfoils.
* **Atmospheric Physics:** Exact 7-layer 1976 U.S. Standard Atmosphere model up to 86,000 meters geopotential altitude with Sutherland dynamic viscosity law.
* **Compressible Aerodynamics:** Prandtl-Glauert subsonic compressibility corrections, Lock/Korn transonic wave drag divergence with non-linear saturation clamping ($C_{D,\text{wave}} \le 0.40$).
* **Numerical Solver:** 4th-order Runge-Kutta (RK4) integrator tracking altitude, Mach number, axial G-load, dynamic pressure (Max-Q), and telemetry data.
* **Dual Recovery Subsystem:** Staged drogue chute deployment at apogee and main canopy inflation for certified safe landing ($v_{\text{touchdown}} < 6.0\text{ m/s}$).

#### 5. 📐 [openengineering-toolkit](https://github.com/perfectalone375/openengineering-toolkit)
> **Transparent, Verified Computational Mechanics, Aerospace Sizing & Rocket Propulsion Library**  
> *Python • FastAPI • CLI • MCP Server • 45 Automated Tests • Multi-Python CI Matrix • MIT Licensed*

* **Rocket Propulsion Analytics:** Tsiolkovsky delta-v, characteristic exhaust velocity $c^*$, nozzle thrust coefficient $C_F$, and total thrust.
* **Fluid Dynamics & Sizing:** Reynolds number regime verification, dynamic pressure $q$, compressible Mach number, and Haaland pipe friction.
* **Structural Solid Mechanics:** Euler-Bernoulli mid-span beam deflection, bending stress, and factor of safety (FoS).
* **Cross-Platform Access:** Exposed via `openeng` CLI, FastAPI REST endpoints, and native MCP stdio server.

---

### 📊 GitHub Dynamic Activity & Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=perfectalone375&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=perfectalone375&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />

</div>

---

### 📫 Connect With Me
* **Email:** [vigneshthirupati2000@gmail.com](mailto:vigneshthirupati2000@gmail.com)
* **LinkedIn:** [linkedin.com/in/vignesh375](https://linkedin.com/in/vignesh375)
* **GitHub Profile:** [github.com/perfectalone375](https://github.com/perfectalone375)
