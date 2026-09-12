# Aydin Abedinia

**Backend & MLOps engineer · PhD researcher in edge AI** — UniGe · UC3M · QMUL

I build and run the systems that carry machine-learning models into production — real-time
data and feature pipelines, low-latency inference services, and the deployment, monitoring
and promotion machinery that keeps them reliable under load. Eight years of that behind a
service with 50M+ users, and now a PhD on making large vision and language models fit the
latency, memory and energy budgets of real hardware.

[![Website](https://img.shields.io/badge/abedinia.github.io-1b7f43?style=flat-square&logo=githubpages&logoColor=white)](https://abedinia.github.io/)
[![Google Scholar](https://img.shields.io/badge/Scholar-c5102a?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=B1SRyKwAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-1b7f43?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-9739-7021)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-c5102a?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aydin-abedinia-96b2276b/)

---

### 🔬 Currently

PhD researcher at the **Elios Lab** (DITEN, University of Genoa), in the JD-ICE joint
doctorate with Universidad Carlos III de Madrid and Queen Mary University of London.


### 🏗️ Previously

**Snapp** (2017–2025) — Iran's largest ride-hailing platform, 50M+ registered users.
Left as Senior Engineering Manager, Backend & AI Platform, having founded and led the
11-engineer team that owned it.

- Real-time online/offline feature store — **~20M inferences/day at sub-50 ms p99**
- Low-latency inference gateways as the default serving path for every new ML use case
- MLOps CI/CD for model promotion: validation gates, staged rollout, drift and skew monitoring
- Governed LLM access layer on LiteLLM + Langfuse — virtual keys, tracing, cost attribution

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
ML & serving  PyTorch · ONNX · vLLM · Triton · Hugging Face · LoRA/QLoRA · quantisation, Tensorflow, Pydantic-AI, LangChain, LangGraph
Platform      Kubernetes · Docker · Helm · Terraform · Argo CD · GitLab CI · GitHub Actions
Data          Kafka · NATS · Airflow · MLflow · Spark · ClickHouse · Redis · PostgreSQL
Observability Prometheus · Grafana · OpenTelemetry · drift & training/serving-skew monitoring, LangFuse
```

### 📫 Contact

📧 **abedinia@duck.com** · 🌍 Genoa, Italy (CET/CEST)
🎓 [Google Scholar](https://scholar.google.com/citations?user=B1SRyKwAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0001-9739-7021) · ✍️ [Medium](https://medium.com/@abedinia.aydin) · 🤝 [Mentoring on ADPList](https://adplist.org/mentors/aydin-abedinia-mrt06exd)
