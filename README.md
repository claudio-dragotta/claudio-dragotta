<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1d3a,50:1e3a8a,100:06b6d4&height=200&section=header&text=Claudio%20Dragotta&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Quantum%20Computing%20%C2%B7%20Machine%20Learning%20%C2%B7%20Intelligent%20Systems&descSize=16&descAlignY=58" width="100%"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=06B6D4&center=true&vCenter=true&width=720&lines=MSc+Intelligent+Systems+Engineering+%E2%80%94+110%2F110+cum+laude;Shor's+algorithm+under+noise+%7C+Quantum+Error+Correction;Machine+Learning+%7C+Robotics+%7C+Distributed+Systems;Open+to+work+%E2%80%94+Italy+%26+abroad" alt="Typing SVG"/></a>

<p>
  <a href="https://www.linkedin.com/in/claudio-dragotta-04096334b"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:claudiodragotta@gmail.com"><img src="https://img.shields.io/badge/Email-claudiodragotta%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://shor-demo-6knp.onrender.com/"><img src="https://img.shields.io/badge/Live%20demo-Shor%20Lab-06B6D4?style=flat-square&logo=qiskit&logoColor=white" alt="Shor demo"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Rome%2C%20Italy-1E3A8A?style=flat-square&logo=googlemaps&logoColor=white" alt="Rome"/>
</p>

</div>

## About me

```yaml
name:      Claudio Dragotta
role:      Engineer — Quantum Computing & Machine Learning
degree:    MSc Intelligent Systems Engineering, Università Campus Bio-Medico di Roma
           graduated Oct 2026 · 110/110 cum laude
thesis:    "Shor's Algorithm under Noise: Machine-Learning Ablation,
            Quantum Error Correction, and Approximate QFT"
focus:     [quantum error correction, noisy quantum simulation, machine learning,
            robotics, distributed systems]
languages: { Italian: native, English: B2, German: B2 }
status:    open to work — Italy, Germany and abroad
```

I started from a **classical–German double diploma** and moved into engineering: that mix of
humanities and hard science shapes how I work — rigorous on method, careful with claims, and
able to explain a technical result to a non-technical audience.

---

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### ⚛️ [Shor on NISQ hardware & QEC](https://github.com/claudio-dragotta/shor-nisq-qec-thesis)
**Master's thesis** · advisor Prof. Paolo Soda, co-advisor Prof. Floriano Caprio

Shor's algorithm studied under realistic noise, from physical errors to logical qubits.

- Surface code d = 3…9: threshold ≈ **0.86 %** (Z) / **0.81 %** (X)
- Approximate QFT on N = 15: holdout success **0.48 → 0.63**, **−23 %** ECR gates
- Gross code `[[144,12,12]]` vs surface-code patches with BP+OSD
- Learned + analytic hybrid decoders, honestly benchmarked against MWPM

`Qiskit` `Aer` `Stim` `PyMatching` `Python`

</td>
<td width="50%" valign="top">

