<div align="center">

# Krish Gupta

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&duration=2500&pause=1200&color=58A6FF&center=true&vCenter=true&width=750&lines=Systems+Engineer+%C2%B7+ML+Researcher;Linux+Kernel+Introspection+(ptrace%2C+BPF);Extreme-Value+Modeling+%26+Statistical+Downscaling;Deep+Learning+(PyTorch%2C+YOLOv8%2C+ViT);Real-Time+Computer+Vision+%26+Knowledge+Graphs)](https://git.io/typing-svg)

<p align="center">
  <a href="https://linkedin.com/in/krish-gupta007"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="24" alt="LinkedIn" /></a>
  <a href="mailto:krishgupta3879@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" height="24" alt="Email" /></a>
  <a href="https://leetcode.com/u/KrishGupta0007/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" height="24" alt="LeetCode" /></a>
  <a href="https://github.com/KrishG7"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" height="24" alt="GitHub" /></a>
</p>

<p align="center">
  <i>Faculty of Technology, University of Delhi — Semester 5 | CGPA 8.09/10.0</i>
</p>

</div>

---

## `$ whoami`

```bash
$ krish --profile --inspect
{
  "profile": "Hardcore Systems & Machine Learning Engineer",
  "research_focus": [
    "Kernel-space introspection & container runtime isolation",
    "Extreme-value distributions & meteorological ML post-processing",
    "Deep learning & real-time computer vision (30+ FPS inference)",
    "Structural proteomics & graph-based drug discovery",
    "Polyglot AST analysis & dependency graph extraction"
  ],
  "methodology": {
    "profiling": "Flamegraphs over intuition; deterministic pipelines",
    "validation": "Statistical rigor; zero temporal lookahead leakage",
    "optimization": "Measure first; profile always",
    "stack": "C/Go (systems) | Python/PyTorch (deep learning) | TypeScript (fullstack)"
  }
}
```

**Systems engineer + ML researcher** operating at the boundaries of kernel introspection, statistical confidence modeling, and deterministic deep learning pipelines. Currently competing in **SIH 2026** (Smart India Hackathon) with two research-grade projects in meteorological AI and precision oncology.

---

## 🔬 **Active Research & Competitions**

### **[WEAVR](https://github.com/ATMOSYNC/WEAVR) — Hybrid AI-NWP Rainfall Forecast Blending** `[SIH 2026, PS 26081]`

*Ensemble weather prediction system blending GraphCast AI with numerical weather forecasts (HRES, IFS) for monsoon-critical rainfall.*

**Your Contributions:**
- **Quantile Mapping Module** (`weavr.quantile_mapping`): Implemented wet-day frequency matching + additive upper-tail rule for bias correction across 0.25° India grid
- **Extreme Value Theory (Generalized Pareto Distribution)**: Built GPD tail repair with pooled shape parameters and continuous splicing with EMOS-CSG; eliminated 193 false-zero cells
- **Critical Memory Optimization**: Fixed `xskillscore.crps_ensemble` OOM by implementing cell-blocking strategy (10.1GB → 6.5GB peak); preserved bit-identical precision
- **Data Engineering**: Built daily IFS-ENS Zarr stores (2018, 2020 monsoon seasons, 3.6GB), unblocking 12 downstream evaluation pipelines
- **Frontend Dashboard**: Extreme-probability threshold toggle with automated canvas pixel-sampling tests
- **CI/DevOps**: Created synthetic test stores (~1/1000 scale) for 7-min test cycles vs. 3-hour real-data runs

**Stack:** Python, xarray, Zarr, SciPy, EMOS/BMA, GitHub Actions  
**Impact:** SEDI improved to 115.6mm at 5/5 forecast leads under LOYO cross-validation; **H7 pre-registered test PASSED**

---

### **[Athena](https://github.com/healers-second-look/Athena) — AI Cancer Copilot** `[SIH 2026 — Ongoing]`

*Knowledge-graph-driven drug discovery system for treatment-exhausted cancer patients using structural docking and mutation proximity analysis.*

- **Knowledge Graph Tier 1**: FalkorDB property graph for clinical literature retrieval (1M+ nodes, <5s query latency)
- **Structural Docking Tier 2**: AutoDock Vina + mCSM-lig for protein-ligand binding energy prediction
- **Mutation Proximity Analysis**: Maps patient-specific mutations to drug-binding pocket residues for treatment response prediction

**Stack:** Python, FalkorDB, AutoDock Vina, mCSM-lig, FastAPI

---

## 🚀 **Flagship Projects**

| Project | Domain | Key Tech | Achievement |
|---------|--------|----------|-------------|
| **[Video-Tracer](https://github.com/KrishG7/Video-Tracer)** | Real-Time MOT | YOLOv8, ByteTrack, OpenCV | 30+ FPS tracking on edge hardware |
| **[SysCV](https://github.com/KrishG7/SysCV)** | Kernel Instrumentation | Go, ptrace, React Flow, WebSockets | Sub-ms syscall tracing + live visualization |
| **[Brahm-Kosh](https://github.com/KrishG7/Brahm-Kosh)** | Codebase Intelligence | Python AST, Three.js WebGL | 13-language AST parser + 3D force-graph |
| **[TriNetra](https://github.com/KrishG7/TriNetra-Farmers-Stack)** | Agricultural AI Stack | Sentinel-2, Gemini 1.5, PyTorch | Satellite + ML fusion for 7-day price forecast (87% accuracy) |
| **[Wait Zero](https://github.com/KrishG7/smart-clinic-booking)** | Healthcare Offline-First | Node.js, MySQL, SQLite, Flutter | Live token queues + GPS geofence check-ins |
| **[Stock Anomaly Detection](https://github.com/KrishG7/stock-anomaly-detection)** | Ensemble ML | scikit-learn, Pandas | Unsupervised equities anomaly detection (walk-forward validated) |
| **[Amazon ML Challenge 2026](https://github.com/claude-s-plan/Amazon_ML_Challenge2026)** | 72-Hour Competition | PyTorch, Pandas | Completed hackathon submission |

---

## 📚 **Technical Competencies**

### **Deep Learning & Vision**
PyTorch • CNNs (ResNet, Inception, EfficientNet, YOLOv5/v8) • RNNs (LSTM, GRU) • Vision Transformers (ViT) • GANs • Image Segmentation • Object Detection • Real-time Inference (TensorRT)

### **Machine Learning & Scientific Computing**
Pandas • NumPy • scikit-learn • Time-Series Forecasting • Word2Vec/GloVe • Generative AI (Gemini 1.5 LLM)

### **Statistical Modeling** *(from WEAVR & meteorology domain)*
EMOS • Bias-Corrected Modeling Average (BMA) • CRPS • Brier Score • SEDI • Generalized Pareto Distribution (GPD) • Quantile Mapping • xarray/Zarr • SciPy

### **Systems & Infrastructure**
Linux Systems Programming (`ptrace`, BPF, system-call tracing) • Docker • POSIX • WebSockets • Ethical Hacking & Security • Kernel Profiling

### **Languages**
**Core:** Python, C, Go  
**Application:** JavaScript, TypeScript, SQL (Oracle, MySQL, PostgreSQL)  
**Hardware:** VHDL, MATLAB

### **Backend & Databases**
Node.js • Express • FastAPI • PostgreSQL (Supabase) • MySQL • SQLite • FalkorDB (Knowledge Graphs) • GitHub Actions

### **Frontend & Visualization**
React • Vite • Next.js • Tailwind CSS • Three.js (WebGL) • Flutter • Google Earth Engine • React Flow

---

## 💻 **Academic Foundation**

**B.Tech in Computer Science & Engineering** — Faculty of Technology, University of Delhi  
Batch of 2028 (Aug 2024 – May 2028) | **Semester 5 (Oct 2026)**  
**CGPA: 8.09/10.0** (Through Semester 3; Semesters 2 & 4 results pending)

**Coursework:** Deep Learning, CNNs, Transformers, Advanced ML, Compilers, Operating Systems, Computer Networks, Database Systems

---

## 📊 **GitHub & Competitive Programming**

![GitHub Stats](https://github-readme-stats.shion.dev/api?username=KrishG7&theme=radical&hide_border=false&include_all_commits=true&count_private=true&bg_color=0d1117&text_color=c9d1d9&title_color=58a6ff)

![Streak Stats](https://streak-stats.demolab.com/?user=KrishG7&theme=radical&hide_border=false&background=0d1117)

### **LeetCode Profile**

**333 Problems Solved** (Oct 2026)  
- 142 Easy | 151 Medium | 40 Hard  
- Global Rank: ~437K  
- **Profile:** https://leetcode.com/u/KrishGupta0007/

![Top Languages](https://github-readme-stats.shion.dev/api/top-langs/?username=KrishG7&theme=radical&hide_border=false&layout=compact&bg_color=0d1117&text_color=c9d1d9&title_color=58a6ff)

---

## 🎯 **Open to**

- **Research roles** in ML, systems optimization, and climate tech
- **Full-stack infrastructure** positions (kernel → frontend)
- **Deep learning** roles focused on computer vision and real-time inference
- **Hackathon collaborations** on healthcare AI, weather prediction, and graph algorithms

---

## 🔗 **Contact**

📧 **Email:** krishgupta3879@gmail.com  
📱 **Phone:** +91 7889782682  
🔗 **LinkedIn:** https://linkedin.com/in/krish-gupta007  
🐙 **GitHub:** https://github.com/KrishG7  
🎯 **LeetCode:** https://leetcode.com/u/KrishGupta0007/

---

## 📖 **Philosophy**

> *"Premature optimization is the root of all evil — but unprofiled code is negligence."*

- **Measurement > intuition** — Flamegraphs always
- **Determinism > parallelism** — Reproducibility is non-negotiable
- **Statistical rigor** — Confidence intervals, never point estimates
- **Zero temporal lookahead** — Validation strictly separated from training

---

<p align="center">
  <i>kernel tracing • extreme-value modeling • deep learning • real-time systems • deterministic pipelines</i>
</p>
