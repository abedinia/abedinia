# Aydin Abedinia

**Software engineer / MLOps · PhD researcher in edge AI** — UniGe · UC3M · QMUL

I work on making large vision and language models run inside the latency, memory and
energy budgets of real hardware — vehicles, embedded devices, and production systems
that have to answer in milliseconds. Before the PhD I spent eight years building the
ML platform behind a service with 50M+ users.

[![Website](https://img.shields.io/badge/abedinia.github.io-1b7f43?style=flat-square&logo=githubpages&logoColor=white)](https://abedinia.github.io/)
[![Google Scholar](https://img.shields.io/badge/Scholar-c5102a?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=B1SRyKwAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-1b7f43?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-9739-7021)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-c5102a?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aydin-abedinia-96b2276b/)

---

### 🔬 Currently

PhD researcher at the **Elios Lab** (DITEN, University of Genoa), in the JD-ICE joint
doctorate with Universidad Carlos III de Madrid and Queen Mary University of London,
inside the EU Horizon 2020 **Hi-Drive** programme.

- Hardware-aware inference for vision–language models and vision transformers
- Quantisation trade-offs — FP32 / FP16 / INT8 — measured on metered hardware, not estimated
- Real-time driving-scenario video understanding, benchmarked H100 → Jetson Orin Nano
- On-device generative pipelines on Jetson, Raspberry Pi 5 and STM32MP2

### 🏗️ Previously

**Snapp** (2017–2025) — Iran's largest ride-hailing platform, 50M+ registered users.
Left as Senior Engineering Manager, Backend & AI Platform, having founded and led the
11-engineer team that owned it.

- Real-time online/offline feature store — **~20M inferences/day at sub-50 ms p99**
- Low-latency inference gateways as the default serving path for every new ML use case
- MLOps CI/CD for model promotion: validation gates, staged rollout, drift and skew monitoring
- Governed LLM access layer on LiteLLM + Langfuse — virtual keys, tracing, cost attribution

### 📄 Papers

| Year | Work | Venue |
|:--|:--|:--|
| 2026 | [Cross-platform deployment and characterization of an on-device generative conversational agent](https://www.sciencedirect.com/science/article/pii/S1383762126002997) | *Journal of Systems Architecture*, Elsevier |
| 2026 | An open-source FPGA framework for extremely quantized edge AI | SIE 2026, Springer · accepted |
| 2026 | When is hybrid better? Hardware-aware benchmarking of single and dual visual backbones | IEEE *JETCAS* · under review |
| 2025 | [Enhancing classification with semi-supervised deep learning using distance-based sample weights](https://arxiv.org/abs/2505.14345) | ICMLT 2025, IEEE · oral, Helsinki |
| 2024 | [Building semi-supervised decision trees with semi-CART algorithm](https://doi.org/10.1007/s13042-024-02161-z) | *IJMLC*, Springer · 34 citations |

### 📦 Code

| Repo | | What it is |
|:--|:--|:--|
| [**video-encoder-benchmark**](https://github.com/Elios-Lab/video-encoder-benchmark) | `Python` | Hardware-aware benchmark of 15 visual-backbone configurations across FP32/FP16/INT8 on H100 and Jetson Orin Nano |
| [**semideep**](https://github.com/WeightedAI/semideep) | `Python` | Distance-based sample weighting for semi-supervised deep learning — `pip install semideep` |
| [**semicart**](https://github.com/WeightedAI/semicart) | `Python` | Semi-CART: semi-supervised decision trees with distance-based weights — `pip install semicart` |
| [**cartgo**](https://github.com/abedinia/cartgo) | `Go` | CART in Go — fit, predict, save, load — for low-latency serving paths |
| [**rust_decision_tree**](https://github.com/abedinia/rust_decision_tree) | `Rust` | Decision trees from scratch, to see what tree learning costs when you own the memory layout |

Every published method ships with an implementation you can install and run.

### 🔧 Stack

```
Languages     Python · Go · Rust · SQL · Bash
ML & serving  PyTorch · ONNX · vLLM · Triton · Hugging Face · LoRA/QLoRA · quantisation
Platform      Kubernetes · Docker · Helm · Terraform · Argo CD · GitLab CI · GitHub Actions
Data          Kafka · NATS · Airflow · MLflow · Spark · ClickHouse · Redis · PostgreSQL
Observability Prometheus · Grafana · OpenTelemetry · drift & training/serving-skew monitoring
Hardware      NVIDIA H100 · Jetson AGX Orin / Orin Nano · Raspberry Pi 5 · STM32MP2
```

### 📫 Contact

📧 **abedinia@duck.com** · 🌍 Genoa, Italy (CET/CEST)
🎓 [Google Scholar](https://scholar.google.com/citations?user=B1SRyKwAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0001-9739-7021) · ✍️ [Medium](https://medium.com/@abedinia.aydin) · 🤝 [Mentoring on ADPList](https://adplist.org/mentors/aydin-abedinia-mrt06exd) (free 1:1)

<sub>Write to me about edge inference, ML platforms, or research collaboration. If it's about a system, tell me the latency budget and the hardware — that's usually where the real question is.</sub>
