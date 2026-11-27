<!-- Animated header (capsule-render, "waving") -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=OscarrGv&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=ML%20-%20AI%20Engineer&descAlignY=58&descSize=20" alt="Header" />
</p>

<!-- Typing text (readme-typing-svg) -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=900&color=36BCF7&center=true&vCenter=true&multiline=false&repeat=true&width=720&height=45&lines=ML+%2F+AI+Engineer;Computer+Systems+Engineering+%40+TecNM+Veracruz;Fraud+detection+and+credit+risk;Explainable+models+with+LightGBM+%2B+SHAP;LangGraph+agents+and+RAG+with+pgvector;NASA+Space+Apps+2026+%E2%80%93+AGROX" alt="Typing text" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/OscarrGv"><img src="https://img.shields.io/github/followers/OscarrGv?label=Followers&style=for-the-badge&logo=github&color=24292e" alt="Followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=OscarrGv&label=Profile%20views&style=for-the-badge&color=2c5364" alt="Profile views" />
</p>

---

## About me

**Computer Systems Engineering** student at **TecNM Veracruz** and member of the **Samsung Innovation Campus** (AI track). I focus on Machine Learning applied to real-world problems, and I care about models that don't just predict well but can **explain their decisions** and reach production with tests, versioning and an API.

- Currently building **TallyGuard**, a banking copilot for fraud detection and credit scoring.
- Participated in **NASA Space Apps Challenge 2026** with **AGROX**, an open digital twin for farm plots.
- Learning: LangGraph, RAG with pgvector, MLflow and model deployment with FastAPI.
- Interested in: explainable ML, lightweight MLOps and tool-using AI agents.
- Open to: internships and junior roles in Data Science, ML and AI.

---

## Featured project

<p align="center">
  <a href="https://github.com/childishtitan90/tallyguard">
    <img src="assets/tallyguard-logo.svg" width="520" alt="TallyGuard" />
  </a>
</p>

**TallyGuard** (team capstone project, in progress) combines two models and an agent:

| Module | What it does | Tech |
|---|---|---|
| Fraud | Flags suspicious transactions and explains every alert | LightGBM, SHAP |
| Credit | Estimates probability of default and expected loss to suggest a safe amount | LightGBM, PD x LGD x amount |
| Agent | Answers analyst questions using the models as tools and looks up policies with RAG | LangGraph, pgvector |
| Platform | Serves the models, tracks experiments and validates every change | FastAPI, MLflow, pytest, GitHub Actions |

---

## NASA Space Apps Challenge 2026 – AGROX

<p align="center">
  <a href="https://github.com/Moco99/agroX"><img src="https://img.shields.io/badge/NASA%20Space%20Apps-2026-0B3D91?style=for-the-badge&logo=nasa&logoColor=white" alt="NASA Space Apps 2026" /></a>
  <a href="https://github.com/Moco99/agroX"><img src="https://img.shields.io/badge/repo-Moco99%2FagroX-24292e?style=for-the-badge&logo=github" alt="AGROX repo" /></a>
</p>

[**AGROX**](https://github.com/Moco99/agroX) is an open-source web prototype that builds a transparent (white-box) **digital twin of a farm plot** anywhere in the world from open satellite, climate and soil data, simulates water balance and crop growth day by day (FAO-56, growing degree days), compares crop rotations and shows the result on a map and in a 3D view.

My contributions (second-largest contributor, 19 merged PRs):

- Batch data collector for the challenge's open data sources and a **global point query** that pulls data for any location in ~10 s.
- Twin climate fed directly from the **NASA POWER API** (1984–today), plus live **Sentinel-2 NDVI**, soil and SPI drought index providers.
- **NASA CMIP6 climate projections** (SSP scenarios) to simulate future seasons.
- Drawn plots anywhere in the world, plot history, vegetation module, agronomic crop-rotation logic and the **3D twin** scene.

**Tools:** Python · FastAPI · Pydantic · pandas · NumPy · rasterio · pytest · React · TypeScript · Vite · Three.js / React Three Fiber · MapLibre GL · Recharts · Vitest · NASA POWER · Sentinel-2 (Microsoft Planetary Computer) · Copernicus DEM · SoilGrids · CMIP6

---

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sklearn,fastapi,postgres,docker,react,ts,threejs,githubactions,git,github,vscode&perline=12" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square" alt="LightGBM" />
  <img src="https://img.shields.io/badge/SHAP-FF0D57?style=flat-square" alt="SHAP" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## Live stats

<!-- Every number in this section is computed by GitHub; nothing is hand-written. -->

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=OscarrGv&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OscarrGv&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=OscarrGv&theme=tokyonight&hide_border=true&background=0d1117" alt="Contribution streak" />
</p>

### Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=OscarrGv&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="GitHub trophies" />
</p>

### Activity

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=OscarrGv&theme=tokyo-night&hide_border=true&bg_color=0d1117&area=true" alt="Activity graph" />
</p>

<!-- Contribution snake. Requires .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OscarrGv/OscarrGv/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/OscarrGv/OscarrGv/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/OscarrGv/OscarrGv/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</p>

---

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer" alt="Footer" />
</p>
