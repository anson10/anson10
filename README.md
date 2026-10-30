<h1 align="center">Anson Antony</h1>

<p align="center">
  <em>ML, data and real-time systems for semiconductor manufacturing</em><br>
  M.Sc. Computational Materials Science, TU Bergakademie Freiberg
</p>

<p align="center">
  <a href="https://www.ansonantony.tech">Website</a> •
  <a href="mailto:anson@ansonantony.tech">Email</a>
</p>

---

### About Me

- M.Sc. student in Computational Materials Science at TU Bergakademie Freiberg (since Oct 2025)
- B.E. Mechanical Engineering, Anna University, Chennai (2024)
- Based in Freiberg, Germany. English C1, German B1, Tamil native
- Open to Werkstudent and HiWi roles in ML, data engineering, MLOps, backend Python and simulation, in Saxony or remote across Germany

---

### Projects

Three connected projects take one problem from model to factory floor. Every result is scored against ground truth or a chance baseline.

| Project | What it does | Key results | Stack |
|---|---|---|---|
| **[FabEye](https://github.com/anson10/FabEye)** | Wafer-map failure pattern recognition on real fab data (WM-811K) | 0.858 macro-F1 on a lot-disjoint split; conformal review rule auto-accepts 96.2% of wafers at a 1.9% error rate on unseen lots | PyTorch, ONNX Runtime, FastAPI, Docker |
| **[WaferLens](https://github.com/anson10/waferLens)** | Yield-excursion detection and root cause on a simulated fab with logged ground truth | Chamber EWMA/CUSUM alarm after a median 8–9 affected wafers vs. 33 for Shewhart; SQL commonality analysis ranks the true chamber first for 72% of yield-loss excursions (chance: 0.8%) | PostgreSQL/TimescaleDB, dbt, Dagster, Kafka, Power BI |
| **[WaferEdge](https://github.com/anson10/WaferEdge)** | Real-time wafer-map watchdog at the equipment, speaking SEMI HSMS/SECS-II | Sort result to lot-hold decision in 0.3–0.5 ms median at 1,000–5,000 wafers/s; own CUDA engine runs FabEye's CNN at ~11,000–13,000 maps/s | C++23, CUDA, AVX2, Asio, CMake |

Also: **[PhaseNet](https://github.com/anson10/PhaseNet)**, phase identification from LAMMPS molecular dynamics snapshots, trained with PyTorch DDP. **[QM9-GPT](https://github.com/anson10/QM9-GPT)**, inverse molecular design on QM9.

---

### Tools I Use

```
Languages :     Python, C++23, CUDA, SQL, Bash
ML        :     PyTorch (DDP), PyTorch Geometric, scikit-learn, LightGBM, ONNX Runtime, MLflow
Data      :     PostgreSQL/TimescaleDB, dbt, Dagster, Kafka (Redpanda), FastAPI, SQLAlchemy
Systems   :     CMake, AVX2, lock-free queues, ASan/TSan, libFuzzer
DevOps/BI :     Docker Compose, GitHub Actions, Prometheus, Grafana, Power BI, Linux/HPC
Simulation:     LAMMPS, OVITO
```