### 🧪 [Shor Lab — interactive demo](https://github.com/claudio-dragotta/shor-demo)
**Live:** [shor-demo-6knp.onrender.com](https://shor-demo-6knp.onrender.com/)

Web app that runs Shor step by step for **N = 15, 21, 35** and lets you switch noise channels
on and off.

- Ideal simulator vs noise lab (depolarizing, T1/T2, readout, coherent over-rotation)
- Bloch spheres, inverse-QFT breakdown, guided tour
- TVD, Hellinger and peak-mass metrics, not just "did it factor"

`FastAPI` `Qiskit` `Docker` `Render` `JavaScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☀️ [24h-ahead PV power forecasting](https://github.com/claudio-dragotta/24-Hour-Ahead-Photovoltaic-PV-Power-Forecasting)
Hybrid **CNN-BiLSTM** forecasting photovoltaic output a day ahead on two years of real
Australian data (17.5k hourly samples).

- MASE < 1 (beats naive baseline), PV–GHI correlation 0.905
- Robust timezone / DST handling across data sources

`PyTorch` `TensorFlow` `LightGBM` `Optuna` `pvlib`

</td>
<td width="50%" valign="top">

### 🤖 [TiAGo ArUco manipulation](https://github.com/claudio-dragotta/tiago-aruco-manipulation)
Autonomous **pick-and-place** with the PAL Robotics TiAGo humanoid.

- ArUco detection + 3D pose estimation from the head camera
- 7-DOF arm via Levenberg–Marquardt inverse kinematics
- State machine: scan → detect → pick → place across 5 ROS 2 nodes

`ROS 2 Humble` `Gazebo` `OpenCV` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ [EnergyGuard](https://github.com/claudio-dragotta/Sistema_distribuito_EnergyGuard)
Distributed real-time monitoring of **100 sensors across 5 sites**.

- WebSocket telemetry with JWT auth, fault/outage/spike scenarios
- Observability stack: Prometheus, Grafana, Loki
- One-command deploy with `docker compose up`

`Flask` `React` `Redis` `Nginx` `Docker`

</td>
<td width="50%" valign="top">

### 🎬 [CogVideoX experiments](https://github.com/claudio-dragotta/CogVideoX-experiments)
Controlled **ablation study** on a 2B-parameter text-to-video diffusion transformer.

- 20 videos, one variable changed at a time, fixed seeds
- Found a non-linear quality cliff below ~20 denoising steps
- Runs on ~15 GB VRAM with CPU offload + VAE tiling

`PyTorch` `Diffusers` `Hugging Face` `CUDA`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | What it does | Stack |
|:--|:--|:--|
| [Elettric_system](https://github.com/claudio-dragotta/Elettric_system) | MPC scheduling for a PV + wind + load + price energy system, config-driven scenarios and reports | Python, optimization, YAML |
| [Diabetes readmission](https://github.com/claudio-dragotta/Analisi-dei-dati-sul-Diabete-Progetto-MOTT) | 30-day readmission prediction on 100k+ patients with age-stratified models and uncertainty flagging | scikit-learn, SMOTE, Pandas |
| [Consistency analyzer](https://github.com/claudio-dragotta/agent-consistency-analyzer) | LLM-based validator for Domain-Driven Design models in a multi-agent requirements pipeline | Python, LLM, DDD |
| [di-Pen app](https://github.com/claudio-dragotta/tesi-DPen) | BSc thesis — mobile app for smart insulin-pen management with QR traceability | Kivy, SQLite |
| [Richter's Predictor](https://github.com/DanieleLimongi/richter-predictor-fia) | Earthquake damage classification, 8-model neural ensemble, F1 0.685 (with D. Limongi) | TensorFlow, Docker |

</details>

---

## Tech stack

<div align="center">

**Languages**<br>
<img src="https://skillicons.dev/icons?i=python,cpp,java,matlab,js,html,css&theme=dark" alt="Languages"/>

**ML & data**<br>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" alt="ML"/>
&nbsp;
<img src="https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white" height="48" alt="Qiskit"/>

**Backend, infra & tools**<br>
<img src="https://skillicons.dev/icons?i=fastapi,flask,react,redis,nginx,docker,kubernetes,aws,azure,githubactions,grafana,prometheus,linux,ros,git,vscode&perline=8&theme=dark" alt="Tools"/>

</div>

---

## Education & experience

| When | What |
|:--|:--|
| **Oct 2026** | **MSc Intelligent Systems Engineering** — Università Campus Bio-Medico di Roma · *110/110 cum laude* |
| **Feb 2025** | **BSc Industrial Engineering** — Università Campus Bio-Medico di Roma |
| 03 – 09/2025 | **Tutor**, DM 66 digital-skills training courses for school staff — MR Digital (remote) |
| 05 – 07/2025 | **Google.org Cybersecurity Seminar Program** — with Campus Bio-Medico |
| 10 – 12/2024 | **CyberX-Mind4Future** — cybersecurity and emerging technologies (online) |
| 2020 | **Classical–German double diploma** — Liceo Classico Umberto I, Palermo |

---

## Activity

<div align="center">

<img alt="Contribution snake" src="https://raw.githubusercontent.com/claudio-dragotta/claudio-dragotta/output/snake.svg"/>

</div>

---

<div align="center">

### Let's talk

Looking for roles in **quantum computing**, **machine learning engineering** or **R&D** —
in Italy, Germany or elsewhere in Europe.

<a href="https://www.linkedin.com/in/claudio-dragotta-04096334b"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:claudiodragotta@gmail.com"><img src="https://img.shields.io/badge/Send%20an%20email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1e3a8a,100:0b1d3a&height=110&section=footer" width="100%"/>

</div>
