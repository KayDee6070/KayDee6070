## Kuntal Dive

M.Sc. Digital Engineering student at **Bauhaus-Universität Weimar**. I build and evaluate
LLM-based applications — retrieval pipelines, evaluation tooling, and the unglamorous
plumbing that tells you whether any of it actually works.

Currently evaluating LLMs as a contractor at Outlier: long multi-turn, side-by-side
comparisons of frontier assistants graded against rubrics, plus review of technical code.
It mostly means reading model output adversarially and looking for the thing that is subtly
wrong. That habit shapes what I build: most of my projects are about measuring a system
rather than just demoing it.

---

### What I'm working on

- **[dep-triage-agent](https://github.com/KayDee6070/dep-triage-agent)** — a tool-using LLM
  agent (LangGraph, local Qwen3-8B via Ollama) that answers Python dependency-security
  questions over a frozen PyPI/OSV snapshot, and the evaluation harness that checks whether
  tool routing actually helps: a held-out split declared up front, two deliberately simple
  baselines, fault injection and fabrication detection, deterministic grading with no LLM
  judge. Shipped as a FastAPI service in a hardened Docker image, with the evaluation report
  live on a [Hugging Face Space](https://huggingface.co/spaces/KayDee6070/dep-triage-agent).
  On development data the agent does not yet beat the baselines, and the report says so.
- **[GraphRAG Bench](https://github.com/KayDee6070/graphrag-bench)** — benchmarking graph
  vs. vector vs. hybrid vs. BM25 retrieval for multi-document questions under one shared
  evidence budget. Local LLM pipeline for knowledge-graph extraction, structured-output
  validation, and citation checks against exact source passages. Runs fully offline.
- **[EvalForge](https://github.com/KayDee6070/evalforge)** — a Streamlit app for
  rubric-based human evaluation of LLM responses: YAML-configured rubrics, score validation,
  error tagging, model-comparison analytics, SQLite storage, pytest coverage and CI.

### Selected projects

| Project | What it is |
|---|---|
| [dep-triage-agent](https://github.com/KayDee6070/dep-triage-agent) | Tool-using dependency-triage agent plus an evaluation harness with baselines, fault injection and fabrication detection · LangGraph, Ollama, FastAPI, Docker, pytest, mypy |
| [graphrag-bench](https://github.com/KayDee6070/graphrag-bench) | Research benchmark for graph vs. vector vs. hybrid vs. BM25 retrieval over a frozen 30-paper corpus, fully offline · Python, NetworkX, PyTorch |
| [EvalForge](https://github.com/KayDee6070/evalforge) | Rubric-based evaluation and analytics for LLM responses · Python, Streamlit, Pydantic, SQLite |
| [Digital-Twin](https://github.com/KayDee6070/Digital-Twin) | Digital-twin web prototype: live sensor data over MQTT, RDF metadata, interactive IFC building viewer · React/TypeScript, FastAPI, PostgreSQL |
| [GenCAD-AI](https://github.com/KayDee6070/GenCAD-AI) | Autoregressive generation of parametric CAD sketches with a hybrid Transformer, plus a Vision Transformer baseline · PyTorch, SketchGraphs |
| [turbofan-rul](https://github.com/KayDee6070/turbofan-rul) | Remaining-useful-life prediction on NASA C-MAPSS turbofan data · Random Forest, XGBoost, LSTM |
| [EnergyForecasting](https://github.com/KayDee6070/EnergyForecasting) | Daily household energy-consumption forecasting with lag and rolling features · Scikit-learn, Streamlit |

### Tools

`Python` · `TypeScript` · `SQL` · `C#` · `PyTorch` · `Hugging Face` · `LangGraph` · `Ollama` ·
`NetworkX` · `FastAPI` · `React` · `Streamlit` · `PostgreSQL` · `Docker` · `Git` · `GitHub Actions`

### Background

Before Digital Engineering I did a B.E. in Civil Engineering and led drone-survey work —
500+ hectares, 100GB+ of geospatial data processed into 10 cm-resolution maps. The GIS and
simulation repositories here are from that side of things.

---

📍 Weimar, Germany · [LinkedIn](https://www.linkedin.com/in/kuntaldive) · kuntaldive.kd@gmail.com
