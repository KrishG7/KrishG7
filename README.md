<h1 align="center">Hi, I'm Krish Gupta 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=58A6FF&center=true&vcenter=true&width=550&lines=Hardcore+Systems+%26+ML+Engineer;Low-Level+Systems+%C2%B7+Kernel+Tracing;Deep+Learning+%C2%B7+Scientific+Modeling;Building+Research-Grade+Pipelines" alt="Typing SVG" />
</p>

<p align="center">
  <strong>Undergraduate Systems & ML Engineer</strong> · B.Tech @ University of Delhi (Batch of '28)<br/>
  <em>Building low-overhead systems, research ML pipelines, and real-time computer vision engines.</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/krish-gupta007"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/KrishGupta0007/"><img src="https://img.shields.io/badge/LeetCode-330%2B%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="mailto:krishgupta3879@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### ⚡ About Me

- 🔬 **Dual SIH 2026 Engineer:** Core developer across two concurrent Smart India Hackathon engineering projects — hybrid weather forecast blending with extreme-value distributions ([WEAVR](https://github.com/ATMOSYNC/WEAVR)) and AI cancer second-opinion copilots ([Athena](https://github.com/healers-second-look/Athena)).
- ⚙️ **Systems & Kernel Enthusiast:** Working close to the metal — sandboxed system-call interception with `ptrace`, memory-bounded tensor processing, and deterministic offline AST parsing for 13 programming languages.
- 🧠 **Deep Learning Foundations:** Solid ground in PyTorch, Vision Transformers, CNN architectures (ResNet, EfficientNet, YOLOv8), GANs, and time-series forecasting.
- 🎯 **Algorithmic Discipline:** 330+ solved problems on [LeetCode](https://leetcode.com/u/KrishGupta0007/) with daily practice across graphs, dynamic programming, and systems algorithms.

---

### 🚀 Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/ATMOSYNC/WEAVR">🌦️ WEAVR</a></h3>
      <p align="center"><em>Smart India Hackathon 2026 · PS 26081</em></p>
      <p><strong>Hybrid AI–NWP Rainfall Forecast Blending for India</strong></p>
      <ul>
        <li>Blends GraphCast AI predictions with IFS and HRES numerical weather ensembles on a 0.25° India grid for 24–96h monsoon leads.</li>
        <li>Engineered quantile-mapping tail repair and continuous splicing with Generalized Pareto Distribution (GPD) extreme-value tails, eliminating all false-zero cells (193 &rarr; 0).</li>
        <li>Eliminated out-of-memory crashes by reducing BMA CRPS peak memory footprint from <strong>10.1GB &rarr; 6.5GB</strong> via cell-bounded blocking.</li>
        <li>Generated production daily IFS-ENS Zarr stores (3.6GB) for 2018 & 2020 monsoons.</li>
      </ul>
      <p align="center"><code>Python</code> · <code>xarray</code> · <code>Zarr</code> · <code>SciPy</code> · <code>EMOS / BMA</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/healers-second-look/Athena">🧬 Athena</a></h3>
      <p align="center"><em>Smart India Hackathon 2026</em></p>
      <p><strong>AI Cancer Second-Opinion Copilot</strong></p>
      <ul>
        <li>Engineered a 2-tier clinical copilot for treatment-exhausted cancer patients combining clinical NLP with structural biophysics.</li>
        <li><strong>Tier 1:</strong> Knowledge-graph retrieval over CIViC and PubMed using <strong>FalkorDB</strong>.</li>
        <li><strong>Tier 2:</strong> Computational protein-ligand docking via <strong>AutoDock Vina</strong> and <strong>mCSM-lig</strong> to evaluate drug-binding pocket mutation proximity.</li>
        <li>Predicts alternative drug-response pathways for patients with zero remaining standard-of-care options.</li>
      </ul>
      <p align="center"><code>Python</code> · <code>FalkorDB</code> · <code>AutoDock Vina</code> · <code>mCSM-lig</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KrishG7/SysCV">⚡ SysCV</a></h3>
      <p align="center"><em>Systems & DevTools</em></p>
      <p><strong>Linux System Call Visualizer</strong></p>
      <ul>
        <li>Intercepts and traces C program syscalls inside sandboxed Docker containers using native Linux <code>ptrace</code>.</li>
        <li>Architecture-specific (x86-64 / ARM64) register inspection in Go hydrating syscall arguments in real time.</li>
        <li>Streams kernel events via WebSockets to an interactive React Flow DAG visualization for live process execution graphing.</li>
      </ul>
      <p align="center"><code>Go</code> · <code>Linux ptrace</code> · <code>Docker</code> · <code>WebSockets</code> · <code>React Flow</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KrishG7/Video-Tracer">👁️ Video-Tracer</a></h3>
      <p align="center"><em>Computer Vision Pipeline</em></p>
      <p><strong>Real-Time Multi-Object Tracking Engine</strong></p>
      <ul>
        <li>End-to-end CV pipeline covering automated video ingestion, bounding-box dataset curation, and YOLOv8 training with GPU acceleration.</li>
        <li>Implements real-time trajectory tracing with <strong>ByteTrack</strong> and <strong>BoT-SORT</strong>.</li>
        <li>Configurable virtual ROI tripwires with sub-second anomaly logging and event dispatching.</li>
      </ul>
      <p align="center"><code>Python</code> · <code>YOLOv8</code> · <code>ByteTrack</code> · <code>BoT-SORT</code> · <code>OpenCV</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KrishG7/TriNetra-Farmers-Stack">🌾 TriNetra</a></h3>
      <p align="center"><em>GFG Hack-4-Viksit Bharat</em></p>
      <p><strong>3-Layer Agri-Intelligence Stack</strong></p>
      <ul>
        <li>PyTorch time-series model forecasting 7-day crop prices with <strong>87% accuracy</strong> benchmarked on national Agmarknet data.</li>
        <li>Integrated Google Earth Engine (Sentinel-2) for NDVI/NDWI satellite-based agricultural credit scoring.</li>
        <li>Gemini 1.5 translation layer providing localized soil advisory and agronomist insights.</li>
      </ul>
      <p align="center"><code>Next.js</code> · <code>FastAPI</code> · <code>PyTorch</code> · <code>Google Earth Engine</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/KrishG7/Brahm-Kosh">🕸️ Brahm-Kosh</a></h3>
      <p align="center"><em>Developer Tooling & AST Analysis</em></p>
      <p><strong>Codebase Intelligence Engine</strong></p>
      <ul>
        <li>Offline static-analysis engine parsing 13 programming languages into a unified AST graph model (~10,000 LOC, 58 tests).</li>
        <li>Deterministic multi-hop blast radius and circular dependency detection without external LLMs.</li>
        <li>Interactive 3D WebGL force-directed graph visualization of complex software monoliths.</li>
      </ul>
      <p align="center"><code>Python (AST)</code> · <code>WebGL</code> · <code>Three.js</code> · <code>React</code></p>
    </td>
  </tr>
</table>

<details>
  <summary><strong>🔍 More Projects & Repositories (Click to expand)</strong></summary>
  <br/>
  <ul>
    <li><a href="https://github.com/KrishG7/smart-clinic-booking"><strong>Wait Zero (Smart Clinic Booking)</strong></a> — Offline-first clinic appointment & live token queue system with SQLite&harr;MySQL two-way sync and GPS geofence check-ins. (<code>Node.js</code>, <code>Flutter</code>, <code>MySQL</code>, <code>SQLite</code>)</li>
    <li><a href="https://github.com/KrishG7/stock-anomaly-detection"><strong>Stock Market Anomaly Detection</strong></a> — Unsupervised detection pipeline for US equities using K-Means and walk-forward DBSCAN with strict temporal leak prevention. (<code>Python</code>, <code>scikit-learn</code>, <code>Pandas</code>)</li>
    <li><a href="https://github.com/KrishG7/financial-time-machine"><strong>Financial Time Machine</strong></a> — Historical financial data visualizer and scenario simulator. (<code>TypeScript</code>, <code>React</code>)</li>
    <li><a href="https://github.com/KrishG7/LeetCode-Solutions"><strong>LeetCode Solutions</strong></a> — Repository of curated algorithmic solutions and notes. (<code>Python</code>, <code>C++</code>)</li>
  </ul>
</details>

---

### 🛠️ Technical Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,go,ts,js,pytorch,tensorflow,fastapi,nodejs,docker,linux,mysql,postgres,git,githubactions,react,nextjs,tailwind,flutter&perline=10" alt="Tech Stack Icons" />
</p>

| Domain | Technologies & Frameworks |
|---|---|
| **Core Languages** | Python, C, Go, TypeScript, JavaScript, SQL (PostgreSQL, MySQL), VHDL, MATLAB |
| **Deep Learning & Vision** | PyTorch, YOLOv8, CNNs (ResNet, EfficientNet), ViT, GANs, OpenCV, scikit-learn, Pandas, NumPy |
| **Statistical & Scientific ML** | xarray, Zarr, SciPy, EMOS, BMA, Extreme Value Theory (GPD), Quantile Mapping |
| **Systems & Low-Level** | Linux (`ptrace`, System Calls), Docker, Node.js, Express, FastAPI, WebSockets |
| **Databases & DevOps** | FalkorDB (Knowledge Graph), PostgreSQL, MySQL, SQLite, Git, GitHub Actions, AWS |
| **Frontend & Visualization** | React, Next.js, Three.js / WebGL, Tailwind CSS, Flutter, Google Earth Engine |

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=KrishG7&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=KrishG7&layout=compact&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="165" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=KrishG7&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak" />
</p>

---

<p align="center">
  <em>Let's connect — reach me at <a href="mailto:krishgupta3879@gmail.com">krishgupta3879@gmail.com</a> or on <a href="https://linkedin.com/in/krish-gupta007">LinkedIn</a>.</em>
</p>