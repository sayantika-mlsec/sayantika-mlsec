# Hi there, I'm Sayantika 👋

# ML Engineer

**Network Threat Detection**

I build production-grade machine learning pipelines. My focus bridges classical anomaly detection, robust MLOps practices, and defensive GenAI evaluation.

### What I've built

- **[NIDS](https://github.com/sayantika-mlsec/network-intrusion-detection-system-project.git)** — Catches network intrusions in CICIDS2017 traffic. XGBoost + SHAP, tuned so it doesn't cry wolf, with Evidently AI watching for data drift.
- **[UEBA](https://github.com/sayantika-mlsec/insider-threat-detection-project.git)** — Spots the insider who's behaving *almost* normally. Isolation Forest + anomaly scoring on the CERT dataset.
- **[Threat Intel Assistant](https://github.com/sayantika-mlsec/RAG-Powered-Threat-Intelligence-Assistant.git)** — A RAG system that answers security questions by actually reading MITRE ATT&CK and CISA KEV, not guessing.

  
### Right now
 
Implementing an **agentic routing layer** for the RAG threat-intelligence assistant (MITRE ATT&CK + CISA KEV) — a Gemini structured-output router that decides which corpus to retrieve from (or whether to skip retrieval entirely) before the RAG pipeline runs. Currently running A/B evals of the routed pipeline against a blind-retrieval baseline to measure whether routing actually improves precision — and using the results to localize where the system breaks next.
 
### Stack
 
 Python · XGBoost · scikit-learn · LangChain · FastAPI · Docker · MLflow · Evidently AI
 
### Find me
 * **LinkedIn:** https://www.linkedin.com/in/sayantika1379 
 * **X:** https://x.com/sayantika1379
 
